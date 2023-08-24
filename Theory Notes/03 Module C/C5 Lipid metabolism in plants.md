# Questions 
- What role does phosphatidylcholine (PC) play in the biosynthesis of unsaturated fatty acids? Explain the relationship between neutral lipids (e.g. diacylglycerol and triacylglycerol) and PC - how does this contribute to the overall lipid composition of seeds?
- What causes lipid diversity + how can this understanding of diversity be used to engineer plants to express non-native fatty acids 
	- *==What factors are likely to determine the chemical diversity found in the fatty acids present in plant seeds? How might these factors impact on biotechnological efforts to make non-native fatty acids in transgenic plants?==*
	- How has the evolution and divergence of fatty acid desaturases contributed to diversity in plant seed oils? Give examples of how this knowledge can be exploited to engineer plants with novel fatty acids.
	- What has been responsible for the chemical diversity of fatty acids present in plants? How can understanding of this diversity be used to engineer plants to accumulate non-native fatty acids?
- ==Discuss the metabolic pathways of fatty acid biosynthesis in plants and how they might be manipulated for bioengineering.==
- Role of acyl-CoA pool 
	- Considering both endogenous and heterologous lipid biosynthetic pathways, why is the acyl-CoA pool considered to be the metabolic hub of extraplastidial plant lipid metabolism?
	- In transgenic plants modified to produce non-native fatty acids, what is the role of acyl-exchange between different metabolic pools?
- Constraints in metabolic engineering of plant lipids
	- What are the constraints on the metabolic engineering of plant lipid metabolism? How might these constraints be circumvented?
	- Describe the metabolic bottlenecks which result in the poor yield of unusual fatty acids in transgenic plants. What approaches can be used to overcome these bottlenecks and to enhance the accumulation of these fatty acids?

# Fatty acids in plants 
## Nomenclature 
- x:yΔ<sup>z</sup> – x = number of carbons, y = number of double bonds, z = position of double bonds (counted from C1, the carboxyl carbon). 9t = trans double bond at C9 
![[Pasted image 20230403165946.png|325]]
## Composition 
- Common lipids
	- 16:0 palmitate 
	- 18:0 stereate 
	- 18:1 oleate 
	- 18:2 linoleate 
	- 18:3 alpha-linolenate 
- Many unusual fatty acids have useful non-food applications as industrial or chemical feedstocks 
	- 12:0 lauric e.g. soap 
	- 22:1 erucic e.g. paint
	- 18:1-OH ricinoleic e.g. lubricant
	- 18:1-O vernolic e.g. plastisizer
	- 18:1Δ<sup>6</sup> petroselinic e.g. high grade plastics 

# Fatty acid biosynthesis pathways 
## General principles
- Fatty acid metabolism occurs in multiple cellular compartments
	- **Plastids mainly contain galactolipids** e.g. monogalactodiacylglycerol (MGDG) or digalactosyldiacylglycerol (DGDG)
	- **Endoplasmic reticulum mainly contains phospholipids** e.g. phosphatidylcholine (PC), phosphatidylethelolamine (PE), or phosphatidic acid (PA)
- Fatty acid metabolism does not occur on free fatty acids
	- In the plastid, fatty acids are **acyl-carrier protein (ACP)-linked** or on **galactolipids**
	- Outside the plastid, fatty acids are **acyl-CoA-linked** or are on **(phospho)glycerolipids** 

## Fatty acid synthesis pathway 
- Initial synthesis occurs in plastids, where fatty acid synthase catalyses a series of reactions to add two carbon units to a fatty acid chain at a time, resulting in a 16 or 18C fatty acid attached to an acyl-carrier protein. In the plastid, a Δ9 ACP desaturase introduces a double bond, coupling synthesis to initial desaturation. 
- ACP moiety is removed by thioesterase, then fatty acid is exported via FAX1 to the cytosol
- Further elongation takes place in acyl-CoA pool, while further desaturation takes place in phosphatidylcholine (PC) pool, both in ER.  
- Acyl editing, mediated by lysophosphatidylcholine acyltransferases (LPCATs), results in exchange between acyl-CoA and PC pools 
- In ER, fatty acids can be sent to DAG pool via two pathways 
	- Acyl-CoA dependent Kennedy pathway
		- G3P is first sequentially acylated by Glycerol-3-phosphate acyltransferase (GPAT), then by lysophosphatidic acid acyltransferase (LPAAT), using acyl-CoA to produce phosphatidic acid (PA) 
		- PA is dephosphorylated by PA phosphatase to produce diacylglycerol (DAG) 
	- PC-derived DAGs can be synthesised in different ways 
		- Phosphatidylcholine:diacylglycerol cholinephosphotranferase (PDCT) transfers head group from PC to DAG 
		- Phospholipase C
		- Reverse reaction of CDP-choline:diacylglycerol cholinephosphotransferase (CPT) 
