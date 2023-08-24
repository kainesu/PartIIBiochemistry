#comment These notes should be linked to the Transcription notes. 

# Questions 
- Discuss, with examples, how histone post-translational modifications affect DNA processes such as transcription
- Discuss how post-translational acetylation of lysines within non-histone proteins regulates transcription and other functions of non-histone proteins. 
- Discuss the factors that can affect expression of transgenes in transgenic organisms.
	- One factor to discuss – insertion site within genome 
	- Using examples from cultured cells, transgenic organisms 
	- What features could you include in the design of the construct used to introduce the transgene to increase the likelihood that it is expressed in the right place and at the right time?

# Higher order structure of DNA 
## Nucleosome 
- H3/H4 tetramer binds DNA
- Two (H2A/H2B) dimers bind either side of the tetramer 
	- Each core histone dimer has 6 DNA binding surfaces that organise 3 DNA turns 
- 145bp of DNA wraps around histone octamer to form nucleosome 
- Nucleosome tails contact adjacent nucleosomes 

## Chromatosome
= Core histone octamer + 1 linker histone (H1) + 2 full turns of DNA (168 bp)

- H1 changes the angle of exit and entry of DNA 
- More H1 in more condensed regions of DNA, as H1 makes nucleosomes come closer together 

## Chromatin fibers
- 11nm ("beads on a string") – euchromatin 
	- Contains active genes 
- 30nm – heterochromatin 
	- Inactive 
	- Generally found near centromeres, telomeres

## Loops

^d7b98e

### Why does chromatin form loops? 
![[Pasted image 20221218132303.png]]

- Promoter-enhancer interaction
- Clustering of multiple regions
- Association of distal elements with a shared subnuclear structure (e.g. insulators)
- Promoter-terminator interaction
- Interaction with nuclear periphery 

### Loop extrusion model of loop formation 
Extrusion can occur in one or both directions. This process requires ATP, and cohesin ATPase activity may be involved 
1. Cohesin complex loads onto chromatin, perhaps preferentially at super-enhancers 
   ![[Pasted image 20221218133306.png|200]]
2. Cohesin complex progressively pushes chromatin through its ring-like structure to extend the loop 
   ![[Pasted image 20221218133317.png|200]]
3. This continues until the complex encounters a CTCF molecule positioned in the correct orientation ("convergent sites")
   ![[Pasted image 20221218133335.png|275]]

## Topologically associating domains (TADs) and subTADs
- Regions of genome undergoing high frequency of local interactions
- Separated by borders that preclude interactions between adjacent TADs 
- Occupancy of architectural protein binding sites (APBSs) define TAD borders 
	- TAD borders are enriched with highly occupied APBSs, which are sites containing multiple architectural proteins 
	- Low-occupancy APBSs are enriched inside TADs 
	- Different TADs have strong borders defined by these high occupancy APBSs, probably involving CTCF 
	- Borders insulate one TAD from another, but weaker borders allow for some cross-talk between regions (subTADs)
- Organisation of chromatin into TADs prevents unwanted enhancer-promoter crosstalk 
	- A boundary disruption can occur when a CTCF binding site is mutated, blocked, etc., preventing appropriate looping and resulting in inappropriate interactions between CTCF from different TADs to form one large TAD 
	- #experimental_evidence r in mice, one such rearrangement brings the *Ihh*, *Pax6*, and *Wnt4* genes into the *Epha4* regulatory domain, which causes ectopic expression of these genes in tissues where only *Epha4* is normally expressed 
	![[Pasted image 20221218134414.png|500]]

## A/B compartments 
- The whole genome can be divided into two spatial compartments, "A" and "B", where regions in compartment A tend to interact preferentially with other A compartment-associated regions than B compartment-associated ones 

## Chromosome territories 
![[Pasted image 20221218132850.png]]

## Techniques for determining long-distance interactions between non-contiguous regions of DNA 
### Hi-C
1. Cross-link DNA 
2. Cut DNA with restriction enzymes
3. Fill ends and mark with biotin 
4. Ligate the ends 
5. Purify and shear DNA
6. Pull down biotin 
7. Sequence using paired ends 
![[Pasted image 20221218132437.png|500]]
8. Produce a genome-wide contact matrix 
	1. Sub-matrices show interactions between successively smaller DNA structures 
	2. Intensity = number of reads 
	3. Diagonals correspond to local interactions 

