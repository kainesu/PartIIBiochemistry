# Questions 
- Structural analysis and translation 
	- *==How have structural data of various conformations of elongating ribosomes advanced our understanding of translation?==*
	- *****==What are the outstanding mechanistic questions in understanding the translation of mRNA into protein, and how would you go about solving them?**==***
	- *==Conformational changes occur throughout all stages of translation. Explain the functions of these changes==.*
	- *==Discuss how the ribosome might be considered an allosteric assembly.==*
	- *==Describe the organisation of the prokaryotic ribosome, and the functions of the key structural features==.*
- Fidelity of translation 
	- ==What chemical reactions occur during tRNA charging== and translation elongation, and what are the consequences for the fidelity of the process?
	- *==How does proofreading occur during protein synthesis?==*
		- *==How is fidelity maintained in translating the genetic code?==*
		- *==What mechanisms ensure fidelity at the different steps of translation?==*
		- *==Using examples from protein synthesis, explain the mechanism of proofreading==*
	- ==Why is proofreading in protein translation necessary==, *==and how does it occur?==*
- Principles of translation 
	- ==What do you consider to be the key principles of protein biogenesis? How have experiments provided insights into these principles?==
		- Note: could be both biochemical and structural principles. 
		- Principles: colinear, unambiguous, unidirectional
	- *==Why is protein biogenesis so energetically demanding? What is the experimental evidence for your explanation?==*
	- What aspects of mRNA translation appear most conserved, and why?
- Discuss how small molecules (with a molecular mass of less than 500 Da) interfere with translation and how this interference can be exploited for medical purposes
	- This is asking about antibiotics 
- Are ribozymes bona fide enzymes? Discuss the characteristics that suggest they may have been catalysts in early evolution.

# Structural components of translation 
- Ribosomal subunits can be separated by fractionation (ultracentrifugation + sucrose gradient)

## Ribosome
### 50S
- Binds nascent peptidyl-tRNA 
- Site of peptide bond formation 

### 30S
- binds mRNA 
- codon-dependent tRNA binding 

### E, P, A sites 
- Each of the three sites has different preferences in non-enzymatic binding 
- A site: Phe-tRNA > N-acetylPhe-tRNA (resembles peptidyl-tRNA)> deacylated tRNA
- P site: Deacylated tRNA > N-acetylPhe-tRNA > Phe-tRNA 
- E site: Deacylated tRNA only 
	- #experimental_evidence tRNA filter binding experiments revealed the presence of the E site.  In a tRNA filter binding experiment, radiolabelled tRNA, ribosomes, and mRNA are passed through a column containing a nitrocellulose filter. Ribosomes and bound tRNA stick to the filter, while unbound tRNA pass through. The amount of radioactivity from the filter is proportional to ribosome-tRNA binding. Nierhaus (1981) did tRNA filter binding experiments with aminoacylated tRNA and compared to if the experiment was done with deacylated tRNA. Found that ribosomes bind a maximum of 2 aminoacylated tRNAs, while binding maximum of 3 deacylated tRNAs per ribosome, suggesting that there was a third (E) site that only binds deacylated tRNA 

### Peptide exit channel
- Hydrophilic – "non-stick" (no hydrophobic patches)
- Average diameter of 15Å – can only fold max alpha helices, so any co-translational folding takes place outside of exit channel
- Macrolide antibiotics block near PT/entrance
- Potential translocon/chaperone contacts by exit proteins 

### Evolution of the ribosome
- The ribosome structure becomes increasingly complicated from prokaryotes to eukaryotes to mammals, but there is a conserved core 
![[Pasted image 20221231222434.png|475]]

## rRNA tertiary structure 
- RNA helices are held together by Mg2+, interhelical base pairs, noncanonical pairs/tertiary interactions (especially minor groove interactions with adenines i.e. A-minor motif), protein interactions (e.g. L39 rRNA)

## EF-Tu 
- Domain 1 – nucleotide binding or GTPase domain 
- Domain 2 – Localised adjacent to 30S shoulder upon ribosome binding
- Domain 3 

# Conformational changes that occur during translation 
## Initiation 
### Initiation in prokaryotes
1.  30s interacts with IF3 and IF1 
	1. The N-terminal and C-terminal parts of IF3 align with the E and P sites respectively, which keeps small and large subunit apart until initiator tRNA clicks into P site
	2. IF3 discriminates against elongator tRNAs 
