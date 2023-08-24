**Discuss how the structures of dynamic proteins and assemblies can be studied. What functional insights can be gained from such studies?**

All proteins and protein assemblies should be considered dynamic 
* Polymers with many degrees of freedom 
* We are generally interested in how dynamics contribute to protein function 
    * Which motions are functionally important? Not all are. 
* To understand dynamics, need to obtain structures of different conformational states, transitions between conformational states, kinetic data, thermodynamic data 
* Choice of technique depends on particular research question / context / type of dynamics under investigation 
    * Time resolution
        * µs to ms: induced fit conformational change 
    * Spatial resolution 
    * Protein size
    * Sample requirements 
        * Labelling
        * Crystallisation 
    * Access to instrumentation, resources 

Discuss – advantages, limitations, context. How do different studies complement each other and how can they be used together? 

For each technique, provide 
* Principle
* Process
* Experimental evidence 
* What particular 

# Biochemical
- FRET studies 
- Atomic force microscopy 
- Optical tweezers (?) 

# Structural 
* Structural 

## NMR 

NMR is considered to be the gold standard for dynamics techniques since it can investigate protein dynamics at a wide range of timescales 

### How NMR works 
- There are many NMR techniques, how to choose the technique to use for the study?  
- Depends on timescale 
	- Most biological processes, e.g. folding and conformational change, occurs on µs to ms timescale 
- Membranes 
	- Solid state NMR 

### Applications 
- High energy states – Proteins fluctuate between various conformations. NMR has been used to show the conformational selection model, wherein a ligand selectively binds to one of the conformations sampled in a solution; rather than inducing structural change, it redistributes the relative populations of conformations. This is because these different populations are seen in both ligand-free and ligand-bound conditions, just in different abundances 
	- E.g. Nitrogen regulatory protein C is made up of two components, a receiver domain and an output domain. The receiver domain can be phosphorylated at an Asp residue. Ntr-Cr changes structure when bound to ligand. NMR studies showed that the structural change is due to redistribution of existing conformations; the unphosphorylated protein samples the active conformation, and the Asp residue is more readily phosphorylated in this conformation. 
	- E.g. DHFR – Exists in 5 different ground states that are linked in a catalytic cycle. NMR studies showed that these ground states exchanges with the ground state preceding it and the one following it. The enzyme is primed for the next step of the cycle by sampling the corresponding state. There are also microscopic conformational changes linking the 5 ground states 
- Elucidating rate-limiting conformational dynamics
	- The rate of catalysis of some enzymes is limited by the rate of conformational change (these are slower enzymes that are not diffusion limited) 
	- Show how conformational changes contribute to catalysis in enzymes 
	- E.g. Adk – catalyses interconversion of AMP and ATP into two ADP molecules. 15N relaxation dispersion experiments (ps-ns timescale!) with Adk showed that in the presence of the bound substrate, the enzyme exhibited opening and closing dynamics. As the microscopic rate constants of domain opening matched the catalytic turnover numbers of the enzyme, Adk may be rate limited by the speed at which it can open to release the products. This was supported by the fact that a thermophilic variant of the enzyme has both a slower catalytic turnover and conformational dynamics than the mesophilic variant. 
- Molecular recognition 
	- **Protein folding during ligand interaction**. Some segments of protein can fold upon recognition of a ligand. 
		- E.g. Trp RNA-binding attenuation protein (TRAP) and Trp can bind; Binding of Trp induces folding, as seen from quantification of chemical shift changes and line-broadening in TRAP when Trp is added 
	- **Protein conformational entropy.** Akke et al used 15N and 2H spin relaxation to discover that protein conformational fluctuations on ps to ns time scale in Galectin-3 are amplified in ligand bound state compared to unbound state, suggesting a contribution of conformational entropy to ligand binding 
	- **Encounter complexes.** Encounter complexes are ensembles of conformations where two proteins sample each other’s surfaces. These conformations are transient, so suitable for NMR study. E.g. Cyt C and ct C peroxidase. 

