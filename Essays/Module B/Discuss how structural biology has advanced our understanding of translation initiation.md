**Discuss how structural biology has advanced our understanding of translation initiation.** 
From James Stowell: 
- Advantages and limitations of structural biology 
- Complementary techniques 

# Introduction 
- Translation initiation involves the assembly/disassembly of numerous transient/intermediate complexes involving over a dozen initiation factors 
- This culminates in the accommodation of the start codon, marking the beginning of an ORF
- Structural biology has revealed how each component of the translation initiation complex moves and interacts with each other, thus shedding some light onto their functions 

# Context 
- Translation initiation = Defined as the assembly of elongation-permissive 80S ribosomes from post-termination complexes, whereby the start codon is base-paired to the anti-codon of the Met-tRNA positioned in the P site 
- Initiation is the rate limiting step of translation 
- Brief description of process 
- Structural determination of 3D structure by NMR, XRC, and cryo-EM provides information about protein interactions, catalytic sites, protein conformational changes

# Steps in translation initiation 
Refer to notes... 
(from group discussion)

| #   | Step                                                                                                                                                                                                                                                                                                                                                                                                   |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 1)  | Ribosome recycling by ABCE1, eIF1, 1A and 3                                                                                                                                                                                                                                                                                                                                                            |
| 2)  | EIF-2-TC formation                                                                                                                                                                                                                                                                                                                                                                                     |
| 3)  | The 40S subunit binds to eIF1, 1A, 3 and then the ternary complex to form the 43S PIC                                                                                                                                                                                                                                                                                                                  |
| 4)  | mRNA activation by eIF4F binding to the cap, and the helicase activity of eIF4F (stimulated by eIF4B) unwinds local cap-proximal mRNA secondary structure (unwinding requires ATP hydrolysis)                                                                                                                                                                                                          |
| a.  | 40S subunits cannot bind ʻnakedʼ mRNA, unless the 5ʼUTR is unstructured (e.g.(CAA)19)                                                                                                                                                                                                                                                                                                                  |
| 5)  | This allows the 43S to bind the 5ʼ end of mRNA (coupled with direct recruitment e.g. eIF4F-eIF3 interactions)                                                                                                                                                                                                                                                                                          | 
| 6)  | 43S complex scans the 5ʼUTR (again with ATP hydrolysis) until the anticodon of Met-tRNAi interacts with the initiator AUG codon, usually the cap-proximal AUG (selection of correct AUG is vital), formation of the 48S initiation complex which switches the scanning complex to a closed conformation and leads to displacement of eIF1 to allow eIF-5 mediated hydrolysis of eIF-GTP and Pi release |
| 7)  | eIF5 triggers GTP hydrolysis and release of eIF2-GDP, as hydrolysis reduces eIF2 affinity for Met-tRNAi.                                                                                                                                                                                                                                                                                               |
| 8)  | eIF5B (which has a ribosome dependent GTPase activity) catalyzes 60S subunit joining to the 48S  complex and all other eIFs supposedly dissociate, leaving an 80S ribosome at the AUG in the P site, ready for the start of elongation                                                                                                                                                                 |
| a.  | GTP hydrolysis by eIF5B, release of eIF1A and eIF5B from assembles elongation-competent 80S ribosomes                                                                                                                                                                                                                                                                                                  |

# Role of structural biology techniques 
Note: I don't personally think this is very relevant but have included here for reference. 
## Cryo-EM 
- involves sample fixation by cryo vitrification and imaging by transmission electron microscopy + computational analyses
	- High resolution, fast, good for large complexes as bigger atoms are easier to image with X-ray crystallography
	- Fast -> important for conformational changes 
	- Natural environment due to capture in vitrified liquid 
- Particularly useful for elucidating ribosomal structure 
	- Large size, globular shape, high RNA content leads to high contrast
	- Also maintains native activity and functional state of samples such as PTMs
	- Issue with flexible regions

## XRC 
- X-ray crytallography 
	- Sample is crystallized + X-ray/high-energy photons shot at the sample, whereby detector measures the angles and intensities of the scattered beam
	- Good for high resolution, limited by crystallization

## NMR 
- NMR 
	- Applies magnetic field to sample containing nuclei with non-zero spin that causes the nuclei to align with the said magnetic field
	- The response of nuclei when they return to original alignment after radiofrequency pulse administration can be measured and is indicative of the chemical environment of those nuclei
		- Useful due to solution state measurements, is non disruptive
		- Provides dynamic information
		- Most limited resolution of these three techniques

# Insights from structural biology 

## Confirm and elucidate structure of ribosome and various IFs

- Cryo-EM for structure of ribosome:
	- 3 major binding sites – A, P, E
	- 18S rRNA associated with the 32 proteins of the SSU, whereas 28S, 5.8S and 5S rRNAs associate with the 47 ribosomal proteins that make up the LSU
	- Eukaryotic ribosomes also contain RNA insertions called expansion segments, the function of which is unclear, and hard to determine structure due to flexibility – probably some eukaryotic-specific function

- Show structural homology with prokaryotic ribosomes
	- Eukaryotic and prokaryotic small ribosomal subunits share a common structural core, whereas the additional eukaryotic regions and 18S rRNA are more located int eh periphery

