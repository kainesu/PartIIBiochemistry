# Programmable C:G to G:C genome editing with CRISPR-Cas9-directed base excision repair proteins

Author: Chen et al
Note type: Source
Project: Base editing
Source type: Journal

# Summary

CGBE consists of three parts: 1) a nickase-Cas9 will pinpoint the mutant gene and focus the entire editor on that gene; 2) a deaminase (an enzyme that removes the amino group from a compound) will then target the defective C, and mark it for replacement, and 3) finally, a protein will initiate cellular mechanisms to replace that defective C with a G.

— [https://www.eurekalert.org/pub_releases/2021-03/afst-ssd031121.php](https://www.eurekalert.org/pub_releases/2021-03/afst-ssd031121.php)

## Background

- Base editors can correct SNPs, but so far only transition edits
    - Cytidine base editors
    - Adenine base editors
- CBEs and ABEs affect some C:G to G:C edits as by-products. APOBEC induces a C to U change, and this U can be converted to an abasic site which is transformed into G:C
    - Others have exploited this to achieve C:G to G:C editing through fusion of APOBEC-nCas9 (C to U) to uracil DNA glycosylase (UNG) – which induces abasic sites
        - APOBEC changes C to U, then UNG removes the base to create an abasic site
- Alternatively, can use cell base excision repair (BER) pathway for transversion edits
    - Since removal of UGI from CBE could lead to increase in C:G to G:C levels, UNG and downstream BER may mediate this C:G to G:C conversion in the presence of bound nCas9.
    - BE3 used as a control. We removed UGI, instead fusing rAPOBEC-nCas9 with DNA ligase 3, DNA repair protein XRCC1, or the DNA binding and lyase domain of DNA polymerase β (PB)
        - Why were these particular BER proteins chosen ?

## Creation of CGBE candidates and initial screen

- The relative orientation of Cas9 fusions may affect its activity, so several CGBE constructs were created with rAPOBEC, BER proteins, and Cas in different arrangements
- HEK293AAV cells were treated with each candidate, along with gRNAs designed to target *HEK2* and *HEK3*
- As controls, cells were compared to BE3 and BE4 with the same gRNAs
- To determine whether the candidates successfully converted C:G to G:C, high-throughput sequencing of HEK2 and HEK3 was performed
    - CGBE candidates edited C:G to both G:C and T:A
    - 20/31 candidates had increased level of C:G to G:C editing relative to BE3 in HEK2
        - C:G to G:C editing was highest at position 6 in the protospacer, then at position 4
    - 12/31 candidates had higher C:G to G:C levels at position 5 in HEK3

## Secondary screen

- Test C:G to G:C editing at 4 sites known to be amemable to BE3 mediated editing (EMX1, HEK4, RNF2, FANCF)

## Characterisation of CGBEs

- CGBEs had higher indel rates than BE3 which may be due to generation of an abasic site

**Does target sequence context affect editing efficiency?**

- CGBEs had higher levels of C:G to G:C editing at Cs immediately following A/T
- 16 gRNAs were designed that target 16 different *HEK2* sites, which collectively cover all possible NCN motifs with targeted Cs at position 6
    - Most edited motifs are WCW, ACC, GCT (see sequence logo)
    

**What is the editing window of CGBEs?** 

- A genomic site was chosen with alternating 5'-WCWCWC-3' sequence so that gRNAs can be designed with Cs located at every odd or even position

**Effect of removing UGI from BE3**

- Promotes C:G to G:C editing at the expense of C:G to T:A, but also increased undesired indels

**Effect of fusing rXRCC1 to rAPOBEC-nCas9**

- Significantly raised C:G to G:C editing levels compared to BE3 without UGI and decreased undesired indel rates, potentially due to equilibrium shift from abasic site to repaired base

So BE3 - UGI + rXRCC1 has less indels than BE3 - UGI alone. 

**Assessing off-target activity**

- CGBE induced off-target editing at the same 15 positions; at 2/15 positions CGBE had greater off-target editing, but lower at the remaining positions

**Efficiency of CGBEs in different cell types**

- CGBEs had low C:G to G:C editing efficiency in H9 stem cells, similar to how BE3 had low C:G to T:A editing in H9 stem cells
    - May be due to chromosomal abnormalities and different methylation profiles in stem cells — APOBEC is inefficient at deaminating methylated cytidines.
    - Further APOBEC engineering and codon optimization may be needed to enhance CGBE efficiency in stem cells
- However, CGBE was more efficient at editing in eHAP cells than BE3
- In HTB9 cells, BE3 and CGBEs have similar efficiency
    - In HTB9, ACX rPB outperforms ACX rXRCC1 → different CGBEs may be more efficient in different cells

# Methods

**Protein fusion - molecular cloning** 

- Genes are cloned into mammalian expression plasmids
- Introducing mutations via blunt end ligation?
- Hot start PCR
- DpNI → T4 polynucleotide kinase → T4 DNA ligase
- Gibson assembly

**Cell culture**

- Confluency?

Have to do replicates for statistical analysis