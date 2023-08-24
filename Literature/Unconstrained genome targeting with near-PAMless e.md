# Unconstrained genome targeting with near-PAMless engineered CRISPR-Cas9 variants

Author: Walton, R.T., et al
Note type: Source
Project: Base editing
Source type: Journal

Study uses **structure-guided engineering** to expand PAM requirements (Compare with [Evolved Cas9 variants with broad PAM compatibility and high DNA specificity](Evolved%20Cas9%20variants%20with%20broad%20PAM%20compatibility%2081e3a2d2e9f84eb48418e9a40e8ad8d4.md) which uses directed evolution). 

Generated an NGN PAM variant (SpG), and from SpG developed a variant that can edit nearly all PAMs (SpRY)

# Background

- SpCas9 recognizes NGG PAM via R1333 and R1335, but modifying either residue results in loss of nuclease activity against sites with NGG, NAG, or NGA PAMs
- Instead, use structure-guided engineering to alter PAM by mutating other residues in the PAM-interacting (PI) domain
- Several PAM-proximal residues are important for PAM recognition

# Methods & Results

## Structure-guided engineering to obtain SpG

- SpCas9-VRQR used as a starting point for mutagenesis
- A high-throughput PAM determination (HT-PAMDA) assay was developed to determine PAM preferencesof many SpCas9 variants
- Five PI-critical positions (D1135, S1136, G1218, E1219, and T1337) in SpCas9-VRQR were mutated in different combinations
- HT-PAMDA identified several variants that were more flexible in recognizing nucleotides at 3rd, 4th PAM position
    - The variant with D1135L/S1136W/ G1218K/E1219Q/R1335Q/ T1337R substitutions (SpG) had the most even targeting of NGA, NGC, NGG, and NGT PAMs

## Measuring nuclease activity of SpG

- wt SpCas9 and SpG editing efficiency was compared at 4 sites with NGA, NGC, NGG, and NGT PAMS in HEK293T
- SpG had high editing activity at all 4 NGN PAms
- Adding non-specific contacts by adding L1111R and A1322R mutations does not work — it reduces editing activity
- SpG was also compared to xCas9(3.7) and SpCas9NG, and outperformed both these SpCas9 variants at all NGN sites, with highest editing efficiency and most even targeting

## SpG and base editing

- C to T editing of wt SpCas9, xCas9, SpCas9-NG, and SpG BE4 cytosine base editor was compared at 22 endogenous sites in human cells
- These sites had NGNN PAMs
- SpG and SpCas9-NG CBE had higher C to T conversion than WT, xCas9 at all nGN sites
- The PAM compatabilities of the CBEs were largely the same as the nucleases (determined by a modified CBE-HT-PAMDA)
- Findings were similar for ABE fusions

## Structure-guided engineering to target NRN PAMs

- NRN = NGN or NAN
- Using SpG as a starting point
- Could substitution of R1333 to Glu also allow access to NAN PAMs?
    - To form a base-specific contact with the adenine
    - However, R1333Q nearly abolished activity in human cells against 4 sites with NRN PAMs
- L1111R and A1322R were able to rescue some activity of SpG(R1333Q), but activity was still lower overall
- SpG(L1111R/A1322R) variants each with a different residue at position 1333 were systematically evaluated for PAM
    - Varisnts with R1333A, R1333C, and R1333P were the most efficient at targeting NRN PAMs
    - The R1333P variant also had greater activity at NRN PAMs compared to R133Q
- To further improve on-target activity of SpGR1333Q, crystal structure of SpCas9 was used to identify other suitable PI domain residues to mutate to R (How were residues identified?)
    - Analagous to mutating L1111R, A1322R
    - Mutating residues to positively-charged R could increase non-specific ionic DNA interactions
    - HT-PAMDA used to determine single and combined effects of A61R, G11104K, N1317R on three SpG(L111R/A1322R) variants (R1333A, R1333C, R1333P)
        - NRN PAM preferences for all 3 variants similar
        - Different combinations of these substitutions were well-tolerated
    - These variants were all also tested on 4 endogenous NRN PAMs in human cells
        - SpG(L111R/A1322R) with R1333P and A61R + N1317R had the highest editing efficiency against NRN PAMs
            - This variant also targets some NYN PAMs (where Y = C or T)
    
    SpRY: SpG(L111R/A1322R) with R1333P and A61R + N1317R
    

