**How would you identify and characterise the components of an extracellular-ligand-dependent signalling pathway that activates transcription factors?**

# Introduction 
- Assuming we have a ligand, and we know the ligand activates something that gives a particular phenotype 
- Goal is to identify proteins in the pathway and characterise their binding properties 

# Identify receptor 
## Purify receptor
- Radiolabelled ligand (possibly one that can stably bind – some modifications?)
- Chemical reagent that reacts with both ligand and receptor [https://www.nature.com/articles/nbt.2354](https://www.nature.com/articles/nbt.2354)
- Affinity chromatography
- Biotinylation
- Genetic screens 
- Screen ligand against library of recombinantly expressed receptor domains 
- Cell-based screening: Have library of cells overexpressing different receptors [https://elifesciences.org/articles/81398](https://elifesciences.org/articles/81398)
	- Generate library with CRISPR activation
	- Use radioligand or fluorescently attached ligand -> cell overexpressing cognate receptor has higher signal 

## Mass spec 
- Identify receptor with MS 

## Characterise receptor 
- Ligand binding kinetics for receptor 
	- Affinity, number, location of binding sites
- Structural determination – cryo-EM/NMR depending on size 
- Changes to receptor (structural and/or chemical) upon ligand binding 
	- Conformational changes 
	- PTMs

# Identify proteins that bind receptor 
- MS for PPIs 
	- SILAC MS to identify changes in PTMs, protein levels upon ligand binding 
	- AP-MS/MS
	- XL-MS/MS
- Y2H 
- Machine learning
	- Use ML algorithms on existing PPI data to generate a pathway e.g. CASCADE_SCAN 
- To confirm that proteins indeed interact: 
	- KD/KO candidate proteins
	- Co-IP 
- Characterisation – determine mechanism of interaction 

# Identify proteins downstream 
- Repeat above steps until TF identified 


