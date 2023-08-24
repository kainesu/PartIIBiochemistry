**What mechanisms in the secretory pathway facilitate efficient quality control in protein folding and protein targeting?**

Is there an upper limit to the accuracy of a single molecular process? 

* What is QC? QC is a collection of processes that survey proteins for correct folding and localisation. Those that are not correct are targeted for degradation. 
* QC stringency – if too low, can accumulate faulty or mislocalised products. But if too high, or overly promiscuous, may target functional proteins for degradation which is wasteful 

# **Introduction**

Fidelity is a hallmark of the central dogma, with faithful transfer information from DNA to RNA to protein necessary for a functional cell. These fidelity-guaranteeing processes continue into post-translational processes of protein folding and localisation. As every molecular process is prone to error, cells have evolved quality control mechanisms to correct errors in protein folding and targeting. In protein folding, quality control mechanisms generally involve cycles of folding and refolding. In protein targeting, quality control mechanisms are more diverse, and may require inputs of energy or changes to activation energy. This essay will discuss how these different mechanisms lead to quality control, which are essential to the maintenance of homeostasis. 

* Accurate target selection is very challenging due to the diversity of the proteome. How can the cell recognise what is “correct” for a certain protein? A feature that may be considered a defect for one protein may be considered “normal” for another protein, e.g. exposed hydrophobic patch – wrong for a globular protein, but could be correct for an integrated membrane protein 
* In addition, the frequency of defective/mislocalised proteins is very low compared to those that are “normal”. QC machinery is more likely to encounter a normal protein than a defective one, so discriminatory power has to be high to avoid inadvertently targeting a normal protein 
* During maturation, polypeptides have to be protected from degradation – QC machinery have to “time” a grace period 

General principles: Combination of biochemical features, local context, cellular location, and time to target aberrant proteins for degradation 

Surveillance + commitment 

# **1. Quality control mechanisms in protein folding**

## General principles
* For proteins targeted by SRP, protein folding takes place co-translationally in the ER; those that are targeted post-translationally are folded in 
* Most proteins fold correctly, assisted by chaperones and post-translational modifications that help to restrict the search space of a polypeptide (i.e. Levinthal’s Paradox) 
* Misfolding leads to exposure of hydrophobic patches, risking formation of toxic aggregates. 
* The native conformation of a protein is the structure with the lowest energy, i.e. the global minimum. However as proteins can take many folding pathways, it is possible that it can stochastically fold into an incorrect structure (folding intermediate) at a local energy minimum. 
    * Analogy to Pachinko 
    * Folding also relies on many weak interactions and amino acid contacts that can be far apart 
* Proteins may also misfold due to mutation, errors in transcription/translation, and cell stress 
* To correct these misfolded proteins, quality control mechanisms in the cell generally involve refolding of the protein. 
    * Mathematically, the proportion of misfolded proteins after each round of refolding should fall exponentially. If x% of proteins remain misfolded in each round of re-folding, then the proportion of proteins that are still misfolded after y rounds of folding = (x/100)<sup>y</sup> (could draw a diagram for this) 
        * Round 1. 5% of proteins are misfolded → go back to start
        * Round 2. 5% * 5% = 0.25% 
        * Round 3. 0.25% * 5% = 0.0125% 
    * As such, refolding is a simple way of reducing error 
    * Advantage of this mechanism – less energy…? 
* Of course, given the multitude of proteins produced in the cell, there is still a miniscule proportion of proteins that do not fold. For these recalcitrant proteins, “last resort” mechanisms exist which degrade the proteins. 
    * What is the number of times a protein can be refolded before it is sent for degradation? 
* Under stress, QC pathways can fail, which triggers a global unfolded protein response (UPR). 

## Mechanisms 
* Disulphide bond formation 
    * PDI 
    * Many other oxidoreductases in ER
        * ERp57 – performs similar role to PDI, but binds to CNX/CRT to act as an oxidoreductase for glycoproteins 
            * Also act as thiol oxidoreductase of heavy chain oxidation in MHC class I biogenesis 
        * ERp44 – localised to ERGIC, engages in folding/oligomerization or retention of some proteins in ER  
    * Some oxidoreductases have specific function, some have redundant functions; function is inferred from binding partners, which define their substrate specificity and localisation 
        * KO of some oxidoreductases are non-lethal in mice e.g. ERdj5, while some are lethal e.g. ERp57
