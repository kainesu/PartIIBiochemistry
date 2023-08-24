**Describe how mass spectrometry can be used to gain insight into multi-protein complex components.**

# Introduction 

Our knowledge of biological systems would be incomplete without a good understanding of proteins, which are the key actors that implement the instructions coded by the nucleus. However, studying the proteome can be challenging due to the greater diversity in chemical composition compared to nucleic acids. In particular, multi-protein complexes can be difficult to characterize given their large size and thus higher complexity compared to pure, monomeric polypeptides. Several approaches have been developed in mass spectrometry (MS) to elucidate the structure and function of the components in multi-protein complexes. 


# Native mass spectrometry and variants 

Since the discovery that noncovalent interactions can be maintained in the gas phase, native MS has been used to characterize the structure of intact protein complexes. In native MS, neutral conditions are used to preserve any protein-protein interactions in the complex, and the employment soft ionization methods such as electrospray ionization (ESI) and matrix-assisted laser desorption ionization (MALDI) also ensures that the complex remains intact during MS. Ultra high mass range mass spectrometers may be used for top-down analysis of large multi-protein complexes. 

Following m/z measurement of the intact protein complex, the complex is usually fragmented into its constituent subunits via collisional activation, then the m/z of the subunits are re-measured (tandem MS) to identify them (Figure 1). These subunits may undergo a further round of fragmentation to break them down into peptides, which would allow for identification of the precursor monomers. Belov et al (2013) employed this method with several protein complexes, including phosphorylase B and GroEL, and were able to map the peptide fragments obtained in MS3 back to the protein sequences of each complex. 

![[Pasted image 20230526010608.png]]
Figure 1: Tandem MS for multi-protein complexes. 

Tandem MS can also be useful in elucidating the architecture of the complex, specifically which protein subunits are core or peripheral to the complex. For example, Lorenzen et al (2007) used tandem MS to characterize the structure of an intact RNA Polymerase II complex. When the precursor ion was fragmented, it primarily led to the elimination of Rpb4, Rpb7, and Rpb4/7 heterodimer, which suggests that these subunits are likely to be on the periphery and also reflects the stable association between Rpb4 and Rpb7. This is because peripheral subunits are more exposed and thus more likely to dissociate first in tandem MS. A more extended approach involves gradually increasing the collision energy used and taking an MS reading at each stepwise increase in energy. Fandrich et al (2000) used this approach to dissect the structure of MtGimC, an archaeal protein involved in protein folding, and found that the protein is likely a pentamer with a core of two MtGimα subunits surrounded by three MtGimβ subunits on the periphery. 

Native MS could also more simply be used to determine the stoichiometry between different subunits in a complex. For homooligomers, the copy number of the subunits can be obtained by simply dividing the mass of the intact complex by the mass of the monomeric subunit, obtained via tandem MS. For heterooligomers, an additional MS step may be needed to determine the mass of each constituent subunit. Alternatively, the complex may need to be denatured chemically into its subunits which are then infused into the mass spectrometer. For larger and more heterogeneous complexes, calculations may be aided by computer algorithms such as MaxEnt or SUMMIT (**what do these do?**)


# Affinity purification - mass spectrometry (AP-MS) 

When not all the components in a multi-protein complex are known, AP-MS can be used to isolate the binding partners of a protein of interest and identify them. In AP-MS, the protein of interest is genetically modified by fusing it to an epitope that binds to a specific antibody, allowing it to be used as a “bait” in an affinity column (Figure 2). Possible epitopes include Flag, Myc, and HA tags. Cell lysate containing a mixture of proteins is then passed through the column, and any interacting partners will bind stably to the bait (the “prey”). Any non-specifically binding proteins are washed off, then all prey proteins are eluted out of the column and prepared for either top-down or bottom-up MS analysis. Two epitopes could also be used to minimize the presence of contaminating proteins binding to the column in place of the bait, and thus reduce the likelihood of false positives. This is known as tandem AP-MS. 
![[Pasted image 20230526010615.png]]

Figure 2: Schematic representation of AP-MS. **(note: bait should also be eluted)**

If the protein of interest is involved in only a single multi-protein complex, then the other members of the complex would simply be the list of prey proteins eluted through the column. However, many proteins are involved in alternative protein complexes, and a single AP-MS run cannot determine what proteins are in which complexes. This is important knowledge as a protein can have vastly different effects in a cell depending on what complex it is found in. Instead, reciprocal AP-MS has to be run on the prey proteins to generate a network of protein interactions (Figure 3). For example, Gingras et al (2005) used tandem AP-MS to identify several mutually exclusive protein phosphatase 4C (PP4C)-containing complexes. 
![[Pasted image 20230526010620.png]]
Figure 3: Reciprocal AP-MS on interacting partners of the bait protein can delineate which sets of proteins form a distinct complex.

