**Discuss the evidence for the “closed loop model” of an efficiently translated mRNA, and briefly comment on the implications this model poses for the regulation of translation.**

# What is the closed loop model? 

* 5’-3’ proximity induced by 4 interactions 
    * 5’ cap bound by cap binding protein eIF4E
    * eIF4E interacts with eIF4G 
    * eIF4G interacts with PABP 
    * PABP recognises 3’ poly(A) tail 
* In this way, regulatory effects at the 3’ end can be transmitted to the 5’ end via spatial proximity
* Closed loop  model proposed to increase efficiency of translation 

# #experimental_evidence  for closed loop model 

* Changes in poly(A) tail length affect 5’ end activities, suggesting that there is communication between the 5’ and 3’ ends of the mRNA 
* Increasing the length of the poly(A) tail is associated with increased cap-dependent translation initiation 
    * E.g. maternally-derived mRNAs have shorter poly(A) tails that are lengthened upon fertilisation. This leads to translational activation (Barkoff et al 1998, Gebauer et al 1994) 
* On the other hand, decreasing the tail length reduces translation efficiency and targets the mRNA for decay 
* Biochemical evidence
    * Each RNA element and RBP has been shown to bind to each other  
    * Studies showed synergy between cap and poly(A) tail – translation efficiency was compared for 4 mRNA substrates: an mRNA with both 5’ cap and poly(A) tail, mRNA with cap only, mRNA with tail only, and mRNA with neither cap nor tail. The mRNAs with cap or tail had higher translation efficiency than the mRNA with neither. However, the mRNA with both cap and tail had higher than expected translation efficiency for a mechanism where cap and tail independently increase translation efficiency. 
    * Yeasts lacking PABP undergo deadenylation-independent decapping
    * Tethering of PABP in yeast to 3’ UTR inhibits decapping 
    * Archer et al (2015) applied formaldehyde to live cells to cross-link protein-protein and protein-RNA. eIF4E, eIF4G and PABP1  co-purified with each other, suggesting that they interact. Then did pull down of each protein, isolated attached mRNA, and did RT-qPCR to determine where each protein interacted and extent of interaction with mRNA. eIF4E and eIF4G pull down were enriched for 5’ end of mRNA, while PAB1 enriched for 3’ end of mRNA 
    * Histone mRNAs lack 3’ poly(A) tail so cannot follow closed loop model. However, replication-dependent histone mRNAs have a 3’ stem loop that binds stem loo-binding protein (SLBP), which interacts with SLBP-interacting protein 1 (SLIP1), that in turn interacts with eIF4G. This stimulates histone synthesis 
* Genetic evidence
    * Disrupting interactions between RNA element and RBPs results in reduction in translation initiation 
        * E.g. Tarun et al (1997) found that a -459 mutation in eIF4E binding site of eIF4G1 is synthetically lethal with an N-terminal truncation that eliminates the PABP binding domain, but is not synthetically lethal with a shorter deletion that keeps PABP binding domain intact 
* Structural evidence 
    * AFM used to visualise closed loop architecture (Wells et al 1998) 
        * Circular mRNA formed only in capped and poly(A)-tailed model RNAs with all protein components of closed loop model present and when the interactions were possible (i.e. not affected by mutation) 
* Phylogenetic evidence 
    * Bannerman et al (2018) – Did genome and transcriptome wide analysis of proteins involved in mRNA processing and translation across six eukaryotic super-groups.
        * Interactions between RNA, proteins involved in closed loop model were found to be conserved across eukaryotes 
        * This suggests that the closed loop model is important to translation regulation in eukaryotes 
        * E.g. eIF4E, eIF4G homologues are found across parasitic kinetoplastids, Archaeplastida, and Opisthokonta groups 

# #experimental_evidence  for how closed loop enhances translation 

* There could be cooperative interactions between the 5’ and 3’ interacting factors, e.g. PABP enhances affinity of eIF4G for eIF4E and eIF4G binding to eIF4E enhances its affinity for 5’ cap; so mRNA in closed loop expected to have higher affinity for eIF4F cap-binding complex 
* PABP binding to eIF4G helps to ensure that eIF4F complex remains tethered to mRNA even if its contacts with 5’ cap are disrupted 

# #experimental_evidence  against closed loop model 



