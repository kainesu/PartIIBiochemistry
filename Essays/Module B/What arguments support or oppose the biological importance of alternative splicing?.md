**Using mass spectrometry-based proteomics data some investigators have suggested that alternative pre-mRNA splicing plays a marginal role in generating proteomic diversity. What arguments support or oppose the biological importance of alternative splicing?**

# Intro 

* Alternative splicing plays many roles apart from generating proteomic diversity 
    * Regulation of expression 
        * Adaptation 
        * Development 
* However, recent mass spec data suggest that mRNA splicing does not play as big a role in generating proteomic diversity as once thought, as transcriptomic data indicates otherwise 
* Here, I provide an overview of the arguments supporting and opposing the importance of AS in biology, as well as caveats for some of the opposing arguments. 

# For
* Transcriptomic evidence has shown that AS does occur, and ribosome profiling studies suggest that these AS transcripts are translated
	* But ribosome occupancy alone not sufficient to demonstrate functionality, since not all translational events result in stable functional proteins 
* AS has been clearly shown to generate functional protein diversity 
    * E.g. _Dscam1_ in neuronal tissue 
* AS impt to regulating expression of other genes in a variety of contexts 
    * Other splicing factors 
        * E.g. PTBP1 – nonsense-mediated decay by inclusion/exclusion of exon that causes frameshift 
        * E.g. All SR proteins contain poison exons 
    * Development and phenotypic plasticity 
        * E.g. _Drosophila _sex determination system 
            * Poison exons 
        * E.g. Poikilothermic_ _reptiles sex determination in response to temperature 
            * In turtles, below 26°C, the kinase CLK1/4 phosphorylates SR proteins so they localise to the nucleus. This turns off certain AS events that cause male development; above 31°C, CLK1/4 is inactive 
        * E.g. Flowering time in _Arabidopsis thaliana _
            * AS of the transcription factor FLOWER LOCUS M produces non-productive isoforms that interact with the floral repressor SVP
        * E.g. The cave-dwelling morph of the _Astyanax maxicanus_ fish has an AS event in the _per2_ gene, which represses Pparγ, thus repressing lipogenesis genes. However, AS of _per2_ leads to skipping of exon 21 and the introduction of a premature termination codon, relieving the repression and thus increasing lipogenesis. This allows the cave-dwelling population to survive during food scarcity. Thus, this demonstrates phenotypic plasticity by AS (since the non-cave dwelling morphs don’t have this AS) 
    * This regulation is orthologous to gene expression regulation, as genome-wide studies have shown that they are regulated by different genes and tend to affect complementary sets of genes within a tissue 
        * As such, AS is not redundant for gene expression but rather adds another layer of complexity to gene regulation; this is supported by the fact that the frequency of AS in species predicts its complexity 
* Rewire tissue-specific protein-protein interactions (10,11) 
    * Alternative splicing has been shown to be tissue-specific 
        * This can be important in… (specific example) 
    * Disordered protein regions are prevalent in alternative isoforms (12), and such regions often have many functions and contain PTM sites and protein binding sites 
    * Splicing can cause changes of functional domains that change which protein partners the isoform interacts with 
        * E.g. AS in FOXP1 transcription factor regulates DNA binding preference 
            * In ES cells, exon 18b is included, upregulating pluripotency genes e.g. OCT4, NANOG
            * In differentiated cells, exon 18 is included instead to promote differentiation 
            * These splicing is conserved in 46 vertebrate species, thus highlighting its importance in regulating protein-protein interactions
- Many AS are evolutionary conserved. Unless it had functional importance, AS would not be selected for as there is energetic cost to maintaining and expressing spliceosome 
- Aberrant splicing has been linked to disease – estimated 15-50% of human genetic diseases relate to splicing errors, e.g. myotonic dystrophy, Frazier syndrome, rheumatoid arthritis 

# Against

* Most genes are not alternatively spliced.
    * “Although many thousands of alternatively spliced transcripts are routinely detected in RNA-seq studies, reliable large-scale mass spectrometry-based proteomics analyses identify only a small fraction of annotated alternative isoforms” 
        * In classical proteomics, proteins are trypsinised to peptides and the peptides are identified (or even sequenced) via liquid chromatography-MS/MS. Protein isoforms could be identified by the detection of peptides unique to the isoforms (e.g. those corresponding to a unique exon) 
        * Abascal et al (2017) – Reanalysed mass spectra from eight large-scale experiments. Found that peptides for most protein-coding genes did not have evidence for more than 1 isoform, only ~2% showed reliable evidence for >1 isoform, suggesting that alternative protein isoforms are not abundant, even though alternative transcripts are abundant based on transcriptomic and microarray data 
            * Instead, most genes have a single main protein isoform 
        * However, part of the discrepancy could be explained by technical reasons. Mass spec often does not have full peptide coverage of even highly expressed proteins, and alternative transcripts that are less expressed may not be well covered, leading to some exons being missed out. This is especially since the authors applied a high stringency filter in including peptides in their study. 
            * In contrast to the study, ribosome profiling experiments identified 75% of human exon-skipping events detected by RNA sequencing 
    * It appears that most of the variance in proteome between human tissues is explained by differences in gene expression in stead (19) 