Combining AP-MS with biochemical fractionation techniques (e.g. gel filtration, ion exchange) can further allow for the complete isolation and characterisation of a particular protein complex. 


# Cross-linking mass spectrometry 

Despite the development of native MS, some protein-protein interactions may still be too weak to survive lysis and purification before MS analysis. To resolve this, cross-linking methods have been developed to create stronger covalent crosslinks between interacting proteins in a complex that can survive to MS analysis. The choice of crosslinker is important – not only does it have to be reactive with proteins, but it has to be cell permeable and have an appropriate spacer length. Methods should also minimize undesired crosslinks to contaminating proteins. Vasilescu, Guo & Kast (2004) chose formaldehyde as a cross-linker to identify a novel binding partner of M-Ras. Cells expressing Myc-tagged M-Ras were treated with formaldehyde, then M-Ras was co-immunoprecipitated with any interacting partners with anti-Myc. Proteins were separated via SDS-PAGE, trypsinized, and subjected to liquid chromatography (LC)-MS/MS. In contrast, Kao et al (2011) chose disuccinimidyl sulfoxide (DSS) as a crosslinker to characterize the structure of the yeast 20S proteasome complex. DSSO contains two cleavable sites that break during collision-induced dissociation (CID), which allows for identification of DSSO-linked peptides. 


# Hydrogen-Deuterium Exchange (HDX)-MS 

While the above methods are used to investigate the identity and arrangement of the components in the multi-protein complex, HDX-MS can be used to probe the binding surfaces of interacting proteins in a complex. The principle of this method is that H atoms in the amide backbone of proteins will exchange with deuterium in D<sub>2</sub>O (if in liquid phase) or ND<sub>3</sub> (if in gas phase) if they are exposed to the surface. If the H atom is inaccessible due to it being buried in the protein, or because it is involved in an interaction, then it is exchanged more slowly. Hence, if we were to compare the deuteration of a protein of interest versus the protein and a binding partner, the parts of the protein that form the binding surface would be hypo-deuterated (Figure 4). This difference can be detected by MS as a molecule with a higher D/H ratio would have a greater mass. The hypo-deuterated peptide fragments can then be mapped back to the original protein to identify the binding surface. 
![[Pasted image 20230526010633.png]]
Figure 4: Schematic representation of HDX-MS. 

Mistarz et al (2019) demonstrated the utility of HDX-MS with several proteins, including cytochrome _c_ and α-lactalbumin. They found that monomers dissociated from protein dimers during CID had lower deuterium content than unbound monomers, suggesting that binding surfaces protect H atoms from deuteration. 

**also: use proximity tagging methods**. 

# Conclusion 

The wide range of MS methods developed over the years have allowed for unprecedented insight into the structure of multi-protein complexes and complement other kinds of structural techniques such as NMR, X-ray crystallography, and cryo-electron microscopy. In deciding which particular technique to use, the experimenter should consider the type of research question and equipment available. Although MS analysis suffers from some limitations, including low throughput, difficulty of analyzing membrane proteins, and the protein inference problem, the numerous experiments in the literature that employ MS techniques indicate that it will continue to be a powerful tool in proteomics. 

# Discarded 

**General References**

Heck & van den Heuvel (2004) 