2.  30s/IF1/IF3 complex interacts with mRNA at ribosome binding site (RBS) (aka Shine-Dalgarno sequence) 
3.  IF2 forms a ternary complex with GTP and charged initiator tRNA (i.e. fMet-tRNAf) 
4.  IF2 coordinates binding of 50s subunit 
5.  IF2 hydrolyses GTP and releases all initiation factors to form 70s initiation complex
6.  IF2 recycled by exchanging GDP for GTP 
7.  70s ribosome assembled at RBS with initiator tRNA in P site and empty A site

In bacteria, initiation pathway is not necessarily linear, and order of binding of factors may be flexible (as determined from cryo-EM structures)
- #experimental_evidence [[MilonEtAl_2012]] Determined that **IF3 and IF2** are the first factors to arrive, forming an unstable 30S-IF2-IF3 complex, then IF1 joins to lock the factors in a kinetically stable 30S PIC. fMet-tRNA is recruited to this PIC. Binding of mRNA is independent of the initiation factors and join any time during assembly. They were also able to determine the association/dissociation rate constants for each step. 
	- FRET reporters were introduced onto each initiation factor, fMet-tRNA, and on mRNA. They monitored FRET between ligands in the 30S PIC to determine the order of formation.
	- IFs can bind to 30S independently of each other, but there is likely to be this kinetically favoured route *in vivo*

### Initiation in eukaryotes
- Eukaryotes use many more initiation factors (about a dozen), but IF1, 2 and 3 are the core conserved factors (as eIF1A, eIF5B, eIF1)
- First AUG is identified via **scanning mechanism** from 5' cap 
	- mRNA forms a loop 
	- Downstream mRNA is pulled through the 40S subunit during scanning 
![[Pasted image 20230101212804.png|550]]


## Elongation 
Similar in prokaryotes and eukaryotes, but elongation factors have different names

## General principles 
- Proteins are colinear with mRNA, and synthesised sequentially according to order of triplet codons in mRNA 
- New amino acids are added to the C-terminus of the polypeptide 
	- #experimental_evidence Correspondence between mRNA 3' and protein C-terminus – AAA(A)<sub>n</sub>AAC end-detection shows Asn at C-terminus of poly-Lys 
	- #experimental_evidence Polypeptides accumulate radiolabelled residues at the C-terminus first upon receiving a pulse of radiolabelled amino acids 
- Peptidyl-tRNA held in P site while incoming tRNA decoded in A site, and peptide bond formation occurs with –NH<sub>2</sub> attacking an activated carboxyl, resulting in N to C synthesis 
- #experimental_evidence FRET experiments with donor and acceptor pairs placed on P- and A-site tRNAs show 3 FRET states – a codon recognition state, GTPase activated state and accommodated state

### Recruitment 
1. EF-Tu binds GTP and aa-tRNA to form a ternary complex to deliver the aa-tRNA to the A site 
    1. EF-Tu binding masks aminoacyl group in aa-tRNA → cannot react with peptidyl-tRNA 
2. Recruitment of EF-Tu/GTP/tRNA to the decoding centre at the A site by L7/L12 protein 
	1. Independent of codon/mRNA  
	2. At first, 30S has open conformation, which forces EF-Tu GTPase domain away from the sarcin-ricin loop (SRL) of 23S rRNA, preventing steric clash 

