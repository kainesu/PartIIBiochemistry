**What methods can be used to detect and quantify mRNA? What would govern your choice?**

# Introduction
mRNA are important mediators of gene expression, serving as intermediaries between the information stored in DNA and proteins. As such, understanding gene expression regulation in cells will require investigation of where mRNA is synthesized, when it is synthesized, and how much of it is synthesized. In that pursuit, numerous methods of mRNA detection and quantification have been developed that rely on different principles, different use cases, and have different levels of speed and accuracy. These methods, as well as some points on how to decide which would work best for an experiment, are described below.

# 1. In-situ hybridisation methods
A large suite of mRNA detection techniques rely on the hybridisation of an oligonucleotide probe to a target mRNA in the cell via complementary base pairing. The basic premise of these techniques is that each probe binds to a target mRNA sequence in a 1:1 fashion, while the probe itself is linked to some detectable substance (e.g. a fluorophore, gold nanoparticles) for quantification. 

One of the most commonly used methods is RNA fluorescent in-situ hybridisation (FISH), which links probe hybridisation to the level of fluorescence measured. It can be used to visualise the positions of mRNA in a variety of samples, including cell cultures and tissue sections. The probe is conjugated to a fluorophore such that fluorescence can be detected via fluorescence microscopy at any position where the probe hybridises. Multiplexing is possible by conjugating each RNA probe to a different fluorophore. The amount of mRNA is quantified by measuring the fluorescence signal intensity in the sample, and comparing it to the fluorescence intensity of a known concentration of oligo in vitro. 

[Diagram] 

As applications tend to suffer from high background fluorescence and non-specific binding, some variants of FISH have been developed to improve the signal to noise ratio and thus improve the accuracy of quantification. For example, single molecule FISH (smFISH) uses multiple short DNA probes conjugated to the same fluorophore and that are complementary to different regions of the target mRNA sequence. Since multiple mis-bound probes are unlikely to co-localise, this reduces the false positive signal. The number of mRNA can then be quantified by counting the number of fluorescent spots within a single region. For example, Nishimura et al (2015) used smFISH to track changes in mRNA abundance across the C. elegans embryo for three genes, chs-1, pgl-1, and bpl-1. 

Another hybridisation method with improved signal to noise ratio makes use of molecular beacons, which are small hairpin-shaped oligonucleotides with an internally quenched fluorophore, which only fluoresces when the beacon hybridizes to its target sequence. An even more sophisticated version combines molecular beacons with FRET, which requires co-localisation of two molecular beacons at adjacent regions on the same mRNA for fluorescence to be detected. In their original study, Santangelo et al (2004) used this method to localize Kras mRNA in human dermal fibroblasts with high signal to background ratio. 

[Diagram] 

For studying mRNA localisation at even smaller scales, immuno-electron microscopy is the method of choice. In general, the method involves the use of an antisense probe conjugated to digoxigenin or biotin. Following hybridisation, a primary antibody is introduced that binds to the probe label, then a secondary antibody conjugated to a gold nanoparticle is used, which binds to the primary antibody. These gold nanoparticles then show up as dark spots on an electron micrograph. Delanoue et al (2007) used this method in ultrathin cryo-sections to follow grk mRNA localisation in the Drosophila oocyte. 

Despite their lower sensitivity compared to RT-qPCR or RNA-seq, in-situ hybridisation methods are particularly useful for studying RNA localisation since the location of the oligonucleotide probes can be detected via microscopy. Depending on the type of sample, speed of the process being observed, and the level of sensitivity required, different microscopy techniques can be used (e.g. wide-field microscopy, confocal microscopy, etc.)

# 2. Protein binding methods 

Apart from using oligonucleotide probes for detection of mRNA, RNA binding proteins can also be used to localize and quantify mRNA. One of the most commonly used methods is the MS2-MCP system, which uses MS2 RNA coat protein (MCP) fused to a fluorescent protein. The gene that produces the target mRNA has to be genetically modified to encode MS2 stem-loop motifs to allow for binding of the MCP fusion protein. For multiplexing, similar stem loop-binding systems have been developed so that multiple mRNAs can be tracked at once. These include the U1A RNA binding system, lambda box B-peptide N system, or human Pumilio system. Different mRNA sequences can then be engineered to include different stem loops. 