### Advantages
- Can be done at physiological conditions (cf XRC and cryo-EM) 
- Wide range of timescales possible to detect different kinds of conformational changes
- Can even be done in vivo 
	- E.g. Selenko and colleagues were able to use NMR to quantify phosphorylation and dephosphorylation of short protein segments in cell lysates 

### Limitations 
- Low throughput, slower 
- Lower resolution in general 
	- Large proteins (>30 kDa) have particularly lower resolution; difficult to separate out peaks 
	- Resolution problem might be overcome by combining NMR data with data from XRC which can often provide higher resolution structures; the static structure could be used as a reference for peak assignment  
	- use time resolved XRC, time resolved cryo EM
	- TROSY, deuteration can help somewhat  

## Time-resolved XRC and XFEL 
- In time resolved XRC, the reaction has to be synchronised across all the active sites in the crystal 
	- Photoinitiation – e.g. Catalytic cycle of fatty acid photodecarboxylase  was characterised with time resolved XFEL 
	- Diffusion – rapidly mix substrate into enzyme microcrystals, and deliver mixture to X-ray 
		- E.g. XFEL experiments with beta-lactamase indicated the presence of a ring-opened catalytic intermediate 
		- Suitable for enzymes that uses gases as a substrate (e.g. O2) since these diffuse quickly -> better synchronisation 
- Electron density maps obtained at different times can be compared to observe the dynamic changes 
	- Analysis is usually done with difference electron density maps (isomorphous difference maps) 
- Have been used to characterise transient enzyme intermediates 
	- Time resolved XFEL investigation of isocyanide hydratase (ICH) showed that catalysis activates motions in ICH that progress the enzyme along the reaction 

### Advantages 
- Serial femtosecond crystallography using XFEL has excellent time resolution, allowing for observation of conformational changes that last femtoseconds to microseconds. 
- Advancements in room temperature data collection for XRC can allow for a wider range of conformations to be investigated, in contrast to conventional methods where crystals have to be cryocooled to reduce radiation damage 
- Pulsed XRC with Laue diffraction can resolve structures to high resolution at short timescales 

### Limitation 
- Need crystal (for XRC) 
- Time resolved XRC has lower time resolution, and accessible conformational states are still limited to those that can be crystallised (so no very transient states) 
- But XFEL has limited beamtime availability, so poor access; applications have so far been limited to light-triggered reactions
- Isomorphous difference maps can be difficult to analyse – in maps where many chemical groups are moving, can be difficult to pinpoint the origin of electron density peaks on the map 
	- Combining data from other techniques – regular XRC e.g. Time resolved XFEL experiment with ICH, could not determine origin of some positive difference peaks without prior XRC structures of the enzyme that showed which parts of the enzyme had moved 
- XFEL experiments done at rt with microcrystals reduces resolution 

## Cryo-EM 
- Temperature-dependent cryo-EM 
	- Temperature induced conformational change is not a simple two-step process, but rather is continuous; so induced fit conformational change is continuous too 
		- E.g.  _Sulfolobus solfataricus_ ketol-acid reductoisomerase N subdomain in complex with inhibitor CPD, coenzyme NADH. Temperature induced conformational changes was continuous. 
        * To understand mechanism of allosteric regulation, need to solve structures of the apo enzyme and enzyme bound with allosteric regulator 
            * XRC can sometimes capture conformations of both, but sometimes crystals not readily obtainable for both 
            * E.g. Subramaniam and colleagues resolved conformers of p97 hexameric AAA+ ATPase both with substrate and with a small molecule allosteric inhibitor with 2.4Å resolution 
- Role of dynamics in catalysis 
	- Cryo-Em used to understand how DNA recombinases catalyse strand exchange during homologous recombination 
		- E.g. Yang et al – Used cryo EM to observe 9 molecules of E. coli RecA binding to different parts of a triplex DNA structure. They created a model for protein dynamics of RecA based on these structures to show how RecA searches for dsDNA that matches the ssDNA. 

