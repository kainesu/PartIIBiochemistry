# Questions
- Discuss the discoveries in cancer biology that have been brought about by massively parallel DNA sequencing.

# Using massive parallel sequencing to identify acquired mutations in cancer
- Germline mutations = mutations you inherit 
- Somatic mutations = mutations acquired during life 
- Cancer cells can be sequenced to identify these acquired mutations

## Massive parallel sequencing 
- Next generation sequencing method increases speed and scale of sequencing massively over Sanger sequencing, allowing for WGS 
	- Illumina can now sequence 1 genome for $200 
- Genome is fragmented, DNA fragments are fixed onto a chip, and every molecule is read out in parallel 

## Paired-end high-coverage NGS experiment 
![[Pasted image 20230405134506.png]]

1. Take DNA samples from blood and from tumour
	1. DNA from blood is a proxy of the germline sequence (point of conception) -> differentiate germline and acquired mutations 
2. Prepare sequencing library 
	1. Fragment genome 
	2. Size selection for fragments (e.g. filter 500bp fragments)
	3. Ligate adapter
	4. Immobilise on chip 
3. Sequencing 
	1. Sequence from both ends (paired ends) -> allows for assembly 
4. Assemble reads into genome by aligning them to a reference genome 
	1. Coverage = number of sequencing reads that are uniquely mapped to a reference and “cover” a known part of the genome
	2. Higher coverage = each base is covered by a greater number of aligned sequence reads, so base calls can be made with a higher degree of confidence (i.e. more accurate)
5. Call all variants from the reference genome in both tumour and blood (germline) genome 
	1. Germline has variants due to natural variation in human genomes – **important to know germline variation as well as germline mutations can contribute to cancer 
		1. Germline sequencing also allows us to see if other family members could have the same mutation (cascade sequencing, genetic counselling) 
6. Identify the somatic mutations by subtracting the germline variants from total variants in tumour
![[Pasted image 20230405135006.png|575]]

## Identifying driver mutations 
- Of the acquired mutations, driver mutations are causative mutations that drive occurrence of cancer and confer growth advantage. They are positively selected for 
- Passenger mutations are mutations that do not directly drive cancer initiation or progression, but were acquired as a result of mutational processes in the cancer cell. They are not selected for and do not confer growth advantage 
- Driver mutations are important to identify so that they can be treated with particular drugs e.g. BRAF(V600E) can be treated with vemurafenib
- Different patients have different driver mutations -> personalised cancer treatments needed 

## Advantages of whole genome sequencing 
- SCALE! The genome is 3 billion base pairs, while the exome only makes up 1.5-2% of the genome. With more base pairs, we get more statistical power. 
- We can see structural variants as well; targeted sequencing only gets you point mutations 
- Can see mutations in non-coding regions 

# Mutational signatures 
- Collection of passenger mutations that are a result of different mutagenic processes in cells
- Each mutational process leaves a characteristic imprint ("signature") on the genome in the form of passenger mutations 
- Composite of all these mutational processes creates a pattern that looks seemingly random
- Experimental work has to be done to identify the mutational processes that causes each signature 
	- e.g. growing cells under different conditions
	- e.g. CRISPR KOs 
![[Pasted image 20230405142456.png|325]]

## Analysing mutational signatures 
- **Signature** = result of each mutational processes
	- **Extraction** = estimating number of signatures and what they look like.
- **Exposure** = "amount" of signature. Reflects strength and duration of the mutational process
	- **Assignment** = estimate how much of each signature is present in each sample 
- The total number of mutations observed in the genome is the **catalogue**
- **Catalogue** = **signatures** * **exposure**
- We can obtain the catalog by sequencing many cancer samples, then counting the number of mutations of each type. There are 96 classes of possible mutations – 6 mutations (C->A, C->G, C->T, T->A, T->C, T->G), and each of these mutations have 16 possible pairs of flanking mutations 
  ![[Pasted image 20230405145809.png|425]]
- Represent the catalog as a big matrix (row = mutation type, column = sample, each value represents the number of that mutation type in the sample) 
- Then obtain the signatures and exposures via non-negative matrix decomposition of the catalog matrix. 
- For structural variants, there isn't really a naturally constrained set of mutation types as there are for single base substitutions, but the COSMIC database presents mutational signatures using "83 different types (of mutations) considering size, nucleotides affected and presence of repetitive and/or microhomology regions" 
- Epigenetic features could be included in theory, but additional features has diminishing returns 