- Structure of initiation factors + where they bind
	- EIF3 is particular complex – 13 subunits
		- EIF3 binds to solvent face 40S subunit, whereas the carboxy-terminal domain of eIF3j is located in the mRNA-binding channel
		- Anti-association function: N-terminal end of eIF3c observed to interfere with intersubunit bridge B4, between rpL30e and rpL13e
		- Stabilizing eIF2-TC binding to 40S: contact between eIF3D with eIF2a-D1 domain
	- EIF2C-TC
		- CCA end of tRNA interacts with eIF2y domain II, and also its elbow domain with D1 and D2 domains of eIF2a
		- GTP interacts with G domain of eIF2y
		- With 40S ribosome:
			- Met-tRNAi anticodon stem-loop is inserted into the P site
			- EIF2 interactions are unclear
	- Multiple translation initiation factors have been solved by NMR, the dynamic nature of NMR has also allowed the effect of protein-protein interactions to be elucidated
	- The ribosome has also been shown to be crystallizable despite its huge size, allowing for high-resolution x-ray crystallography images to be produced:
		- Although this is limited for dynamic interactions, but the entire 48PIC should be visible by this method
		- 70S subunit in T. thermophilus by Cate et al 199
		- 30S subunits by Clemons et al 1999
- For more detail see Querido 2020 et al
	- Reconstituted human 48S initiation complex 
	- Single particle analysis Cryo-TEM with ATP-y-S with mRNA without a start site to capture 48S subunit at pathway intermediate after mRNA recruitment, but before accommodation
-	The m7GpppG cap of mRNA binds to eIF4E by stacking between two critical Tryptophan residues (W56 and W102)

## Order of binding of initiation factors
- Can be done in in vitro re-constitution assays seen through cryo-EM
- Hussain et al 2016
	- Involved use of 11 single-particle cryo-electron microscopy reconsttructions of complex with initiator tRNA, 30S subunit mRNA, and IFs 1-3
	- Bacteria require three IFs
		- IF1 – binds 30S A site
		- IF2 – GTPase that recruits formylmethionyl-tRNA
		- IF3 – role in fidelity of tRNA selection and start codon
	- Binding of ribosomes generally occurs with base-pairing of mRNA Shine-Dalgarno sequence with anti-Shine Dalgarno sequence on 16S rRNA
	- Order and function of IFs are further clarified in this study:
		- mRNA binds prior to tRNA
		- CTD of IF3 initially clashes with P-site tRNA, anchored by IF1
		- CTD of IF3 can interact with codon in the P-site, possibly for role in identifying and stabilizing a good start codon
		- When tRNA first binds it is incompletely accommodated for fidelity checks
		- Conformationally rotated state may distort 30S-tRNA interactions such that only the correct base-pairing is sufficiently stable
		- CTD of IF3 can only be moved by energy provided by perfect codon:anticodon duplex, along with being pulled by IF3 NTD which must bind with sufficient affinity to the elbow of the tRNA

## Large scale conformational changes occurring during initiation 
- There are various large scale conformational changes that occur during initiation that otherwise would not be visible at the level of sequence abstraction
- Hussain et al already illustrates many conformational changes occurring during translation initiation = during accommodation, IF3 movements facilitate this process
	- Large-scale conformational changes such as swiveling of the ribosomal head are both present in eukaryotic/prokaryotic initiation
	- eIF1 and eIF1A together induce a conformational change in the 40S subunit that opens the mRNA binding channel
- Codon recognition as an example: results in a series of conformational changes in the ribosome, tRNA and EF-Tu in prokaryotes (EF-Tu equivalent is a-subunit of EF-1a) (**Note: I feel that this part may be straying from the focus of the question, which is initiation.**)
	- In the ribosome, codon recognition results in CC from gain in free energy from ribosome and codon:anticodon interaction
		- Large scale closure of the 30S subunit which disrupts the S4-S5 interface and additional contacts involving S12
			- Critical movement, when facilitated results in an error-prone phenotype, whereas if closure is made more difficult -> hyperaccurate 
	- G530 (16S rRNA) acts as a latch that fastens the codon-anticodon helix into the decoding centre, bringing the 530 loop of the 30S shoulder towards the body, resulting in domain closure
	- For tRNA to bind to the ribosome it adopts bent A/T state formation from a straight tRNA binding in the TC
		- Involves structurally:
			- Distortion of the anticodon stem loop (ASL)
			- Movement of D-stem away from acceptor/T-stem stack
			- Mutations that affect these movements will profoundly affect decoding
		-  Each native tRNA is hypothesized to adopt unique conformation when delivered to the ribosome to allow accurate decoding
	- EFTu, upon codon recognition, is pulled into the factor binding site and its domains re-arrange
		- Initial selection is achieved by separating the EF-TU domain 1 from the 50S SRL until the tRNA is recognized in the 30S decoding centre
- These conformational changes are critical for inducing GTPase activation of EF-Tu, and EF-Tu dissociation such that tRNA can accommodate
	- Accommodation = the large movement of the A-site acceptor stem on the 50S subunit following dissociation of EF-Tu-GDP

## Regulation of transcription initiation
- Structural elucidation of 4E-BP mechanism and how this contributes to 4E binding 
- E.g. phosphorylation regulation of 4E-BP 

# Conclusion 
- Structural studies are useful in understanding the sequential steps involved in translation, the structures of the multiple components involved in the process and the structural effects of these factors binding 
- Cryo-EM is the main technique involved in ribosome studies due to speed and high resolution, as well as relatively natural environment
	- But cryo-EM is static -> need information about mechanisms, kinetics as well 
- They can also be very useful for generating drugs – especially for those involved in structural studies of prokaryotic for antibiotics, but also eukaryotic in order for anti-tumor, parasitic or inflammatory therapies
	- Structure-based drug design uses all three of these methods
- Initiation however remains a dynamic process, also requires techniques to study kinetic proofreading for example
	- Idea that preferential selection of the cognate tRNA will arise from rapid dissociation of near cognate/noncogate tRNAs before and after GTP hydrolysis
	- The use of successive selection steps separated by irreversible energy consumption increases selectivity, but just at an increased energetic cost
	- Require improvement in high-resolution microscopy techniques, FRET is also used to study these interactions

