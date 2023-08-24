# What is phase separation 
- mRNAs and proteins may assemble into biomolecular condensates
- Three main roles of biomolecular condensates in regulation 
	- Concentrating molecules
	- Exclude molecules that suppress biochemical activity
	- Sequester signalling molecules
	- Organisational hubs 
- Proteins in condensates tend to contain intrinsically disordered regions 
- Examples of phase-separated compartments: stress granules, P bodies 

# Properties of condensates
- The formation of a droplet requires a discrete transition from one stable phase to another upon the change of some physical parameter e.g. protein concentration 
- Highly dynamic – composition constantly changing 
	- Protein composition of condensates depends on the conditions within the cell 
- Behave as liquid droplets 
	- Coalesce upon contact 
	- Fission and fusion
- Affected by temperature 
- Can be by salt concentrations
	- Electrostatic interactions are important for some phase separations
- Different phases may be immiscible with each other
	- E.g. Nucleolus has a core-shell architecture 
		- This architecture may be important to sequential processing of rRNA transcripts 
	- Stress granules also have core-shell architecture 
	- P granules have some internal structure 

# Process of phase separation 
- Involves weak transient interactions between multivalent proteins, intrinsically disordered proteins, and/or RNA 
	- Multivalent proteins: proteins with repeats of binding domains
		- #experimental_evidence Making protein constructs with 3 or more SH3 domains mixed with similarly repeating PRM domains resulted in droplet formation.
	- IDRs are regions with low sequence complexity and are thus flexible.
		- #experimental_evidence DDX4 found to have IDRs at C, N-terminus 
		- Interactions between IDRs can be driven by different forces depending on the amino acid composition of the IDR, e.g. charge-charge, charge-π, π-π, hydrophobic interactions 
		- E.g. transcription-related proteins 
	- RNA can promote phase separation, and can contain multiple binding sites for one or multiple RBPs 
		- #experimental_evidence Li et al (2012) showed that polypyrimidine tract-binding protein (PTB) with 4 RRM domains undergoes LLPS in presence of RNA without IDRs present 
		- RBPs contain RBDs, e.g. RRM, RGG sequences 
		- LLPS of some RBPs require specific mRNA transcripts, while others are promiscuous and can undergo LLPS with any mRNA 
		- RNA can lower critical concentration for RBPs, but overly high concentrations can also block LLPS 
			- #experimental_evidence High RNA concentration blocks RBP FUS from LLPS in mammalian nuclei 
	- Transcription factors, transcriptional co-activators, RNA pol II, and RNA can undergo reversible chemical modifications (e.g. acetylation) which allow for cross-links to form between multiple molecules
- Concentration-dependent 
	- Critical concentration required for phase separation to occur 
	- For multivalent proteins, the critical concentration falls as valency increases (i.e. number of binding domain repeats)

> [!image] Langdon & Gladfelter (2018)
> ![[Pasted image 20230518222024.png]]

# Models for condensate formation 
**Scaffold-client model**
- RNAs bind to scaffold proteins to form RNPs in the cytoplasm, that  then nucleate to form a primary granule upon reaching a critical concentration **(scaffold)**. Only a few proteins are needed for phase separation. 
- Subsequently, addition or subtraction of certain **client** proteins can change the nature of the condensate, e.g. to make it more viscous or to make it more dynamic ![[Pasted image 20221220183049.png|575]]
# Regulation of phase condensates
- ATPases e.g ATP-dependent RNA helicases 
	- #experimental_evidence Viscoelasticity of nucleoli depends on ATP levels
	- #experimental_evidence Stress granule dynamics decrease when ATP levels are low 
