**How can Mass Spectrometry-based approaches be used to investigate changes in a cellular response that involve stable protein modifications and protein-protein interactions? Briefly outline complementary methods which could be used to verify the initial findings**. 

- Brief explanation of how MS works

# PTMs 
## Techniques 
- What PTMs are there?
	- MS – mass shift can be used to identify PTM
	- Need to enrich sample -> fractionation 
- Otherwise difficult to detect proteins of very low abundance vs. very high abundance proteins
	- Pre-enrichment
		- Can use TiO2 columns to enrich for phosphorylated proteins
		- Antibodies for other PTMs? 
- Complementary methods

- Bottom/top-down proteomics

## Complementary methods 
- NMR/other structural 
- Antibody-based techniques
- Finding the protein responsible for the PTM
- In vitro reconstitution - if you add responsible protein and see if PTM is also added
- In vivo knockout – is high throughput if CRISPR/lentivirus screening is used with a kinase library. 
- Site-directed mutagenesis

## Limitations
- Phosphorylation will ablate the positive charge of the ions. Therefore difficult to work with
- Protein-inference problem
- Rare PTMs could be missed by MS 

# Protein-protein interactions 
- What proteins interact
- XL-MS – limited by cross-linker length (e.g. formaldehyde is ~2Å)
- HDX
- AP-MS 
	- #experimental_evidence Mousson et al (2008) used for identification of TBP binding partners 
- BioID/APEX/SPPLAT – 10 nm range
	- #experimental_evidence Roux et al (2012) used BioID to identify protein interacting partners of lamin A, including a novel nuclear envelope-associated protein SLAP75
	- #experimental_evidence Chu et al (2017) used APEX to identify microprotein-protein interactions
		- APEX tagging to an uncharacterized microprotein called C11orf98 revealed that this microprotein interacts with nucleolar proteins nucleophosmin and nucleolin
- (Hyper)LOPIT for identifying candidates – doesn't specifically identify interactions, just what compartments the protein is in 

## Complementary methods 
- NMR 
	- Titration 
- FRET 
- BRET
- Y2H Yeast-two-hybrid
- SPR
- IP
- Bioinformatics – look for homologues + interactors
- Radioligand binding assay

Not cell-wide, but more quantitative for individual binding interactions compared to MS. 

# Multiplexing 
Multiplex techniques would be needed to compare cellular responses e.g., SILAC, TMT 

- SILAC – unlabelled grown in light isotope, labelled grown in heavy isotope. Up to 5 plex
- TMT 

From MZ: ![[Pasted image 20230527215803.png]]