## Characterising SpRY nuclease, CBE, ABE activity

**Nuclease activity**

- SpRY had higher nuclease activity at NRN PAMs except at NGG PAMs than WT
- SpRY often had comparable nuclease activity at NGN sites to SpG, but SpG was most effective NGN PAM variant
- SpRY had signficant nuclease activity at more NYN sites with than wt SpCas9 (which had 0 sites)

**Base editor activity**

- SpRY CBE had moderate editing efficiency at 14 NRN sites, while WT CBE edited NGG PAMs most efficiently, and edited NAG and NGA at lower efficiency than SpRY
- SpRY CBE could also edit 5 high activity NYN PAM identified from nuclease activity experiments. WT CBE had negligible editing at NYN.
- Similar experiments performed for ABE fusions. At NRN sites, SpRY-ABE had moderate editing efficiency, while WT CBE edited NGG PAMs most efficiently, with minor editing at three sites with noncanonical PAMs
- At the 5 high activity NYN sites, SpRY-ABE editing was more modest, but WT ABE had no editing

## Characterising off-target activity and high fidelity improvements

- Could relaxed PAM tolerances of SpG, SpRY lead to greater off-target activity? And, could it be reduced using high fidelity improvements(see [High-fidelity CRISPR–Cas9 nucleases with no detectable genome-wide off-target effects](High-fidelity%20CRISPR%E2%80%93Cas9%20nucleases%20with%20no%20detect%2070fe804ba35d4c688e98f513a8b4c8f9.md))?
- SpRY had similar on-target modification rates with WT, SpCas9-NG, SpG, and their high fidelity (HF1) variants
- GUIDE-seq used to look for off-target editing
    - GUIDE-seq DSON tag showed similar levels of on-target editing between WT, SpG, SpRY, and HF1 derivatives
    - GUIDE-seq shows that SpG and SpRY had somewhat higher off-target editing as WT SpCas9, but this rate is similar to those reporteed by other studies
        - Nearly all new off-targets were due to the expanded PAM recognition (this seems to contradict with the conclusions of [Evolved Cas9 variants with broad PAM compatibility and high DNA specificity](Evolved%20Cas9%20variants%20with%20broad%20PAM%20compatibility%2081e3a2d2e9f84eb48418e9a40e8ad8d4.md) — that relaxing PAM requirements is not a trade-off with specificity)
    - However, the HF1 variants eliminated nearly all off-target editing events and increased on-target editing events

## Using relaxed PAM Cas9 variants to edit disease-associated alleles

- Activities of WT-, SpG-, and SpRY- CBEs assessed in *SOST* W124X AND *MSTN* IVS1
    - WT CBEs had most robust editing at NGG PAMs, but for MSTN IVS1, there was potentially deleterious *bystander* editing
    - Bystander edit was avoided or reduced using SPG or SpRY-CBEs targeted to NGC and NAT PAMs
- In the same genes, assessed activities of WT-, SpG-, and SpRY- CBEs at NRN PAMs
    - WT CBEs could not efficiently make intended edit
    - SpG and SpRY CBEs could make the intended edits
- By using SpG and SpRY, we can avoid deleterious bystander edits by selecting a targetable site that produces silent or toelrable collateral edits
    - This selection is only possible because SpG and SpRY offer multiple possible targetable sites with their expanded PAM range

# Reference

Walton, R. T., Christie, K. A., Whittaker, M. N., & Kleinstiver, B. P. (2020). Unconstrained genome targeting with near-PAMless engineered CRISPR-Cas9 variants. Science, 368(6488), 290–296. [https://doi.org/10.1126/science.aba8853](https://doi.org/10.1126/science.aba8853)