# Learning outcomes and Questions
* How can we study internal protein dynamics and dynamic structures? 
    * ==Discuss how the structures of dynamic proteins and assemblies can be studied==
    * Discuss, using examples, how NMR spectroscopy has contributed to our understanding of protein dynamics.
* How do protein internal dynamics contribute to enzyme function? 
    * What is the experimental evidence for internal motions in proteins? How do these motions contribute to an enzyme’s function?
    * ==What functional insights can be gained from biophysical studies of dynamic processes in globular and membrane proteins?==
    * How would you explore the role of protein dynamics in enzyme function?
    * Explain how internal motion contributes to enzyme function.
    * What methods are available for detecting dynamic processes in globular and membrane proteins, and what functional insights have they generated?
* *==[Is cryo-EM making NMR and XRC obsolete? ](https://docs.google.com/document/d/1So5CVEMer0826aqtO5jXxuhQNRMif8cppMypY3-bIpU/edit)==*
    * Advances in electron microscopy have made NMR spectroscopy and X-ray crystallography redundant for structure determination of macromolecules. Discuss.
    * ‘Cryo-electron microscopy is the method of choice for determining protein structure and function.’ Discuss.
    * Advances in electron microscopy have made NMR spectroscopy and X-ray crystallography redundant for structure determination of macromolecules. Discuss
* What methods can we use to study the structures of proteins and other molecules? 
    * **==*You have isolated a 40 kDa protein and would like to obtain its high resolution structure. Describe the method you would use and explain why this is the most appropriate. Would the method you choose differ if the protein were much larger (e.g. 1000kDa) and had multiple domains? Explain your reasoning.*==**
    * What methods can be used to study single molecules in biology? Using examples, outline some of the advantages of such approaches.
    * ==How would you determine the atomic bonds involved in the binding of a small molecule into the binding site of a protein, and why is this information useful?==
* How are NMR and XRC complementary to each other? 
    * ***==NMR spectroscopy and X-ray crystallography provide complementary information about the structure and dynamics of proteins. Discuss==***

# Cryo-EM, NMR, and XRC are complementary methods
* While large protein structures (above 250 kDa) are being increasingly studied with cryo-EM, XRC still preferred for smaller proteins and for drug design

## NMR vs X-ray crystallography for structural determination 
| NMR                                                                                                                                                                            | XRC                                                                                                                                         |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------- |
| Sample is in native solution phase                                                                                                                                             | Sample has to be crystallised                                                                                                               |
| Can study both structure and dynamics (basically the method of choice for studying dynamics – other methods e.g. XRC, fluorescence spectroscopy, only give an average picture) | New XRC variants being developed may be able to allow for protein dynamics investigations, but are not as well-developed as NMR (e.g. XFEL) |
| Can study detailed chemistry – e.g. Presence of H-bonds, tautomeric states, etc.                                                                                               |                                                                                                                                             |
| Only proteins less than 30 kDa are suitable for routine NMR, but many proteins are bigger than that                                                                            | Can study much larger structures                                                                                                            |
| Still needs user intervention to obtain a solution structure                                                                                                                   | Quicker, methods are easier to use and automate                                                                                             |
| Can be used to visualise disordered regions – helpful as disordered regions can mediate protein interactions (e.g. RNAP II CTD)                                                | Flexible regions do not provide coherent X-ray scattering and do not contribute to final electron density map                               |
| Timescale = Weeks                                                                                                                                                              | Timescale = days                                                                                                                            | 

* Small proteins that provide good quality <sup>15</sup>N <sup>1</sup>H heteronuclear correlation (HSQC) NMR spectra under conditions generally suitable for 3D structure determination by NMR is not correlated with successful crystallisastion and structure determination by XRC (Snyder et al 2005) ⇒ NMR is more suitable than XRC for some proteins 
* Despite these differences, both NMR and XRC continue to be used for protein structure determination – idea is to try both and see which method works more easily for the protein 

## XRC vs Cryo-EM 
![[image16.png]]
Reproduced from Wang & Wang (2016) 

| XRC                                                                                                                                                                       | Cryo-EM                                                                   |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------- |
| Slower – need to optimise protein for crystallisation, screen for crystallisation conditions, grow crystals                                                               | Faster – only few hours prep and data acquisition needed                  |
| May not always be representative as protein is forced into highly ordered conformation of crystal; protein may be modified to allow for crystallisation; radiation damage | No crystallisation; Cryo-ET images in situ                                |
| Not all proteins can be crystallised, e.g. fibrous proteins, disordered proteins, membrane proteins                                                                       | Can image membrane proteins, disordered proteins, fibrous proteins        |
| Difficult to obtain different conformational states                                                                                                                       | Higher throughput to acquire structures of multiple conformational states |
| Higher resolution, less than 1Å                                                                                                                                           | Lower resolution generally (3-4Å), but is improving                       |
| Metal ions can be localised using metal anomalous diffraction                                                                                                             | No good method for identifying metal ions                                 |
| No minimum size                                                                                                                                                           | Minimum size of ~150 kDa                                                  |
| High throughput drug discovery                                                                                                                                            | Lower throughput for drug discovery                                       | 

| NMR                                                                  | Cryo-EM                         |
| -------------------------------------------------------------------- | ------------------------------- |
| Can capture higher energy, transient structures with short lifetimes | Only static structures          |
| Can measure transition rates between conformational states           | Cannot measure transition rates |
| Can capture structural changes at a wide range of timescales         |                                 |
| Can study proteins at physiological temperature                      | Proteins vitrified in ice       | 

## Combining methods 
-  past studies have docked high resolution crystallographic or NMR structures into low resolution cryo-EM maps to obtain a detailed overall structure, and cryo-EM structures have also been used to solve the phase problem

# Other structural methods 
* Single-molecule FRET
* Machine learning approaches. 

## Atomic force microscopy 
- A high resolution scanning probe microscopy technique
	- Cantilever with a sharp tip (probe) scans the surface of the sample, interactions between the tip and sample surface deflect the cantilever, and cantilever deflection is measured using the reflection of a laser. 
- Allows for single molecule detection to measure individual molecular properties (compare with bulk methods that measure average properties) 
- AFM can operate in scanning mode and in functionalised imaging 
	- Scanning mode – for topography and imaging of structures
		- Determining the oligomeric states of different rhodopsin species. 
			- E.g. Bovine rhodopsin is a dimer, while bacteriorhopdsin is a trimer 
			- E.g. oligomerisation states of VDAC-1 
		- Structural variability of membrane proteins 
	- Functionalised imaging – the tip/probe is *functionalised* to monitor different properties of molecules (e.g. charging the tip, adding biomolecules to the tip) to study the relationship between structure and function 
		- Quantitative mapping of membrane electrostatics, i.e. scanning with probes of different charges can reveal electrostatic surface potentials
			- #question what are some applications of this? why would we want to do this? 
		- Single-molecule force spectroscopy – the cantilever tip with the molecule attached is slowly withdrawn to determine the force required to pull a molecule from its environment
			- #question don't get what the point of this is? 

### Advantages
- Conditions are close to native – no labelling, staining, or special buffers 
#comment should elaborate on this more. 

## Electron paramagnetic resonance (EPR) with SDSL 
- Similar idea to NMR, except that it excites <u>electron</u> spin state transitions and requires unpaired electrons in the molecule 
- Best suited in combination with site-directed spin labelling (SDSL) where the unpaired electron is introduced in the form of a nitroxide spin label at a natural or engineered cysteine site 

### Applications 
- Distance measurements – if we have two sites with a spin label, measure the resonance between them (i.e. double electron-electron resonance or DEER)
- Measuring the intrinsic flexibility of domains (i.e. dynamics) via distance distribution analysis of DEER data 
- Establish orientation of integral membrane proteins within membranes 
	- Hyperfine coupling depends on orientation 
	- Can determine orientation of the protein by changing the membrane orientation, then recording the spectrum for sequential amino acids with a spin label 

## Machine learning approaches 
- E.g. AlphaFold 

#experimental_evidence 