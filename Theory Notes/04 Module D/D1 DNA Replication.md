# Questions
- Describe the roles of Cyclin Dependent Kinases (CDK) during eukaryotic DNA replication.
- ==Describe in molecular detail how DNA replication licensing and initiation are completely separated within the cell cycle.==
- Describe the regulation and structural changes of the Mcm2-7 replicative helicase complex throughout the cell cycle.
- How do cells prevent DNA re-replication?(by separating licensing and initiation lmao)

# Licensing in G1 phase– how DNA is only replicated once
## Why is DNA replication control important 
### Re-replication is bad 
- Can lead to gene amplification (Re-Replication Induced Gene Amplification)  genome instability, oncogenic effects, etc (Green et al 2010)
  ![[Pasted image 20230120090501.png|150]]
- Leads to centromere duplication, preventing correct segregation during mitosis and chromosome breaks 
- Causes fork collisions → "genome shearing", genome instability 

## Early experiments on licensing 
- Early hypotheses 
	- #experimental_evidence Blow & Laskey (1988) – In-vitro replication system from *X. laevis*. Template DNA added to *Xenopus* egg extract leads to its replication. First proposed a model for a "licensing system": A licensing factor binds to DNA to allow replication to occur. Once licensing occur, licensing factor is inhibited to prevent further re-licensing. During S-phase, there is activation of licensed DNA. Once replication is complete, licensing factor and origins become de-activated 
	- #experimental_evidence Rao & Johnson (1970) – Findings influenced hypothesis created by Blow & Laskey (1988); fused G1 with S phase cells, resulting in G1 nuclei becoming competent to replicate → S phase cells contain an activator. However when G2 nuclei and S phase were fused, G2 nuclei did not become competent and did not replicate. G1 cells are licensed, while G2 cells (after replication) have inhibition of licensing factor. S phase has the activator.   ^25970e
- Identification of licensing factor
	- #experimental_evidence Bell & Stillman (1992) – Looked for proteins that bind at the origin via footprinting. They passed yeast extract over the origin of replication and isolating a protein in the extract that resulted in footprinting, which was ORC. 
	- #experimental_evidence Diffley (1992) – However, ORC was found to not be the licensing factor alone. ORC is constitutively bound to origin DNA throughout the cell cycle, yet licensing must be inhibited in G2 phase. Did footprinting *in vivo* in yeast cells, while Bell & Stillman (1992) did this *in vitro*. Synchronised yeast cells in the same cell cycle phase, and found a larger footprint only in G1 cells, suggesting that there is a much larger complex that is cell-cycle regulated, which was called the pre-replicative complex (pre-RC).  ^3eb6cc