### Advantages 
- Transient reaction intermediates can be captured since time consuming crystallisation process not necessary – grid preparation only takes a few minutes before plunge freezing
- Don’t need crystal 
- Membrane ok 
	- GPCRs 

### Limitation
- Also lower time resolution than NMR 
	- Some transient intermediates may have to be modified to increase the duration that the protein stays in that conformation 
		- E.g. Kang et al had to use unnatural amino acid substitutions to slow down dissociation of alpha and beta subunits in a class I ribonucleotide reductase. This transient association is involved in a radical transfer pathway that had not been previously determined structurally 
	- Have to use a system that allows for rapid sample blotting, e.g. microfluidics – instrumentation availability 
	- Deep learning methods combined with cryo-EM maps have allowed for generation of protein dynamics information (e.g. Matsumoto et al used this method to generate info similar to that generated by MD simulations at an atomic and residue level) 

## Mass spectrometry 
- HDX-MS can reveal dynamics on the minute to ms timescale
	- HDX measures rate of exchange between hydrogen and deuterium 
	- Hydrogens in backbone NH and side chain NH, OH, SH can exchange 
	- H with low solvent accessibility or involved in H bonding undergo exchange more slowly 
* Time resolution is limited by speed of sample introduction 
    * Manual sampling – >1 min 
    * Automated robotic sampling – 30 s 
    * Flow injection – ms timescale, shortest 10 ms  
* Pulse label HDX can achieve ms time resolution
* Protein folding 
	* Tightly folded protein structures exchange more slowly than those that are disordered  
	* Continuous flow: Conformational dynamics of protein population in equilibrium. Native protein exposed to D2O, and deuterium incorporation monitored over time with MS 
	* Pulse labelling: for short folding intermediates. Target protein denatured, refolding triggered, and protein exposed to brief (millisecond long) deuterium pulse (quenched by rapid acidification). Vary time interval between refolding trigger and pulse, and do MS for each time interval 
		* Can show different relative populations, since different folding intermediates have different deuterium uptake. Longer time interval -> more folding can be done 
	* Covalent labelling of solution-accessible surfaces e.g. using hydroxyl radicals 
		* Refolding of acid-denatured cytochrome C was followed by exposing protein to HR pulse, which is only 1 µs -> greater time resolution. Covalently bound oxygen adducts can be detected by MS 
* HDX + peptide mapping of deuterium exchange pinpointed features that undergo structural rearrangement during ligand binding 
    * E.g. Study of cGMP-dependent protein kinase using HDX-MS and peptide mapping showed that when PKG binds to cGMP, autoinhibitory domain disengages from catalytic domain so that it can bind to substrates 
- Enzyme dynamics during catalysis
	- E.g. Using quench flow microreactor and MS, found that chymotrypsin is transiently acetylated on serine during p-NPA hydrolysis 
- Changes in quaternary structure
	- Subunit exchange  between oligomers 
		- E.g. α-crystallins have two isoforms, A- crystallin and B-crystallin, that can homodimerise or heterodimerise, but prefer the latter. As they have different masses, formation of heterodimers can be tracked by doing MS and monitoring the change in mass over time. Found that exchange between homo and heterodimers was relatively rapid and equilibrium reached after 30 min. 
	- Sequence and timescale of complex assembly – MS can separate complexes into subunits 
		- Follow biogenesis in vivo in real time 
			- Monitor changes in intensity of monomers, intermediates, and fully assembled complex
		- Can also use IM-MS to separate the different assembly intermediates 
		- Alternatively, follow disassembly of an isolated protein complex in vitro 
		- E.g. Assembly pathway of 20S proteasome from _Rhodococcus erythropolis_ was determined using MS 
			- α, β subunits were mixed, and assembly monitored by time resolved MS. This showed that the assembly is initiated first by a/b-heterodimer formation, followed by a half-proteasome (a7b7) and then the fully assembled proteasome (a14b14) 
	- Ion mobility-mass spectrometry (IM-MS) – after ionisation, ions are first separated according to their mobility in a gas phase, then introduced into MS. Drift time refers to the time taken for the ion to pass through  drift tube containing the gas phase, with smaller ions drifting faster and so having a shorter drift time. 
		- E.g. b2-microglobulin (b2) fibril transient oligomers could be separated and detected using this method. 

