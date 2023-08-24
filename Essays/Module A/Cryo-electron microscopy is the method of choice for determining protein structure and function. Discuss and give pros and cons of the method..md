**Cryo-electron microscopy is the method of choice for determining protein structure and function. Discuss and give pros and cons of the method.**

# Introduction 

Since its first usage in the 1980s, cryo-electron microscopy (cryo-EM) has increasingly become the preferred technique for structural biologists. By plunge-freezing the protein sample in liquid ethane, the proteins are embedded in a layer of vitrified water, and 2D images of the protein can be obtained via electron microscopy, which can then be combined and processed computationally to reconstruct a 3D structure of the protein at high resolution (Figure 1). Due to its speed and because it obviates the need for  crystallisation, there have been predictions that cryo-EM is likely to become the dominant method for studying protein structure and function. However, cryo-EM is not a perfect technique and should be seen as complementary to existing techniques, mainly X-ray crystallography and NMR. 
![[Pasted image 20230526005616.png]]

Figure 1: Schematic representation of cryo-EM process. 

# Advantage 1: Cryo-EM is the fastest technique for obtaining an initial protein structure. 

Cryo-EM is capable of obtaining a low to medium resolution density structure in just a few hours. This makes it highly suitable for proteins with unstable structures, which may denature over long sample preparation and data acquisition periods. In contrast, X-ray crystallography tends to take a long time due to the long process of optimising the protein for crystallisation, screening for suitable crystallisation conditions as well as growing sufficiently large crystals for diffraction. Similarly, solving a structure from NMR data can take several weeks, with a high degree of user intervention to obtain a suitable structure. As such, when fine structural or mechanistic details are not necessary for the study, or when there is a need to obtain a structure rapidly, cryo-EM may be the most suitable technique. For example, earlier in the Covid-19 pandemic, there was an urgent need to determine the structure of the SARS-CoV-2 spike (S) protein to better understand how to combat the disease. Most of the solution structures of S protein currently in the Protein Data Bank (PDB) were obtained through cryo-EM. This shows how the speed of cryo-EM can be leveraged to address urgent biological questions. 

# Advantage 2: Cryo-EM provides realistic protein structures that are likely to resemble the structure in the protein’s native environment. 

Since the protein is captured in vitrified water, the protein structure will be as close to its natural environment as possible, with no dehydration or staining involved like in conventional EM. The protein is also not forced into the highly ordered conformation of a crystal, which may even require modification of the protein in some cases for it to be crystallisable (e.g. truncation of disordered domains, mutations of certain residues). There is minimum damage to the protein as well due to radiation damage. The development of cryo-electron tomography (cryo-ET), in particular, will allow cryo-EM to achieve the peak of realisticness as it would be able to acquire structures _in situ_ rather than in a purified form. In cryo-ET, a tilt series of 2D images of the sample is taken, with each image taken at a different angle, and a tomographic 3D structure is reconstructed from these images computationally (Figure 2). 
![[Pasted image 20230526005629.png]]
Figure 2: Schematic representation of cryo-ET. 