[Gingras et al (2007) ](https://www-nature-com.ezp.lib.cam.ac.uk/articles/nrm2208)

[Hyung & Ruotolo (2012) ](https://analyticalsciencejournals.onlinelibrary.wiley.com/doi/full/10.1002/pmic.201100520?casa_token=GXpS4dy1Va8AAAAA%3A9AzPMviRva-MzItt56S-GziLQXKtf2r2I6RQBDWdTf4Z5jVwFVs7mQmy_qNpvPasq-XR2aUZ8Rr-pEQ)

[Heck (2008) ](https://www-nature-com.ezp.lib.cam.ac.uk/articles/nmeth.1265)

**Planning **

Explain how the method works → give experimental examples → state what the experiment found → explain how the MS approach was used to determine the conclusion. 



* Native MS
    * Ultra high mass range MS
        * E.g. Loo et al. (2005) used native MS to characterise the structure and stoichiometries of the 20S proteasomes from Methanosarcina thermophila and rabbit, and found that mammalian proteasomes have higher heterogeneity than prokaryotic ones. 
        * E.g. van de Waterbeemd et al (2018) used native mass spectrometry to characterise the structure of ribosomes 
        * E.g. Lorenzen et al (2007) used native MS to characterise structure of an intact RNA Pol II complex. The precursor ion was separated into its constituent subunits via collision, and their masses measured in MS2. 
    * E.g. Rostom and Robinson (1999) confirmed the structure of GroEL using ESI MS 
    * To study cooperativity 
        * E.g. Rogniaux et al (2001) 
    * E.g. [Pinkse et al (2003)](https://analyticalsciencejournals.onlinelibrary.wiley.com/doi/full/10.1002/jms.443?casa_token=11S7wPD_gY4AAAAA%3AFx_sRvziNMb-7_Dqojg7DuYADwogV6i2ioNmTB3KvtAOtLGfPgSrrGvNW8I-Fire4V423LpLLujXiOE) used nanoflow ESI MS to establish that the _H pylori_ urease complex has a dodecameric structure 
    * [Belov et al (2013)](https://pubs.acs.org/doi/full/10.1021/ac4029328?casa_token=7y41cSG-TEYAAAAA%3ACs9f8j83x1vnNUbbVkzaRZTjCZltzYH4KlgkKRVZGTgN8UnbOeAwncHcQM4-DfrHU2XSybfXYxQOqS0) present a two-step fragmentation MS (MS<sup>3</sup>) that breaks down a native protein complex into its constituent subunits, which are then broken down further into peptides. Their approach was applied to characterize several protein complexes such as GroEL, phosphorylase B, pyruvate kinase. 
* Determining stoichiometry 
    * For homo oligomers, obtained mass is divided by mass of monomeric subunit. Validate copy number using MS/MS to break the complex down into its subunits 
    * For heterooligomers, an additional MS step is required to determine the mass of each constituent subunit (such as by tandem MS/MS, or by MS analysis of a denatured complex). 
    * However for larger and more heterogenous complexes, more complex MS workflows may be necessary aided by computational algorithms e.g. MaxEnt, SUMMIT 
* Determining which subunits are core and which are on the periphery 
    * Peripheral subunits are more exposed → dissociate first during MS/MS → by increasing the acceleration gradually and analyzing the fragments in each step, can identify which subunits are peripheral 
    * E.g. [Fandrich et al (2000)](https://www.pnas.org/doi/10.1073/pnas.240326597) used MS in this manner to study the arrangement of subunits in the protein complex MtGimC 

**AP-MS**



* If not all components in a multi protein complex are known, AP-MS can be used to capture all binding partners of a protein of interest and identify them 
* However if the bait protein is involved in alternative protein complexes, a single AP-MS run cannot determine what proteins are in which complexes, which is important as a protein can have different effects in different complexes 
    * Instead, reciprocal AP-MS has to be done with the prey proteins to generate interactome networks 
        * E.g. Gingras et al (2005) – used tandem AP-MS to identify several mutually-exclusive protein phosphatase 4C (PP4C) -containing complexes 
* Combining AP-MS with biochemical fractionation techniques (e.g. gel filtration, ion exchange) can allow for complete isolation and characterisation of a particular protein complex 

**Cross linking **



* Some protein-protein interactions are too weak to survive lysis and purification necessary before analysis by MS 
* Choice of crosslinker is important – must be cell permeable, reactive, and have an appropriate spacer length 
* Also must minimize undesired crosslinks to contaminating proteins 
* E.g. Vasilescu, Guo & Kast (2004) treated live cells with formaldehyde to form protein-protein cross links. Myc-tagged proteins could then be pulled down with any cross-linked interacting partners, then partners are separated via SDS PAGE and identified using tandem MS. They used this method to identify a novel binding partner of M-Ras. 
* E.g. [Kao et al (2011)](https://www.mcponline.org/article/S1535-9476(20)31372-4/fulltext) used a DSSO cross linker to characterize the structure of the yeast 20S proteasome complex. 

**Hdx ms **



* E.g. [Canet et al (2002)](https://www-nature-com.ezp.lib.cam.ac.uk/articles/nsb768) – used HDX-MS to investigate which part of an amyloidogenic lysozyme mutant is involved in cooperative unfolding, and thus contributes to the formation of fibrillar structures 
* Can be used to probe binding surfaces of protein interacting partners in a complex 