* Glycosylation 
    * Glycans are very hydrophilic. If a protein is glycosylated, it won't fold into the interior, and will want to be retained on the exterior of the protein, thus restraining the conformations that the protein can access
    * N-glycan, calnexin/calreticulin cycle 
        * #structural_evidence crystal structure of bacterial OST shows that peptide substrate is bound as a constrained loop, so in motif Asn-X-S/T, P cannot be in second position as it will form a kink in the peptide chain. Also explains why OST can only transfer N-glycan to an unfolded protein 
        * #experimental_evidence Experiments on vesicular stomatitis virus G (VSVG) and influenza HA glycoproteins
        * Mannosidase I trimming – removal of first mannose results in a glycan structure shared between folded proteins exiting ER and ER-retained misfolded proteins, so Mns1 does not differentiate between diff protein structures 
    * O-glycan 
        * O-mannosylation in ER – single mannose residue linked to S/T hydroxyls in alpha configuration 
            * Glycan can be extended further in Golgi 
            * Mannosyl donor = Dol-O-Man. Made on cytosolic side of ER, flipped to luminal face 
            * O-mannosyltransferase protein transfers mannose from Dol-P-Man to peptides 
        * Various functions, depending on protein 
            * Maintain substrate solubility e.g. KHN
            * Retain in ER e.g. misfolded Gas1
            * Inhibit ERAD e.g. Non-glycosylated pro-alpha factor 
        * Also may  terminate futile protein folding cycles
            * ER-GFP in yeast cells is O-mannosylated, but fast-folding variant of GFP is not. Elimination of O-mannosylation _in vivo_ allowed ER-GFP to fold to completion. 
            * In vitro assays – O-mannosylated ER-GFP cannot fold, but non-modified form folds 
            * O-mannosylation also prevents interaction with yeast BiP → remove substrates from protein refolding 
            * Unclear if also applies to mammalian cells 
* BiP/GRP96 system
    * BiP is an ATPase. ADP-bound BiP has high affinity for substrates where the hydrophobic region is closed. This prevents unfolded proteins from forming aggregates 
