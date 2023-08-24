# High-fidelity CRISPR–Cas9 nucleases with no detectable genome-wide off-target effects

Author: Kleinstiver, B.P. et al
Note type: Source
Project: Base editing
Source type: Journal

# Background

- Cas9 may mutate off-target sites
- Excess energy hypothesis: SpCas9-sgRNA-target complex has more energy than is needed for optimal binding to target DNA ⇒ allows it to bind to off-targets as well
- Is it possible to increase specificity by decreasing non-specific interactions with DNA?
    - E.g. SpCas9 can interact non-specifically with the phosphate backbone of DNA via hydrogen bonding
    - (this seems pretty similar to melting temperature selection for PCR...)
- By mutating residues involved in non-specific interactions, binding to off-target sites would be destabilized to a greater extent than target sites.

# Methods & Results

## Testing spCas9 variants

- 15 different SpCas9 variants were created with different combinations of substitutions at 4 residues, then these variants were tested for their ability to bind to on-target DNA
    - EGFP disruption assay demonstrated that they had similar activity to wt SpCas9
        - Mutated spCas9 were attached to an EGFP-targeted sgRNA to create an insertion or deletion in EGFP. Knockown of EGFP is proportional to
- Variants were again tested with EGFP disruption assay but with derivatives of EGFP-targeted sgRNA with different combinations of mutations to test their specificity
    - One of the triply substituted and the quadruple substitution variant had minimal EGFP disruption → lowest off-target disruption → highest specificity
    - Quadruple mutant chosen for further analysis (renamed spCas9-HF1)

## Testing on-target activity of spCas9-HF1

- Compare on-target activity between spCas9-HF1 and wt spCas9 with multiple sites by using additional sgRNAs
    - EGFP disruption assay
    - T7 endonuclease I mismatch assay (?)
- SpCas9-HF1 showed differences in activity to wt spCas9 for some gene loci — why?

## Testing genome-wide specificity of SpCas9-HF1

- SpCas9-HF1 attached with different sgRNAs targeted at different endogenous human gene loci
- Genome-wide DSBs were identified using GUIDE-seq to look for any off-target breaks
- SpCas9-HF1 and wt had similar levels of dsODN tag integration (determined by RFLP assay) and indel formation (by T7 endonuclease I assay) ⇒ comparable on-target activities ⇒ SpCas9-HF1 not impaired by sgRNAs used (control)
- SpCas9-HF1 had completely no GUIDE-seq detectable off-target mutations for 6/7 sgRNAs used, while SpCas9 had multiple of-target sites for these sgRNAs.
- SpCas9-Hf1 also did not create any new off-target sites that were not also observed in wt SpCas9
- GUIDE-seq findings were confirmed using targeted amplicon sequencing to measure frequency of indel mutation by wt SpCas9 vs SpCas9-HF1 at on-target sites and 36/40 off-target sites
    - wt SpCas9 and SpCas9-HF1 had similar indel frequency at each on-target site ⇒ nucleases and sgRNAs were functional
    - wt SpCas9 had significantly higher indels than background rate at off-target sites at 35/36 sites, confirming GUIDE-Seq
    - SPCas9-HF1 had similar indel rates to background at 34/36 sites (i.e. significantly lower than wt SpCas9)
        - At the 2 off-target sites that seem to have significantly higher indel rates than control, mean frequency of indels was too low to determine whether it is due to sequencing or PCR errors, or if it's really due to genuine nuclease indels
- Can SpCas9-HF1 also reduce off-target mutations with sgRNAs targeted at homopolymeric/repetitive sites?
    - Such sites have high numbers of known off-target sites
    - SpCas9-HF1 attached to sgRNA targeting cytosine-rich homopolymeric sequence or sequence containing multiple TG repeats in human *VEGFA* gene
    - GUIDE-seq dsODN tag incorporation and indel mutation was similar for wt and HF1 SpCas9 ⇒ SpCas9-HF1 not impaired by these sgRNAs (control)
    - SpCas9-HF1 significantly reduced off-target sites for these sgRNAs (GUIDE-seq)
    - Again, SpCas9-Hf1 also did not create any new off-target sites that were not also observed in wt SpCas9

## Further refining specificity of SpCas9-HF1

- Combining other methods of reducing SpCas9 off-target effects with SpCas9-HF1, e.g. truncating sgRNAs, mutating D1135E
    - SpCas9-HF1 with truncated sgRNA impairs on-target activities (EGFP disruption assay)
    - SpCas9-HF1 with D1135E substitution had >70% activity of wt SpCas9 with 6/8 sgRNAs tested
- Further mutated SpCas9 HF1 by creating SpCas9-HF3 (L169A) and SpCas9-HF4 (Y450A)
    - These residues mediate non-specific hydrophobic interactions with target DNA at the PAM proximal end
        - Y450A is involved in base stacking interactions with the sgRNA
    - SpCas9-HF3 and SpCas9-HF4 retained >70% activity of wt spCas9 with 6/8 sgRNAs
- SpCas9-HF4 significantly reduced indels at FANCF site 2 (T7 endonuclease I assay) and increased on-target activity
- SpCas9-HF2 reduced indel rates at VEGFA site 3 (T7 endonuclease assay) and increase on-target activity

# Reference

Kleinstiver, B. P., Pattanayak, V., Prew, M. S., Tsai, S. Q., Nguyen, N. T., Zheng, Z., & Joung, J. K. (2016). High-fidelity CRISPR–Cas9 nucleases with no detectable genome-wide off-target effects. Nature, 529(7587), 490–495. [https://doi.org/10.1038/nature16526](https://doi.org/10.1038/nature16526)