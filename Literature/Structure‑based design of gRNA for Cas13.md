# Structure‑based design of gRNA for Cas13

Author: Bandaru, S. et al
Note type: Source
Project: RNA editing
Reference: Bandaru, S., Tsuji, M. H., Shimizu, Y., Usami, K., Lee, S., Takei, N. K., Yoshitome, K., Nishimura, Y., Otsuki, T., & Ito, T. (2020). Structure-based design of gRNA for Cas13. Scientific Reports, 10(1), 11610. https://doi.org/10.1038/s41598-020-68459-4
Source type: Journal

- Cas13 activity depends on RNA local secondary structure, with cleavage preferred at single-stranded regions
    - Cas13 does not induce local melting required for strand separation → prevents crRNA from binding to DS regions
    - Expression of XIST was reduced significantly when ss regions of transcript were targeted compared to ds regions
    - Extensive cleavage of ss region of XIST transcript was found
- A central seed region is required
    - Complementation of all 8 bases in the central seed region in gRNA to ss region is sufficient to induce knockdown regardless of the terminal nucleotides in gRNA that complement DS regions
    - Central seed regions have solvent-exposed sugar-phosphate backbones that facilitate base pairing with target RNA while being close to HEPN domain
- RNA secondary structures can be visualized using structure-seq information in RNAstructure suite
- Pseudoknots do not influence Cas13 mediated cleavage
- PFS dependency rules for Cas13 nucleases are less strict (than Cas9) and vary across orthologs
- In lieu of structure-seq information, computational structure prediction may be employed (e.g. ViennaRNA package, RNAstructure, Mfold), but is not a perfect substitute