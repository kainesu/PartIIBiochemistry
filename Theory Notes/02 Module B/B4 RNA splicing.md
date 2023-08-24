# Learning outcomes and questions
* Tissue-specific AS
    * ==How is neuron-specific inclusion of alternative exons in mRNA achieved?==
    * What progress has been made towards deciphering tissue-specific “alternative splicing codes”? 
    * *==Discuss the insights into the regulation of tissue-specific alternative splicing that have been enabled by techniques that allow global profiling of alternative splicing events.==*
* Functional consequences of AS 
    * ==*Using mass spectrometry-based proteomics data some investigators have suggested that alternative pre-mRNA splicing plays a marginal role in generating proteomic diversity. What arguments support or oppose the biological importance of alternative splicing?*==
    * *==Discuss the functional importance of properly regulated alternative pre-mRNA splicing==*
	    * There could be an argument that improper regulation could be substrate for evolution... so in the evolutionary timeline, perfect regulation would not be good 
* Deciphering splicing codes 
    * How have _in silico_ (computational) approaches contributed to our understanding of pre-mRNA splicing and its regulation?
    * ==How well do computationally assembled tissue-specific “splicing codes” agree with experimental analyses of individual tissue-specific regulated alternative splicing events?==
    * Discuss the advantages and disadvantages of computational and experimental genome-wide approaches for identifying cis-acting elements involved in splicing regulation.
* Mechanisms of splice site regulation 
    * Discuss the insights into the mechanisms of regulated alternative pre-mRNA splicing that have been afforded by investigations of the genetic pathways that regulate sex-determination in Drosophila melanogaster.
    * Proteins with arginine-serine rich domains (RS domains) that regulate splicing function as splicing activators while RNA binding proteins without RS domains function as repressors. Discuss.
    * *==Which mechanisms determine the assembly of splicing complexes at regulated splice sites?==*
	    * Information deficit 
    * How have exon-splicing enhancers (ESEs) been identified and what are their mechanisms of action?
* Splicing in mammals vs yeast
    * Mammalian genes typically contain multiple introns that can be thousands of nucleotides in length, while in Saccharomyces cerevisiae genes have at most one short intron. Yet the information content of consensus splice sites is higher in S. cerevisiae than in humans. Discuss.
    * In mammals typical protein coding genes contain introns whereas in yeast they do not. For both mammals and yeast, how are atypical mRNAs accommodated by the nuclear export machinery?
    * *==Discuss the evidence that helped to address the problem of the “information deficit” in mammalian consensus splice site sequences==* 

# Pre-mRNA splicing 
Some mammalian genes lack introns (e.g. heat shock protein, interferon genes) 

## Experimental evidence for splicing
1. Hybridise mRNA to corresponding ds DNA fragment under conditions that favour DNA-RNA interactions over DNA-DNA annealing
2. Hybridised mRNA displaces one strand of DNA, forming a loop of single stranded DNA (R loop)  ![[Pasted image 20221218211958.png]]
3. Visualise nucleic acids via microscopy 
   Result: In adenovirus DNA, mRNA had “tails” protruding on both ends 
* 3’ end explained by poly(A) tail 
* 5’ tail – R loops? 

4. When mRNA in R loops was incubated with DNA fragment from a separated (non-contiguous) part of the virus genome, it could anneal ⇒ mRNA is a composite of fragments complementary to separate regions 

## Structure of exon-intron boundaries
* Introns mostly start with GU and end with AG (GU/AG rule)
* 5’ splice site (donor site) at exon-intron boundary 5’ of intron 
    * Consensus sequence is (C/A)AG|**GU**RAGU
* Branch point consensus – contains conserved adenine, found closely upstream of 3’ splice site (18-40 nt upstream)
* Polypyrimidine tract – pyrimidine rich, 18-40nt, downstream of branch point 
* 3’ splice site (acceptor site) at 3’ exon-intron boundary 
    * Consensus sequence is Y**AG **(Y = Pyrimidine) 
* Minimal distance between splice sites (~70nt) required for productive binding of splicing factors 

## Trans factors 
* Small nuclear ribonucleoprotein (snRNP) particles 
    * Small  nuclear RNA associated with several proteins 
    * RNA component base pairs with substrate 
    * snRNAs U1, 2, 4-6 – splicing
        * U1 – base pairs with 5’ splice site
        * U2 – base pairs with branch point 
* U2AF (U2 snRNP Auxiliary Factor) – U2AF65 binds to polypyrimidine tract, U2AF35 binds to AG in the 3’ splice site 
![[Pasted image 20221218212026.png]]

## Experimental evidence of interactions between splicing cis elements and trans factors
* Removal of 1st eight nucleotides of U1 snRNA blocks splicing 
* Complementary mutations in U1 snRNA and U2 snRNA can reverse some mutations in 5’ splice site not in highly conserved GU or branch point A respectively ⇒ U1 snRNA and U2 snRNA base pair to their respective sites 
* Antibodies against U1 snRNP block splicing 
* Removing U snRNPs from nuclear extracts inactivate their splicing ability 

## Experimental determination of splice sites 
1. Synthesise radiolabelled splicing substrate via _in vitro _ transcription 
    1. Clone gene fragment into plasmid vector with T7 promoter on 5’ side and unique RE sites on 3’ side 
    2. Cut plasmid with RE to linearise 
    3. Transcribe with T7 RNA Pol, NTPs, radiolabeled UTP 
2. Incubate radiolabeled RNA with nuclear extracts (e.g. from HeLa, yeast) and ATP 
3. Take samples at various times 
4. Remove proteins and analyse RNA via denaturing electrophoresis and autoradiography 
	1. Treat RNA with debranching enzymes to hydrolyse 2’-5’ bonds in circular lariat intermediates – converts intermediate to linear RNA so that can migration rate can be compared with other linear intermediates 
	   ![[Pasted image 20221218212103.png|475]]

