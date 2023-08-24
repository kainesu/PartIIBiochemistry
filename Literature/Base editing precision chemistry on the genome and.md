# Base editing: precision chemistry
on the genome and transcriptome
of living cells

Author: Rees, H.A. & Liu, D.R.
Note type: Source
Project: Base editing
Source type: Journal

- Combine Cas with inactivated nuclease domain with base editing enzymes to create point mutations at a particular site without making DSBs
- base pairing between the guide RNA and the target DNA strand leads to displacement of a small segment of single- stranded DNA in an ‘R loop'
- Then, DNA bases within this ssDNA bubble are modified by the deaminase enzyme.
- Catalytically disabled nuclease also generates a nick in the non- edited DNA strand, inducing cells to repair the non- edited strand using the edited strand as a template
- Easier to make transition edits than transversion edits (smaller chemical change)
- ClinVar database

# Cytosine base editors

- Converts CG to TA (C→T) by deaminating cytosine to uracil
- e.g. APOBEC1 cytidine deaminase
    - Accepts ssDNA as a substrate but not dsDNA
- Fusion of APOBEC1 to dead Cas9 (inactivated nuclease domain) to form **BE1**: When bound to cognate DNA, dCas9 denatures DNA duplexes to generate an R loop (ssDNA) — DNA strand not paired with gRNA exists as disordered single stranded bubble
    - APOBEC1 then acts on DNA in single stranded bubble
    - Since APOBEC1 only acts on ssDNA, the deamination activity is restricted to the target DNA within the bubble
    - Since APOBEC1 is fused to dCas9, it's in close proximity to the target site
- BE1 not efficient in human cells due to **DNA repair processes** that oppose target base pair conversion
    - Cells repair UG intermediate via base excision repair initiated by uracil N-glycosylase (UNG), reverting it back to CG
- UNG can be inhibited by fusing UGI to BE1 to create BE2
- However BE2 can only edit one strand of DNA: to edit the other strand, Liu et al created BE3 which also **nicks** the non-edited DNA strand
    - BE3 = APOBEC1 + Cas9-D10A nickase + UGI
    - Nicking the non-edited strand biases cellular repair of UG mismatch to create UA because cells favour repairing the nicked strand → UG converted to UA, then U repaired to T

# Adenine base editors

- GC to AT mutation is the most common pathogenic SNP — cytosine deamination is very common
- Deamination of adenosine yields inosine which is functionally equivalent to guanine
- As there were no known adenosine deaminase enzymes that could act on ssDNA, Liu et al evolved a deoxyadenosine deaminase that accepts ssDNA from a tRNA adenosine deaminase
    - This enzyme had to be further engineered

# RNA base editing

## Using ADAR

- To date, the only reported programmable oligonucleotide- directed transformation that changes Watson–Crick base pairing in RNA is deamination of A to I using ADAR adenosine deaminases
- ADARs are not natively RNA guided — they contain an RNA-binding domain that recognizes and localizes enzyme to certain regions of **dsRNA**
- ADAR can be tethered to a guiding antisense RNA oligonucleotide
    - Fuse SNAP tag to ADAR and link SNAP-ADAR to BG modified antisense RNA
    - Append RNA-binding N protein to ADAR and fuse antisense RNA
    - Fuse antisense RNA to natural substate for ADAR2 to localize ADAR2 to antisense RNA
- ADAR1 and 2 preferentially deaminate adenines mispaired with cytosine in dsRNA
    - ADAR efficiency can be increased by using an antisense RNA that places a C opposite target A
- To reduce off-target editing, Stafforst et al introduced an inducible SNAP-ADAR fusion construct into HEK293 and delivered chemically modified antisense 22-nucleotide bG-RNAs by lipofection
    - SNAP tag spontaneously binds to BG-RNA
- Modifying all nucleotides in antisense RNA with a 2' methoxy group other than C that specifies target A can minimize **proximal** off-target editing, except at adenine-rich triplet targets
- Hyperactive ADARs increase editing efficiency but increases distal off-target editing
- ADAR is sequence context dependent — GAN sites are not efficiently edited

## Using Cas13 - REPAIR

- Catalytically dead RNA-guided Cas13b can be fused to ADAR to localize it to the target RNA
- Incorporates use of hyperactive ADAR2 and specifying target adenine with AC mismatch
- Broader sequqence context compatability
- To increase specificity of REPAIRv1, Zhang et al mutated hyperactive ADAR2 to reduce binding affinity between ADAR2 non-target RNA

# Base editor limitations

- Low base editing purity in CBEs due to by-product formation
    - UNG causes by-product formation in CBE editing, so important to inhbit UNG e.g. fusing a second UGI domain to BE3
    - Using more "flexible" (?) set of linkers
    - Overexpression of UGI in trans with BE3 — but this could also cause global increase in C to T mutation rates