- To move from DAG to TAG: 
	- diacylglycerol acyltransferase (DGAT) transfers acyl-CoA to sn-3 position of DAG to produce TAG
	- Phosphlipid:diacylglycerol acyltransferase (PDAT) transfers sn-2 acyl group from phospholipid to DAG to form TAG. 

> [!image] Major pathways of TAG production in seeds (Haslam et al, 2016)
> PC pool = site of fatty acid desaturation 
> 
> Acyl-CoA pool = site of fatty acid elongation 
> 
> TAG pool = site of fatty acid compartmentation; metabolic dead end 
> ![[Pasted image 20230601160426.png]]

## Desaturation 
### Synthesis of monounsaturated fatty acids 
- Desaturase properties 
	- Catalysed by a soluble desaturase 
	- Done on ACP-linked substrates = ACP desaturase 
	- Ferredoxin used as electron donor 

#### Structure of plastidic stearoyl ACP Δ9-desaturase 
- Dimer, but only "half-of-the-sites" reactivity
	- #experimental_evidence Liu et al (2015)
- Desaturase is di-iron enzyme. Δ9 carbon atom is in vicinity of one iron atom 
- Monomer consists of a single domain of 11 alpha-helices, 9 of which form an antiparallel helix bundle 
- A deep channel extends throughout the desaturase that binds the fatty acid 
- #structural_evidence Lindqvist et al (1996), Cahoon et al (1997) obtained X-ray crystal structure 
- Uses 18:0 as substrate 

### Converting monounsaturated to polyunsaturated fatty acids 
- Synthesis of fatty acids containing 2 or more double bonds occurs in both plastid and ER
- Monounsaturated fatty acids can be exported from the plastid to the ER, or incorporated into plastidial lipids 
- Desaturase properties
	- Membrane-bound enzymes – more challenging to obtain crystal structures, and still no crystal structure for these enzymes
	- Done on lipid-linked substrates
	- Uses cytochrome b<sub>5</sub> (ER) or ferredoxin (plastid) as electron donors 

#### Structure of polyunsaturation desaturases 
- Conserved HxxHH and HxxxH motifs that are essential for catalytic activity 
	- His boxes may coordinate Fe atoms used in desaturation reaction (similar to soluble ACP desaturase)
- Enzymatic reaction likely to occur on cytosolic face of ER/stromal face of plastid 
- Electron transport chains are in proximity (cyt b<sub>5</sub>/ferredoxin)
![[Pasted image 20230403172533.png|200]]

### Fatty acid desaturases generate diverse lipids 
- All plants contain a 18:0 (stearoyl) Δ9 desaturase 
- But there are many other **diverged** desaturases that act on different fatty acids and desaturate at different carbons
	- Different plant species can have different desaturases
	- These generates diversity in lipids between plant species 

#### Structural determinants of specificity 
- #structural_evidence Homology modelling of variant forms of ACP desaturases onto archetype stearoyl ACP Δ9-desaturase 
	- E.g. Geranium 14:0Δ9 ACP desaturase has a leucine residue at the end of the lipid binding channel where the regular stearoyl ACP Δ9-desaturase would have a glycine. This was predicted to shorten the binding channel such that the desaturase becomes specific to 14:0 instead of 18:0 #comment factcheck this 
- #structural_evidence Structure-function predictions from homology modelling could be tested via rational design site-directed mutagenesis of ACP desaturases 
	- E.g. Castor Δ9-18:0-ACP desaturase was mutated with a L118W mutation. L118 is located at the end of the binding channel, so mutation to W was expected to shorten binding channel. This resulted in an increase in activity on 16:0 and 14:0 lipids and a decrease in activity on 18:0 lipids. However, the mutation did not abolish activity on 18:0 lipid, suggesting that residues other than L118 are responsible for determining specificity 
	  ![[Pasted image 20230403172005.png|225]]
- Need more structures of enzymes involved in lipid metabolism to understand specificity 

