**What methods can be used to study single molecules in biology? Using examples, outline some of the advantages of such approaches.**
Refer to: [[VeigelSchmidt_2011]]

# Introduction 
- Why do we want to study single molecules 

# Localisation and quantification 
## Super-resolution microscopy
- STORM 
- PALM 
- AFM 
	- Traffic jams in cellulase on cellulose – Igarashi et al (2011)  «Trichoderma reesei cellobiohydrolase I (TrCel7A) molecules were observed to slide unidirectionally along the crystalline cellulose surface but at one point exhibited collective halting analogous to a traffic jam. 
- CoSMoS – colocalisation single molecule spectroscopy 
- TEM 
- Airyscan confocal microscopy e.g. Wightman (2023) movement of cellulose synthase 

### Advantages 
- Can take videos 

### Disadvantages 
- Need tagging of molecules. Could use fluorescent proteins tags, but they take time to fold and are usually less stable than chemical dyes. Could therefore use self-labelling tags such as HaloTag or SnapTag which can self-label with stable and bright fluorophores such as Alexa Fluorphores. For RNA can use the MS2-MBP system.

## Single molecule fluorescence 
- smFRET
	- How does FRET work? 
		- In FRET measurements, the extent of non-radiative energy transfer from a donor fluorophore to an acceptor fluorophore reports the distance between the two fluorophores; as the distance between the fluorophores increases, the less efficient the energy transfer is. 
	- For single molecule detection, ideal to use TIRF which only images surface, reducing background fluorescence 
	- Three fluorophores could even be used for more complex motion
		- #experimental_evidence Three-color smFRET used to detect correlated motions of a Holliday junction 
	- Optical tweezers could be used along with smFRET to measure how molecules change in conformation in response to force applied by the tweezers 
		- #experimental_evidence Tarsa et al (2007) combined optical tweezers with smFRET to study the opening and closing of a DNA hairpin. The hairpin is open and closed by the optical tweezers, and this structural change is monitored by changes in FRET. ![[Pasted image 20230528212215.png|250]]
	- Advantages 
		- Can provide anisotropic data
		- Very widespread, so likely to be available 
		- Provides real-time quantitative information
		- Monitor distance changes at molecular level 
	- Disadvantages
		- Low signal-to-noise ratio 
		- Fluorophores can be affected by local environment 
		- Time resolution is limited by frame rate of the CCD camera (best case usually = 1 ms)
		- Absolute distance measurement is challenging because fluorescence and energy transfer also depends on environment, orientation of dyes. But relative distances are ok. Accuracy of absolute measurements could be improved by using standards/controls, where the FRET between dyes of known distance is measured. ,
- smFISH
	- Quantification and localisation 
	- Multiple short oligos are bound to the same transcript.  
	- #experimental_evidence Schreur & Kortekaas used smFISH to study the spatial and temporal distribution of RNA genome segments in the Rift Valley Fever virus throughout its replication cycle. Probes were designed for the S, M, and L segments of the genome. 
	- Sensitive – "Binding of multiple oligos to the same transcript yields a bright spot, indicative of a single mRNA transcript. Since mis-bound probes are unlikely to co-localize, this method effectively reduces false-positive signal from non-specific probe binding.”
	- Small oligo size allows probes to penetrate target tissue efficiently, so that even low-abundance transcripts can be detected 

# Structural 
## Cryo-ET 
- Takes sequential pictures of a single molecule that is rotated on an axis 
- Advantages
	- Can visualise proteins in the endogenous environment
	- Can be done in vivo eg. AcrAB-TolC

## Single molecule cryo-EM 

## Single molecule X-ray diffraction 
- E.g. with XFEL 

# Mechanical/physical properties 
- Patch clamp for ion channels -> potential of a single channel 
- Optical tweezers
- Magnetic tweezers
- AFM 

To provide insight into mechanical properties of individual molecules 