Hi-C used to identify A/B compartments, and then TADs and loops 

# Chromatin structure affects expression levels 
- In vitro, naked DNA + basal TFs + RNA Pol II → accurate and efficient transcription 
- However, in vivo, DNA is compacted into nucleoprotein structures (chromatin) that is highly repressive towards transcription, and needs to be derepressed for efficient transcription 

# Processes that affect chromatin structure 
## Remodelling factors (ATP-dependent)
- Remodelling factors move nucleosomes 
- If the nucleosome is on the promoter, remodelling of chromatin (i.e. shifting of nucleosome position) is needed so that RNA Pol II can access the promoter. 

## Histone modification  
### Histone code hypothesis 
- It is very difficult to be certain of a biological outcome from a particular histone modification, and we have to look at the context of that modification, e.g. other modifications on the same tail and on other tails 

#### Components of histone code 
- Writer: enzyme that introduces a PTM 
- Eraser: enzyme that removes PTM  
- Reader: Binds to post-translationally modified protein 
	- Effector: Reader that recruits other activities within same polypeptide or complex to which it belongs, such as 
		- ATP-dependent remodelling of the chromatin fiber 
		- Stabilisation of higher order chromatin structure 
		- Further PTMs or removal of PTMs 
		- Other gene regulatory effects e.g. recruitment of RNA Pol II machinery 
	- Presenter
		- Reader that binds to a particular sequence of PTMs and presents a side chain of this bound epitope for further modification by writers 
	- Histone modifying enzymes can be recruited by 
		- Transcription factors 
		- Intrinsic specialised domains (e.g. bromodomains) to bind to pre-existing histone marks 
		- Specific forms of RNA Pol II complex (e.g. ScSet1 recruited by CTD S5)
		- Non-coding RNA e.g. HOTAIR ncRNA recruits PRC2 to methylate H3K27 and LSD1 to demethylate H3K4 in Polycomb repressed gene promoters

### Using ChIP-seq to study histone modifications 
- Highest resolution of ChIP-seq is nucleosome (which is fundamental unit of chromatin)  
- Immunoprecipitation for H3K9Ac determines which regions of chromatin are transcriptionally active as K9Ac is linked to gene activity (due to acetylation). It is not an absolute prediction but generally correlates with gene activity 

### Modifications on histone H3 tail 
![[Pasted image 20221217205241.png|700]]

### Histone acetylation and deacetylation at lysines
- Acetylation activates transcription by relaxing chromatin while deacetylation represses transcription by condensing chromatin 
- Acetylation neutralises lysine's positive charge, and provides a binding platform for proteins with specialised domains e.g. bromodomains that activate transcription 
- Acetylases: CBP, P/CAF, GCN5, TAFii250 
- Histone deacetylases (HDACs): HDAC1, 2, 3, 4

### Histone methylation at lysines and arginines 
- Methylation does not affect charge significantly, but methyl groups do create binding sites for proteins with specialised binding domains (e.g. HP1 can bind H3K9me2/3 via chromodomain)
- Lysine can be mono, di, and trimethylated
- Arginine can be mono or dimethylated, and when dimethylated the methylation can be symmetric (on different N atoms) or asymmetric (same N atom)
	- Symmetry of dimethylation matters. Asymmetric mark inhibits K4 methylation, while symmetric mark promotes K4 methylation  ^3915d0
- Histone marks can be both activating (e.g. H3K4me2/3, H3K36me3) or repressive (e.g. H3K9me2/3, H3K27me3)
	- Some specialised cells have both active and repressive marks which allows them to be quickly activated or repressed by removing one kind of mark ("poised" genes) 
		- E.g. ES cells have genes whose promoters have bivalent domains harbouring H3K4me3 and H3K27me3. These poised genes can be rapidly activated or repressed as ES cells differentiated into different lineages and tissues 
