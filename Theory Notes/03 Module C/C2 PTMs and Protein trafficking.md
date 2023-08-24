
# Questions 
- Sorting in the endosomal pathway
	- How are sorting decisions made within the endocytic and endosomal pathways?
	- ==What mechanisms control the selectivity of protein targeting within the endocytic and secretory pathway?==
	- What new insights into protein sorting within the endocytic pathways have come from atomic-resolution **structures**?
- Sorting in the secretory pathway (=Golgi)
	- How are cargo proteins sorted within the secretory pathway?
	- ==How can protein targeting within the secretory compartment be achieved with high efficiency using weakly interacting molecular components?== (slightly different angle to the same question)
		- Multiple checkpoints... 
- [[C2 PTMs and Protein trafficking#Movement of proteins from cis to trans Golgi|Movement of proteins from cis to trans Golgi]]
	- ==To what extent can traffic through the secretory and endocytic pathways be described in terms of a stable compartment model or a continuous maturation model?== [[C2 PTMs and Protein trafficking#Continuous maturation model|Golgi maturation]], [[C2 PTMs and Protein trafficking#Endosome maturation|endosome]]
	- Why is it so difficult to come to a consensus on the mechanism(s) by which soluble proteins traffic through the Golgi compartment?
- Coated transport vesicles 
	- Discuss the role of coat **adaptor** proteins in the assembly and selectivity of coated transport vesicles. 
	- What insights into clathrin coated vesicle function have been provided by structural studies?
- Membrane fusion 
	- Most transport vesicles fuse constitutively with their target membrane. In contrast, synaptic vesicles will only fuse in response to a selective signal such as a neurotransmitter-activated increase in calcium concentration. What is the underlying molecular basis for these differences?
	- ==Interactions between SNARES, tethering proteins and their respective cognate partners are proposed to provide a 'quality control' mechanism to ensure fusion between correct membrane compartments. Discuss.==
- Error correction in protein folding and protein sorting 
	- Protein folding and protein sorting from the endoplasmic reticulum have a high error rate. Discuss. 
	- Error correction mechanisms are ubiquitous within the secretory and endocytic pathway. Discuss. 

# ER quality control systems 
## Protein folding in the ER has a high error rate
- In vivo, proteins often do not fold correctly unless there are helper proteins (e.g. chaperones) that help them through the folding pathway 
	- #experimental_evidence Temperature-sensitive folding mutants (e.g. vesicular stomatitis virus envelope glyco-protein and HA-tagged influenza virus proteins) remain in the ER at the non-permissive temperature, and are immunoprecipitated in association with chaperones (e.g. Bip, calnexin)
- However, even with chaperones, protein folding still has a high error rate due to the crowded environment of the ER; there is always a background level of misfolding. This is especially so for large or complex multi-subunit proteins. 
- As such, the ER needs QC systems to recognise misfolded proteins, retain them in the ER, and either correct the folding or degrade them 
- Protein misfolding can lead to accumulation of toxic aggregates

> [!image] Protein folding energy landscape (Balchin et al 2016)
> ![[Pasted image 20230514222154.png]]


## Ribosome effect on protein folding 
- Ribosome exit tunnel confines conformational states a nascent peptide can access while folding
- Ribosome may stabilising folding intermediates that are otherwise short-lived in solution 
- Ribosome may have a chaperoning effect with emerging peptides, protecting the nascent peptide from misfolding until the protein is fully synthesised 
- Ribosome acts as a platform for protein biogenesis factors that interact with nascent peptide for maturation and localisation 

## Disulphide bond formation 
- Disulphide bonds are formed in the ER due to the oxidation state of the cytosol 
	- ER is much more oxidised than cytosol. The cytosol contains glutathione which makes it more reduced. Different amounts of glutathione control the oxidation state of the cell. 
- ==Protein disulphide isomerase== catalyses the oxidation of sulfhydryl (–SH) groups on proteins to form disulphide bonds, and becomes reduced in the process. 
- ==ER oxidoreducin (ERO)== converted reduced PDI back to its oxidised form using FAD as the oxidising agent 
- ==Glutathione== does not act directly in protein folding, but rather works to rescue misfolded protein. 
	- Many proteins may contain multiple –SH groups, but the correct pair must be bridged for correct folding to occur. 
	- If the wrong pair of –SH groups is bridged by PDI, the incorrect bridge can be reduced back via action of reduced glutathione (GSH), which converts it to oxidised glutathione (GSSG)
	- #experimental_evidence [[RobinsonBulleid_2020]] – At a non-permissive temperature, temperature-sensitive ERO mutants accumulate PDI<sub>red</sub> due to slower regeneration of PDI<sub>ox</sub>. Howeer, if we also remove the GSH producing protein, there is slower unfolding of misfolded protein, which places less stress on PDI to re-fold the unfolded proteins. 

![[Pasted image 20230224221359.png|425]]

## Glycosylation QC system  
- Upon entry into the ER lumen via Sec61, oligosaccharyltransferases (OSTs) add a 14-membered N-linked core glycan at Asn next to a Ser/Thr (see [[C1 ER Targeting and Integration#N-linked glycosylation|N-linked glycosylation]])
- Subsequently, glucosidase I removes a terminal glucose residue, and glucosidase II removes a second and third terminal glucose residue 
- As protein is being made, the chaperone calnexin/calreticulin binds to the glycoprotein isoform with 1 terminal glucose
	- #structural_evidence Crystal structure of calreticulin shows that carbohydrate binding site is just big enough to fit the oligosaccharide with 1 terminal glucose. It also has a structural "arm" that can bind to other chaperones, creating a localised region that protects the folded protein from other misfolded proteins, hydrophobic proteins. 
	- #structural_evidence Calnexin is similar but has an additional membrane domain. 
- Once protein folded, glucosidase II removes last terminal glucose, allowing dissociation 
- However, another enzyme UDP-glucose:glycoprotein glucosyltransferase (UGGT) can add this last terminal glucose back, which causes it to bind to calnexin/calreticulin again for refolding 
	- It is uniquely selective for partially folded or misfolded proteins. Spots exposed patches of hydrophobic residues
		- #experimental_evidence (see reading list)
	- N-glycan binds to UGGT in part via GlcNAc residues at the glycan base. As GlcNAc is very close to the attached protein, it may only be accessible to UGGT if there is some local polypeptide flexibility, which is another indicator of unfoldedness
	- #structural_evidence Has thioredoxin-like domain. Has sensors that spots exposed patches of hydrophobic residues – Zhu et al (2014)

> [!image] Folding QC using N-linked 14-membered glycan
> Calreticulin/calnexin binds to glycoprotein with 1 terminal glucose, but UGGT can add the terminal glucose back for refolding
> ![[Pasted image 20230305170530.png]]


- #experimental_evidence Castanospermine is a drug that can inhibit glucosidase I and II. If you carry out a pulse chase experiment with radioactive amino acids then cold amino acids, and add at same time as inhibitor. Binding of calreticulin (to soluble proteins)/calnexin (to membrane proteins) inhibits binding, and secretion of proteins is inhibited. But if you do pulse chase first to allow the protein to bind to calreticulin, then add drug, the dissociation of protein from calreticulin is inhibited. So manipulation of sugars regulates assembly of newly synthesised glycoprotein with calreticulin/calnexin, but also regulates its dissociation

## ER-associated degradation (ERAD) of misfolded proteins 
- If the protein does not fold, then the oligosaccharide on the misfolded protein is further digested by α-1,2-mannosidase, then EDEM 1/3 (ER degradation enhancing mannosidase-like, and the resulting oligosaccharide is recognised by an ERAD lectin (e.g. OS-9)
![[Pasted image 20230305170836.png|450]]
- Misfolded protein is exported into the cytoplasm by a retrotranslocon for degradation by proteasome ![[Pasted image 20230305171012.png|475]]
	- Der1p is a 6 α helices TM protein, probably need oligomer of Der1p. Forms pore in ER membbrane. Cdc48 is a complex ATPase provides energy to drive pumping of protein out of ER lumen 
	- #experimental_evidence Experiments with the yeast CPY*, a mutant form of carboxypeptidase Y, cannot be folded. In a wild type cell, it is glycosylated in the ER and then degraded. KO experiments in yeast reveal which alleles of derlin proteins (DER1, DER2, DER3) are needed in the pathway 
	- #experimental_evidence HMG CoA reductase is inhibited by a downstream product, farnesyl pp. Fpp changes its conformation such that it is recognised by the ERAD pathway. So mutants can be screened  for loss in this activity. Many mutants turn out to be components of the ubiquitin-induced proteasomal degradation pathway. ![[Pasted image 20230305170937.png|475]]
- #question At what point is a protein shunted from the refolding pathway to ERAD? 

> [!image] Full calnexin/calreticulin cycle for refolding misfolded proteins
> ![[Pasted image 20230305170857.png]]

> [!image] Full ER protein folding quality control (Araki & Nagata, 2011)
> ![[Pasted image 20230514195537.png]]

## Unfolded protein response (UPR)
 - Misfolding proteins overwhelms protein folding pathways e.g. under oxidative stress 

### UPR1 (early)
- PERK is a sensor that senses abnormally high levels of misfolded proteins. Normally misfolded proteins associate with chaperones, e.g. BiP, but if there is a large amount of them, some start to interact with PERK. This drives local dimerisation of PERKs. Cytoplasmic tails have autocatalytic activity leading to cross phosphorylation. This activates downstream pathways, mainly involved in inhibiting 80S ribosome assembly and general inhibition of protein synthesis, e.g. by phosphorylating eIF2α ([[B5 Translation and translation regulation in eukaryotes]]). This prevents furthe influx of nascent proteins into ER. At the same time, eIF2α activates expression of ATF4 transcription factor, which recognises promoters of a set of ERSC response elements involved in rescuing the situation. 
	- #comment I suppose we expect that PERK should have a lower binding affinity for unfolded proteins than BiP? 

### UPR2
- Ire1p sensor forms dimer in presence of misfolded proteins, similar to PERK 
- Cytoplasmic tail has endonuclease activity acts on a specific mRNA which is normally not translated as it has a residual intron ([[B4 RNA splicing#Alternative splicing|alternative splicing]]). Endonuclease removes intron to create functional mRNA which generates a TF XBP1, to activate a series of target genes associated with ER stress element
- #structural_evidence Ire1p has similar structure to MHC even though they have different sequences (convergent evolution). It has a pocket that captures peptides

### UPR3 
- Involves ATF-6, tethered on membrane of ER. Normally it is associated with various chaperones. But if chaperones removed due to excess of misfolded proteins, ATF-6 moves through secretory pathway to Golgi. Protease chops it off and releases it, allowing it to go back to nucleus to activate ERSE-target genes 

### Integration of UPR 
- ATF4 controls expression of XBP1 
- It also upregulates ATF6 
- Once ATF4 is activated, it enhances sensitivity of misfolded protein response 
	- Positive feedback loop 

![[Pasted image 20230305171126.png|UPR system]]

## Protein misfolding and disease 
- CFTR ΔF508 results in misfolding (at 37°C) resulting in degradation; degradation requires ubiquitination and is prevented by proteasome inhibitors 
- Human α-antitrypsin (AAT) has a missing C-terminus, so cannot fold. Degradation is also inhibited by proteasome inhibitors
- The human cytomegalovirus avoids immune detection by targeting MHC proteins for degradation. The USII gene products binds to the MHC to prevent correct folding, thus leading to retrotranslocation and degradation in the cytosol. Proteasome inhibitors block degradation. 

# Transport between the ER and Golgi 
## COP II vesicles mediate transport between ER and Golgi 
### Structure 
- Outer coat proteins – Sec13p, Sec31p (show synthetic lethality)
- Inner coat proteins – Sec23p, Sec24p (show synthetic lethality) 
- Small GTP binding protein Sar1p 

![[Pasted image 20230305173252.png|475]]

### Sar1p drives assembly of the coat proteins 
- Sar1p activates assembly of the coat proteins 
- Sec12p acts as GEF, Sec23p acts as GAP for Sar1p 
	-  #structural_evidence Sar1p interacts with Sec23p which in turn interacts with Sec24p. Can interact with membranes to stabilise curvature as the assembly is curved
	- #structural_evidence Sec23p provides R722 (Arg finger) which points into active site, stabilising transition state for hydrolysis of GTP. 
	- #experimental_evidence VSV G protein is a marker for secretion that is membrane bound. If we take membranes from cells infected with VSV-G, and add back minimal components, minimally need activated Sar1p and Sec23/24p to recover VSV G proteins
- When GTP binds, there is a conformational change in Sar1p, resulting in change of relative orientation of an amphipathic α helix and β sheet, helix opens up and can embed in the membrane. This alters morphology of vesicles to become more tubular 
- The inner coat proteins drive assembly of the vesicle, with Sec23p/Sec24p acting as a GAP for Sar1p. However, the outer coat proteins Sec13p/31p stimulate the GAP activity of Sec23p/24p. 
	- #experimental_evidence Antonny et al (2001) – Following GTP hydrolysis, a Trp residue in Sar1p reduces fluorescence at 340 nm, which can be used as a proxy for Sar1p-induced GTPase activity. When Sec13/31p is added, Trp quenching is accelerated. 
	- #structural_evidence Sec13p/31p has a proline-rich domain with which it stimulates Sec23/24 GAP activity 
		- Interacts at interface between Sar1p and Sec31p
		- In the presence of Sec24p and Sar1p, R finger is pointing in but it's still a bit exposed, when Sec31p is added, it covers the region, creating another binding site, to increase efficiency of hydrolysis 
		- R722 etc are known to be important by forming networks with Asn and Trp to lay down Sec31p peptide on top of Arg finger
- Upon GTP hydrolysis, dissociation of the Sec24/23p from Sar1p occurs 
	- #experimental_evidence FRET studies of interaction between Sec24/23p and Sar1p show that dissociation is actually slower than GTP hydrolysis – FRET signal decays more slowly than GTP hydrolysis (as measured by reduction in Trp fluorescence)

### Inner coat proteins interact with cargo receptors for cargo selection 
- Cargo receptors bind to a cargo to deliver it to a transport vesicle
- Sec24p has a small number of localised patches that act as binding sites for receptor motifs (e.g. DxE, LxxLE, YxxNPF) in the cytoplasmic tails of cargo receptors (e.g. Erv29, Erv14), or within the cargo molecules themselves ![[Pasted image 20230601224808.png|500]]
- Although individual interactions between the motifs and Sec24p is weak, as there is a large surface area for binding, even low affinity interactions are captured. 

### Assembly of outer coat proteins Sec13p and Sec31p 
- #structural_evidence Fath et al  (2007) – Has β-propeller structure at N-terminal. There are 7 β blades in Sec13p, one of which is missing, the last blade is provided by Sec31p, allowing for interaction
	- Crystallisation made use of an "Ancestral coat element" fragment to show interaction between Sec13 and Sec31 
	- Interaction also involves α solenoids  ![[Pasted image 20230305195247.png|500]]
- Dimer formation between Sec31 and Sec13 allows for formation of a ==cuboctohedron coat== around the vesicle
	- Dimer is flexible – interface between Sec31 and 13 can bend 
- Vertices are assembled by Sec31p β-propeller interactions involving either face-to-face or face-to-side interactions 
	- Vertices are flexible
  ![[Pasted image 20230305195445.png|600]]   
### Sec16p recruits coat proteins for assembly at the ER exit sites 
- There are intermediate compartments between ER and Golgi – ER Golgi intermediate compartments (ERGIC) / Vesicular tubular clusters (VTCs) 
	- Protein markers 
- COP II vesicles are exported to ERGIC, which is generated from homotypic fusion of COP II vesicles, where sorting occurs
- Certain regions of ER have COP II forming preferentially – these are ER exit sites (ERES). 
- Sec16 is associated with ERES sites (Hughes et al 2009). Sec16p acts upstream to recruit Sec23/24/13/31 
	- #experimental_evidence Hughes et al (2009) – Confocal microscopy, showed overlap in localisation between these fusion proteins of these vesicle proteins and fluorescent proteins 
- Sec16 has multiple binding proteins, one binds to coat proteins, one to Sec13, one to Sec12 (GEF). This drives assembly of GTP with Sar1p, which is itself required for nucleation of Sec23/24p inner and outer coats. Unlike Sec31, Sec16 inhibits Sec31/13 stimulation of Sar1p 
	- #experimental_evidence Cranio-lenticulo-sutural dysplasia (CLSD) – cannot secrete collagen from fibroblasts. Mutations are in Sec23A (F382L, E599K). Effect is to reduce affinity of Sec23 for ERES sites by reducing its affinity for the pre-bud complex of Sec13/31. Sec16 starts to accumulate, so intermediate get stuck, as coat protein assembly is not complete, and transport vesicles do not bud off. 

## Transport of large cargos 
- Many COPII are only 70 nm, but we know there structures exported far bigger than this, e.g. pro-collagen (300 nm), chylomycrons (400 nm)
- COP II vesicles can form in a variety of different shapes by changing the way the Sec13/Sec31 dimers interact at the vertices. 
	- In spherical COP II, one end of dimer interacts face to face, and one is face to side
	- But in tubular COP II, both are face to side on both ends of dimer 
	- #experimental_evidence Zanetti et al (2013) – in vitro system 
- Transport of large cargos may also be mediated by a tunnel between ERES and ERGIC 
	- ERGIC membranes can be recruited to ERES to form tunnel 
- A number of proteins associate with ERES site that is important for assembly of collagen into tubular structures
	- E.g. Transport and Golgi organisation (TANGO) protein assembles with Sec16. It has multiple independent domains. Lumenal SH3 domain interacts with collagen. Cytosolic proline-rich domain recognises a site on Sec23p that overlaps with proline rich domain region of Sec31. In fact, competition between Sec31p and and TANGO1 can occur for binding to Sec23p. 
	- As such, it may be that TANGO acts as a capture for the collagen. It then captures Sec23, then lays them down in an organisation to form a tubular vesicle. 

## Alternative models of ER to Golgi transport 
- COP II may be involved in selecting and concentrating exported cargo from the ER rather than coating Golgi-bound carriers 
	-  #experimental_evidence Shomron et al (2021) used live cell and electron microscopy techniques to show that the COP II coat remains bound to the ER-ERES boundary during protein export, and manipulation of the cargo binding domain in COP II Sec24b inhibits cargo accumulation at the ERES. 
	- COP II decorates neck of ERES 
- Transport is then mediated by tunnels between ERES and ERGIC, or via COP II-free carriers that accumulate COP I as they move towards the Golgi 
	- Since ERGIC is formed by COP II vesicles, tunnel model can be reconciled with vesicle model 
- Different types of carriers may coexist to transport cargo from ER to Golgi
	- Different groups may have reached different conclusions depending on the type of cargo they tested (e.g. using waves of synchronised trafficking or bulky cargo may have shifted the balance towards a certain type of carrier)
	- The type of ERES may also affect what carrier is used (e.g. depending on distance from ERGIC, tunnel may not be as practical as carriers?)
![[Pasted image 20230403192608.png|375]]
 
## Experimental techniques
- Genetic approaches
- Biochemical approaches 
	- Radioactive S fed into yeast gP-α factor. Isolate ER, then add back components of cytosol to see if they can form smaller vesicles. Transport works if you add ATP, GTP, certain cytosol fractions -> defining minimum components 
	- Mix vesicles with purified Golgi to see what is needed for next step in pathway 
		- Requires α-1,6-mannose, requires cytosol ATP, GTP, etc. 
		- This step is inhibited by non hydrolysable analogs of biochemistry 

# Transport within the Golgi 
## Structure of Golgi 

| Region       | Marker             | Function |
| ------------ | ------------------ | -------- |
| Cis          | GM130              | Entry    |
| Medial       | Mannosidase II     |          |
| Trans        | GalT               | Exit     |
| Medial/Trans | GlcNac transferase |          |

## Biochemical assay for Intra-Golgi transport between cisternae 
1. Isolate a Golgi-containing fraction from VSV infected cells (so they contain VSV G marker protein) that are also mutated to lack GlcNac tranferase – this is the "donor" compartment
2. Isolate a Golgi-containing fraction from uninfected wild type cells – this is the "acceptor compartment"
3. Mix donor and acceptor
4. If transfer occurs from donor to acceptor, then VSV G will be modified by Glc Nac tranferase, which can be observed biochemically, usually by incorporation of radioactivity of radioactive N-acetylglucosamine 

Assay needs ATP, cytosol proteins, and GTP. 
In the presence of non-hydrolysable GTP analogues, resulted in accumulation of coated vesicles (COP I). 

## COP I mediates retrograde transport from trans to cis Golgi cisternae
- COP I coats assemble on donor membranes and transform into coated vesicles. These mediate transport between Golgi vesicles. 
- So COP II = anterograde, COP I = retrograde 
	- #experimental_evidence ERD2p, the yeast KDEL receptor responsible for retrieving resident ER proteins back to the ER, is enriched in COP I coated vesicles, and retrieval is blocked by COP I temperature-sensitive mutants. 
![[Pasted image 20230401172658.png|375]]

### Structure of COP I coat 
- #structural_evidence  Use of cryo-EM was instrumental to elucidation of COP I coat structure 
- COP I is made up of the B and F subcomplexes, which are each made up of protein subunits 
- There is limited homology of individual COP I proteins with COP II, however there are shared *functional* features, which may be common to all coat structures. 
- COP I B subcomplex – structurally similar to Sec31/13 complex, but sequence not that similar. 
	- Core structure is better conserved 
	- 2 β propeller domains next to each other. In COP I, both β propellers part of single polypeptide chain (cf Sec31/13, 1 propeller from each chain)
	- Centre of β propellers in B subcomplex is binding site for KK sequences in captured receptors (vs Sec31/13, where β propellers bind face to face or face to side)
- COP I F subcomplex – structurally similar to clathrin adaptors 
	- Also interacts with membrane but predominantly with Arf

### Assembly of B and F subcomplex 
- B subcomplex forms an arch over the F subcomplex, so that cargo binding sites face the membrane. (vs COP II which has inner and outer coat. Here, both interact with different membrane bound components)
- Three such COP I B/COP I F complexes form a triad, which is the basic building block of the coat Triads are linked together, with contacts of variable valence. Can get different size of coats with different numbers of triads, and thus different sized vesicles. 
- Arf interacts with components of both B and F subcomplex 
- B subcomplex does not form outer cage like in COP II
![[Pasted image 20230401172922.png|250]]

### Delivery of COP I vesicles depends on Arf 
[[A7 G proteins#Small G protein Structure and function]]
- Arf has an N-terminal helix that is myristoylated. This prenylated helix is important for membrane interaction. 
	- In GDP form, N-terminal helix is tucked into the enzyme  
	- In GTP form, N-terminal helix flips out with hydrophobic tail -> makes hydrophobic interactions with membrane 
- After a cargo receptor binds to its cargo, it recruits Arf GEF, which in turn recruits Arf1, resulting in nucleotide exchange and activation 
- Activation of Arf1 drives further activation of Arf GEF, as binding to the GTP-bound form of Arf1 results in a conformational change that opens up a Sec7 domain on ArfGEF. This results in a positive feedback loop. 
- When activated, Arf1 is recruited onto membranes via attachment to p23/24 proteins, which are resident on the membrane. It also extends myristoylated N-terminal helix for membrane interaction. 
	- p23/24 proteins contain C-terminal KKxx-like motif, important to nucleating assembly of coatomers 
- COP I binds as pre-assembled B and F subcoats onto activated Arf1. Arf GAP also recruited. 
	- Arf1 GAP is not itself part of coat. Most but not all have Arg finger. 

## Retrograde transport process – cargo selection
- Dilysine and diaromatic signals can interact with COP I coat; site of binding depends on motif  
- Cargo proteins can interact with COP I coat directly or via receptors (e.g. Erd2/KDEL receptor)
![[Pasted image 20230601224808.png|500]]

### From trans Golgi to cis Golgi 
- ARFs are involved in selection of cargo for incorporation into carriers 

#### Role of lipids
- The level of PI4P in the Golgi membrane could be important to cargo sorting 
- This is due to Vps74, a PI4P binding protein that also binds to cytoplasmic sorting signals on Golgi resident enzymes
	- #experimental_evidence Loss in function of Vps74, a PI4P binding protein, resulting in mislocalisation of Golgi mannosyltransferase, which is usually located in early/cis Golgi compartments 
	- #experimental_evidence There is a polarised distribution of PI4P across Golgi, with increasing concentration from cis to trans compartment 

### From cis Golgi to ER 
#### Membrane ER proteins 
- Membrane ER proteins contain the sorting signal KKXX or KXKXX in their cytosolic tails 
- These are directly recognised by COP I adaptor proteins, α and β' to form transport vesicles in an ARF-dependent manner.
	- The order in which adaptor proteins associate with cargo or with ARF is unclear. 
- #experimental_evidence KK motif can be put on yeast pheromone receptor Ste2p. This results in receptor being trapped in ER (as it is retrieved to ER), and yeast cells do not respond to pheromone. 
	- Mutations in COP I re-acquire pheromone sensitivity 

#### Luminal ER proteins 
- Luminal ER proteins contain C-terminal KDEL sequences, which is a retrieval signal recognised by a membrane-bound KDEL receptor in a post-ER compartment
	- In yeast, KDEL receptor is ERD2P
	- In mammals, KDEL receptor is KDELR
- KDEL receptor binds to an ARF-GEF, which in turn binds to ARF, causing nucleotide exchange of GDP to GTP
- ARF binds to cytosolic side of cis-Golgi membrane and inserts myristoylated N-terminal helix into membrane 
- COP I assembles onto ARF to form the vesicle, which buds off. 

## Movement of proteins from cis to trans Golgi 
- Controversies may be due to 
	- Use of non-representative model systems
	- Difficulties in imaging 

### Stable compartment model 
- Each Golgi cistern stably maintains its own composition by depending on material coming in on one end and exiting on the other via anterograde transport vesicles 
- Secretory cargo is transported anterograde from one cisternae to the next 

### Continuous maturation model 
#### Main claim and evidence 
- Golgi cisternae are dynamic, steady state structures where luminal material is continuously recycled via retrograde transport of COP I vesicles. While secretory proteins remain in place, Golgi resident enzymes are recycled back to earlier cisternae, such that each compartment gradually matures and acquires the composition of the trans-Golgi. 
	- #experimental_evidence Matsunra-Tokia et al (2006) found that material from more trans cisternae are being moved into material from more cis cisternae, transforming cis cisternae to trans cisternae. 
		- Budding yeast Golgi cisternae are not tightly stacked, but there are individual cisternae, these are easier to observe. Put red fluorescent marker on marker for trans golgi (Sec7p), and green fluorescence marker on marker for cis golgi (Gos1p). Then use microscopy to follow in real time the change in fluorescence. What happens is the colour changes within individual stacks, with initially green cisternae turning more red.
	- #experimental_evidence Ishii et al (2016) showed that COP I is responsible for retrograde transport between Golgi vesicles in yeast. 
		- Used purple tag for a cis marker and green for trans marker. Also used auxin-inducible degron (AID) signal to tag Sec21, to induce ubiquitination in the presence of the drug napthaleneacetic acid (NNA), and thus KO COP I structure. In control, cisternae changes from green (trans) to purple (cis). But when COP I KO'ed, no change in cis and trans markers over time.
	- #experimental_evidence Rizzo et al (2013) demonstrated similar findings as Matsunra-Tokia et al (2006), except in a mammalian Golgi system. 
		- FM domains cause the formation of aggregates as FMs form dimers. These aggregates are too large to be captured by coated vesicles. 
		- A cis/medial Golgi marker, mannosidase I (MANI) was genetically fused to FM domain. The cells were grown in the presence of a drug, AP, which causes dissociation of FM oligomerisation. Under these conditions, MANI was localised in the cis and medial cisternae. 
		- When AP drug washed away, they observed a movement of MANI along the cisternae, accumulating in the trans Golgi. This was because MANI aggregated and became too large to be captured by coated vesicles, preventing retrograde transport to the cis cisternae. 
	- #experimental_evidence Mironov et al (2001) demonstrated in human fibroblasts both small and large cargo proteins can transit through the Golgi complex from cis to trans without leaving the lumen of its cisternae. 
		- Synchronised pro-collagen I (PC-I) and VSVG transport by controlling the exit of both cargoes from the ER and the VTC. 
			- A temperature-sensitive mutant of VSVG was used which does not fold properly at 40°C and is thus accumulated in the ER. This block is lifted by shifting the temperature to 32°C, allowing for transport to VTC. 
			- PC-I exit from ER can be blocked by depriving medium of ascorbic acid (AA), as it is a cofactor for prolyl hydroxylase, preventing hydroxylation of PC-1 prolines and thus preventing folding. 40°C also enhances folding block. Adding AA and reducing temperature removes block. 
			- Traffic from VTC to Golgi can be stopped by immobilising VTC near ER at 15°C, and this block can be released by increasing the temperature. 
			- Thus, the researchers were able to release "pulses" of cargo material by blocking and releasing the blocks on cargo trafficking 
		- Use microscopy to observe VSVG and PC-I trafficking
			- They found that VSVG and PC-I traverse the Golgi at the same rate, suggesting they are transported via the same mechanism. This is possible under a cisternal maturation model but hard to imagine for a anterograde trafficking model 
			- When folding block released for PC-I, did not observe megavesicles for transport of ER, but only distensions of the Golgi cisternae containing the PC-I. 
			- When VSVG pulse was released to traverse Golgi, such that the pulse enters the Golgi at the same time, VSVG was concentrated within 1-2 stacks only, and a gradient of VSVG was not observed throughout the Golgi stack, as would be expected for an anterograde trafficking model. They also did not observe the presence of VSVG in Golgi vesicles.
	- #experimental_evidence Kurokawa et al (2019) also showed that cargo stays in a Golgi cisternae during maturation from cis-Golgi to trans-Golgi 
		- Axl2 is a transmembrane protein targeted to the plasma membrane. Axl2-GFP, Mnn9-mCherry (cis Golgi) and Sys1-iRFP (trans-Golgi). Pulse-chase assay for Axl2-GFP showed that cis-cisternae with Axl2-GFP matured into trans-cisternae while maintaining its cargo. 

#### Modifications of model  
- Retrograde trafficking may be taking some cargo back with them, resulting in back-transformation of Golgi cisternae. 
	- #experimental_evidence Casler et al (2019) designed a pulse chase experiment where "cargo was engineered to form ER-localized aggregates that dissociate into tetramers upon addition of a ligand. The solubilized tetramers rapidly exit the ER and then transit through early and late Golgi compartments before being secreted". They observed that the amount of fluorescent secretory cargo in a cisterna increased around the time of the early-to-late transition. This was due to intra-Golgi recycling that is dependent on the AP-1 clathrin adaptor. 
- Cargo exit from the Golgi has been observed to be exponential, which has been attributed to "rapid partitioning of enzymes and transmembrane cargo between two lipid phases combined with relatively rapid exchange among cisternae". 
	- #experimental_evidence Patterson (2008) #comment to read 
- Cisternae can form transient tubules between them? Intra-cisternal tubules may be another way for material to flow between cisternae. 
	#experimental_evidence Mironov (2017)

#### Process
1. VTCs (ER Golgi intermediate compartments) are generated by homotypic fusion of COP II derived coated vesicles
2. VTCs acquire Golgi components by heterotypic fusion with Golgi-derived COP I vesicles 
3. VTC elements fuse to form cis Golgi 
4. Cis Golgi cisternae mature into trans Golgi cisternae via retrograde trafficking via COP I vesicles

# Vesicle targeting 
or, how do vesicles know which compartment to go to for correct trafficking. 

## SNARE system 
### SNARE structure 
- Type II integral membrane proteins (i.e. N-terminal on cytosolic side)
- α-helical 
- 2 types of SNAREs, Q-SNAREs and R-SNAREs, which differ on whether they have Q/R at a particular site 
	- Q-SNAREs are SNAREs with a Q, e.g. e.g. syntaxin, SNAP25
		- SNAP-25 is unusual in that it is made up of a Qb-like domain and Qc-like domain that is linked by a palmitoyl group embedded in the membrane. 
		- Q-SNAREs form three different phylogenetic clusters (Qa, Qb, Qc)
	- R-SNAREs are SNAREs with an R, e.g. VAMP
- Target membranes usually have three different Q snares
	- Plasma membrane-originated membranes have a single syntaxin-like SNARE (Qa) and SNAP25-like SNARE (Qb, Qc)
	- Intracellular membranes have a syntaxin-like SNARE (Qa) and two non-syntaxin "light chains" (Qb, Qc)

### Mechanism of SNARE interaction  
- Q-SNARE and R-SNARE interact with each other via the R and Q, which form an internal hydrogen bond network buried inside hydrophobic core of SNARE ("zero layer")
- Isolated SNAREs are relatively disordered, but upon assembly they form α-helices, and interact to form tight coiled-coil structures. 
- Different membranes have different combinations of Q- and R-SNAREs. For two membranes to fuse, they need to have compatible sets of Q- and R-SNAREs. 
	- Homotypic fusion occurs if a particular combination of Q- and R-SNAREs is self-compatible, i.e. each Q-SNARE has a matching R-SNARE it can bind to in the same membranes. 
- On interaction, the SNAREs drive the fusion of the two membranes without external energy input. 
	- **Fusion hypothesis**. SNAREs can drive fusion on their own due to the presence of a stiff TMD. Formation of the coiled coil structure is very stable and releases so much energy that it can drive membrane fusion on its own without external energy input.
		- #experimental_evidence If TMD is replaced by flexible lipid anchor, it no longer works, as straining of stiff TMDs transmits energy onto membranes to bend/deform them. 
- After fusion, donor membrane SNAREs are incorporated into target membrane 
	- #question So how is the target membrane SNARE composition regenerated? 
	- SNAREs inevitably spread through several compartments during vesicular transport, so docking/fusion specificity cannot be determined by distribution of SNAREs alone 

### Experimental evidence for SNARES
- #experimental_evidence Isolating SNAREs. 
	- Take crude extracts from brain, incubate with tagged NSF/SNAP. In presence of non hydrolysable ATP forms stable complex of NSF/SNAP with SNARE. Then immunoprecipitate. 
- #experimental_evidence **Cracked PC12 assay** can be used to determine which regions of the SNARE is important for interaction. 
	- PC12 is a neuroendocrine cell, which has synaptic vesicles which can be loaded with neurotransmitter. Can stimulate exocytosis with drugs, e.g. carbocol. 
	- You can also break open cells to generate "cracked" cells, which results in cytoplasm leaking out, but keeps internal structures intact
	- By adding toxins that cleave the SNAREs, then adding back the cleaved off region, can see which regions can reconstitute the interaction and are thus critical for interaction 
		- E.g. Botulinum toxin cleaves between R180 and I181 in SNAP25 to release C-terminal peptide. A recombinant SNAP25 peptide can be added back into the cracked PC12 assay to restore fusion ability. 
		- Mutation in zero layer region (Q or R) has low effect on the assay. #question why? 
- #experimental_evidence Reconstitution of Q- and R-SNARE interaction. 
	- Purify SNAREs in liposomes. Use liposome assay to generate a panel of 11 R-SNAREs. Test for fusion with 3 Q-SNAREs
	- To some degree, pattern of membrane flow in cells is recapitulated by isolated SNARE proteins as predicted by SNARE hypothesis. 
- #experimental_evidence In vitro assay for homotypic SNARE interactions. 
	- Two yeast strains, one has pro-Alkaline phosphatase. No peptidase 46. Other has no pro-Alk Phos, but has peptidase 46. Peptidase 46 cleaves Alk Pho to activate it. If membranes fuse, see activity of Alk Pho. In each strain, can KO individual SNAREs. Same set of R SNARE and Q SNARE needed in each membrane for homotypic interaction (R of one membrane interacts with Q of other; Q of other interacts with R of other). But need to add NSF and SNAP. Sec17 and 18 unpick SNARE bundles i.e. disassembly. As complex is very stable, disassembly probably requires ATP input. 

## Regulation of SNARE assembly 
### SM proteins catalyse SNARE assembly 
- SM = Sec1p/Munc18p-like proteins. 
	- Munc = mammalian uncoordinated 
- SM proteins catalyse SNARE complex assembly through specific SNARE recognition
	- e.g. Vsp33 
		- #structural_evidence Baker et al (2015) showed that Vsp33 acts as a clamp to bring two SNAREs together. 
	- e.g. Munc18 
		- Munc18 binds to syntaxin, a Q-SNARE (according to #experimental_evidence affinity chromatography experiments)
		- Munc18 can bind to syntaxin when its Habc domain is in either the open or closed state. The open state is needed for membrane fusion, so initial experiments thought that Munc18 inhibited fusion because it was actually binding to syntaxin in its closed state. 
- This may increase efficiency of assembly, and also act as a quality control to ensure that the right R and Q-SNAREs interact. 

### NSF and SNAP catalyse SNARE disassembly 
- **Mechanism**. NSF and SNAP stack on SNARE complex. SNAP interacts with SNARE via Leu and Tyr residues that form a "chock" in between the helix bundles of SNAREs. When ATP is hydrolysed, there is rotation of D1 ring of NSF, which pulls down N domain of NSF, and in doing so pulls down SNAP and also rotates it anticlockwise. Effect is that chock will slide down between α helices of SNARE complex and open them up. As helices are pulled apart, water enters and breaks H-bond network between R and Q residues in zero layer. 
- #experimental_evidence Mutation of R and Q residues in SNAREs prevents disassembly by NSF, SNAP. 
- #structural_evidence Zhou et al (2015)

### Complexin and synaptotagmin poise vesicles for fusion 
- At the presynaptic terminal of a neuron, synaptic vesicles can fuse with the membrane to release neurotransmitters into the synapse via exocytosis. 
- Fusion of the synaptic vesicles via SNAREs is regulated by synaptotagmin and complexin
- Within the terminal, SNAREs of the synaptic vesicles and the plasma membrane are assembled into coiled coil complex, which poises them for fusion. 
- However, fusion is prevented by complexin, which interacts with the SNARE coiled coil complex. 
- Synaptotagmin can compete with complexin for binding to SNAP25, and binding of synaptotagmin allows fusion to occur. 
- Competition of synaptotagmin and complex is calcium-dependent. 
	- Under high calcium concentrations, calcium binds to synaptotagmin and causes a conformational change, increasing its affinity for SNAP25 and alowing it to compete off complexin. 
		- Calcium binding occurs at loop regions on synaptotagmin 
		- R233 is critical for calcium binding to loop; mutation to Q was known to prevent exocytosis. 

#comment  to read sudhof (2014)

## Tethering 
- SNARE system still shows errors of vesicle-target interaction 
- Tethering involves linkage between vesicle and target membranes that extend over 200-300 nm 
- Tethering involves macromolecular complexes that bring the vesicle closer to the target membrane to facilitate fusion via SNAREs
- Tethering is Rab-dependent, and many tethers are Rab GEFs. 
- Many tethering molecules exist, and are often not homologous, suggesting that they independently evolved. But there are two broad categories: long coiled-coil proteins and multi-subunit complexes. 

#comment How can this section be integrated with [[A7 G proteins#GDIs and Rab membrane cycling]]? 

### Tethering is Rab dependent 
- E.g. EEA1 tethers early endosomes to late endosomes. 
	- EEA1 binds vesicles to target in Rab-dependent manner
	- **Mechanism**. EEA1 is a dimer with long α helices. This is normally very stiff. But at one end it has a Zinc finger that binds to Rab, while the other end has FYVE domain that binds to lipids in early endosome. When GTP is hydrolysed, helix collapses. An allosteric change is transmitted through helix such that helix becomes disordered ('entropic collapse' of helix). This pulls the vesicles together so SNAREs can interact. As Rabs have intrinsic GTPase activity, if wrong Rab has bound, it can hydrolyse GTP to restore EEA1 structure, so thing may fall apart before fusion occurs. 
- E.g. TRAPP (TRAnsport Protein Particle) binds ER-derived COP II-coated vesicles to recruit Rab1p (Ypt1 in yeast)
	- TRAPP is a GEF for Rab1p
	- Rab1p recruits a coiled-coil tether to tether COP II to Golgi, e.g. Uso1 
	- TRAPP binds COP II vesicles via Bet3 subunit of Sec23 
- E.g. Golgin family tethers can mediate recruitment of cargo from early endosome to trans Golgi 
	- #experimental_evidence Cui et al (2019) 
- E.g. Exocyst tether recruits early endosome carriers to plasma membrane 

### Rab conversion couples Rabs to particular compartments 
- After a resident GEF recruits a Rab, that Rab itself brings in another GEF which recruits the Rab for the downstream compartment. In turn, the downstream Rab recruits a GAP for the upstream Rab. This results in different Rabs being tightly associated to different compartments. 
- E.g. TRAP I and II.
	- As Golgi cisterna matures from cis to trans, TRAPP I can acquire additional proteins (3 more subunits) to form TRAPP II
	- TRAP II is a GEF for another (yeast) Rab called Ypt31p (a late Golgi Rab)
	- #experimental_evidence Rivera-Molina & Novick (2009) – Ypt31p Rab brought in by TRAPPII GEF also brings in GAP for upstream Rab Ypt1p. 

#experimental_evidence Cai et al (2007) #comment to read 

# Endocytosis
## Process
1. Cargo binds to receptors in coated pits 
2. Coated pits invaginate to form vesicles
3. Coat proteins dissociate, leaving vesicle with cargo receptors and cargo 

## Structure of coated pits 
Coated pits are coated by a complex of proteins that exhibit avidity. 
#question How does cargo binding to the receptor lead to initial invagination of the pit? 
![[Pasted image 20230402000642.png|300]]
### Clathrin outer coat 
- Clathrin triskelion (three clathrin heavy chains and associated light chains) assembles into an outer coat 
- Different outer coat sizes can be created with different angles at vertex of triskelion and at distal kink, allowing for transport of different-sized cargo 
- #structural_evidence Cryo-EM has been critical to get atomic resolution of outer coats 
- #structural_evidence EM with platinum replica of membrane shows that under coated pits, clathrins form into hexagons. 
- Coated pits are created by local assembly of clathrin triskelions
- #structural_evidence Smith and Smith (2022) – Cryo-EM tomography shows that arrangement of lattice is disordered at local regions, e.g. breakage, misalignment. 
	- Tendency to form pentagons sometimes! 
	- Brownian ratchet 
	- Tension between hexagon formation (flat layer) and pentagon formation (spheres) drives shape changes. 

### Adaptors 
- 5 different APs associated with different compartments 

| AP  | Compartment                            |
| --- | -------------------------------------- |
| 1   | Trans-Golgi                            |
| 2   | Plasma membrane                        |
| 3   | Endosome – taking material to vesicles |
| 4   | Endosomes                              |
| 5   | Endosomes                              | 
![[Pasted image 20230402000529.png|325]]
- All have similar box-like structure comprised of two large adaptins 
- Adaptins have globular appendages that are linked to box via proline-rich linker. Linker means that a given adaptor can wiggle around and use appendage domain to explore a large volume than if it were rigidly attached to box 
- #structural_evidence Jackson et al (2012) – X-ray structure has been solved 
- AP2 appendages are binding sites for receptors 
	- AP2 acts as an adaptor that binds receptors, linking them to coated pit complex -> wider range of cargo can be captured by AP2 
	- Binds DFF motifs in a single hydrophobic binding pockets; DFF motifs found in many kinds of proteins 
- Has PIP2/PIP3 binding sites on mew subunit 
	- As AP2 binds to plasma membrane, it does so initially via PIP2/PIP3 binding site – weak binding affinity
	- Conformational change occurs where mew subunit swings out (it is linked to main body via linker)
	- Linker contains a threonine that can be phosphorylated which increases affinity of AP2 for plasma membrane. 
	- This reorientates mew so second PIP2/PIP3 binding site is exposed. It also exposes YXXphi for binding ==> increased binding affinity at membrane. 

![[Pasted image 20230402000545.png|175]]

#### Evolutionary origins of vesicle coats 
- AP adaptins are structurally similar to F subunit of COP I with a core 'block', a subunit equivalent to mew, and similar appendages 
![[Pasted image 20230402000848.png|300]]
- #experimental_evidence Hirst et al (2014) – COP I, APs, muniscin originate from the evolution of the TSET complex, members of which can be found across the eukaryotes. 
- The nuclear pore complex components are also distant homologs of clathrin, COP I, COP II coats 
	- Formation of nuclear envelope also involves bending of the membrane 
- β-propeller structure found across coat proteins – clathrin, COP I, COP II. But the structure mediates protein interactions in different ways: 
	- Clathrin – proteins slide between propellers
	- COP I – bind to center of propeller
	- COP II – bind face-to-face or face-to-side of propeller 

### Epsin 
- Affects shape and structure of membrane – along with clathrin, can drive deformation of coated pit without external energy input (e.g. from ATP)
- Has **globular domain** that interacts with membrane 
	- Globular domain has a helix that binds into hydrophobic pocket, but when it binds to lipids, it undergoes conformational change that causes helix to flip out, allowing lipid to bind. This induces tubulation, distorting the membrane, probably bc it can insert into inner leaflet without inserting in outer leaflet -> bends membrane. 
- It also has a **long disordered tail** containing multiple motifs that interact with multiple members of coated pit complex -> scaffold 

## Dissociation of pit from membrane 
![[Pasted image 20230402000753.png|175]]
### Amphiphysin 
- Assembles along neck of growing coated pit, forming a circular ring. Each stack on each other to give a tube that forms around the neck 
- Has BAR domain which is seen in many proteins involved in protein traffic 
- BAR domain is curved 
- Amphiphysin and BAR domain also contains motifs that recruit other proteins e.g. synaptojamin, which chops off head of pit -> introduces directionality to invagination 

### Dynamin 
- Also assembles on amphiphysin. 
- Has PH domain for lipid binding, proline rich domain for binding other proteins (e.g. amphiphysin)
- GTPase domain 
- GTPase effector domain. Physically distant from GTPase domain, so single dynamin cannot activate itself. But when it assembles on necks in association with amphiphysin can effector domain of one dynamin can interact with GTPase domain of another dynamin, activating the GTPase. GTP hydrolysis drives snapping of neck probably by constricting the neck until membranes break. 
	- #experimental_evidence Shibire mutation in *Drosophila*. At neuromuscular junction, see accumulation of invaginated coated pits. 
	- #experimental_evidence Dynamin KO creates elongated necks that are also covered in actin. In absence of dynamin, BAR domain amphiphysin continue to accumulate, and they recruit actin filaments. Final snapping off of coated pits may be enhanced by presence of actin. Combination of amphiphysin, dynamin, and likely actin probably drives snapping off of vesicle. And also synaptojamin. 

## Uncoating 
- HSC70 (heat shock cognate 70) coopted as an uncoating enzyme. Binds to C-terminal sequence (QLML motif) on clathrin which sits underneath vertex. 
- In assembled coat, motif interacts with an inner layer of clathrin
- HSC70 interacts with the motif, assisted by auxilin. 
- It dissociates outer triskelion and inner clathrin. Either because it disrupts interaction ("steric wedge" model), or because when it binds, random movement of HSC70 can dislodge the clathrin ("wrecking ball" model)
	- Different from COP II and COP I #question how are these uncoated... 

![[Pasted image 20230402000828.png|275]]

# Endosomal pathway 
![[Pasted image 20230401235843.png|300]]
## Function and flow
- Fundamentally, the classic endosomal pathway has a few elements
	- Recycling circuit for plasma membrane components and ligands – early endosomes + recycling endosomes 
		- Marker – transferrin and transferrin receptor 
	- Degradative system for digesting macromolecules – late endosomes, LROs, lysosomes
		- Marker – EGF and EGFR; after ubiquitination of EGFR, it is taken to lysosomes 
	- A feeder pathway from early to late endosomes for transporting fluids, membrane components from the recycling circuit to the degradative system
- The trans Golgi network can send vesicles to any of the endosomes
- Most cargo internalised via endocytosis is recycled back to plasma membrane via the early endosomes (e.g. receptors)
- Other cargo is sent to lysosomes; selection for this pathway is stringent 
- Lysosomal components are also transported via the degradative pathway (e.g. lysosomal hydrolases, membrane proteins) to replenish the components 
- Events in the pathway can occur non-synchronously, and many markers are only transiently associated with organelles; "ambiguity, heterogeneity, and lack of synchrony" makes it difficult to define particular models for the endosomal pathway (Huotari and Helenius 2011)

## Components of endosomal pathway 
### Early endosome 
- Receives cargo from endocytic vesicles. 
- Targets cargo to degradative pathway or recycling pathway. 

#### Organelle identity 
- Rab5 and effector VPS34/p150 (a PI(3) kinase) complex generate phosphoinositide PtdIns(3)P

#### Traffic between early endosome and TGN 
[[C2 PTMs and Protein trafficking#Transport from endosomes to trans Golgi network|Endosomes to trans Golgi]] 
- Bidirectional 
- Occurs at all stages of endosome maturation 
- Required for delivery of lysosomal and removal of endosomal components for endosome maturation 

#### Traffic from early endosome to lysosome 
- After uncoating, endocytic vesicles fuse with early endosomes 
- Receptors of lysosome-targeted cargo proteins are mono-ubiquitinated soon after activation by cargo binding. Adaptors eps15 and epsin have a ubiquitin interacting motif (UIM) protein that binds to the ubiquitin, allowing interaction with the coated pit 
![[Pasted image 20230402001021.png|175]]
- Ubiquitination causes receptor to get stuck in early endosome rather than recycle back to membrane due to association with Hrs. 
	- #experimental_evidence If transferrin is tagged with ubiquitin, it gets stuck in early endosome instead of recycling back to endosome 
- Hrs also recruits clathrin to the early endosome 
	- Hrs binds to ubiquitin on receptor
	- STAM acts as bridge between clathrin and Hrs 
	- #experimental_evidence Raiborg et al (2006) – Hrs KO via siRNA. Then transfect siRNA-resistant Myc-Hrs RNA. When Hrs restores, it reassociates with EEA1 and clathrin. 
![[Pasted image 20230402001045.png|400]]
#structural_evidence Paraan et al (2020) – review of structural techniques used to study entire structure of coated pits 

### Late endosomes 
- Can fuse with each other as well as with lysosomes 
- Fusing with lysosomes results in most late endosome content being degraded, but some are retained in lysosome and contribute to its function 

## Flow between endosomal pathway compartments 

### ESCRT complexes form internal vesicles in early endosome 
#### Function 
- Sorts ubiquitinated membrane proteins into internal vesicles

#### Mechanism 
- ESCRT0 binding to ubiquitinated receptor triggers a cascade of assembly locally that leads to perturbation of membrane 
	- #structural_evidence Structures of ESCRT0 heterodimer of HRS/STAM show that it uses an N-terminal VHS domain and central ubiqutin-interacting motif or di-ubiquitin-interacting motif 
- ESCRT0 -> ESCRT I -> ESCRT II -> ESCRT III 
	- Ubiquitin-tagged cargos are sequestered by different ESRT subunits via different structural mechanisms, sequestering the cargo into endosomal domains  ![[Pasted image 20230601223040.png]]
	- However all contact same surface of ubiquitin containing Ile44, so ubiquitin cannot bid more than 1 ESCRT subunit at a time. Modification of ubiquitin chain can thus affect sequestration of cargo by ESCRT (e.g. polyubiquitination, deubiquitinase)
- ESCRT II is bivalent, allowing for assembly of a ring-like structure. This invaginates the early endosome from the outside.
- After cargo is sequestered in endosomal domain, they are deubiqutinated and sorted into intraluminal vesicles formed by ESCRT III 
- Vps4 catalyses hydrolysis of ATP, releasing energy to drive a twisting force that snaps off the neck of the invagination, resulting in the formation of internal vesicles containing the cargo and receptor.
- ESCRT proteins are also involved in virus budding and cytokinesis 

![[Pasted image 20230402001143.png|400]]
Olmos (2022)

### Transport from endosomes to trans Golgi network via Retromer complex 
- Retromer complex create vesicles from early endosomes that transport cargo to the trans Golgi 

#### Structure 
- Three core subunits, VPS29, VPS26A/B, and VPS35, which scaffold regulatory factors 
- SNX (sorting nexin) proteins are adaptors select cargo in early endosome for recycling to TGN (i.e. SNX3) or to plasma membrane (i.e. SNX27) and interact with Retromer complex 
	- PX domain of SNX3, SNX27 interacts with endosomal lipid phosphatidylinositol-3-phosphate (PtdIns3P) 
	- SNXs recognise particular signal motifs in cytoplasmic domains of receptors, e.g. SNX3 can recognise WLM motif in cation-independent mannose-6-phosphate receptor (CI-MPR)
	- Some SNX proteins (e.g. SNX17, SNX5) also interact with other retrieval complexes (e.g. Commander, ESCPE) but these are not covered here 
- Retromer itself also mediates cargo recognition alongside SNX 
	- #structural_evidence Lucas et al (2016) solved crystal structure of Retromer and SNX3 in complex with the divalent metal transport 1-II (DMT1-II)
		- Retromer-SNX3 recognises a hydrophobic motif ΩΦ[LMV] (Ω = aromatic, Φ = hydrophobic)
		- SNX3 N-terminal domain interacts with interface between VPS26A and VPS35 in Retromer complex, which causes C-terminal β-sheet domain of VPS26A to undergo a conformational change, exposing a hydrophobic ligand binding site for recycling cargo 
		- Cargo binding site formed by VPS26A and SNX3
	- #structural_evidence Clairfeuille et al (2016) solved crystal structure of SNX27 PDX domain bound to DGKζ-derived peptide 
		- SNX27 PDZ domain binds binding motifs with consensus sequence [ST]xΦ 
		- Binding is further enhanced if the binding motif contains negatively-charged Asp or Glu which form H bonds and ionic interactions with Asn56, Arg58 in SNX27 binding pocket 
		- Alternatively, phosphorylation of the residues in the same positions as Asp or Glu will suffice by mimicking negative charge 
		- Binding affinity sterically enhanced by SNX27 interaction with VSP26
	- So mechanism of how Retromer contributes to cargo selection by SNX proteins differs.
- In yeast, Vps5 and Vps17 are SNX family proteins that can also associate with Retromer for retrieval of vacuolar cargoes, but in higher eukaryortes they have been repurposed for retrieval of a range of different transmembrane proteins in a Retromer-independent manner, as part of the ESCPE-1 complex 
- BAR domains of SNX can drive membrane tubulation by assembling into a ring 
- Some Rabs do bind selectively to retromer complexes
	- E.g. Rab7 is required for stable association of Vps35 and further stabilising local patches of membrane that will eventually be removed to mature that endosome (see [[C2 PTMs and Protein trafficking#Endosome maturation|endosome maturation]])

### Endosome maturation  
- Rather than early and late endosomes being distinct compartments, early endosome matures into late endosome
- Analogous to Golgi cisternae maturation? 
- Maturation involves [[C2 PTMs and Protein trafficking#Rab conversion couples Rabs to particular compartments|Rab conversion]] 
	- #experimental_evidence Peplowska et al (2007)
	- #experimental_evidence Rink et al (2005) – maturation can be followed in real time via fluorescence microscopy 
	- Rab5 (vps21 in yeast) is exchanged for Rab7 (Ypt7 in yeast)
		- Yeast vps21/mammalian Rab 5 is driven onto early/sorting endosome by a tether called CORVET, which is a GEF
		- Rabex-5, a Rab5 GEF, is recruited to EEs via a ubiquitin E3 ligase domain, which binds to ubiquitinated proteins found in EE. Rabex-5 activates Rab5. 
		- Rabex-5 activity is itself promoted by the Rab effector Rabaptin-5, resulting in a positive feedback loop between Rab5 and Rabex-5 
		- Activated Rab5 recruits the Rab7 GEF SAND1/Mon1-Ccz1 complex, which in turn recruits Rab7, HOPS,  and diplaces Rabex-5 from endosomal membrane, thus promoting Rab7 binding. SAND1/Mon1-Ccz1 additionally may displace GDI from Rab7
		- Rab5 GAP is recruited following Rab7 recruitment 
		- CORVET and HOPS share core proteins but have different accessory proteins. Since Rab5 interacts with CORVET, and Rab7 with HOPS, the CORVET/HOPS conversion may be linked to Rab conversion 
	- Rab4, 11 and 22 are also lost, while Rab9 is added 
- Maturation could also involve a fission event 
	- Part of a hybrid endosome containing a nascent Rab7 is separated from the rest 
	- Microtubules, dynein involved in separating endosomal elements containing transferrin from EGF, markers for recycling and lysosomal pathways respectively (Driskell et al 2007)
	- Dynamin may also be involved (Mesaki et al 2011)
- Changes in fusion specificity. 
	- Acquisition of new tethering complexes and SNAREs that ensure that late endosomes only fuse with each other, with lysosomes, and autophagosomes 
- Transmembrane cargos are sorted into separate membrane domains during maturation, based on whether they are targeted for recycling or degradation 
	- ESCRT targets cargo for degradation while a variety of opposing retrieval complexes target cargo for retrieval and recycling in a sequence-dependent manner. SNX proteins are often adaptors for cargo recognition. ![[Pasted image 20230601214055.png|500]]
- Other characteristics: formation of ILVs (via ESCRT), acidification, PI conversion, change in morphology, gain of lysosomal components from TGN, loss of recycling pathway, removal of proteins via retromers, etc.
- These changes ensure that late endosome becomes closed off to recycling and other functions of early endosomes, while facilitating its function in the degradative pathway 

We are still struggling to connect static structural understanding with dynamics of protein trafficking. 

## Sorting in endosomal pathways 
- Sorting takes place in endosomes. Endosomes are fed by vesicles from endocytosis (from membrane to cytoplasm) or secretory pathway from Golgi (from cytoplasm to membrane)
- Sorting requires a coat complex, and a sorting signal on the cargo that is recognised by the coat. 
- "Compartment boundaries along the recycling or degradation pathways seem blurred at the molecular level, in particular when following a single component. It is probably the interplay between key components that defines the functional boundaries in each pathway." 

## Sorting signals 
- Short linear motifs contained within cytoplasmic domain 
- Although individual affinity is very weak, on surface of plasma membrane, with 2D interaction and high local concentrations, binding can be significant 
- Sorting signals can be identified via Ala substitutions in the receptor tails (Ala scanning) and measuring the extent of internalisation/endocytosis of the protein 

| Signal                            | Function                                                                          |
| --------------------------------- | --------------------------------------------------------------------------------- |
| D/E(polar)-LL                     | Endocytic and lysosomal                                                           |
| YX(anything)XO(bulky hydrophobic) | Y is critical. X tends to be polar. Subtle differences for AP1 and AP2 preference | 

- AP1 seems to be more restricted to particular types of motifs, while AP2 is more promiscuous. 
	- This allows for error correction. Most cargo intended for the lysosome is captured by vesicles coated with AP1, but some are not and are secreted to the plasma membrane. As AP2 is more promiscuous, these incorrect cargo can also be captured and recycled back into endosome for delivery again. 
	- On the other hand, for secretory cargo not intended for the lysosome, most will bypass it and be secreted. 
- YXXΦ motif binds to µ subunit of adaptin. 

# Remaining issues
(from Barlow & Miller 2013)

- How do folding, degradation, export machineries interact to regulate secretory protein biogenesis 
- How is early secretory pathway organised? 
	- What is the importance of ER exit sites? 
- Do all secretory proteins go through Golgi? 
- How is cis Golgi created? 
- How are protein and lipid needs of cell sensed and maintained?
- How are rates of retro and anterograde traffic balanced? 