[Diagram] 

More recently, the RNA binding CRISPR-Cas13 system has also been used for RNA detection. Gootenberg et al (2017) presented the first such Cas13-based detection system, known as SHERLOCK, to genotype nucleic acid sequences from various sources. The technique relies on the fact that Cas13a can be reprogrammed with CRISPR RNAs that are complementary to particular target sequences, and upon binding to the target sequence will cleave non-target RNA. In SHERLOCK, any RNA present undergoes an isothermal amplification step, then Cas13a detects the target RNA, upon which it cleaves a reporter RNA that releases a fluorescent signal upon degradation. This system was able to detect single stranded RNA with attomolar sensitivity, which is comparable to qPCR. Shinoda et al (2021) subsequently created a SHERLOCK variant called SATORI that can be used for RNA detection. It has femtomolar sensitivity but removes the amplification step, thus increasing the speed of detection. In theory, calibration for the fluorescent signal could allow for RNA quantification as well, although this has not been explored. 

[Diagram] 

# 3. PCR-based methods 

The current gold standard for RNA quantification in terms of sensitivity and accuracy is reverse transcription-quantitative PCR (RT-qPCR), which involves the reverse transcription of the RNA to DNA, followed by a qPCR step to quantify the amount of RNA present. For total mRNA quantification in eukaryotes, oligo dTs can be used as primers for reverse transcription as they anneal to the polyA tail. Alternatively, random hexamers can be used. For quantification of specific mRNA sequences, a specific primer can be employed instead. In the quantification step, PCR amplification of the DNA in the presence of an intercalating dye (e.g. SYBR Green) or a fluorescent oligonucleotide probe allows for determination of the starting quantity of DNA, and in turn RNA. This is based on calculation of the Ct value, which refers to the number of PCR cycles required to generate fluorescence above a particular threshold. 

[Diagram]  

A closely related alternative, known as digital droplet PCR (ddPCR), involves partitioning the PCR reaction plus fluorescent probes into many small droplets, then after a certain number of amplification cycles, each droplet is checked for fluorescence. The fraction of droplets with fluorescence then correlates to the initial amount of RNA. 

While highly accurate and sensitive, PCR-based methods do suffer from lower speed and possible risk of contamination if used by an untrained operator. As such, these methods may not be suitable for monitoring the changes in gene expression of mRNA with short half-lives, or for monitoring highly dynamic processes. 

# 4. Global mRNA profiling methods  

The previously described methods allow for detection and/or quantification of specific target mRNA. While multiplex variants of some of these techniques exist, they would be impractical if we wish to study changes in quantity of hundreds of target mRNA sequences at a global scale. Instead, techniques better suited to global mRNA profiling such as microarrays or RNA-seq should be used. 

Microarrays are mainly used for relative quantification of mRNA from two different samples, and also involve hybridisation of RNA to oligonucleotide probes. However, the difference with other hybridisation-based methods is that microarrays contain a collection of DNA oligos that are complementary to many different mRNA sequences. With microarrays, the mRNA has to be reverse transcribed to cDNA, and cDNA from each sample tagged with a different fluorophore to allow them to be differentiated. Then the cDNA is hybridized to the DNA in the microarray, and the fluorescence intensity from each fluorophore is measured to quantify the quantity of each mRNA. This allows for the generation of an expression profile, where changes in mRNA quantity can be observed across many genes at once. 

[Diagram] 

With the advent of next generation sequencing, RNA sequencing (RNA-seq) has become more commonly used for global mRNA profiling. Compared to microarrays, RNA-seq has the advantage of being more sensitive to differences in mRNA quantity, a greater dynamic range, and does not require prior knowledge of the species’ genome, as it does not involve the use of oligonucleotide probes for RNA detection. In RNA-seq, quantification is done by counting the number of mRNA sequence reads that map back to each gene in the reference genome. If no reference genome exists, the sequence reads have to be assembled into longer contigs to generate a reference genome. Nagalakshmi et al (2008) developed RNA-seq to generate a transcriptomic map of the yeast genome. 

# 5. Which method to use?

While some considerations for the choice of mRNA detection and quantification method have been discussed above, the most important consideration is the research question – what information would be sufficient to answer the question at hand, using minimal time and resources? 

