# Questions 
- Signalling pathways of *==small G proteins vs heterotrimeric G proteins==*
	- Compare and contrast the mechanisms of activation of small G proteins versus that of heterotrimeric G proteins. Briefly speculate on why these two different mechanisms might have evolved. [[A7 G proteins#Guanine nucleotide exchange factors (GEFs)|Small G protein activation]], [[A7 G proteins#Activation|Heterotrimeric G protein activation]]
	- Compare and contrast the termination of signalling by the small G proteins and the heterotrimeric G proteins. [[A7 G proteins#Termination – GTPase activator proteins (GAPs)|Small G protein termination]], [[A7 G proteins#Termination|Heterotrimeric G protein termination]]
- Heterotrimeric G protein mechanisms
	- How do heterotrimeric G proteins integrate transduced signals? 
	- Describe, with examples, the mechanisms by which heterotrimeric G proteins interact with and modulate their effector proteins. [[A7 G proteins#Effectors for Gα|Effectors for Gα]], [[A7 G proteins#Effectors for Gβ/γ|Effectors for Gβ/γ]]
- ==Structure and function relationships – what are the differences in structure between Ras and other small G proteins, and how does it influence their function?== 
	- Describe the unique features of the small G protein Ran compared to the canonical small G protein, Ras. How do these features of Ran allow the protein to function? [[A7 G proteins#Small G protein Structure and function]]
	- Describe the unique features of the Arf small G-proteins compared to the canonical small G-protein, Ras. Explain how the regulation of the molecular switch in Arf proteins is linked to their functions in vesicular trafficking.
	- Describe the features of Rab small G protein regulation that allow control of vesicle trafficking.
	- *==Post-translational modifications and their influence on function==* [[A7 G proteins#Post-translational modification of small G proteins|PTMs]]
		- How are G proteins anchored to membranes? How does the anchoring impact on the functions of these proteins? 
		- Discuss how G proteins are post-translationally modified. How do these modifications contribute to their functional interactions with other proteins?
- Studying G protein structure 
	- ==How has NMR spectroscopy advanced the understanding of G-protein coupled receptor signalling?==
- Structure-based drug design 
	- *==Based on your knowledge of how G proteins function, design strategies to interfere with G protein signalling==*

# Small G protein signalling pathways
## G protein function 
- G proteins act as ==molecular switches== by existing in two states of GDP-bound (off) and GTP-bound (on)
- In the 'on' state, it can activate downstream effectors 
- External stimuli cause exchange of GDP for GTP to activate the G protein 

## Components of signalling pathways 
- ==G protein activating proteins (GAPs)== catalyse the G proteins' slow intrinsic GTPase activity, accelerating the switch from GTP-bound to GDP-bound
- ==Guanine exchange factors (GEFs)== catalyse exchange of GDP for GTP
- ==Guanine nucleotide dissociation inhibitors (GDIs)== inhibit the exchange of GDP for GTP 

![[Pasted image 20230323135937.png|525]]

## Guanine nucleotide dissociation inhibitors (GDIs)
- Identified for Ras/Rho/Rab families 
- GDIs can ==extract== Ras/Rho/Rab from the membrane and **maintain** it in an inactive form in the cytoplasm by ==blocking GDP from being exchanged for GTP==
- An appropriate stimulus (e.g. ==GDI displacement factor / GDF ==) can induce dissociation of the complex with concomitant membrane association of the small G protein 

### Structure and function 

| Structure                 | Function                                                                                                                    |
| ------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| N-terminal domain         | Blocks nucleotide exchange by contacting switch I and II.                                                                   |
| C-terminal Ig-like domain | Contains hydrophobic cleft to bind to prenyl group, maintaining prenylated small G protein in soluble complex in cytoplasm. |
| Surface groove (RabGDIs)  | Hydrophobic cleft is too small to accommodate two GG groups, so the second GG group is thought to bind to a surface groove  |
| β-sandwich (RasGDI)    | Interacts with farnesyl group in KRAS                                                                                       |

- The RasGDI phosphodiesterase δ (PDEδ)  lacks the N-terminal regulatory arm that contacts switch regions, and only recognises the farnesyl group and a few residues of the hypervariable region which may explain its lack of specificity – it can act on other prenylated proteins that are not G proteins

### GDIs and Rab membrane cycling 
![[IMG_1ECF561FC3F4-1.jpeg|525]]

1. GDI-Rab/GDP complex is delivered to donor membrane 
2. At donor membrane, Rab GDI is displaced by GDI displacement factors (GDFs)
3. Rab is activated by GEF that are resident on donor membrane
4. Once in GTP bound form, Rab interacts with effector proteins to trigger delivery of the vesicle and control specificity of tethering 
5. After vesicle fusion to target membrane, Rab GAPs that are resident on the target membrane mediate GTP hydrolysis to inactivate Rab 
	1. It is important that the Rabs are extracted from the target membrane, or it could trigger delivery of vesicles from the target membrane to the wrong membrane 
6. GDP bound form is recognised by GDIs, which extract it from the membrane and maintain it in an inactivate form in the cytoplasm 
	1. Ensures specificity of Rab delivery to correct donor membrane 

## Guanine nucleotide exchange factors (GEFs)
Accelerate the rate of GDP to GTP exchange, thus activating the small G proteins 

### General mechanism of action
- Open up nucleotide binding pocket and reduces affinity of G protein for GDP 
- When GEF binds, Mg2+ is displaced/blocked by elements of Switch II (Ala59) and/or the GEF, which reduces nucleotide binding 
- Push (Switch II) and pull (Switch I) mechanism
	- P-loop is disturbed, Lys16 reorientates towards Switch II, which is then pulled in towards the nucleotide binding site. This disrupts contacts to phosphates. 
	- At the same time, Switch I is displaced, preventing contacts between Switch I residues and the nucleotide, allowing GDP to dissociate
- Binding of GTP displaces GEF to reverse these effects. 
![[Pasted image 20230324105316.png|300]]

| Element                                 | Ras                       | Rho (Tiam1/Dbs)     | Rho (Dock9) | Arf      | Ran                       |
| --------------------------------------- | ------------------------- | ------------------- | ----------- | -------- | ------------------------- |
| Displacement of Mg2+                    | Ala59                     | Ala59               | V1951       | Sec7 E97 |                           |
| Displacement of P loop                  |                           |                     | DHR2        |          | Insertion of β hairpin | 
| Displacement of Switch I (Phe28, Thr35) | Helical hairpin insertion | DH domain           | DHR2 lobe B |          |                           |
| Allosteric regulation                   | Yes, by RasGTP            |                     |             |          |                           |
| Occlusion of ribose binding site        | No                        | Il33                |             |          |                           |
| Contact with Switch II                  |                           | DH domain, PH (Dbs) | DHR2        |          |                           |


### Ras GEFs e.g. SOS  
**Interactions**
- **Displacement of Switch I**: Helical hairpin inserts into Ras to displace Switch I – critical residues such as Phe28 and Thr35 cannot contact nucleotide and are instead stabilised by interactions with SOS 
- Extensive Switch II interactions
- **Occupation of nucleotide binding site**: Glu942, Leu938
- **Mg2+ binding site perturbation**: Ala59 
- **Interaction with Glu62**: Gly60 and Lys16. This prevents Glu62 from interacting with the nucleotide. 

**Effect**
- These changes reduce affinity of Ras for nucleotide.
- The ribose binding site is left accessible, allowing for binding of incoming GTP by ribose, causing changes in switches to displace SOS in reverse reaction. 

**Allosteric regulation of SOS by RasGTP results in a positive feedback loop**
- The interface between REM domain and GEF domain provide a second binding site for RasGTP, when RasGTP binds there, it increases GEF activity of SOS -> Ras can potentiate its own activation. 

![[Pasted image 20230324134539.png|425]]

### Rho GEFs
#### Tiam1 is a GEF for the Rho family protein, Rac1 
- **Occlusion of ribose binding site**: Ile33
- **Occlusion of Mg2+ site**: Ala59
- **Contacts with Switch I and II**: DH domain of Tiam1 makes extensive contact with Switch I and II, they shift upon interaction with Tiam1 so Thr35 cannot contact Mg2+
- PH domain of Tiam1 does not contact G protein but stabilises the position of the DH domain 

#### Dbs is a GEF for the Rho Cdc42
- Unlike Tiam1, PH domain also directly contacts switch II to assist in exchange 

#### DOCK9 is a GEF for Cdc42 
- **Contacts with Switch I and II**: DHR2 domain interacts with Cdc42 mainly via switch I, but this is augmented with Switch II interactions. DHR2 has 3 lobes (A, B, C), and lobes B & C interact with Cdc42 
- **Displacement of Switch I**: Phe28 is displaced, bound back into hydrophobic pocket in lobe B, disrupting contacts to guanine base 
- **Occlusion of Mg2+ binding site**: Insertion of V1951 from Dock9 into binding site to occlude Mg2+ binding site
- **Displacement of P loop**: Binding of DHR2 domain causes movement of Cys18 in P loop to disrupt contacts to phosphates.

![[Pasted image 20230324113431.png|275]]

### Arf GEFs e.g. Gea2
- **Extensive contacts between Gea2 and switches** 
- **Occlusion of Mg2+ binding site**: Sec7 domain inserts a glutamic acid residue (E97) into the Arf nucleotide binding site, obscuring the Mg2+ binding site and perturbing the β phosphate binding site
- GEF activity is reversible as γ phosphate of GTP displaces E97 
- Activation of Arf requires the action of a GEF AND membrane interaction
	- Membrane sequesters N-terminal HASP to release interswitch region -> shift in nucleotide binding site to make γ phosphate binding site accessible
	- Then, GEF can promote GDP release so GTP can bind. 
- Still push and pull mechanism! 

### Ran GEFs e.g. RCC1 
- RCC1 is predominantly β sheet (β propeller!), unlike other GEFs 
- **No contacts with switch I, some with switch II** 
- **Shift in P loop and displacement of autoinhibitory C-terminal helix**: β propeller structure inserts a β hairpin close to P loop of Ran, but doesn't directly interfere with nucleotide binding site. Rather, it induces a small shift in the P loop (1.3 A) which is followed by movement of Asp125, which stabilises guanine base. These changes clash with C terminal helix of Ran, causing it to be released from surface of G protein. 

## Signalling to effectors 
- Small G proteins can interact with a large number of effector proteins 
	- E.g. Ras interacts with at least 9 effectors (or families of effectors), with more being discovered, allowing for control of multiple signalling pathways 

### Common principles 
- Formation of intermolecular β sheet, involving Switch I (so switch I has to be in active conformation)
- Disruption of autoinhibition 
- Nanoclustering to promote dimerisation of effector 

| Feature                                         | Ras and Raf                                                                                | Cdc42 and WASP                                                      |
| ----------------------------------------------- | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- |
| Formation of intermolecular β sheet          | Yes                                                                                        | Yes                                                                 |
| Disruption of autoinhibition                    | Disruption of interaction between Raf's N-terminal autoinhibitory domain and kinase domain | Disrupt interaction between VCA domain and G protein binding domain |
| Dimerisation of effector increases its activity | Yes                                                                                        | Yes                                                                 |
| Nanoclustering of G protein                     | Yes                                                                                        | Yes                                                                 | 

### Ras and Raf interaction 
- **Formation of intermolecular β sheet** between Ras and Raf. Binding interface is mainly hydrophilic. 
	- Switch I of Ras is the major contact with Raf, so only GTP loaded Ras can engage with effector as switch I has to be in active conformation
- Binding of RasGTP results in **disruption of the interaction between Raf's N-terminal autoinhibitory domain and its kinase domain.** This releases occlusion of Raf catalytic site, thus activating the kinase 
- **MRas activates Raf via a different mechanism** – it activates a phosphatase complex composed of PP1 and SHOC2, and when active can dephosphorylate Raf and contribute to its full activation => multiple Ras family proteins may be needed to fully activate Raf
- **Nanoclustering** of Ras is important to signalling – spatial concentration of Ras increases the chance of Raf dimerisation, which increases its signalling activity 

#### Activation cycle of c-Raf 
![[Pasted image 20230324140054.png]]

### Rho family control of cytoskeleton
[[C3 Cytoskeleton and Organelle Movement]] – roles of Rho, Rac, and Cdc42. 

### Cdc42 and WASP 
- On binding, forms **intermolecular β-sheets**
- WASP is **autoinhibitory** via interaction between VCA domain and G protein binding domain (GBD). **Activated Cdc42 can bind to GBD** which frees VCA domain which can recruit monomeric actin and Arp2/3 to polymerise monomeric actin, resulting in formation of actin filament 
- **Dimerisation** of WASP makes it a more potent activator of Arp2/3
- **Nanoclustering** of Cdc42 promotes dimerisation of WASP (similar to Ras/Raf interaction)

## Termination – GTPase activator proteins (GAPs)
- GTP hydrolysis is the timing mechanism used to switch off molecular switch 
- G proteins have intrinsic GTP hydrolysis, but it's very slow 
- Many diseases are associated with loss of function of GAPs e.g. NF1 (RasGAP) in neurofibromoatosis, RhoGAP loss in X-linked intellectual disability 
- Study of G protein/GAP complex structures has to make use of a non-hydrolysable GTP molecule (e.g. GMppNP, GDP-AIF3)
	- GDP-AIF3 has the advantage of being a transition state analogue 

### Mechanism of action 
#### Intrinsic mechanism
- Gln acts as a base in active site to position water molecular in binding site. 
- Oxygen of water mediates a nucleophilic attack (Sn2) on γ phosphate. 
- Gln also contacts one of γ phosphate oxygen to stabilise transition state of reaction. 
- Mutation of Gln decreases hydrolysis rate by 100fold and locks GTPase in ON state, and often found as a cancer-associated mutant 
![[Pasted image 20230324140734.png|275]]

#### GAP catalysis mechanism 
**Arg finger**
- Positive charge neutralises the buildup of negative charge on the β and γ phosphate oxygens
- At the same time, it stabilises the position of the catalytic Gln61 
- Positioning of Arg is stabilised by a secondary basic residue (e.g. Arg, Lys)
- Typically the GAPs will contact the switch regions as well. 

![[Pasted image 20230324140817.png|225]]

| Mechanism    | Ras/p120         | RhoA/RhoGAP      | Arf1/ArfGAP1 | Arf6/Asap3 | Rab33/GIP1         | RanGAP                                                                      |
| ------------ | ---------------- | ---------------- | ------------ | ---------- | ------------------ | --------------------------------------------------------------------------- |
| Arg finger   | Yes, with 2° Arg | Yes, with 2° Lys | No           | Yes        | Yes, "dual finger" | No; Ran Tyr39 takes the role of Arg finger. RanGAP stabilises Tyr39, Gln69. |
| Co-activator | No               | No               | Coatomer     | No         | No                 | RanBP1 relieves autoinhibition by Ran C-terminus                            |

### Complex of Ras/p120RasGAP 
- Arg finger mechanism. Secondary Arg stabilises Arg finger. 

### Complex of RhoA/RhoGAP 
- RhoGAP also inserts an Arg finger into active site of RhoA which is stabilises by a Lys 

### Complex of Arf1/ArfGAP1 – unique mechanism 
- No catalytic Arg finger 
- ArfGAP1 stabilises switch I
- However, there is requirement for coatomer (COPI) for efficient GTP hydrolysis in Arf1 
	- This gives proofreading ability for Arf1 protein by ensuring GTP hydrolysis only occurs in context of making tarnsport vesicles 
- In ArfGap1, the GAP binding site and effector binding site do not overlap, in contrast to Ras 
- Later structure of Arf1-coatomer complex could not model in ArfGAP1 as it clashed with coatomer 
- So still unclear how Arf1 is activated – more structural information needed

### Complex of Arf6 with ASAP3GAP 
- GAP domain in ASAP3 is in completely different orientation from ArfGAP1. It contacts switches and does insert Arg finger into Arf6 active site 

### Complex of Rab GAP (GIP1) with Rab33 
- RabGAP has Arg finger from GAP 
- **Dual finger mechanism**: RabGAP also contributes Q378 which acts as the catalytic Gln rather than the Rab's own Gln61, which is displaced
- Complex of Rab GAP from hepatitis C (TBC1D20) and human Rab protein Rab1A has the same "dual finger" mechanism 

![[Pasted image 20230324140924.png|400]]

### Ran GAPs 
**Nuclear import/export**
- Ran regulates nuclear import/export 
- Unlike other G proteins, Ran GTPase cycle is unique as it is **compartmentalised**. GTP hydrolysis only occurs in cytoplasm, while GDP/GTP exchange occurs in nucleus 
- For nuclear import, importin complexes with RanGTP and complex encounters RanGAP, which releases importin, that then binds to import cargo to take it into the nucleus
- In nucleus, importin encounters high levels of RanGTP, preferentially binding to it and releasing import cargo. Then importin-RanGTP is exported out into cytoplasm 
![[Pasted image 20230324140953.png|375]]

**RanBP1 is a co-activator with RanGAP**
- RanBP1 acts as a co-activator with RanGAP
- **Interaction**: C-terminal helix of Ran wraps around RanBP1 to form a secondary interface; N-terminus of RanBP1 also acts similarly and wraps around Ran. This interaction leaves both switch I and II available to interact with RanGAP
- **Effect**: RanGAP:RanGMPPNP:RanBP1 complex suggest that RanBP1 and RanGAP do not interact. RanBP1 interacts with C-terminus of Ran to relieve autoinhibition. 

**RanGAP catalyses Ran GTP hydrolysis**
- RanGAP does not use Arg finger. Instead, Tyr39 from Ran forms hydrogen bonds with γ phosphate and Gln69. Ran GAP just stabilises and positions both Tyr39 and Gln69 ==> Tyr39 from Ran itself does the same role as Arg finger in other GAPs. 
- As a consequence, maximal rate of GAP stimulated GTPase reaction is very similar for Ran, unlike other G proteins. 

![[Pasted image 20230324141311.png|250]]

## Receptors 
### Ras receptor e.g. PDGF  
1. Activation of PDGF results in dimerisation and autophosphorylation 
2. Grb2 binds to phosphorylated tyrosines via SH domain
3. Grb2 recruits SOS, a Ras GEF 
4. SOS catalyses GDP/GTP exchange in Ras 
5. Activated RasGTP recruits and activates Raf 
6. Raf initiates a MAP kinase cascade (Raf --> MEK -> Erk)
7. Erk phosphorylates Elk-1 transcription factor
8. Elk-1 activates a plethora of genes involved in cell growth/differentiation 
9. p120 GAP also is recruited by PDGFR via its own SH2 domain, and can terminate cascade by catalysing hydrolysis in RasGTP. 

# Small G protein structure and function 
- All G proteins contain a G domain that binds to guanine nucleotides 

## Functions
| G protein | Function                        |
| --------- | ------------------------------- |
| Ras       | Cell growth and differentiation |
| Ran       | Nuclear transport               |
| Rho       | Cytoskeletal regulation         |
| Rab       | Vesicular transport             |
| Arf       | Vesicular transport             |

### Rab function 
See [[C2 PTMs and Protein trafficking]]
- Each Rab protein is localised to the cytosolic face of distinct intracellular membranes
- Rabs can cycle between membranes (unlike SNAREs)

### Ran function 
See [[B2 RNA localisation#^1f6167|Regulation of nuclear export]]

## Overall structure 
### Ras 
- α, β protein with a 6-stranded β-sheet (five parallel, 1 anti-parallel) and five helices on both sides of the sheet. 
![[Pasted image 20230323140724.png|325]]
- Most of the G protein is unimportant to interacting with the nucleotide and with regulators, but they still have a function. 

## Important structural elements (Ras numbering)
Ras is considered to be the **minimal** and **canonical** small G protein, and other small G proteins have variations on this structure. 

| Element                 | Sequence     | Function                                                           |
| ----------------------- | ------------ | ------------------------------------------------------------------ |
| PM1 (G1) motif (P-loop) | 10GxxxxGKS/T | Interaction with phosphates                                        |
| PM2 (G2) motif          | T35          | Switch I, contacts Mg2+                                            |
| PM3 (G3) motif          | 57DxxGQ/H/T  | Gln residue catalyses GTP hydrolysis reaction; Gly is in Switch II |
| G1 motif                | F28/Y        | Hydrophobic interactions with nucleotide                           |
| G2 (G4) motif           | 116N/TKxD    | Forms binding pocket around 1 base                                 |
| G3 (G5) motif           | 145S/CAK/L/T | Helps to stabilise F28 in G1                                       |
| Mg2+                    |              | Ionic interactions with phosphate groups                           |

![[Pasted image 20230323141026.png|400]]

### Variations in other small G proteins 
| G protein | Variation                                                                                                                            |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| Ran       | extra C-terminal helix and C-terminal extension                                                                                      |
| Arf       | extra N-terminal helix which affects the rest of the Arf molecule – switch I has an extra β strand, and switch II is more helical |
| Rab       | Extra C-terminal helix                                                                                                               |
| Rho       | Insert loop                                                                                                                          | 

## Nucleotide binding site 
Location of loops and regions surrounding binding site. 
![[Pasted image 20230323141458.png|350]] 

Location of critical residues surrounding the active site
![[Pasted image 20230324134342.png|350]]
## Switch region and switch mechanism 
### Ras 
- Flexible loops within Ras that change in conformation between GDP bound and GTP bound states 
![[Pasted image 20230323142827.png|350]]
- Switching between GTP and GDP bound states involves a "loaded spring mechanism" whereby Thr35 in Switch I and Gly60 in Switch II interacts with the oxygen atoms on GTP γ-phosphate, and release of γ-phosphate on hydrolysis allows the system to relax. 
  ![[Pasted image 20230323143058.png|400]]

### Ran switch mechanism 
- The C-terminal tail binds back onto the relatively basic surface of the protein 
- Apart from Switch I and II, the C-terminal helix acts as a ==third switch region== 
- During GDP/GTP exchange, re-orientation of Switch I and II results in the release of the C-terminal helix from the surface of Ran due to steric clashes 
	- Important to nuclear transport 

### Arf N-terminal switch mechanism 
- In Arl8 subfamily of Arf proteins (e.g. Arf1, Arf6), the canonical γ-phosphate binding site is displaced in the GDP form 
	- In this inactive conformation, the interswitch positions a conserved aspartate (D) in the DxxGQ motif upstream of Switch II to mimic the charges of the γ-phosphate of GTP, thus preventing the binding of GTP (Pasqualato et al 2002)
- For GTP to bind, the N-terminal helix has to be displaced. Displacement of the N-terminal helix causes conformational changes in switch I and II to restore them to an active conformation for GTP to bind. 
- The interswitch region communicates structural changes from the N-terminal helix to Switch I and II 
	- The interswitch region undergoes a "two-residue register shift", pulling switch I and II up (Pasqualato et al 2002)
	- The interswitch also extrudes the N-terminal helix by occluding its binding pocket (Pasqualato et al 2002)
- "In vivo, the displacement of the N-terminal hasp is mediated by the interaction of its hydrophobic side with membranes, thus coupling the activation of Arf by GTP to its recruitment to membranes" (Pasqualato et al 2002)
	- In principle, displacement could be achieved via protein-protein interaction as well 
- Because of this unique switch mechanism that requires both nucleotide exchange AND interswitch toggling, "guanine nucleotide exchange for the Arf proteins involves two complementary components, a classical GEF function plus an additional hasp-unfastening factor, each poorly active on its own" (Pasqualato et al 2002)

![[Pasted image 20230323144010.png|400]]

Change in interswitch region between GTP and GDP-bound states. 
![[Pasted image 20230323144042.png|300]]

See more about Arf function: [[C2 PTMs and Protein trafficking#COP I mediates retrograde transport from trans to cis Golgi cisternae]]

## Allosteric lobe 
- The allosteric lobe is isoform specific for Ras 
- Maintains correct Ras-membrane interaction 
- Isoform-specific sequences in the allosteric lobe can also affect GTP hydrolysis and how Ras interacts with effector proteins, and this is due to allosteric effects on dynamics and conformational states 
	- Specifically, H bonding networks link the effector and allosteric lobes, e.g. Switch I and nucleotide-sensing residues in helix 5 are linked by water and hydrogen bonding between polar residues, including loop 8 and helix 4, which are highly variable between Ras isoforms [[JohnsonEtAl_2017a]]
- Some mutations, e.g. H-RasQ61L, H-RasG12R/A59T are speculated to alter the structure of Ras-membrane interaction or disrupt the effector-to-allosteric lobe communication pathway which affects how Ras is oriented in the membrane. These mutations may lock Ras in a signalling-conducive conformation 

# Post-translational modification of small G proteins
## Lipid modifications and membrane association 
- C-terminal lipid modifications anchor the small G proteins to plasma membrane or endogenous membranes to localise it for signalling 
- Small G proteins contain a hypervariable C-terminal region (HVRs) that is constitutively prenylated 
- Many HVRs contain the conserved sequence "CAAX" (where C is cysteine, A is any aliphatic amino acid, and X is any amino acid) which is the primary site of prenylation (i.e. addition of prenyl group, a type of lipid)
- Further "secondary" prenylations can occur at other sites along the hypervariable region, usually cysteines 
	- In Ras, the primary farnesylation only results in weak membrane binding, and this secondary membrane anchoring signal is needed to enhance membrane binding. The secondary signal also differs between Ras isoforms and defines isoform-specific trafficking and microlocalisation patterns for each Ras isoform 

### Lipid modifications for each small G protein family 
| G protein             | Lipid modification                                                                                                                              |
| --------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| HRAS, NRAS, KRAS (4A) | Farnesylation at C-terminal cysteine*, Palmitoylation at penultimate cysteines (different patterns of palmitoylation for each isoform)          |
| KRAS (4B)             | Farnesylation at C-terminal cysteine*, positively charged Lys6 region. Phosphorylation of Lys by protein kinase C disrupts membrane interaction |
| Rho                   | Geranyl geranylation                                                                                                                            |
| Rab                   | Double geranyl geranylation (they have 2 C-terminal Cys residues)                                                                               |
| Arf                   | Myristoylated at N-terminus after removal of N-terminal Met                                                                                     |
| Ran                   | No post-translational modification as it functions in nuclear import/export, so it has to be soluble in cytoplasm and nucleus                   | 

`*`KRAS and NRAS can be alternatively geranyl-geranylated if farnesylation is inhibited. 

### Process of C-terminal prenylation 
1. Prenylation of cysteine of CAAX by a pair of prenyltransferases that attach a polyisoprene lipid via a stable thioester linkage to Cys 
2. Proteolysing of AAX residues ("axing") by Rce1 endoprotease  
3. Exposed C-terminal carboxylic acid group is methylated by a methyltransferase, Icmt1 
4. Localisation to membrane 
5. Further lipid modifications on other cysteines 

![[Pasted image 20230323145039.png|425]]

**Different steps in the prenylation process occur in different cellular compartments!**
![[Pasted image 20230323150042.png|375]]

### Regulation of membrane association 
- **Farnesyl-electrostatics switch in KRas 4B**. PKC can phosphorylate KRAS4B S181 within the polybasic region, to dissociate it from the plasma membrane and instead promote association with intracellular membranes, including the outer membrane of the mitochondria, where phospho-KRAS can interact with Bcl-XL
	- #experimental_evidence KRAS with a phosphomimetic residue (Glutamic acid) at position 181 induced apoptosis via Bcl-XL 
- **Palmitoylation/Depalmitoylation cycle**. palmitoylation is a reversible post-translational modification due to the labile thioester linkage between the palmitoyl group and the cysteine, thus a palmitoylation/depalmitoylation cycle can regulate the trafficking of NRAS and HRAS between the plasma membrane and the Golgi apparatus. This in turn regulates the sets of proteins NRAS and HRAS can interact with over space and time
	- When the Ras proteins are palmitoylated, they are affinity trapped in a membrane compartment and transported to the plasma membrane on vesicles. After some time, depalmitoylation can occur to release the Ras proteins back into the cytosol to be trafficked to the Golgi. 
	- #experimental_evidence Goodwin et al (2005) used FRAP to show that NRAS and HRAS to translocate between the PM and the Golgi in a palmitoylation-dependent manner. When palmitoylation was inhibited with 2-bromo-palmitate, it caused the fraction of NRAS associated with the ER and Golgi to increase.
	- While palmitoylation is thought to be constitutive as no regulator for palmitoyl acyltransferases (e.g. DHHC9-GPC16) have been found, depalmitoylation may be regulated by another post-translational modification – peptidylprolyl isomerisation. In HRAS, the cis/trans isomerization of the Gly-Pro peptidyl-prolyl bond regulates the rate at which HRAS is depalmitoylated. 
		- Isomerisation acts as a “molecular timer” for the half-life of each HRAS isoform, and together with palmitoylation acts as a temporal regulator of Ras protein interactions by regulating the time it spends in different cellular compartments.
		- #experimental_evidence Application of FK506, an inhibitor for the prolyl isomerase FKBP12, resulted in inhibited HRAS depalmitoylation. 

### Small G proteins are localised to distinct membrane microdomains 
- Membranes are organised into ordered domains (with higher amounts of cholesterol and saturated lipids) and disordered domains (less cholesterol, more unsaturated lipids)
- G proteins tend to ==localise to distinct domains== and these clusters are important to signalling
	- Exception is KRAS (4A) and (4B), which tend to reside in disordered domains but in two spatially distinct regions corresponding to GTP-bound and GDP-bound states
		- Acidic lipids may cluster around proteins with polybasic membrane-binding domains, such that KRAS becomes the recruiting centre of a signalling nanocluster. For example, KRas can recruit the acidic phosphatidylserine, which in turn recruits Raf-1 as it selectively binds phosphatidylserine. 
	- Ras can move in and out of different regions in the membrane depending on what PTMs it has and what nucleotide state it is in 
		- #experimental_evidence In-vitro microscopy studies show that H-RasGDP resides in lipid rafts, but when activated by GTP binding, it exits these domains to signal from non-ordered domains. 
		- In contrast, N-RasGTP localises to lipid rafts, while NRas GDP localises to the phase boundary between ordered and disordered regions 
- G proteins may have a preference for membranes with certain lipid compositions 
	- #experimental_evidence E.g. Gregory et al (2017) propose that KRAS (4B) has a binding preference for Nanodiscs containing PIP2 (using *single frequency fluorescence anisotropy decay experiment*) due to the formation of long-lived salt bridges with PIP2 head groups but not monovalent DMPS (*molecular dynamics*). PIP2 also interacts with Helix-4 in the catalytic domain of KRAS4B, to orient the protein such that it can associate with signalling partners. 
- Proteins present in particular membrane domains can help to direct Ras-membrane association 
	- E.g. Galectin-1, Galectin-3 help stabilise H-RasGTP and K-RasGTP respectively when each isoform is localised in the correct lipid microdomain 
- Ras proteins themselves may be needed for lipid raft formation 
	- E.g. HRas can induce negative changes in membrane curvature to promote lipid recruitment and formation of ordered regions 

#### Structural elements important for membrane association 

| Element              | Function                                                               |
| -------------------- | ---------------------------------------------------------------------- |
| Hypervariable region | Prenylation, stabilise membrane orientation                            |
| Lys6 (KRAS 4B only)  | Membrane interaction, recruitment of acidic lipids                     |
| Helix 4              | Stabilise membrane orientation                                         | 
| Helix-4 (KRAS4B)     | PIP2-specific interaction                                              |
| L3                   | Nucleotide sensing residues                                            |
| Allosteric lobe      | Transmits structural change due to nucleotide state change to membrane |

### Significance of membrane association 
- Association of G proteins with membrane constrains their mobility to just two dimensions, facilitating interactions with GAPs and GEFs that also interact with the membrane and allowing for rapid signal transmission 
	- #experimental_evidence Ras GEFs (e.g. SOS) also localise to membrane via interaction with membrane proteins (via SH2 domains) or with membrane phospholipids (via PH domains)
- Localisation of G proteins to the membrane ==affects which regulatory and effector partners they interact with==, resulting in different signalling outputs even if the effector domain sequences are very similar (e.g. HRAS, NRAS, KRAS4B)
	- #experimental_evidence HRas GDP and NRasGTP localise to lipid rafts, which positions them to interact primarily with cholesterol and sphingomyelin. In contrast, H-RasGTP and N-RasGDP residues should interact with unsaturated phospholipids, including PtdCho, PtdSer, and PtdIns. 
	- [[A7 G proteins#Small G proteins are localised to distinct membrane microdomains]]
- Proteins present in the microdomain can orient the small G protein for a specific effector interaction
	- #experimental_evidence  Hydrophobic pocket of galectin may interact with farnesyl group to stabilise it in an appropriate membrane orientation for effector interaction 
- Membrane orientation of small G proteins allows for signalling control – G proteins are typically oriented in the membrane such that specific regions are exposed, modifying the specificity of effector interactions
	- E.g. H-RasGTP is oriented in a way that exposes switch regions and effector lobe residues crucial for interaction with effectors, e.g. Raf, PI3K, GAPs. When inactivated, H-RasGDP undergoes a conformational change that buries these interacting regions. 

## Ubiquitination 
- Ubiquitination can also regulate the trafficking of HRAS to and from endosomes, with ubiquitinated HRAS being restricted to endosomes, which apparently reduces MAPK signalling. 
- "KRAS ubiquitination increases GTP loadingin concert with G12V mutation, amplifying its interaction with its effectors Raf and PI3K" (Parker & Mattos 2015)

# Heterotrimeric G proteins signalling pathways 
## Signalling cycle  
1. Gα exchanges GDP for GTP, becomes activated 
2. Gα separates from Gβ/γ subunit, and each interact with downstream effectors 
3. Gα hydrolyses GTP to GDP, becomes inactivated
4. Reassociation of Gα with Gβ/γ. 
5. Heterotrimeric G protein binds to GPCR. 
![[Pasted image 20230325105250.png|275]]

## Activation 
### GPCRs
- ==GPCRs take the role of GEFs== to promote GDP-->GTP exchange. β γ subunits act cooperatively to promote nucleotide exchange 
- e.g. **β<sub>2</sub> adrenergic receptor with G<sub>s</sub>

#### Interaction between GPCR and heterotrimeric G protein
- **Receptor and Gs**. Primary contact between receptor and Gs is N-terminal α helix and also carboxy-terminal α helix (α5). These are quite distant from nucleotide binding site, so conformational changes in helices have to be propagated through α subunit to nucleotide binding site 
- **βγ**. There are no direct contacts between β γ subunit and the receptor, even though they are required for efficient coupling of α subunit to receptor 

#### Mechanism of action 
#comment verify this 
1. Ligand binds to GPCR via TM domains and extracellular loops to activate it. This results in changes in the external domain of the receptor that is transmitted to the cytosolic domain 
2. Conformational changes in cytosolic domain of receptor 
	1. 14Å outward movement of cytoplasmic end of TM6 – "toggle switch" residue in TM6 (commonly a conserved proline) induces a kink in the helix so that it can move 
	2. α helical extension at cytoplasmic end of TM5
	3. ICL2 goes from disordered to α helical
3. Hydrophobic cleft in cytosolic domain is exposed by outward movement of TM5 and 6, forming G protein binding site 
4. G<sub>s</sub> binds to receptor via N-terminal α helical domain, resulting in its displacement from the G domain. 
5. Conformational changes in G<sub>s</sub> to promote nucleotide exchange – Movement of α5-β6 loop outwards, and this loop normally interacts with guanine ring of nucleotide. There are also smaller shifts in α1 and β1 which are transmitted to the α1β1 loop, which is actually the P loop
6. Exchange of GDP for GTP 
7. Retraction of N-terminal α helical domain, resulting in dissociation of α subunit from βγ and receptor. 

### GBA motif proteins
- ==GBA motif proteins== are cytosolic non-receptor activators of the heterotrimerics
	- Bind to monomeric GDP bound α subunits
		- After Gα undergoes hydrolysis, it is briefly in monomeric GDP bound form in cytosol. At this point, it can become a target for GBA motif proteins, allowing Gα to undergo more rounds of activation. 
		- Also some evidence that GBA motif proteins can dissociate β/γ subunit from heterotrimer. 
	- Binds in cleft between switch II and α3. This perturbs β1 strand to disrupt α1β1 loop (P loop), thus disrupting binding to nucleotide phosphate, inducing nucleotide release. But it does not perturb guanine binding site

### Competition between GPCRs and GBA proteins


## Effectors for Gα
- cGMP phosphodiesterases, adenylyl cyclases, PLA, PLC, PI3K, ion channels. This is very few compared to small G proteins, but these effectors all ==impact secondary messenger systems==, resulting in wide-ranging effects on signalling. 
- Common theme of ==release of autoinhibition== of effector 

| Feature                          | cGMP PDE                            | Adenylyl cyclase | PLC                                         |
| -------------------------------- | ----------------------------------- | ---------------- | ------------------------------------------- |
| Relief of autoinhibition         | Sequester C-terminal region of PDEγ | No               | Sequester helical domain, X/Y linker of PLC | 
| Weakened membrane interaction    | Yes, due to flipping of Gt          | Yes, for Gαs     |                                             |
| Direct activation of active site | Yes, via helical domain of Gt       | Yes, for Gαs     | Yes, reorientation of PLC C-terminal        |

### Interaction of G<sub>αt</sub>/transducin with cGMP phosphodiesterase 
- cGMP PDE catalyses formation of 5' GMP from cGMP
- **Signal transduction**. Light activates GPCR rhodopsin -> transducin binds -> nucleotide exchange -> α subunit binds to γ subunit of cGMP PDE --> releases catalytic subunit to form GMP
![[Pasted image 20230325142250.png|425]]
- **Relief of autoinhibition**. PDEγ contacts cleft formed between Switch II and α3 on transducin, same cleft that GBA protein binds to. Switch I isn't involved. This interaction with Switch II sequesters 5 C-terminal residues on PDEγ that have an autoinhibitory effect 
	- #experimental_evidence Proteolysis and deletion mutagenesis of PDEγ C-terminal residues
- **Activation of PDE by helical domain of transducin.** Helical domain of transducin contacts catalytic subunits of PDE. This contributes to PDE activation. 
- **2 molecules of transducin have to bind for full activation of PDE**. Transducin molecule undergoes an alternating translational motion across surface of PDE, such that when one transducin molecule is moving, the other remains fixed. Transducin pivots on helical domain/PDE interface. This supports the model of **"alternating site catalysis"** of PDE developed from kinetic observations, where the two active sites alternate between which is doing the catalysis, and this is determined by which site has the translating transducin. 
- **Transducin membrane interaction is weakened when bound to PDE.** When transducin binds to PDE, it is oriented such that it is completely flipped with respect to membrane. This results in very weak association between membrane and Gα subunit, and it can be dissociated relatively easily from the effector.
-  #structural_evidence Gao et al (2020) cryo-EM studies revealed dynamics of PDE activation by transducin.  ^c7e6b4

![[Pasted image 20230325114058.png|350]]

### Interaction of G<sub>αs</sub> and G<sub>αi</sub> with adenylyl cyclases 
- ACs catalyse conversion of ATP to cAMP, a secondary messenger that activates PKA 

#### Structure of AC
- Integral membrane protein, anchored by two TMDs (M1 and M2) 
- Two cytosolic domains, C1 and C2, which are catalytic. C1/C2 dimer forms a hydrophobic cleft with two pockets where ATP can bind. 
	- Both AC and just isolated C1/C2 dimer can be activated/inhibited by Gαs and Gαi
- Helical domain that connects TM domain to C1/C2 is an extension of TM helix 6 and 12 – possible communication between TM domain and catalytic domain? Could TM domain have a receptor function? 
![[Pasted image 20230325144039.png|275]]

#### Activation by Gαs
- **Gαs stabilises the AC transition state**. Gαs binds to the C2 domain (α helix 2 and 3) via Switch II, resulting in α1α2 loop to apply pressure to C1, reorienting ATP binding site. Reorientation of R1029 in C2 to stabilise transition state of cyclase reaction. 
- When Gαs is activating AC, it also **detaches from the membrane transiently**. 

#### Inhibition 
- **Gαi inhibits adenylyl cyclase by binding into cleft on C1** which is analogous to Gαs binding site on C2. MD simulations indicate that Gαi makes catalytic site less favourable for ATP binding. 
- Myristoyl group on Gαi also may play a role #question what role? 

### Interaction of G<sub>αq</sub> with PLC 
- Interacts with PIP2 to form DAG and IP3 

#### Structure
- 2 helices that are autoinhibitory by binding near the catalytic core 
- C-terminal domain contains elongated coiled-coil region with basic residues that interact with membrane 
- X/Y linker that blocks active site of PLC 

#### Interaction 
- **G<sub>αq</sub> contacts** **autoinhibitory helices** and sequesters helices away from the active site of PLC. 
- **C-terminal domain of PLC** makes contacts with both Gαq (at N-terminus of Gαq via a hydrophobic patch) and the catalytic core of PLC to orientate the catalytic site towards lipid bilayer. This increases efficacy of PLC. 
	- This is also helped by **palmitoylation** on Gαq N-terminus 
- **Displacement of X/Y linker from PLC active site** by steric and and electrostatic repulsion mediated by close proximity to plasma membrane. This only occurs upon binding to Gαq. 

![[Pasted image 20230325120633.png|475]]

![[Pasted image 20230325145058.png|475]]

## Effectors for Gβ/γ 
- α subunit occupies effector binding site on β/γ subunit, so one dissociated, β/γ can activate their effectors 

### Ion channels 
**GIRK2 K+ channel and Gβγ**
- 4 βγ subunits bind to cytoplasmic domains of GIRK2 channels at interface between each channel monomer 
- Binding of βγ subunits causes clockwise rotation of cytoplasmic domains relative to membrane spanning domain of channel. 
- βγ binding only opens permeation pathway slightly ("pre-open" state), but additional twisting in same direction widens inner gate further allowing K+ ions to move through ("open") state. 
- This twisting is stochastic, and may govern "bursting" behaviour by the channel 
![[Pasted image 20230325145230.png|350]]

## Termination 
### Gα
- **Tethered helical domain in Gαs inserts an Arg finger** into active site of G domain of Gα to catalyse GTP hydrolysis in similar way to GAPs 
	- E.g. In Gαt, R174 resides in loop between G domain and helical domain, with position stabilised by helical domain
- As a result of cis acting Arg finger, Gα hydrolyse GTP 100x faster than small G proteins; however the intrinsic hydrolysis rate is still slower than *in vivo*, so there are actually additional GAPs – RGSs, and some effector proteins. 
![[Pasted image 20230325145439.png|325]]

### Regulators of G-protein signalling (RGS) proteins 
- All contain a conserved catalytic domain 
- Have a higher affinity for GTP transition state than ground state 

#### Catalytic mechanism 
- Holds switch regions in correct orientation so that Arg finger can act in nucleotide binding site 
- RGS may also interact and stabilise catalytic moieties directly e.g. water, catalytic Gln 

#### Other functions and cross-talk 
- Mammalian RGS proteins have more domains than just RGS – highly modular. 
	- E.g. DH and PH – Rho GEF domains. 
	- E.g. GoLoCo motifs – can activate βγ subunits while acting as GDIs for α subunits 
	- E.g. GGL domains – resemble γ subunit, so can complex with β subunits. 
- Large degree of cross-talk between different pathways... 
	- Dual role for RGS proteins in GPCR signalling 
- RGS3 can also act as GAP for KRas (Li et al 2021)! 
	- "RGS3 enhanced GTP hydrolysis in mutant KRAS-inclusive manner, affecting both WT and several oncogenic mutants (including G12C, G12D, G12V, G13C, and G13D). This effect was dependent on a key asparagine residue in the GAP domain of RGS3. KRAS mutations impede the catalytic arginine (or R-finger) of canonical RAS-GAPs (such as NF1 or RASA1) from enhancing an otherwise slow GTP hydrolysis rate"
	- The Asn residue "was predicted to orient away from the P-loop and therefore less likely to be impeded by G12 substitutions"

### Some effector proteins 
- Effector proteins may also act as GAPs to achieve signal acuity, since the Gα is quickly deactivated after engaging its effector. This results in a sharp signal, with high responsiveness and low noise. 

**PLCβ and Gαq**
- PLCβ has a loop that is inserted between its EF3 and 4 domains
- Loop points into active site of Gαq, and loop **Asn260 interacts with Gln209** to stabilise it in the transition state. 
- At same time, **Asn260 interacts with Glu212 on Switch I**, so it stabilises orientation of Switch I for hydrolysis 

**cGMP PDE and Gαt**
- PDEγ binding to Gαt leaves Switch I and II available for stabilisation by RGS9. RGS9 then interacts with all three switch regions to stabilise them and also Arg finger.
- Coupling because RGS9 can only bind to Gα it is already bound to PDEγ, as PDEγ forces switch II in correct orientation to engage RGS9 
- PDE also stabilises Arg204 in Gα, allowing it to make hydrogen bonds to G199 and stabilise the catalytic Gln200 

# Structure and function of heterotrimeric G proteins 
- α subunit is guanine nucleotide binding protein 
- β and γ subunits form a non-separable unit but as they can interact with many α subunits, many possible combinations can form to result in many heterotrimeric G proteins 

## Gα
- Families of G proteins: G<sub>s</sub>, G<sub>i</sub>, G<sub>q</sub>, G<sub>12</sub>
- **G domain**. Have the same G domain fold as Ras, but with four insertions – 1 large **helical domain** and three small insertions 
![[Pasted image 20230325105447.png|300]]
- **Lipid modifications**. Many have Gly2 which is myristoylated after removal of N-terminal methionine. Many also have Cys at N-terminus which can be palmitoylated 
- **Mg2+**. Gα only binds Mg2+ in GTP bound form, while small G proteins bind Mg2+ in both GDP and GTP forms 
	- βγ subunit binds Gα GDP to inhibit nucleotide release, thus taking on the role of Mg2+ and also one function of GDI proteins of Ras, Rho, and Rab families 
- **3 switch regions**. Similar to small G proteins, switch I and II are present, along with a third switch loop that points into the nucleotide binding site. A network of hydrogen bonds connects the switches to the nucleotide, so they can reorientate depending on what nucleotide is bound. 
- **Arg-Gln hasp.** Connects the three switch regions to lock the α subunit in GTP-bound conformation. The presence of this hasp results in Gα subunits having a preference for GTP binding, compared to small G proteins which bind to GTP and GDP with equal affinity. 
![[Pasted image 20230325150421.png|225]]
- **N-terminal α helix.** Extends away from Gα when bound to GDP. Is sandwiched between βγ subunit and GPCR, so exchange of GDP for GTP results in dissociation of the α subunit from βγ and from receptor. 
![[Pasted image 20230325112706.png|275]]

## Gβ/γ
- Forms an obligate dimer. 
- Gβ has β propeller structure
- γ has extended α-helical structure with extensive contact with β subunit
- γ subunits also has **CAAX box**, like small G proteins. So can be farnesylated or geranyl-geranylated on cysteine of CAAX. AAX residues are cleaved off similarly. 
- **Interactions with Gα**. Gβγ makes extensive contact with the switch regions of Gα, and also stabilises the interaction of Gα N-terminal helix with GPCR 

## Lipid modifications 
**E.g. transducin** 
- α subunit myristoylated and/or palmitoylated at N-terminus
- γ subunit is farnesylated at C-terminus
- β subunit not modified, but as it forms obligate dimer with γ subunit, it is also membrane associated. 

# Cross-talk between GPCRs and small G proteins. 

# Studying G protein structure 
## NMR 
- G proteins undergo conformational changes upon binding to ligands at both their active site and at allosteric sites that might reveal other binding pockets
	- "Conformational selection is widely believed to underlie allosteric behavior (3, 4). All molecules exist in a thermal equilibrium in which they sample multiple conformations; some states may have relatively high free energies and therefore be sparsely populated. Ligands bind to a subset of conformations, which results in a population shift that establishes a new equilibrium. For example, an agonist shifts the conformational distribution such that more molecules are able to bind the partner G protein, whereas an inverse agonist depopulates such states." [[WeisKobilka_2018]]

# Structure-based drug design for Ras
## Methods of drug discovery
- Serendipitous discovery – identifying active ingredient from effective materials 
- Classical pharmacology – screening libraries of small compounds in cells, organisms to identify substances with desired therapeutic effects 
- Target-based (reverse pharmacology) – high throughput screening of large libraries of small compounds against specific biological targets, hypothesised to be crucial for the disease 
	- Hit identification -> medicinal chemistry for optimisation of hits to increase useful properties 
	- Look for clefts for drug binding 
		- This makes enzymes popular drug targets as there is an obvious binding site – the active site 
- Biologics – pharmaceutical products manufactured or extracted from a biological source, e.g. vaccines, recombinant insulin, antibodies, peptides.
- Fragment-based screening – screens much smaller ligands that match target well, but have lower affinity due to small contact size. But, after screening fragments, can link fragments together to form a higher affinity compound, or take one fragment and grow it chemically to exploit other contacts on the target
	- Need good understanding of structure 

## Ras mutations 
- Ras has isoform-specific bias in mutation, and each type of cancer has a bias towards different mutations in each isoform. It is unclear why this correlation exists. 
- Ras mutations lock Ras into active, GTP bound state that is not regulatable by GAP proteins. 

### Common Ras mutations leads to hyperactivity 
- G12V – RasGAP is in close proximity to G12, and replacement of Gly with any other amino acid would result in steric hindrance, preventing formation of transition state complex between RasGAP and G12V (though binding is still possible). This prevents catalysis. G12P is the only non-transforming mutation known. 
- G13A – Any side chains introduced at G13 would sterically clash with the Arg finger.  
- Q61 – Catalytic residue for hydrolysis. Amide group of Q61 forms hydrogen bond with carbonyl of Arg finger, while its sidechain carbonyl accepts H bond from nucleophilic water. Gln is the only amino acid that can serve this function. Asn wouldn't be long enough. 

## Druggable Ras targets
- see [[A7 G proteins#Fragment-based drug discovery for Ras|Fragment-based drug discovery for Ras]], [[A7 G proteins#Ras G12C tethers|Ras G12C tethers]]

## Direct targeting of Ras
- Ras is challenging to target directly 
	-  Nucleotide binding site is on protein surface and is accessible to small molecules 
		- However affinity of Ras for nucleotide is picomolar. Concentration of GTP approaches micromolar levels, so how likely can we find a small molecule that we can compete with such a high affinity ligand? Even a low nanomolar affinity drug (the benchmark) would not be sufficient 
	- Other hydrophobic clefts/pockets/grooves 
		- Only appear under certain contexts 

### Fragment-based drug discovery for Ras
- Fragment-based drug discovery – screen fragments, then grow the fragment or combined different fragments 
- #experimental_evidence Sun et al (2012) used FBDD and found a hydrophobic binding pocket that was not previously discovered; only was exposed on ligand binding. Also induced formation of a second pocket next to it, and this pocket is electronegative. So first fragment grew to exploit second pocket, which increased its affinity. These molecules block KRAS from interacting with the SOS GEF. 

### Covalent inhibitors 
#### Ras G12C tethers 
- G12C in KRAS introduces a cysteine
- Screened for "tethers" that reacted with Cys12 
- Binding also resulted in formation of new binding site not previously observed 
- FDA approved! 

#### Tri-complex inhibitor 
- Revolution Medicines is developing a Tri-complex inhibitor 
- Inhibitor is made up of a compound that specifically targets a specific Ras mutant, as well as a chaperone protein. The two are linked. 
- Covalent binding of compound to Ras mutant brings chaperone into close proximity, blocking interaction between Ras and GEFs or other effector proteins 

## Protacs
- Proteolysis-targeting chimeras. E3 ligase linked to a ligand for a target protein. 
- Ras Protac
	- #experimental_evidence Bond et al (2020) developed L2-C, a PROTAC that can degrade endogenous KRAS<sup>G12C</sup>, L2-C binds KRAS<sup>G12C</sup> via a small molecular warhead and recruits the E3 ligase VHL to induce degradation, which led to suppression of MAPK signalling in cell lines  
- Poor tumour access, so haven't been efficacious in disease models 
- Modular, any ligand can be turned into a PROTAC. 

## Targeting membrane interaction of Ras 
### Farnesyl transferase inhibitors
- Ras modified to lack C of CAAX box couldn't transform fibroblasts. 
- **CAAX analogues** – tetrapeptides that compete with Ras CAAX box for farnesyl transferases 
	- Found to reduce anchorage independent growth of Ras transformed cells and slowed growth of Ras-transformed cells in nude mice
	- But were rapidly degraded, and couldn't be taken up into cells efficiently 
- **Modified CAAX analogues** – replace aliphatic amino acids with benzodiazepine (BZA) or aminomethyl benzoic acid (AMBA) 
	- Effective inhibitors
	- More stable 
- **Small molecule FTase inhibitors** e.g. lonafarnib, tipifarnib 
	- But they don't seem to interfere with cell proliferation... which is what you need for cancer
	- However, inhibiting FTase just resulted in most Ras isoforms being geranylgeranylated instead as they are weak substrates for GGTases. 
		- HRas was an exception and could not be geranylgeranylation 
		- FTIs disrupt membrane localisation of HRas but not KRas bawsed on fluorescence microscopy of GFP-tagged Ras isoforms (Basso et al 2006)
		- Unfortunately, all the pre-clinical models used HRas. 
	- But Ho et al (2021) reported some efficiency of tipifarnib for HRas driven cancers e.g. head and neck squamous cell carcinoma. 
- **GGTase inhibitors** were too toxic as they have many targets in the cell, resulting in pleiotropic effects. 

> [!Warning] Ras isoforms are very different biochemically despite their similarity in sequences!

### PDEδ inhibitors
- RasGDI that chaperones Ras to membrane
- E.g. Deltarasin inhibits KRas-PDEδ interaction and suppress proliferation and MAP kinase signalling in KRAS-dependent pancreatic cancer cells (Zimmerman et al 2013)

### Preventing nanoclustering of Ras 
- Target dimer interface of Ras
- Monobodies are high affinity synthetic proteins based on a molecular scaffold (e.g. fibronectin type II domain) – alternative to antibodies 

### Reorienting Ras to use membrane to occlude effector binding site 
- Fang et al (2018) – Compound II engages shallow pocket on KRAS and associates with lipid bilayer, which stabilises KRAS in orientation where membrane occludes effector binding site -> reduces Raf binding to impair activation 

## Targeting downstream effectors of Ras 
- Many enzymes downstream of Ras are kinases, which have previously been known to be quite druggable (e.g. Gleevec)

### Ras-Raf pathway 
- There are three Raf isoforms, ARAF, BRAF, CRAF/RAF1
- **First generation BRAF inhibitors** e.g. Sorafenib
	- Off-target activity against VEGFR2, PDGFR, Flt-3, c-kit, FGFR-1 
	- But no efficacy against mutant BRAF because it acts by interacting with inactive form of Raf kinases and locking them in inactive form, so no activity against mutant BRAF V600E which is constitutively active 
	- Any efficiency observed in other cancers was due to antiangiogenic properties (since it inhibits VEGFR2)
- **Second generation V600E BRAF inhibitors** e.g. Vemurafenib (PLX4032) 
	- Blocks proliferation of BRAF lines in vitro and in vivo 
	- But **ineffective against Ras mutant cell lines** and do not block ERK activation in this context 
		- "Raf Paradox" – these inhibitors actually activated the RAF-MEK-ERK pathway. 
		- Raf actually exists as a dimer that can be homo or heterodimers between the three isoforms. When in a dimer, one Raf monomer inhibits the other by phosphorylating it. In the cell, BRAF can form a heterodimer with CRAF, and specific inhibition of BRAF resulted in activation of CRAF. This increased stimulation of the RAF-MEK-ERK pathway. 
		- As such, BRAF inhibitors should not be used in Ras cancers
			- Patient stratification / personalised medicine 
	- Also ineffective in non-RAS, RAF-specific cancers (e.g. melanoma) too due to development of **drug resistance**
- **First generation MEK1 inhibitors** had underwhelming early clinical trials due to compensatory and feedback mechanisms induced by MEK inhibitors 

### PI3 kinase pathway 
- Ras mutant tumours do not respond to single agent Pi3K inhibitors nor to single agent dual PI3K-mTor inhibitors 

### Ral pathway 
- Ral pathway largely ignored because mainly protein-protein interactions (rather than enzymatic reactions) which are hard to target – large contact surface and relatively flat, no binding pockets. 
- Peptides can be helpful in blocking such protein-protein interactions but difficult to develop peptides that are stable, good pharmacokinetics, and can bypass cell membrane 
- **Stapled peptides** – RALB-RLIP76 (effector) form a complex. 80% of buried surface area involves 1 alpha-helix of RLIP76. 
	- However, single helix peptide are often unstable, don't maintain helix structure 
	- This can be stabilised by chemically "stapling" specific residues in the peptide, stabilising turns on the helix to nucleate formation of the rest of the helix 
	- Hydrocarbon stapling using unnatural amino acids. Staples not only nucleate helix but also increase binding, help peptides get into cell, protect peptide from degradation
- **Cyclised peptides** 

### Combination therapies 
- MAPK/PI3K combination therapies are in clinical trials, but narrow therapeutic window due to cytotoxicity 

## Principles of drug resistance 
![[Pasted image 20230326173819.png|225]]

# Links to other topics 
- [[A8 Machinery of Translation]]
	- Ras, Ran GTPases are architecturally very similar to EF-Tu, but use a substrate-assisted mechanism for catalysis 
	- The ribosome acts as a GAP for EF-Tu. 
- [[C1 ER Targeting and Integration]]
	- SRP and SR are G proteins, but differ from other G proteins in that they are multistage GTPase switches with <u>three</u> stable states rather than two. 
- [[C2 PTMs and Protein trafficking]]
	- [[C2 PTMs and Protein trafficking#Sar1p drives assembly of the coat proteins|Sar1p]] drives assembly of coat proteins in COP II vesicles 
	- [[C2 PTMs and Protein trafficking#COP I mediates retrograde transport from trans to cis Golgi cisternae|Arf]] interacts with components of B and F subcomplexes in COP I coats to deliver COP I vesicles to target membranes during retrograde transport 
	- [[C2 PTMs and Protein trafficking#Tethering|Rab]] is involved in tethering vesicles together 
- Many [[C3 Cytoskeleton and Organelle Movement#G proteins involved in cytoskeleton regulation|G proteins]] are involved in cytoskeletal regulation – Rac, Cdc42, Rho
- Ras and cancer 
	- [[D3 Oncogenes and Tumour Suppressors]]
	- [[D14.1 Drug-based cancer therapies#Small molecule inhibitors]]
	- etc