[Albert et al (2017)](https://www.pnas.org/doi/abs/10.1073/pnas.1716305114) used cryo-ET to image cytosolic and nuclear proteasomes directly within cells, allowing the researchers to demonstrate that nuclear proteasomes tether to the nuclear pore complex, as well as the mechanism for this tethering interaction. By combining structures obtained from single particle cryo-EM with the images obtained via cryo-ET, structural biologists can obtain detailed information about protein structures as they exist in their local environment. This is important as protein function can often be context-dependent and structures can be affected by where the protein is in the cell, as well as what interactions the protein has with other molecules in its environment. 

# Advantage 3: Cryo-EM can be used to acquire the structures of a wider range of proteins as they do not have to be crystallisable 

The biggest hurdle for X-ray crystallographers is to obtain a crystal structure of the protein. This can be challenging for certain kinds of proteins that do not lend themselves to an organised arrangement, such as fibrous proteins or proteins with disordered regions, but cryo-EM is able to obtain a structure for such proteins. Fitzpatrick et al (2017) demonstrated the versatility of the technique by obtaining the cryo-EM structure of tau filaments from Alzheimer’s disease at 3.4-3.5Å resolution. These filaments have a core region made up of repeating units as well as disordered regions towards the N and C-termini, which would likely have made it difficult to crystallise. In addition, disordered regions tend to “disappear” in the diffraction pattern obtained via X-ray crystallography because of the low average electron density. 

Membrane proteins have often posed a challenge to X-ray crystallographers as well. They are difficult to crystallise, and to obtain a crystal, crystallisation conditions have to be optimised for detergent type and amount, or the proteins have to be embedded in micelles. However, these workarounds can lead to crystals with lower resolution. This is not as big of a problem for cryo-EM studies – Zhao et al (2019) used cryo-EM to determine the structure of a eukaryotic voltage-gated Ca<sup>2+</sup> channel at less than 3Å resolution, and cryo-EM has been successfully used to determine the structures of all 7 TRP channel subfamilies. 

![[Pasted image 20230526005636.png]]
Figure 3: Difficult to crystallise proteins. 

Moreover, cryo-EM is less strict in requiring protein samples to be homogeneous compared to X-ray crystallography. It can be used to study structures in structurally heterogeneous samples in a single experiment due to image classification, whereby cryo-EM images of different particles or conformations can be separated out during image processing. This can be useful for proteins that are difficult to purify or have low abundances in the cell. 

# Advantage 4: As cryo-EM can image structurally heterogeneous samples, it can obtain the structures of different conformations of the same protein to gain mechanistic insights 

In cryo-EM, proteins in the sample can be visualised in all conformations they adopt as they are suspended in whatever conformation they were in at the time of vitrification. These different conformations can be separated out during image processing. Being able to see multiple conformations of the protein at once allows for understanding of conformational changes, which are crucial to understanding protein function. 

For example, cryo-EM analysis of glutamate dehydrogenase (GDH) by Borgnia et al (2016) showed that GDH can exist in two conformational states depending on whether it binds to NADH or not, and each state differs in the conformation of NADH in the regulatory site of GDH, thus revealing a possible function of NADH as a GDH regulator. In contrast, X-ray crystallography can only at best generate a series of snapshots of the protein, and each conformational state has to be stabilised and crystallised, which can be laborious. By looking at different conformational states, cryo-EM can also be used to study different stages of a biochemical process. Li et al (2019) found via cryo-EM that Snf2, a chromatin remodeler, has a closed conformation when bound to ATP, but adopts an open conformation when bound to ADP, which alters its interaction with DNA. By acquiring structures at different processive stages, the microscopist can construct a mechanistic model for various cellular activities. 

# **Disadvantage 1: The resolution of Cryo-EM is generally lower than X-ray crystallography and NMR**

The speed of cryo-EM may come at a trade-off with resolution. Most structures solved by cryo-EM have a resolution of 3-4Å, though a few have better resolution at about 2Å. The map quality of many cryo-EM structures are not considered sufficient to accurately identify non-protein densities (e.g. drug molecules, lipids). This resolution is lower than for X-ray crystallography, which can achieve resolutions even below 1Å (Figure 4). Furthermore, unlike in X-ray crystallography, there is no good method similar to metal anomalous diffraction for identifying the locations of metal ions. Unfortunately, because of this low resolution, cryo-EM has in the past been labelled as nothing more than “blobology”. As such, for obtaining very high resolution structures, cryo-EM may not be the best method. However, the resolution of cryo-EM may improve as microscopy technology evolves – Yip et al (2020) was able to accomplish a particularly high resolution structure (1.25Å) of apoferritin with a new type of electron microscope. 

![[Pasted image 20230526005653.png]]
Figure 4: Resolution of cryo-EM vs X-ray crystallography.

Cryo-EM is also only suitable for larger proteins, as there is a minimum size (~150 kDa) the protein must be to have its structure solved accurately by cryo-EM. That being said, the weight limit may be gradually decreased, as the structure of the 52 kDa streptavidin was successfully reconstructed recently with 3.2Å resolution (Fan et al, 2019). This size limit might also be overcome by binding antibodies to the protein (e.g. β<sub>1</sub>AR-arrestin complex). 

**also, "main limiting factor in Cryo-EM still remains the quality of the sample. In many cases, trying to get the biological molecules into very thin films causes them to encounter the air-water interface. This interface has surface forces capable of destroying the tertiary structure of the molecules or causing the so-called preferential orientation of molecules. Which in turn will severely limit the resolution"**

# **Disadvantage 2: Cryo-EM is slower than X-ray crystallography for drug discovery**

Although cryo-EM is faster at obtaining an initial structure than X-ray crystallography, the process is not as high throughput. Once a protein is crystallised, it becomes very efficient to generate the structures of thousands of different drugs in complex with the protein, often by simply soaking the crystal in a solution containing the drug. With cryo-EM, it takes hours to days to generate enough data for each high resolution EM structure, and there is no high throughput method for optimising the buffer conditions – the only way is to check the images after processing. As such, for drug discovery campaigns, cryo-EM still has some ways to go before it can compete with X-ray crystallography as the preferred technique. 

# **Disadvantage 3: Cryo-EM cannot tolerate excessive structural heterogeneity, nor capture small, transient changes in structure**

While cryo-EM is capable of capturing different structural conformations, this is only true to an extent – stable and homogenous samples still tend to produce higher quality images. More crucially, cryo-EM is not able to visualise minute and rapid changes in protein structure that may nonetheless be key to its function. Similar to X-ray crystallography, the lowest energy conformer is typically the one captured by cryo-EM, which could mean it misses out higher energy, transient conformations with millisecond-long lifetimes. Also, cryo-EM can only provide a range of static structures, without indicating how the structures interconvert or how quickly they interconvert (Figure 5). As such, NMR still retains a unique role in its ability to elucidate protein dynamics, as it is highly sensitive to even small structural changes at a wide range of timescales, from picosecond to millisecond. This is especially because it can study proteins at their physiological temperatures, thus capturing native protein dynamics, whereas with cryo-EM, the proteins have been vitrified in a layer of ice.  For example, Gladkova et al (2017) used chemical exchange saturation transfer NMR to detect a C-terminally retracted conformation of ubiquitin that is sparsely populated, yet is important to the interaction between ubiquitin and PINK1 as it has higher binding affinity. Other questions about protein dynamics, such as whether structural changes are driven by conformational selection or induced fit, are better answered by NMR than cryo-EM. 
![[Pasted image 20230526005709.png]]

Figure 5: Cryo-EM cannot capture transient conformations, or measure transition rates between conformations

# Conclusion

Future advancements in cryo-EM technology, particularly the development of more sensitive detectors and more accurate image processing methods, will make cryo-EM more effective for protein structure and function determination. We will probably see a rapid increase in cryo-EM usage in the coming years. However, it is unlikely that cryo-EM will become the sole method used in structural biology, given its weaknesses in resolution, throughput, and sensitivity to protein dynamics. In fact, future structural studies could benefit from combining different methods, as each of the three main structural techniques are highly complementary. For example, past studies have docked high resolution crystallographic or NMR structures into low resolution cryo-EM maps to obtain a detailed overall structure, and cryo-EM structures have also been used to solve the phase problem. Rather than being seen as the method of choice in all instances, cryo-EM should be seen as one of several tools for structural biologists to answer diverse biological questions.  

# Discarded 

General outline 



* Intro 
    * Why structural biology? Protein structure gives insight into its function. Structures can be used to create mechanistic models, especially if structures of multiple conformational states are known. 
* <span style="text-decoration:underline;">Brief</span> description of how the method works 
* Cryo-EM as the method of choice for protein structure – advantages/disadvantages (with elaboration), situations where it can be useful/not useful
    * Advantages
        * Speed 
            * Cryo-EM is a relatively quick method – low to medium resolution density structure can be obtained in a few hours
            * If the protein structure is unstable, better to use Cryo-EM than XRC as protein more likely to maintain its structure 
        * Realisticness 
            * Cryo-EM – Since the protein is captured in vitrified liquid, the protein structure will be as close to in its  natural environment as possible – no dehydration or staining is involved unlike in conventional EM. 
            * Minimise radiation damage to sample 
            * The development of Cryo-electron tomography (Cryo-ET) may even allow for _in situ_ structural biology – can obtain structures in their native cellular environment 
                * “In cryo-ET, a tilt series of 2D images of a sample are taken using a transmission electron microscope; each image is taken at a slightly different angle, after which computational methods are used to create a tomographic, 3D reconstruction of the sample. This 3D reconstruction represents a snapshot of the cell and can capture transient and rare events that can be missed when using purified components. By combining averaging tools from single-particle cryo-EM with images obtained with cryo-ET, structures can currently be obtained with 10–30 Å resolution. These tomograms can also be fitted with high-resolution structures obtained using other approaches to create detailed models of structures and complexes as they occur in cells” ([Strack 2020](https://www.nature.com/articles/s41592-019-0704-4)) 
                    * Can also understand the location of structures, surrounding context which is lost in purified structures
                    * While lower resolution, it can be combined with more high resolution techniques to localise detailed structures in their correct context in the cell 
                * E.g. [Hoffmann et al (2008)](https://www.pnas.org/doi/abs/10.1073/pnas.0709530105) used Cryo ET to image the native organisation of the _Mycobacterium smegmatis _cell envelope  
        * Does not require crystallisation, therefore 
            * Can be used to image large objects with internal symmetry e.g. viral capsids (NMR has size limitation, XRC ?) – 250 kDa
                * XRC limitation – 10-150 kDa 
                * NMR limitation – &lt;30 kDa 
                * E.g. Basore et al (2019) – Cryo-EM structure of the Mxra8 receptor bound to chikungunya virus-like particles 
            * Can image fibrous proteins with open symmetry e.g. actin (difficult to crystallise for XRC) 
                * E.g. Fitzpatrick et al (2017) – Cryo EM structure of tau filaments from Alzheimer’s disease at 3.4-3.5Å resolution. Tau filaments have a core region which is made up of repeats, and disordered regions towards the N and C termini
            * Can be used to image structurally heterogeneous samples in a single experiment due to image classification 
                * Protein can be seen in all conformations they adopt since the proteins are suspended in random conformations (i.e. the conformation they were in) upon vitrification in a thin layer of ice 
                * Cryo EM images of different particles or conformations can be separated out during image processing 
                * Helpful for proteins that are difficult to purify or have low abundances 
                * E.g. [Koh et al (2014)](https://www.pnas.org/doi/full/10.1073/pnas.1406335111) – 80S ribosome complex with the Taura syndrome virus internal ribosome entry site (IRES) has two conformations. 40S small subunit was rotated in different orientations in each conformation. This movement may be involved in IRES translocation. 
                * Being able to see multiple conformations of the protein at once allows for understanding of conformational changes
                    * E.g. Cryo-EM analysis of glutamate dehydrogenase showed that GDH can exist in two conformational states depending on whether it binds to NADH or not, and each state differs in the confirmation of NADH in the regulatory site ⇒ reveals a possible function of NADH as a GDH regulator (Borgnia et al 2016) 
                    * E.g. Cryo-EM studies of p97 show that there are three co-existing conformational states when ATPγS is added to p97, suggesting that there is a set of conformational changes that occur upon ATP binding → mechanistic insight into p97 activation 
                * This can be particularly helpful for dynamic proteins e.g. GPCRs 
                * At best, XRC can only generate a series of snapshots of the protein, assuming that each conformational state can be stabilised and crystallised 
            * Can image disordered proteins, proteins with post-translational modifications 
                * Disordered regions “disappear” in XRC because of low electron density 
                * Cryo-EM doesn’t need as much optimising of the protein, which takes time, compared to XRC where the protein has to be optimised for crystal formation 
            * Membrane proteins
                * Difficult to crystallise – need to optimise for detergent conditions, use micelles, etc. But these methods can lead to crystals that have lower resolution (5Å) 
                * E.g. [Zhao et al (2019)](https://www.sciencedirect.com/science/article/pii/S0092867419304957) used cryo-EM to to determine the structure of eukaryotic voltage-gated Ca2+ channel in complex with three different antagonistic drugs at less than 3Å resolution 
                * TRP channels have been difficult to crystallise successfully, while Cryo-EM has managed to determine the structures of all 7 TRP channel subfamilies 
                * Can use nanodiscs to mimic membrane environment (which is not compatible with XRC) 
        * Uses less resources 
            * Out of 5-10m particles in a cryo EM data set, only 100-300k may be used for the cryo-EM structure, while a typical GPCR crystal could have billions of identical molecules 
    * Disadvantages 
        * Resolution of Cryo-EM vs XRC, NMR 
            * Cryo-EM – Most structures solved by Cro-EM have a resolution of 3-4Å, though a few have better resolution at ~2Å. 
            * In contrast, XRC can achieve resolutions even below 1Å 
            * However, resolution of Cryo-EM may improve as technology evolves. [Yip et al (2020)](https://www.nature.com/articles/s41586-020-2833-4) was able to accomplish even higher resolution structure (1.25Å) of apoferritin due to advancements in electron microscopy 
            * Map quality of Cryo-EM is still not sufficient to identify non-protein densities (e.g. drug molecules, lipids) accurately 
            * Unlike XRC, no equivalent method to metal anomalous diffraction to identify locations of metal ions in proteins 
        * While Cryo-EM can image structurally heterogenous samples, this is only true to an extent – stable and homogenous samples tend to produce higher quality structures 
        * Unlike XRC, there is no high throughput method for optimising experimental / buffer conditions. Only way to know is to check the images, and image processing takes hours 
        * Still slower than XRC for drug discovery (Renaud et al 2018) – once a protein is crystallised it is efficient to generate structures of thousands of drugs bound to it in a short period of time, vs hours-days for to generate enough data for high res EM structures 
            * In contrast cryo-EM is not as high throughput 
        * Accessibility – ”electron microscopists are typically still expert scientists, and the elevated costs of purchasing and maintaining modern microscopes makes experimental time both scarce and expensive”
        * Low signal to noise ratio due to lack of staining and hence lack of contrast 
        * “Specimen preparation can be tricky – not only to optimise ice thickness, but also to optimise particle distribution. Sometimes proteins adopt preferred orientations that make 3D reconstruction impossible.”
        * Not useful for small proteins – the protein has to be big enough to be seen under EM, which generally requires a minimum of 150 kDa, though the weight limit has been pushed all the way down to 52 kDa (Fan et al 2019 imaged 52 kDa streptavidin with 3.2Å resolution) 
            * Large proteins have better contrast 
            * However, could be overcome by binding antibodies to the protein, e.g. Lee et al (2020) used an F<sub>ab</sub> to increase the size of the β<sub>1</sub>AR-arrestin complex 
        * Stability of protein complexes can be an issue – complexes may dissociate. Techniques such as ProteoPlex and GraFix can help to improve stability 
            * Proteoplex – method to test complex stability in buffer conditions to allow for screening without having to image by Cryo EM 
            * GraFix – uses density gradient centrifugation to isolate homogenous complexes 
* Cryo-EM as the method of choice for protein function – advantages/disadvantages, situations where it can be useful/not useful 
    * What is meant by protein function? = studying interactions with other molecules to understand its purpose in the cell. Dynamics, conformational changes. 
    * Advantages 
        * Cryo-EM structures of complexes in different stages of a process
            * E.g. Li et al (2019) – Investigated mechanism of how Snf2, a chromatin remodeler, couples ATP hydrolysis to nucleosome translocation. Used cryo-EM of Snf2-nucleosome complex to report that Snf2 is in an open conformation when bound to ADP,  and is in a closed conformation when bound to ATP, and has altered interactions with DNA in each conformation. 
        * Able to obtain high resolution structures of proteins in complex with binding partners 	
            * E.g. see Zhao et al (2019) above
        * Ability to obtain structures for dynamic regions that are often important to protein function 
    * Disadvantages 
        * Not as good at protein dynamics, studying disordered structures as NMR due to timescale 
            * NMR is much more sensitive to even small, transient changes in structure and is better suited to capturing the conformational range of proteins and protein dynamics at different timescales from picosecond to millisecond 
                * “lowest energy or most abundant conformer is the one typically captured by methods such as X-ray crystallography or cryo-electron microscopy” 
                * NMR can also indicate the presence of _minor_ states or transient states which may be difficult to detect even with image classification algorithms used for Cryo EM 
                * “Proteins frequently make transient excursions to thermally accessible, higher energy conformations with lifetimes on the order of a few milliseconds”
                * E.g. [Gladkova et al (2017)](https://www.embopress.org/doi/abs/10.15252/embj.201797876) used chemical exchange saturation transfer NMR to detect a C-terminally retracted conformation of ubiquitin that is sparsely populated, and yet is important to the interaction between ubiquitin and PINK1 as it has a higher binding affinity → allows for more efficient PINk1 phosphorylation 
            * NMR can study proteins at physiological temperatures to accurately capture native protein dynamics in solution, whereas for Cryo-EM the proteins are vitrified in a layer of ice → can only obtain static pictures of conformational states 
            * Two methods could complement – Cryo-EM for larger scale changes and NMR for smaller-scale changes e.g. protonation states, bond rotations, aromatic ring flips, etc. 
            * Cryo-EM cannot provide information on rates of transition between conformational states
            * E.g. questions about conformational selection vs induced fit are better answered by NMR than Cryo-EM
* Conclusion 
    * Future advancements that might make it more effective for structure and function determination → likely to become increasingly preferred
    * However, unlikely that Cryo-EM will become the sole method used in structural biology 
    * Mention of complementarity in structural biology 
        * Should combine different methods! [https://www.sciencedirect.com/science/article/pii/S1046202309000887](https://www.sciencedirect.com/science/article/pii/S1046202309000887)
        * Hybrid studies that use both XRC and EM are not uncommon. 
        * Low resolution cryo-EM maps can be used to provide overall structure, while subunits are studied with XRC. E.g. [Studying ryanodine receptors](https://www.sciencedirect.com/science/article/pii/S014341601630046X#bib0160) – large protein, so can use EM to get the coarse structure of the whole protein, while using XRC to get finer structural detail of individual fragments. Cryo-EM studies of the ryanodine receptor RyR1 showed discrepancies in the identities of domains within the SPRY domain cluster, which was only resolved when RyR domain crystal structures were solved 
        * The crystallographic structures can be docked into a low resolution Cryo-EM map to get the fine structure of the molecule as a whole
            * Lau & Van Petegem (2014) – crystal structure of Ryanodine receptor 1’s SPRY2 domain was docked as a rigid body into 10Å resolution cryo EM map of RyR1 
            * This method can be used to understand conformational changes too. E.g. [Liu et al (2014) ](https://www.nature.com/articles/nsmb.2736)
        * NMR structures can also be docked 
        * Cryo-EM structures could also be used to solve the phase problem 
            * Low res Cryo-EM reconstruction is used as the initial phasing model
            * E.g. Stuart & Abrescia (2013) – Used this method to determine the structure of the marine bacteriophage PM2. They used molecular replacement starting from a low resolution cryo-EM structure to obtain an X-ray structure of the virus. 
            * This can be useful if molecular replacement from homologous structures is not possible or by other methods, as was in the case for Wang et al (2015) in the structural determination of Toll-like receptor 13 with its RNA substrate 

 Refs

* [https://thebiologist.rsb.org.uk/biologist-features/focus-on-cryo-electron-microscopy](https://thebiologist.rsb.org.uk/biologist-features/focus-on-cryo-electron-microscopy)
* Benjin, X., & Ling, L. (2020). Developments, applications, and prospects of cryo‐electron microscopy. _Protein Science : A Publication of the Protein Society_, _29_(4), 872–882.[ https://doi.org/10.1002/pro.3805](https://doi.org/10.1002/pro.3805)
* Cheng, Y. (2018). Membrane protein structural biology in the era of single particle cryo-EM. Current Opinion in Structural Biology, 52, 58–63. [https://doi.org/10.1016/j.sbi.2018.08.008](https://doi.org/10.1016/j.sbi.2018.08.008)
* Earl, L. A., Falconieri, V., Milne, J. L., & Subramaniam, S. (2017). Cryo-EM: Beyond the microscope. Current Opinion in Structural Biology, 46, 71–78. [https://doi.org/10.1016/j.sbi.2017.06.002](https://doi.org/10.1016/j.sbi.2017.06.002)
* Wang, H.-W., & Wang, J.-W. (2017). How cryo-electron microscopy and X-ray crystallography complement each other. Protein Science, 26(1), 32–39. [https://doi.org/10.1002/pro.3022](https://doi.org/10.1002/pro.3022)
* García-Nafría, J., & Tate, C. G. (2021). Structure determination of GPCRs: Cryo-EM compared with X-ray crystallography. Biochemical Society Transactions, 49(5), 2345–2355. [https://doi.org/10.1042/BST20210431](https://doi.org/10.1042/BST20210431)
* Alderson, T. R., & Kay, L. E. (2020). Unveiling invisible protein states with NMR spectroscopy. Current Opinion in Structural Biology, 60, 39–49. [https://doi.org/10.1016/j.sbi.2019.10.008](https://doi.org/10.1016/j.sbi.2019.10.008)