### Limitations 
- Only used in somewhat niche applications
- Limited timescale of ms to minutes 

## Integrated methods 
- Usually a more “static” method is used with NMR. 
- XRC and NMR – NMR can be used to understand protein dynamics, especially at ps-ns timescale for bond fluctuations. On the other hand, XRC provides high resolution data of atomic coordinates. 
	- E.g. Fenwick et al (2013) used both XRC and NMR to describe the conformations of dihydrofolate reductase (DHFR) 
- CryoEM and NMR – CryoEM structures often do not have atomic level resolution, while NMR is restricted to small (&lt;30 kDa proteins); integrating these methods might overcome the limitations 
	- E.g. Gauto et al (2019) used an integrated NMR and cryo-EM approach to obtain an atomic resolution structure of a 468 kDa dodecameric aminopeptidase, TET2. They used magic angle spinning NMR assignments of the 39 kDa-large subunits, which were then mapped onto a 4.1 Å cryo-EM map, guided by NMR-derived distance restraints. 
	- The advantage of this approach is that crystallisation is not necessary

## Computational 
- Computational techniques help to integrate different structural snapshots as obtained by cryo-EM, XRC into a coherent picture by mapping the dynamic process between each snapshot. 
- Molecular dynamics – simulation method for understanding dynamics at an atomic level 
	- Limitation: Large-scale conformational changes rarely observed with MD (takes too long/computationally intensive) 
	- E.g. Mhashal et al (2022) used “regular” MD simulations and coarse-grained MD (MARTINI) a to investigate the domain movements of bacterial ribose-binding protein (RBP). Compared to MD, MARTINI simulations predicted that there is a wider sampling between the open and intermediate states of RBP across the domain twist component. 
        * Coarse grained approaches – lower resolution, “larger” motions e.g. domain motions, structural rearrangements. Atoms in the protein are grouped together and moved as a group 
            * E.g. Coarse-grained normal mode analysis 
            * coarse-grained MD e.g. MARTINI – side chain atoms are grouped onto beads defined by property (polar nonpolar, charged) 
        * Machine learning has also been employed for simulations
        * However, analysing the simulations can be difficult – how do the conformational changes observed relate to experimental data? 
            * Machine learning extraction of data 

# Functional insights 

(Have functional insights at different timescales, spatial scales) 

## Translation fidelity 
* Control of translation fidelity 
    * CryoEM to study sequence of ribosome conformational changes during translation that are important to decoding 
    * Processivity – movement of 1 codon at a time -> prevent frameshifting (was this structural or found by FRET…) 

## Enzyme catalysis 
* How enzymes catalyse their reactions
    * Directed evolution and engineering enzymes 
    * Can use example of CAZymes (hehe) 
        * Sequence of conformational changes important to specificity
    * Conformational selection 

## Signalling 
* Signalling pathways and regulation – G proteins 
    * G proteins undergo conformational changes (e.g. in switch regions) to change their activation state 
* Intrinsically disordered proteins 
* Protein folding pathways 
* Protein interactions -> e.g. translation fidelity – EF-Tu and ribosome 
    * Conformational changes occur during protein interactions 

# Synthesis 

* There is a rich amount of functional information to be gained from studying protein dynamics 
* Different techniques have their place – broadly, could say that time-resolved XRC and Cryo-EM can provide a sequence of static snapshots, with finer details and high energy states filled in by NMR, and transitions between states can be visualised with MD  ? 
* Sometimes multiple techniques could provide similar resolution (time/spatially) and the choice depends on operator skill, accessibility to instrumentation, and/or ease of data analysis 
* Will also be complemented by single molecule methods, such as FRET and fluorescence spectroscopy, which are not discussed here 
* Understanding the relationship between protein dynamics and function has important implications for protein engineering, drug design, and elucidating pathophysiological pathways (HAHA) 