## Licensing  = loading and activation of DNA helicase in pre-replication complex 
- Each monomer in DNA Helicase exists in different states (E=Exchange, T=ATP bound, T*=ATP hydrolysis, D=ADP), and this 4 states occur in sequence each subunit, resulting in rotational movement along DNA (Thomsen & Berger, 2009) 
- Loading of two head-to-head hexameric helicase (Mcm helicase in eukaryotes) is the source of the larger footprint found by [[D1 DNA Replication#^3eb6cc|Diffley (1992)]]. 
- Features of MCM2-7 loading – highly conserved
	- #experimental_evidence Remus et al (2009) – in vitro preRC formation from purified components mixed with yeast origin DNA (ARS) showed that the loading reaction results in double hexamers of Mcm2-7 encircling the dsDNA with NO unwinding. However, the MCM double hexamers are able to passively slide along the dsDNA – if MCM double hexamers are loaded on circular DNA, they never fall off ("topological trap"), and this can be visualised on a gel 
	  ![[Pasted image 20230120092337.png|225]]
	- **ORC, CDC6, CDT1** are sufficient to load Mcm2-7 as two head-on-head hexamers onto DNA to form the **pre-replicative complex** (**preRC**). ORC and CDC6 AAA+ ATPases can drive many rounds of MCM loading (even at a single origin)
	- Loading reaction results in double hexamers of Mcm2-7 encircling dsDNA
	- During licensing action (when MCM double hexamers are loaded), they are inactive (i.e. do not unwind DNA), but can passively slide on dsDNA 
	  ![[Pasted image 20230120092423.png|300]]
	  - MCM double hexamers can be iteratively loaded 

## Regulation of licensing 
### CDK-dependent
- Eukaryotic cell cycle is driven by changes in subunits and activity of CDK kinase 
- S-CDKs and M-CDKs are an inhibitor of licensing reaction, which leads to MCM loading only during G1 phase 
- Every preRC component can inhibited by CDKs 
- PreRC inactivation mechanisms are interconvertible – as all these processes are required for licensing reaction, it doesn't matter *how* each component is inhibited, what matters is that they are all inhibited 
- Multiple mechanisms, e.g. 
	- Cdk phosphorylates Cdc6 resulting in Cdc6 degradation by SCF complex 
	- Cdk phosphorylates ORC to prevent MCM loading 
	- Cdk phosphorylates Mcm4 directly to exclude it from the nucleus 
	- Cdk phosphorylates Cdt1 which is then degraded by SCF complex SCF<sup>Skp2</sup>

### CDK-independent 
- In higher eukaryotes 
- e.g. Geminin inhibits Cdt1, preventing it from recruiting Mcm2-7 to the DNA. Geminin is inhibited by APC/C, which is itself inactivated by Cdk, so geminin is only active when Cdk is present.
- e.g. Cdt1 bound by PCNA, leading to degradation by SCF complex CUL4-DDB1<sup>CDT2</sup>

### Multiple pathways of inhibition are required 
- Ensures Pre-RC formation is strictly regulated throughout the cell cycle 
	- E.g. Cdc6 is inhibited at different points of cell cycle by different mechanisms
		- S-phase – Degraded by SCF<sup>CDC4</sup>
		- G2 – sequestered by Clb2
		- M-G1 – Transcriptional regulation by Swi5 which is excluded from nucleus by CDK. Transcription can only happen when Cdk is gone, which only allows a pulse of Cdc6 expression in M-G1. 
- Ensures licensing is 100% effective. A single re-replication event can be lethal, and each cell has many origins that need to be regulated (in eukaryotes)

# DNA replication initiation in eukaryotes vs prokaryotes 

| Cat                   | Prokaryotes                                                                                                                | Eukaryotes                                                                                                                                                                   |
| --------------------- | -------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Number of origins     | Single origin                                                                                                              | Multiple origins (on each linear chromosome)                                                                                                                                 |
| tREP                  | tREP* is proportional to fork rate (but there is an upper limit on fork rate as well due to rate of unwinding by helicase) | tREP is inversely proportional to interorigin distance, i.e. more origins -> faster replication                                                                              |
| Genome size           | Constraints to genome size                                                                                                 | No limit to genome size                                                                                                                                                      |
| Imaging               | Cairns (1963)                                                                                                              | Huberman & Riggs (1968), Blumenthal et al (1973)                                                                                                                             |
| Initiation regulation | Major regulatory step is loading of DnaA (analogous to ORC), which loads DnaB (helicase) which is active IMMEDIATELY       | Major regulatory step is loading of preRC complex. Helicase loading (Mcm) does not lead to immediate activation as has to wait for cell cycle signals to ensure coordination |

`*`tREP = rate of replication 

## Problems with multiple origins 
- Replication initiation across whole genome must be coordinated 
- Under-replication prevents replication bubble from expanding. This prevents segregation 
- Over-replication may lead to re-replication, leading to more than 2 copies of genome going into mitosis 

![[Pasted image 20230120090218.png|550]]

# Initiation of replication in S phase 
## Mcm2-7 helicase is inactive in pre-RC 
- Pre-replicative complex = licensing reaction 
- Mcm2-7 unwinds DNA by encircling the leading strand only and moving 3' to 5', i.e. it is a 3-5' ssDNA helicase 
	- #experimental_evidence Fu and Walter 2011 – Covalently linked two strands of DNA together which prevents replication at the linked point by preventing the two strands from separating (point 0), and incorporated at exact positions on the DNA biotinylated nucleotides. Streptavidin bound to the biotin is able to block Mcm2-7 from passing that position on the DNA, which blocks further replication past that position, resulting in shorter DNA that can be visualised on a gel. By incorporating biotinylated nucleotides on the leading strand, lagging strand, or both, the study showed that replication was only blocked when the leading strand or both strands have biotinylated nucleotides incorporated, suggesting that the Mcm2-7 is loaded on the leading strand. 
![[Pasted image 20230124231609.png|525]]
![[Pasted image 20230124231621.png|525]] ^103bbb
- Mcm2-7 helicase is inactive in pre-RC 
	- #experimental_evidence When Mcm2-7 is added to a DNA duplex consisting of a circular DNA and an annealed radiolabeled oligonucleotide, no separation is seen. 
	  ![[Pasted image 20230124233322.png|200]]
	  #experimental_evidence Remus et al (2009) 

## Activation of Mcm2-7 helicase in replisome 
- To activate Mcm2-7, the leading strand has to be passed through Mcm2-7 in a **strand passage event**, which is enabled by the fact that the hexamers can separate and each hexamer is a "cracked ring", with a gap in the hexamer ring called the 2-5 gate 
- Each Mcm2-7 helicase recruits Cdc45 and GINS to form the CMG complex, resulting in an active helicase 
	- #experimental_evidence When CMG complex was reconstituted, separation between circular DNA and radiolabeled oligo observed on gel 
	- #structural_evidence Cryo-EM shows that Cdc45 and GINS bind Mcm2-7 edge and close the 2-5 gate in Mcm2-7 (Costa et al 2011) 
- The two heads of the double hexamer separate to unwind DNA in both directions of the replication bubble 

## Regulation of replication initiation
- S-CDK and DDK are required to activate CMG complex 
- S-CDK = CDK + cyclin 
	- S-CDK phosphorylates the proteins Sld3 and Sld2 that allows for binding to Dpb11 to form a ternary complex that recruits components to form CMG complex as well as Pol-ε
		- Sld3 binds MCMs and Cdc45
		- Sld2 binds GINS
		- Dpb11 binds pol-ε
  ![[Pasted image 20230124235123.png|500]]
- DDK = Cdc7 + Dbf4 
	- DDK activates Mcm2-7 helicase phosphorylates N-terminus of 5 out of 6 of subunits of Mcm2-7. Probably important for separating two heads and resulting in structural changes (not certain how) that activates Mcm2-7
	- #experimental_evidence Mutation in Mcm5 in budding yeast called Mcm5-bob1 (P83L) can bypass requirement for both Cdc7 and Dbf4 

![[Pasted image 20230124235236.png|475]]

## Inhibition of unfired origins by DNA replication 
- At unfired regions, MCM2-7 remains as inactive double hexamers. 
- #experimental_evidence Douglas et al (2016) – active MCM2-7 push inactive double hexamers. 
	- #comment Needs elaboration 

# Summary: How licensing and firing are separated. 
![[IMG_488F5422BE0C-1.jpeg]]
# Termination of replication 
## Removal of MCMs 
- Converging CMG helicase complexes pass each other and CMG now encircles new dsDNA, which it cannot unwind 
- MCM2-7 is recognised by an E3 ubiquitin ligase, CRL2<sup>LRR1</sup>, a SCF complex. It recognises MC2-7 when it finishes replicating, and ubiquitylates Mcm2-7 subunit, resulting in Cdc48 ATPase recognising and disassembles ubiquinated complex 
- Lagging strand template binds to CMG complex that protects it from being degraded by CLR2<sup>LRR1</sup>, but once CMG complex transitions to dsDNA, complex no longer protected by an extruded lagging strand, allowing it to be degraded 

![[Pasted image 20230124235831.png|450]]

# DNA replication and the cell cycle
## Mcm2-7 cycle 
![[Pasted image 20230124235907.png]]
1. G1 phase – licensing. ATP-dependent loading of Mcm2-7 double hexamer in an inactive state on unreplicated dsDNA 
2. S phase – helicase activation 
3. Late S phase/G2 phase – Termination of replication. Disassembly of complex allows components to be **recycled** for next G1 phase 

## Switch-like activation of CDK ensures replication occurs only once per cell cycle 
1. In G1 phase, Pre-RC assembly is allowed (i.e. [[D1 DNA Replication#Licensing = loading and activation of DNA helicase in pre-replication complex|licensing]] occurs), [[D1 DNA Replication#Activation of Mcm2-7 helicase in replisome|origin activation]] is inhibited (i.e. they are mutually exclusive)
2. S-phase switch 
3. Pre-RC assembly prohibited (i.e. [[D1 DNA Replication#Regulation of licensing|Regulation of licensing]])  origin activation is allowed 
Sharp switch ensures unidirectional process of replication initiation and that initiation only occurs once per cell cycle 

- #experimental_evidence Nurse and colleagues (1991) – #comment Need to fil this in. 
- Switch-like S-Cdk activation is due to multisite phosphorylation of Sic1 (a CDK inhibitor), which generates an ultrasensitive response 
	- [[NashEtAl_2001]]
	- Critical threshold for phosphorylation results in degradation 
	- Cdk further phosphorylates Sic1, so as soon as Cdk is released, it leads to destruction of its own inhibitor, resulting in positive feedback loop
- However, there is also a buffer zone where licensing is turned off well before origin activation occurs to prevent re-replication from occurring 
	- #experimental_evidence Ruesswig et al (2016) – G1 CDK inhibits licensing factors by phosphorylating them. #comment Need to elaborate on this. 
- 11 CDK sites in Sld2, but only 1 is required to bind to Dpb11 

![[Pasted image 20230125002016.png|500]]

## Evolution of DNA replication
- Some archaea have only one ori, while others have multiple origins of ori, however lack many of the  regulatory machinery that eukaryotes have 

# Other ways cells maintain genomic stability 
- Coordination of replication initiation with the cell cycle (i.e. all of the above)
- Replication machinery controls duplication fidelity, but mechanisms are unclear 
- Monitoring of DNA replication fidelity by repair pathways and DNA damage checkpoint kinases 

# Summary!
![[Pasted image 20230530225822.png]]