> [!NOTE]- Using NMF to extract mutational signatures (ChatGPT explanation)
> 
> Non-negative matrix factorization (NMF) is a mathematical technique used to break down or decompose a large non-negative matrix into two smaller non-negative matrices, which can help reveal hidden patterns or features in the original data.
> 
> In simple terms, imagine you have a large grid of numbers (matrix), where all the numbers are zero or positive (non-negative). NMF aims to find two smaller grids (matrices) with non-negative numbers that, when multiplied together, will come close to recreating the original large grid.
> 
> The smaller matrices thus represent fundamental features or underlying patterns that contribute to the data represented in the original matrix.  
> 
> In the context of cancer genomics, a mutation can be represented as a change from one nucleotide to another (e.g., A->C, C->T, etc.). To study these mutations and their patterns, researchers often consider the neighboring nucleotides (one on each side) of the mutated base, resulting in 96 possible mutation types (6 types of mutations x 4 possible upstream neighbors x 4 possible downstream neighbors).
> 
> Now, let's assume we have mutation data for 10 cancer samples, each with a different number of total mutations. The data can be organized in a matrix, where rows represent the 96 possible mutation types and columns represent the individual cancer samples. The matrix entries would be the count of each mutation type observed in each sample. For simplicity, let's assume we have a smaller 6x10 matrix, where rows represent 6 hypothetical mutation types (A->C, A->G, A->T, C->A, C->G, and C->T) and columns represent 10 cancer samples:
> 
> ![[Pasted image 20230405144430.png]]
> 
> To identify the underlying mutational signatures, we apply NMF to decompose the original matrix into two smaller matrices, one representing the signatures (latent features) and the other representing the contribution (weights) of each signature to the samples.
> 
> Suppose we believe there are two mutational signatures (S1 and S2) responsible for the observed mutation patterns. We would decompose the original matrix into a 6x2 matrix (mutation types x signatures) and a 2x10 matrix (signatures x samples):
> 
> Mutation types x signatures matrix:
> 
> ![[Pasted image 20230405144516.png]]
> 
> Signatures x samples matrix:
> 
> ![[Pasted image 20230405144601.png]]
> 
> Now, the first matrix represents the mutational signatures, with each row showing the distribution of the 6 hypothetical mutation types (A->C, A->G, etc.) in each signature (S1 and S2). The second matrix shows how much each signature contributes to each cancer sample.
> 
> In this simplified example, the NMF application allows us to identify two mutational signatures that represent the fundamental patterns of mutations across the samples.
> 
> > [!WARNING]- There are many ways to decompose a matrix. How can we check that the matrices reflect biologically meaningful signatures?
> > 
> > 1. **Select the number of signatures (k):** The choice of k, the number of mutational signatures, is crucial for obtaining a meaningful decomposition. Too few signatures might result in overly broad patterns, while too many signatures may lead to overfitting or splitting of true signatures into multiple components. To determine the optimal k, researchers often analyze the stability and reproducibility of the signatures, as well as the interpretability of the results. They may also use techniques like cross-validation or look for an "elbow point" in the reconstruction error plot (the point where adding more signatures results in diminishing improvements to the approximation).
> > 2. **Ensure stability and reproducibility**: Researchers assess the stability of the identified signatures by repeating the NMF process multiple times with different initializations or by using subsets of the data. Stable signatures will consistently appear across different runs and data subsets. Additionally, researchers compare their results to known biological mechanisms or previously identified signatures to ensure that the signatures discovered are meaningful and reproducible.
> > 3. **Biological interpretation:** After obtaining the signatures, researchers interpret them by comparing the patterns to known mutagenic processes or by searching for correlations with other molecular or clinical features. For instance, a signature with a high proportion of C->T mutations at specific sequence contexts might be linked to exposure to ultraviolet (UV) light. If the identified signatures align with known biological mechanisms, it increases confidence that the decomposition reflects true mutational processes. 
> > 4. **Evaluate performance**: Researchers may also evaluate the performance of the NMF decomposition by comparing it to other matrix factorization methods or by assessing the quality of the reconstruction of the original matrix. A good decomposition will have a low reconstruction error and will perform better than alternative methods.
> 

## Causes of mutational signatures 
Different mutagens create very different mutational signatures!

**Methyl-cytosine deamination**
C>T where C is upstream of a G (Methyl CpG islands)
![[Pasted image 20230405150132.png]]
**APOBEC deamination**
APOBECs deaminate at specific sites 
![[Pasted image 20230405150152.png]]
**UV light**
![[Pasted image 20230405151310.png]]
**Tobacco smoke**
![[Pasted image 20230405151318.png|525]]
**Aristolochic acid**
![[Pasted image 20230405151326.png|525]]

## Distribution of mutational signatures across tumour types
![[Pasted image 20230405151357.png|625]]
Each bar represents a cancer sample. 

# Cancer evolution and phylogeny
- Subclonal heterogeneity can be used to trace back the evolutionary history of a cancer 
- Most mutations are found in just a fraction of tumour cells
- However, every tumour has a dominant subclonal lineage 

## Using mutations to infer clonal heterogeneity
- Clustering of mutations suggests subclonal populations with distinct mutation patterns 
- These mutations can be substitutions or copy number variations 

## Phylogenetic trees 
- Mutations can be assembled into phylogenetic trees to show the evolutionary history of a cancer
- Have to assume mutation rate is uniform over time, which is not necessarily always the case e.g. chromothripsis 
![[Pasted image 20230405152105.png]]
- Sequencing data for a patient might be taken from a single sample, multiple samples taken at the same time, or multiple samples taken at different time in the patient's life 
- Mutations suggest a model for breast cancer development over molecular time: 
  ![[Pasted image 20230405154342.png|300]]

# Clinical applications of genomic data
- **Mutational signatures can be used to infer cancer drivers** (germline mutations, acquired mutations, external mutagens) that can then be used to provide targeted treatments to patients 
- Mutational signatures can also identify the **primary site of the cancer** as different tumour types have different distributions of mutational signatures. This can also change the type of treatment given to the patient. 
- **Machine learning algorithms** trained on the genomic data can be used to identify these cancer drivers from mutational signatures 
	- #experimental_evidence Davies et al (2017)– HRDetect algorithm 
- **Prognosis**. HRDetect could distinguish survival chance of different patients, even for patients where cause of passenger mutation could not be found. 
- **Prediction of drug sensitivity**. Patients with high HR detect scores have a low CDR15 ratio, which represents the amount of tumour still in the blood. If the tumour is sensitive to a drug, the level of CDR15 will drop. This could be used to predict sensitivity to a PARP inhibitor 
- To apply genomic algorithms in the clinic, **retrospective** and **prospective** **clinical studies** are needed to **validate** if the algorithm can prognosticate accurately

