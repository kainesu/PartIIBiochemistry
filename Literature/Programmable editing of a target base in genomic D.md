# Programmable editing of a target base in genomic DNA without double-stranded DNA cleavage

Author: Komor, A.C., et al
Note type: Source
Project: Base editing
Source type: Journal

Creates a base editor to convert C to T. 

# Background

- Engineered fusions of CRISPR/dCas9 and cytidine deaminase to mediate direct conversion of cytidine to uridine, effecting a C→T substitution
- Current strategies to correct point mutations using HDR under therapeutically relevant conditions remain inefficient (typically ~0.1 to 5%) especially in unmodified, non-dividing cells.
- Instead, direct conversion of one base to another at a programmable target locus without using DSBs could increase the efficiency of editing (compared to HDR) without introducing too many random indels
- Cytidine deaminases that act on DNA require ssDNA; fortunately when dCas9 binds to DNA, at least 9 nucleotides of the displaced DNA strand become unpaired to form an R loop complex

# Results

- 4 cytidine deaminase enzymes were tested for ssDNA deamination; rat APOBEC1 (rAPOBEC1) showed highest deaminase activity
    - why these 4 chosen.
- Fusing rAPOBEC1 to N terminus of dCas9 preserves deaminase activity but not when fused to C terminus
- 4 rAPOBEC1-dCas9 fusions with linkers of different lengths, compositions were tested for sgRNA-programmed dsDNA deamination in vitro
    - Efficient, sequence-specific, sgRNA-dependent C to U conversion was observed in vitro
    - Efficiency was greatest for linkers > 9 amino acids in length
    - Activity window increases from 3 to 6 nt as linker length increases from 3 to 21 AAs
    - 16 AA XTEN linker had a good balance between efficiency and width of activity window
- rAPOBEC-XTEN-dCas9 = BE1
- BE1 was tested for ability to correct seven T→C mutations in vitro and was able to corrrect 6, with average editing efficiency of 44%
- BE1 was tested for sequence context-dependence by assaying its ability to edit a dsDNA 60-mer with a fixed C at position 7 in the protospacer, and all 36 single mutant variants where bases 1-6 and 8-13 were individually varied to each of the other three bases  (12 x 3 = 36)
    - High throughput DNA sequencing showed that conversion efficiency was 50-80%
    - Editing efficiency was independent of sequence context unless base immediately 5' of target C was a G, which lowers efficiency
    - Why base 1-13. I thought the activity window is only 5 nt long
- BE1 activity was assayed for activity in vitro on all 4 NC motifs at positions 1 to 8 within protospacer; activity followed order TC > CC > AC > GC. Maximum editing efficiency achieved when target C is at or near position 7
    - base editor is processive: it converts most or all Cs to Us on same DNA strand within activity window
- In vivo, cellular DNA repair response to U:G pair decreases editing efficiency: Uracil DNA glycolase catalyzes removal of U from DNA and initiates base excision repair, reverting U:G to C:G
    - To inhibit UDG activity, Uracil DNA glycolase inhibitor (UGI) was fused to C terminus of BE1 to create BE2, which increased editing efficiency
- Both BE1 and BE2 resulted in indel formation rates < 0.1%
- Editing efficiency can be further increased by nicking the unedited strand, which induces mismatch repair to remove and resynthesize the strand, or induce long patch BER, which would preferentially resolve U:G mismatch into U:A and T:A products
    - dCas9 was replaced by dCas9 nickase to create BE3
    - Small frequency of indels observed (average 1.1%)
- Editing permanent confirmed by monitoring editing efficiency over multiple cell divisions in cell lines
- To examine off-target activity, top 34 known Cas9 off-target sites and top 12 known dCas9 sites were sequenced (rAPOBEC1 sequence preference is independent of bases more than one nucleotide from target C)
    - Off-target base editing was detectable for a subset of known Cas9 off-target sites, but not for dCas9
    - All detected off-targets contained a C within the activity window
    - No increase in C→T conversions outside protospacer in 3200 cytosines around six on-target and 44 off-target sites compared to untreated cells
- BE3 showed potential to correct disease-relevant mutation in mammalian cells
    - *APOE4* was converted to *APOE3r* in mouse astrocytes with relatively high efficiency
    - p53 mutation Tyr163Cys was corrected in 3.3-7.6% of nucleofected human breast cancer cell line
- As the product of base editing is no longer a substrate, the reaction is not reversible

# Notes

- We can start with an poor base editor but improve it over several iterations
- We need to understand the causes of low editing efficiency
- Important to test for off-targets, in different cell lines
- Consider what molecules in-vivo could interact with your system

# Reference

Komor, A. C., Kim, Y. B., Packer, M. S., Zuris, J. A., & Liu, D. R. (2016). Programmable editing of a target base in genomic DNA without double-stranded DNA cleavage. Nature, 533(7603), 420–424. [https://doi.org/10.1038/nature17946](https://doi.org/10.1038/nature17946)