- Different histone lysine methylations can also be associated with different transcriptional activities that are localised at different places
	- E.g. scSet1 binds to S5-P of CTD and thus does H3K4me3 at mainly TSS of the gene, while scSet2 binds S2-P of CTD and is associated with elongation, so its modification H3K36me3 is found throughout the transcribing region 
- Enzymes
	- Methyltransferases e.g. SETD2 bound to Pol II adds H3K36me3 to actively transcribed genes, MLL
		- SET domain is common in methyltransferases 
		- Methyltransferases may be found in larger complexes that confer other properties on the methyltransferase e.g. MLL-associated proteins help it to be recruited to the right location on the DNA, regulate its activity, and change what substrate the enzyme recognises 
	- Demethylases e.g. Jumonji family proteins
		- Erasing histone methylations can be done in several ways 
			- Amine oxidation (e.g. LSD1) – mono and dimethyl lysine only
			- Radical attack (e.g. by Jumonji domains) – potentially all methylated forms 
			- Deimination (e.g. PADl4) – arginines, mono-methyl R only. 
				- Produces citrulline rather arginine, so not a true eraser 
		- Similar to methyltransferases, demethylases can be found in larger complexes that determine demethylase specificity 
			- E.g. LSD1 can form a complex with hCo-Rest or hAR. When complexed with hCo-Rest, it target H3K4me (activating), resulting in repression. In complex with hAR, it targets H3K9me (repressive), resulting in activation 
	- Methyl-binding domain proteins e.g. DNMTs with read-write activity recognise repressive histone methyl marks and adds methyl marks to CpG sites 
		- Some readers have cross-talk with DNA methylation machinery e.g. HP1 

![[Pasted image 20221217210109.png|450]]

### Histone prolyl isomerisation 
- Isomerisation allows H3K36 to be presented for methylation, and H3K36me stabilises the trans conformation 
- P38 cis is more common in areas of basal transcription, while P38 trans is more common in areas of activated transcription 

### Histone ubiquitylation/deubiquitylation 
- Occurs at lysines 
- May be activating or repressive depending on specific sites modified 
	- Repressive – prevent acetylation at lysines? 
- Large modification – Ub is 76aa while histones are only ~120aa
- H2A, H2B are monoubiquitinated 
	- H2BK123Ub is activating and leads to H3K4me
		- Deubiquitylation helps to establish appropriate levels of H3K4me
	- H2KA119Ub is repressive and is promoted by H3K27me 

### Histone sumoylation 
- Occurs at lysines
- Generally repressive 
	- Recruits corepressors?
	- Block acetylation? 

### Even more modifications
- Dopaminylation, histaminylation in the brain 

### Effects of histone modifications 
- Directly change compaction e.g. acetylation 
- Indirectly by recruiting other proteins or preventing transcription factors or remodelers from binding to adjacent modifications 