## Process of splicing 
### Spliceosome assembly 
![[Pasted image 20221218212115.png|500]]
All steps except E complex involve ATP hydrolysis by the RNA helicases 
1. H complex: hnRNP proteins – ATP and splice-site independent 
    1. Binding of hnRNP proteins indicates that the pre-mRNA has not been fully processed yet and is not ready for export to the cytoplasm 
2. E complex: U1 recognises 5’ splice site, U2AF recognises polypyrimidine tract and 3’ splice site	
    2. Commitment step for splicing 
        1. Evidence: When excess unlabelled competitor RNA was added to pre-assembled E-complex which contained labelled RNA, it did not prevent splicing upon ATP addition 
3. A complex: U2 recognises branch point sequence via base pairing with U2 snRNA 
4. B complex: U4/6, 5 recognises A complex. Pre-catalytic
    3. All assembly steps until B complex are reversible, and become irreversible after U4 snRNA leaves the complex ⇒ regulation can only occur up to B-complex  
	    1. #question but if E complex is reversible, how can it be a commitment point...? 
5. B*, C, and C* complexes
6. Catalytic spliceosome: U4:U6 base pairing broken, U1 displaced from 5’ splice site, U6 base pairs with 5’ splice site and with U2 
    4. RNA rearrangement positions substrate pre-mRNA for catalysis (see figure below) 
    5. U2 and U6 form catalytic core 
    6. Some protein splicing factors catalyse RNA conformational changes and rearrangement 

![[Pasted image 20221218212130.png]]

![[Pasted image 20221218212155.png]]

### Splicing reactions 
Two transesterification reactions occur: 
1. In “B*” complex: 2’OH group of A in branch site attacks phosphate on 5’ end of intron to release 5’ exon and form a lariat
    1. 5’ end of intron and A in branch site become linked via 2’-5’ bond
2. In “C*” complex: 3’ OH group of 5’ exon attacks phosphate at 3’ end of intron → exons are now ligated and intron is released in the form of a lariat 
3. Debranch lariat 
4. Linear intron is degraded 
5. The spliced mRNA has an exon junction complex (EJC) deposited ~25nt upstream of the splice junction, which can be involved in downstream steps of gene expression 

No ATP is consumed during this reaction. 

The number of phosphodiester bonds is conserved. 

![[Pasted image 20221218212216.png|300]]

## Are exons or introns the functional unit for splicing? 
* Exon definition: The pair of splice sites across an exon are recognised by the spliceosome first 
    * Note that even with the exon definition, the splice sites across an intron still have to be recognised eventually as that is what will be spliced out 
* Intron definition: The pair of splice sites across an intron are recognised by the spliceosome first 
* The exon definition occurs when the flanking introns are long, while the intron definition occurs when the introns are short (depends on the “architecture” of the gene) 
    * In humans exon definition dominates, but in some species intron definition dominates 
* Evidence for exon definition 
    * Berget group – When the 5’ splice site of an exon is mutated the exon is skipped  
      ![[Pasted image 20221218212232.png|500]]
        * Even though splice site of intron was mutated, the intron was still spliced out 
    * Berget group – when the exon is expanded, the exon is skipped even though neither splice site on the exon was altered 
        * Despite introns still being wild type, their splicing was altered. 
    * #experimental_evidence Grabowski et al 1992 – Mutating the 5’ splice site of a cassette exon in preprotachykinin gene to a consensus sequence makes the exon constitutive, and in nuclear extract, this increased the binding of U2AF<sup>65</sup> binding to the polypyrimidine tract
      ![[Pasted image 20221218212255.png|425]]
        * Supports exon definition – PPT and 5’ splice site flank the exon 
        * However, when purified U1 snRNP (binds to 5’ SS) was added to purified U2AF + exon, there was no increased binding of U2AF ⇒ the factors interact indirectly via other factors i.e. SR proteins 
        * This suggests that in the exon definition, stabilising interactions across the exon between factors bound at the 5’ and 3’ splice sites precedes subsequent formation of cross-intron complexes
    * Most exons are only 50-300 nt long 
        * This is consistent with the threshold Berget group found – when exon was expanded beyond 300nt, there was exon skipping. The exon could not be recognised by spliceosome complex components 
    * Splicing phenotypes of most genetic diseases are consistent with the exon definition (i.e. exon skipping, activation of a cryptic splice site, creation of pseudo exon) rather than intron definition (i.e. intron retention) 
        * Splice site mutations results in changes to exon rather than intron  
* Reason for 300 nt threshold? May be due to competition with general repressive packaging into hnRNP particles
	* #question what does this mean??? 
* After initial binding of spliceosome components across exon splice sites, there then has to be a way for the exon definition complexes to be exchanged for cross-intron complexes for splicing to occur – converting exon definition to intron definition (i.e. exon juxtaposition) 
    * Unclear how this occurs as it is difficult to analyse biochemically. Don't have a good way of bringing exon definition complexes together 
	    * Trans splicing might be a way to investigate this, but it is inefficient because the intron/exon are not tethered to each other anymore 
    * However, exon juxtaposition would represent another potential point for regulating the splice site
      ![[Pasted image 20221218212307.png|425]]