## Initial selection
3. **Codon recognition**: Anticodon samples codon and decoding centre until a match is sensed by the decoding center nucleotides G530 and A1492-A1493 of the rRNA, which undergo [[A8 Machinery of Translation#Interaction between codon:anticodon helix and decoding center nucleotides results in selective stabilisation of cognate tRNAs over near-cognate|conformational changes]].  ^6e4b11
	1. If anticodon-codon match is incorrect, then ternary complex is released without GTP hydrolysis. However, near-cognate codons often still bind at this step, requiring further [[A8 Machinery of Translation#Decoding: mechanisms of discriminating codons|decoding]]
4. Codon recognition triggers a series of **conformational changes in the ribosome and EF-Tu for GTPase activation**
	1. G530 fastens the codon:anticodon helix into the decoding centre, which brings the 530 loop of the 30S shoulder towards the body, resulting in 30S domain closure (Loveland et al 2017). 
	2. Domain closure of 30S subunit brings shoulder domain into contact with EF-Tu, and shifts regions of domain 2 of EF-Tu (including a β-turn) towards shoulder. 
	3. EF-Tu docks at the SRL. 
4. This distorts of the 3' acceptor arm of aminoacyl-tRNA, which disrupts interactions between the tRNA and switch I loop and positions EF-Tu on the ribosome for GTPase activation ^bdeab4
5. Phosphate of residue A2662 of SRL positions the catalytic His84 into the GTPase center, which activates a water molecule to attack the terminal phosphate of the bound GTP
	1. The ribosome thus acts as a GTPase-activating protein for EF-Tu via SRL by stabilising the transition state for GTP hydrolysis, lowering the activation energy. 

Loveland et al (2017)
![[Pasted image 20230103004517.png]]
Initial binding = [[A8 Machinery of Translation#Recruitment|Recruitment]]
Codon recognition = [[A8 Machinery of Translation#^6e4b11|Codon recognition]]
GTPase activation = [[A8 Machinery of Translation#^bdeab4|GTPase activation]]
(b) shows structural changes in decoding centre during decoding; discrimination between cognate and near cognate tRNAs is due to interaction between [[A8 Machinery of Translation#^a425e1|G530 and codon:anticodon helix]]

### **Post- GTP hydrolysis**
6. GTP hydrolysis (kinetic proofreading)
	1. This step is [[A8 Machinery of Translation#Kinetic proofreading|faster]] for cognate than near-cognate tRNAs 
7. Release of Pi results in disordering of Switch I loop and a ~100° rotation of the nucleotide binding domain relative to domains 2 and 3. This disrupts the interactions between the nucleotide binding domain with SRL, and between switch II and tRNA acceptor arm, resulting in... 
8. ... Dissociation of EF-Tu from ribosome 
	1. #structural_evidence Cryo-EM classifications – During accommodation, cognate tRNA is locked into ribosomes with a closed 30S subunit, so ribosome is committed to tRNA. In contrast, ribosomes with near-cognate tRNA continue to sample the conformation with open 30S subunit with disengaged G530
9. **Accommodation**: A-site acceptor stem of the tRNA moves towards peptide transfer centre, which is accelerated for cognate compared to near-cognate tRNA 
	1. Failed accommodation results in dissociation of tRNA from the ribosome 

### **Peptidyl transfer** 
9. **Peptidyl transfer**: Peptidyl transferase catalyses **peptide bond formation**, which transfers polypeptide from tRNA in site P to tRNA in site A
	1. Upon binding of A site substrate, series of conformational changes in 23S rRNA exposes peptidyl tRNA ester for nucleophilic attack by the α-amine 
		1. #experimental_evidence First observed in structures of 50S subunit with minimal oligonucleotide substrates
		2. #experimental_evidence Voorhees et al (2009) – Observed in X-ray crystal structures of whole ribosomes with intact A- and P-site tRNAs that mimic pre- and post-peptidyl transfer states  
- Nucleophilic attack by alpha amino group of A site aa-tRNA on carbonyl carbon of ester link between peptide of P-site peptidyl tRNA 
- Peptidyl transfer is catalysed by entropic effects 
- There is a movement of protons in a *proton wire* which couples aminoacyl-tRNA accommodation to peptide bond formation 
	- Proton wire relies on contributions from protein component of ribosome (E.g. A2451 residue)
	  ![[Pasted image 20230101203726.png|575]]
	- #experimental_evidence Polikanov et al (2014) – crystal structures of preattack and postcatalysis complexes of *Thermus thermophilus* 70S ribosome 
- 2' OH of A76 in peptidyl tRNA may also play a role in inducing an active conformation of the peptidyl transferase centre 
- No ribosomal proteins are directly involved in catalysis, though proteins have been observed in the peptidyl transferase centre of the bacterial ribosome 

### Translocation 

> [!NOTE]- Why study translocation? 
> - Maintains the reading frame
> - Required more generally for translation to proceed

10. Peptidyl transfer drives formation of a **hybrid state**
	1. 3' ends of A-site peptidyl tRNA and P-site deacylated tRNA move to P and E sites of 50S subunit, while anticodon ends and mRNA remain anchored in 30S subunit
	2. In this hybrid state, the 30S subunit is rotated (ratcheted) with respect to 50S subunit  ^b2bb75
		1. #experimental_evidence Cryo-EM 
		2. FRET
	3. The hybrid state can only occur after peptidyl transfer 
		1.  #experimental_evidence aa-tRNAs favour the canonical A/A state, while peptidyl-tRNA favours A/P conformation. Only a deacylated 
		2. #experimental_evidence Crystal structures show that only deacylated tRNAs can access the E site of the 50S subunit, so P/E state can only be accessed after peptidyl transfer 
11. EF-G + GTP binds to ribosome A site to stabilise hybrid state by placing its translocase domain 4 near the A/P* tRNA, while EF-G domain 5 is anchored at L11 stalk of LSU. Domain 4 blocks peptidyl-tRNA if 30S subunit tries to rotate back to classical state. 
    1. EF-G resembles ternary complex – GTPase domain resembles EF-Tu, and its extended domain IV mimics the shape of tRNA anticodon arm, allowing it to bind to the A site 
    2. Can only bind when EF-Tu is not present ⇒ Translocation can only occur after peptide bond formation  
    3. EF-G must be in GTP bound state so that GTPase domain is structurally complementary to SRL and rotated 30S subunit 
12. EF-G catalyses reverse rotation to translocate the ribosome, by "converting spontaneous ribosome fluctuations into tRNA translocation". 
	1. **Conformational changes**. During translocation, ribosome to translocate three nucleotides/1 codon along mRNA in 5’ to 3’ direction, resulting in mRNA and anticodon ends of peptidyl-tRNA transferred to P site while deacylated tRNA moves to E site  of 30S subunit, restoring canonical state of ribosome. 30S subunit rotates from hybrid state to classical state. 
	2. **EF-G disengages the decoding center nucleotides** from the codon:anticodon helix
	3. **mRNA moves with the tRNAs** and they remain base-paired to each other throughout translocation
		1. #experimental_evidence Measurements of rates of mRNA and tRNA translocation indicate that they are essentially the same 
	4. **Mechanism for EF-G is unclear**  – it may use the free energy of GTP hydrolysis in a power stroke to drive translocation directly, or to provide a free energy gradient for a Brownian ratchet; direct measurement of forces generated in translocation would be needed to answer this question (e.g. with optical tweezers), or can use FRET measurements, or MD simulations (since each mechanism has different energy barriers/landscapes)
		1. #experimental_evidence [[ChenEtAl_2016]] used single molecule polarised fluorescence microscopy to propose a hybrid model where power stroke initiates translocation and Brownian ratchet completes it. 
		2. #experimental_evidence [[Korostelev_2022]] – Non-hydrolysable GTP analogs and catalytically dead EF-G mutants still accelerate translocation by more than 3 orders of magnitude, so GTP hydrolysis may not substantially contribute to tRNA movement? 
13. EF-G + GTP binding also stimulates GTPase activity. GTP hydrolysis ennables EF-G dissociation, yielding a vacant A site 
14. Pi release prevents spontaneous backward tRNA movement -> unidirectional translocation 
15. A site now empty for next aa-tRNA 
16. Deacylated tRNA leaves through E site 

(Voorhees & Ramakrishnan 2013)
![[Pasted image 20230102225904.png]]

### **Recycling of EF-Tu**
15. EF-Ts acts as a GEF that catalyses the exchange of EF-Tu + GDP to EF-Tu + GTP 
    1. EF-Ts binds to Ef-Tu and displaces GDP 
    2. GTP displaces EF-Ts and binds to EF-Tu 
16. EF-G+GDP is recycled to EF-G+GTP without ancillary factors as it has higher affinity for GTP than GDP 
![[Pasted image 20221231212708.png]]

| Prokaryotes | Eukaryotes | Function                         |
| ----------- | ---------- | -------------------------------- |
| EF-Tu       | EF1A       | Amino acid delivery to A-site    |
| EF-Ts       | EF1B       | Recycling EF-Tu-GDP to EF-Tu-GTP |
| EF-G        | EF2        | Translocation                    | 

## Structural techniques to study elongation 
### Role of EF-G 
- EF-G allows peptide to be released from ribosomes  
- #experimental_evidence Traut & Monro (1964) added puromycin to elongating ribosome complex. Puromycin resembles the 3' end of aminoacylated tRNA. It can enter the A site and transfer to the growing polypeptide chain, forming a puromycylated nascent chain which causes premature chain release.
	- When puromycin only was added to the ribosomes, there was 40% peptide release, but when puromycin was added with S100 fraction of proteins (containing a GTPase) + GTP, there was more peptide release

### Structural techniques
- Many stable intermediates in elongation cycle have been crystallised and structures determined to high resolution, while others have been characterised to lower resolution by Cryo-EM 
- FRET is used in kinetic studies of translation 
	- E.g. #experimental_evidence FRET has been used to determine the lifetime of the codon-recognition state, GTPase-activated state, and accommodated state during translation. This was done by placing donor and acceptor pairs on the P- and A-site tRNAs 

## Termination 
Release factors (RFs) are proteins that recognise stop codons (UAA, UAG, UGA) and induce hydrolysis of polypeptide from tRNA 
- RFs mimic the shape of a tRNA molecule 
	- One domain of the protein localises close to the peptidyl transferase site to induce hydrolysis of the peptidyl-tRNA by bringing in a water molecule. 
	- Other domain recognises termination domain 

### Prokaryotes 
- In **prokaryotes**, there are two classes of RFs 
	- Class I RFs (RF1 and RF2) recognise termination codon directly. Each has different specificity for different stop codons 
	  ![[Pasted image 20230101210341.png|200]]
		- "NAND" logic gate – avoids misrecognition of UGG (Trp) as a stop codon. In RF2, it is a result of incompatibility of hydrogen bond interactions between RF and non-cognate codons  
		- RF2 binding triggers conformational changes of conserved decoding centre bases (G530, A1492, A1493)
	- Class II RF (RF3) is a GTPase. RF3-GDP binds to the ribosome and GTP replaces GDP while on the ribosome. Conformational change releases the class I factor and subsequent GTP hydrolysis releases RF3. 
	- Either Class I factor, along with RF3, is needed for termination  

![[Pasted image 20230101211706.png]]

### Eukaryotes 
- In **eukaryotes**, there is a single release factor (eRF1) that recognises all 3 stop codons 
- ABCE1 ATPase helps to dissociate 40S and 60S 
- NAND gate in eRF1 – molecular basis of stop codon recognition. #comment See brown et al (2015)

## Ribosome recycling 
- Ribosome recycling factor (RRF) acts like a "molecular crowbar" to mechanically disrupt interactions between large and small ribosomal subunits 
- May have synergistic interaction with EF-G 

# Fidelity of translation 
![[Pasted image 20221231214317.png]]
## Why is proofreading needed? 
- **Increase accuracy**. Although binding events during protein biosynthesis are relatively accurate, errors in biosynthesis can be so devastating to the cell that life has evolved mechanisms for proofreading to catch any errors that do slip through 
	- No biochemical process can be 100% accurate and each does exhibit different degrees of accuracy 
- **Increase speed?**
- **Point of regulation?** E.g. LeuRS regulates TORC 

## Errors in protein biosynthesis 
- At equilibrium, accuracy of molecular recognition processes depends on ΔΔG of desired vs undesired interactions 
- In vivo (non-equilibrium), as substrates are immediately and irreversibly used up, difference in activation energy of the rate limiting step is more important. 
- In other words, *in vivo*, molecular recognition processes are under **kinetic control** rather than **thermodynamic control!**
- This is why energy input is necessary to ensure that the desired interaction occurs – it helps to accelerate the reaction by overcoming the activation energy barrier. 
	- Arrhenius equation: Rate = Ae<sup>-E<sub>a</sub>/RT</sup>

### Missense errors
- Wrong amino acid incorporated 
- Very low frequency 
- Can arises in two ways
	- Incorrect charging of tRNA
	- Incorrect codon-anticodon recognition on ribosome
- In translation, substrates and competitors to be distinguished are often very similar (e.g. amino acids Val vs Ile or codon-anticodon base pairs G:U vs A:U)

### Processivity errors 
Failure to complete translation of open reading frame due to 
- Accidental frameshifting (during translocation or decoding) 
	- Leads to encounter of out-of-frame stop codon and thus premature chain release
	- Accidental frameshifting often occurs on "slippery" mRNA sequences, i.e. sequence where codon in 0, -1, or +1 readingframes can be readb ythe same tRNA (e.g. AAAAA)
- Erroneous mis-reading of a sense codon as a stop codon 
- Amputated/truncated mRNA 
- Spontaneous and accidental peptidyl-tRNA drop off – peptidyl-tRNA released from the ribosome is hydrolysed by peptidyl-tRNA hydrolase to free tRNA and peptide 

#### Measuring the rate of processivity errors 
- Compare yields of a double-length LacZ and a normal length LacZ, each with co-expressing promoters. After correcting for processivity errors in transcription, estimated that processivity errors occur 1 in 4000 per codon 

## tRNA charging 
### Charging process
![[Pasted image 20221231233332.png|475]]
1. Formation of aminoacyl-adenylate intermediate 
	1. Hydrolysis of PPi shifts equilibrium forward; adenylate does not dissociate in this step due to tight binding in catalytic site 
2. Amino acid transferred from adenylate to 3' adenosine of tRNA

- E. coli have 20 aaRS, 1 for each amino acid, though some amino acids have several cognate tRNAs (isoacceptors)

### How synthetases recognise tRNAs 
- 2 classes of RS, I and II (10 in each class)
	- Conserved catalytic domain (within each class)
		- Class I has Rossman fold domain for catalysis
	- Different structures for recognising tRNA 
	- Bind tRNA from opposite faces 
- Not all RS can do editing – IleRS, ValRS, and LeuRS in class I, and ThrRS, ALaRS, ProRS, and PheRS in class II 
  ![[Pasted image 20221231235813.png|650]]
- Different synthetases recognise different identity sites on the tRNA, but anticodon and 3' CCA acceptor stem are generally important sites 
	- e.g. tRNA-Met recognised by anticodon and N73
	- e.g. tRNA-Ala recognised by G-U pair in acceptor stem 
	- Other synthetases recognise more disperse set of features, sometimes including anticodon (e.g. PheRS) or not (e.g. SerRS)
- aaRSs are selective for their cognate tRNAs due to the large contact surface area available during recognition and kinetic proof reading during aminoacylation 

### Val/Ile/Thr discrimination is challenging 
- Val, Ile, and Thr are small and difficult to distinguish by binding energy alone 
- Difference of 1 methyl group between Val and Ile cannot account for sufficient difference in binding energy with aaRS 
	- Other enzymes that metabolise Ile have at least 1% relative efficiency/rate on Valine, while discrimination for tRNA charging approaches 1 in 10 000 
- Thr is also isosteric with Val 

### Editing 
- **Double sieve editing**: Misactivated products from "near-cognate" amino acids that evade a first, "coarse sieve" are destroyed by a "fine sieve"
- In ValRS, first sieve is based on size (steric occlusion) to separate out Ile, which has an extra methyl group
- Second sieve in ValRS is based on hydrophilicity – Thr has OH in **editing** site. 
- Upon recognition, the incorrectly charged Thr is discarded by hydrolysis of 
	- Thr-AMP (Pre-transfer editing), or 
	- Misacylated Thr-tRNA (post-transfer editing)
	- Most enzymes with an editing site can do both, but have preference for one or other route; post-transfer editing is preferred for ValRS 
![[Pasted image 20221231234611.png|550]]

![[Pasted image 20221231234850.png|500]]

- Other aaRS may have different kinds of sieves? #comment Look into this. 
	- E.g. ValRS vs IleRS

#### Biochemical evidence for ATP usage in discrimination 
- 60 ATPs are used per Thr-tRNA<sub>Val</sub>
- 1.1 ATPs used per Val-tRNA<sub>Val</sub>

#### Structural evidence for proofreading for IleRS
- X-ray structure of IleRS in presence of Val or Ile shows that 
	- Val is bound in two different sites (activating site and editing site)
	- Ile is bound in only 1 site, the activating site, being too large to fit into the editing site of IleRS 
	- CCA end of tRNA is flexible, allowing for amino acid to be transferred from activating site to editing site 

#### Editing sites can act as drug targets
- E.g. Benzoxaboroles can form an adduct with tRNA<sub>Leu</sub> at the editing site of LeuRS to inhibit protein synthesis 

## Preventing processivity errors 
- During translocation, the hybrid state weakens interactions between tRNA and mRNA, which could provide the tRNA the opportunity to sample codons in 0 and -1 reading frames. 
- Synchronised movement of EF-G and 30S head during translocation probably helps to prevent this, thus preserving the  reading frame 
	- #experimental_evidence [[PengEtAl_2019]] studied translation in an *in vitro* translation system using *E. coli* components. They did mutation analysis of residues in domain 4 of EF-G and found that these residues were critical for maintaining reading frame. 
		- #structural_evidence Zhou et al (2019) created a crystal structure of the pretransloccation complex and found that the EF-G restricts forward movement of A-site tRNA into -1 frame 
	- #experimental_evidence [[PengEtAl_2019]] further used FRET reporters for EF-G to study the kinetics of translocation in different EF-G domain 4 mutants. 
		- FRET reporters were attached to EF-G and to ribosomal protein L12. Fluorescence of L12 reporter was quenched when wt EF-G binded to it. Mutations in domain 4 did not affect the rate of EF-G binding, but dissociation was delayed when Q507 or H583 was mutated. 
		- FRET reporters were also attached to the ribosomal proteins S6 and L9 (SSU body rotation) or to S13 and L33 (SSU head rotation/swiveling). P-site tRNA movement was measured by monitoring FRET between the initiator tRNA and L33. When wt EF-G is first added, SSU body domain rotates backwards to non-rotated state, while SSU head remains highly rotated. When Pi is released from EF-G, the SSU head domain moves backwards, and this facilitates tRNA translocation. 
			- Mutations of Q507 and H583 decrease the rates of SSU body and head rotation. 
			- The delay in these structural rearrangements allows the tRNAs to sample codons in either 0 or -1 frame to establish interactions, leading to frameshift. 
	- #experimental_evidence Cryo-EM and FRET studies show that frameshifting can occur during head swiveling in translocation 
	- #experimental_evidence In the absence of EF-G, head-swiveled ribosome with cognate tRNA does not preserve WC pairing of codon:anticodon helix in ap/P state 

## Decoding during initiation 
Discriminating initiator tRNA from elongator tRNA 
- Difference in thermodynamic stability of cognate tRNA and mismatched tRNA too small to account for stringency of discrimination 
- Cryo-EM of ensembles of initiation complexes found that IF3 CTD acts as a switch that selects for initiator tRNA binding to start codon 
	- In absence of initiator-tRNA, CTD of IF3 blocks AUG codon in the P site and interact with IF1 to block A site 
	- 30S subunit samples open and closed states 
	- Three GC pairs in initiator-tRNA interact with G1338 and A1339 at the head of the 30S subunit to stabilise it 
	- The 30S subunit also closes, requiring dissociation of IF3 CTD from AUG codon and from IF1  
	- In closed complex, tRNA shifts to interact with IF2 to trigger subunit joining. 
- IF2 also has specificity for initiator tRNA 

## Decoding during elongation 
How is the cognate tRNA selected from the pool of cellular tRNAs? 

### Challenges in discriminating between codons 
- Trinucleotide-trinucleotide pairing is very weak 
- Discrimination between cognate and non-cognate codons is not difficult – large differences in sterics 
- Discrimination between cognate and near-cognate codons is difficult – e.g.  difference between U:A and U:G base pairs is small, at most 3-fold difference. 
- However, wobble pairing (U:G) is possible 
	- In wobble pairing, a mismatch is allowed at the third base position but not the first two positions 
	- E.g. AAG:UUU for Phe 
	- Wobble pairing is allowed because the Interaction of conserved ribosomal bases with the three codon-anticodon base pairs shows a specific recognition of Watson-Crick geometry at the first two positions, and a tolerance of GU wobble pair at the third position

### Interaction between codon:anticodon helix and decoding center nucleotides results in selective stabilisation of cognate tRNAs over near-cognate 
- Upon codon recognition, decoding center nucleotides G530 and A1492-A1493 of the rRNA undergo a conformational change such that they interact with the minor groove of the codon-anticodon helix at the first and second, but not the third positions
- G530 forms hydrogen bonds with the codon-anticodon backbone to stabilise the codon-anticodon helix  ^a425e1
	- In the near-cognate tRNA, G530 does not stabilise the codon-anticodon helix 
	- Stabilisation of this interaction may be affected by tRNA modifications at position 34 and Mg2+ 
- A1492 and 1493 insert into the minor grooves of the helix to form a tertiary structure called an A-minor motif 
- These interactions require Watson-Crick pairing for first two positions but allow for wobble pairs (i.e. G:U) at third position 
- The excess binding energy from recognition of cognate base pairs at minor groove is used to induce conformational changes in the tRNA essential for EF-Tu GTPase activation, as described in [[A8 Machinery of Translation#Initial selection|initial selection]]. 
	- Specifically, domain closure requires Watson-Crick base pairing at the first two codon-anticodon positions (Loveland et al 2017). Near-cognate codons may be able to bind to the anticodon, but would not trigger these conformational changes due to specific interactions with decoding center bases, thus favouring an open 30S subunit and inactive EF-Tu, which promotes its departure. 

### Distortions in the tRNA body beyond the anticodon also assist in codon recognition 
- Binding of aminoacyl tRNA to ribosome along with EF-Tu requires tRNA to adopt the A/T state, which allows for simultaneous interaction of the anticodon with the codon and with EF-Tu, thus allowing for EF-Tu GTPase activation 
- To adopt the A/T state, the anticodon stem has to be distorted, and the D-stem has to move away from the acceptor/T-stem stack 
	- #experimental_evidence "Hirsh supressor" tRNA contains a single mutation in the D-stem of tRNA<sub>Trp</sub> that allowed read-through of UGA (near cognate) stop codons. This is because it allows formation of an additional hydrogen bond that stabilises the A/T conformation, allowing for GTPase activation despite the use of a near-cognate tRNA 
- Other mutations in the tRNA body can also affect accuracy: 
  ![[Pasted image 20230101231651.png|425]]

### Accommodation and kinetic proofreading 
- Accommodation is accelerated in cognate tRNA compared to near-cognate tRNA 

### Kinetic proofreading 
- There is forward acceleration of GTP hydrolysis step that commits it in an irreversible direction upon binding to cognate codon, resulting in separation between initial selection and proofreading stages  

![[Pasted image 20230101010346.png|625]]

### Proofreading mechanisms post-peptidyl transfer 
- Can preferentially terminate translation 
- E site participates in decoding 

## Other factors affecting fidelity 
- **Codon usage and concentration of cognate tRNA.** Since translation involves a competition between cognate and near-cognate tRNA, a higher concentration of cognate tRNA would increase the encounter rate between the translation machinery and the cognate tRNA, increasing the likelihood it is incorporated. This also means that a codon that corresponds to a more abundant tRNA is more likely to be decoded correctly 
	- #experimental_evidence Precup & Parker (1987) – frequency of missense errors in *E. coli* is reduced if same amino acid is translated by a codon corresponding to an abundant tRNA rather than a low abundance one 
	- #experimental_evidence Akashi (1994) observed that frequency of preferred codons is higher at conserved amino acid positions, suggesting that there is selection for optimal codons at sites where a missense error would have a greater effect on protein structure 
- **Increased misincorporation of Met under stress.** When mammalian cells are under some stresses, programmed translation error can occur where there is increased misincorporation of Met due to misacylation of Met residues on non-Met tRNAs. Met has some protective capacity against ROS (why?) so incorporation may protect against oxidative stress 

# Protein biogenesis factors 
## Co-translational chaperones 
- Help to prevent protein from trapping in energy minima, accelerate folding of multiple subunits 
- Trigger factor – facilitates fold of many proteins in bacteria 
	- #experimental_evidence Oh et al (2011) used selective ribosome profiling to show what transcripts are associated with trigger factor, as well as how far they must be translated before associating with trigger factor. Proteins are not immediately met by TF, but there is a "sphere of influence" 
	  ![[Pasted image 20230101204353.png|200]]

## Protein localisation factors
### Signals 
![[Pasted image 20230101204731.png|400]]
### Factors 
- ER: [[C1 ER Targeting and Integration]]

# Summary – prokaryotic translation 
![[Pasted image 20230101212958.png]]

# Links to other topics
- Obviously see [[B5 Translation and translation regulation in eukaryotes#Process of translation in eukaryotes|Process of translation in eukaryotes]] 
- [[B5 Translation and translation regulation in eukaryotes#Studying translation|Techniques]] for studying the process of translation, particularly transcriptomic methods 
- [[C2 PTMs and Protein trafficking#Protein folding in the ER has a high error rate|Protein folding]] occurs co-translationally 
- [[C1 ER Targeting and Integration|Protein targeting]] occurs co-translationally and post-translationally 