- Post-translational modification of polypeptides 
	- #experimental_evidence Arg methylation increase concentration required for DDX4 droplet formation *in vitro* as it prevents charge-π interactions 
	- Phosphorylation also affects protein-protein and protein-RNA interactions in droplets 
		- #experimental_evidence kinase activity of DYRK3 can affect stress granule properties. When DYRK3 was transiently expressed in HeLa cells, it undergoes liquid-liquid phase separation. However, a kinase-deficient version of DYRK3 forms more solid-like aggregates 
		- #experimental_evidence Phosphorylation of G3PB inhibits stress granule assembly 
		- #experimental_evidence JNK phosphorylation of DCP1A releases it from P-bodies 
		- #experimental_evidence Pat1 phosphorylation inhibits P body assembly 
	- Seed condensation, e.g. negatively-charged poly adenosine 5'-diphosphate ribose (PAR) modification. Mimics way RNA nucleates phase separations. 

# Functions of phase condensates 
## Reaction crucible 
- Increase local concentration of reactants to increase rate of signalling
	- #experimental_evidence During T cell receptor signalling, linker for activation of T cells (LAT) acts as an adaptor to cause phase separation. 
	- #experimental_evidence Higher multivalency increases activation of mitogen-activated protein kinase (MAPK), suggesting that phase separation enhances signalling 
- RNP bodies can also enhance reaction rates
	- #experimental_evidence Model experimental system using polyethylene glycol and dextran to cause phase separation of ribozymes, RNA enzymes. Phase separation enhances reaction rates by two orders of magnitude. 
- E.g. Nucleolus acts as reaction crucible for rRNA biogenesis 

## Sequestration 
- Condensates may sequester unnecessary factors to prevent off-target effects
	- E.g. TORC1 is sequestered into stress granules, which suppresses its signalling 
	- E.g. Sequestration of RACK1 in stress granules prevents signalling to MAP kinases
- E.g. cytoplasmic stress granules compartmentalise stalled translation complexes 

## Organisational hub 
- Condensates can be used for spatial organisation 
- E.g. Organisation of spindle assembly 
	- #experimental_evidence *Xenopus* BuGZ is a microtubule-binding protein that was predicted to have IDRs. It undergoes LLPS *in vitro* and these droplets could concentrate tubulin. Seen to.play a similar role to spindle organising centres in cells 
- Heterochromatin in early *Drosophila* embryos with heterochromatin protein 1a (HP1a) have similar features to condensates, e.g. fusion, molecular exchange 

# Condensates regulate cellular processes

## Transcription 
[[B1 Transcription#Hypothetical phase separation model of transcription|Model of phase separation for transcription]]

## Spatial regulation of translation 
[[B2 RNA localisation#Phase separation]]

## Temporal regulation of translation 
[[B5 Translation and translation regulation in eukaryotes#Phase separation]]

## Chromatin organisation 
[[B3 Chromatin structure and gene expression#Liquid-liquid phase separation]]

# Criticisms of phase separation experiments 
- **Many experiments done _in vitro_** and not under physiological conditions (e.g. not at the endogenous concentrations of the proteins as proteins are often overexpressed, use of non-native buffers e.g. dextran) 
- **Many experimental systems are highly simplified**, using only single proteins or isolated domains → need to use more realistic, multi-component droplets 
- **1,6-hexanediol**, which is commonly used for disrupting LLPS droplets, was found to immobilise and condense chromatin in cells (Itoh et al 2021) → should be careful about interpreting results when 1,6-hexanediol is used if the droplets contain chromatin 
- **FRAP** is also commonly used but cannot determine whether a droplet behaves as a “liquid”, only indirectly shows changes in mobility of protein components 
- **LLPS not necessary** to explain all transcriptional regulation – IDRs can recruit transcriptional machinery via multivalent interactions 
- **Some experiments rely on protein mutation** to disrupt phase separation, but this can also affect protein function and interactions 
	- Need to use other tools to disrupt phase separation, or use protein homologs that don’t exhibit phase separation  

# Future directions/questions 
- Single molecule imaging and tracking – can be used to track the behaviour of molecules when they transition in and out of the droplets 
	- #experimental_evidence Ide et al (2020) used this method to investigate the molecular behaviour of RNA Pol I in the nucleolus, which consists of multiphase droplets

# References
[[ShinBrangwynne_2017]]