# Principle
* When an X-ray hits the protein, the X-rays scatter in all directions, and these scattered beams mostly cancel out, while in some direction they reinforce, creating a _diffracted beam_
* A _diffraction pattern_ is the set of diffraction maxima observed for a particular crystal orientation and appears as a series of sharp spots that reflects the structural arrangement of the crystal 
* Bragg’s Law can be used to deduce the original structure of the crystal from the diffraction pattern, but requires two pieces of information – 1) the amplitude (intensity) of the diffracted beams, and 2) the phases of the diffracted beams 
* However, while a diffraction pattern can tell us the amplitude of the beams (which is the intensity of the diffracted spots), the phase angle is lost – **phase problem** 
    * Phase information can be recovered in a variety of ways, either experimentally or computationally, e.g. SIR/MIR, SAD/MAD, SIRAS/MIRAS, or molecular replacement
* Intensity and phase information can then be reconstructed and Fourier transformed computationally to generate a virtual structure for interpretation

# Overall process
Steps 1-5 covered in [01 Gene Cloning and Manipulation](https://docs.google.com/document/u/1/d/1_KzBA06XnX2pzt3GCw0K6m4ZZP4yFnJXEQsQq3gmExs/edit). 

## Obtaining a purified protein 
1. Obtain DNA sequence for the protein from databases 
2. Analyse sequence
    1. For homology to to other proteins 
    2. Domains, secondary structures 
3. Synthesize expression construct – clone DNA fragment of target protein into expression vector 
    3. Select vector with strong promoter
    4. May include fusion partners for purification (e.g. His-tag, GST) 
4. Express protein in a recombinant host (typically _E. coli_, but yeast, mammalian cells, insect cells can also be used) 
5. Purify protein to homogeneity (various chromatographic methods) 
    5. Protein has to be conformationally pure so that it can form a crystal 

## Crystallize the protein 
6. Crystallize protein. 

Aim is to find optimal chemical conditions for obtaining well-diffracting crystals – different proteins have different optimal conditions. Protein crystals grow when proteins are precipitated out from supersaturated salt solutions (i.e. “salted out”) 

7. Mix pure protein with ligands or co-factors, if present (optional) 
8. Screen for initial crystal hits i.e. screen for crystallization in many different chemical conditions, using either batch crystallization or vapor diffusion crystallization 
    6. Typical chemicals used – (NH<sub>4</sub>)<sub>2</sub>SO<sub>4</sub>, PEGs, small organics, other salts
    7. Water has to be removed to make protein more and more concentrated until it forms a crystal 
    8. The protein concentration and crystallising agent concentration has to be just right for the protein to start nucleation 
![[image7 1.png|400]]
9. Inspect screens microscopically 
10. Reproduce the hits and refine crystallization conditions (reiterate) 
    9. This process can be automated with crystallisation robots 
11. Obtain single, large enough crystals that have good diffraction

### Batch crystallisation 
* Simplest method for crystallisation
* An oil layer prevents drop from drying out
* Mix different volumes of protein and precipitant solution and hope u reach nucleation phase 
![[image17.png|225]]

### Vapour diffusion crystallisation
* In each well, put crystallisation buffer
* Put protein solution on cover slip and flip it over the well 
* Over time, protein in droplet becomes more concentrated. Water evaporates and goes into well to concentrate protein
* Gentler than batch crystallisation 
![[image4 1.png|450]]

## Obtain diffraction data
12. Cool single crystals in vitreous ice to 100K 
    10. High intensity X-rays can cause radiation damage, so cooling helps to minimise the damage 
13. Shoot crystal from multiple angles with highly focused beam of X-rays (i.e. rotate the crystal)
    11. X-ray usually obtained from synchrotron 
14. Collect scattered X-rays with a detector 
15. Merge all diffraction data and extract intensities of the diffraction spots 

## Solve the phase problem
16. Solve the structure by solving the phase problem i.e. fit the diffraction pattern to an electron density map
	1. Use a closely related structure (molecular replacement) –Currently the main method for solving phase problem due to large number of protein structures available from PDB and AlphaFold 
	2. Introduce heavy metals into the protein (multiple isomorphous replacement) or seleno-methionine labelling (multiple anomalous scattering) 
17. After obtaining phases, calculate electron density map from phase and intensity information via a Fourier transform 

## Fitting and analysis 
18. Fit atomic model of the protein to the electron density 
    14. Fit known sequence of protein to match electron density as well as possible 
19. Refine model computationally 
    15. R-factor – measure of agreement between crystal structure created and experimental diffraction data 
    16. The obtained structure can be validated by comparing the phi and psi angles to the Ramachandran plot, since only a restricted range of phi and psi angles are biologically possible 
20. Interpret the structure

## Modifying the protein for X-ray crystallography 
Some proteins are difficult to crystallise in their native conformation and have to be modified to make them easier to crystallise

* Truncating disordered regions 
* Breaking down multisubunit proteins into their constituent subunits 
* Using more stable homologs 
* Mutating the protein to improve stability 
* Create favourable crystal contacts by inserting soluble domains into loops
* Stabilise particular conformational states and create crystal contacts by binding the protein to antibody fragments/nanobodies
    * E.g. Nanobodies are useful for studying GPCR structures as they are mimetic of Gα<sub>s</sub>. In studies of β<sub>1</sub>AR, it stabilises the active state, and thus also study how the active conformation interacts with ligands 
* Stabilise active state by binding protein to a binding partner (fusion partner) 

# XRC Variants
## Time-resolved XRC
* Expose the protein sample to a short pulse of X-ray (e.g. 150 picoseconds) to obtain the structure at a particular timepoint (versus normal XRC which uses a pulse train) 
* Can be used to follow conformational changes in enzymatic reactions 
* E.g. Schotte et al (2003) used time-resolved XRC to obtain the structure of an intermediate in the myoglobin L2F mutant reaction pathway

## X-ray free electron laser (XFEL) 
* The reason protein even need to be crystallised is that if an X-ray hits a single molecule, the intensity of the diffracted beam is to weak to measure, even if synchrotron radiation is used. To increase the signal, use many molecules that are lined up together, which creates measurable signals but only at positions of constructive interference (i.e. diffraction spots) 
* With XFEL, the beam brightness is greatly increased, making it possible to image microcrystals or even single molecules 
* XFEL also reduces radiation damage to crystals 
* #experimental_evidence Seibert et al (2011) used XFEL to determine the structure of a single mimivirus particle 
* Serial femtosecond crystallography (SFX) makes use of XFEL to study enzymatic reactions, protein dynamics 
    * In SFX, “single-shot diffraction images are collected in series from a continuous flow of micro-crystals with random orientation”, and the femtosecond exposure time enables the acquisition of diffraction data with minimal radiation damage 
    * The technique has much higher time resolution than conventional crystallography methods 
    * #experimental_evidence Takehiko et al (2017) used time resolved, serial femtosecond crystallography with XFEL to track the reaction progress of fungal NO reductase 
    * #experimental_evidence Bhowmick et al used serial femtosecond crystallography with XFEL to understand the structural changes that occur in the active site in the oxygen evolving complex during the transition between the S<sub>3</sub> to S<sub>4</sub> to S<sub>0</sub> states. 
* However, synchrotron radiation likely to still be main beam source – XFEL has limited beamtime availability, more involved data processing, and requires large amounts of crystalline material (Garman 2014) 

# Using XRC to study protein dynamics
* If substrate-mimic ligands can be found, crystal structures can provide snapshots of an enzyme in different stages of its catalytic cycle 
* Can also use [[A2 X-ray crystallography#X-ray free electron laser (XFEL)|XFEL]]
* Problems: 
    * No information is provided about the rate of transition between states 
    * Dynamic loop regions show little electron density and do not show up on electron density maps, and yet are often the sites of most interest as they are often involved in enzyme function (e.g. in active site) 
    * Structures determined at 100K after crystal freezing can possess altered conformations 

# Examples of X-ray crystallography
* #experimental_evidence Prasad et al (1999) – XRC structure of Norwalk virus capsid 
* #experimental_evidence Tilton et al (1991) – XRC structure of ribonuclease A at 9 different temperatures to demonstrate the effect of temperature on structure
* #experimental_evidence Using XRC for drug design 
    * Xchem facility – high throughput screening of crystals with libraries of molecules for rational drug design  

# Advantages and disadvantages of X-ray crystallography 
## Advantages 
* No size limit to the size of the target protein or sample in theory
    * E.g. crystal structures of whole viruses have been determined 
* High resolution, well below 1 angstrom (atomic level resolution) 
	* Detailed information of interactions and ligand binding can be obtained
* The structure of the protein in a crystal is similar to that in solution, because crystals contain large channels of solvent and the proteins contact each other at a few points only.  

## Disadvantages
* The larger the protein, the more difficult it is to solve for the structure 
* Gives a static view of the structure, so cannot show protein dynamics 
* Requires a crystal of the protein which is difficult to obtain 
    * Crystallisation requires a highly homogenous structure, and large losses of protein may have to be incurred to obtain a pure sample
    * Mobile loops, linkers and other structures impede crystallisation and are often removed → possible loss of important information 
    * Multidomain proteins can be difficult to crystallise – can break the protein up into domains then crystallise each domain 

# Membrane XRC 
The advantages and limitations for each technique is similar to non-membrane proteins, with some additional points. 

## Making protein crystals
1. Solubilise membrane protein in detergent micelles 
2. Screen multiple cosolute and concentration conditions 
3. Hanging drop vapour diffusion 

## Improving crystallisation of membrane proteins 
- While hanging drop vapour diffusion is popular and easy to set-up, the quality of crystal hits is often too low for high resolution studies. 
- Strategies for improving crystallisation as in [[A2 X-ray crystallography#Modifying the protein for X-ray crystallography|Modifying protein for XRC]] also apply, but membrane proteins can undergo additional optimisations: 

### Enhance crystal contacts by enlarging soluble domains 
- Adding a protein-specific antibody can enlarge particular domains, and also lock the membrane protein into a particular conformation 
	- E.g. crysallisation of KscA potassium channel 
- Inserting a soluble domain (e.g. T4 lysozyme) in loops or at the termini 
	- E.g. β2-adrenergic receptor with T4 lysozyme fused at N-terminus 

### Reconstitute protein into lipid bilayer phases 
- Bicelle crystallisation (solubilised bilayer)
- Lipidic cubic phase – as described by [[LandauRosenbusch_1996]], consists of a "cube" of lipids which is basically an infinite bilayer. Water-soluble parts of the protein interact with an infinite water conduit system 
![[Pasted image 20221215150345.png|400]]

## Advantages of using XRC for membrane proteins
- Could be used to reveal protein dynamics 
	- E.g. VDAC-1 structure determination – each of the X-ray studies revealed two different conformations for the N-terminal helix, which suggests a possible gating mechanism where the helix moves to open and close the channel 
	- E.g. G proteins – highly dynamic, change conformation upon ligand binding to transmit the stimulus across the bilayer 

## Examples of membrane XRC 
- VDAC1-structure determination – used bicelles (DMPC/CHAPSO), followed by lipidic phase crystallisation 

# Links to other topics 
- Crystal structures of enzymes in complex with substrates can help to understand structural basis for substrate specificity, e.g. [[OsmaniEtAl_2009]], [[CulbertsonEtAl_2018]]
- Structures of [[C2 PTMs and Protein trafficking#Assembly of outer coat proteins Sec13p and Sec31p|outer coat proteins]] shows how it assembles
- Structure of [[C2 PTMs and Protein trafficking#Glycosylation QC system|calreticulin]] shows how it is specific to glycoprotein isoforms with just 1 glucose residue during QC of protein folding in ER lumen 
- Structure of [[C5 Lipid metabolism in plants#Structure of plastidic stearoyl ACP Δ9-desaturase|plastidic stearoyl ACP Δ9-desaturase]] to understand how structure determines substrate specificity of the desaturases 
- [[A8 Machinery of Translation#Structural techniques|Intermediates of elongation cycle]]
- Understand catalytic mechanism of [[B7 Small RNAs#RNAse III enzymes generate small RNAs|Class I RNase III]] 
- Structure of [[C1 ER Targeting and Integration#Structural studies|SecY]], which is a prokaryotic homolog of mammalian Sec61α, part of the Sec61 translocon complex
- [[A8 Machinery of Translation#Structural evidence for proofreading for IleRS|IleRS proofreading]]

 