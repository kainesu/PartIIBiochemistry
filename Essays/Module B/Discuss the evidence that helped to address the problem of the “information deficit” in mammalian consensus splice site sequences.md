**Discuss the <span style="text-decoration:underline;">evidence</span> that helped to address the problem of the “information deficit” in mammalian consensus splice site sequences.**

# **Intro** 

* While yeast splice sites have sufficient information to unambiguously specify authentic sites, metazoan splice site sequences are generally weak and degenerate – in fact, the information content of mammalian splice sites is insufficient and is much less than in yeast, despite mammals having larger splice sites as well as many and longer introns. 
    * As such it is difficult to computationally predict splice sites from their sequence alone
* This raises the question of how authentic, alternative splice sites in mammals, including humans, are correctly recognised by spliceosome components under the appropriate conditions when the isoform is required. The task is complicated by the fact that many mammalian introns have numerous pseudo-exons, which are sequences flanked by apparent consensus 3’ and 5’ splice sites, and yet are not included in the mature mRNA, making it unclear how they are differentiated from real exons by the spliceosome. 
* Studies have shown that mammalian cells can address this problem by specifying authentic splice sites using the information encoded in other _cis _elements and _trans _factors that make up a splicing code. 
    * The information required to specify authentic splice sites is contained within splice code elements 
* In addition, spatial and temporal constraints help to restrict which splice sites can be paired
* Discovery of recursive splice sites also suggests that many introns are not as long as previously thought, which eases the task of splice site recognition in mammalian cells. 
* The answer to how mammalian cells address the information deficit overlaps may perhaps be the mechanisms by which splice site recognition is regulated. 

# Splicing code encodes additional information for specification of the correct splice sites 

* Cis elements
    * The efficiency of splice site usage is regulated by enhancers and silencers that form a “splicing code” and can be found in exons or introns
    * These enhancers/silencers recruit regulatory proteins that modulate the interactions between nearby splice sites and the spliceosome 
    * As such, the difference in frequency of enhancers and/or suppressors is what distinguishes authentic exons from introns and pseudo-exons, rather than just the sequence of the splice sites themselves 
        * Zhang & Chasin (2004) uses a bioinformatics approach to show that exons have a higher frequency of ESEs and a lower frequency of ESS’s compared to pseudo-exons and introns 
            * Identify octamers that are enriched in (i) 5’ UTR of constitutive exons vs pseudo-exons, (ii) 5’ UTR of constitutive exons vs intronless 5’ UTRs and (iii) have z scores > 2.5 (i.e. more than 2.5 SD away from mean)
                * 5’ UTR was used to avoid biases caused by protein coding constraints 
                * Octamers that were enriched in 5’ UTR constitutive exons were considered to be putative ESEs, while those in intronless 5’ UTRs or pseudo-exons were putative ESS’s 
                * Exons having a higher frequency of ESEs suggests that they are more likely to be spliced, such as by increased recruitment of SR proteins that promote splicing via various mechanisms (see below) 
        * Barash et al (2010) went further in showing that tissue-specific exon skipping or inclusion could be predicted from various RNA motifs and transcript structure, including enhancers and silencers, via machine learning 
            * This model scored 94% true-positive in predicting the direction of change between tissue groups, suggesting that other features apart from the splice site sequences themselves are important to specifying splice sites 
            * However, the model was not good at predicting absolute inclusion values, suggesting that there is still a gap between what we know regulates splicing and what actually does regulate splicing in the cell 
            * In addition, not all the short motifs identified as having the strongest regulatory evidence appear to be known ESEs/ESSs or _trans_ factor binding sites, so further work would be needed to mechanistically understand how these motifs help to address the information deficit 
