# Evolved Cas9 variants with broad PAM compatibility and high DNA specificity

Author: Hu, J. H., et al
Note type: Source
Project: Base editing
Source type: Journal

# Methods & Results

## Directed evolution of Cas9 using PACE to expand PAM compatability

**Creating selection system**

- Bacterial one-hybrid selection
- Selection phage encodes dCas9 fused to ω subunit of bacterial RNA polymerase
- Accessory plasmid introduced that encodes sgRNA and gene III
- When dCas9-RNA Pol fusion binds to an sgRNA, it can bind to a PAM and protospacer upstream of gene III
- RNA Pol then causes gene III expression, allowing the phage to propagate
- A library of all 64 possible NNN PAM sequence at the target protospacer in the accessory plasmid was created
- Phages encoding Cas9 variants with broader PAM compatability can thus replicate in more host cells → fitness advantage  ****
- Cas9 DNA binding and gene expression was optimized to maximize gene expression activation

**Selection**

- Optimize ω-dCas9 by growing phage on host cells containing accessory plasmid with NGG PAM
    - Cas9 evolved I12N mutation
- Expanded PAM compatibility selected for by generating three accessory plasmids that each contain a different sgRNA, as well as a corresponding protospacer upstream of an NNN PAM
    - The more PAMs that can be recognized, the more phages can be replicated → fitness advantage
    - 5 Cas9 clones isolated
    - E480K, E543D, and E1219V were recurring mutations
        - E1219 is close to R1333 and R1335 which are involved in PAM recognition
- 5 isolated Cas9 clones were further evolved
    - New recurrent mutations: A262T, K294R, S409I, M694I
        - S409I and M695I are located near DNA-sgRNA interface — may be involved in DNA sequence recognition and switching of Cas9 from open to closed conformation upon binding to target DNA
- Resulting phages evolved once more on host cells containing accessory plasmids with HHH PAMs, where H is A, C or T. This selects for Cas9 variants that can act on non-NGG PAMs.
    - Two evolutionary pathways emerged: Cas9-3.0-Cas9-3.5 all contianed K294R and Q1256K, while Cas9-3.6-Cas9-3.13 all contained A262T, K294R, S409I, M694I
    - Both pathways have core mutations E480K, E543D, and E1219V
- It is possible that the evolved Cas9 (xCas9) mechanism differs from engineered Cas9 variants which have mutated DNA-contacting residues, since any residues in Cas9 could have been mutated to create xCas9

## Characterization of xCas9

- Catalytic residues of xCas9 were restored to test if it can still cleave DNA
- xCas9-3.0-xCas9-3.13 were tested in a PAM depeletion assay: xCas9 variants were transfected cells containing a library of plasmids. The plasmid has a protospacer and all possible NNN PAM sequences within an antibiotic resistance gene; if xCas9 can cleave the DNA, the bacterium loses resistance to spectinomycin.
    - xCas9-3.0-xCas9-3.3 and xCas9-3.5-xCas9-3.9 can cleave DNA at more PAMs than wt Cas9
    - xCas9-3.7 had highest PAM depletion score

## Characterise xCas9 activity and PAM compatibility in human cells

**Transcriptional activation**

- dxCas9 fused to a transcriptional activator, VPR (dxCas9-VPR)
- Plasmids transfected into HEK293T, which together encode dxCas9-VPR, a GFP reporter downstream of a target protospacer, and a corresponding sgRNA ⇒ level of transcriptional activation corresponds to level of fluorescence
- Three different target-site PAM sets were tested: NGG, reporter library with NNN PAMs, and a reporter library with NNNNN PAMs
- 2 different protospacer sequences were also tested with corresponding sgRNAs
    - Why?  To ensure the mechanism is not protospacer-specific?
- Most xCas9 outperformed wt SpCas9 all three PAM sets
- dxCas9(3.7)-VPR was also tested on 6 endogenous genomic loci in human cells
    - Check whether the broadened trnascriptional activation is limited to partially chromatinized reporter plasmids
    - dxCas9(3.7)-VPR outperformed dSpCas9-VPR at NGG PAM sites and NGN PAM sites, but not at NNG sites
    

**Genomic DNA cleavage**

- Express xCas9-3.7 and -3.6 nuclease with genomically integrated GFP gene in HEK293T
    - Loss of GFP fluorescene measured — higher nuclease activity, higher indel rate in GFP, greater loss of fluorescence
    - GFP contains several different PAM sites
    - xCas9-3.7 and -3.6 outperformed SpCas9 on NGG and non-NGG PAMs, but not NNG PAMs
- Endogenous genomic sites were also targeted in HEK293T cells
    - Indel formation measured via high-throughput sequencing
    - xCas9-3.7 had comparable activity to wt spCas9 at NGG PAMs, and outperformed it at NGT, NGA, NGC, GAA, and GAT PAMs
    - xCas9-3.6 had indel frequencies similar or slightly lower than xCas9-3.7 at all sites tested
- Genomic cleavage had greater variability in efficiency with different PAMs and protospacers ⇒ DNA cleavage may have more extensive reuqirements than DNA binding, or it may be due to differences in chromatinization of genome vs plasmid

**Base editing**

- Replace wt SpCas9 with xCas9-3.7 in BE3 architecture
- Plasmids containing xCas9(3.7)-BE3, xCas9(3.6)-BE3, and spCas9-BE3 were separately transfected into mammalian cells
- Editing efficiency at 20 endogenous genomic sites was tested
- xCas9(3.7)-BE3 outperformed SpCas9-BE3 at NGG PAM, NG, GAA, GAT, NGT, NGA, NGC PAMs
- xCas9(3.6)-BE3 had comparable or slightly worse editing effficiency than xCas9(3.7)-BE3
- xCas9-3.7 also tested in BE4.
    - Fewer indels generated, with higher product purity, but editing efficiency lower
- xCas9(3.7)-ABE was also tested at 7 endogenous genomic sites that contain an A in the ABE targeting window
    - At all sites, xCas9(3.7)-ABE had higher editing efficiency than SpCas9-ABE (NGG, GAT, NGC, NGA)
    - xCas9(3.6)-ABE had comparable or slightly worse editing effficiency than xCas9(3.7)-BE3

## Characterising off-target activity of xCas9

- GUIDE-seq analysis performed on xCas9-3.7, xCas9-3.7, and SpCas9 in HEK293T and U2OS cells
- For all NGG PAM sites in both cell lines, xCas9-3.7 and -3.6 actually had much lower off-target activity than SpCas9
- GUIDE-seq results verified by HTS
- At GAA and CGT PAMs, xCas9-3.7 and xCas-3.6 had higher on-target activity than SpCas9
    - Neither site had off-target activity for xCas9-3.7

Wt SpCas9 may have such higher off-target activity as there was no selection pressure to — the bacterial genome is much smaller than the human genome, so less likely for off-target activity to occur even though SpCas9 is not highly specific 

# Reference

Hu, J. H., Miller, S. M., Geurts, M. H., Tang, W., Chen, L., Sun, N., Zeina, C. M., Gao, X., Rees, H. A., Lin, Z., & Liu, D. R. (2018). Evolved Cas9 variants with broad PAM compatibility and high DNA specificity. Nature, 556(7699), 57–63. [https://doi.org/10.1038/nature26155](https://doi.org/10.1038/nature26155)