### Cross-talk between histone modifications 
Very complex. 
- E.g. R2 methylation matters whether it is [[B3 Chromatin structure and gene expression#^3915d0|symmetric or asymmetric]]
- E.g. 2B lysine mono-/di-/triubiquitination can affect methylation on another trail 
	- #question for triubiquitinated 2B, how is it not recognised by proteasome degradation pathway 
- E.g. H2BK123Ub → H3K4me 
![[Pasted image 20221218162414.png|500]]

## Heterochromatin formation 
![[Pasted image 20221217214834.png]]

- HP1 interacts with Suv3-9, a K9 methyltransferase, which methylates other K9 which in turn recruit more HP1, resulting in spread of heterochromatin 
- Heterochromatin spreads unless it is prevented from doing so 

### Integration with metabolic information 
- Many HATs use acetyl-CoA for acetylation, as well as propionyl-CoA and butyryl Co-A to butyrylate or propionylate lysines in histones 

## Facilitators of elongation 
### FACT (FAcilitator of Chromatin Transcription)
- FACT allows Pol II to progress through nucleosomes 
- Destabilises H2A:H2B dimers to allow Pol II to progress past, then reforms the dimers 

### Approach for identifying FACT (FAcilitator of Chromatin Transcription)
1. Assemble chromatin on promoter template *in vitro* with GAL4 sites 
2. Add GAL4 activator and allow ATP-dependent remodelling 
3. Purify the remodelled template via gel filtration 
4. Add back an *in vitro* transcription system (purified components or nuclear extract) and check for (i) initiation and (ii) elongation 
	1. Initiation is checked by only adding the first two nucleotides so that only the firsts phosphodiester bond is formed, and one nucleotide is radiolabelled so that the product can be visualise on a gel via autoradiography 

#### Results 
- In the chromatin template, initiation was not possible in the absence of GAL4
- Purified IVT system could initiate on chromatin template but Pol II stalls at positions up to 50 nt into the template, which could be overcome by FACT, which is present in the nuclear extract ⇒ remodelled nucleosome was moved downstream of the promoter, and FACT facilitates the passage of RNA Pol II through nucleosomes for elongation 
	- Subsequent depletion and add back experiments showed that the FACT complex is responsible 

## lncRNAs
### In *cis*
- **Displacement**: Transcription *in cis* can displace DNA-bound factors that inhibit or activate transcription of a neighbouring gene 
- **Tethering**: Nascent ncRNA transcripts can tether chromatin-modifying complexes and/or transcriptional regulators to activate or repress genes
	- **Recruitment of chromatin-modifying complexes.** E.g. Study in larval imaginal discs suggests that *bxd* lncRNAs tether a histone methyltransferase to the *Ubx* promoter to induce its expression 
	- **Recruitment of transcriptional regulators.** E.g. in imprinting, parental-specific expression of lncRNAs is controlled by inheritance of differentially methylated DNA sequences, i.e. imprinting control regions (ICRs). Unmethylated ICR enables expression of nearby lncRNA, which silences selected neighbouring genes *in cis*. ([[PauliEtAl_2011]])
		- "In mice, paternal-allelic expression of two lncRNAs, *Airn* and *Kcnq1ot1* is essential for silencing of some neighbouring paternal genes" 
		![[Pasted image 20221218152929.png|500]]

### In *trans*
- **Binding platforms**: Trans-acting ncRNAs can serve as platforms for assembly of protein complexes, with target sites specified by DNA-binding proteins 
- **Guide**: Specify target sites for chromatin modifiers and transcriptional regulators by hybridising with complementary DNA sequences 
- **Modulation of protein complex activity** by inducing conformational changes 
	- E.g. HOTAIR ncRNA interacts with a binding pocket in coREST and also recruits PRC2 to occupy and repress HOXD and several other loci
	![[Pasted image 20221218153120.png|475]]

### ChIRP for identifying ncRNA interactions 
- ChIRP = chromatin isolation by RNA purification 
- Can be used to identify 
	- genomic sites bound by ncRNAs 
	- Proteins and modifications bound by ncRNAs 

1. Cross-link RNA-protein-DNA complexes (via UV?)
2. Sonicate to fragment DNA 
3. Hybridise ncRNA of interest to biotinylated tiling oligonucleotides 
4. Pull down RNA (with associated complex) using streptavidin beads 
5. Separate lncRNA, genomic DNA, and RNA-binding proteins for further analysis
	1. Nucleic acids – qRT-PCR, high throughput sequencing 
	2. Proteins – Western blot, mass spec 

- RNA modifications have been mapped to specific sites on mRNAs, tRNAs 
- Function is unknown for most, but a few are known 
- E.g. m<sup>6</sup>A modification by METTL3/METTL14 recruits m<sup>6</sup>A-binding proteins which results in multiple effects, including modifying chromatin structure 

### Interactions between epigenome and epitranscriptome 
- Although heterochromatin is highly repressed, there is still some window for transcription. RNA transcribed from heterochromatin is important to setting up chromatin, feedback onto heterochromatin, allowing Suv3 and HP1 to operate properly 
- M6A methylation of RNAs is also required for feedback on heterochromatin 
	- Endogenous retroviral RNAs are also m6A modified and take part in maintaining heterochromatin with K9 methylation 
	- E.g. m6A methylation of XIST promotes X chromosome silence – the m6A mark is recognised by a reader which effects silencing of X chromosome 
- TFs can recruit RNA modifying enzymes 
	- E.g. In TGFβ signalling, SMAD2/3 transcription factor can recruit METTL3/14-WTAP, which then does m6A methylation 
- Some histone marks can also recruit RNA modifying enzymes 
	- E.g. H3K36me3 on gene body recruiting METTL14 

## RNAi 
- RNAi can also mediate the formation of centromeric heterochromatin in *S. pombe*
- There is a window of opportunity after replication where there is bidirectional replication of repeat DNA in centromeric region. The dsDNA products are used to generate short siRNAs which are loaded onto RISC (Ago-Tas3-Chp1) 
- RISC targets nascent RNA transcripts to recruit RNA-directed RNA polymerase complex (RDRC) and Clr4 
- Clr4 methylates H3K9 which recruits Swi6, the HP1 homolog in yeast. It recognises H3K9me2/3 which recruits Clr4 to methylate more H3K9, resulting in heterochromatin spreading at the centromere 

![[Pasted image 20221218144651.png|500]]

## Liquid-liquid phase separation 
- Factors have different diffusion kinetics between different phases, such that some factors can be trapped in droplets while other factors cannot diffuse into the droplet, resulting in compartmentalisation 
- Droplets can be created by self-associating chromatin binders
![[Pasted image 20221218144913.png|450]]

# Factors affecting transgene expression / long-range regulation of gene transcription 
## Insertional effects 
- A transgene can be introduced into an organism via pronuclear injection of the DNA into oocytes, which results in homologous recombination among injected molecules at random chromosome insertion sites 
	- While there are more sophisticated techniques to generate transgenic organisms now, this basic method allows researchers to investigate how host genome can affect randomly integrated transgenes 
- When the DNA integrates, it forms head to tail arrays consisting of variable numbers of genes inserted into the host genome 
- However, integration can affect the host genome by causing duplications, rearrangements, deletions, translocations at the insertion site 

## Position effects 
- The particular location the gene is inserted in the genome can affect expression of the gene 
- The gene could be inserted near an enhancer, silencer, or a region of DNA methylation (repressive)
- The gene could also be inserted into or near heterochromatin, which results in **position-effect variegation** whereby the gene is inactivated in some cells but not others, as the heterochromatin may or may not spread to the gene and inactivate it 

### Enhancers 
- Enhancers are distinct genomic sequences that contain binding sites for TFs, chromatin modifiers (e.g. HAT p300) and that upregulate transcription of a target gene from its TSS 
- They are orientation independent, can be upstream/downstream of the gene, and can be proximal/distal, or even found within introns 
- **Topology effects**. However, they have to be on the same loop of DNA to act on a promoter. Loops are held together by cohesin, and any enhancer brought into the same loop as the gene can act on it. This can modify enhancer activity for different tissues for differential expression 
	- #comment Need to add this to Transcription notes as well... 
- Enhancers are typically devoid of nucleosomes, but the flanking nucleosomes have specific marks e.g. H3K4me1, H3K27ac
- May produce enhancer RNAs (eRNAs) which are lncRNAs. Unclear how they work but may contact the Mediator complex to stabilise the transcription complex
	- #comment Need to do more research on how Mediator complex works. 
- May be subject to position-effect variegation, as heterochromatin can also encroach on the enhancer to result in basal transcription. Enhancers offer no protection to heterochromatin spreading. 
- "Typical" enhancers drive expression of housekeeping genes, while "super enhancers" specify expression of cell type identity genes (see [[B1 Transcription#Super enhancers]])
	- Super enhancers have very high levels of H3K4me1, H3K27ac and BRD4 (bromodomain protein)
		- BRD4 is critical for most super enhancers – for some leukaemia, treatment with the BRD4 inhibitor I-BET prevents it from binding to acetyl lysines to inactivate super enhancers, thus switching off genes and preventing leukemia cells from proliferating (Nicodeme et al, 2010)
	- Super enhancers can also be commissioned and decommissioned 
		- E.g. Endothelial cells can exist in a basal or stimulated state, and basal cells become stimulated if treated with TNFα. Upon streatment with TNFα, there is a redistribution of BRD4 from SEs required for the basal state to SEs required for the stimulated state, so basal SEs become decommissioned while stimulated SEs are commissioned. This redistribution is dependent on NF-κB, but its mechanism is unclear 

### Silencers
Very similar properties to enhancers except they are repressive
- Orientation/position independent 
- Subject to position effect variegation – heterochromatin encroachment results in gene expression upregulation 
- E.g. human thyrotropin B gene has an upstream silencer that binds to Oct1, a silencing factor. In non-thyrotrop cells, Oct1 silences the gene, while in thyrotrop cells, an enhancer overcomes the activity of the silencer 

### Locus control regions 
- An LCR is a long-range cis-regulatory element containing hypersensitive (HS) sites that enhances the expression of genes at distal chromatin sites 
	- Different LCRs have different numbers and spatial arrangements of HS sites, but each HS site contains the same set of transcription factor binding sites ([[Udvardy_1999]]) 
- E.g. required for normal expression of mouse β globin, human CD2 gene, mouse *tyrosine* gene

#### Properties of locus control regions 
- Transcriptional enhancer activity that may be tissue specific depending on the LCR and promoter it interacts with  
	- E.g. in β-globin LCR, enhancer activity resides in 5' HS2-4, which contain binding sites for ubiquitous and erythroid-specific trans factors 
	- Can affect basic transcription machinery directly – e.g. RNA Pol II associates with β-globin LCR  
- Confers position-independent, copy number-dependent expression on a linked gene 
	- Ability to confer this property distinguishes an enhancer from an LCR 
	- Copy-number dependent expression is indicative of open chromatin structure 
	- Protect against position effect variegation
		- #experimental_evidence Festenstein et al (1996) integrated hCD2 with intact LCR into thymocytes and compared with hCD2 with deleted HS3. Thymocytes with intact LCR all expressed hCD2, while those with deleted HS3 exhibited position effect variegation (as determined by FACS analysis). hCD2 from thymocytes in the "expressed" population were sensitive to DNase, suggesting an accessibly chromatin structure, while hCD2 from the "silenced" population were DNAse resistant, suggesting DNA condensation 
![[Pasted image 20221217235054.png|550]]

#### Mechanisms for function of LCR 
- **Looping**: 5' and 3' HS sites bind to the architectural factor CTCF which works with cohesin to form a loop that loops the gene away from heterochromatin 
	- #experimental_evidence Tolhuis et al (2002) showed that the HS sites of the β-globin LCR come into close spatial proximity with the genes using 3C, and the intervening chromatin with inactive globin genes loops out 
	- The loop is hyperacetylated and has histone marks for transcriptional competence (i.e. acetylation, di-/trimethylation of H3K4)

### Boundary elements/insulators 
- Insulators do not kill enhancer activity – enhancers can still affect other genes outside the influence of the insulator, indicating that insulators do not propagate the formation of a repressive chromatin structure 

#### Models of insulation 
- **Insulate genes from position effects** (so can protect from encroachment of heterochromatin as well)
- **Insulate genes from enhancers**, preventing effects on basal activity
	- e.g. *Fab-7* DNA element in *Drosophila* embryos (Zhou et al 1996)
		- H1 is an enhancer that acts on the anterior region of embryos, while IAB5 is an enhancer that acts on the posterior 
		- When the *Fab-7* element is inserted in the construct below, it blocks each enhancer from upregulating the expression of the gene behind the insulator, thus affecting where it is expressed in the embryo. 
		- Thus, a DNA sequence can be tested for insulation effects by inserting it between two enhancers 
		![[Pasted image 20221218131826.png|500]]

**Mechanisms for enhancer insulation** 
- **Blocking**: Physical blocking of enhancer-bound activators and promoter 
	- e.g. ICR at imprinted regions 
		- At imprinted genes, CTCF is involved in enhancer blocking. Imprinted genes are genes with allele-specific expression depending on the parental origin of the chromosome. In maternal chromosome, the imprinting control region (ICR) is not methylated, allowing CTCF to bind to the ICR and thus preventing the enhancer from acting on H19.
		- In paternally inherited chromosomes, DNA has undergone spermatogenesis and  the ICR and promoter of H19 is methylated, preventing CTCT from binding to the ICR and allowing the enhancer to act on Igf2. On the other hand, methylation of H19 promoter switches its expression off. 
		- It is uncertain whether this model applies to other sites with boundary elements as well 
	![[Pasted image 20221217235859.png|500]]
- **Looping**: The insulator loops out a region of DNA to remove it from the control of an enhancer on another loop 
  ![[Pasted image 20221218132214.png|500]]
	- See [[B3 Chromatin structure and gene expression#^d7b98e|Loops]]
- **Tracking**: Transcription factors bound to enhancer elements track along DNA in search of target promoters; insulator-bound sequence specific DNA-binding proteins block TFs from reaching target promoter during tracking 
- **Decoy**: The insulator resembles a promoter to attract activator proteins assembled on enhancer into a non-productive interaction 

Current data is insufficient to allow unambiguous distinction between models (Udvardy 1999) 
- #comment This may have changed by now. 

![[Pasted image 20221218145932.png|350]]

# Effect of acetylation of non-histone proteins on DNA processes
- Phosphorylation of many non-histone proteins can achieve similar effects. 
- Many HATs also acetylate non-histone substrates, e.g. CBP/p300, P/CAF

## Regulation of DNA binding 
### Stimulation of DNA binding 
E.g. by p53
- p53 is acetylated by TIP60, CBP/p300 and P/CAF at multiple sites
- In each case, p53 site-specific DNA binding activity is enhanced 
	- #experimental_evidence Liu et al (1999) showed using deletion analysis that the minimum p53 domain that is acetylated is position 300-369. Then showed using EMSA that acetylated p53 has enhanced DNA binding activity 

### Inhibition of DNA binding 
E.g. HMG-I/Y 
- Acetylated by CBP/p300 and by P/CAF 
- CBP/p300 and P/CAF HAT activity required for efficient IFN-β gene induction 
	- HMG-I/Y is the DNA binding component required for enhanceosome assembly at the  IFN-β promoter, which is a gene induced by viral infection 
	- It nucleates enhanceosome formation 
- Only CBP/p300 activity required for post-viral shut off of the gene 
	- Acetylation of HMG-I/Y by CBP/p300 causes HMG-I/Y to dissociate from the enhanceosome to disrupt enhanceosome 

![[Pasted image 20221218163740.png|500]]

## Regulation of transactivation 
Transactivation is a protein-protein interaction 

### Stimulation 
E.g. EKLF 
- EKLF is a red cell specific transcription factor that activates the β-globin promoter and can also repress other genes
- Acetylated by CBP/p300 at K288 and K302 
- Acetylation at K288 promotes interaction with SWI/SNF complex, leading to activation 
- Acetylation at K302 promoters interaction with Sin3A/HDAC1 repressor complex, leading to repression 

### Repression 
E.g. TCF
- TCF is a HMG domain transcription factor 
- CBP-mediated acetylation of TCF inhibits TCF binding to coactivator, beta-catenin, which prevents activation of TCF by Wnt/Wingless signalling 
![[Pasted image 20221218164056.png|500]]

## Regulation of localisation 
E.g. P/CAF 
- P/CAF is a HAT and coactivator of numerous genes 
- P/CAF is autoacetylated at region 352-658, which contains a nuclear localisation sequence 
- P/CAF is hyperacetylated and excluded from the nucleus of differentiated myoblasts (i.e. myotubes), suggesting P/CAF acetylation regulates nuclear localisation? 
	- Further experiments – Acetylated vs deacetylated P/CAF NLS fused to GFP 

## Regulation of protein stability 
E.g. E2F-1 
- E2F-1 is a TF that stimulates expression of S-phase inducing genes 
- In early G1 phase, E2F-1 activity is repressed by binding to Retinoblastoma protein, Rb, but as cells approach S phase, Rb dissociates from E2F-1 which allows CBP/p300 and P/CAF to acetylate E2F-1, which stimulates E2F-1 DNA binding and stabilises the protein 
- E2F then recruits HATs to activate transcription 

## Protein interactions with acetyl groups 
### BRD4 
- Some TFs (e.g. Twist) mimic histone sequences that can be acetylated, and these acetyl groups recruit bromodomain proteins e.g. BRD4 
	- Example of "molecular mimicry" – Twist is acetylated by Tip60, which cannot distinguish between histone and Twist 

