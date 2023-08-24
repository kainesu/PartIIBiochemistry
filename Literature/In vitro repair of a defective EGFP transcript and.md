# In vitro repair of a defective EGFP transcript and translation into a functional protein

Author: Balke, D., Becker, A., & Müller, S.
Note type: Source
Project: RNA editing
Source type: Journal

Using twin ribozymes for RNA repair. The twin ribozymes exchange a short segment of RNA with an artificial donor RNA strand

# Background

- Twin ribozymes are created through duplication of a hairpin ribozyme
- Twin ribzoymes can excise a short segment from an RNA strand, then ligate a separate RNA strand into the gap
    - In this process, there are 2 cleavage events and 2 ligation events
    - Binding of the introduced RNA competes with reassociation of excised fragment → equilibrium must be shifted
        - To do this, the twin ribozyme could create a destabilizing structure in the region of the sequence to cut out (e.g. by creating mismatches). This would promote dissocation of the original sequence. In contrast, the external RNA can form a more stable duplex
            - Mismatch bubbles
            

Why use **twin** ribozymes in the first place? Why not just a single ribozyme. Can the same result be achieved with just one  ribozyme unit? 

# Methods & Results

## Substrate design

- A deletion was made in *EGFP* mRNA to act as the substrate for the twin ribozyme
    - Mutation site is flanked by two cleavage/ligation sites for the twin ribozyme
    - Previous studies have shown that suitable cleavage/ligation sites have a particular consensus sequence
        - However, the substrate may deviate from the consensus sequence somewhat and still be cleaved/ligated efficiently. The exception is G+1 → This must be conserved
- The length of the fragment to be cut out should be 12-18nt for sufficient dissociation
    - If length is too long, dissociation is slower
- EGFP mRNA was screened for suitable cleavage/ligation sites that meet these sequence and length requirements.
- A substrate was created by deleting 4 bases in the *EGFP* RNA, while the external RNA has 4 additional base pairs
    - Since external RNA is longer, it can form more hydrogen bonds → stronger association
- It is important that the twin ribozyme-product complex is more stable than the ribozyme-substrate complex to shift equilibrium towards product formation

## Choosing twin ribozyme units based on cleavage and ligation analysis

- Cleavage activity analyzed using 20 mer cleavage substrates CS-A (for N7 ribozymes) and CS-A'  (for U6 ribozyme)
- Substrates fluorescently-labelled with ATTO680 for analysis with PAGE on LICOR DNA sequencer
- CS-A cleaved by all 4 N7 ribozymes
    - HP-EGFP-C7 had highest cleavage rate and product yield
- U6 ribozyme had cleavage rate higher than all N7 ribozymes with similar product yield
- Ligation reaction was analyzed by using the labelled 3'-cleavage products as 3' ligation subtrates
    - Ligation activity observed for all 4 N7 hairpin ribozymes
    - Ligate rate constants were higher than cleavage rate constants
    - HP-EGFP-C7 had best ligation result and highest product yield
    - HP-EGFP-U6 also had good ligation activity and product yield
- C7 and U6 chosen as 5' and 3' unit for ribozyme respectively (why this order)

## Twin ribozyme repair reaction principle

- When the twin ribozyme binds to EGFP mRNA, a 4 nt bulge forms because 4 bases are deleted from EGFP
- The bulge promotes dissociation of a 15mer cleavage fragment
- On the other hand, the 19mer repair oligonucleotide preferentially anneals. It has 4 additional nts complemenetary to the bulged sequence of the twin ribozyme, so it forms a. more stable and continuous duplex
- If mRNA repair is successful, EGFP mRNA can be translated, resulting in functional EGFP that is fluorescent

## Testing twin ribozyme repair reaction

- Repair reaction was first tested with a shorter model substrate instead of the entire EGFP mRNA
    - Longer substrates more likely to form secondary structures that could affect reaction
- Is a two-base deletion or 4-base deletion more efficient for repair reaction?
    - Although 4 base deletion promotes dissociation of cleavage fragment, it would make it more difficult for the twin ribozyme to bind to the subtrate in the first place to catalyze the reaction
    - In tests, the twin ribozymes repaired both substrates with similar product yield
- Testing with the full EGFP mRNA: reaction was carried out and analyzed by denaturing PAGE on LICOR DNA sequencer
    - Since there are two cleavage/ligation sites, 5'-single ligation products and 3'-single ligation products are also expected in addition to the full-length repair product
    - Product yield of up to 32% obtained
    - The repaired mRNA could also be translated into functional protein — some fluorescence was observed
        - Lower fluorescence as not all mRNA was repaired (?)

# Reference

Balke, D., Becker, A., & Müller, S. (2016). In vitro repair of a defective EGFP transcript and translation into a functional protein. Organic & Biomolecular Chemistry, 14(28), 6729–6737. [https://doi.org/10.1039/C6OB01043A](https://doi.org/10.1039/C6OB01043A)