## Splice site recognition 
### Splice site specificity problem 
* The spliceosome has to be able to recognise specific splice sites for correct splicing 
* This can be challenging in some genes because 
    * Mammalian introns can be long 
    * A single gene may have many introns (e.g. myosin heavy chain genes) 
    * Alternative splicing means that some splice sites are not recognised constitutively 
    * Introns can have numerous pseudo-exons, which are sequences flanked by apparent consensus 3’ and 5’ splice sites, and yet are not included in the mature mRNA, which poses the question of how these pseudo-exons are differentiated from real exons by the spliceosome 
* While yeast splice sites have sufficient information to unambiguously specify authentic sites, metazoan splice site sequences are degenerate and are poorly conserved – in fact, the information content of human splice sites is insufficient and is much less than in yeast, despite humans having larger splice sites and longer introns 
    * In humans, a reasonable match to the 5’ splice site occurs every 290 nucleotides, while 3’ ss/PPT every 450 nt 

### Cells can pair the correct splice sites via different mechanisms 
* Exon definition – There is a spatial restraint (300 nt) on pairs of viable splice sites defining an exon 
    * However, this does not explain the existence of pseudo-exons that are similar in size to authentic exons
* Spatial proximity – all other factors being equal, proximal splice sites are favoured 
    * However, if the splice sites are too close to each other, splicing cannot occur – if the 5’ splice site is less than 48 nucleotides away from the branch point sequence, splicing fails (may be used to enforce mutually exclusive splicing) 
* Temporal proximity – Splicing is co-transcriptional. In the kinetic coupling model (Bentley 2014), 5′ introns are excised before 3′ introns as they are transcribed first, so spliceosomes can assemble on 5’ introns first 
* Recursive splicing – intron “ratcheting” via “zero length” exons 
    * The intron contains a recursive splice site, which is composed of a 3’ splice site adjacent to a 5’ splice site 
    * After splicing of the recursive splice site, the 5’ splice site is reconstituted, and splicing is repeated to join the exons together 
      ![[Pasted image 20221218212324.png|475]]
        * #experimental_evidence E.g. Sibley et al (2000) – Used total RNA-seq data to demonstrate the existence of RS sites. They observed a saw-tooth pattern of RNA accumulation across long introns, because as soon as the 3’ end of the intron is synthesised, splicing occurs and the excised intron is degraded, so the sequences at the 5’ ends of introns have a longer lifetime and accumulate more. In some long introns, a discontinuity in the saw tooth occurred in the middle of the intron, which corresponds to zero-length exons
        * In vertebrates, recursive splicing requires initial definition of an RS "exon" that follows the RS site, and this exon is excluded from the mature mRNA due to competition with the reconstituted 5’ splice site. However, it can be included when it is preceded by cryptic promoters or when the reconstituted 5’ ss is weak. Most such RS exons contain a premature stop codon that weakens mRNA stability upon inclusion due to nonsense-mediated decay, thus differentiating the half-lives of different mRNA splice variants  
    * RS sites have a consensus sequence. 
    * The presence of RS sites implies that introns may not be as long as they appear. 