# Expression of non-native fatty acids in plants 
## Many fatty acids are economically valuable but unsustainably produced 
- Many polyunsaturated fatty acids are economically valuable
- E.g. Omega-3 long chain polyunsaturated fatty acids (LC-PUFA) – EPA and DHA 
	- Important dietary components 
	- Primary source is fish oil 
	- But over-fishing and marine pollution means that fish oil is not a sustainable source of omega-3 fatty acids 
	- Synthesis in plants would be a sustainable alternative 
- E.g. wax esters (also LC-PUFA) – used as biolubricants and surfactants. Highly thermostable and more sustainable than fossil fuels 
- E.g. Unusual fatty acids – chemical feedstocks. 

## Why are seed lipids amenable to engineering? 
- Lipid biosynthetic pathways are well-characterised
- Analytical techniques for measuring fatty acid, lipid molecules have been developed
- Lipidomic technique exist for global profiling of lipids 

## Why engineering in the first place
- Extent of genetic diversity achievable via conventional crop breeding is limited 

## Process overview 
We want to express a desired lipid and have it be in the TAG pool. 
Expression of non-native fatty acids in plants relies on
1. Expression of the necessary enzymes that can convert endogenous fatty acids into the desired product 
	1. Heterologous expression of enzymes 
	2. Modifying endogenous enzymes 
	3. Altering expression patterns of endogenous enzymes 
2. Ensuring that the fatty acids are in the right metabolic pool to be enzymatically processed (acyl editing/acyl exchange)
	1. Use acyltransferases to shift lipids between metabolic pools 
	2. Use enzymes that act on the same metabolic pool 
3. Selecting the right host plant – endogenous pathways may be important too 

Afterwards, **iterative design** and testing will be needed to fully optimise the pathway (i.e. introducing genes 1 at a time and measuring the effect on lipid accumulation)
- E.g. To engineer expression of LC-PUFA in plants, a number of studies used an iterative pathway combining different genes to alter lipid synthesis 
- Efficacy can be determined using lipidomic analysis – accumulation of a particular lipid intermediate suggests a bottleneck 

# Bioengineering strategies 
## Engineering enzymes 
- FAD2 Δ12 desaturase can be converted to an FAH12 C12-hydroxylase and vice-versa 
	- #experimental_evidence Broun et al (1998) achieved this via brute-force mutagenesis rather than rational design 
		- 4 changes were needed to convert desaturase to hydroxylase, but 7 to do the reciprocal. Unclear why. 