* Trans factors 
    * Splicing enhancers and silencers recruit regulatory trans factors, the complement of which can differ from tissue to tissue. As such, whether an exon is included or skipped is determined by the particular combination of enhancer and silencer binding proteins. 
        * E.g. Nova1/2 is only expressed in neurons, while Esrp1/2 is only expressed in epithelial cells 
        * The complement of enhancer/silencer binding proteins can be determined in part by small RNAs 
            * E.g. During neuronal differentiation, miR-124 is upregulated, which inhibits PTBP1. This leads to skipping of exon 11 in PTBP1, and inclusion of exon 10 in PTBP2, thus changing their levels of expression
    * SR proteins are important to specifying genuine exons for inclusion in the mature mRNA as they promote splicing of the exon 
        * SR proteins tend to bind ESEs and promote splicing of an exon by recruiting U2AF to 3’ splice sites. The RS domains of the SR protein and U2AF35 interact, and U2AF35 in turn recruits U2AF65
            * Graveley & Maniatis (1998) – ESE in 3’ exon is replaced by hairpin binding site for the MS2 coat protein. When MS2 was fused to RS domains from SRSF1/2/7, splicing was activated
        * SR proteins aso enhance splicing by contacting the branch point directly, which may help to promote BPS:U2 snRNA interaction in the A complex
            * Shen et al (2004) used RNA-protein crosslinking to identify where ESE-bound RS domains bind.  They created an MS2-RS domain chimera, and prepared pre-mRNAs radioactively labelled at different candidate binding sites for the RS domain, including the branch point. They found that RS domain polypeptide was only detected with pre-mRNA substrate labelled at branch point. 
        * SR proteins can antagonise silencers
            * E.g. in HIV _tat _exon 3, there is a hnRNP A1 binding silencer (ESS3), as well as an upstream ESE. In the absence of any SR proteins, hnRNP A1 can bind first at ESS3, then this initial hnRNP A1 recruits more hnRNPA1 via Gly domain in a cooperative manner, inhibiting splicing. However, if SRSF1 binds to the upstream ESE, it prevents cooperative binding of hnRNPA1, allowing splicing to occur
    * On the other hand, splicing repressors bind to splicing silencers to repress splicing e.g. PTBP1 prevent U2AF binding 
    * Trans factors can also exhibit position dependence – for example, NOVA1/2 proteins binding upstream and/or in exon causes repression of splicing, while downstream binding activates splicing of the exon. In this way, information is encoded not just by the nucleotide sequence of the _cis _element but by its position relative to the exon as well 
    * Trans factors also link chromatin packaging to splicing, providing another point of regulation for splice site specification 
        * E.g. Luco et al (2010) – Found that splicing of exon IIIb vs IIIc in the human fibroblast growth factor receptor 2 (_FGFR2_) gene was dependent on H3K36me3 mark. MRG15 may recognise H3K36me3, and in turn recruit PTB to repress exon inclusion. As a consequence, exon IIIb is included in human prostate normal epithelium cells, while exon IIIc is included in human mesenchymal stem cells
            * Overexpression of MRG15 caused exclusion of PTB-dependent exons 
            * Endogenous PTB also co-IP’ed endogenous MRG15 in both cell types 
            * Distribution of MRG15 mirrors PTB on repressed exon IIIb in hMSCs 
* However, the existence of a splicing code alone does not fully account for the information deficit, since _S. cerevisiae_ pre-mRNA also contain intronic splicing enhancers e.g. _MER3_, which recruits MER1 to recruit U1 snRNP to promote splicing in meiotic cells. MER1 is only expressed in meiotic cells, ensuring that splicing is meiotic cell specific 
    * Perhaps it is the extent to which a splicing code is employed in mammals differentiates them from yeast – yeast may have less reliance for a splicing code given the higher information content of their splice sites 

# Spatial and temporal constraints restrict which splice sites that can be paired 