* Splicing enhancers and silencers (see [[B4 RNA splicing#Regulation of splicing – splicing code|Regulation of splicing – splicing code]]
    * Enrichment of ESEs vs ESSs is what distinguishes authentic exons from introns and pseudo-exons – exons have higher frequency of ESEs and lower frequency of ESS’s compared to pseudo-exons and introns (Zhang & Chasin 2004) 
      ![[Pasted image 20221218212404.png|625]]

## Regulation of splicing – splicing code
* Efficiency of splice site usage is regulated by enhancers and silencers that form a “splicing code” and can be found in exons or introns
* Splicing code regulates splicing by recruiting regulatory proteins that interact modulate interactions between nearby splice sites and spliceosome 
* Splicing code is gene specific (each gene has its own code) 
* Exons that are always included in mature mRNA are “constitutive”, while exons not included in final mRNA are “skipped” 
* Note: in principle, splicing code could refer more broadly to all inputs that affect splicing (e.g. chromatin structure), and not just the enhancers and silencers of splicing 

### Splicing factors 
#### e.g. SR proteins
* SR proteins have a modular structure
    * RNA binding domain (1-2 RNA recognition motifs [RRM]) to bind pre-mRNA 
    * Protein interaction domain (RS [Arg/Ser] domain) 
        * These domains are intrinsically disordered and mediate protein interactions with spliceosome components, e.g. U2AF35 and U170K 
        * Is reversibly phosphorylated during splicing
        * Promote pre-mRNA:snRNA base pairing 
* Bind to ESEs 
* How do SR proteins promote splicing at an exon (i.e. inclusion)? 
    * SR proteins may promote recruitment of U2AF to splice sites via interaction between RS domains of SR protein and UA2F35 
        * #experimental_evidence Graveley & Maniatis (1998) – ESE in 3’ exon is replaced by hairpin binding site for the MS2 coat protein. When MS2 was fused to RS domains from SRSF1/2/7, splicing was activated ![[Pasted image 20221218212430.png]]
        * RS domains found to promote binding of U2AF65/35 to the 3’ splice site (determined by UV cross-linking) – enhancers recruit SR proteins, which in turn recruit U2AF35 via RS domain. U2AF35 recruits U2AF65.![[Pasted image 20221218212438.png]]
        * However, splicing of MS2-dependent RNAs in S100 requires MS2-RS fusion protein _and_ intact native SR proteins ⇒ SR proteins have both enhancer-dependent and independent functions 
        * If the PPT is strengthened, enhancer dependency of splicing and U2AF binding is relieved 
    * Another way SR proteins may enhance splicing is by contacting the branch point directly, which may help to promote BPS:U2 snRNA interaction in the A complex 
    * Modification of splice site pairing after E complex formation 
        * In RNA with competing 3’ ss, one of the 3’ss may be ESE dependent, and is only used when ESE is activated by SR protein binding ![[Pasted image 20221218212444.png]]
        * #experimental_evidence Lim & Hertel (2004) – incubate the pre-mRNA in HeLa extract without RS-MS2 with spliceosome assembly blocked at E or A complex. Then, remove the blockade to spliceosome assembly in the presence or absence of RS-MS2. In the absence of RS-MS2, distal 3’ ss was used. In the presence of E complex + RS-MS2, proximal sites are used. But in presence of A complex + RS-MS2, distal site was used ⇒ Splicing activators can change splice site choice until  E complex – once A complex has formed, choice cannot be changed 
    * Antagonising silencers 
        * E.g. in HIV _tat_ exon 3, there is a hnRNP A1 binding silencer (ESS3), as well as an upstream ESE. In the absence of any SR proteins, hnRNP A1 can bind first at ESS3, then this initial hnRNP A1 recruits more hnRNPA1 via Gly domain in a cooperative manner, inhibiting splicing. However, if SRSF1 binds to the upstream ESE, it prevents cooperative binding of hnRNPA1, allowing splicing to occur![[Pasted image 20221218212452.png]]
    * SR proteins may show all of these mechanisms, some or just one  
* SR proteins affect alternative splice site selection, e.g. SRSF1
* Essential for splicing 

#### e.g. hnRNPs (heterogeneous nuclear ribonucleoproteins) 
* hnRNPs have a modular structure
    * RNA binding domain (1-2 RRMs) and/or KH-type RNA binding domain 
    * Protein interaction domain (may be Gly-rich domain or may be RRM itself) – no RS domains 
    * Additional variable domains can mediate protein-protein interactions (oligomerization) and are usually intrinsically disordered 
* Bind to pre-mRNA to form hnRNA 
* PTB protein prevents UA2F binding by competing with it for binding to the splice site, as well as via other mechanisms ([[B4 RNA splicing#Mechanisms of regulation in CNS (from study of neuron-specific cSRC N1 exon)|See CNS splicing]]) 
* Not essential for splicing 
* Are _sometimes_ repressive by repressing specific splice sites/exons or antagonising SR proteins 
    * Acts a repressor when bound to splicing silencers (ESS and ISS) 
* In general, for non-SR regulators, binding upstream and/or in exon represses, while downstream binding activates e.g. NOVA1/2 proteins

### Methods for experimental identification of ESEs and ESSs
* Deletion/substitution of enhancer/silencer and see effect on splicing 
    * Low throughput 
* Look at human clinical genetics – diseases associated with exon skipping 
    * 15% of human genetic diseases are splicing-related 
    * Exon mutations can cause exon skipping by impairing ESEs or creating ESSs 
    * Such mutations have to be identified by analysing mRNA – analysing genomic sequence alone can be misleading 
        * E.g. 50% of mutations in _NF1_ and _ATM_ genes cause aberrant splicing, but many were initially classified as nonsense, missense, or even silent based on effects on mRNA ORF 
    * ESE/ESS databases (e.g. ESE-FINDER and RESCUE-ESE) can be used to predict likely splicing phenotype of exon mutations 
* RNA binding Selected Evolution by Exponential Enrichment (SELEX)  ^ed58df
    * Use splicing activators or repressors to enrich for cognate RNA binding sites 
    * Low throughput 
    * #experimental_evidence Tuerk & Gold (1990) – SELEX for identification of optimal RNA protein binding sites. Used by subsequent studies to identify the consensus sequences for many spliceosome components and splicing factors![[Pasted image 20221218212507.png]] ^1fc4aa
* Functional SELEX in vitro (“functional” because splicing occurs) 
    * Low throughput 
    * #experimental_evidence Liu et al (1998) – Incubate splicing factor with an ESE-dependent pre-mRNA, amplify the spliced product by RT-PCR, sequence individual clones, and analyse the selected sequences for functional enhancer motifs  ^50408d
* Functional SELEX in vivo 
* RNAcompete 
    * High throughput alternative to SELEX 
* RNA Bind ‘n’ Seq 
    * More quantitative than SELEX – sequences all RNAs that bind to an RNA binding protein and also sequences the entire starting pool from which they were selected 
* Bioinformatics approaches, 
    * e.g. RESCUE-ESE
        * Identify hexamers that are (i) enriched in exons vs introns, (ii) enriched in exons with weak vs strong splice sites, and (iii) have z scores > 2.5 (i.e. more than 2.5 SD away from mean) 
            * Rationale for looking at upper right quadrant is that ESEs are likely to act on genes with many exons that have weak splice sites 
            * Hexamer used as the motif size as they occur frequently and most structures of RNA binding domains bound to RNA indicate that 3-5nt is most commonly recognised, so 6nt should capture most motifs  
        * Enriched hexamers are clustered together into groups
        * Test the the candidate ESEs in a splicing minigene transfection assay – as a negative control, use a single point mutation such that the resultant hexamer lies in the lower left quadrant of the scatter plot 
        * In assay, inclusion of central exon depends on whether an ESE is present![[Pasted image 20221218212533.png]]
    * #experimental_evidence E.g. Zhang & Chasin (2004) – searched for octamers enriched in (i) 5’ UTR constitutive exons vs in pseudo-exons and (ii) in 5’ UTR constitutive exons vs in intronless 5’ UTRs 
        * 5’ UTR used to avoid biases caused by protein coding constraints 
        * Octamers that are enriched in 5’ UTR constitutive exons are considered to be putative ESEs, while those in intronless 5’ UTRs or pseudo-exons are considered putative ESS’s 

### Factors affecting efficiency of splice site usage
* Strength of splice site (affected by similarity of exon-intron boundaries to consensus sequence) 
    * Splicing can be seen as competition between splice sites 
    * 3'ss strength is primarily driven by strength sequence of more variable PPT and branch point sequence. YAG sequence doesn't vary much, though RAG would indeed be weaker 
* Presence/absence of enhancers/silencers
    * Exon splicing enhancers (ESEs) can activate splicing by providing high affinity binding sites for SR proteins 
    * Introns may sometimes have these – intron splicing enhancers (ISEs) 
    * These enhancers can be constitutively active or inducible 
    * Activate adjacent weak 3’ or 5’ splice sites by promoting the binding of U2AF (3’ ss) and U1 snRNP (5’ ss) 
        * However they only activate 3’ splice sites within 300 nt 
    * ESEs often correspond to optimal binding sites for SR proteins 
* Presence/absence of activators/repressors – may be expressed only in specific tissues or in particular developmental stages 
    * The combination of enhancer and silencer binding proteins in the cell determines the splicing outcome (i.e. exon inclusion or skipping), and the outcome can be changed by altering what combination of these proteins are present 
* RNA secondary structure – can mask splice sites and *cis* regulatory sequences 

# Alternative splicing 
* Different combinations of splice sites are paired, resulting in different combinations of exons being included in the final mRNA
* Tissue or developmental stage-specific 
* Sequences from the same gene can be aligned to determine whether alternative splicing has occurred 

## Types of alternative splicing
![[Pasted image 20221218212549.png]]
(d) and (e) may not be regulated at the level of splicing 

(e) Has been discussed in [Alternative cleavage and polyadenylation](https://docs.google.com/document/d/1TUAu_Y-NPoaVWVRD2QSYVXZL4UvtP2h2SD_XX_mykUI/edit#heading=h.a3pc4b4iuzew)

## Functional consequences of alternative splicing 
* Generate variability in protein coding information → multiple protein isoforms → different functions 
    * E.G. SV40 T antigen – competing 5’ splice sites. Large T antigen or small t antigen can be formed. t is produced during early infection to repress apoptosis, and T produced later to induce transformation ![[Pasted image 20221218212636.png]]
    * E.g. _Drosophila_ DSCAM gene – Cell surface Ig domain protein. Has >38000 isoforms from alternative splicing. Each isoform recognises a specific neuron, allowing for neuronal patterning 
        * 4 arrays of mutually exclusive exons for diversity generation 
        * There is a strong preference _in vitro _for homotypic interactions between identical isoforms 
        * Neurons with identical isoforms that can bind will repel each other and grow away, while those with different isoforms will not repel each other and continue to grow together![[Pasted image 20221218212645.png]]
* Regulate gene expression 
    * E.g. _Drosophila_ sex-lethal RNA – males include exon 3 which includes a stop codon → no SXL. But females skip exon 3 
        * Exons with premature termination codons = “poison exons”
    * E.g. forkhead gene – Developmental transcription factor. Has mutually exclusive splicing. Exon 18a/18b encodes variants within the Forkhead DNA binding domain → alters DNA binding specificity 
        * 18a exon → differentiation 
        * 18b exon → pluripotency maintenance 
        * This exon affects folded domains. 
    * E.g. Wilms Tumor Gene – a Zn finger transcription factor that is essential to urinogenital development. It has an alternative 5’ ss that is 9 nt apart on exon 9 that results in the inclusion or exclusion of a tripeptide (KTS) – a microexon 
        * -KTS isoform (upstream 5’ ss) associates with transcriptional machinery 
        * +KTS (downstream 5’ ss) associates with splicing factors 
        * Frazier Syndrome (defects in kidney development and sex determination) results from mutations that disable +KTS splicing event 
* Rewiring of tissue-specific protein-protein interaction networks

## Regulation of alternative splicing
Same as [[B4 RNA splicing#Factors affecting efficiency of splice site usage|Factors affecting efficiency of splice site usage]]
Directs which splice site spliceosome factors are recruited to 

### Intron retention in _MER3_ in _S. cerevisiae_
* In yeast, intron retention is used to switch off gene expression 
* In early meiotic cells, _MER3_ pre-mRNA is poorly spliced → no protein produced
    * 5’ splice site in _MER3_ pre-mRNA is weak → U1 snRNP binds inefficiently 
    * Mutations that restore consensus at 5’ splice site result in constitutive splicing
* In late meiotic cells, _MER3_ pre-mRNA is spliced → protein produced 
    * Retained intron contains an intronic splicing enhancer
    * MER1 binds to ISE to recruit U1 snRNP 
        * No splicing is seen _MER1_Δ cells or in cells with mutated ISE 
* MER1 is only expressed in meiotic cells → splicing is meiotic-specific 

### Sex determination in flies is controlled by a cascade of regulated alternative splicing 
![[Pasted image 20221218212734.png]]

#### Negative splicing regulation of *Transformer* mRNA by SXL protein (_Drosophila_) 
* Transformer RNA has two alternative 3’ splice sites
    * U2AF<sup>65</sup> can bind to both sites, but preferentially to the proximal 3’ splice site 
    * Males use proximal 3’ splice site → exon contains premature termination codon (poison exon) → no protein 
        * In males U2AF<sub>65</sub> binds to proximal site → splicing occurs at proximal site
        * The proximal PPT  matches the Sxl optimal binding site 
        * #experimental_evidence Valcarcel et al – Fused N-terminal RS domain of U2AF<sup>65</sup> to Sxl. This resulted in splicing at the 3’ splice site. 
    * Females use distal 3’ splice site → protein produced 
        * SXL (only in females) binds to proximal polypyrimidine tract but not to distal one → U2AF<sub>65</sub> cannot bind → splicing occurs at distal site 
![[Pasted image 20221218212800.png|600]]
* Regulation is negative at the upstream 3’ ss
    * When the upstream site is deleted, the downstream is used whether or not Sxl is present  

#### Autoregulation of *Sxl* _mRNA by SXL protein (Drosophila_) 
* In male _Drosophila_, exon 3 of Sxl is included which encodes a stop codon → No Sxl produced (“poison exon”) 
* In females, exon 3 is skipped → Sxl produced 
* U-rich sequences are present in the flanking introns around exon 3. SXL binds cooperatively RNAs with multiple such U-rich sequences – thus they act as ISSs 
    * Deleting the N-terminal 125 aa Gly/Asn-rich region abolishes cooperative RNA binding and Sxl autoregulation, but not binding to single URS and regulation of Transformer ![[Pasted image 20221218212827.png]]
* The U-rich sequences are distant from the splice sites, so inhibition of splicing is not simply due to direct binding competition with U2AF (as is the case for SXL), and other genes (e.g. snf, vir) are required for regulation as well 
* The exon definition of exon 3 relies on a distal AG, but in splicing a proximal AG is used as the 3’ SS 
    * Presence of proximal AG weakens the exon![[Pasted image 20221218212836.png]]
    * Using site-specific UV crosslinking, found that U2AF<sup>35</sup> binds to the distal AG, while SPF45 binds to a proximal AG 
        * SPF45 binding depends on prior U2AF<sup>35</sup> binding, and this occurs in the A complex 
        * SXL interacts with SPF45 via N-terminal G/N rich domain 
* So SXL interacts with both the U-rich sequences and SPF45 via its G/N domains → results in an abortive A complex?  
* Positive feedback loop resulting from Sxl autoregulation provides a stable genetic switch for sex determination 

#### Initiation of female SXL splicing 
* To produce SXL, _Sxl_ exon 3 is skipped, but skipping relies on SXL protein. 
* In the embryo, there is an embryonic promoter adjacent to exon E1 that is only active in females. This exon can splice directly to exon 4, resulting in skipping of exon 3 → Sxl can be produced 
* This embryonic Sxl is sufficient to define later female-specific splicing of Sxl transcripts from the adult promoter 

#### Epitranscriptomic regulation of Sxl splicing? 
* Haussmann et al (2016) – m6a may promote female-specific alternative splicing of Sxl. Fl(2)d, which is required for Sxl autoregulation, forms part of m6A methyltransferase complex. 

#### Positive splicing regulation of *Dsx* splicing by Tra/Tra2
* Females – Dsx exon 3 is spliced to exon 4 
    * Tra (female-specific) and Tra2 are required for E4 splicing 
    * Tra and Tra2 form a complex with SRSF7 that recognise 6 x 13 mer repeats, and Tra/Tra2 form a complex with SRSF1 that recognises a 1 x purine rich element in the E4 3’ UTR 
    * SRSF7 and 1 are SR proteins 
    * In the absence of Tra, binding of SRSF1/7 and Tra2 to each site is weak ⇒ Tra induces cooperative binding of trimeric complex to _each_ site 
    * The Tra/Tra2/SRSF complex strengthens splicing by recruiting U2AF<sup>35</sup> to the weak PPT of exon 4 via their RS domains
    * The distance between the Dsx enhancer and the 3’SS is important – when distance between enhancer and 3’ ss is reduced, it becomes constitutive 
        * Purine-rich element – has to be in UTR (hard to accommodate in coding sequence) 
        * Design principle – enhancer is only induced in presence of a factor 
* Males – Exon 3 spliced to exon 5 
    * Exon 4 has a weak PPT, so is skipped in the absence of Tra/Tra2 ⇒ Tra/Tra2 strengthens splicing of exon 4 
![[Pasted image 20221218212902.png|625]]

### Mammalian tissue-specific AS 
- One or multiple regulators may be involved in creating tissue-specific splice patterns 
	- Regulatory protein expression often not restricted to single tissue or cell type 

> [!image] Examples of AS regulatory factors in mammals 
> ![[Pasted image 20230505085016.png]]

#### Features of CNS splicing code 
- In CNS, elements of splicing code are concentrated in alternative exons or in sequences immediately flanking the exons. Few are found in the flanking exons. 
- CNS code contains numerous elements and many features are shared with other tissue codes (e.g. muscle)

> [!note] Elements involved in neuronal splicing
> - **CU-rich elements**. PTBP1/nPTB binding. Found upstream of neuronal exons
> - **YCAY**. NOVA binding sites. Found downstream of neuronal included exons and upstream/within neuronal skipped exons 
> - **(U)GCAUG**. RbFOX sites. Found downstream of neuronal included exons 
> - **AUUAAAU**. Novel, cognate factors not yet known 
> - **UGAUUUU**. Novel, cognate factors not yet known 

- There is significant co-occurrence of feature pairs
	- E.g. Upstream CU-rich motifs with a distant first upstream AG (indicative of a distant branch point) often paired with downstream RbFox sites 
- Few motifs are enriched in neuronal included exons, as they tend to be short and not cause frameshifts/PTC inclusion when skipped 
- Splicing code also contains features not recognised by spliceosome due to conservation ( #question meaning?)

#### Mechanisms of regulation in CNS (from study of neuron-specific cSRC N1 exon)

**Neuronal microexons**
- Small casette exons (3-27 nt) highly conserved in neurons 
- e.g. nSR100/SRRM4 is a key activator via UGC motifs between exon and PPT 
	- Enhancer of microexon (eMIC) domain essential for activity
	- Antagonises PTBP1 expression
- Microexons modulate interaction domains of neuronal proteins
- #experimental_evidence Irimia et al (2014) – Can be misregulated in autism

**Exon skipping of N1 in non-neural cells** 
- Short exon size (18 nt) could make it too short for efficient exon definition
	- #experimental_evidence Expansion of exon to ~100 nt makes it constitutive 
- Binding sites for PTB1 upstream and downstream of exon 
	- #experimental_evidence mutation of PTBP1 binding sites activates splicing in vitro (in HeLa nuclear extracts)
	- #experimental_evidence SELEX experiments identified YYYUCUUYYY as the optimal binding site, which also matches known ESSs and ISSs
- PTB1 acts as a splicing repressor via multiple mechanisms
	-  #experimental_evidence for PTB1 repressor activity –Depletion of PTB1 from HeLa nuclear extract promotes N1 exon splicing; rescue with recombinant PTB1 restores inhibition 
	- PTBP1 can directly compete with U2AF65 at regulated PPTs (same as [[B4 RNA splicing#Negative splicing regulation of *Transformer* mRNA by SXL protein (_Drosophila_)|Sxl regulation of Tra]], findings from [[B4 RNA splicing#^ed58df|SELEX]])
		- #experimental_evidence Matlin et al (2007) –  showed that PTBP1 binding to *Actn1* SM exon PPT antagonised U2AF65 binding, but that additional downstream PTB1 binding sites were required 
	- Cooperative PTB1 binding can lead to repression
		- #experimental_evidence Chou et al (2000) – Site-specific UV-crosslinking shows binding of PTBP1 to upstream sites depends on downstream sites and vice-versa. 
			- BS103 and BS73 substrates with mutations in PTB1 sites that activate splicing show ATP-dependent PTB1 displacement 
	- PTB1 represses cross-intron interactions between U1 snRNP at *c-SRC* N1 5'ss and SF3A1 (in U2AF) by interacting with stem loop 4 of U1 snRNA, thus inhibiting N1 splicing. PTB1 stabilises U1 snRNP binding to N1 5'ss, thus stabilising this non-productive interaction 
		- #experimental_evidence Sharma et al (2006)
			- Purified H complex from HeLa extract (N1 not spliced in, as well as H and E complex from WERI cell extract (a neuronal cell in which N1 exon is spliced in). Comparison of complexes indicated that HeLa H complex has more PTBP1 and less U2AF than WERI H complex
			- Depletion/addback experiments showed that PTBP1 was responsible for reduced U2AF65 binding 
			- If RNA has constitutive 5'ss of exon 3, PTBP1 no longer blocks U2AF65 binding 
		- #experimental_evidence Sharma et al (2008)
		- Further experiments in the Black group showed that repressive PTB1 interacts directly with stem-loop 4 of U1 snRNA at the 5'ss of the N1 exon, and that the U1 snRNA stem loop 4 interacts with the U2 snRNP protein SF3A1 to mediate cross-intron interactions 
- However, PTB can also *activate* splicing from a downstream location by recruiting U1 snRNP 
	- Activation may depend on PTBP1 binding only downstream of exon, as all exons with binding sites on both sides (e.g. N1) are repressed by PTPB1 
		- #experimental_evidence Llorian et al (2010) showed that PTBP1 activated exon with a downstream binding site could be converted to a repressed exon by addition of an upstream site 

**N1 exon inclusion**
- ESE at 5' end of exons – binds SRSF1
- ISE downstream control sequence – overlaps a PTB1/2 binding site, contains GCAUG RbFOx1/RbFOX2 binding site in an "activating location"
- Expression of PTBP paralogs – PTBP2 is increasingly expressed and PTBP1 is less expressed. PTBP2 is a weaker repressor for certain exons (e.g. N1) than PTBP1, so a subset of exons is upregulated. On other exons, it has similar activity 
	- This switch of expression is mediated by PTBP1-induced nonsense-mediated decay of PTBP1 and 2. PTBP1 causes partial skipping of exon 11 in PTBP1 to limit its levels, while promoting complete skipping of exon 10 in PTBP2. As these exons are 34 nt long, skipping causes frameshift, leading to NMD. ![[Pasted image 20230505103039.png]]
	- During neuronal differentiation, miR-124 is upregulated, which inhibits PTBP1. This leads to skipping of exon 11 in PTBP1, and inclusion of exon 10 in PTBP2, thus changing their levels of expression 
- Enhancer complex on DCS – assembly of intron enhancer complex containing hnRNP H, hnRNP F, KSRP, PTBP2 (RbFox1/2)
	- PTBP2 promotes assembly of enhancer complex
- RbFox1/2 binding – promotes N1 splicing 

### Mutations in splice sites or splice code can result in disease
* Mutations can inactivate 5’ and 3’ splice sites, enhancers, or silencers
* Mutations can also generate new splice sites 
* Some exons are particularly vulnerable to mutations that disrupt splicing (“hotspot exons”) 
* E.g. Hutchinson-Gilford Progeria Syndrome (HGPS) 
    * Point mutation in exon 11 of prelamin A gene activates a cryptic splice site 
        * Cryptic splice sites are sites in the DNA that _could_ act as splice sites, but are not used because splicing occurs at a more favourable site 
    * Resulting protein has 50aa deletion that removes a protease cleavage site → protein not processed correctly
    * This mutation is technically silent as it does not change the amino acid encoded (still Gly), but it has phenotypic effect 
![[Pasted image 20221218212932.png|600]]
* E.g. Frazier Syndrome
* E.g. Myotonic dystrophy – CUG binding protein (CUG-BP) (=CELF1) regulates splice site selection in the insulin receptor (IR) gene by antagonising the facilitatory activity of MBNL1 and MBNL2 on IR exon 11 splicing. 
    * CUG expansion in 3’ UTR of _DMPK_ or in intron 1 of _ZNF9_ produces CUG expansion RNA, which sequesters MBNL proteins into nuclear foci 
    * CUG expansion RNA also leads to PKC activation, phosphorylation and stabilisation of CELF proteins
    * The end result is removal of exon 11 from IR → insulin resistance 
    * MBNL1 also inhibits exon 7a inclusion in CIC-1, which encodes a stop codon (UGA) → MBNL1 sequestration results in 7a inclusion → isoform is degraded by nonsense-mediated (NMD) RNA decay → myotonia Some human exons are particularly vulnerable to splice-disrupting mutations (“hotspot exons”) 
* Splicing regulatory elements can be therapeutic targets 
    * E.g. Nusinersen – splice modulating drug for spinal muscular atrophy. The drug is an antisense RNA that blocks hnRNP from binding to an intronic splicing silencer to promote SMN2 exon 7 inclusion  

## Methods for studying global AS events (ASEs)
- Genome-wide approaches can be used to decipher the general rules of splicing programmes 

### Splice-sensitive arrays 
- Obsolete method (based on microarray)
- RNA (or cDNA) hybridised to multiple probes immobilised on a microarray to profile changs in large numbers of ASEs
- Probes may bind exons and/or exon junctions
- Arrays rely on prior annotation i.e. known protein isoforms
	- May also include computer isoforms 
	- May include previously unobserved junctions between known exons 
- However, cannot be used for discovery of new ASEs 

> [!image] Splice-sensitive arrays
> ![[Pasted image 20230505111747.png]]

### Global AS profiling by RNA-seq
- Uses NGS to replace arrays for transcriptome profiling
- Allows discovery of novel ASEs 
- Can be used for quantification of ASEs
	- Can be difficult to quantitatively profile ASEs in lowly expressed genes 
- Create sashimi plots 

> [!image] Splice-sensitive arrays
> ![[Pasted image 20230505111803.png]]

### Bioinformatic analysis of co-regulated ASEs to identify a splicing code 
See [[B4 RNA splicing#Methods for experimental identification of ESEs and ESSs]]

> [!Note] Process
> 1. Compile data-sets of co-regulated exons and control exons (i.e. those that are constitutively spliced or are unregulated)
> 2. Divide each experimental and control event into 7 regions 
> 3. For each region, statistically analyse for enrichment/depletion of different sequence k-mers (k=4-7) in the experimental vs control exon set
> 4. If enriched motifs correspond to a known RBP binding site, investigate whether changes in expression of RBP mRNA can explain the inferred activity of motifs 

- Disadvantage is that enriched motifs do not necessarily indicate protein binding 

> [!image] Example of bioinformatic analysis
> ![[Pasted image 20230505085936.png]]

### Splicing maps 
- Determine where RBPs bind and the functions of RBPs in AS
- KO/knockdown or overexpress RBP, and observe how AS changes using mRNA-seq data (previously splice sensitive array was used)
- Determine where RBPs bind to RNA using CLIP 
	- HITS-CLIP – highthroughput version 
	  ![[Pasted image 20230505112749.png]]
	- Provides single-nucleotide resolution, transcriptome-wide view of protein-RNA contacts 
- #experimental_evidence Licatalosi et al (2008) determined a splicing map for Nova1 and Nov2, which are brain-specific KH-domain RNA binding proteins. SELEX had previously been shown that YCAY is the optimal site for binding. 
	- Used splice sensitive array analysis of wt vs Nova2(-/-) neocortex
	- NOVA2 CLIP of mouse neocortex
	- Found that upstream NOVA binding is associated with repression, while downstream NOVA binding is associated with activation 

> [!note] Process of CLIP 
> 1. UV irradiate live cells to cross-link proteins to RNA 
> 2. Lyse cells -> partial RNAse digest to ~100-200 nt RNA fragments (fragments have to be long enough to allow mapping back to genome)
> 3. IP against RBP of interest 
> 4. Recover RNA-protein complex from SDS gel 
> 5. Treat with proteinase to recover RNA
> 6. Deep sequence reverse-transcribed, adapter-ligated RNA fragments 
> 7. Map RNA reads to genome 
#### Questions raised
- How does same protein lead to different regulatory outcomes depending on the location of binding?
- How do a variety of different proteins have the same effect when bound at similar locations? 
	- Common mechanisms of action and molecular targets? (e.g. targeting different subunits of U1 snRNP to promote recruitment to weak 5' splice sites?)
		- E.g. TIA1 recruits U1C, PTBP1 recruits U1 snRNA stem-loop 4, SAM68 recruits U1A 

### Computational deciphering of splicing code 
- Prediction of changes in splicing based on genomic sequence input 
- #experimental_evidence Barash et al (2010) – used splicing array data from 26 mouse tissue/cell lines for 3665 casette exons and 1000 RNA "features" (known ESEs, ESSs, protein binding sites, secondary structure, exon length, conservation, etc. ) as inputs for a machine learning model to produce a predictive splicing code
	- Data was clustered into 4 tissue groups, muscle, CNS, embryo, and digestive tissues 
	- They found that the model scored 94% true-positive in predicting the **direction** of change between tissue groups; was not good at predicting absolute inclusion values 
	- Exon inclusion or skipping in particular tissue groups was determined by multiple features, with may interacting; few individual features were absolutely specific for a tissue 
	- Some code elements were consistent with splicing maps, while motif enrichments were associated with co-regulated exons

# Links to other topics 
- [[Module D index]] – Dysregulation of alternative splicing can lead to cancer 
	- David & Manley (2010) do a good review of this topic, showing how dysregulation of AS can affect genes important to different stages of cancer development 