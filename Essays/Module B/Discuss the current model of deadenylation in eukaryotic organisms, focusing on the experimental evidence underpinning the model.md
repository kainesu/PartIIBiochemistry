**<span style="text-decoration:underline;">Discuss</span> the current model of deadenylation in eukaryotic organisms, <span style="text-decoration:underline;">focusing</span> on the <span style="text-decoration:underline;">experimental evidence</span> that underpins the model. (2022 Paper 2)**

**Explain how each of the main experimental techniques described in this essay work:** 
* Transcription pulse-chase 
* TAIL-Seq 
* Bulky poly(A) assay 
* RNAi 

Etc 

# Intro 
* Why cells degrade RNA
* Deadenylation = removal of poly(A) tail from 3’ end 
* Role of deadenylation 
    * Deadenylation is the first step in the canonical mRNA degradation pathway and is thus important in regulation of the pathway
* Brief summary of the current model 

**summary diagram of interactions**

# Body 

* Deadenylation is mediated by deadenylases, which are 3’ → 5’ exoribonucleases that catalyse RNA hydrolysis, with preference for poly(A) as the substrate [(Yan, 2014)](https://www.zotero.org/google-docs/?1VD4pj)
    * In yeast, there are at least 4 types of deadenylases, CCRF, CAF1, PAN2, ANGEL and that are highly conserved among eukaryotes 
    * KO of specific deadenylases does not affect poly(A) tails globally but only specific subsets of mRNA 
    * Subcellular localisation of deadenylases means that different deadenylases are used in different compartments 
        * CCR4, CAF1, PAN2, PARN, etc are nuclear-cytoplasmic shuttling proteins and function in both the nucleus and cytoplasm 
            * CCR4, CAF1, PAN2, mainly in cytoplasm 
            * Most PARN in nucleus 
        * CCR4d and CAF1 concentrated in Cajal bodies in nucleus 
        * PDE12 is mitochondrion-specific deadenylase 
    * There are also non-specific exonucleases that can act on poly(A) tails 
* In the canonical decay pathway, degradation of the mRNA is initiated by deadenylation, which leads to decapping by Dcp1-Dcp2 complex and subsequent 5’ to 3’ exonuclease digestion by Xrn1 enzyme. Alternatively, if this pathway is compromised, the mRNA can be degraded from the 3’ end by the exosome complex after deadenylation 
* In the canonical model of deadenylation, deadenylation is biphasic. 
    * Biphasic model of deadenylation:
        * Tet-off **transcriptional pulse-chase experiments **show that mammalian deadenylation exhibits biphasic kinetics (Yamashita et al 2005) 
            * “in proliferating NIH3T3 cells, the stable β-globin (BBB) mRNA had biphasic decay kinetics. In the first phase (0–3 h), the transcript underwent a slow and synchronous deadenylation without decay of the RNA body. When the poly(A) tail was shortened to around 110 nucleotides (nt), deadenylation became less synchronous, leading to decay of the mRNA body.” 
            * The first phase exhibits kinetics consistent with distributive enzymatic digestion. The enzyme dissociates from the poly(A) tail after hydrolysing only a few nucleotides before switching to another tail. The mRNAs undergo slow, but fairly synchronous deadenylation
            * The second phase exhibits kinetics consistent with processive digestion, where the enzyme nearly completely hydrolyses the poly(A) tail before switching. The mRNAs undergo less synchronous deadenylation, with a wide size distribution in the poly(A) tail of 110 to 10 nt 
* Initial trimming of poly(A) tail by PAN2/3, which is then continued by CCR4-NOT
    * Yamashita et al (2005) – ”Overexpression of wild-type PAN2” resulted in the observation of mRNA with “poly(A) lengths ranging from full-length to less than 20 nt even at the initial time point, indicative of immediate access and action by PAN2. By 1 h nearly all the mRNA was poly(A)− and decay of the RNA body was underway”. On the other hand, when CCR4a was overexpressed, the first phase of kinetics was still observed, but it was shortened to 1h and “was followed immediately by the onset of the second phase of deadenylation”
    * Webster et al (2018) incubated recombinant CCR4-Not with RNA substrate with a 30(A) tail, +/- PABP. Tail length was resolved over time using denaturing PAGE; presence/absence of PABP did not affect deadenylation.
    * Tucker et al (2001) observed using transcriptional pulse-chase analysis that “MFA2pG mRNA was stabilised approximately 2- to 3-fold in ccr4Δ and caf1Δ [yeast] strains compared to wild type”
* However as residual deadenylation was still observed in caf1Δ ccr4Δ strains, they constructed a ccr4Δ/pan2Δ double mutant. Transcriptional pulse chase found that transcripts did not undergo any significant shortening of the poly(A) tails 
* With CCR4-NOT as the dominant deadenylase complex. 
    * Yi et al (2018) – RNAi depletion of Caf1 (CCR4-NOT) or Pan2 in HeLa cells followed by TAIL-seq found that  Caf1 depletion leads to most mRNAs gaining elongated poly(A) tails, particularly cytosolic mRNAs.
    * Yamashita et al (2005) showed that when CCR4 is overexpressed, it can compensate for the loss of PAN2/3
* CAF1 and CCR4 in CCR4-NOT alternate in deadenylating the poly(A) tail 
    * Yi et al (2018) – in human cell lines transfected with mutant CCR4 but with wt CAF1, bulky poly(A) assay suggested the formation of deadenylation intermediates in CCR4 suppressed cells. 
        * Each PABPC molecule protects a poly(A) segment of 23-27 nt, suggesting that the pattern is due to PABPC binding 
* Mechanism. CAF1 appears to trim naked poly(A) segments, but is blocked by PABP
    * Yi et al 2018 – RNAi of CCR4 shows footprinting consistent with PABP (using bulk poly(A) assay) 
* Mechanism. CCR4 is activated by PABPC to shorten PABPC-protected sequences
    * Yi et al 2018 – RNAi of CAF1 resulted in reduction in adenylation in absence of PABPC1, but deadenylated with PABPC1 present 
* CCR4 is needed and has the ability to remove PABP from RNA, unlike CAF1
    * Webster et al (2018) performed deadenylation assays with point mutants in nuclease active sites; Caf1(D53A) had no effect on deadenylation in the presence of PABP1, while Ccr4(E387A) reduces deadenylation in the presence of PABP1
* More recently, a modification to the biphasic model was discovered, as it was found that short poly(A) tails have slower deadenylation than longer poly(A) tails 
    * This could be due to protection by La ribonucleoprotein 1 
    * E.g. Park et al (2023) identified La ribonucleoprotein 1. They measured the steady state and pulse-chased distribution of poly(A) tail lengths using various seq methods (e.g. TAIL-Seq). They found that deadenylation is slower then the tails are 30-60 nt long. LARP1 knockdown globally reduced mRNA abundance. 
    * Mechanism. LARP1 blocks CCR4-NOT deadenylation _in vitro_ via interaction with PABP and poly(A) 
* However, this biphasic model of deadenylation triggered by the canonical mRNA decay pathway does not sufficiently account for all instances of deadenylation in eukaryotic cells. Firstly, Deadenylation can also be triggered by other pathways… 
    * ARE-directed decay 
        * See notes for experimental evidence 
    * Decay mediated by destabilising elements in protein-coding regions 
    * Nonsense-mediated decay 
        * Biphasic kinetics also observed 
        * Accelerated deadenylation is caused by recruitment of Pan3 by PABP. In mRNA with a premature termination codon, an exon junction complex (EJC) deposited in the middle of an ORF is not removed by a translation elongation complex, and this EJC causes alteration of the termination complex, preventing component eRF3 from interacting with PABP, thus increasing interaction with Pan3 (?) 
    * miRNA-mediated decay – recruitment by GW182 
* Eukaryote deadenylation is also regulated, which would affect the kinetics of deadenylation. 
    * Codon usage 
        * CCR4-Not is a sensor for slow translation due to the use of non-optimal codons → affects rate of initiation of deadenylation 
        * See evidence from Presnyak et al (2015), Buschauer et al (2020)  in notes 
    * Trans-acting factors (e.g. proteins with IDRs) (Yan, 2014) 
        * Many trans-acting decay factors (including TTP) interact with hydrophobic grooves on CCR4-NOT via IDRs that recruit CCR4 via Not1- scaffold as well as non-enzymatic subunits 
        * Deadenylases are usually targeted to specific RNA via binding partners → point for regulation 
            * PARN can interact with 5’ cap structure directly
            * Cytoplasmic polyadenylation elements (CPEs) can recruit CPE binding proteins (CPEBs) that in turn can recruit PARN directly or CAF1 indirectly via TOB/BTG proteins 
            * PABP family proteins can recruit PAN2-PAN3 directly and CCR4-NOT complex indirectly via TOB/BTG proteins 
            * AU-rich elements (ARE) binding proteins can recruit deadenylases e.g. Tristetraprolin recruits CCR4-NOT by interacting with hydrophobic grooves on CCR4-NOT
    * Phase separation 
* Moreover, non-biphasic kinetics of deadenylation have also been observed… (where?)

# Conclusion

* Importance of experimental techniques in understanding models of deadenylation
    * Particularly development of new technologies e.g. massively parallel sequencing, RNAi improves resolution of poly(A) tail and manipulability of cells, allowing for new insights into deadenylation 