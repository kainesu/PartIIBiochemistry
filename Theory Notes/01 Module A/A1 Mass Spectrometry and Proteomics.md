# Questions
* **==Protein complexes==** [[A1 Mass Spectrometry and Proteomics#Native mass spectrometry|Native MS]], [[A1 Mass Spectrometry and Proteomics#MS and structural proteomics|Structural proteomics]]
	* Describe how mass spectrometry can be used to gain insight into multi-protein complex components
	* Outline how mass spectrometry can be used to study protein complexes purified from cells. Why does this help in characterising the proteins involved?
* Protein identification quantification 
	* Outline the limitations of mass spectrometry for identifying and quantifying proteins in mammalian cells. What other methods might be used to overcome these limitations?
	* Protein identification: what are the strengths and weaknesses of using mass spectrometry over an ELISA (detection and quantification using enzymes)?
	* In what situations would you consider using SILAC labelling for a quantitative proteomics experiment? Give examples of applications. 
	* *==To what extent is it possible to use mass spectrometry to systematically identify and study the protein complement within a cell? How might one best go about this?==*

# Principle of MS 
* MS measures the the **intensity **and **m/z** ratio of a molecule 
    * Intensity → relative abundance 
    * m/z → mass to charge ratio, depends on molecular composition of molecule  
* Organic molecules have isotope envelopes (i.e. a range of isotope masses) on an MS spectrum due to different proportions of <sup>12</sup>C/<sup>13</sup>C!

![[image1.png|400]]

* **Ion source** – Biological molecules have to be ionised using soft ionisation methods to avoid fragmentation of the molecule 
    * Matrix-assisted laser desorption ionisation (MALDI) 
        * Sample is mixed with a matrix which co-crystallises with the analyte. Laser irradiation causes the matrix/sample mixture to sublime into the gaseous phase, ionising the sample 
        * Usually coupled with Time-of-Flight (TOF) 
    * Electrospray Ionisation (ESI) 
        * ESI produces small positively-charged analyte ions via Coulombic explosion – charges are packed into the droplet until it fragments 
        * A volatile acid is used to make certain molecules positively charged by protonation (e.g. amino acids), alternatively a volatile base can be used to make molecules negatively charged via deprotonation (e.g. nucleic acids) 
* **Mass analyzers **
    * Time-of-Flight – Measures time taken for ion to travel the length of a vacuum chamber. Velocity of ions through the flight tube depends on m/z ratio. Flight tubes can be calibrated using molecules of known mass 
        * Reflections reduce the spread of flight times of ions with the same m/z caused by ions having different kinetic energies as they exit the ion source 
    * Quadrupoles 
        * #comment better explanation for this is needed 
        * Variant – octupoles 
    * Orbitraps 
        * An orbitrap consists of outer and inner coaxial electrodes that generate an electric field. Ions form harmonic oscillations along the axis of the field, and the frequency of the oscillation is inversely proportional to m/z ratio (calculated with Fourier transform) 
        * Lighter ions enter the orbitrap earlier and are squeezed closer to the inner electrode 
    * Different mass analysers are used depending on the level of resolution required (i.e. better separation of peaks of molecules with similar m/z) 
        * A higher resolution is preferable for complex samples with many molecules of similar m/z 
          ![[Pasted image 20221218180127.png|500]]
        * ICR ion cyclotron resonance > TOF, orbitraps > quadrupoles 
* **Detectors 
    * Electron multiplier detector 


## Using liquid chromatography to fractionate samples 
* For samples that have a simple composition, direct infusion may be sufficient 
* However for more complex samples (e.g. global protein analysis), MS analysis becomes simpler if the sample is fractionated using LC and the fractions infused into the MS sequentially 
* In LC, a column is packed with a stationary phase (matrix) 
    * For reverse phase (RP) LC, the stationary phase consists of hydrophobic beads while the mobile phase consists of an increasingly hydrophobic buffer. More hydrophilic peptides pass through the column more quickly and are eluted first 
        * The hydrophobicity of a peptide largely depends on its size, so smaller peptides are eluted first (peptides with exceptionally high proportions of hydrophobic residues e.g. W, Y may elute more slowly) 
        * The mobile phase is made up of increasing % of acetone/water 

# MS and imaging 
* MALDI can be used for imaging the position of molecules in tissue
* A slice of tissue is placed on a MALDI target, and the laser performs a raster of the sample. From each position on the target, obtain a mass spectrum, and use the intensity of the peak of the molecule of interest as a measure of its abundance in that location 
    * This data can be used to create a spatial distribution map of that molecule in the slice 
    * This can also be done over a time course to get kinetic data 
* Examples
    * #experimental_evidence Kakuda et al (2017) used MALDI-imaging mass spectrometry to visualise the spatial distribution of amyloid β deposits in the brains of deceased Alzheimer’s disease patients. Frozen tissue sections were created from the brains for imaging. 
    * #experimental_evidence Herring et al (2007) described the use of MALDI-IMS to visualise the spatial distribution of protein in the tumour and adjacent normal regions of the tissue in clear cell renal cell carcinoma 
        * Use of MS allowed for further identification of the proteins 
        * MS provides an alternative diagnostic marker for cancer 
    * #experimental_evidence  Bouslimani et al (2010) – MALDI-IMS for assessing distribution of the drug oxaliplatin to understand its metabolism in rat kidneys. It was found to  localise to the kidney cortex 
![[image4.png|325]]

# MS and protein characterisation 
## Intact protein mass spectrometry 
* MS on the intact protein 
* Best carried out on purified proteins 
* Not good for identifying proteins – isotopic envelope of protein may overlap with other proteins 
* Done in acidic conditions to promote protonation of proteins and protein unfolding 

## Native mass spectrometry 
- MS done in neutral conditions so that protein structure and protein-protein contact preserved

### Characterising protein complexes with tandem MS 
![](https://lh6.googleusercontent.com/JQw50VLytj7svh2jCc9iGg3mahgak3XqBzZqVESzFuLbwZHBHBmF9rpBhU409g1dPn-AIIzZ550miCclLXawC-rlCpfmPeHgYX0niB7RmNHFg6cN_qjU7w6mANPyaVo7LbTgHXoCNldAdPWcnjv42Q)
- Following m/z measurement of the intact protein complex, the complex is usually fragmented into its constituent subunits via collisional activation, then the m/z of the subunits are re-measured (tandem MS) to identify them. These subunits may undergo a further round of fragmentation to break them down into peptides, which would allow for identification of the precursor monomers.
	-  #experimental_evidence Belov et al (2013) employed this method with several protein complexes, including phosphorylase B and GroEL, and were able to map the peptide fragments obtained in MS3 back to the protein sequences of each complex.
- **Tandem MS can also be useful in elucidating the architecture of the complex**, specifically which protein subunits are core or peripheral to the complex
	- #experimental_evidence  Lorenzen et al (2007) used tandem MS to characterize the structure of an intact RNA Polymerase II complex. When the precursor ion was fragmented, it primarily led to the elimination of Rpb4, Rpb7, and Rpb4/7 heterodimer, which suggests that these subunits are likely to be on the periphery and also reflects the stable association between Rpb4 and Rpb7. This is because peripheral subunits are more exposed and thus more likely to dissociate first in tandem MS.
- A more extended approach involves gradually increasing the collision energy used and taking an MS reading at each stepwise increase in energy
	- #experimental_evidence Fandrich et al (2000) used this approach to dissect the structure of MtGimC, an archaeal protein involved in protein folding, and found that the protein is likely a pentamer with a core of two MtGimα subunits surrounded by three MtGimβ subunits on the periphery.
- **Native MS could also more simply be used to determine the stoichiometry between different subunits in a complex**. For homooligomers, the copy number of the subunits can be obtained by simply dividing the mass of the intact complex by the mass of the monomeric subunit, obtained via tandem MS. For heterooligomers, an additional MS step may be needed to determine the mass of each constituent subunit. Alternatively, the complex may need to be denatured chemically into its subunits which are then infused into the mass spectrometer

### Ultra high mass range MS may be used for proteins with high MW
- E.g. #experimental_evidence Loo et al. (2005) used native MS to characterise the structure and stoichiometries of the 20S proteasomes from _Methanosarcina thermophila_ and rabbit
- E.g. #experimental_evidence van de Waterbeemd et al (2018) used native mass spectrometry to characterise the structure of ribosomes 

### Study protein-protein interactions
- E.g. #experimental_evidence Chen et al (2022) used native MS to monitor the signalling cascade of rhodopsin receptor activation  
	- #comment more detail needed here 
	* #experimental_evidence  Lorenzen et al (2007) used tandem MS to characterize the structure of an intact RNA Polymerase II complex. When the precursor ion was fragmented, it primarily led to the elimination of Rpb4, Rpb7, and Rpb4/7 heterodimer, which suggests that these subunits are likely to be on the periphery and also reflects the stable association between Rpb4 and Rpb7. This is because peripheral subunits are more exposed and thus more likely to dissociate first in tandem MS.

## Protein identification via peptide MS 
* Single protein or global analysis of proteins in a sample
* Many proteins have similar masses, and large proteins do not fly well in a mass spectrometer 
* Instead, **proteins are often digested to peptides**, then peptides are characterised and act as a surrogate for the parent protein 
    * **Trypsin** is often used to cleave specifically at peptide bonds at the C-terminus of K, R such that the peptides have protonatable groups at their C-terminus (for ionisation in MS) 
    * The protein can be identified by feeding the m/z of the tryptic peptides, or m/z of the peptides + fragment ion data (i.e. sequences) into a database 
        * However, databases may only be usable for species with well-annotated genomes, e.g. zebrafish, mouse, _Arabidopsis_

### Peptide sequencing via LC-MS/MS
* In tandem MS/MS, the m/z of the intact precursor ion is measured, then the precursor ion is re-selected, fragmented, and the m/z of the fragment ions measured 
* Fragmentation occurs via collision-induced dissociation (CID) 
    * Precursor undergoes repeated collisions with inert gas 
* Different mass analyzers can be combined in tandem MS/MS, e.g.  
![[image5.png|400]]
* In peptides, the **peptide bond is the weakest bond** in the carbon backbone, so is most likely to break in fragmentation 
    * The MS/MS parameters (e.g. energy level, duty cycle) are set so that b and y ions dominate (i.e. most peptides only fragment at the peptide bond rather than at other covalent bonds) 
* The N-terminal fragment of the peptide is known as the **b ion**, C-terminal fragment = **y ion ** 
![[Pasted image 20221218180437.png|425]]
* Each peptide has a probability of cleaving at a different peptide bond, such that fragmentation produces a set of nested fragments 
* The **[mobile proton model](https://pubs-acs-org.ezp.lib.cam.ac.uk/doi/10.1021/jp911772q)** explains how b and y ions are formed – during electrospray ionisation of tryptic peptides, protonated peptides are produced that typically have at least two positive charges. During collision, peptide ions can undergo isomerisation reactions that result in one of the protons moving to a less thermodynamically stable site. 
* The mass difference between each b-ion / y-ion in the nested set corresponds to particular amino acids, and this can be used for sequencing. 
![[Pasted image 20221218180535.png|375]]
* Alternatively, the fragmentation spectrum of the amino acid can be searched against a database of predicted fragmentation spectra 

## MS and proteomics
* Proteome = all proteins present at a given time in any given sample (e.g. whole organism, tissue, cell, organelle, protein complex) 
* The proteome has to be studied directly – the transcriptome is a poor representation of the proteome due to
    * Other processes that affect the proteome, e.g. protein degradation, rate of translation, post-translational modifications 
    * Some cells lacking a transcriptome e.g. red blood cells, biofluids 

### Bottom-up proteomics 
* Separation via LS at the peptide level, followed by MS 
    * Purified protein → trypsinization → LC of peptides → MS

### Top-down proteomics 
* Separation at the protein level
    * SDS PAGE followed by proteolytic digestion → LC-MS/MS 
    * 2D PAGE (Isoelectric focusing → SDS PAGE) → proteolytic digestion → MS 
* But only possible for proteins 20 kDa and below 

## MS and quantitative proteomics
### **Extracted ion chromatogram** 
- Sums intensities of signals for a particular m/z from each timepoint in the LC
- Intensity of signal of particular m/z recorded as a function of retention time 
- Then integrate area under the curve 

### **Label free quantitation** 
* Uses spectral counting or ion intensity as a measure of quantity. 
* Spectral counting – number of spectra for a given peptide in different biological samples are counted, then sum the results 
* Ion intensity – integrate the signal intensity of a particular m/z 
	* Extracted ion chromatogram – if done with LC, intensities of signal peak at a particular m/z (corresponding to one or more analytes) can be integrated over time 
* For every precursor, a spectral library can provide information on the elution time, fragment ion m/z, and relative intensity to one another 
* To positively identify an ion, have to check both m/z and retention time in LC-MS – if the elution time of a peptide is similar to its fragment ions, we can be confident about its identity 
* One limitation of label free quantitation is that if there is a lot of technical variability between experiments to quantify individual proteins, we may not be able to see more subtle differences between different protein levels. Also, it takes a long time to do multiple MS runs → solution is to **multiplex** using stable isotope levels, since quantifying multiple proteins at once reduces the effect of technical variability 
* E.g. #experimental_evidence Mergner et al (2020) – used label free quantitation for the proteome of _Arabidopsis thaliana_ 

### Stable isotope labels
* Used for multiplexing as each protein of interest can be labelled with a different stable isotope. 
* As the analytes being compared have different masses, this will allow them to be distinguished and quantified by MS 
    * E.g. We want to compare the level of protein in a control group vs a treatment group. We can label the proteins in the treatment group with a heavy isotope, then pool samples from both groups for MS → only a singular MS run is needed to measure proteins from two treatments
* Stable isotope labelling in vivo – heavy isotope incorporated into proteins by growing the cells in media containing a heavy version of a particular amino acid or a source of heavy isotope (e.g. <sup>15</sup>NH<sub>4</sub>)
    * If grown in amino acid = stable isotope labelling of amino acids in cell culture (SILAC) 
        * Multiple isotope variants of each amino acid can be created by varying the number of <sup>13</sup>C in the carbon backbone of the amino acid 
        * For heavy amino acids, typically K/R is chosen as trypsin cleaves at the C-terminal of these residues ⇒ ensures that every other peptide carries the isotope label 
        * However R can be converted to proline in the urea cycle, so may want to avoid using R or load media with proline can help to minimise the cell's own proline synthesis 
        * SILAC is limited by the need to grow the sample in media with replaceable amino acids. Also we are growing the cells in an artificial medium, could affect their biology. The tag also has to be incorporated to 100% of the proteins which may not be possible for proteins with long half-life 
    * If grown in isotopic element = stable isotope labelling by elemental replacement 
        * Instead of just having one amino acid being “heavy”, all amino acids are affected as they all have the heavy isotope incorporated 
    * If incorporated into mammals = stable isotope labelling in mammals (SILAM) 
        * Mammals have to be labelled with heavy K and not R as R forms part of the urea cycle – label will be incorporated into other amino acids. 
        * Mice are labelled by feeding them a diet containing <sup>13</sup>C-labelled lysine over 4 generations 
    * Super SILAC – SILAC on multiple cell lines to get a more representative sample of the proteome e.g. Geiger et al (2010) mixed labelled protein lysates from several established cancer cell lines 
* Stable isotope labelling in vitro 
    * Proteolysis in the presence of light or heavy water – results in 4 Da offset between peptide digested in light water vs heavy water 
    * Chemical modification of peptides e.g. dimethyl labelling 
* Applications
    * <span style="text-decoration:underline;">Studying protein turnover</span> e.g. #experimental_evidence Mathieson et al (2018) – used SILAC to measure protein turnover in different cell types. They grew cells in SILAC, then changed the medium to heavy SILAC, and collected the cells at different timepoints for LC-MS/MS. Newly synthesised proteins would be labelled with the heavy isotope 
    * <span style="text-decoration:underline;">Studying protein expression</span> e.g. #experimental_evidence Song et al (2015) – Used pulsed SILAC to quantify newly expressed proteins in colistin-tolerant _Pseudomonas aeruginosa_ biofilms. Biofilms were grown in light medium, exposed to colistin, then briefly grown in heavy medium with colistin. Proteins newly synthesised following development of colistin tolerance will be labelled with the heavy isotope. By comparing the ion intensity of heavy-labelled peptides with light-labelled ones, can determine fold change in expression. 

### Isobaric labels 
* Allows for multiplexing
* While stable isotope labels result in peptides from different experiments having different masses, isobaric labels result in the peptides having the same mass 
* All peptides from a certain experiment are tagged with a particular isobaric tag on the amino group, then peptides from different experiments are pooled for multiplex MS/MS. The tag drops off in MS2 following fragmentation, forming a positively-charged reporter ion 
    * Each isobaric tag has a different reporter ion mass to allow for differentiation between the peptides
    * The intensity of the tag signal corresponds to the quantity of the peptide since each peptide is labelled once with a tag 
    * Number of tags (up to 18) = number of samples that can be multiplexed
*  Although the reporter ions differ in mass, the labels are made isobaric (same mass) by the presence of a mass normaliser component in the tag which is neutral such that it is not detected when it drops off during fragmentation 
	* The variation in mass is due to the distribution of heavy/light isotopes between the reporter ion and mass normaliser. As such, the difference in tags is limited by the number of carbon/nitrogen in the tag. This means the number of plex is limited by the size of the tag. 
* The point of using isobaric labels is so that in the first MS, the same precursor ion can be selected no matter what exact label it contains (since they all have the same mass) 
![[Pasted image 20221218180620.png|500]]
* E.g. [Chick et al (2016)](https://www-nature-com.ezp.lib.cam.ac.uk/articles/nature18270) –  used isobaric labels (Tandem Mass Tag [TMT]) to label proteins isolated from mouse livers and determine the extent of diversity in protein abundance between mice that arises from natural genetic diversity. 

## Comparison of multiplex methods 
- Isobaric has higher plex than SILAC 

## MS and protein interactions 
### Cross-linking mass spectrometry (XL-MS) 
* For identifying protein-protein interactions 
* Disuccinimidyl sulfoxide (DSSO) is often used as a cross-link between proteins as it reacts with primary amines (e.g. Lys side chains) 
    * Can be done in vivo – soaking cells in DSSO cross-links proteins 
* When the cross-linked proteins are introduced into MS/MS, the cross-linker breaks which separates the two proteins 
* On the MS spectrum, the masses of the two proteins can be measured and used to identify the proteins – the peaks can be re-selected for analysis 

![[Image10.png|350]]
-  #experimental_evidence Vasilescu, Guo & Kast (2004) chose formaldehyde as a cross-linker to identify a novel binding partner of M-Ras. Cells expressing Myc-tagged M-Ras were treated with formaldehyde, then M-Ras was co-immunoprecipitated with any interacting partners with anti-Myc. Proteins were separated via SDS-PAGE, trypsinized, and subjected to liquid chromatography (LC)-MS/MS
- The choice of crosslinker is important – not only does it have to be reactive with proteins, but it has to be cell permeable and have an appropriate spacer length. Methods should also minimize undesired crosslinks to contaminating proteins
- XL-MS can be a useful alternative to native MS for identifying protein complexes if the protein-protein interactions are too weak to survive lysis and purification before MS analysis 
	- Cross-linking helps to create stronger covalent crosslinks between interacting proteins in a complex that can survive to MS analysis
	- #experimental_evidence Kao et al (2011) chose disuccinimidyl sulfoxide (DSS) as a crosslinker to characterize the structure of the yeast 20S proteasome complex. DSSO contains two cleavable sites that break during collision-induced dissociation (CID), which allows for identification of DSSO-linked peptides.

### Hydrogen/Deuterium Exchange (HDX) 
* Uses deuterium to coat exposed surfaces of the protein 
* H atoms in the amide backbone of proteins will exchange with deuterium in D2O (if in liquid phase) or ND3 (if in gas phase) if they are exposed to the surface. If the H atom is inaccessible due to it being buried in the protein, or because it is involved in an interaction, then it is exchanged more slowly. Hence, if we were to compare the deuteration of a protein of interest versus the protein and a binding partner, the parts of the protein that form the binding surface would be hypo-deuterated. This difference can be detected by MS as a molecule with a higher D/H ratio would have a greater mass. The hypo-deuterated peptide fragments can then be mapped back to the original protein to identify the binding surface.
  ![[image 11.png|450]]
  ![](https://lh3.googleusercontent.com/MIMhJl5WVGeH1rx6EB2sUuTP8s32__lrJKo-PC3-u3bunxnjpqLsBNz5rFDu_vFIs1fBPQ9w7yIJLGpCNutRJyMovsh3FhLZLTFRE6FgoqqDeNtQk2nGQbHYOL1RbAKj_B3sUB14gaDrXLeJkIZw4Q)
* HDX can be used to study protein folding, conformational characterisation, dynamics, and protein-ligand interactions 
    * E.g. #experimental_evidence [Schubert et al (2017)](https://www-nature-com.ezp.lib.cam.ac.uk/articles/nature24645) used HDX to uncover ubiquitin interactions with PINK1. HDX was performed on Pink1 alone and Pink1-Ubiquitin complex, then the samples were broken down into peptides and run in MS. By checking which peptides became non-deuterated in the Pink1+Ubiquitin compared to Pink1 alone, can identify which regions of Pink1 interact with ubiquitin 
        * Control is needed to control for any non-deuteration due to burying in the complex, other effects unrelated to Ubq binding 
        * Protein interactions “protect” peptides from hydrogen-deuterium exchange 
    * **Probing binding surfaces**. E.g. #experimental_evidence [Mistarz et al (2016)](https://www-sciencedirect-com.ezp.lib.cam.ac.uk/science/article/pii/S096921261500502X) used HDX-MS to characterise the binding surface between lysozyme and an oligosaccharide substrate, and trypsin and a peptide substrate. Bound proteins exhibited less deuterium uptake. 

### Affinity purification-mass spectrometry 
* Capture all interacting partners of a protein using affinity purification (pull-down) – protein of interest act as the “bait” and interacting partners are the “prey”. The bait protein is genetically modified by adding an epitope that binds to an antibody so that it can be attached to an affinity column. Then the bait protein is used to capture proteins in a lysate that bind to it. After pull-down, any non-binding proteins are washed, then the bait and prey complex is eluted out of the column and prepared for either top-down or bottom-up MS analysis
    * Two epitopes can be used to minimise contaminating proteins (tandem AP-MS) → reduce likelihood of false-positive identification  
	    * Harsh washing conditions are also not necessary, allowing for recovery of native complexes. 
	    * Another advantage of such approaches is that they are generic, making them particularly suited to the study of interaction networks in which binding partners for multiple proteins can be analysed in parallel (Gingras et al 2005) 
	* Possible tags – GFP, calmodulin binding protein, Flag, Myc, HA, His<sub>6</sub> 
![[image12.png|450]]
![](https://lh5.googleusercontent.com/raux_0SRIoXaL1SgFoFVlTocw3bbb1oM78wqHwVIm-WPpDxQF5dB_nYFZGE3PSWJHwJoQHMvoyngyzrH8Q_aVmPYh8ThH4EtyQLYquTecv4rCy22i8YA7A_nGHvSmfYcE20AHeKPkuR9sbOJuUgoIg)
* E.g. #experimental_evidence Huttlin et al (2021) uses AP-MS using C-terminal Flag HA tags to identify networks of protein interactions 
* AP-MS can also be used to identify multi-protein complexes. 
	* If the protein of interest is involved in only a single multi-protein complex, then the other members of the complex would simply be the list of prey proteins eluted through the column. However, many proteins are involved in alternative protein complexes, and a single AP-MS run cannot determine what proteins are in which complexes. This is important knowledge as a protein can have vastly different effects in a cell depending on what complex it is found in. Instead, **reciprocal AP-MS** has to be run on the prey proteins to generate a network of protein interactions ![](https://lh5.googleusercontent.com/-kc7tj4mwlPI-vijCCZp6spAJVtLKzvL9C6a8Z2Pp2K4pNV1HOjYDPktJ5QDSOXzNgJQSjO3ugYo19Dp9SFPlSgCa4Sq2BH1Sb1W1Ov79OYdr5uPFJpOjlnlAO_76fnwyizwxI-kJBrj8IoxrHnghQ)
	* #experimental_evidence Gingras et al (2005) used tandem AP-MS to identify several mutually exclusive protein phosphatase 4C (PP4C)-containing complexes.
	* Combining AP-MS with biochemical fractionation techniques (e.g. gel filtration, ion exchange) can further allow for the complete isolation and characterisation of a particular protein complex.

## MS and mapping protein localisation 
* Immunofluorescence: Protein of interest is tagged with an antibody, then the antibody is labelled with a fluorescent affinity reagent (e.g. a secondary antibody) 
* Localisation of organelle proteins by isotope tagging (LOPIT): Fractionation of organelles followed by proteolytic digestion of proteins and in vitro isotope labelling of peptides in each fraction. Organelles do not partition into distinct fractions but they have unique enrichment patterns, thus allowing for assignment of proteins to organelles. Proteins in the same subcellular niche codistribute, so proteins with the same distribution pattern as known subcellular markers can be assigned to that particular compartment 
	* #question How is this different from protein correlation profiling? 
	    * E.g. #experimental_evidence Christoforou et al (2016) used a LOPIT variant (hyperLOPIT) to map the subcellular localisation of over 5000 proteins in in a pluripotent stem cell population 
		    * #question How does hyperLOPIT differ from regular LOPIT? 
    * E.g. Barylyuk et al (2020) used hyperLOPIT to map proteins in _Toxoplasma gondii_
* Proximity tagging: Bait protein is fused to a biotinylating enzyme (e.g. biotin ligase), which results in biotinylation of any interacting partners that come into close proximity of the bait. Interacting partners can then be pulled down with streptavidin and identified with MS  ^013483
    * Can also use [ascorbate peroxidase (APEX)](https://www-ncbi-nlm-nih-gov.ezp.lib.cam.ac.uk/pmc/articles/PMC4863649/) – ascorbate peroxidase catalyses the conversion of biotin-phenol to a free radical that covalently labels proteins proximal to the active site of APEX. APEX can be directed to a specific location in the cell in several ways, such as genetic fusion of APEX to a protein known to reside in the compartment, or to a targeting peptide. 
        * Advantage – allows for characterisation of compartments that cannot be biochemically isolated 
        * E.g. [Loh et al (2016)](https://www-sciencedirect-com.ezp.lib.cam.ac.uk/science/article/pii/S0092867416309916) used APEX to characterise the proteome of inhibitory and excitatory synaptic clefts 
        * Limitations: Cells have to be engineered to express and traffic APEX to the desired location; the system has to tolerate biotin-phenol and H<sub>2</sub>O<sub>2</sub>; there is limited utility outside of cell culture. 
    * Or horseradish peroxidase (SPPLAT) – A peroxidase-linked antibody binds to a protein of interest. Peroxidase catalyses the conversion of the tyramide moiety in a biotin-tyramide label into a free radical, which covalently labels any proteins in the proximity of the peroxidase, thus attaching a biotin label. Biotinylated proteins are pulled down with streptavidin. 
      ![[image13.png|500]]
    * E.g. #experimental_evidence [Go et al (2021)](https://www-nature-com.ezp.lib.cam.ac.uk/articles/s41586-021-03592-2) used proximity labelling to map the locations of thousands of proteins in HEK293 cells. In their study, they fused biotin ligase to a “bait” protein of interest, which biotinylates any lysine residues within 10 nm of the bait. Biotinylated proteins are then captured by streptavidin pull down and identified with MS. The average globular protein is 5-10nm diameter, hence this method can identify direct interacting partners and other proteins in the immediate vicinity. Biotin ligase was fused to profile intracellular protein markers for 32 different cellular components
        * Limitations: Low throughput as each bait requires a separate experiment; long incubation times make systems very noisy; some compartments are difficult to label (e.g. cytosol); difficult to compare proportions of a protein in different locations 
* Organelle enrichment/subtractive enrichment 
* Protein correlation profiling – Organelles are partially separated using centrifugation, and proteins from each organelle co-fractionate and hence exhibit similar distributions throughout the gradient. #experimental_evidence Dunkley et al (2004) then labelled proteins in each fraction with an isotopic label _in vitro_ for quantitation via MS. Localisation of novel proteins was determined by comparing their distribution with that of proteins with known localisation. The authors used this method to demonstrate membrane protein localisation in ER and Golgi of _Arabidopsis_. 
    * #experimental_evidence  [Andersen et al (2003) ](https://www-nature-com.ezp.lib.cam.ac.uk/articles/nature02166)used the method to identify centrosome-associated proteins 
* For multiplexing with these methods, the cell culture may have to be isotopically labelled from the start of the experiment (e.g. via SILAC)

## Clinical proteomics 
* Aim of the field is to find and use biomarkers in easily accessible biofluids e.g. blood 	
    * E.g. for cancer – proteins leaked out of tumours can be found in biofluids 
    * Problem is improving detection sensitivity – these proteins are present in small amounts compared to albumin
* E.g. Messner et al (2020) – identified serum protein biomarkers for Covid 19 and developed a MS platform for high throughput measurement of biomarkers 

# Other applications of MS
* Identifying bacterial species (Sauget 2017) 

# Major limitations of proteomics
* **Protein inference problem** – With bottom up proteomics, we cannot be certain what the specific precursor protein of the peptides are e.g. which protein isoform, which post-translational modifications 
	* #experimental_evidence Spellman et al (2007) – Did LC-MS/MS of proteome from PTB/nPTB knockdown cells to study PTB-dependent alternative splicing events in HeLa cells. Peptides diagnostic of TPM2 exon 6 skipping or inclusion were not found, yet RT-PCR showed a shift towards exon 6 inclusion in the mRNA 
	* “One hit wonders” – proteins with only one identified peptide 
	* Degenerate peptides – peptides that can be shared by multiple proteins. Often derived from homologous proteins 
* Could use top-down proteomics for validation, however MS is difficult with whole proteins because
    * MS workflows only optimised for small proteins 
	    * #question why? 
    * Difficult for membrane proteins
    * Limited coverage
	    * Highly expressed proteins rarely exhibit full coverage of all possible peptides, while lowly expressed proteins can sometimes be undetected 
    * Not used routinely for protein quantitation between samples 
* Low throughput 
* Dynamic range of MS is 5 orders of magnitude, but in the cell there are 8 orders of magnitude and in the serum, there is 15
	* Very abundant proteins have to be depleted out of serum first 
* For PTMs, phosphate groups will drop of S and T but not Y 
	* Electron transfer dissociation can prevent this – breaks peptides to get c and z ions (instead of b and y) 

# Links to other topics 
- [[B4 RNA splicing]] – Using mass spectrometry-based proteomics data, some investigators have suggested that alternative splicing plays a marginal role in generating proteomic diversity
- SILAC and proximity labelling has been used to study [[C3 Cytoskeleton and Organelle Movement#Myosin interactions|myosin interactions]] 
- [[D5 Cell Cycle#^44351e|Use MS to classify proteins]] phosphorylated under high CDK activity or low CDK activity, and thus identify any common characteristics 