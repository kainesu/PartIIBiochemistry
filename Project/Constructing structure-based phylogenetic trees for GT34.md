# Method 
1.  Prepare input sequences: Obtain the amino acid sequences of the 50 enzymes in FASTA format and save them in a single multi-FASTA file.
2. Retrieve predicted structures from AlphaFold DB  – see `afdb_search.py`, which does NCBI BLAST of the sequence, takes the top hit, retrieves uniprot ID, searches for it in the AlphaFold database, and downloads the pdb file for the predicted structure onto the computer. 
4.  Predict structures using ColabFold for those not in AlphaFold DB: 
	1. Access the AlphaFold2_batch (https://colab.research.google.com/github/sokrypton/ColabFold/blob/main/batch/AlphaFold2_batch.ipynb) and follow the instructions to set up your session. 
	2. Upload sequences to a folder in Google drive (each sequence must be in its own .fasta file)
	3. Enter the path name to the folder into the notebook, as well as the path name to a folder for the output. 
	4. Runtime -> Run all (will take ~15min / protein structure)
	5. Download the resulting PDB files to your local machine and move them to a directory. 
5.  Filter low-confidence terminal regions using a local Python script: 
	1. Write a Python script that uses the BioPython library to read AlphaFold's PDB files and the corresponding pLDDT confidence scores. 
	2. Filter the low-confidence terminal regions based on the threshold and save the filtered structures as new PDB files.
6.  Calculate pairwise TM-scores and build the distance matrix: 
	5. Install TM-align on your MacBook Pro ([https://zhanggroup.org/TM-align/](https://zhanggroup.org/TM-align/)). 
	6. Write a script to calculate pairwise TM-scores for all possible pairs of filtered PDB files using TM-align and create the distance matrix using the formula: distance = 1 - TM-score.
	7. Save the distance matrix in a suitable format, such as PHYLIP or NEXUS.
7. For steps (4) and (5), this can be done by doing the following in terminal:
```terminal
cd working_directory
python process_pdbs_and_calculate_distance_matrix.py
```
Make sure that all the PDB files and pLDDT files are is in the working_directory. 

7.  Build the phylogenetic tree using the FastME software ([http://www.atgc-montpellier.fr/fastme/](http://www.atgc-montpellier.fr/fastme/)): 
	1. Install FastME on your MacBook Pro. 
	2. Load the distance matrix and run the FastME algorithm with options for the desired tree construction method, such as neighbor joining or balanced minimum evolution. 
	3. Save the resulting tree in a standard format, such as Newick or Nexus.
8.  Visualize and analyze the tree: 
	1. Use a tree visualization software, such as FigTree ([http://tree.bio.ed.ac.uk/software/figtree/](http://tree.bio.ed.ac.uk/software/figtree/)) or iTOL ([https://itol.embl.de/](https://itol.embl.de/)), to visualize and analyze the phylogenetic tree.

This modified workflow offloads the most computationally intensive step, the AlphaFold structure prediction, to Google Colab, reducing the workload on your MacBook Pro. The rest of the steps should be manageable on a modern MacBook Pro, but the processing time may vary depending on your specific hardware configuration.

# Resources
- [[KempenEtAl_2022]]
- https://search.foldseek.com/search
- [[GligorijevicEtAl_2021]]
- [[MalikEtAl_2020]] (method inspiration)
- ChatGPT 