For simple detection of mRNA without quantification, Cas13-based methods like SHERLOCK may be sufficient. For questions on the spatial organization of mRNA, an imaging technique that tags the mRNA with a visible marker would work best as it would allow for visualization of the positions of mRNA in the cell. As such, methods like FISH, immuno-electron microscopy, or MS2-MCP could be used, depending on the exact spatial scale required. On the other hand, questions on only temporal changes in mRNA could be better served by RT-qPCR if higher accuracy results are desired. However, as such sensitive methods are also often more difficult and slow to use, the experimenter has to consider how sensitive the method has to be – if the mRNA levels exhibit large fold changes over time, then it would be sufficient to use e.g. a hybridisation method which is faster and will still indicate significant changes in mRNA quantity. It may also be unviable to use such slower methods if the change in mRNA level occurs too rapidly, such as if the mRNA has a short half-life, unless a separate technique is used to preserve the quantity of mRNA at a particular point in time. 

Some research questions focus on a particular mRNA sequence that the experimenter may already have prior knowledge on, which may be a necessity for some methods that rely on the use of complementary oligonucleotide probes or primers. An example of such an appropriate question would be “How does ASH1 mRNA localize in yeast cells over the course of the cell cycle?” Investigating multiple mRNA sequences at once to study their interactions is also possible due to the development of multiplex variants of each technique. However, if the research question is more exploratory in nature, for example, “What changes in gene expression drive the development of colorectal cancer?”, then the study would be too limited in scope if only particular genes were focused on. In such cases, global mRNA profiling methods would be more appropriate, i.e. microarrays and RNA-seq.

It is also often the case that the best method to use would simply be the one that is the most easily employed given the resources available in the lab. Many of the above techniques require optimisation or calibration of the experimental conditions to acquire clear results, so it may be easier to use a method with an existing protocol assuming it serves the purpose of the experiment well. This is particularly so for techniques that require a higher level of operating skill, e.g. RT-qPCR. 

# Conclusion. 

- Gaps in techniques? 
- Cancer, developmental biology, stem cell biology 
- Importance of CONTROLS

# Extra stuff
## Detection only
- Immuno-electron microscopy
- Injection of RNA that is synthesized and labeled with a fluorescent label in vitro
- In vitro assays to study RNA motility (Soundarajan & Bullock 2014)

## Detection and quantification 
### Semi-quantitative
- Northern blot 

### Fluorescence
#### Hybridisation methods (variants) 
- ISH 
	- FISH
	- Radioactive
- Live in situ hybridisation 
- Molecular beacon 
- Forced intercalation 
- Nuclease protection assay 
	- [https://www.thermofisher.com/uk/en/home/references/ambion-tech-support/northern-analysis/tech-notes/strategies-for-detecting-mrna.html](https://www.thermofisher.com/uk/en/home/references/ambion-tech-support/northern-analysis/tech-notes/strategies-for-detecting-mrna.html)
- Microarrays 

#### Protein binding 
- In vivo labeling with MS2 system 
	- And variants of stem loop binding system 
- CRISPR-Cas13 
	- Gootenberg et al (2017) [https://www-science-org.ezp.lib.cam.ac.uk/doi/10.1126/science.aam9321](https://www-science-org.ezp.lib.cam.ac.uk/doi/10.1126/science.aam9321)
	- Shinoda et al (2021) [https://www-nature-com.ezp.lib.cam.ac.uk/articles/s42003-021-02001-8](https://www-nature-com.ezp.lib.cam.ac.uk/articles/s42003-021-02001-8)

#### RNA aptamers (e.g. Spinach) 

### High accuracy 

- RNA-seq
- RT-qPCR
	- qPCR with intercalating dye
	- qPCR with sequence-specific fluorescent oligonucleotide probe 
	- Needs normalisation using housekeeping genes
	- Cannot measure RNA localisation 

### Rapid 
- Spectrometry 
- [RT-LAMP](https://bmcinfectdis-biomedcentral-com.ezp.lib.cam.ac.uk/articles/10.1186/s12879-019-4277-8)

## Other techniques 
- “Click chemistry” labelling – bioorthogonal chemistry
- Spectrometry (UV absorbance) 
- [Flow cytometry](https://pubs-acs-org.ezp.lib.cam.ac.uk/doi/10.1021/acs.analchem.1c04355)