* Biochemical evidence 
    * Cap-tail synergy may not be due to formation of closed loop, as PABP can promote translation _in trans_ a capped mRNA without a tail. PABP enhances the affinity of the eIF4F complex for the cap even in the absence of a poly(A) tail 
        * Borman et al (2002) – Used a rabbit reticulocyte lysate in vitro translation system. When poly(A) chains of physiological length was added to capped, non-polyadenylated mRNA, it increased their translation efficiency. This suggests trans stimulation by poly(A) is possible, at least _in vitro_, so the synergy cannot be attributed to closed loop model alone 
    * Synergy may also simply be due to both the cap and tail protecting the mRNA from degradation 
* The model predicts that disruption of any of the 4 interactions will affect translation and mRNA stability 
    * However, perturbing PABP-eIF4G in _S. cerevisiae_ (by mutating eIF4G) does not cause lethality 
        * It was discovered that eIF4G has an RNA recognition motif that can bind 3’ UTR to circularise mRNAs 
            * Park et al (2011) deleting the PABP binding domain of eIF4G1 is in fact not sufficient for synthetic lethality with -459 mutation in eIF4E binding site, building on findings from Tarun et al (1997). The larger deletion, including the extreme N-terminus of eIF4G1 (termed RNA1) must be deleted along with the PABP binding domain to cause synthetic lethality. This suggests that RNA1 has an overlapping function as PABP binding domain. As it was previously shown to bind RNA, strongly suggest it binds to 3’ end of mRNA as well 
            * So PABP-eIF4G interaction is just one of multiple to close the loop 
    * Need additional experiments on the effect of disrupting eIF4E-eIF4G on translation efficiency 
        * Disrupting cap-eIF4E may have other consequences as it is an important step in mRNA decay 
        * Have to be able to differentiate between effect on translation initiation and effect on closed loop (since eIF4E-eIF4G required for initiation outside of role in closed loop) 
* Kaye et al (2009) – eIF4E-cap interaction does not increase binding affinity of purified eIF4F for mRNAs >60 nt in  length 
* What promotes closed loop interactions occurring in_ cis_ rather than in _trans_? 
    * So far, no evidence for an mRNA being regulated by 3’UTR and poly(A) tails from other transcripts
    * Current model must ensure that the 5’-3’ communication occurs in _cis_ and that it can reform in _cis_ if disruption occurs 
* mRNA 5’ and 3’ ends are intrinsically close without the involvement of RBPs, even in large mRNAs 
    * #experimental_evidence Lai et al (2018) introduced fluorophores at each end of mRNA and used FRET to show mRNA have an intrinsic tendency to fold such that the 5’ and 3’ ends are close to each other in the absence of any protein 
        * Used yeast and human mRNAs that encode housekeeping proteins and have well-annotated 5′ and 3′ UTR sequences e.g. GAPDH 
    * So rather than being required for closed loop, the RBPs just reinforce the inherent proximity of 5’ and 3’ ends. The closeness facilitates interaction between 3’ RBPs and 5’ cap binding proteins, rather than the other way around 
* Viral RNAs – not cellular mRNAs, but exhibit different mechanisms for 5’-3’ communication 
    * RNA-RNA interactions
    * RNA-protein interactions
    * Some viruses also recruit translation initiation factors to 3’ ends that are used to initiate translation at 5’ end 
* The the AFM study by Wells et al (1998) is the only direct structural evidence for the model
    * However, the RNA used was hybridised to a complementary DNA molecule that held the RNA in a looped out state. This could have affected the need for the RNA to be in a closed loop 

# Implications for regulation of translation 



* Disruptions to any interactions that form the closed loop results in sharp reduction in translation efficiency due to synergy between cap and tail (sigmoid?) 
    * E.g. repressive closed loop 
    * E.g. GW182-PABP interaction
        * However, translation of mRNAs that lack poly(A) tails can also be repressed by miRNAs, so this cannot entirely account for the effects of GW182
    * Point of regulation of translation efficiency – regulatory factors can modulate interaction, affinity between RBPs and mRNA 
* Have to consider whether other mRNA binding proteins compete with the cap-binding and tail-binding proteins, and if so, what affects binding priority/preference 
* mRNA decay will rapidly reduce translation efficiency due to removal of poly(A) tail and PABP1 even before decapping

# Remaining questions 



* Are 5’ and 3’ ends always attached? Or is it a transient interaction, in which case how long do they have to be attached? 
* How does translation affect 5’-3’ proximity 
    * smFISH studies showed that 5’ and 3’ ends are 90-200 nm apart for mRNAs >5000 nt long that are being translated, while mRNAs not being translated have ends that are only ~30 nm apart 