* Apart from the information contained within the splice sites themselves, splice site recognition can be constrained by the physical parameters of space and time 
* Spatial restraints
    * Exon definition – there is a spatial restraint (300 nt) on the pairs of viable splice sites that can define the exon
        * Most exons are only 50-300 nt long. The Berget group showed that when an exon is expanded beyond 300 nt, it is skipped even when neither splice site on the exon was altered  
        * However, this constraint does not explain the existence of pseudo-exons that are similar in size to authentic exons
        * Possibly, exon juxtaposition could then provide another potential point for regulating splice site specification
            * Exon juxtaposition: After initial binding of spliceosome components across exon splice sites, there then has to be a way for the exon definition complexes to be exchanged for cross-intron complexes for splicing to occur – converting exon definition to intron definition
    * Spatial proximity – all other factors being equal, proximal splice sites are favoured. On the other hand if the splice if the splice sites are too close to each other, splicing cannot occur – if the 5’ splice site is less than 48 nucleotides away from the branch point sequence, splicing fails (may be used to enforce mutually exclusive splicing) 
        * Reed & Maniatis (1986) – analysed in vitro splicing products of pre-mRNA containing tandem duplications of 5’ or 3’ splice sites of human beta globin IVS1. Internal splice site was found to be preferentially used
* Temporal restraints 
    * Temporal proximity – since splicing is co-transcriptional, the kinetic coupling model (Bentley 2014) suggests that 5’ introns are excised before 3’ introns as they are transcribed first, allowing spliceosomes to assemble on 5’ introns first 
        * In other words, splice site pairing is determined by which pairs are transcribed first 

# Recursive splicing reduces the amount of information needed to specify splice sites 

* Some introns contain recursive splice sites, which is composed of a 3’ splice site adjacent to a 5’ splice site 
* After the recursive splice site is spliced, the 5’ splice site is reconstituted, and the splicing is repeated to join the exons together. [diagram] 
* Evidence for RS sites comes from Sibley et al (2000), who used total RNA-seq data to demonstrate the existence of RS sites 
    * They observed a saw-tooth pattern of RNA accumulation across long introns, because as soon as the 3’ end of the intron is synthesised, splicing occurs and the excised intron is degraded, so the sequences at the 5’ ends of introns have a longer lifetime and accumulate more. In some long introns, a discontinuity in the saw tooth occurred in the middle of the intron, which corresponds to zero-length exons

# **Conclusion** 

* Information needed to specify authentic splice sites in mammalian cells appears to be provided by many sources outside of the sequence of the splice sites themselves: in regulatory _cis _elements; by genes encoding regulatory _trans _factors; by the regulatory networks that modulate expression of _trans_ factors; as well as spatial and temporal constraints. 
* These different sources may interact as well – Barash et al (2010) generated feature interaction networks based on unexpectedly frequent feature pairs; many of these pairs corresponded to authentic mechanisms, e.g. nPTB, Mbn1 and Cugbp binding sites all occur jointly in the 3’ region of introns upstream of exons included in CNS tissue 
* The information deficit problem in mammalian splice sites may reflect a larger theme in the evolution of more complex organisms, in that the specificity of molecular recognition is regulated via multiple mechanisms rather than by a single binding site. In fact, one could argue that the information deficit is an advantage to mammalian splicing in that it allows for this regulation, whereas if all splice sites were strong, there is little dynamic range possible in splicing frequency 
    * Could draw a comparison to non-specific IDRs, SLiMs, weak promoters in transcription, which are relatively degenerate binding sites, but the culmination of regulatory processes leads to specificity 
    * “Thhese degenerate consensus splice sites may be a key feature that allows the generation of diverse alternative splicing patterns”, and also allows for increased flexibility as the cell can modulate splicing (and other reactions) in response to a range of conditions
*  Remaining questions that may be explored relating to the information deficit may include 
    * How has solutions to the information deficit evolved over time in different species? Is this a problem unique to metazoans, or do e.g. plants and fungi also have this issue? 
    * What is the functional significance of linking splicing to chromatin structure? 
    * To what extent do the different factors that fill the information deficit contribute to splice site specificity? 