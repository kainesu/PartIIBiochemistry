# Principle 
* EM produces a magnified image that includes the full structural information of the molecule  
* Reconstructs 3D structure from many 2D projections 

# Process
1. Apply protein sample in solution on a microscopic grid 
2. Stain protein with uranyl acetate (negative stain, high contrast, low resolution, may introduce artefacts) OR freeze in liquid ethane to cause water to vitrify (less contrast, high resolution) 
    1. Negative staining → normal TEM 
    2. If vitrification is used → cryo-TEM 
3. Obtain many 2D images of the protein. 
    3. Each 2D image represents a projection of the 3D shape of the molecule 
    4. Protein is oriented in different directions in the EM grid
4. Reconstruct 3D shape from 2D images computationally 
    5. Each 2D image can be Fourier transformed, and each 2D Fourier transform can be considered sections of a 3D Fourier transform. After combining the 2D Fourier transforms, to make a 3D FT, do Fourier inversion to make a 3D map of the original 3D specimen
![[image11.png]]

# Examples of Cryo-EM 
* #experimental_evidence Fitzpatrick et al (2017) – Used Cryo-EM to determine the structures of tau filaments from Alzheimer’s disease patients 
* #experimental_evidence Cao et al (2013) – Cryo-EM solution structure for transient receptor potential cation channel subfamily V member 1 (TRPV1) in complex with vanilloid agonist resiniferatoxin (RTX)
* #experimental_evidence Fernandez et al (2013) – Cryo-EM structure of 80S ribosome in complex with eIF5B despite the structural state of interest only making up 3% of the recorded particle images. Unsupervised maximum likelihood classification was still able to identify these particles and generate a structure with decent resolution (6.6Å) 
* #experimental_evidence Wang et al (2017) – visualizing inhibitor binding to a transporter 

## Studying structural heterogeneity with cryo-EM 
- Thanks to image classification algorithms, cryo-EM can be used to study structurally heterogenous samples
* Most existing 3D reconstruction methods for cryo EM are ineffective at modeling flexible proteins
* 3D variability analysis (3DVA) is an algorithm that can be used to resolve and visualize molecular dynamics of proteins at high resolution (Punjani & Fleet, 2021) 
    * #experimental_evidence 3DVA was applied to dataset of Cannabinoid Receptor 1-G GPCR complex particles and was able to resolve the bending of the CB1 transmembrane domain towards and away from the G-protein, perpendicular bending of CB1 domain, and twisting of CB1 transmembrane region around a vertical axis perpendicular to the membrane (this particular motion is remarkable as it occurs in a small subregion) 

### Protein dynamics 
- In cryo-EM, proteins in the sample can be visualised in all conformations they adopt as they are suspended in whatever conformation they were in at the time of vitrification. These different conformations can be separated out during image processing. Being able to see multiple conformations of the protein at once allows for understanding of conformational changes, which are crucial to understanding protein function. By acquiring structures at different processive stages, the microscopist can construct a mechanistic model for various cellular activities.
- #experimental_evidence Borgnia et al (2016) showed that GDH can exist in two conformational states depending on whether it binds to NADH or not, and each state differs in the conformation of NADH in the regulatory site of GDH, thus revealing a possible function of NADH as a GDH regulator
- #experimental_evidence Li et al (2019) found via cryo-EM that Snf2, a chromatin remodeler, has a closed conformation when bound to ATP, but adopts an open conformation when bound to ADP, which alters its interaction with DNA.