* For proteins that do exhibit alternative isoforms, the isoform is unlikely to be functionally different
    * A substantial proportion (60/282) involve duplication of homologous exon substitutions (Abascal et al 2017) 
    * Many isoforms did not differ in Pfam functional domain composition
* Alternative exons are under weaker negative selection than the dominant isoform 
    * Most alternative exons evolve neutrally – the ratio of nonsynonymous to synonymous mutations was higher in alternative exons than in exons included in the dominant isoform, suggesting that mutation in these exons does not significantly impact function 
    * However, alternative exons may be expressed to a lower level and so are not under as intense selection pressure 
        * Moreover, this could lead to increased sequence diversity in the alternative transcripts that could be selected for in a change of environment (evolutionary capacitation; see more below) 
* Splicing can be explained by stochastic models, and does not always leads to protein coding 
	* Degree of exon skipping found to be consistent with degree of RNA pol II errors (see Lin & Hertel et al)
	* Some noise from sequencing could also be detected incorrectly as splicing event
    * Melamud & Moult (2009) proposed that the number of isoforms and abundance of each isoform can be predicted by the number of introns in a gene and its expression level, suggesting that AS is simply stochastic noise (i.e. error) in the splicing machinery and is not functionally significant 
        * This model was tested on a virtual cDNA library assembled from various EST libraries. ASEs were identified by comparing the intron structure of the major isoform with the intron structure of each EST sequence. If the EST sequence has at least 1 intron different from the major isoform at the 5’ or 3’ splice site, it was considered an alternative transcript. 
    * However, noisy splicing may actually drive evolution – stochastically produced alternative transcripts could potentially provide new functions that are selected for  ^a8bcab
        * As only a few mutations are needed to alter AS events and thus phenotype, AS can cause large changes in phenotype within just a few generations, allowing species to adapt to rapidly changing to environments, particularly if these mutations occur in regulatory proteins 
        * E.g. AS of _Drosophila melanogaster_ neural transcription factor _lola_ generates 19 different transcripts that each differ in how they bind DNA, increasing the number of possible protein-protein interactions and signalling pathways → possibility of creating new regulatory pathways 
        * E.g. Vampire bat and TRPV1 receptor with poison exon 
        * AS could be more evolutionarily flexible than mutations in genes, since mutations are “hard-coded” and could result in all isoforms carrying the mutation and becoming non-functional, whereas AS allows a functional isoform to dominate while less functional ones are expressed at a low level, and perhaps be selected for should an environmental change occur. Effectively, this results in a trade-off between maximisation and flexibility, which could be an advantage in species that often experience environmental change  
        * It has also been hypothesised that alternative transcripts that induce NMD could act as a form of evolutionary capacitance, whereby variation is accumulated without affecting phenotype. NMD lowers expression of the transcript, but if a mutation were to reverse the NMD, it could create variation that is selected for under new conditions; this hasn’t been tested though. 
* Prokaryotes appear to enjoy high fitness in their particular niches despite rarely using alternative splicing, so alternative splicing is clearly a non-essential process for life (compared to other more widely used regulatory processes such as transcriptional control) 

# Testing the functional significance of splicing events 
- Challenging because many functionally important events are tissue-specific; if we do not test in the right tissue, no function can be uncovered 
- Generally difficult to interpret from negative evidence. 
- But we could use e.g. CRISPRi to block AS and test if there are phenotypic outcomes
- #experimental_evidence Charton et al (2016) blocked a splicing of a key exon in mouse titin, and this resulted in tissue dystrophy, demonstrataing that splicing had functional importance. 

# Conclusion 

* Reconciliation: 
	* Although mass spec suggests that few proteins have alternative isoforms, this does not explain why alternative transcripts continue to be detected in abundance. 
	* Although alternative splicing may not account for all of proteomic diversity and gene expression regulation, it clearly does explain a subset of them 
	* The fact that AS does not occur as commonly as once thought, does not discount its importance in each instance it occurs, as it has been shown to play a role in regulating highly important genes involved in development and adaptation, with systemic consequences for organisms 
	* Frequency =/= importance. 
	* Supported by the fact that some of these ASEs are highly conserved 
* Moreover, spliceosome and splicing is a complicated event, the fact that it has been conserved across eukaryotes is indicative that it is important to biology in some way, even if the extent is not as high as once thought 
* The importance of AS could be species-specific; many studies focus on just a few model species (e.g. humans, mice, _Drosophila_), and may not account for the greater importance of AS in other species (possibly) 
    * For example, the study by Abascal et al (2015) used databases of the human proteome and transcriptome, so may not be applicable to all species 
* Applications 
    * Synthetic biology – generate increased diversity in protein libraries for directed evolution, or could be incorporated into genetic circuits for gene control 
* Future research required to advance the debate 
    * More experiments on the role of AS in evolution – e.g. using flies, engineer a gene to have different alternative transcripts and see whether this might improve fitness of the lineage in the long term 
    * Artificially increase alternative transcript expression and see if this changes the ratio of synonymous to nonsynonymous mutations in the alternative exons over several generations 
    * In the future, alternative transcripts should not be assumed to encode functional isoforms, and each transcript has to be functionally characterised to show how it contributes to protein diversity 
        * Machine learning could be helpful in identifying functionally important isoforms 
        * Experimental determination could be done via editing of the splice site or RNAi 