- ABE has high product purity — perhaps due to weaker ability of cells to remove inosine than uracil
- Base editing might create indels
    - UNG knockouts have reduced indel formation — UNG may create an abasic site following C to U deamination, which then leads to nicking of the deaminated strand of DNA by AP lyase. Now since Cas9 nickase also nicks the opposite non-edited strand, the two nicks are recognized as a DSB which is resolved by indel-prone end-joining processes.
    - Indel formation can be reduced by fusing Mu-Gam protein to BE4
- ABE has low indel frequencies — consistent with requirement of a glycosylase or other DNA repair enzyme to remove inosine and then induce nick in edited strand to form indel
    - And since removal of inosine is less efficient than removal of uracil, fewer nicks are created in deaminated strand → fewer DSBs.
- Improving fidelity of base editing (reducing off-targets)
    - As not all the Cas nuclease off- targets contain an editable cytosine, off-target profiles of CBEs are generally more favourable than that of the corresponding nucleases programmed with the same guide RNAs
    - High fidelity versions of BE3 have been generated by incorporating mutations known to improve editing fidelity of Cas9
- For gene editing, an ideal base editor has a narrow activity window which focuses activity only on the target base; but such a narrow window would need a base editor targetable at a broad range of PAM sequences
    - On the other hand, broad editing windows may facilitate access to target base pair and may be useful when targeting non protein coding sites
- Some target sites have multiple editable bases (Cs or As) within or near the activity window
    - Bystander editing = editing within the activity window at a nucleotide other than the target nucleotide
    - To reduce bystander editing, can develop base editor variants with altered activity windows, or with strong sequence context preference
- CRISPR enzymes are restricted in targets because they require a PAM in an appropriate position relative to the target base
    - To increase number of targetable bases, researchers have developed base editors that make use of different CRISPR-associated nucleases with alternative PAMs
    - PACE has been used to evolve SpCas9 to recognize more PAMs
    - Rational design has also been used to develop SpCas9 variants with broader PAM compatability
- Base editor targets may be restricted by sequence context preferences.
    - E.g. rAPOBEC1 does not process cytosines within some GC motifs well
    - But sequence context preferences can help reduce bystander editing
- Improving intracellular expression and nuclear localizati0on of base editors
    - Optimizing codon use, protein expression
        - use of ancestral sequence reconstruction starting from the protein sequences of the hundreds of known APOBEC homologues, a process that has been demonstrated to improve protein expression
    - Optimizing nuclear localization sequence (NLS)

Why do these context preferences exist? 

# Delivery of base editors

- Chemical transfection, lipid mediated transfection of plasmid, electroporation, viral infection of DNA encoding protein, then rely on target cell transcription and translation to produce desired proteins
    - Electroporation is followed by FACS to isolate transfected cells
    - Plasmid-based delivery raises risk of exogenous DNA recombination into genome, and overexpression of genome editing agents increases off-target editing rates
    - Viruses are immunogenic, but AAV thought to be non-inflammatory and non-pathogenic
        - Challenging as AAV has small packaging limit of 4.9kbp. Kim et al used two RNA splicing AAVs that each encode half of an ABE, which in-vivo can produce the full length ABE
- RNP delivery: DNA-free base editing is advantageous as it removes exposure of cell to exogenous DNA which can lead to sustained overexpression. This is bad bc it erodes DNA specificity — after editing, the target site is no longer a binding site for the editing agent, so residual editors act on off-target sites
    - Purified Cas9 complexed with guide RNA to form an RNP complex can be delivered into mammalian cells via electroporation
    - RNP delivery of Cas9 improves DNA specificity relative to plasmid delivery
    - Cationic lipid-mediated delivery of Cas9 RNP complexes can facilitate in vivo delivery of Cas9 near site of administration, which increases DNA specificity relative to plasmid delivery (**why**)
- mRNA delivery: in vitro transcription then purification of mRNA, delivered in combination with guide RNA into cells

# Applications of base editing

- Install or correct pathogenic point mutations
- Editing postmitotic cells
- Cytosine base editing to introduce premature stop codon
- Generating animal models by base editing embryos
- Record cellular signals and exposure to stimuli — couple stimulus of interest to base editor activity
    - stimulus-dependent promoters
    - ligand-dependent ribozyme
- Base editing in plants

# Reference

Rees, H. A., & Liu, D. R. (2018). Base editing: Precision chemistry on the genome and transcriptome of living cells. Nature Reviews Genetics, 19(12), 770–788. [https://doi.org/10.1038/s41576-018-0059-1](https://doi.org/10.1038/s41576-018-0059-1)