## Studying structures *in-situ* via cryo electron tomography (Cryo-ET) 
* In cryo-ET, a tilt series of 2D images of the sample is taken, with each image taken at a different angle, and a tomographic 3D structure is reconstructed from these images computationally ![|475](https://lh5.googleusercontent.com/-5FxY2zWPwxud4gMVy_fk2P_4J-dIrHT4mg2OOA53Ytxs56eKRwesPJte_g1DQ2MyvZ0W4HPswYaQuQhsKifJNNxmh2D4tA69IVPPDgN1cFmA-ajyb18srqllGwPIE7Lg6F-DYNkKs9bqt_EWQmFDAM)
* Cryo-ET allows for the study of structures in their _in vivo_, native environment, thus capturing the complexity of the *in vivo* environment
* For membrane proteins, this is useful as it can capture the complexity of the native membrane environment which membrane mimetics are unable to 
* By combining structures obtained from single particle cryo-EM with the images obtained via cryo-ET, structural biologists can obtain detailed information about protein structures as they exist in their local environment. 
	* This is important as protein function can often be context-dependent and structures can be affected by where the protein is in the cell, as well as what interactions the protein has with other molecules in its environment.
* #experimental_evidence Chen et al (2021) used cryo-ET to obtain the in situ structure of AcrAB-TolC efflux pump is at 7 Å resolution, which is sufficient to fit high resolution models of AcrAB–TolC 
    * Difference with _in vitro_ structure 
        * Membrane proximal (MP) domain of AcrA in cryo-ET structure is rotated by 8° compared to _in vitro_ structure, which is likely caused by the AcrA termini being in its native environment where it is anchored to the inner membrane, rather than bound to free surfactant ⇒ lipid-protein interactions are important to maintaining the structure of the protein 
* #experimental_evidence Albert et al (2017) – used cryo-ET to image cytosolic and nuclear proteasomes directly within cells, allowing the researchers to demonstrate that nuclear proteasomes tether to the nuclear pore complex, as well as the mechanism for this tethering interaction

## Time-resolved cryo-EM (trEM) 
* A time resolved series of cryo-EM images would allow for structural determination of intermediates as well as the order in which they occur, thus providing information on protein dynamics 
* For time resolution, there is a need to develop a system that allows for rapid sample blotting on the cryo EM grid, fast enough to capture short-lived intermediates in biochemical processes (i.e. sub-second timescales). Standard cryo-EM preparation methods are too slow to capture such intermediate states without the aid of mutagenesis, chemical inhibitors or crosslinking agents that could interfere with the function of the protein (Maeots et al, 2020)
* #experimental_evidence Maeots et al (2020) used a modular microfluidic device to visualize reaction intermediates of early RecA filament growth at sub-second timescales 

### Advantages of trEM (Maeots et al, 2020)
* Does not rely on fluorescent or radioactive labels 
* All structural transitions in the molecule can be studied in the same experiment, rather than just areas close to chosen label sites 

### Limitations of trEM 
* Large amount of sample is consumed per experiment compared to other sample preparation methods 
* Multiple structurally similar states may co-exist → have to be able to detect them reliably to quantify their relative populations at any point in time to determine the order of molecular events 

# Advantages and disadvantages of cryo-EM
## Advantages
- Can acquire the structures of a much wider range of proteins as they do not have to be crystallisable e.g. membrane proteins, flexible proteins 
	- Obtaining a crystal structure of the protein can be challenging for certain kinds of proteins that do not lend themselves to an organised arrangement, such as fibrous proteins or proteins with disordered regions, but cryo-EM is able to obtain a structure for such proteins.
		-  #experimental_evidence Fitzpatrick et al (2017) – obtained the cryo-EM structure of tau filaments from Alzheimer’s disease at 3.4-3.5Å resolution. These filaments have a core region made up of repeating units as well as disordered regions towards the N and C-termini, which would likely have made it difficult to crystallise. In addition, disordered regions tend to “disappear” in the diffraction pattern obtained via X-ray crystallography because of the low average electron density.
	- Membrane proteins are also difficult to crystallise, and to obtain a crystal, crystallisation conditions have to be optimised for detergent type and amount, or the proteins have to be embedded in micelles. However, these workarounds can lead to crystals with lower resolution
		- Overcome with cryo-EM. #experimental_evidence Zhao et al (2019) – determine the structure of a eukaryotic voltage-gated Ca2+ channel at less than 3Å resolution, and cryo-EM has been successfully used to determine the structures of all 7 TRP channel subfamilies.
	- Can obtain conformations of proteins under a wider variety of conditions since conditions are not restricted by whether it can produce a crystal 
* Can be used to study large objects
* Can be used to image large objects with internal symmetry e.g. viral capsids 
* Can be used to image fibrous proteins with open symmetry e.g. actin 
* Can determine structures at atomic resolution i.e. ~2Å
* Requires less material than XRC 
* Can be used to identify multiple structure from the same specimen 
* Can be used to study structurally heterogeneous samples by classifying cryo-EM datasets. Cryo-EM images of different particles or conformations can be separated out during data processing. 
	* Because of this, samples do not need to be as pure as in XRC. This is useful for proteins that are difficult to purify or have low abundances in the cell 
	* Also useful for obtaining structures of different conformational states to gain mechanistic insights, since all stable conformational states will be suspended in vitrified liquid at once 
		* Compare to XRC, where each conformational state would have to be stabilised and crystallised, which is laborious 
	* However, this is limited by the size of the particles. “For complexes that are smaller than ribosomes, or that contain continuously flexing domains, separation of the particles in structurally homogeneous subsets is difficult”
* Since the protein is captured in vitrified liquid, the protein structure will be as close to in its  natural environment as possible. 
	* Protein is not forced into ordered conformation of crystal, which may even require modification of protein in some cases for it to be crystallisable (e.g. truncation of disordered domains, mutations of certain residues)
	* Minimum damage to protein from radiation 
	* Cryo-ET will take cryo-EM to peak of realisticness by acquiring structures *in situ*
* Relatively quick method – low to medium resolution density structure can be obtained in a few hours 
	* Thus suitable for proteins with unstable structures that may denature over long sample preparation and data acquisition periods 
	* Suitable if need for speed > need for accuracy 
	* #experimental_evidence Most solution structures of SARS-CoV-2 spike (S) protein currently in PDB were obtained via cryo-EM. This was because there was an urgent need to rapidly determine the structure of the S protein to understand how to combat the disease 
* Phase information remains accessible – no phase problem like in XRC 

## Limitations
- Lower resolution than XRC and NMR 
	- Most structures solved by cryo-EM have a resolution of 3-4Å, though a few have better resolution at about 2Å.
	- map quality of many cryo-EM structures are not considered sufficient to accurately identify non-protein densities (e.g. drug molecules, lipids).
	- XRC can achieve resolutions of even below 1Å
	- But probably will improve with innovations in microscope technology
		- #experimental_evidence Ip et al (2020) was able to accomplish a particularly high resolution structure (1.25Å) of apoferritin with a new type of electron microscope.
- Need many molecules to get a decent reconstruction – ~100k 
- Low signal to noise ratio 
	- We cannot simply increase electron beam density or it will destroy structures 
	- This is especially problematic for smaller particles because the maximum beam density we can use without destroying the particles is lower 
		- Could increase size by attaching nanobody 
	- Signal to noise ratio can be improved by using thinner ice, using more particles, and using a more sensitive detector
		- Ice cannot be too thin or molecules cannot fit 
- No good way of localising metal ions 
	- Cf XRC, can use metal anomalous diffraction 
- Time-consuming – not high throughput 
* Still slower than XRC for drug discovery (Renaud et al 2018) 
    * Once suitable crystallization conditions have been found, it is easy and quick to obtain subsequent structures with different compounds, often simply by soaking the crystal in a solution containing the drug. Crystallisation conditions can also be screened in high throughput (~2000 in 1h) 
    * In contrast, it takes much longer to screen suitable samples and conditions for cryo-EM – hours to days to generate enough data for each high resolution EM structure
    * #experimental_evidence  At XChem, can obtain diffraction data for ~500 crystals in 24h, with data processed within a week vs cryo-EM which would take half a year for data collection and 1 year for model building 
- Proteins can have preferential conformations in vitrified ice
	- Resolution anisotropy 
	- "In many cases, trying to get the biological molecules into very thin films causes them to encounter the air-water interface. This interface has surface forces capable of destroying the tertiary structure of the molecules or causing the so-called preferential orientation of molecules. Which in turn will severely limit the resolution"
		- We can remove one of the air-water interfaces by using a layer of carbon in the grid.
		- Or add detergents – not sure of mechanism but helps with air-water interface problem
		- Particle adsorption to air-water interface
* When studying multi-protein complexes, components may dissociate 
* Accessibility – ”electron microscopists are typically still expert scientists, and the elevated costs of purchasing and maintaining modern microscopes makes experimental time both scarce and expensive”
* Stopping beam-induced motion as it causes image blurring  
    * Use direct electron detection (DED)detectors 
        * “Fast readout makes it possible to compensate for small movements that inevitably happen when the electron beam strikes the thin, unsupported cryo-sample” 
    * Record a movie and align individual frames of the movie to get a clear image
    * Electron counting can help to correct for this 
* Minimum size floor of ~150 kDa for protein structure to be accurately solved by cryo-EM 
	* Weight limit may be gradually decreased 
		* #experimental_evidence Fan et al (2019) – weight limit may be gradually decreased, as the structure of the 52 kDa streptavidin was successfully reconstructed recently with 3.2Å resolution
	* Or bind antibodies to protein (e.g. β<sub>1</sub>AR-arrestin complex)
- Low throughput of optimising buffer conditions
	- Only way is to check images after processing 
- Not as good as NMR at capturing enzyme dynamics 
	- While cryo-EM is capable of capturing different structural conformations, this is only true to an extent – stable and homogenous samples still tend to produce higher quality images
	- cryo-EM is not able to visualise minute and rapid changes in protein structure that may nonetheless be key to its function. Similar to X-ray crystallography, the lowest energy conformer is typically the one captured by cryo-EM, which could mean it misses out higher energy, transient conformations with millisecond-long lifetimes. Cryo-EM can only provide a range of static structures, without indicating how the structures interconvert or how quickly they interconvert

Januliene & Moeller (2020) 
Bai et al (2015) 

## Areas for advancement
* Improving CMOS detectors to improve average DQEs 
* Need for better image classification methods 
* Improvements in computational hardware – maximum likelihood methods, better GPUs 

# Membrane Cryo EM 
- Protein also has to be isolated in some membrane mimetic e.g. nanodiscs (see)
- Cryo-ET may allow for imaging of proteins in their native membranes albeit at lower resolution ^a0caf0
	- E.g. Chen et al (2021) 

### Examples 
- [[QiuEtAl_2018]] embedded AcrB in nanoparticles based on styrene maleic acid (SMA) lipid particles (SMALPs)
- #experimental_evidence Du et al (2020) embedded detergent-solubilised AcrB/Z or AcrB in Saposin A nanodiscs with *E. coli* lipid, which could then be imaged via cryo EM
	- #comment This is a Luisi lab paper lmao 
- #experimental_evidence Harris et al (2021) determined the structure and mechanism of the yeast transporter Pdr5 via cryo EM by embedding it in a peptidisc, which is a short amphipathic bi-helical peptide used to create a native membrane-like environment 

# Links to other topics 
- Dynamics
	- [[A7 G proteins^c7e6b4|Dynamics of PDE activation by transducin]]
	- During translocation, [[A8 Machinery of Translation#^b2bb75|30S subunit]] is rotated (ratcheted) with respect to 50S subunit 
	- Intermediates in [[A8 Machinery of Translation#Structural techniques|elongation cycle]]
	- [[VoorheesHegde_2016]] used cryo-EM of stalled translocation intermediate using canine ribosome-Sec61 with secretory protein preprolactin was used to determine the structural changes that occur in Sec61 during translocation 
- Structures of large complexes 
	- Structure of [[C2 PTMs and Protein trafficking#Clathrin outer coat|clathrin outer coats]]
	- Structure of [[C2 PTMs and Protein trafficking#Structure of COP I coat|COP I coats]]
	- [[C3 Cytoskeleton and Organelle Movement#Microtubule-associated proteins (MAPs)|Microtubules in complex with MAPs]]
	- [[C3 Cytoskeleton and Organelle Movement#Clathrin-mediated endocytosis|Serwas et al (2022) used Cryo-ET]]  to visualise the actin network involved in endocytosis
	- Cryo-EM used to show how Cdc45 and GINS bind to Mcm2-7 helicase to form [[D1 DNA Replication#Activation of Mcm2-7 helicase in replisome|CMG complex]]
	- Cryo-EM shows no regular amorphous regions in [[C6 Cell walls, energy, materials#Structure|cellulose]]
	- Structure of [[C6 Cell walls, energy, materials#CesA proteins|CesA trimers]] 
- [[BuschauerEtAl_2020]] – Cryo-EM structure of CCR4-NOTwith ribosomes showed how CCR4-NOT is recruited to ribosomes when ribosome adopted a distinct conformation lacFing accommodated tRNA in the A-site, indicative of impaired decoding kinetics" 
- Studying [[B1 Transcription#Pause elongation complex and release|proximal promoter pausing]]