  # Background 
- β-mannan is a major class of hemicelluloses in plant cell walls 
	- Hemicelluloses are a type of heteropolymers found in terrestrial plant cell walls. They are composed of many sugars. 
	- β-mannans are polysaccharides with repeating units of mannose, with galactose or glucose, or both, attached to a β-mannan backbone. 
	- Glucomannan is when some of the mannan in the backbone is replaced by glucose. 
	- The sugars in β-mannan may also be acetylated. 
	- Here are some variants of β-mannan: 
	  ![[Pasted image 20221220214839.png|600]
- β-mannan structures have changed throughout plant evolution. There is an overall trend of increasing complexity from homomannan in algae to AcGGM in bryophytes and gymnosperms, to β-GGM in angiosperms. 
  ![[Pasted image 20221220215151.png|625]]
  - Mannan α-galactosyltransferase (MAGT), is the enzyme that catalyses <u>galactosylation</u> of <u>mannan residues</u> on <u>glucomannan backbones</u>, to form <u>galactoglucomannan</u>. It can be found in some eudicots, gymnosperms, and monocots. 
![[Pasted image 20221220215341.png|500]]
- However, backbone recognition differs across plant species. MAGT in different species may recognise related backbones, not necessarily just glucomannan backbones, for example: 
  ![[Pasted image 20221220215653.png|475]]
  - MAGT also has homology to the enzyme Xyloglucan Xylosyltransferase (XXT), which is an enzyme that catalyses the xylosylation of glucose backbones to form xyloglucan. MAGT and XXT are considered to be GT34 enzymes. XXT can generally be found in monocots, some pteridophytes, and eudicots. 
    ![[Pasted image 20221220220116.png|525]]
- Bryophytes also have a GT34 enzyme, but **it is not classified into MAGT or XXT subclades despite the presence of XyG and possibly Gal on AcGGM**. 
	- Possibly, bryophytes have an ancestral GT34 that has dual activity on XyG and AcGGM
- GT34 is a single pass membrane protein, has TMD – found in Golgi Apparatus (https://www.uniprot.org/uniprotkb/Q7X9N4/entry)

# Research questions  
- What is the MAGT (and XXT) responsible for mannan galactosylation in lower land plants? 
	- Lower land plants = Bryophytes? 
	- Selection of candidates? 
	- Bioinformatics + biochemistry approach 
	- Enzyme identification. What are approaches taken for other biological questions? 
- Do ancestral GT34s have dual activity on β-mannan and XyG? 
	- Ancestral GT34 = GT34 in lower land plants? 
	- Test for dual activity by incubating with β-mannan and XyG (which kind of XyG?)
	- If it has dual activity, what are the implications for structure? 
		- Has to be able to accommodate both backbones 
		- Must be able to accommodate both galactose and xylose for the transfer reaction 
	- I predict that the rate of enzymatic activity will be lower for ancestral GT34 than for the specialised enzymes, if it is truly dual activity. 
	- What parts of beta-mannan, XyG, and ancestral GT34 are conserved? 
- What kind of β-mannan does the ancestral GT34 act on? 
	- There are many kinds of β-mannan, how to determine what the cognate substrate is? For other enzymes the cognate substrate can be determined because there is a natural in vivo substrate 
		- What β-mannans are present in lower plants? Are there any global omics methods for sugars 
	- If we are doing a combinatorial approach, what is the most efficient way to test. i.e. what is the least number of β-mannan variants we need to test to conclusively determine what the substrate is. Although there could be multiple substrates? Tbh, enzyme activity is often promiscuous. 
	- What about finding a consensus structure? If we test on different backbones, maybe we could create a logo diagram. 
	- Could we do some kind of proximity labeling / cross-linking ... lmao but idk how that would work for polysaccharides? 
	- If we test multiple substrates, the one that results in fastest enzymatic activity is probably the right substrate 

# Method 
1. Identify ancestral GT34 candidates via bioinformatics 
	1. Dicot plaza 5.0 
	2. How to choose candidates?
		1. Compare conserved active site sequence? 
		2. Compare structural homology (if available?)
		3. I think it might just be what is available in the lab but can check 
2. Express ancestral GT34 candidates in tobacco leaves and purify 
	1. Goldengate cloning of sequences into expression constructs (done)
	2. Express in tobacco leaves using *Agrobacterium* 
	3. Purification – GT34 is a membrane protein 
		1. Microsomes? 
		2. Nanodiscs? (e.g. https://pubs.acs.org/doi/10.1021/acssynbio.2c00366) 
3. Purify different β-mannan backbones (pine de-acetylated glucomannan, pine acetylated glucomannan, patterned glucomannan, pure mannan, cellohexaose, mannohexaose)
	1. AIR = Alcohol Insoluble residue. Obtained by washing plant extract with ethanol and air-drying the pellet. Pellet obtained = AIR. [[YuEtAl_2022]]
	2. Incubate with alkali to solubilise and deacetylate hemicelluloses [[YuEtAl_2022]]
4. Test the activity of each GT34 candidate with different β-mannan backbones via an *in vitro* assay 
	1. Q: Test for activity on β-mannan
	2. Q: Identify the type of β-mannan that the ancestral GT34 candidates act on
		2. What if ancestral GT34 does not work with ANY of the backbones
		3. Could we test ancestral land plant glucomannan (AcGGM?)→ pine may be similar 
	3. In vitro assay: enzyme is incubated with β-mannan backbone. If it galactosylates the backbone, then upon digestion with CjMan26A followed by β-Glcase/β-Mannase, it will produce a particular oligosaccharide. If it does not galactosylate the backbone, then it will produce monosaccharides as Man26A does not tolerate substitution of Man by Gal. These two results can be differentiated by [[Polysaccharide analysis by carbohydrate gel electrophoresis (PACE)|PACE]]. 
		1. Ratio between oligos to monosaccharides = extent of activity? 
		2. CjMan26A = Cellvibrio japonicus β-mannanase 26A. Endo-β-1,4-mannananses 
		3. Control: β-mannan backbone not incubated with MAGT1, UDP-Gal that is also digested by Man26A OR reaction stopped by heating at 100°C for 10min 
		4. To validate whether it is indeed the action of MAGT1, apply α-galactosidase to recapitulate the bands in the control 
		5. β-Glcase hydrolyses glucose monomers linked by β-glycosidic bonds, while β-mannase hydrolyses which degrades mannan linked by β-glycosidic bonds 
		6. β-mannanase 26A (Man26A) is specific to Man at -1 subsite but can tolerate Glc at +1 subsite and hence can cleave β-Man-(1,4)-β-Glc but not β-Glc-(1,4)-β-Man. Substitution of Man at -1 subsite by Gal or acetate is not tolerated [[YuEtAl_2018a]]
5. Test activity of GT34 candidates with XyG 
	1. Q: Test for activity with XyG 

Other possible questions that could be tested? 
- Mechanistic – how does the ancestral GT34 galactosylate the substrate (e.g. at specific residues like every 4th residue?)
	- Is it possible to tell from PACE... 
- Evolutionarily – what changes in sequence are responsible for differences in activity between ancestral GT34 and "modern" GT34s? 
	- Mutagenesis studies – SDM on the DNA constructs? 
	- Speculation on why specialisation occurred in "higher" plants 
- Enzyme kinetics 
	- Time course using PACE assay 
	- How to quench reaction? 

# Summary 

| Question                                                               | Data                                                                           |  |
| ---------------------------------------------------------------------- | ------------------------------------------------------------------------------ | 
| What is the MAGT responsible for galactosylation in lower land plants? | Galactosylation activity of different GT34 candidates on glucomannan backbones | 
| Does ancestral GT34 have dual MAGT and XXT activity?                   | Xylosylation activity on glucose backbones                                     |
| What kind of beta mannan does ancestral GT34 galactosylate?            | Compare galactosylation activity on different glucomannan backbones            |  

- The data from the in vitro assays will probably be presented as bar graphs. 
- Backbone → logo diagram? 