* Conformational protein determinants are recognised by ER to Golgi cargo receptors for export to ER. Unfolded proteins expose hydrophobic patches, which are recognised by ER chaperones for retainment in the ER for refolding or degradation 
* ERAD – last resort step. Terminally misfolded proteins are retained in ER and degraded to prevent continuously unsuccessful folding and <span style="text-decoration:underline;">accumulation</span> of misfolded proteins (if we allow too many refolding steps, will accumulate in ER) 
    * Currently we don’t know how ERAD discriminates between correctly folded proteins, folding proteins, or those that cannot be folded correctly. ManI/EDEM2 disrupts calnexin cycle to remove mannose, and send non-folding proteins to ERAD, but don’t know this is regulated. If they do it too early, risks destroying functional proteins, but if too late, then misfolded proteins accumulate. 
        * Proteostasis (protein homeostasis) – balance between protein folding and degradation (ERAD) determines probability that proteins fold into their native structure? 
        * In yeast, yeast osteosarcoma 9 (Yos9) is required for glycoprotein ERAD. OS9 in mammals. Yos9/OS-9 or XTP3-B lectins deliver proteins to dislocation machinery for degradation
            * Sequential reactions by glucosidase I, glucosidase II, and mannosidase I may set a timer for protein folding. Unfolded proteins detected outside this window (i.e., with the N-glycan without 2 Glc and 1 Man), are vulnerable to further glycan modification and ERAD 
                * So all proteins that take long to fold are sent to ERAD. This does not differentiate between irreversibly misfolded proteins or just slow folding proteins. This causes some waste but as misfolded protein can be toxic, it may be an acceptable tradeoff to maximise fitness 
        * In mammals, proteins retained longer in calnexin recycle may have higher probability of having a mannose trimmed by ER-mannosidase I (mannose timer model) 
            * So higher rounds of folding increases probability of degradation 
            * Trimming by mannosidases may increase hydrophobicity of misfolded proteins. Trimming also makes them successively poorer substrates fo UGGT and GII
            * Substrates with expired mannose timer are committed to degradation as they are prevented from further rounds of refolding 
            * Trimmed N-glycan recognised by OS9 or XTP3-B lectins. They both associate with HRD1 E3 ubiquitin ligase via SEL1L protein. 
            * Folding status of polypeptide may also be checked by retrotranslocation directly (Shan & Hedge 88) 
                * Checking by both OS9/XTP3B and retrotranslocon sharpens discrimination; prevents degradation of folded proteins or maturing proteins 
            * Relative rate of glycan trimming and mannose trimming prioritises folding over degradation. Proteins are allowed multiple rounds of refolding via cycles of glucosylation and removal, while mannose trimming limits number of refolding rounds 
                * There is also competition between lectins and glycoprotein-modifying enzymes since binding is mutually exclusive. Some proteins may have higher binding affinity for UGGT and/or CNX/CRT, which decreases interaction with GII and mannosidases 
                * So length of mannose timer is not absolute, but does set an upper limit 
            * Unfolded, non-glycosylated proteins are recognised by ER chaperones, mostly BiP. Retention time of substrate by BiP determines fate; prolonged retention may recruit BiP cofactors involved in ERAD, e.g. ERdj4/5
            * Second mannose timer may be set by may be set by slow mannosylation of S/T by ER mannosyltransferases. This modification prevents further refolding. 
                * Only been shown with an artificial substrate, so unsure how timer might work in vivo 
    * Proteins have to be retrotranslocated back into cytosol for ubiquitination then proteolysis by proteasomes 
        * Unclear what mediates retrotranslocation, maybe Sec61, Der-1(yeast)/Derlin-1(mammals), or Hrd1p? 
            * Reconstitution essay with fluorescently labelled substrate showed Derlin-1 can mediate substrate retrotranslocation (Wahlman 2007)
            * Reconstitution of Hrd1 minimal system – Hrd1, Ubc7-Cue1, Cdc48 complex, Ufd1-Npl4. In proteoliposomes, complex binds to unfolded substrate, ubiquitylated it and extracts it 
        * Cdc48 (p97/VCP) recruits E3 ligases 
    * Proteins are labelled for degradation by an E3 ligase
        * In yeast, there are two major Membrane-associated E3 ligases, Doa10p and HRd1p 
            * Doa10p is for substrates with misfolded regions on cytosolic side 
            * Hrd1p act on substrates with defect in luminal region
            * Both can act on misfolded membrane proteins 
            * After ubiquitination, pathways converge on complex consisting of ATPase Cdc48p, and two cofactors Ufd1p and Npl4p 
        * In mammals, there are more diverse ERAD E3 ligases, perhaps for monitoring more specific classes of substrates 
    * In cytosol, glycoprotein is deglycosylated, chaperones prevent protein aggregation and deliver it to proteasome. 
    * Misfolded proteins that inadvertently get exported to Golgi may be glycosylated with α-1,6-linked mannose residues which marks them as unfolded. They may be retrieved from the Golgi to ER for ERAD 
        * Some cytosolic glycans released from ERAD substrates contain Golgi modifications 
        * In HeLa cells, ManI found to be localised to Golgi and contribute to retrieval 
        * It may be the case that retrieval is obligatory for some substrates
* Other degradation pathways for specific proteins 
    * Aggregated Type I collagen is degraded by autophagy, while non-aggregated forms subjected to ERAD 
        * If ERAD or proteasomal activities not functional, autophagy is triggered by UPR pathway components 
    * EDEM1 is also degraded via autophagic-like pathway 
        * Electron microscopy studies – EDEM1 localised in double-membrane buds outside ER exit sites 
        * Degradation pathway for EDEM1 allows excess EDEM1 (and some other ERAD components) to be synthesised, so that there is extra ERAD factors at steady state, perhaps in case ERAD needs to be activated 
* UPR response 
* TMD insertion 

# 2. Quality control in protein targeting

## General principles

* In the secretory pathway, proteins move from the cytoplasm to the ER, from the ER to the Golgi and finally from the Golgi to the cell membrane for release from the cell 
* Each transport step requires the protein to be targeted to the next destination compartment accurately 
* Multiple mechanisms are involved in each protein targeting step to reduce the chance of error. 
    * What’s the advantage of doing it this way? 
