# Questions
- To what extent do aberrations in the cell cycle machinery contribute to cancer?
- ==*Ensuring unidirectionality of cell cycle*== 
	- What mechanisms ensure that the cell cycle only goes in one direction?
	- How does the cell ensure that entry and exit from mitosis are all-or-nothing events? 
- Role of cell cycle components
	- ==SCF and APC/C ubiquitin ligases play critical roles in cell division. Compare and contrast their mechanisms of action and regulation.==
	- *==How do we know that the cell cycle results from alternating high and low Cdk activities?==*
	- ==What part do small linear motifs (SLiMs) play in the control of the cell cycle?== **SLiMs regulate the timing of protein-protein interactions, involved in phosphatase recruitment, kinase recruitment, and ubiquitin-ligase recognition. Motifs are widespread, and their modular nature, gives flexibility to integrate different signals.**
- Role of proteolysis. -> unidirectionality 

# Cell cycle engine 
## Alternation problem 
- Cells alternate between phases of DNA replication and chromosome separation 
- Exceptions 
	- Multinucleate cells do not undergo chromosome separation, e.g. megakaryocytes, placenta
	- Gametes do not undergo DNA replication after chromosome separation (i.e. meiosis)
	- Alternation of generations in plants, fungi? 

## Completion problem 
- Complete each phase before the next 
- DNA replication must be complete before chromosome separation, and chromosome separation must be complete before DNA replication
- Otherwise, DNA damage occurs 
- Checkpoints check for completion 
![[D1 DNA Replication#^25970e]]
- G2 to M progression is delayed if G2 cell is fused with S phase cell, as cell detects incomplete DNA synthesis. 

# Cdk control of the cell cycle 
- M phase cyclin-CDK 
- S phase cyclin-CDK 
- #experimental_evidence Yeast genetics (cdc mutants)
- #experimental_evidence Xenopus meiosis (MPF)
- #experimental_evidence Translational control in sea urchin eggs (cyclins)

## Cyclin activate CDKs 
- Cyclin pulls T loop out of substrate binding cleft, allowing for substrate binding 
- Residues are in place to coordinate DNA properly so that beta gamma bond of ATP can be hydrolysed
- #structural_evidence 
- In the absence of cyclin, CDKs bind ATP such that it cannot be hydrolysed, and substrates cannot bind 

## Cyclins are cyclically synthesised and destroyed
- Destroying the activator is an irreversible form of regulation as it will take many minutes for the cyclin to be resynthesised in sufficient quantities to affect the cell cycle. This lends unidirectionality to the cell cycle
- Because of cylical cyclin concentration, CDK activity alternates between phases of low and high activity. 
- When there is low CDK activity, origins of replication assemble and fire
- When there is high CDK activity, oris are repressed, and cells build mitotic apparatus 
	- Addresses completion problem 
	- Unidirectionality 
- When cyclins degrade (to irreversible turn off CDK activity)

## Cyclins bind to Short Linear Motifs (SLiMs)
- Hydrophobic patch in cyclins can bind to different substrates with Short Linear Motifs (SLiMs)
- SLiMs are 3-4 amino acids long in an unstructured region 
- Different cyclins bind to greater affinity to different SLiMs
- In addition to primary sequence motif (containing S/T), SLiM is a secondary binding motif -> increase affinity of substrate for particular cyclin 

## Cyclin-CDK complexes define the state of the cell cycle
- #experimental_evidence Temperature sensitive fission yeast 
	- Fission yeast length depends on phase of cell cycle -> Can infer cell cycle position based on length of fission yeast. Uniformly divide at 14µm
- #experimental_evidence If fission yeast is arrested at G2 (by using restrictive temperature), cdc13-cdc2 (M-cyclin and M-cdk) degraded, and you lift the arrest at G2 (by lowering to permissive temperature), fission yeast will **reinitiate DNA synthesis**
	- This shows that low levels of M-CDK corresponds to G1. As such if you degrade M-CDK, this signals to the cell to restart G1 
	- Cell thinks it's in G1 ![[Pasted image 20230407173417.png|450]]
	- If cell starts with high Cdk activity, reducing Cdk activity re-initiates DNA replication ( #comment find paper)

## Cells where only 1 cyclin is important e.g. S. pombe 
- Cyclin identity is not important, rather amount of Cdk activity regulates the cell cycle (**Threshold hypothesis**)
	- #experimental_evidence Coudreuse & Nurse (2010) – Cyclin-cdc2 fusion can drive cell cycle in absence of other cyclins. We can artificially control the amount of Cdk activity through analogue sensitive Cdc2. S/T kinases have an N-terminal lobe and C-terminal lobe; ATP binds in between them. A gatekeeper residue (bulky hydrophobic) blocks access of things other than ATP to the binding site. If this residue is mutated to a small residue, ATP binding pocket can accept bulky analogs. At the same time, no other kinase in the cell will be able to bind bulky analog as all other kinases have the conserved bulky hydrophobic residue. Analog acts as competitive inhibitor for ATP, thus can be used to control activity of kinase. 
		- Analog-sensitive Cdc2 was fused to activating cyclin to prevent complications from the two proteins having to find each other and bind 
		- All other cyclins were deleted, and found that cyclin-Cdc2 alone can drive cell cycle 
		- Testing threshold hypothesis by varying inhibitor concentration to change Cdk activity
		- Low concentrations of inhibitor block mitosis => need high Cdk activity to drive mitosis, and DNA replication unaffected
		- High concentrations block DNA replication
		- Non-degradable cyclin (Cdc13) normally arrest cells in mitosis as cells cannot degrade the cyclin. But if Cdk is inhibited, can still exit mitosis. 
- The amount of Cdk activity defines the cell state because substrates for DNA replication are recognised by higher affinity than substrates for mitosis. A low amount of Cdk activity -> only phosphorylation proteins with high affinity; low affinity need more Cdk activity.  ^44351e
	- #experimental_evidence Swaffer et al (2016) – Used analog sensitive Cdc13-CDC2 with inhibitor I-NM-PP1 to control Cdk activity. Then use mass spectrometry to measure changes in phosphorylation state across the proteome. Classify proteins that can be phosphorylated with low Cdk activity and those with high Cdk activity. 
		- G1/S substrates have higher affinity for Cdk. These proteins are phosphorylated at low concentrations of Cdk. Tend to have SLiMs with sequence RxL. RxL motif has to be certain distance away from primary motif. 

## Cells where more than one cyclin is needed e.g. S. cerevisiae, mammals  
- Can drive with 2 cyclins in budding yeast and early mammalian embryos
	- 1 cyclin to act in G1 
	- 1 cyclin to act from replication onwards 
- Cyclins determine substrate specificity by binding to SLiMs 
	- In budding yeast, Cln2, Clb3 and Clb2 recognise specific substrates
	- CLN recognises L-P, CLB5 recognises RxL, CLB2 recognisies LxF 
	- Cks subunits recognise phospho-threonine-P 
- This may be why multiple cyclins are needed, since each recognise different substrates 
- As SLiMs are very short, they can be found across the genome, and could cooperate 

![[Pasted image 20230407175711.png|500]]

### Multiple SLiMs cooperate 
- Cyclin CDKs have an extra kinase subunit called Cks that binds to C terminus of kinase and it recognises T followed by P that has been phosphorylated. And T followed by P is a CDK site. then CDK phosphorylates other sites which have lower affinity. So same kinase can phosphorylate an initial site and then other sites around it 
- This can work with hydrophobic patch to recognise other substrates 
- This sets substrates that can only be phosphorylated at high levels or at high levels
![[Pasted image 20230407233038.png|300]]
- Cooperation between SLiMs can be used on the same kinase or between different kinases ![[Pasted image 20230407233159.png]]
	- There is cooperation between CDKs and Polo kinase. There are many substrates phosphorylated by CDK, then by Polo 
	- Polo has a kinase domain with C terminal polo boxes. Polo boxes bind to S-pT or S-pS, which are often generated by Cdk. Thus, Cdk phosphorylation generates Plk substrate 
		- #experimental_evidence Goo et al (2006) – E.g. Cdk1 phosphorylates INCENP to recruit Plk1 to kinetochores 

# Regulation of cyclin-Cdk activity 
## Robust switches in Cyclin-Cdk1 activity can be achieved via changes in phosphorylation state 
- Inactivate via phosphorylation of ATP binding site 
	- E.g. Wee1 and Cyclin B-Cdk1
- Activate with phosphatase 
	- E.g. Cdc25 and Cyclin B-Cdk1 
- A robust switch in cyclin-Cdk activity is regulated by negative feedback and positive feedback loops ![[Pasted image 20230407233810.png]]
	- Wee 1 – negative feeback 
	- Cdc25 – positive feedback 

### Kinase
- mik1 is stabilised by unreplicated DNA -> repress cyclin CDK activity 
- Myt1 and Wee1 prevent mitosis 
- Animal cells have ultrasensitive response to inhibition by Cdk1 – bistable state
	- *Xenopus* Wee1 have phosphorylation sites in N terminus and a cluster nearer to the kinase domain
		- N-terminal sites not well conserved – does not inhibit Wee1  
			- Higher affinity
		- Central sites are well conserved – inhibits Wee1
			- Lower affinity -> will only be phosphorylated when Cdk reaches a certain threshold -> ultrasensitivity. 
	- Thus ultrasensitivity is built into the protein by ordered phosphorylation of sites ![[Pasted image 20230407234503.png]]
- Does N-terminus of WEE1 inactivate kinase domain? Unclear. 

### Phosphastase 
- In a phosphorylation system, kinase has to be turned on AND phosphatase turned off, or vice versa, or there will be a futile cycle 
- Phosphatases only have a few dozen catalytic subunits that have broad substrate specificity (cf kinases where there are hundreds, each being very specific)
- But phosphatases are incorporated into a complex. Accessory proteins regulate substrate specificity by recognising different SLiMs ![[Pasted image 20230407234923.png|450]]
- Phosphatases are regulated by Ensa and Gwl ![[Pasted image 20230407235306.png|375]]
	- Gwl and Ensa inhibit PP2A-B55δ
	- Cdk activates Gwl, Gwl phosphorylates Ensa, Ensa binds and inhibits PP2A-B55δ. It does not touch other B55 subunits. 
	- Phosphorylated ENSA is itself a substrate for B55δ with SLiM Motifs recognised by B55. It binds with high affinity but is a poor substrate as it hydrolyses slowly, effectively acting as an inhibitor 
- The result is that Cdk1 and PP2A-B55 activities are out of phase ![[Pasted image 20230407235204.png]]

## Proteolysis achieves irreversible regulation of cyclin-Cdk activity 
- Proteolysis is more irreversible than proteolysis. 
- Key proteins must be degraded for mitosis to progress
	- Anaphase entry is inhibited by securin 
		- Securin inhibits separase that cuts the cohesin complex that holds sister chromatids together ![[Pasted image 20230408000905.png|375]]
	- Mitotic exit is inhibited by Cyclin B-Cdk1 
- APC/C destroys both of these  ![[Pasted image 20230408000346.png]]
	- APC/Cs destroys cyclin B1 when all chromosomes are attached to the spindle. This inactivates Cdk1 and resets the cell cycle. Exit from mitosis is also coupled to relicensing of origins of replication 
	- APC/C is inactivated before cells begin S phase to allow mitotic cyclins to reaccumulate 

### Ubiquitinylation 
- Chains of Ub on Lys tends to be recognised by 26S proteasome 
- Within proteasome are three different protease activities, caps of proteasome recognise ubiquitin chains 
![[Pasted image 20230407235420.png|500]]
- Ubiquitin can form different chain conformations, which are recognised by different receptors ![[Pasted image 20230407235555.png]]
	- 26S proteasome cap has receptors that prefer K48-linked chains 
	- K63-pUB used in signalling in inflammation response 

#### Ubiquitin ligases 
- Ubiquitin ligases are modular 
- RING E3 ligases are modular ![[Pasted image 20230407235926.png|500]]
	- Scaffolding subunit – cullin 
	- Catalytic subunit – RING. Catalyses transfer of ubiquitin from E2 to substrate 
	- Substrate recognition subunit – F-Box, SOCS Box, DOC1 
		- Fbox can have WD40 domain (Fbw) or leucine rich domain (Fbl) or other domains (Fbx)
		- Skp2, involved in cell cycle, is Fbl 
	- Different cullins tend to have different substrate recognition subunits for different functions 
	- Nedd8 is important for activity. It is removed by COP9/signalosome 
		- Nedd8 changes conformation of SCF protein to bring E2 closer to substrate, facilitating transfer of ubiquitin to the target ![[Pasted image 20230408000123.png]]

### SCFs 
- Skp1 + Cullin + F-box protein 

### APC/C 
- Anaphase promoting complex/cyclosome 
- Anaphase must be tightly regulated as it is a point of no return – once sister chromatids are separated, they cannot be re-attached. If separation fails, aneuploidy occurs 
- APC/C can recognise different substrates at different times via SLiMs 
	- Destruction box 
	- KEN box 
	- ABBA motif
- Small variations in SLiM sequence and combinations of sequence can alter affinity of interaction. SLiMs can also be post-translationally modified to change their recognition by APC/C. This enables competition between substrates and regulators.
- APC recognises substrates with WD40 co-activator proteins, that also contain C box and KILR motif important for binding to APC. 7 beta propellers; between blades 1 and 7 + APC10 is where Destruction boxes bind, and between blades 2 and 3 is where ABBA motifs bind. On top is where KEN box binds.  ^963170 ![[Pasted image 20230408002539.png]]![[Pasted image 20230408001650.png]]
	- Cdh1
	- Cdc20 
- Coactivator also causes conformational changes in APC 
	- In absence of Cdh1 or Cdc20, APC11 is too far away from substrate binding site, so you cannot get ubiquitin transferred to substrate 
	- When coactivator binds, N-terminus of it pushes APC11 closer to where substrate will bind 
	- Thus, coactivator also performs a similar function to Nedd8 
	- #experimental_evidence Chang et al (2014)
- APC is auto-inhibited – blocks binding site for C-box in Cdc20. 
	- Without coactivator, APC blocks where N-terminus binds. APC has to be moved out of the way for Cdc20 to bind 
	- To get it out of the way, need to phosphorylate APC (kinase cooperation!)
		- CyclinB-Cdk1 and Polo kinase 1 are involved in phosphorylating APC. They work together by Cdc phosphorylating first on APC3 subunit. This creates a binding site for its own Cks subunit. This causes Cdc to bind more tightly so that it can recognise other sites with lower affinity, such as 1 between APC1 and APC8. When this is phosphorylated, polo kinase 1 can phosphorylate next to it. Together, they displace the autoinhibitory part of APC/C. 
	- Tight regulation of APC/C activation is crucial to avoid overly early activation of APC/C 
- For Cdc20 to bind to APC/C, Cdc20 has to be dephosphorylated while APC/C has to be phosphorylated 
	- This is achieved by the different preferences of PP2A-B56 which prefers p-T to p-S
	- Cdc20 is phosphorylated on the N-terminus to block binding to APC/C (on threonine), while APC1 disordered autoinhibitory loop is phosphorylated by CDK (on serines)
	- Cdc20 is preferred as a substrate. So PP2A-B56 dephosphorylates Cdc20 and leaves APC/C alone 

### Structure 
APC/C is a RING E3 ligase 
- APC2 has a cullen domain 
- APC11 is a RING domain 
- APC10 has a Doc domain 
- Coactivator binds near APC10. Between coactivator and APC10 forms binding site for substrates 

# Principles of the cell cycle 
## Negative feedback loops
- Stabilise regulatory systems, maintain steady state 
- E.g. Presence of unoccupied kinetochores activates a negative feedback loop that decreases the number of unoccupied kinetochores 
	- Unoccupied kinetochores activate spindle assembly checkpoint. Checkpoints arrests mitotic progression to give cell more time to get kinetochores occupied 
- E.g. cyclin B-CDK1 and APC/C<sup>Cdc20</sup>
	- Activation of cyclin B-cdk1 drives G2->M transition, but also activates APC/C<sup>Cdc20</sup>, which tags cyclin B for degradation 
- Requires for oscillations, as in cyclin B-CDK1 and APC/C-Cdc20 

## Positive feedback loops 
- Amplify signals 
- Sensitivity amplifier – small change in input -> large change in output 
- Act as bistable, hysteretic or irreversible switches 
- E.g. As the cell cycle progresses into M phase, Cdk1 activates its own activator Cdc25 and turns off its inactivator Wee1; in interphase, Cdc25 turns off and Wee1 turns back on 
	- This bistability converts a continuous increase in input (e.g. concentration of cyclin B1) into a discontinuous change in output (e.g. activity of Cdk1) ![[Pasted image 20230530220854.png|500]]
- Hysteresis contributes to irreversibility of G2 to M transition 
	- System resists switching states until controller variable crosses threshold 
- Cdk1/Cdc25/Wee1 positive feedback loop reinforces by Cdk1/APC/C<sup>Cdh1</sup> feedback loop 
- However, bistability is not an inherent consequence of positive feedback 

## Linked positive and negative feedback loops 
- Bistable trigger could promote oscillations 
	- E.g. positive feedback adds time delay into process of Cdk1 activation or destabilise steady state 

## Reciprocal regulation 
- Phosphorylation state of Cdk1 substrates is controlled by balance between Cdk1 activity and an opposing phosphatase 
	- For some Cdk1 substrates (e.g. APC3/Cdc27), the phosphatase is PP2A-B55δ 
	- For other substrates (e.g. XErp1), PP2A-B'56 is the phosphatase 
- Cdk1 activates Greatwall, which phosphorylates Ensa, which then inhibits PP2A-B55δ 
- Thus, Cdk1 activation increases rate of substrate phosphorylation and decreases rate of dephosphorylation  = reciprocal regulation 
- This converts Michaelian regulation into an ultrasensitive response ! 
- System is more sensitive to Cdk1 activity. 
- Inclusion of reciprocal regulation in positive feedback loops can make it easier to generate bistability 