- Castor ACP Δ9 desaturase that is specific to 18:0 ACP-linked fatty acid could be [[C5 Lipid metabolism in plants#Structural determinants of specificity|engineered]] to be specific to 16:0-ACP
	- This allowed for production of an omega-7 unsaturated fatty acid, i.e. palmitoleic acid (16:1Δ9), which is rare in oilseed crops 
	- Vegetable oils enriched in omega-7 monounsaturated fatty acids can be used to produce 1-octene, and could replace petroleum as the feedstock for 1-octene 
- **Wax ester synthesis.** Need to engineer a **fatty acid reductase** to convert fatty acids to fatty alcohols, and **wax synthase** to link fatty alcohol to other fatty acids, producing wax esters
	- Both FAR and WS use acyl-CoA substrates, so no substrate dichotomy problem. 
	- #experimental_evidence Heilmann et al (2012) co-expressed mouse WS with mouse peroxisomal FAR, engineered to localise them to the ER, in Arabidopsis seeds. 
- Alteration of ORF can be done *in vivo* with CRISPR-Cas9 as well, directly editing genome 

## KO/KD enzymes with undesired activity 
- #experimental_evidence Cahoon and Shanklin (2000) – To produce more omega-7 monounsaturated fatty acids in *Arabidopsis*, β-ketoacyl-ACP synthase (KASII) was inactivated via mutation to prevent elongation of 16:0-ACP to 18:0-ACP, increasing concentration of 16:0-ACP available to an engineered Δ9-16:0-ACP desaturase 
- #experimental_evidence In contrast to the strategy by Cahoon and Shanklin (2000), [[NguyenEtAl_2015]] knocked down KASII in *Camelina sativa* with RNAi. They also knocked down fatty acid elongase 1 (FAE1) and FatB 16:0 ACP thioesterase with RNAi, to further increase the pool of 16:0-ACP 
- #experimental_evidence To improve conversion of DAGs to acTAGs instead of "regular" TAGs, Liu et al (2015) used RNAi to knock down DGAT1 in *C. sativa*, which produces regular TAGs from DAGs. This prevents competition between EaDAcT and DGAT1 for DAG substrate  
- Delete gene from genome using CRISPR-Cas9 -> less "leaky" than RNAi and amenable to growing in field 
	- #experimental_evidence Haun et al (2014) Nucleases were used to silence soybean FAD2 to create a seed rich with oleic acid 

## Heterologous expression of enzymes with desired activity 
- #experimental_evidence [[NguyenEtAl_2015]] co-expressed an engineered Δ9-16:0-ACP desaturase with a *C. elegans* FAT5 Δ9-16:0-CoA desaturase to increase omega-7 monounsaturated fatty acids 
- Acetyl-TAG could be useful as a lubricant, cooking oil, or replacement for some biodiesels. It is similar to TAG but with an acetate at sn-3 position instead of fatty acid. To produce acetyl TAGs, we need an enzyme from *Eunymous alatus*, diacylglycerol acetyltransferase (EaDAcT), which transfers acetyl group from acetyl-CoA to DAG.  
	- #experimental_evidence Liu et al (2015) expressed EaDAcT in seeds of *Camelina sativa* and soybean, resulting in seed oils with up to 70% of TAGs being acTAGs 

## Alter regulatory elements 
- E.g. gene orientation, spacing, promoter choice, co-expression of transcription factors 
- Site of transgene introduction – ideally should be one that is [[Discuss the factors that can affect expression of transgenes in transgenic organisms.|highly expressed]] and lack essential genes for plant fitness 
- However, having too many copies of the same promoter sequence could cause silencing in some genes 
	- #experimental_evidence Chen et al (2006) used a strong seed-specific promoter for several transgenes used to produce DHA in *Brassica juncea*, but the levels of fatty acid went down in subsequent generations, which was speculated to be due to silencing 

## Acyl exchange 
### Attachment to different lipids results in fatty acids being recognised by different enzymes 
- Fatty acids can be present in different lipids as part of lipid "pools"
	- Fatty acids can exist outside of a lipid (free fatty acid)
	- Also occur in different lipids
		- Phosphatidylcholine 
		- Diacylglycerol
		- Triacylglycerol
		- Acyl-CoA 
- However, depending on the lipid pool it is in, the fatty acid can be recognised by some enzymes but not others. As such, fatty acids can be "hidden" from enzymes if they are not in the right lipid pool 
	- #experimental_evidence  Castor C12 hydroxylase (FAH12) was heterologously expressed in non-native hosts (e.g. *Arabidopsis*) to synthesise ricinoleic acid. However, this resulted in poor accumulation of ricinoleic acid (17-25% in seeds, compared to 90% in castor). This is because In its native host, ricinoleic acid is found on seed triacylglycerols. This involves transfering the ricinoleic acid from their site of synthesis (phosphatidylcholine) and incorporating them into triacylglycerols. Ricinoleic acid is not membrane compatible (because of the hydroxyl group), and so must be rapidly removed from phospholipids. However, non-native hosts lack this transfer activity
	- At the moment, we don't understand what are the structural determinants of specificity for one lipid pool but not another 
- Metabolic pools in plants 
	- PC pool = site of fatty acid desaturation. Fatty acid desaturases require glycerolipid substrates 
	- Acyl-CoA pool = site of fatty acid elongation. Fatty acid elongases require acyl-CoA substrates 
	- TAG pool = site of fatty acid compartmentation (where we want to extract the fatty acids from)
- "Pachinko" – at every step of a metabolic pathway, the fatty acid could be shuttled between different metabolic pools. 
	- Shuttling of lipids is mediated by endogenous acyltransferases 
		- PDAT (Phospholipid:Diacylglycerol Acyltransferase) channels Δ6-desaturation products into TAG pool 
		- CPT/PDCT (Phosphatidylcholine:Diacylglycerol cholinephosphotransferase) channels Δ6-desaturation products into DAG pool 
		- LPCAT (Lyso-phosphatidylcholine acyltranferase) – PC to CoA 
		- DGAT – DAG to TAG 
![[Pasted image 20230403181415.png|250]]
- The low accumulation of non-native fatty acids is thus often due to the fatty acids being in the **incorrect metabolic pools**, which prevents them from being processed by enzymes or being moved to TAG for compartmentation 

### Synthesis of omega-3 LC-PUFA is constrained by acyl exchange
- To create transgenic plants that can produce omega-3 LC-PUFA, the biosynthetic pathway has to be reconstituted in plants 
	- This can be done by engineering genes encoding heterologous enzymes (e.g. from microalgae, diatoms) that can convert endogenous fatty acids into the desired product 
	- Most oilseeds accumulate linoleic or alpha-linoleic fatty acids as products of FAD2/3, and converting these fatty acids into LC-PUFAs requires the action of multiple enzymes that **elongate** and **desaturate**
- However, elongation and desaturation occur in different metabolic pools, and fatty acids have to be **exchanged** between the PC pool and acyl-CoA pool for both to occur (**substrate dichotomy** between desaturation and elongation)
	- Initial attempts at producing LC-PUFA resulted in successful desaturation, but elongation worked poorly. This was because of poor acyl-exchange between the two metabolic pools – non-native fatty acids were **not released from site of synthesis (PC pool)** into acyl-CoA pool for elongation, stalling PUFA biosynthesis at elongation step. 
	- Apart from staying in the PC pool, **intermediates in PUFA biosynthesis were also being shunted to the TAG pool** and other non-useful metabolic pools, sequestering them from enzymatic processing 
		- #experimental_evidence Abbadi et al (2004)

![[Pasted image 20230403181102.png|425]]

### Resolving acyl exchange issue 
#### Use other synthesis pathways 
- LC-PUFAs can be synthesised in two ways by swapping the order in which desaturation and elongation occur 
- Alternative LC-PUFA biosynthesis pathways are found in some algae to bypass substrate dichotomy of desaturases/elongases 
![[Pasted image 20230403183344.png|425]]

#### Alter expression of enzymes that mediate acyl exchange
- KO/KD enzymes involved in diversion of lipids to different pools
	- #experimental_evidence [[NguyenEtAl_2015]] suppressed FatB 16:0 ACP thioesterase to prevent diversion of 16:0 ACP into free fatty acid pool, increasing the concentration of 16:0-ACP substrates for an engineered Δ9-16:0 desaturase 

#### Avoid substrate dichotomy with enzymes that act on the same metabolic pool 
- Use enzymes to use the same substrate type (Acyl-CoA) avoids the need for channeling the lipids into different pools 
- Acyl-CoA desaturases are found in other species (e.g. mammals, *Ostreococcus tauri*, *Borage*) and can be engineered into plants 
![[Pasted image 20230403183538.png|350]]
- #experimental_evidence Sayanova et al (2012) – OtD6 is a Δ6-desaturase that can use acyl-CoA substrate, and it rapidly accumulates stearidonyl-CoA, an intermediate in the PUFA biosynthesis pathway 
- #experimental_evidence Ruiz-Lopez et al (2014) included OtD6 in a complement of enzymes engineered into Camelina, resulting in a high level of accumulation of EPA and DHA in Camelina 

#### Heterologous expression of acyl exchange enzymes 
E.g. from animals, algae, other plants, etc. 
- Flux from PC to TAG pool is a common bottleneck for expression of industrial oils, partly due to lack of acyl exchange enzymes specific to the desired fatty acid 
	- #experimental_evidence Yu et al (2014) co-expressed an *E. coli* cyclopropane synthase with a *Sterculia foetida* lysophosphatidic acid acyltransferase (LPAT), which naturally contains a high level of cyclopropane fatty acids. This resulted in increase in cyclopropane fatty acids in engineered Arabidopsis seeds in TAG pool  ^fcc72f

#### Engineer enzymes 
- Remove ability of enzymes to catalyse the reverse reaction? 

#### Create a new metabolic pool 
- Petrie et al (2012) has attempted to build a pathway for TAG synthesis by creating a MAG metabolic pool 
- In mammals, pancreatic lipase digests dietary fat into 2-MAG and free fatty acids, which are reassembled into TAG by MAG and DAG acyltransferases 
- Tumaney et al (2001) discovered MAG acyltransferase activity in developing peanut cotyledons 
- TAGs could be assembled from MAGs using MAG ad DAG acyltransferases in plants as well 

## Reduce lipid turnover 
- Lipids may be destroyed by lipases, e.g. SUGAR-DEPENDENT1 lipase 
	- #experimental_evidence Kelly et al (2013) found that SUGAR-DEPENDENT1 lipase can limit TAG accumulation in *Arabidopsis* vegetative tissue 
	- KO of lipases could improve lipid accumulation 
- Or, protect of lipids from lipases by upregulating expression of lipid droplet-associated proteins e.g. oleosins, LDAP1, LDAP2 

## Expressing genes in senescent leaves
- Oil accumulation should ideally not affect photosynthesis and plant development, which could reduce biomass yield
- One way to achieve this is to place transgenes under the control of senescence-induced promoters, so that TAG only accumulates in leaves that have reached their maximum size 

## Expression in correct host plant/tissue 
- Common to express in **seeds**, which are storage tissues. If heterologous expression is done in non-storage tissues (e.g. leaf), novel fatty acids are barely detectable 
	- However, if a suitable transcription factor is co-expressed, lipid composition of other tissues could be altered
		- #experimental_evidence Petrie et al (2010) showed that seed-specific genes could be expressed in leaves by co-expressing the WRI1 transcription factor, allowing for ectopic expression of LC-PUFA transgenes from seed-specific promoters in leaves 
- Different plant species may accumulate different levels of desired lipid even if the same synthetic pathway is expressed. 
	- #experimental_evidence Wu et al (2005) – Seed specific expression of LC-PUFA biosynthesis genes in Brassica resulted in higher levels of C20 fatty acids than in tobacco or linseed, reflecting differences in endogenous lipid metabolism 
	- #experimental_evidence Petrie et al (2012, 2014) transfected the same construct for DHA synthesis into *Arabidopsis* and *C. sativa*, but Arabidopsis produced less DHA. 
- Reason could be that endogenous enzymes in different plants have different affinities for non-native substrates 
	- E.g. [[C5 Lipid metabolism in plants#^fcc72f|Yu et al (2014)]] 
- *Camelina sativa* is often used as a model system for lipid metabolic engineering 
	- Hexaploid? Regulatory network more flexible when transgene inserted? 
	- Like *Arabidopsis*, also in Brassicaceae. Genes involved in lipid metabolism are shared with *Arabidopsis*, which has a well-annotated genome
	- Simple to transform with *Agrobacterium*
	- Short life cycle 
	- Oil is rich in polyunsaturated fatty acids (α-linolenic acid, linoleic acid) that can be used in LC-PUFA synthesis 
	- Genome, transcriptome have been studied 
- Why continue to use plants as the host instead of reconstituting biosynthetic pathways in e.g. yeast? 
	- infrastructure for growing plants is well established – scale up is easier -> cheaper 
	- growing plants in field vs algae in steel fermenters
	- carbon source for algae is from plants anyway
	- Scale of agriculture is much larger than algae
	- Algae less established
	- algae have potential for some niche applications, but mostly boils down economics.
	- e.g. DHA currently mostly produced by algae
	- Algae prob better for high value low vol products?
	- plants for low value high vol products
	- algae somewhat out of favour at the moment
	- agriculture always beats fermentation
	- although transgenic algae possible, problem is more difficult to do more traditional genetics – mutagenising and backcrossing. we don't know how to do this backcrossing with algae; the **only** exception is *Chlamydomonas*, and it is really atypical as an algae and is not a great chassis (lmao)
	- Other algae do more interesting things and potentially useful to do genetic improvement on but don't know enough 

## Considerations for choosing a strategy 
- Change in fatty acid composition should have minimal effect on seed germination 
	- E.g. Liu et al (2015) – increased expression of AcTAG did not affect seed germination 
- Accumulation of non native fatty acids may depress total seed oil synthesis
	- #experimental_evidence Bates et al (2014) – expression of FAH12 reduced total amount of fatty acids in seeds
- Minimal effect on crop yield 

# Future challenges for bioengineering 

## Identifying genes involved in lipid synthesis 
- Many enzymes involved in synthesis, modification of fatty acids into **TAGs** have been well characterised
- But we do not understand enough about the genes, assembly of pathways that result in all the different seed oil lipids (apart from TAGs?)
- Could use comparative transcriptomics, analysis of co-expression 

## Assembling complex constructs 
- GoldenBraid 2.0 – modular assembly of transgene casettes 
- CRISPR/Cas9 -> introduce casettes into specific loci easily 

## Engineering better enzymes 
- Structures of enzymes poorly understood, hard to engineer enzymes via rational design 
- [[A9 Protein Engineering (NEW)]] could help? 

# Case studies 
[[NguyenEtAl_2015]]