# Learning Outcomes 
* Structure of plasma membrane 
    * Discuss the molecular variety present on the external face of the plasma membrane of eukaryotic cells.
* ER membrane protein insertion via the SEC61 pathway 
    * Membrane protein insertion into the endoplasmic reticulum often involves proteins other than the SEC61 complex. Discuss.
    * The SEC61 translocon is a versatile **multifunctional** protein machine. Discuss. (See [[LangEtAl_2017]]; also [[C1 ER Targeting and Integration#QC by translocon|QC by translocon]]) 
    * ==*Many different types and topologies of integral membrane proteins are inserted into the endoplasmic reticulum. How well do we understand these processes of membrane protein insertion?*==
    * What are the major obstacles to insertion of a membrane protein into the lipid bilayer and how do the SRP and Sec61 complexes overcome these barriers?
    * What are the unresolved questions in our understanding of targeting and insertion of proteins into the endoplasmic reticulum membrane? Explain how current techniques are addressing these questions.
    * To what extent do we understand the Sec61-mediated process of integration of proteins into the endoplasmic reticulum membrane?
* Why is protein targeting to ER so accurate? 
    * How can hydrophobic peptide sequences lead to high fidelity targeting of nascent proteins to the endoplasmic reticulum membrane?
    * Discuss the mechanisms that lead to highly specific selection of nascent proteins for targeting to the endoplasmic reticulum.
    * ==*Discuss the mechanisms that ensure the correct selection of proteins to be targeted to the endoplasmic reticulum for membrane insertion or secretion.*==
* Quality control in folding and targeting 
    * *==What mechanisms in the secretory pathway facilitate efficient quality control in protein folding and protein targeting?==*
    * What cellular and molecular features within the endoplasmic reticulum contribute to error correction mechanisms in protein folding within this compartment?
    * How does the lumenal environment of the endoplasmic reticulum (including the presence of resident endoplasmic reticulum proteins) enhance the efficiency of protein folding?
* Protein glycosylation in the ER 
    * *==How are proteins glycosylated in the endoplasmic reticulum? (N-glycosylation, O-glycosylation, GPI anchoring) Give some examples of the functions of the different types of glycosylation.==*
    * Which are the most important aspects of protein glycosylation pathways in the endoplasmic reticulum that remain incompletely understood?  ==*How would you go about characterising these aspects of the pathway?*== 
    * How is cytosolic GDP-mannose used to initiate endoplasmic luminal glycosylation of proteins and how is this process related to a disease mechanism of muscular dystrophy?
    * Discuss the evidence that flippases are required for protein glycosylation.

# Structure of the plasma membrane 
- Refer to [[A5 Preparing membrane proteins for structural study#Structure of membranes|Structure of membranes]]
- In addition, membrane proteins are in thermodynamic equilibrium with the lipid bilayer, so the stability and structure of membrane proteins are affected by how it interacts with lipids in the bilayer 

# Protein targeting to the ER 
Proteins are targeted to the ER when they are intended for secretion, compartmentalisation, or insertion into a membrane. 

## SRP cotranslational pathway 
* Most secretory proteins have an N-terminal hydrophobic signal peptide, which is cleaved off in the final protein by a peptidase 
    * Signal peptide contains AXA motif
    * There is often a positive charge on the N-terminus side 
    * Has low sequence conservation 
    * Can function as the transmembrane domain in the signal anchor of type II proteins 
    * Can interact with targeting and translocation machineries 
    * Can interact with transmembrane lipids 
* The signal recognition particle (SRP) recognises the signal peptide for targeting to the ER 
    * A 54 kDa subunit is essential to signal recognition (i.e. SRP54), and thus is highly conserved evolutionarily 
        * Experimental evidence – _In vitro _reassembly of signal recognition particle 
* The main advantage of the SRP pathway being co-translational is that the machinery for targeting and insertion is physically coupled to the ribosome at the ribosome exit, allowing proteins with transmembrane domains to maintain solubility, and giving the targeting machinery a kinetic advantage in binding to translocated proteins over other binding partners in the cell 
    * SRP pathway outcompetes other pathways as well e.g. Get – in the absence of SRP, Get3 can bind substrates with internal TMDs (i.e. not at C-terminal), while SRP cannot recognise a TMD that is near the C-terminus 

### Structure of SRP54
![[Pasted image 20221222142500.png|500]]
* Switchable protein interaction domain (NG) and signal binding domain (M) connected by a flexible linker domain
* M domain recognises signal peptide. It contains methionine bristles on amphipathic α helices – flexible hydrophobic residues provide sufficient structural plasticity for SRP to bind to signal sequences of different lengths and sequences 
* N domain interacts with ribosome near exit tunnel 
* Alu domain (eukaryotic?) interacts near GTPase centre of ribosome 

### Mechanism of SRP54 interaction with signal peptide 
#structural_evidence [[VoorheesHegde_2015]] – cryo-EM structures of scanning and engaged SRP 
* The challenge of recognising the signal sequence is that the signal sequence is not well conserved – different proteins have signal sequences of different lengths and sequences, yet all have to be targeted accurately to the ER. Additionally, their difference from the signal sequences of non-SRP substrates is minor 
* SRP prefers to bind to ribosomes in a non-ratcheted (rotated) state
	* #experimental_evidence Ogg and Walter (1995) – cycloheximide pauses translation, presumably in unratcheted state. "Cycloheximide rescues translocation defects caused by limited SRP availability" (Voorhees & Hegde 2015). In contrast, anisomycin pauses ribosomes in a ratcheted state, and does not rescue translocation defects. 
* SRP finds the signal peptide via a scanning mechanism. The M domain scans nascent chains of translating ribosomes, and during scanning the SRP54 M domain is positioned at the exit site of the ribosome close to the ribosomal proteins L23a and L35, allowing it to contact the signal peptide shortly after its emergence from the ribosome 
    * SRP molecules do not exist in equimolar amounts to ribosomes, so it will dissociate from the translating ribosome if it does not encounter a targeting signal → proteins with targeting motifs positioned away from the N-terminus would not be captured as efficiently by this scanning mechanism, and may use alternative pathways (see [[C1 ER Targeting and Integration#Post-translational ER targeting pathways|Post-translational ER targeting pathways]]) 
* During scanning, Alu domain probably occurs immediately after dissociation of eEF1 or eEF2 during translation cycle so that it can access the GTPase centre, while S domain presumably binds transiently anytime. When eEF1 or eEF2 associates again during translation cycle, Alu dissociates. However, SRP remains associated with RNC because S domain dissociation is far slower than an elongation cycle, ensuring there is always at least 1 contact point 
	* Competition between Alu domain and eEFs may be the cause of the slowing of translation by SRP; slowing of translation could give more time for signal peptide recognition and delivery to translocon  
* Upon recognition of signal peptide, SRP54 undergoes multiple conformational rearrangements to enter the "engaged" state
    * It moves away from L23a of ribosome, which may allow the translocon to dock with the ribosome as the translocon also interacts with L23a
    * The SRP54 NG domain undergoes a massive rearrangement and binds to the ribosome L23 subunit, displacing the nascent polypeptide-associated complex (NAC).
    * M domain undergoes a conformational change when it binds to a signal peptide
        * Signal sequence helix and αM4 interact via a 4-4 “ridges into grooves” helix packing, resulting in extensive interaction between the signal peptide h-region and αM4
        * Trp420 in M domain undergoes rotation 
    * A C-terminal helix of SRP54 is displaced upon binding to signal peptide, creating a threshold for binding – signal peptide only binds if it has sufficient hydrophobicity to outcompete the helix for binding  ^e70f4d
	    * #structural_evidence [[VoorheesHegde_2015]]After displacement, the C-terminal helix in eukaryotic SRP is rearranged such that the hydrophobic face is oriented towards the signal peptide, thus helping to sequester the hydrophobic sequence 
* In engaged state, SRP S domain is stably bound to ribosome as it interacts with exit tunnel and nascent chain 

### Antagonistic binding by nascent polypeptide-associated complex (NAC) prevents inappropriate ribosome binding to SEC61 translocon on ER 
* SRP and NAC both bind to ribosome nascent chain, and SRP displaces NAC in ER-targeted proteins 
* RNCs can interact with SEC61 translocon regardless of whether the protein is destined for membrane targeting or not. NAC, which is bound to virtually all ribosomes, blocks the translocon docking site to prevent incorrect ribosome binding to Sec61 translocon in the absence of SRP 
    * Cytosol-destined proteins become more associated with the membrane in the absence of NAC 
* NAC recruits SRP to RNC via its NG domain interaction, allowing SRP to begin scanning of the nascent polypeptide chain 
* As nascent chain emerges with a signal, NAC interaction with RNC is weakened, allowing SRP to displace it from RNC 
    * #experimental_evidence Jomaa et al (2022) – Incorporated photo-cross-linking probes inside and outside the NAC hydrophobic pocket to test its proximity to nascent chains that coded for a cytosolic, mitochondrial, or ER protein. Cross-linking occurred to ER targeting signals and only when the targeting signal was fully exposed outside of the exit tunnel, and cross-linking was prevented when helices in hydrophobic pocket were covalently linked by disulfide bonds 
* NAC also prevents SRP from binding ribosomes that are synthesising cytosolic and mitochondrial proteins 
    * #experimental_evidence Gamerdinger et al (2015) – in animal extract depleted of NAC via RNAi, the fraction of ribosomes attached to the ER membrane increased 

Jomaa et al 2022  ![[Pasted image 20221222144725.png|325]] 
### Early recruitment of SRP to membrane proteins 
- TMDs are more insoluble than signal peptide but are too long to be shielded by M domain, so early targeting is important so that protein can be delivered to translocon before or as soon as TMD emerges, minimising TMD exposure to the cytosol 
	- #experimental_evidence Jan et al (2014) ribosome profiling experiments in yeast suggest that many proteins are delivered to Sec61 before TMD is synthesised  
- For SRP to be recruited early to the ribosome, there has to be a minimum hydrophobic element of > 7-9 hydrophobic residues 
- Early recruitment also gives SRP first interaction with protein before other chaperones (e.g. TRC40, SGTA), and gives more time for targeting RNC to translocon 
- However, unclear how TMD causes early recruitment from inside the exit tunnel 
	- #structural_evidence [[VoorheesHegde_2015]] could not detect any conformational changes in the exit tunnel or ribosome surface 

### Lengthening the targeting window
- Increases likelihood of successful RNC delivery to SRP 
- Early SRP recruitment 
- Translational slowing by Alu domain 
- Strategic position of slowly decoded rare codons 
	- #experimental_evidence [[PechmannEtAl_2014]] found that SRP recognition of signal peptide is improved if the mRNA has nonoptimal codons clusters ("REST elements") 35-40 codons downstream of the SRP binding site, which is a distance as long as the ribosome exit tunnel. Effectively, this causes translation to slow down as soon as the signal peptide emerges from the exit tunnel, which is demonstrated by ribosome profiling experiments in yeast that showed that there is increased ribosomal occupancy on REST elements. Removal of REST elements reduced efficiency of translocation 

### SRP brings the ribosome nascent chain (RNC) to the SRP receptor on the ER membrane in a process regulated by GTP hydrolysis 
* Once it recognises the signal peptide, SRP can bind to SRα domain of the SRP receptor (SR) via their respective NG domains
    * SRP contains a GTPase domain in SRP54, while SR has 2 GTPase subunits (SRα and SRβ) 
    * NG complex rearrangements and SR compaction may also drive detachment of the GTPase complex from L23a to expose the docking sites near the ribosome exit for interaction with Sec61 translocase 
    * Coordinated binding of GTP to SR and SRP is required for accurate targeting of SRP to SR 
    * **Role of SRβ**. SRβ is the subunit of SR that resides in the ER membrane, anchoring the SR dimer to the membrane. It is a GTPase and has to be loaded with GTP by an exchange factor to bind SRα, which in turn recruits SRP. Hence dimerisation of the two subunits is necessary to localise the SRP-RNC complex to the ER membrane 
        * Sec61 may be a possible GEF for SRβ as it has homology to ARF-GEF ⇒ SR is localised to adjacent regions around translocon 
        * Anchoring of SR to membrane restricts search for vacant translocon to 2D surface of ER membrane 
    * While free, SR adopts an extended conformation, with a disordered linker that may act as a “leash” allowing it to increase the search space in the cytosol for the RNC-bound SRP, and after binding it compacts to bring the RNC close to the ER membrane 
* After binding, a second rearrangement of SRP occurs to expose the translocon binding site on the ribosome, allowing the nascent polypeptide chain to enter the translocon 
	* #experimental_evidence [[JiangEtAl_2008]] showed that SR and translocon interaction is important for translocation. When the TM domain of yeast SRβ is deleted, yeast exhibit cotranslocational defects. However, when *SSH1* gene (part of Ssh1 translocon) is also deleted, the defects are enhanced.
* **GTPase cycle**. Multiple conformational changes in SRP-SR complex occur to ensure accurate ER targeting. 
	- Unlike other GTPases, SRP54 and SRα are multistage GTPase swtiches with <u>three</u> stable states rather than two (GDP/GTP) like most switches: GDP, GTP, and empty. The GTPases also do not exhibit substantial conformational changes depending on the nucleotide state. Also, no external GEFs are needed to switch GTPases from GDP to GTP-bound state because their nucleotide exchange rates are much faster than classical GTPases. 
      ![[Pasted image 20221222143823.png|350]]
    * Both proteins start in an inactive “open” conformation and interact to form a transient “early” intermediate independently of GTP. This promotes GTP binding. and upon GTP binding the proteins undergo a structural rearrangement to form a stable “closed” complex. 
    * The "early" intermediate is stabilised by cargo loading (i.e. RNC) to accelerate complex assembly while delaying GTP hydrolysis  
        * This delay of GTP hydrolysis may provide a window of time for SRP to quality control the fidelity of protein targeting (see [[C1 ER Targeting and Integration#Kinetic proofreading|kinetic proofreading]]) 
    * The subsequent rearrangement to a closed complex promotes cargo unloading 
    * A further rearrangement of the closed complex results in an "activated" complex, which activates GTP hydrolysis to drive complex disassembly to recycle SRP and SR. 
    * #experimental_evidence Zhang et al (2009) used FRET to monitor the conformational changes of the SRP-SR complex. The transient "early" intermediate has a lower FRET value than "closed" and "activated" complexes. An acrylodan label at residue 235 of the SP detects "closed" and "activated" complex formation, and acrylodan label at residue 356 of SR near its catalytic loop detects "activated" complex 
* Ribosome subsequently completes the synthesis of the membrane protein while remaining bound to the SEC61 translocon
![[Pasted image 20221222225810.png|675]]
(Zhang et al 2009. T = GTP, D = GDP) 

### Quality controls for preventing incorrect cargo binding 

> [!Summary] Mechanisms for QC of SRP binding
> - Binding affinity of cargo to SR 
> - Stabilisation of closed SRP-SR complex
> - Rate of GTP hydrolysis 

#### Cargo binding step is insufficient 
- The cargo binding step to SR is not sufficient to discriminate against incorrect cargos – over 75% are able to enter the SR pathway if there are no further fidelity checks after the initial binding step. This is expected given the low conservation of the signal peptide sequence 
- #experimental_evidence [[ZhangEtAl_2010a]] varied the signal sequence of alkaline phosphatase by changing the Leu:Ala ratio to vary the hydrophobicity. RNC binding to SRP was measured by the extent of increase in fluorescence anisotropy of fluorescein-labelled SRP. They found that affinity of "weak" cargos for SRP was still substantial, with Kd of 80-100 nm. Given that SRP concentration is ~400 nm, there are still many incorrect cargos that could bind to SRP. 

#### Correct cargos stabilise "early" complex 
* The early SRP-SR complex is stabilised more strongly by correct than incorrect cargo, thus speeding up the transition to the closed complex
* #experimental_evidence [[ZhangEtAl_2010a]] assembled cargo-SRP-SR early complexes in the absence of nucleotides to block rearrangement of GTPase complex. The stability of this early complex was measured via FRET between donor- and acceptor-labelled SRP and SR respectively. 
	* "Correct" cargos (using variants of alkaline phosphatase, as above) stabilised early complex, and stability was lowered by up to 50-fold for weakaer cargos 
- Zhang et al (2010) suggested that "SRP and SR are likely to be positioned differently in the early targeting complexes formed by incorrect cargos", and this could lead to "slower rearrangement to form the closed complex for cargo unloading" 
    * #experimental_evidence They pre-formed the early targeting complex and directly measured its rearrangement using acrylodan-labelled SRP. "Correct" cargo allows for faster rearrangement to form the closed complex, while "incorrect" cargos are more likely to exit targeting prematurely 

#### Kinetic proofreading 
* Correct cargos delay premature GTP hydrolysis in the closed complex for a longer time than incorrect cargos. Premature GTP hydrolysis in the SRP-SR complex would result in complex disassembly, aborting the targeting reaction before the cargo is unloaded into the translocon 
* #experimental_evidence [[ZhangEtAl_2010a]] determined the GTP hydrolysis rates from cargo-SRP-SR complex – correct cargos lowered the rate compared to no cargo, while incorrect cargos did not significantly change the rate

#### QC by translocon 
* Quality control can be carried out by the translocon too 
* #comment This needs expansion 

### Overall, ER targeting relies on GTPase molecular switches
![[Pasted image 20221222142607.png]]

## Post-translational ER targeting pathways 
* SRP is a cotranslational ER targeting pathways, but there are also post-translational targeting systems. 
* Given the substrate diversity of ER-targeted proteins, it makes sense for multiple targeting pathways to evolve that are optimised for targeting proteins with different characteristics 
* These are necessary for very short proteins e.g. insulin – synthesised too quickly for signal sequence to be recognised by SRP
	* Translocation of short proteins can be arrested by adding a very bulky group at the C-terminal end that prevents translocation 
* Often involve cytosolic chaperones, e.g. calmodulins, Hsp40 proteins, Hsp70, that then interact with a specific ER-localised receptor 
    * Unclear whether role of chaperones is to preserve nascent polypeptides in a translocation competent, misfolded state, or if they take part in targeting 

### Post-translational translocation of secreted and type II proteins 
* Cytosolic chaperones bind to the protein before docking occurs
* Signal recognition is carried out by Sec61 + Sec62/63 complex 
* Sec61 can switch from a cotranslational to a posttranslational mechanism depending on the availability of SR. If SR availability is high, SR can dislodge Sec62 from association with Sec61, allowing Sec61 to bind to the ribosome and nascent chain for cotranslational translocation 
	* #experimental_evidence Crosslinking of Sec62 to Sec61α reduced by addition of SR to assay 
	* SR links cotranslational and posttranslational translocation! 
* Chaperone ratchet system – a chaperone in the ER called BiP acts as a ratchet that pulls the polypeptide through the translocon, with ATP input. 
    * In SRP system, translocation is driven directly by process of protein synthesis 

![[Pasted image 20221222142620.png|350]]

### Post-translational translocation of tail-anchored proteins 
* Doesn’t rely on Sec61 
* Specialised for tail anchored proteins with no N-terminal signal sequence or TMD, but have a C-terminal hydrophobic sequence (e.g. SNAREs) 
* Has to be post-translational as the signal only emerges after synthesis (being at the C-terminal) 
![[Pasted image 20221222142633.png|325]]

#### Guided Entry of Tail-anchored (GET)/TMD recognition complex 40 (TRC) pathway 
* For proteins with high hydrophobicity TMDs or glycosylphosphatidylinositol (GPI) anchored proteins in yeast 
* Upon emergence from the ribosome, the transmembrane domain is bound by the co-chaperone SGTA 
    * SGTA has a methionine-rich domain for recognising a range of hydrophobic substrates, similar to SRP 
* SGTA hands over protein to Get4-Get5 pre-targeting complex in yeast or Ubl4a-TRC35-Bag6 complex in mammals
    * Get4-Get5 (TRC35-Ubl4a) forms a scaffold that bridges Sgt2 (which binds Get5) and Get3 (which binds Get4) 
    * Get4 may bind preferentially to the ATP-bound (closed) conformation of Get3, which is the correct conformation for substrate binding 
* Protein is passed to Get3 ATPase in yeast (Asna1/TRC40 in mammals), which binds to the hydrophobic sequences on the C-terminus
    * Get3 is a homodimer, with each monomer consisting of an α-helical subdomain and ATPase domain 
        * In the presence of ATP, the helical subdomains associate to form a hydrophobic groove that binds to the transmembrane domain of the tail-anchored protein – closed conformation (similar to [[C1 ER Targeting and Integration#^e70f4d|C-terminal helix of SRP]])
    * Interaction between Get3 and TA protein induces ATP hydrolysis through ATPase activity of Get3 → partially closed conformation 
    * Following release of TA protein and ADP, Get3 shifts back into an open conformation, and subsequent ATP binding allows Get3 to be recycled back to cytosol in a closed conformation 

![[Pasted image 20221222142657.png|Hegde & Keenan (2011)|300]]

* Protein is passed to Get1/Get2 (CAML-WRB in mammals) heterodimer in ER membrane, which are membrane integrases that insert hydrophobic sequences into the membrane 
    * #experimental_evidence Mariappan et al (2011) reconstituted the minimum set of factors required for TA protein insertion using purified, recombinant Get1, Get2, Get3
    * Long flexible N terminus of Get2 captures ADP-bound Get3 with TA protein
    * Get3-TA complex is transferred to Get1, which wedges open the hydrophobic groove formed by the Get3 α-helical domains from each subunit to promote substrate and ADP release 
* Receptor binding releases TA from Get3/TRC40, and subsequent binding of a new ATP molecule is required for its complete dissociation, freeing it for another round of targeting 
* **ATPase cycle of Get3**. As is the case for SRP, nucleotide state of Get3 is important to regulating its interactions – ”Some of these interactions subsequently change the nucleotide state. This allows Get3 to proceed unidirec­tionally through its cycle of conformational changes and thereby selectively bind substrate in the cytosol and release it at the membrane”
    * In cytosol, Get3 is in ATP-bound closed state, which is preferentially binds to Get4 
    * Once loaded, TA substrate locks Get3 in a closed state 
    * TA substrate possibly stimulates ATP hydrolysis, generating a committed ADP-bound Get3-TA complex 
    * This complex is captured by Get2 and transferred to Get1. This transfer state relies on ATP having already been hydrolysed, as binding site for Get1 on Get3 is partially buried when it is bound to ATP 
        * Timing of ATP hydrolysis not particularly clear – it must occur after substrate binding to Get3 and before binding to Get1 
        * Possible that timing may form a point of regulation via kinetic proofreading – if hydrolysis is slow, weak substrates will dissociate before hydrolysis can occur to target Get3 to Get2/Get1 
    * Get1 binding then promotes Get3 release of ADP to form the open conformation → substrate release 
    * Rebinding of ATP then dissociates Get3 from Get1. 
![[Pasted image 20221222142742.png|500]]

#### ER Membrane protein Complex (EMC) pathway 
* For proteins with low hydrophobicity TMDs in the C-terminus (i.e. tail-anchored)
* After translation, calmodulin acts as a cytosolic chaperone to bind to the TMD 
    * Calmodulin contains a flexible Met-rich helical scaffold that can bind a broad range of peptide sequences, similar to SRP 
* The proteins are held in the cytosol with chaperones before being transferred to the endoplasmic reticulum membrane complex (EMC), which acts as a membrane insertase
    * #experimental_evidence In their review, Guna et al (2022) suggest that the Met-rich cytosolic loops of EMC3 and EMC7 act as a landing site to bind to and shuttle transmembrane proteins into the bilayer, however there is insufficient experimental evidence currently 
    * EMC also contains a hydrophobic groove to connect the cytosol with the hydrophobic core of the bilayer for insertion 

#### SRP-independent targeting (SND) pathway 
* Can compensate for loss of both SRP and GET pathways 
* Mechanism is not yet clear, but a study by Aviram et al (2016) proposed that the ribosome-associated SND protein 1 (Snd1) may capture nascent substrates, while ER-localised proteins Snd2 and Snd3 that form a complex with the translocon could be involved in substrate capture and transfer to the translocon 
* Conserved in mammals 
* #experimental_evidence Aviram et al (2016) used proximity-specific ribosome profiling to determine the substrate range of SND pathway 
    * Proximity-specific ribosome profiling – “utilizes a biotin ligase (BirA) localized to a subcellular location, such as the surface of the ER or the mitochondrial outer membrane, to label ribosomes at this location. Subsequent affinity purification of labeled ribosomes and sequencing of ribosome-protected mRNA fragments provide a snapshot of translation at that subcellular location.” See ([[A1 Mass Spectrometry and Proteomics#^013483|proximity tagging]]) 
    * In Δsnd yeast strains, some transcripts were depleted from the ER membrane 
    * Transcripts with an N-terminal transmembrane domain (TMD) (i.e. within the optimal recognition window of SRP26) were not depleted, whereas proteins with more downstream TMDs were depleted in Δsnd strains

### Some proteins may be recognised by more than one pathway 
* May allow for a greater level of regulation and efficiency in protein targeting
* Creates redundancy – in case one pathway becomes dysfunctional, other can still be used 
    * #experimental_evidence E.g. Aviram et al (2016) showed that overexpression of SND pathway rescues lethality caused by loss of SRP pathway 

## Error correction pathways ensure that ER targeting is high fidelity
* Not only are membrane proteins correctly taken to the ER, non-membrane proteins are also prevented from being taken to the ER 
* Despite the above described mechanisms for fidelity, incorrect cargo is on occasion taken by the SRP to the ER, and these errors must be corrected 
    * “As with any molecular recognition event, a degree of inefficiency is inevitable because of intrinsic limits on specific binding. Most protein targeting pathways face the additional problem that targeting signals are degenerate and not sequence-specific (von Heijne 1985, 1995). 
    * "Furthermore, the targeting signals for different destinations can share a degree of similarity, risking inappropriate recognition. Thus, even under optimal conditions, protein targeting can fail for a proportion of nascent proteins. Because proteins in the wrong cellular compartment are at risk of inappropriate interactions, unregulated function, or aggregation, they must be promptly recognized and either degraded or rescued.” (Hegde & Zavodsky 2019) 
* ER-targeted cargo is also sometimes taken incorrectly to other organelle compartments, which must be degraded
    * E.g. Costa et al (2018) – Upon auxin-induced degradation of SRP72 to deplete SRP, used proximity-specific ribosome profiling to find that transcripts normally targeted to ER were mislocalized to mitochondria.  

### ER-associated degradation (ERAD) pathway 
#comment Needs expansion 

### ER proteins taken to cytosol – Bag6-mediated proteosome degradation 
* Mislocalized ER-destined proteins were found to interact with Bag6 (Hessa et al 2011) 
* Bag6 interacts with E3 ligase RNF126 to mediate the ubiquitination of mislocalised proteins → degradation by proteasomes 
* Bag6 targets proteins with long linear hydrophobic sequences, e.g. ER targeting signals, TMDs, and carboxy-terminal GPI-anchoring signals
* Bag6 avoids competing with protein targeting factors due to kinetic reasons 
    * E.g. SRP54 located at ribosome exit tunnel, calmodulin in greater abundance, SGTA has a greater on-rate 
* Bag6 is involved in the handover of tail-anchored proteins from SGTA to TRC40 in mammals so if the handover fails to occur, Bag6 is positioned to bind to the protein 

> [!image] Quality control of mislocalised ER proteins (Shao & Hegde, 2016) 
> ![[Pasted image 20230515214238.png]]
> Chaperones capture mislocalised proteins to shield their hydrophobic elements. SGTA interacts with Bag6 complex, which bridges SGTA with the posttranslational targeting factor TRC40 (4). Tail-anchored (TA) are transferred to TRC40 for delivery to the ER. Otherwise, mislocalized proteins are captured by Bag6, which recruits the ubiquitin ligase RNF126 via an N-terminal Ubl domain. 

Read more at 
* [Protein targeting and degradation are coupled for elimination of mislocalized proteins | Nature](https://www.nature.com/articles/nature10181)
* [The Cytoplasmic Hsp70 Chaperone Machinery Subjects Misfolded and Endoplasmic Reticulum Import-incompetent Proteins to Degradation via the Ubiquitin–Proteasome System](https://www.molbiolcell.org/doi/full/10.1091/mbc.e06-04-0338?keytype2=tf_ipsecsha&ijkey=d2a70c2ce9e53ce49e548fab85c902e125132f03)

### ER proteins taken to mitochondria
* Msp1
    * Msp1 is a membrane-anchored AAA-ATPase that localises to mitochondria and peroxisomes 
    * May function in local organelle surveillance by extracting mistargeted tail-anchored proteins
    * Proteins are extracted in an ATP-dependent reaction that pulls the protein out of the membrane through a pore formed by homohexamerisation of the ATPase domain 
    * #experimental_evidence Okreglak & Walter (2014) – Msp1 prevents the accumulation of Pex15 in the mitochondria, which is normally targeted by the Get pathway – in Δmsp1 cells, GFP-Pex15 is localised to mitochondria, while overexpressing Msp1 in Δget3 cleared mislocalized Pex15 from the mitochondria 
* Ubiquilin-mediated proteasome degradation 
    * Binds hydrophobic elements, e.g. TMDs and signal sequences
    * Recruit an unidentified ubiquitin ligase 

### Non-ER proteins taken to ER
* Degradation 
    * ER resident E3 ligase Doa10 in yeast 
* Retrieval to correct compartment 
    * ER-localised factor Djp1 is involved in retrieval to mitochondria 

## Summary of mechanisms to ensure ER targeting fidelity 
* SRP54 selection of signal peptide 
* Post-translational targeting pathways 
* Error correction pathways 

## Mislocalization of ER-destined proteins can result in disease
#comment Needs expansion 

# Translocation into the ER 
## Protein topologies 
![[Pasted image 20221222155340.png|625]]
- Membrane proteins contain transmembrane domains (TMDs) that do not translocate fully across the translocon, such that they integrate into the membrane
- Secretory proteins translocate fully across the membrane into the ER lumen 
- For polytopic proteins, each TMD has to follow each other in N to C terminal succession. 
- "Positive-inside rule" – positively charged residues preferentially occur at the cytoplasmic end of TMDs 

## Sec61 complex 
### Structure of Sec61 
- The translocon contains a heterotrimer of three proteins known as Sec61α, β, γ in mammals
- Channel is formed at interface of two pseudosymmetric antiparallel halves of Sec61α
- There is a lateral gate at the front side of the Sec61 complex
- The back of the Sec61 complex is braced by the diagonal TMD of Sec61γ with Sec61β on one side 
- Central channel is occluded by a short plug helix displaced during translocation 

| Mammals | Yeast        | Prokaryotes/Archaea | Function in yeast                                                           |
| ------- | ------------ | ------------------- | --------------------------------------------------------------------------- |
| Sec61α  | Sec61p/Ssh1p | SecY                | Ssh1p is a co-translational translocon. Sec61p is post and cotranslational. |
| Sec61β  | Sbh1p/Sbh2p  | SecG                | Sbh1 is a GEF for SRβ                                                       |
| Sec61γ  | Sss1         | SecE                | Sss1 regulates oligosaccharyl transferase attachment to translocon          |

### Translocation of Type I membrane proteins across Sec61 (single pass/first TMD)
- After recognition by SRP, SRP is brought to SRP receptor (SR) 
- Handover of the ribosome from the SRP-SR complex to the Sec61 complex occurs. This handover is not completely understood – how is the hydrophobic components shielded from the cytosol during handover? 
- Polypeptides insert into Sec61 translocon with the N-terminus first. 
- At first, TM2 helix of Sec61 blocks the entry pore of the Sec61 complex
	- This is a similar mechanism to an [[C1 ER Targeting and Integration#^e70f4d|earlier step of the SRP targeting pathway]].
- When Sec61 first binds, it induces a conformational change that partially opens the Sec61 lateral gate without displacing the central plug
- When a translocating chain starts to move through Sec61, it rearranges to the "engaged" conformation. The signal peptide becomes integrated into the pore itself, displacing the TM2 helix and replacing its interactions with helices 7 and 8. This "trigger`[`s`]` a rotation that opens the central pore both axially across the membrane and laterally towards the lipid bilayer"  ^0635c1
	- Displacement of the TM2 helix acts as a regulatory step as only a sufficiently hydrophobic sequence would be able to displace TM2. The signal peptide is comparably hydrophobic and is able to do so, simultaneously widening the pore to allow polypeptides to pass through  
- **Identification of TMDs for insertion into membrane vs translocation into ER lumen.** Sec61 selects and inserts TMDs into the ER membrane via a lipid partitioning mechanism. During translocation, the lateral gate samples open and closed states, allowing the polypeptide to periodically sample the membrane. If a polypeptide region is hydrophobic enough, it will be inserted into the ER membrane and become a TMD, and if it is not, it will remain in the lumen. This gating process is probabilistic, and is also not entirely dependent on hydrophobicity, despite being an important factor. Additional protein factors apart from Sec61 may also be involved in TMD selection. 
	- #experimental_evidence Hessa et al (2005) developed a technique to study translocon selection of TMDs. Engineered polypeptide segments (H-segments) were fused to the lumenal P2 domain of integral membrane protein leader peptidase (Lep). These H segments contain two engineered Asn-X-Ser glycosylation sites (G1 and G2) that can only be glycosylated when they are in the lumen of the microsomes. If only G1 is glycosylated, then all three TMDs were inserted, but if both G1 and G2 are glycosylated, then the third TMD was not inserted. The number of glycosylations could be determined using gel assays, since a double glycosylation would result in a higher MW protein isoform. From the gel assays, insertion could be quantified to determine an apparent free energy of insertion. 
	  ![[Pasted image 20221223021519.png|600]]
	  - #experimental_evidence In experiments carried out by Hessa et al (2005), different H segments were designed to have different levels of hydrophobicity by varying the identity of the amino acid residue placed in the middle of the H segments. They found that hydrophobicity correlates well with free energy of insertion, though it wasn't a perfect correlation. 
		  - The importance of hydrophobicity in selection of TMDs for insertion by the translocon due to interaction between the TMD and surrounding lipids. 
	  - #experimental_evidence Apart from overall hydrophobicity, the particular sequence of amino acids within the TMD is important as well. Hessa et al (2005) introduced an Arg residue at different positions along the H segment sequence and determined the apparent free energy of insertion for each sequence, and found that there was large variation in the free energy across the sequence. This is because varying the position of Arg varied the distance of the charge from the wet bilayer interface, with a greater distance resulting in greater energetic cost of insertion. 
	  - Many TMDs in polytopic MPs have free energies that are positive, suggesting that they are energetically costly to insert, and yet they are inserted into membranes, which suggests that TMDs may rely on interactions with neighboring TMDs for insertion 
	  - Despite knowledge of the factors that affect TMD insertion, details of partitioning mechanism are unclear. 

### Translocation of Type II membrane proteins across Sec61 (single pass/first TMD)
- For type II proteins, the first TMD initiates SRP-mediated targeting and engages Sec61 in a similar way to the signal peptide 
- The polypeptide downstream from the TMD is then translocated through the Sec61 channel 
- For single pass proteins, completion of translocation and TMD partitioning is sufficient 
- For multipass proteins, the second TMD enters Sec61 when it emerges from the ribosome and inserts into the membrane in N<sub></sub><sub></sub><sub>exo</sub> topology similar to first TMD of type I proteins 
	- If both TMD1 and 2 have partial hydrophilic character, they can insert together. 
- **For secretory and type II membrane proteins**, the polypeptide folds to form a hairpin initially in the lumen of the translocon prior to signal peptide cleavage, while type I membrane proteins do not form a hairpin. Whether the polypeptide forms a hairpin or not is determined by the charges around the transmembrane domain, with positive charges preventing the hairpin. This ensures the proteins are inserted in the correct orientation in the membrane. 

### Experimental evidence for Sec61 translocation model 
#### Reconstitution studies 
- Reconstitution of secretory protein translocation into liposomes can be achieved with only the SR and Sec61p complexes *in vitro*, though other proteins are involved *in vivo* ^e7a4a8
	- #experimental_evidence Görlich et al (1993) – Polypeptides that are successfully translocated into liposomes are resistant to protease digestion, so no digestion is an indicator of successful translocation. The researchers synthesised preprolactin, a secretory protein, *in vitro*, and measured the synthesis of the protein under different concentrations of SR and presence/absence of Sec61p. They found that in the presence of Sec61p, as SR complex increases in concentration, more full length prolactin was observed as more protein ribosome nascent chain was brought to the liposome and released to Sec61p. When protease was then added, only prolactin was resistant to protease, while preprolactin was sensitive, as prolactin can only be created when PPL is translocated into the liposome and has signal peptide cleaved off by a peptidase to form prolactin. 
- Reconstitution of type I membrane proteins can be achieved with SR, Sec61p, and TRAM *in vitro*, with other proteins involved *in vivo*
	- #experimental_evidence Görlich et al (1993) – Used VSV-G protein that has a C-terminal TMD. Using the same protease test for translocation [[C1 ER Targeting and Integration#^e7a4a8|as described above]], found that translocation was only successful when SR, Sec61p-complex, translocating chain associated protein (TRAM) were all present.

#### Crosslinking studies 
- Translocation through the translocon can be arrested at diferent points along the polypeptide by truncating the gene at various points before the stop codon (e.g. using restriction sites), which prevents the ribosome from dissociating from the polypeptide to release it through the translocon. This results in the polypeptides of varying lengths being translocated through the translocon 
- A lysine residue can be replaced with a modified lysine containing a UV activated crosslinking reagent, using a modified Lys-tRNA. This can be used to crosslink to proteins in the vicinity of the lysine. Since polypeptides of different lengths are used, the assay can determine what proteins interact with the polypeptide at different timepoints during translocation 

![[Pasted image 20221222150908.png|475]]

- #experimental_evidence This method was used to show that polypeptides form a hairpin while translocating through Sec61. In a longer polypeptide (187mer) with no signal peptide, initially saw a region crosslinking to Sec61α. However, in a shorter polypeptide (132mer) that still contains the signal peptide, there was a second region of crosslinking, suggesting the formation of a hairpin structure prior to signal peptide cleavage

#### Structural studies 
- #structural_evidence **X-ray crystal structure** of SecY has a hydrophilic pore, with conserved amino acids found towards the centre of the pore rather than towards the outside facing lipid, suggesting that the important interactions are in the core. There is also a small α-helix (TMD2a) present in the pore that blocks the pore in the closed state. 
- #structural_evidence **Cryo-EM** of stalled translocation intermediate using canine ribosome-Sec61 with secretory protein preprolactin was used to determine the structural changes that occur in Sec61 during translocation ([[VoorheesHegde_2016]]). The same arrest method from the crosslinking studies was used. Cryo-EM showed that Sec61 rearranges into the [[C1 ER Targeting and Integration#^0635c1|"engaged" conformation]] and confirms the hairpin structure suggested by crosslinking studies 

## ER membrane complex (EMC) inserts first TMD of Type III and tail-anchored proteins 
- There is conflicting evidence on whether Sec61 is involved in the insertion of Type III membrane proteins
	- How type III TMDs are inserted into the ER membrane is unclear. 
	- #experimental_evidence Cross-linking experiments with mammalian ER and reconstitution experiments with purified Sec61 suggested that TMDs of Type III are inserted via Sec61 lateral gate concurrently with N-tail translocation through Sec61 channel 
	- #experimental_evidence However, type III protein insertion in mammals is not affected by biochemical or genetic Sec61 depletion, or by Sec61 channel inhibitors.
	- #structural_evidence Additionally, cryoEM of type III protein at point of insertion showed closed Sec61 lateral gate 
- This conflicting evidence may be explained by the fact that Oxa1 family members are involved in insertion of Type III proteins, e.g. EMC 
	- #experimental_evidence EMC KO results in insertion of type III proteins in N<sub>cyt</sub> topology, presumably by Sec61 
- **Structure of EMC.** Oxa1 family members contain a hydrophilic vestibule that forms a half-channel to facilitate translocation of short polypeptide segments (< 50 amino acids)
	- The mechanism of this is unclear, but may act by thinning the membrane adjacent to the vestibule to make it easier for TMDs to insert across 
- #experimental_evidence Proteomic analysis combined with crosslinking experiments suggested that multipass proteins, particularly those with bulky hydrophilic amino acids, interact with EMC 
- EMC may be involved in translocation or chaperoning of some multipass proteins, particularly those with ==TMDs that contain charged and/or bulky residues== (e.g. transporters, which contain charges residues to create hydrophilic pores for solute delivery)
	- TMDs are not fully hydrophobic, so it is energetically unfavourable for a TMD to be isolated in a hydrophobic lipid bilayer, and usually they interact with other protein domains or even hydrophilic pores. Inserting a TMD into a lipid bilayer directly without other TMDs to interact with may result in incorrect protein folding. As such, other proteins near Sec61, including EMC and TRAM, may chaperone these new TMDs until other TMDs are inserted, allowing the whole protein to fold correctly in a lipid environment. 
	- #experimental_evidence [[ShurtleffEtAl_2018]] used proteomics approaches to demonstrate that the EMC is involved in translocation of multipass proteins. Using proximity-specific ribosome profiling, they showed that the EMC engages multipass proteins cotranslationally, and also remains associated with the proteins after translation  to protect them from degradation by [[C1 ER Targeting and Integration#ER-associated degradation (ERAD) pathway|ERAD]] and to allow for recruitment of chaperone (see orange helix in diagram). 
	  ![[Pasted image 20221223025756.png|550]]
- EMC is also required for insertion of the first TMD of certain polytopic proteins, without reliance on Sec61. This then establishes the topology of subsequent TMDs. 
  ![[Pasted image 20221223031826.png|500]]
	-  #experimental_evidence Chitwood et al (2018) – Used reconstitution studies of β1 adrenergic receptor (β1AR) biogenesis to show that EMC is required for cotranslational insertion of the first (N<sub>exo</sub>) TMD, and without EMC there are significant errors in TMD1 insertion. They used a truncated β1AR that consisted of just the first TMD, and found that this construct was only glycosylated at the N-terminus 50% of the time in ΔEMC microsomes, suggesting a significant failure in insertion. 
- EMC has also been shown to [[C1 ER Targeting and Integration#ER Membrane protein Complex (EMC) pathway|insert tail-anchored membrane proteins]] into the ER post-translationally 

## Determinants of protein topology 
- Insertion of the first TMD necessarily constrains orientation of downstream TMDs as they alternate between N<sub>exo</sub> and N<sub>cyt</sub> 
- The first TMD is oriented based on three parameters
	- Positive inside rule – positive charges that flank a TMD tend to be retained in the cytosol 
	- Long or folded N-terminal tails are retained in the cytosol 
	- More hydrophobic TMDs tend to be inserted in N<sub>exo</sub> topology if not constrained by first two factors 
- However, the mechanistic basis for why these parameters affect topology of the first TMD is unclear 
	- According to a new hypothesis proposed by Smalinskaite and Hegde (2023), topology is determined mechanistically by a two-step model. Involving both EMC and Sec61.
	- After SRP-mediated targeting, Oxa1 family member encounters nascent chain first, and inserts preferred substrates (not positively, short N-tails ) in N<sub>exo</sub> topology 
	- Substrates with positively-charged or long N-tails would tend to be poor substrates due to repulsion by positive charges in the hydrophilic vestibule. 
	- These rejected substrates bind to Sec61 instead, which inserts substrate in N<sub>cyt</sub> orientation. Positive charges flanking TMD are retained in cytosol via interactions with phospholipids or phosphate backbone of rRNA ![[Pasted image 20221222223903.png|450]]
		- #experimental_evidence Loss of EMC influences topology of N<sub>exo</sub> TMDs
		- If there is only a transient window for EMC-mediated insertion before reaching Sec61, this could explain why high hydrophobicity TMDs favour N<sub>exo</sub> topology, since they are presumably inserted more rapidly 
- For subsequent TMDs, insertion of the first TMD constrains the orientation of the subsequent TMDs, since TMDs have to be inserted in alternating orientation. This is why topology determination of the first TMD is so important. 
- Machine learning could be employed to generate a rules table for signal sequences 

## Insertion of late TMDs in multipass proteins 
- How these subsequent TMDs are inserted mechanistically is also ambiguous. 
- In the classic **iterative model** for multipass protein insertion, subsequent TMDs use Sec61 in similar way to first TMD. The next TMD would engage the lateral gate of Sec61 in N<sub>cyt</sub> topology and pass into the membrane (if selected). The N-flank is constrained to the cytosol due to N<sub>exo</sub> topology of previous TMD, while C-flank is translocated through Sec61 until subsequent TMD emerges and inserts into membrane in N<sub>exo</sub> topology 
	- Cytosolic loops are extruded through gap between Sec61 and bound ribosome
	- Luminal loops translocated through Sec61 channel 
	- All TMDs pass through Sec61 lateral gate 
	- TMDs interact with each other to shield hydrophilic regions ![[Pasted image 20221222223922.png|450]]
		- #experimental_evidence Immunodepletion of Sec61 showed that Sec61 was required for model signal peptides and type II proteins; purified Sec61 was also sufficient in a reconstituted system for model signal peptides, type II proteins, type III proteins; Sec61 inhibitors affect signal peptide and type II protein insertion 
- However, some evidence appears to repudiate this classical iterative model, and suggest that **subsequent TMDs are inserted in a Sec61-independent, EMC-dependent manner** 
	- Late TMDs are less hydrophobic than early TMDs, and cannot open Sec61 when tested out of native context
	- Late TMDs of Type III proteins are not sensitive to inhibition of Sec61 – unexpected, since iterative model proposes that later TMDs of Type III would use Sec61 even if first TMD used EMC 
	- Multipass proteins can be entirely inserted by Oxa1 in mitochondria as long as the translocated domains are not too long (remember that Oxa1 family member insertases are constrained by length)
		- In GPCR family, only 1 of the 106 translocated domains longer than 70 amino acids residues between two TMDs; rest are located at N-terminus between signal peptide and TMD1, and so are necessarily translocated through Sec61. This suggests that there is a bias against long inter-TMD loops 
		- Experiments in *E. coli* suggest that some multipass proteins could have TMDs inserted by Oxa1 family insertases if the first translocated domain is short, e.g. MscL first two TMDs and its short intervening loop are translocated by YidC 
		- Need eukaryote experiments 
		- Need genome-wide analysis of translocated loop length with accurate topology information (from structural studies) to resolve the model of how subsequent TMDs are inserted 
- Chaperones involved in stabilising multipass insertion intermediates are also not well understood 
	- However, chaperones involved in stabilising protein insertion intermediates are not well understood 
	- Oxa1 family members could be candidate chaperones, using hydrophilic vestibule to stabilise hydrophilic regions of TMDs (see [[C1 ER Targeting and Integration#ER membrane complex (EMC) inserts TMDs of polytopic proteins and tail-anchored proteins|EMC insertion]])
		- #experimental_evidence Nascent inserting TMD can be cross-linked to YidC 
	- TRAM1 could also be a chaperone
		- #experimental_evidence Within cross-linking distance of signal peptides and TMDs at time of insertion 
	- PAT complex – heterodimer of Asterix and CCDC47 
		- Asterix interacts with multipass TMD during substrte folding 
		- PAT is specific to multipass proteins due to specificity for semihydrophilic TMDs, found in all multipass proteins 
		- #experimental_evidence PAT complex depletion partially impairs biogenesis of several unrelated multipass proteins but not single-TMD proteins 
- A **multi-pass translocon involving Oxa1 protein** may specialise in multipass proteins instead ![[Pasted image 20221222223940.png|450]]
	- Involves TMCO1, an Oxa1 family member 
		- #experimental_evidence mRNA translated by ribosomes attached to TMCO1 were strongly enriched for multipass membrane proteins 
	- Also involves CCDC47, TMEM147, Nicalin and NOMO 
		- #experimental_evidence Mass spectrometry of ribosomes attached to TMCO1 
	- Asterix, TMCO1 and C20Orf25 surround a lipid cavity behind Sec61 via hydrophilic surfaces, which may distort and thin the membrane, thus reducing the barrier to translocation 
		- Given the positioning of Asterix, TMCO1 and C20Orf2, the TMDs that emerge from the ribosome may be inserted pairwise into this backside lipid region, as they can be stabilised by the hydrophilic surfaces of the three proteins (needs experimental confirmation)
- Smalinskaite & Hegde (2023) propose a new speculative  model for multipass protein insertion that **combines the iterative model involving Sec61 and the multipass translocon model**. 
	- After insertion of the first TMD (mechanism depends on Type I, II, or III), the inserted TMD(s) would reside at back of Sec61 
		- #structural_evidence Cryo-EM of type III protein immediately after insertion showed unoccupied lateral gate and TMD between back of Sec61 and OST. 
			- #experimental_evidence This would explain why TMD1 in a type III multipass protein cross-links to Sec61γ 
		- Relocation of the first TMD(s) to the back would also facilitate interaction with the PAT complex located on this side of Sec61 
	- Multipass TMDs with short translocated loops continue to be inserted by Oxa1 family protein (e.g. TMCO1) in multipass translocon 
	- Multipass TMDs with long translocated domains are inserted by Sec61 lateral gate (since it doesn't have a length constraint)
		- Long loop is translocated through Sec61 until next TMD emerges to be inserted in N<sub>exo</sub> topology 
		- For Sec61 to be accessed, the multipass translocon (particularly CCDC47) would need to be displaced; how this happens has not been determined 
			- Smalinskate & Hegde (2023) speculate that displacement could be triggered by accumulation of non-translocated polypeptide in the space between ribosome and translocon 
	- Hence, =="Sec61 and Oxa1 family proteins collaborate to insert different parts of a multipass protein depending on the features of the TMDs and translocated flanking domans"== (Smalinskate & Hedge 2023)

# Glycosylation 
## Functions of glycosylation 
- Functions of glycosylation are often unknown because it is difficult to study the structure due to the diversity in glycan architecture. Glycans are not directly genetically encoded and depend on species and cell type. 
- Assisting protein folding ^bf0c86
	- Glycans are very hydrophilic. If a protein is glycosylated, it won't fold into the interior, and will want to be retained on the exterior of the protein, thus restraining the conformations that the protein can access
- Protein quality control in the ER export – [[C2 PTMs and Protein trafficking#Protein folding in the ER has a high error rate|N-glycans]]
- Maintaining membrane asymmetry 
	- After being flipped, a lipid/protein can be glycosylated to make it harder to scramble 
- Facilitating protein secretion and protein sorting to final cellular destinations 
- Protection of proteins form proteases or controlling end-of-life 
- Protection of cell and tissue from the environment (mucus, matrix)
- Cell adhesion 
	- Diversification of glycosylation thought to play a major role in the evolution of multicellularity 
- Recognition for glycoprotein interaction – important in development, immunity 
	- E.g. Oocytes contain surface glycans on the zona pellucida that are multivalent sialyl-Lewis<sup>x</sup> members of the bi-, tri- and tetra-antennary glycan families. Sperm bind oocytes based on unique oocyte glycans. ![[Untitled-2022-12-22-1431.png]]
		- Sialyl-Lewis X is a tetrasaccharide composed of a sialic acid, fucose, and N-acetyllactosamine 
		- Antennary → comes from word "antenna" → number of branches in the glycan. 
	- E.g. Pathogen recognition of host is often through glycans. Humans have lost the ability to synthesise N-glycolyl neuraminic acid, so sialic acid types are different in humans and animals, which may have been an adaptation to avoid zoonoses.  For example, sialic acid linkages on glycans are different in man and birds, with H5N1 avian flu recognising glycans with α2,3 while humans have largely α2,6 linked sialic acid. This has implications for diet since dietary sugars (including sialic acids) are incorporated into our glycans, so vegans may have different cell surfaces. 
	- Glycans on pathogens, cancer cells may be druggable targets 
	- Issues with transfusion, transplantation, xenotransplants 

## Mechanisms of ER glycosylation 
### Glycosyltransferases
- Each sugar linkage is synthesised by a specific glycosyltransferase (GT) enzyme that uses mostly sugar nucleotides, e.g. UDP-glucose, GDP-mannose 
- Due to the diversity of glycan structures, there are a large number of GTs encoded into genomes, and GT sequences are highly divergent, which can make them difficult to identify based on amino acid sequence alone (i.e. bioinformatics approaches)
	- High selection pressure – red queen effect? 
- Despite this diversity in primary sequence, structures of known GTs fall into one of three protein fold groups, GT-A, GT-B, or GT-C (which is rare)

### N-linked glycosylation 
- Attachment of oligosaccharide to a nitrogen (N) atom of an Asn residue in a particular glycosylation site, Asn-X-Ser/Thr 
- This type of glycosylation is uniquely found on the lumenal/extracellular domains of proteins 
- The structure of the oligosaccharide is evolutionarily conserved, consisting of Glc3-Man9-GlcNAc2 
  ![[Pasted image 20221224163956.png|300]]

#### Synthesis of precursor oligosaccharide
![[Pasted image 20221224171511.png|500]]
- **Role of dolichol**. Dolichol is an isoprene lipid that acts as a membrane anchor for the oligosaccharide, and the sugar is transerred from the dolichol donor to the glycosylation site. Dolichol is also involved in the transfer of monosaccharides to the forming oligosaccharide-dolichol carrier. 
	- Dolichol localises biosynthetic pathway to the ER 
	- Synthesised by cis-prenyltransferase via the addition of C5 isoprenoid units to farnesylpyrophosphate 
	- Chain length of dolichol is species-specific, and determined by cis-prenyltransferase 
- Glycosyl residues enter biosynthetic pathway as nucletide activated sugars (Leloir sugar nucleotides), UDP-GlcNAc, GDP-Man, UDP-Glc 
- **Addition of GlcNac**. First glycosylation step is the addition of GlcNac-P to dolichol phosphate (Dol-P) by Alg7p on the cytosolic face of the ER using UDP-GlcNac. Second GlcNac added by a protein complex encoded by *ALG13* and *ALG14* loci 
	- #experimental_evidence Accessible to protease/EDTA  ^ee2aee
- **Addition of mannose (cytosolic)**. First 5 mannosyl transferases use GDP-mannose. These transfer steps occur on the cytosolic face of the ER since no ER GDP-mannose transporter has been detected. 
	- First Man added by *ALG1* encoding β-1,4-mannosyltransferase 
	- Next two branching mannose added by Alg2p. α-1,3 is added before α-1,6; how this ordering is achieved is not understood 
	- Last two mannose added by *ALG11* 
	- **Addition of first mannose is cytosolic.** #experimental_evidence The activity of ALG1, the first mannosyltransferase, is sensitive to protease and EDTA. Also, the N-glycosylation sites are not used, suggesting that the region around the catalytic site of the protein is in the cytosol, since N-glycosylation only occurs in the ER. Additionally, we predict that the more positively charged end of the TMD is in the cytosol.  ^904f96
- **Flipping of dolichol.** After addition of first 5 mannoses, GlcNAc<sub>2</sub>Man<sub>5</sub> intermediate is translocated across the ER membrane. 
	- Flipping is required so that N-glycan can be co-translationally attached to protein being translocated across ER membrane  
	- Apart from translocation of GlcNAc<sub>2</sub>Man<sub>5</sub>, dolichol also has to be flipped at 3 in other situations, 1) After attachment of mannose in the lumen, 2) After attachment of glucose in the lumen, and 3) For recycling of dolichol to the cytoplasmic surface after the oligosaccharide has been transferred to the protein. 
- **Addition of mannose (luminal).** 
	- Mannose is added from Dol-P-Man, which is synthesised on the cytoplasmic side of the ER by Dol-P-Man synthase (Dpm1). Dol-P-Man is flipped into luminal side by an as yet identified flippase 
	- b antenna: *ALG3* α-1,3 mannosyltransferase -> *ALG9* α-1,2 mannosyltransferase 
	- c antenna: *ALG12* α-1,6 mannosyltransferase -> *ALG9* α-1,2 mannosyltransferase
	- **Last 7 steps of oligosaccharide synthesis are luminal**. #experimental_evidence Lectins (e.g. Concanavalin A) are glycan-binding proteins that can be used to study the orientation of oligosaccharide intermediates. If the lipid precursor is oriented to the cytosol, it can bind to ConA, and if the precursor can only bind to ConA in the presence of the detergent TX100, suggests that orientation is luminal, since detergent dissolves the membrane and thus allows access to ConA. GlcNAc<sub>2</sub>Man<sub>6</sub> to GlcNAc<sub>2</sub>Man<sub>9</sub> bind to ConA only if TX100 is present, which indicates that these intermediates are luminal.  ^4090c2
- **Addition of glucose (luminal)** by Alg6p at a-antenna, then Alg8p adds second α-1,3 Glc residue, lastly Alg10p adds α-1,2 Glc
	- Glucose is transferred from Dol-P-Glc,which is synthesised on cytoplasmic side of ER by Dol-P-Glc synthase. Flippase not identified. 
- **Transfer of complete oligosaccharide to protein luminally.** The oligosaccharyltransferase (OST) is associated with Sec61 and is located in the ER lumen. OST contains many subunits, with Stt3 as the catalytc subunit. It transfers the oligosaccharide from the dolichol carrier to the amide group of Asn in motif NxS/T (x = any amino acid except proline)
	- #experimental_evidence In bacteria, the Stt3 homolog catalyzes the transfer of a variety of undecaprenol-P-P-linked glycans to N-X-S/T motifs of proteins 
- **Identifying GTs**. #experimental_evidence [[HuffakerRobbins_1982]] – Yeast incorporate a lot of mannose into N-linked glycans and cell surface proteins. In mutants that cant glycosylate protiens, they incorporate less mannose. Generate a library of yeast mutants and grow in 3H mannose. The less mannose incorporated, the less radioactivity they are exposed to, so the more viable they are. Radioactive-resistant mutants that survive likely have mutations in enzymes involved in glycosylation. Altered glcyosylation can be confirmed using SDS-PAGE since proteins that are not glycosylated properly will have lower molecular weight. Using this method, authors were able to identify different complement groups that correspond to enzymes involved in the synthesis pathway, e.g. alg1 accumulated lipid-linked GlcNAc2, suggesting it adds the first mannose in the pathway.  ^89421b

#### Topology of lipid-linked oligosaccharide assembly 
- Because of bipartite nature of lipid-linked oligosaccharide synthesis, two types of glycosyltransferases are involved, one that uses Leloir sugars in the cytoplasm, and one that uses Dol-P-bound sugars as a substrate in the lumen 
- Lipid-linked oligosaccharides must be flipped across the ER membrane, resulting in asymmetry in the glycan topology of the ER membrane. 

#### Substrate specificity of OST 
- *In vitro*, Dol-PP-GlcNAc2 is the minimal oligosaccharide structure accepted by OST
- *In vivo*, OST prefers the fully assembled N-linked oligosaccharide 
	- The "capping" α-1,2 Glc on a-antenna of N-linked oligosaccharide is the requirement for substrate recognition by the OST 
	- #experimental_evidence Oligosaccharide structure transferred in N-glycosylation pathway exhibits high conservation in eukaryotic species 
- Mechanism for how LLO recognises OST is not known 
- OST is also specific to the dolichol carrier, with some flexibility
	- #experimental_evidence Truncated dolichol with only 11-12 isoprene units synthesised by heterologously expressed *G. lamblia* cis-prenyltransferase in *S. cerevisiae* did not result in a hypoglycosylation phenotype. This suggests that the truncated dolichol could also be recognised by yeast OST. However, yeast OST cannot use very short lipid carriers with only 3-4 isoprene units *in vitro*  
- OST glycosylates a large variety of protein acceptors, which contain the NxS/T motif 
	- #structural_evidence Crystal structure of bacterial OST PglB from *Campylobacter lari* in complex with peptide shows that acceptor peptide forms a 180° turn, with hydroxyl amino acid (?) at +2 position recognised by a conserved binding pocket formed by WWDYG motif. 
		- Binding pocket explains preference for NxT over NxS of OST *in vitro* 
	- But not all NxS/T sites are glycosylated; sequences around the glycosylation site may also affect glycosylation, as well as distance from a transmembrane domain or to the next N-glycosylation site
	- Analysis of bacterial OST suggests that acceptor motif has to be in a flexible domain, but many N-glycosylation sites are also found within ordered structures e.g. beta-sheets
- Glycosylation can occur before folding, as OST is located next to translocon 

#### OST isoforms 
- Different OST isoforms in mammalian cells can cooperate and act sequqentially to N-glycosylate proteins. Each isoform has a different catalytic subunit (STT3A or STT3B)
- Nascent polypeptides contact multiple OST complexes as they enter the ER lumen, which scan along the polypeptide for cognate sequons 
	- #experimental_evidence Factor VII is a glycoprotein with an obligatory cotranslational glycosylation site at N183, and a posttranslational glycosylation site at N360. In vivo pulse labelling of Factor VII suggested that when STT3A was depleted via siRNA KD, efficiency of N183 site glycosylation was reduced without affecting N360. When STT3B is depleted, N183 glycosylation not affected but efficiency and extent of N360 glycosylation reduced. 
	- STT3B is probably located more distal from the translocon than STT3A 
	- Depletion of STT3A did not eliminate cotranslational glycosylation, suggesting that STT3B can act on the skipped glycosylation sites. But because it is more distal, the efficiency was reduced. 
		- This could be useful if the glycosylation sequon is located too close to the membrane surface; for example, in pCatC, the N29 site may leave the lumenal face of the translocon too rapidly to interact with STT3A. Instead it is glycosylated by STT3B 
-  #experimental_evidence [[Ruiz-CanadaEtAl_2009]] used siRNA to knockdown specific OST isoforms. Found that STT3A needed for cotranslational glycosylation of nascent polypeptide, while STT3B needed for cotranslational glycosylation of an acceptor site adjacent to the N-terminal signal sequence, as well as posttranslational glycosylation of C-terminal glycosylation site 

#### Congenital disorders of glycosylation (CDG)
- Often lead to severe abnormalities
- Can occur at different steps of glycan synthesis 
- Assay serum transferrin for modified glycosylation using gel electrophoresis 
- Class I of CDGs involve problems with N-linked glycans
- Class II involve defects in processing N-linked glycans, mainly in Golgi 
- Creation of treatments
	- E.g. GDP-Fuc transporter can be treated with oral fucose tablets. Increases concentration of GDP-Fucose to compensate for decrease in transporter. Also shows importance of *diet

### Identification of flippases 
- Flippases are "membrane protein(s) that facilitate bidirectional, ATP-independent flipping of polar lipids across a biogenic membrane" (Sanyal & Menon, 2009)
- However as the lipid is consumed after being flipped, this flipping is effectively unidirectional 
- Flippases have been difficult to identify because they are hard to purify, and genetic and biochemical evidence often seem contradictory 

#### Man<sub>5</sub> dolichol intermediate flippase 
- Identification of the Man<sub>5</sub>-dolichol intermediate flippase/scramblase has been challenging, and has yet to be determined definitively: 
- #experimental_evidence Helenius et al (2002) suggest that RFT1 is a putative yeast scramblase/flippase for Man<sub>5</sub>-linked dolichol intermediate. Repression of RFT1 expression results in reduced N-linked glycosylation of CPY (as shown by SDS PAGE) and accumulation of GlcNAc<sub>2</sub>Man<sub>5</sub> (as shown by HPLC) ^fa86f9
- #experimental_evidence RFT1 is a member of the MOP family of transporters, which also include MurJ of peptidoglycan synthesis. Peptidoglycan synthesis in bacteria also involves synthesis of a glycan on an isoprene lipid in bacterial membrane, with sugar added on cytosolic face, and MurJ acts as a flippase to flip it out to cell wall side. Homology of RFT1 suggests it carries out a similar function.  ^49349c
- #experimental_evidence **Studying the activity of RFT1**. [[SanyalMenon_2009]] – Man<sub>5</sub> dolichol can be extracted with chloroform, methanol, and water mixture, but become insoluble when bound to Con A. In liposomes with [<sup>3</sup>H]M5 DLO treated with ConA, only 50% are extracted by solvent, since 50% are in the outer leaflet and bind Con A (as measured by radioactivity). In proteoliposomes with flippase activity, M5 DLOs in the inner leaflet will be translocated to the outer leaflet, resulting in 100% of M5 DLOs becoming resistant to solvent extraction.  ^d1176f
	- When a water-soluble analog of GlcNAc2-PP-dolichol was added, GlcNAc2-PP-citronellol, it effectively competed with the dolichol-attached lipid, reducing the rate of M5-DLO flipping. This suggests that M5-DLO flippase recognises a core component common to both molecules, probably GlcNAc2-PP-dolichol or GlcNAc-PP-dolichol
	- **Flippase activity of Rft1 was also investigated.** However, found that Rft1 was not correlated with flipping activity, as even when Rft1 was removed (e.g. via antibody-mediated depletion), flipping activity continued. This suggests that Rft1 is not the M5-DLO flippase after all
![[Pasted image 20221224221333.png|325]]
 ^bb3f7f
- #experimental_evidence Rush et al (2009) Sealed microsomes from Rft1-depleted yeast could elongate [<sup>3</sup>H]GlcNAc2-PP-dolichol to Man9GlcNAc2-PP-dolichol, as well as transport [<sup>3</sup>H]GlcNAc2-PP-dolichol<sub>15</sub> (a water soluble analog of GlcNac2-PP-dolichol) across the membrane, suggesting the presence of flippase activity despite depletion of Rft1. 
- #experimental_evidence Verchere et al (2021) – Purify fractions of proteins from ER via size chromatography, then use flippase assay on different fractions. Then look for correlations of protein abundance (via mass spectrometry) with flipping activity in that fraction. Scramblases with an activity profile that match the activity profile of the fraction are shortlisted as scramblase candidates. Each protein was purified independently and did negative subtraction assay, where each protein was removed independently from the mix (via immunodepletion or TAP-tagging) and see if it affects flipping activity. However, none of the depletions affected flipping.  ^d80579
	- The group speculated that 

#### Dolichol-linked mannose flippase 
- #experimental_evidence Sanyal & Menon (2010) set up an assay where flipping is identified if the mannose is accessible to oxidation by a carboxy TEMPO NO radical, which is membrane impermeable. Oxidised dolichol-linked mannose has greater mobility compared to non oxidised on a gel. 
- **Is the flippase Dpm1?**
	- #experimental_evidence Haselback and Tanner (1982) – At first, reconstitution analysis suggested that Dpm1 is the flippase
	- #experimental_evidence However, Zimmerman & Robbins (1993) found that the function of Dpm1 was retained even when transmembrane domain was removed, so Dpm1 unlikely to be MPD flippase 
- **Is the flippase Lec35?**
	- #experimental_evidence Lec35 MPDU1 mutants of Chinese hamster ovary cells can synthesise MPD, but cannot mannosylate M5-DLO. They also cannot C-mannosylate proteins or add mannose to GlcN-acylPI in GPI synthesis, suggesting it has a role in flipping MPD into the lumen. 
	- #experimental_evidence However, in sealed microsomes prepared rom mutant cells, these defects were not recapitulated. Lec35 permeabilised with pore-forming toxin, Streptolysin O, did not elongate M5-DLO to Man9GlcNac2-PP-dolichol 
	- #experimental_evidence On the other hand if the permeabilised cells were given Man-P-Cit, Man9GlcNAc2-PP-dolichol synthesis was possible. 
	- Lec35 unlikely to be the flippase, but regulates access of MPD to flippase? This would explain why Man-P-Cit could be used as a donor, since it would not interact with Lec35. 
- **Characterising substrate specificity**
	- #experimental_evidence Sanyal and Menon dveloped an assay for MPD flipping in a reconstituted system that uses [<sup>3</sup>H]MPD, and fund that MPD flippase is not a glycoprotein. When a water-soluble isoprenoid phosphate was added as a competitor to MPD, the flipping was inhibited by citronellyl phosphate but not neryl phosphate. Nerol has one less isoprene unit than citronellol, so MPD flippase may recognise isoprene unit of carrier lipid in addition to mannose residue. 
		- Snice citronellyl phosphate is also a dolichyl phosphate analogue, could the MPD flippase be involved in dolichyl phosphate recycling too? 
- However, protein has yet to be identified 

### GPI anchoring 
- GPIs are added to the C-terminus of extracellular proteins and act as a cell membrane targeting signal / membrane anchor 
- Protein can be released from GPI anchor by phospholipase C/D 
- Has a conserved core structure: 
	- Mammalian GPIs additionally have a PE side branch linked to the 2-position of the first α1,4-linked Man
	- There are slight variations in this structure between species and between tissues of the same species 
	- In mammalian GPI in nucleated cells Phosphoinositol moiety has two saturated fatty acid chains, while free PI in same cells have unsaturated chain at sn2 position. Saturation is necessary for association with membrane microdomains 
	- GPI in human RBCs have three fatty chains – unsaturated fatty acid on sn2, palmitoyl chain at 2-position of inositol ring (removed after attachment of GPI to protein) -> more stable association with cell membrane? 
  ![[Pasted image 20221224184008.png|400]]
  
#### GPI anchor biosynthesis 
- PIG A enzyme – GlcNAc transferase transfers GlcNAc to phosphatidyl inositol 
	- Catalytic site is on cytosolic face 
	- Product is sensitive to phospholipase C -> cytosolic 
- GlcNAc is deacetylated to GlcN by PIG-L on cytosolic face 
- (In mammalian cells) At this point, glycolipid has to be flipped across the ER membrane to face luminal surface, requiring the activity of a yet identified flippase/scramblase 
	- #experimental_evidence Kajiware et al (2008) suggested from genetic studies that yeast ARV1p is the flippase, as ARV1 deletion in yeast accumulates GlcN-acylPI, while not affecting Dol-P-Man synthesis and GPI-MT activity  
	- #experimental_evidence [[OkaiEtAl_2020]] – **ARV1 is a candidate flippase and is required for the first mannosylation**. However, KO leads to acyl-PI-GlcN accumulation. So not really clear what the function is. 
	- #experimental_evidence Vishwakarma and Menon (2005) demonstrated the flipping of GlcN-PI  in proteoliposomes reconstituted from detergent-solubilised rat liver ER. Study suggested that GlcN-PI may be transported by the phospholipid flippase in an ATP-dependent manner, rather than by a specialised GPI flippase 
	  ![[Pasted image 20221224190604.png|475]]
- Inositol acylation occurs by Gwt1/PIG-W with predicted luminal catalytic activity; inositol derived from fatty acyl CoA synthesised in cytoplasm that is then transported into ER lumen. Unknown how it is transported across into ER lumen. 
	- It is not clear whether GlcN-acylPI or GlcN-PI is flipped into the luminal side, or if both are flipped 
	- #experimental_evidence  [[OkaiEtAl_2020]] proposed that some GlcN-(acyl)PI generated in the lumen is translocated spontaneously to the cytoplasmic side of the ER membrane, and Arv1 is required to flip it back to the ER lumen, but this is unclear 
- In lumen, PIG-M transfers first mannose, PIG-V second, PIG-B third, using Dol-P-Man as the donor 
- Oligosaccharide is modified with phosphoethanolamine residues to generate GPI anchor precursor. Phosphoethanolamine is derived from PE synthesised in cytoplasm that is translocated into ER lumen by a specialised flippase 
- #experimental_evidence **Assay to identify enzymes involved in GPI synthesis**. Prepare library of mutants, and use complement killing system using antibody against GPI-anchored proteins. Mutants are resistant to complement killing. Resulted in isolation of PIG-A to PIG-Y genetic complementation groups.  ^080dcb

#### Transfer of GPI to proteins in ER lumen 
- GPI-anchored proteins have a conventional N-terminal signal peptide, as well as a C-terminal hydrophobic domain of at least 13 amino acids 
	- #experimental_evidence The C-terminal 37 amino acids of Decay Accelerating Factor is sufficient to convert a secreted protein to a GPI anchored protein 
	- Since sequences are known, can use bioinformatics to predict GPI-anchored proteins 
- The C-terminal signal is cleaved off at a consensus ω site, and glycolipid is put at new C terminus by GPI transamidase. There is a small amino acid at ω+1, ω+2, and ω+3 
	- ω-site amino acids are generally those with small side chains, i.e. G, A, S, N, D, C 
	- Hydrophilic spacer sequence with 6 or more residues starts at ω+3 site 
	- C-terminal hydrophobic sequence long enough to span ER membrane 
	- #experimental_evidence When GPI attachment signal peptide is attached to a non-GPI-AP, they are converted into a GPI-anchored protein 
- Multienzyme complex, GPI transamidase, catalyses transamidation of GPI anchor to cleaved protein. 
	- GPI-8 (aka PIG-K) is catalytic subunit for transamidation, and activity occurs in lumen. 
	- Additional subunits may confer specificity, and are essential or nearly essential for GPI attachment, but function not clear  
- Acyl group of inositol subsequently removed from the GPI 
- GPI lipid moieties remodelled to be more hydrophobic, converted to a diacylglycerol or ceramide 
- GPI anchored proteins may be targeted by the SR and/or SND pathways to the ER using N and C-terminal signals (Yang 2021)

![[Pasted image 20221224190100.png|300]]

#### Disorders in GPI synthesis 
- In humans, PIG-A deficiency can cause paroxysmal nocturnal haemoglobinuria 
- In plants, PIG-A/C mutation results in defective pollen tube germination, PIG-M mutation results in defective embryos 
- GPI synthesis is an antifungal and antiparasite drug target since biosynthetic pathways for GPI synthesis are different in different species 

### Mucin type O-linked glycosylation 
- Mucin contains a tandem repeat region rich in Ser, Thr, and Pro, which is highly O-glycosylated. Peptides have an extended "bottle brush" conformation 
  ![[Pasted image 20221224190958.png|225]]
- Mucin O-glycans (O-GalNAc) are found on many proteins. The core sugar consists of a single N-acetylgalactosamine linked to S/T though the exact addition site is difficult to predict. The glycan can be added by the Golgi by up to 20 different GTs, and the glycan can be further extended by other GTs or sulphated in the Golgi. 
	- Much greater number of GTs involved in O-glycosylation than N-glycans 

### O-mannosylation 
- Protein mannosyl transferases can recognise many different substrates, so protein motif recognition is complicated
- E.g. Cadherins, α-dystroglycan 

#### Biosynthesis of O-mannosyl glycans
- Mannosyl transferase in ER adds the first mannose to S/T in yeast from donor Dol-P-mannose. Mammals have PMT homologues (for mannosylation of POMT, dystroglycan) and the unrelated enzyme TMTC (cadherin)
- Subsequent steps require sugar nucleotide transporters and several GTs in the Golgi. 
- Glycans can then be further extended or modified in the Golgi 
- **Identification of proteins involved in α-dystroglycan glycosylation.** #experimental_evidence Jae et al (2013) – Library of human HAP1 mutants created via [[Gene trapping]], then tested for resistance to VSV infection in assay where VSV glycoprotein is replaced with Lassa virus glycoprotein. This allows VSV to recognise α-dystroglycan and infect the cells. Failure to glycosylate results in VSV resistance, hence allowing for identification of genes involved in glycosylation.  ^986910

![[Pasted image 20221224191854.png|375]]

#### Disorders in O-mannosyl glycan synthesis 
- E.g. The Dystroglycan complex binds to the lamina in muscle via laminin. Laminin binding to α-dystrolgycan requires correct glycosylation of α-dystrolgycan with matriglycan, an extension of O-mannosylation. Defects in matriglycan, an extension of O-mannosylation, can cause some types of muscular dystrophy due to aberrant glycosylation of α-dystrolgycan. 
	- One defect involves Fukutin, which is inolved in adding a ribitol 5-phosphate to the core O-mannosyl glycan. Fukutin-defective muscular dystrophy patients could be treated with oral ribitol. 
- E.g. Matriglycan is a binding site for leprosy and lassa virus entry 
	- #experimental_evidence Vesicular stomatitis virus (VSV) was able to infect human haploid HAP1 cells, a non-natural host, when the lassa virus glycoprotein was incorporated, as it was able to bind to α-dystrolgycan with matriglycan.  ^3e9a1d

## Regulation of lipid-linked oligosaccharide synthesis 
- Dolichol carrier could be recycled in a "dolichol cycle" that returns it back to cytoplasmic side 
	- May involve phosphatases
		- #experimental_evidence dolichylpyrophosphate phosphatase deficiency results in N-glycosylation deficiency 
	- If transfer of LLO by OST is rate-limiting step for N-glycosylation, then level of dolichol in ER determines LLO substrate level present in cell 
	- Rate of recycling sets level of available dolichol in cytoplasm 

## Approaches to studying glycosylation 
### Studying orientation of glycans  
- Accessibility to protease/EDTA 
	- [[C1 ER Targeting and Integration#^ee2aee|GlcNac transferase is cytoplasmic]]
	- [[C1 ER Targeting and Integration#^904f96|Addition of first mannose is cytoplasmic]]
- Use lectins e.g. ConA with detergent 
	- [[C1 ER Targeting and Integration#^4090c2|Last 7 steps of N-glycan synthesis are luminal]]

### Studying function of glycans 
- Glycans can be engineered artificially onto the surface of cells
	- #experimental_evidence Sheikh et al (2022)
- Or onto viruses
	- [[C1 ER Targeting and Integration#^3e9a1d|VSV engineered with lassa virus glycoprotein can infect human HAP1 cells, a non-natural host]]

### Identifying enzymes  
- Genetic approach – knockout gene, and develop an assay to test whether gene KO had an effect on the activity of interest 
	- [[C1 ER Targeting and Integration#^89421b|3H mannose test]]
	- [[C1 ER Targeting and Integration#^fa86f9|SDS-PAGE and HPLC]]
	- [[C1 ER Targeting and Integration#^080dcb|Complement killing system]]
	- [[C1 ER Targeting and Integration#^986910|Infection by engineered VSV]]
- Biochemical approach – characterise the activity of the active gene 
	- [[C1 ER Targeting and Integration#^bb3f7f|ConA binding to characterise flippase activity]]
	- [[C1 ER Targeting and Integration#^d80579|Protein abundance correlation and negative subtraction]]
- Bioinformatics approach – look for homology with known proteins 
	- [[C1 ER Targeting and Integration#^49349c|RFT1 homology to MOP]]