* These mechanisms involve the use of energy. Since protein targeting restricts the number of states the molecules can be in, energy input is required to overcome the decrease in  entropy. 
    * Targeting converts transport from a random walk to a biased random walk 

## Mechanisms 

* Conformational proofreading  
* Antagonistic binding 
    * NAC 
    * TM2 helix in Sec61 
* Kinetic proofreading (by GTPases) 
    * Kinetic proofreading uses energy to convert small differences in binding energy into sharp differentiators of substrate (ref machinery of translation essay) 
    * Competition between ubiquitinases and deubiquitinases
        * #experimental_evidence the HIV-encoded membrane protein Vpu mediates degradation of CD4 protein from ER by recruiting SCF<sup>βTrCP</sup>. Point mutations that weaken interaction between Vpu, CD4 reduce ubiquitination. When this system was reconstituted _in vitro_, mutations had no effect. This suggested additional factors were involved in discrimination. When a promiscuous deubiquitinase was added to the system, difference in polyubiquitination between wild-type and mutant interactions were enhanced by 10-fold 
        * Extent of polyubiquitination is determined by the length of time the protein is attached to the ligase. If it dissociates, there is competition between DUB and ligase reassociation. If DUB binds first, protein is completely deubiquitinated. If the ligase binds first, the ubiquitin chain is extended. 
        * Binding of other proteins affects kinetics of these two competing interactions. E.g. binding of coat proteins or export receptors for ER exit may sterically exclude ubiquitin, thus favouring non-ubiquitinated state. On the other hand, polyubiquitin binding factor e.g. Cdc48 initiates dislocation into cytosol by preventing removal of ubiquitin. 
        * Threshold for QC can be modified by DUB activity; lower DUB activity means more promiscuous degradation 
    * SRP-SR pathway 
    * Rabs 
    * Sar1p
* Degradation 
    * Targeting to ER can fail, resulting in a mislocalized protein. 
    * Proteins mislocalized to ER are recognised by hydrophobic target element by Bag6. Bag6 recruits E3 ligase RNF126 for ubiquitination
    * Bag6 is selective for lengthy hydrophobic domains, allowing it to discriminate between ER-targeted proteins and cytosolic proteins 
        * How does bag6 mediate degradation without competing with targeting factor? 
            * Spatial constraints. 
            * SRP is attached to ribosome, so binds to proteins first for targeting 
            * Bag6 also attaches to ribosomes but cannot interact with proteins cotranslationally 
            * Kinetic constraints
                * When released from ribosome, TMD-containing proteins favour binding to SGTA. SGTA transferred to TRC40 via Ubl4A-Bag6-TRC35 (mammal) complex. This ensures protein transfer occurs in the proximity of Bag6 
                * Proteins prefer to bind to TRC40, and this binding occurs rapidly. This commits protein to targeting as it facilitates dissociation from TRC35. If TRC40 is unavailable or substrate is not optimal, Bag6 binding favoured. 
        * Bag6 commits substrates to degradation. N-terminal Ubl domain recruits RNF126 
        * Bag6 is relatively promiscuous, allowing it to capture most elements that should have been captured by targeting factors. Only SRP/TRC40 prevents degradation. 
* Catalysis 
    * SNAREs – SM proteins, NSF and SNAP 
* Tethering – “pre-selection” of vesicles for targeting 
* Re-capture and recycling to catch any mis-targeted proteins 
    * AP1 and AP2 

# **Conclusion **

* Quality control pathways exemplify the ordered nature of cells 
* Quality control mechanisms can still go wrong → disease 
    * QC defects particularly acute in neurodegenerative disease – neurons long-lived, so sensitive to accumulation of defective proteins over time 
    * Chemical chaperones for stabilising mutant proteins 
        * E.g. 4-PBA – beneficial for some misfolding-related disease e.g. cystic fibrosis 
* Unanswered questions 
    * How do quality control components recognise unfolded proteins? 
        * In O-mannosylation, we don’t know 
* Numerous processes have to take place that a protein is synthesised, folded, and localised correctly. If each step even has a small error rate, the number of incorrect proteins will compound. This makes error correction vital 