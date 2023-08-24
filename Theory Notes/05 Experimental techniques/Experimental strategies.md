# Experimental design 
1. What is the question? 
2. Design an initial experiment 
	1. Independent variables – how to change? 
	2. Dependent variable – how to measure? 
	3. Controls – how to ensure that change in dependent variable is only due to the independent variable we are interested in? Think about what are all the variables that could affect the dependent variable, then create a control for those that isolates their effects 
3. Design a follow-up experiment that could confirm the results of the initial experiment 
4. Possible limitations? 

# Structural techniques 
- Deletion analysis – "once a molecule is demonstrated to participate in an interaction, several deletion derivatives are produced and tested in the binding assay to identify the minimal fragment (domain) that can still support the interaction"
	- Can be protein or RNA 
- Mass spectrometry 
- Cryo-EM 
- NMR 
- AFM 
- Small angle X-ray scattering 
- Molecular dynamics 
- EPR
- Directed evolution 

# Membrane movements
- FRAP 
- Membrane mimetics – can control lipid composition if want to study effect of different lipids 
	- Nanodiscs 
	- Liposome
- Microscopy using membrane markers 

[[C2 PTMs and Protein trafficking#Experimental techniques]]

# DNA 
- Sequencing 

## Transcription 
- Deletion, mutation analysis 
- PRO-Seq
- Nuclear run on assay 
- Rescue mutations 

## DNA-protein interactions 
[[B1 Transcription#Mapping DNA-protein interactions]]
- Identify candidates using pull-down with DNA as bait; heparin as non-specific DNA binding protein control. Then mass spec 

## *Cis* regulatory elements
[[B1 Transcription#Identification of UEs using *in vivo* transcription assays]]

[[B1 Transcription#Identification of promoters]]
In silico 

[[B1 Transcription#Enhancer trap assay for identifying enhancers]]

## Chromatin 
[[B1 Transcription#Chromatin conformation capture (C3)]]

[[B3 Chromatin structure and gene expression#Techniques for determining long-distance interactions between non-contiguous regions of DNA]]

[[B3 Chromatin structure and gene expression#Approach for identifying FACT (FAcilitator of Chromatin Transcription)]]

# RNA 
## Function of RNA 
- Sequence -> bioinformatics
	- Coding region 
	- Splice site prediction 
	- What regulatory elements are present? 
- mRNA -> riboseq, cap binding assay 
- KO with RNAi 

## Secondary structure
- Computational prediction, e.g. SHAPE 
- XRC 

## Identifying RNA-binding proteins 
- RNA affinity columns
- UV-crosslinking
- Gel retardation assays (e.g. EMSA, gel shift)
- SELEX – identify optimal RNA-protein binding sites 
- OOPS
- RNA footprinting 
- NMR chemical shift 
- IP 
- Use biotinylated nucleotides
- Radio-label RNA + crosslink 

Important to have control RNA, as many proteins bind RNA non-specifically 
- Random RNA sequence – but risk of creating another kind of protein binding site 

## Translation 
- Ribosome profiling 
- Reporter assays 
- Mutation analysis
- Create constructs with reporters (e.g. luciferase, GFP)
	- Need controls e.g. RLuc 
- RNA-Seq 
- Toeprint assays
- Pulse labelling to determine rates of translation – SILAC for proteins, 4-sU for mRNAs. 

[[B5 Translation and translation regulation in eukaryotes#Studying translation]]

## Decay 
[[B6 Cytoplasmic RNA decay#Approaches to studying RNA decay]]

## Splicing
[[B4 RNA splicing#Methods for experimental identification of ESEs and ESSs]]

[[B4 RNA splicing#Methods for studying global AS events (ASEs)]]

## Detection – localisation and amplification 
[[B2 RNA localisation#Techniques for detecting mRNA]]
- Northern blot 

# Protein
## Enrichment / isolation of candidate
- Fractionation 
- 2D gel 
- Genetic screens (Forward genetics) 
	- Selection e.g. [[HuffakerRobbins_1982]]
- Gene trapping 
- TiO2 columns for phosphorylated proteins 
- Antibodies
- Pull-down assay using known ligand 
- Cell-based screening 

## Identifying protein 
- MS proteomics 

## Understanding protein function (once candidate has been identified)
- Inhibit the protein with a drug 
- RNAi or miRNA 
- KO gene and see phenotype (reverse genetics)
- Radioligand assay
- Fusion proteins -> fuse domain to another protein to see its function 
- Rescue experiments 
- Tethering assay – Hairpin-MS2 system 
- Deplete protein from lysate with antibody or affinity column 
- Isothermal titration calorimetry 
- Overexpress protein 
- Degrons 
- Temperature sensitive 
- Look at clinical databases for mutations 
- Inject exogenous protein into cells 
- Mutation analysis / site-directed mutagenesis 
	- Dominant negative mutations
- Digestion with protease 
- Tissue-specific promoter 
- Heterologous expression of a homologous protein in a KO system -> if it rescues, means they have same function 
- Analog-sensitive proteins
- Bioinformatics -> look for homology to other proteins 
- Antibodies to identify PTMs, other moieties 

## Protein interactions 
- FRET 
- Co-fractionation 
- Y2H 
- Co-IP 
- Pull down 
- GST pull down 
- SPR 
- Radioligand binding assay
- Bioinformatics 
- [[A1 Mass Spectrometry and Proteomics#Characterising protein complexes with tandem MS]]
- [[A1 Mass Spectrometry and Proteomics#MS and mapping protein localisation]]

## Biophysical properties 
- Optical tweezers 

## Detection 
- Western blot 

## Localisation 
- Antibodies 
- GFP fusion protein 
- [[A1 Mass Spectrometry and Proteomics#MS and mapping protein localisation]]

# Carbohydrates
- Lectins
- Antibodies 
- Digestion 

# Cytoskeleton 
[[C3 Cytoskeleton and Organelle Movement#Techniques for studying the cytoskeleton]]
- Quantification of Arp2/3 using nanocages as a standard 

# Phase separation 
- 1,6-hexanediol 
- FAPS 

# Process analysis 
- Reconstitution analysis
- Pulse-chase analysis: "A method for examining a cellular process occurring over time by exposing the cells to a labeled compound (pulse) and then to the same compound in an unlabelled form (chase)... movement of the labeled (compound) can then be tracked within the cell" 
	- or activate expression (pulse) and then stop and monitor (chase)
	- Used to prove the existence and function of Okazaki fragments
- Time course cross linking 

# Model systems
[[D9 Experimental Models]]

*Arabidopsis* for plants 

Clinical trials, longitudinal studies for humans 

# Single molecule 
- smFRET 
- smFISH 
- Super-resolution microscopy – STORM, TEM, Airyscan 
- Spectroscopy – optical tweezers, magnetic tweezers
- Cryo-ET 
- Patch clamp 

[[VeigelSchmidt_2011]]

# Does this process account for everything 
- KO the process and see if response goes to 0. if not, means there are other processes at work 
- Use a conditional mutant e.g. temperature sensitive, Tet-controlled 