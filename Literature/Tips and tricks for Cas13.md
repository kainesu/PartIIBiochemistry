# Tips and tricks for Cas13

Author: Abudayyeh O. & Gootenberg J.
Note type: Source
Project: RNA editing
Source type: Website

- Cas13s use a ~64nt guide RNA to target specific RNA
- Cas13 complexes with guide RNA by recognizing a short hairpin in the crRNA, while target specificity is encoded by a ~28-30nt region complementary to the target site
- All Cas13s also exhibit collateral activity after recognition and cleavage of a target transcript, which results in non-specific degradation of any nearby transcripts regardless of complementarity to the spacer
    - May be part of a programmed cell death pathway in bacteria
    - However, the collateral activity is **undectable in mammalian cells and plants**
- Certain orthologs of Cas13b are more stable and robust in mammalian cells (compared to Cas13a) for RNA knockdown and editing
- All known Cas13 family members contain two HEPN domains that confer RNAse activity
- RNA knockdown relies on cleavage of targeted transcripts by dual HEPN domains
    - Efficiency of knockdown differs between orthologs, subtypes of Cas13
- PFS restrictions for Cas13b have been observed in bacteria but not in mammalian cells
- Sequence-based rules for targeting with Cas13 *in vivo* can be deduced by testing more guides
- There may be target restrictions due to the secondary structure of the RNA.
    - In vitro, Cas13 cleaves near unstructured regions of target RNA
    - In vivo, predicted secondary structure is negatively correlated with knockdown in bacteria or mammalian cells as Cas13 requires a single stranded substrate, and likely lacks helicase activity for opening up dsRNA regions
- In a screen of guides against *E. coli* genes with Cas13b, spacers with secondary structure near the protospacer had reduced depletion in the screen
- In mammalian cells, transcript had greater knockdown when the spacer was targeted in regions of low secondary structure
- Different Cas13 subtypes have varied activities in different model systems

# Reference

Abudayyeh, O., & Gootenberg, J. (n.d.). Tips and Tricks for Cas13. Zhang Lab. Retrieved 11 August 2021, from [https://zlab.bio/cas13](https://zlab.bio/cas13)