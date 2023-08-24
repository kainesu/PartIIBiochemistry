**Which mechanisms determine the <span style="text-decoration:underline;">assembly of splicing complexes</span> at regulated splice sites?**

Determine 
1. Whether splicing complex assembles or not 
2. Efficiency of splicing complex assembly 

# **Introduction **

The process of splicing is mediated by splicing complexes, also known as the spliceosome, which assemble at splice sites at intron-exon junctions. As such, regulation of splicing at these splice sites often involves mechanisms that affect the efficiency of spliceosome assembly at these sites, or indeed whether the spliceosome can assemble at all. Such mechanisms involve various _cis _regulatory elements, as well as _trans_ factors that interact with the splice site and spliceosomal components, and may act at different steps of the spliceosome assembly process (Figure 1). 

![[Pasted image 20230525003402.png]]

Figure 1: Summary of mechanisms

# 1. Splice site strength 

The strength of a splice site refers to the affinity of a splice site for binding to spliceosomal components, and is determined by the similarity of the splice site to its consensus motif. For the 5’ splice site, the consensus sequence is  (C/A)AG|GURAGU, while for the 3’ splice site, the consensus is YAG, where Y is a pyrimidine. The consensus motif represents the sequence with highest binding affinity for the respective spliceosomal component, as it is complementary to the snRNA present in the cognate snRNP. As such, given two adjacent splice sites for alternative exons in a gene, the one with the stronger splice sites would have a tendency to recruit splicing complex components first, increasing the efficiency of spliceosome assembly at that splice site. For example, mutational analysis of splice sites by Lamond et al (1987) found that 5’ splice site mutations caused an accumulation of half-assembled spliceosomes. Roca et al (2005) explains this observation by calculating the predicted free energy change (ΔG) of base pairing between the U1 snRNA and a stronger 5’ splice site versus a weaker 5’ splice site.  The stronger 5’ splice site had a greater free energy change (ΔG), and the weaker 5’ splice site is only used if the stronger one was inactivated by mutation. Hence, splice site strength affects whether a complete spliceosome can assemble for splicing to occur. 

# **2. Splicing code – interactions between _cis_ regulatory sequences and splicing activators/repressors**

***Note: this should be the main part of the essay** 
- Go into detail on the different mechanisms by which activators, repressors affect the binding of core splicing factors and thus the assembly of splicing complexes, e.g. repressors can compete for binding with core splicing factors (e.g. SXL at Tra) or promtoe dead end splicing complexes (Sxl autoregulation, PTBP1 repression of CSRC N1 exon) – can refer to notes for this

Apart from the strength of the splice site itself, other _cis_ regulatory sequences within the exons and introns can enhance or repress spliceosome assembly at adjacent splice sites. Different combinations of enhancers and silencers, as well as differential expression of activators and repressors in different tissue types, results in combinatorial control of splicing efficiency that is often referred to as a “splicing code”. 

Generally, enhancers promote splicing by recruiting activators that in turn recruit spliceosome components to the splice site. In the female _Drosophila_, for example, exon 4 inclusion is promoted by the presence of the splicing activators Tra and Tra2. Tra and Tra 2 form a complex with SRSF7, as well as separately with SRSF1, to recognise two different enhancer sequences, and these trimer complexes promote splicing via recruitment of U2AF<sup>65</sup> to the weak polypyrimidine tract of exon 4. 

In contrast, silencers prevent spliceosome assembly, either by recruiting splicing repressors that directly block spliceosome components from binding or antagonise activator function. In the HIV _Tat_ pre-mRNA, hRNP A1 binds to an intronic silencing sequence upstream of exon 3, which then recruits more hRNP A1 to result in multimerisation of the repressor along the RNA. This blocks binding of U2 snRNP to the 3’ splice site (Figure 2). 

![[Pasted image 20230525003410.png]]

Figure 2: Mechanisms of splicing activation and repression by trans factors

The effect of some _trans_ factors on spliceosome assembly may even be position-dependent, acting as either an activator or repressor depending on context, which could allow for coordinated regulation of related genes by a single protein. A splicing regulator in brain tissue, NOVA1, binds to the intronic splicing enhancer of the _GABRG2_ gene to promote inclusion of exon 9, but binds to the exonic splicing enhancer in exon 4 of its own pre-mRNA to promote its skipping. Thus, such _trans_ factors can directly affect the ability of spliceosome components to assemble at splice sites to regulate their usage. 

Less directly, other _trans_ factors are also known to compete with splicing activators/repressors for binding to their cognate enhancer sequences. In _CALCA_ pre-mRNA, the binding site of FOX1 and FOX2 overlaps with an exon splicing enhancer, which blocks the splicing activators TRA2 and SRp55 from binding. This prevents the recruitment of the spliceosome component U2AF by these activators, inhibiting E complex formation (Zhou & Lou 2008). FOX1 and FOX2 thus regulate spliceosome assembly at this _CALCA _splice site in an indirect manner by interacting with splicing factors. 

# **3. RNA secondary structure **

In some mRNAs, the formation of secondary structures can mask splice sites and other _cis _regulatory sequences, which affects whether the spliceosome can assemble on the splice site. Shepard & Hertel (2008) performed a genome-wide analysis to look for conserved RNA secondary structures that overlap exon/intron junctions, and found that sequences that can form stable RNA secondary structures tend to be found at exon/intron junctions that undergo alternative 5’ or 3’ splice site selection. This would suggest that RNA secondary structure has widespread involvement in splicing regulation. For example, formation of an RNA hairpin close to the 5’ splice site of the _SMN2_ exon 7 inhibited its splicing by interfering with the binding of U1 snRNP (Figure .  

Competitive secondary structures could also reinforce mutually exclusive splicing, determining at which site the spliceosome will assemble at. The most salient case of this happening is in exon 6 cluster of the _DSCAM _gene of _Drosophila_. In the intron upstream of exon 6.1, there is a sequence known as a docking site, and each exon has an upstream selector sequence which is complementary to the docking site. When the docking site pairs to a particular selector (Figure 3), it activates its corresponding exon, by relieving the effect of splicing repressors that prevent spliceosome assembly, or promoting recognition of the splice site by spliceosome components. A parallel can be drawn with splice site selection in the _Transformer_ gene, except that selection is mediated by RNA structure rather than by _trans_ factors. **(chris was not convinced by this analogy haha)**

![[Pasted image 20230525003417.png]]

Figure 3: RNA secondary structure effects on spliceosome recruitment

# **4. Rate of transcriptional elongation (kinetic coupling model) **

The rate of transcriptional elongation by RNA polymerase II can also affect which splice sites spliceosomal components are recruited to, as it affects how soon splice sites can be transcribed to recruit spliceosomal components or splicing regulators. In different contexts, changes in elongation rate can result in splicing or skipping of a particular exon. In contexts where a slower rate results in exon splicing, the spliceosome is recruited to the weaker splice site because the stronger splice site has not yet been transcribed. On the other hand, where slower elongation rate results in exon skipping, this occurs when both alternative splice sites are equally strong, but one splice site is negatively regulated, fast elongation allows spliceosomal components to be recruited to both sites before negative regulation can occur, while a slow rate provides time for the negative regulator to repress splicing, resulting in exon skipping. 

Direct evidence for the kinetic coupling model comes from studying the effect of slow Pol II on splicing. For example, de la Mata (2003) showed that transcription by a mutant human RNA Pol II with a slower elongation rate resulted in increased EDI exon inclusion in fibronectin. The 3’ splice site of the intron upstream of the EDI exon is weaker than the one for the downstream intron, so if RNA Pol II pauses between the two sites, then only the upstream splice site can recruit spliceosome components for assembly, resulting in exon inclusion (Figure 4). In other words, RNA Pol II elongation rate affects the availability of splice sites that splicing machinery can access for assembly. 

![[Pasted image 20230525003422.png]]

Figure 4: Slowing transcriptional elongation can promote exon inclusion in some contexts

# **5. Chromatin effects **

The structure of chromatin and associated histone modifications can also affect splicing in several ways. In the first way, histone modifications can affect the elongation speed of RNA Pol II, which in turn affects splicing, as described in the kinetic coupling model. Some repressive histone marks are able to recruit the heterochromatin-associated protein HP1-α, which Allo et al (2009) showed slowed RNA Pol II and was linked to changes in splicing patterns. Alternatively, histone modifications may recruit splicing factors via adapter proteins, and these splicing factors then facilitate or inhibit assembly of spliceosome components. One such histone modification is H3K36me3, which recruits the adapter MRG15 that in turn recruits the splicing repressor polypyrimidine-tract binding protein. Lastly, some chromatin remodelling proteins may even interact with spliceosome components directly to facilitate spliceosome assembly, as with CHD1 which interacts with U2 snRNP. 

# **Conclusion **

Spliceosomes are regulated via many different mechanisms at different steps of assembly, which modulates the efficiency of different splice sites. The cell’s ability to determine how splicing complexes assemble is critical to regulating gene expression, generating protein diversity, and rewiring protein-protein interactions. As such, having multiple mechanisms for splicing regulation ensures that the process remains robust as well as sensitive to multiple cellular inputs. This understanding of the determinants of spliceosome assembly at regulated splice sites could prove useful in developing therapeutics for diseases caused by splicing malfunctions, such as cancer. 

# Discarded stuff
**Affects whether splicing complex can assemble – splice site selection** 
* Strength of splice site – Affinity of splice site to facilitate splicing complex formation. This is determined by its similarity to consensus motif 
    * Roca et al (2005) – Stronger 5’ ss that could outcompete weaker 5’ ss for selection have greater free energy change (ΔG) upon base pairing to U1 snRNA 5’ terminus. Weak 5’ ss only used if stronger 5’ ss inactivated by mutation 
* Exon-intron architecture – the relative sizes of the introns and exons affect alternative splicing 
    * Fox-Walsh et al (2005) – If intron 200-250 nt, intron definition. If intron > 250nt, exon definition. However, as intron definition results in more efficient splicing than exon definition, this could increase inclusion of exons with weak splice sites. In _Drosophila_, exons with long introns had a higher chance of being excluded than those with short introns 
* Spatial proximity – proximal splice sites are favoured 
* Temporal proximity (kinetic coupling model) – Rate of transcriptional elongation affects which exons are included, as it affects how soon the exon splice site can be transcribed and recruit spliceosome components. 
    * de la Mata et al (2003) – Mutated RNAP II to decrease its elongation rate → promoted inclusion of alternative exon with weaker splice sites in the _FN1_ EDI exon
    * Post-translational modifications of RNAP II CTD – Ser5 phosphorylation can cause RNAP II stalling. RNAPII with Ser5 phosphorylation pauses at a variant exon region of CD44 and associates with the protein BRM, which also results in increased association of BRM with splicing machinery, leading to V5 exon inclusion  
* Different levels of core spliceosomal proteins in different tissues 
    * Microarray studies of mouse, chimpanzee, humans show that snRNPs are differentially expressed in different tissues ()
    * Changing levels of core spliceosomal proteins (e.g. components of U1, U2, U4/6 snRNPs) leads to changes in alternative splicing
        * RNAi studies in _Drosophila_
* RNA secondary structure – can mask splice sites and _cis_ regulatory sequences → affect assembly 
    * E.g. A hairpin structure sequesters exon 6B of chicken β-tropomyosin pre-mRNA, leading to its exclusion 
    * E.g. Masking regulatory sequence – IDX exon of _RAS_ can form a secondary structure with an ISS to prevent binding of hnRNP H to ISS1 → promote spliceosome assembly 
        * IDX exon is excluded in the presence of RNA helicase P68 which unwinds the secondary structure and exposes ISS1
    * E.g. Formation of an RNA hairpin close to the 5’ splice site of the _SMN2_ exon 7 inhibited its splicing by interfering with the binding of U1 snRNP 
    * E.g. competitive secondary structures can reinforce mutually exclusive splicing – In _DSCAM_ gene, there is a docking site in the intron upstream of exon 6.1, and each exon has an upstream selector sequence. The docking site is complementary to the selector sequence. When the docking site pairs to a particular selector, the proximal alternative exon is activated by relieving the effect of splicing repressors or promoting recognition of its splice site 
    * Shepard & Hertel (2008) performed a genome-wide analysis to find conserved RNA secondary structures that overlap exon/intron junctions. Using a bioinformatics approach, they found that sequences that can form stable RNA secondary structures correlates with exon/intron junctions that undergo alternative 5’ or 3’ splice site selection 
* Steric hindrance – protein binds to a splice site to mask it from snRNPs or splicing activators 
    * E.g. Sxl 
    * E.g. Block snRNPS – Polypyrimidine-tract binding protein (PTB) binds to PPT to block binding of U2AF at regulated exons (Singh et al 1995) 
    * E.g. Block snRNPs – hnRNP A1 binds ISSs located upstream of exon 3 in HIV _Tat_ pre-mRNA to prevent binding of U2 snRNP 
        * Can occur via multimerisation along the RNA 
    * E.g. Competition with activators – FOX1, FOX2 inhibit E complex formation by binding to an exon in _CALCA_ pre-mRNA close to the ESE of TRA2, SRp55 → prevents recruitment of U2AF by these activators (Zhou & Lou, 2008) 
    * E.g. looping out of exon – hnRNP A1 binds to elements upstream, downstream of exon 7B in its own pre-mRNA → prevent spliceosome assembly even though splice site is not masked 
* Post-transcriptional mRNA editing 
    * Solomon et al (2013) – Used a bioinformatics approach to find that ADARs make adenosine-to-inosine edits in exonic splicing regulatory elements (SREs) in the pre-mRNA, and cassette exons are particularly enriched with such editing sites. ADARs also edit the mRNA of trans-acting elements. Used exon microarray, RNA-seq to show that ADAR KO cells had altered AS patterns 

**Splicing complex efficiency **

* Exon juxtaposition (converting from exon definition to intron definition) 
    * House & Lunch (2006) proposed that an A-like exon definition complex forms across exons in the absence of hnRNP L, then U4/U6-U5 snRNP complex is recruited to the intron-defined A complex to form the B complex. But when hnRNP L is present, the A-like complex prevents U1 or U2 snRNPs bound to the splice sites of exon 4 from cross-intron pairing with adjacent U1 or U2 → exon skipping 
    * PTB may also be involved in the blocking of the transition from exon definition to intron definition. Sharma et al (2008) compared active and inactive spliceosomes in neuronal WERI-1 cell nuclear extracts vs HeLa cell nuclear extracts… 
    * Activation of intron definition – in experiments with substrates containing expanded introns, binding sites for hnRNPs near intron boundaries can promote splicing, presumably due to cross-intron interactions between hnRNPs that bring the ends of the introns together. (Martinez-Contreras et al 2006) 
* Transcriptional coupling – RNAPII and TFs can interact with splicing factors to affect efficiency of splicing 
    * E.g. PGC1 is a transcriptional coactivator that can interact with splicing factors via its RS domain, thus altering alternative splicing 
* Post-translational modification of splicing factors
    * “Post-translational modifications of splicing factors enable cells to switch between alternative splicing isoforms rapidly after environmental stimuli. Phosphorylation can change the intracellular localization of splicing factor, protein–protein and protein–RNA interactions and even intrinsic splicing factor activity.” (Chen & Manley 2009) 
        * E.g. Localisation – Hyperphosphorylation of hnRNP A1 during osmotic shock leads to relocalisation of hnRNP A1 to the cytoplasm from the nucleus → altered AS pattern of adenovirus E1A reporter transcript
    * May be important for changing alternative splicing patterns rapidly e.g in response to stress 
* Splicing code 
    * Differentiates exons from pseudo-exons 
    * Presence/absence of enhancers/silencers
        * Enhancers – splicing activators recruit spliceosome components (e.g. positive regulation of Dsx splicing by Tra/Tra2) 
        * Silencers – may act to destabilise spliceosome complex (e.g. autoregulation of Sxl) 
        * ESE/ESS → in exons. ISE/ISS → in introns 
    * Differential expression of activators/repressors in different cells – can be tissue specific 
        * E.g. In vivo, SRp38 favours inclusion of Flip exon of _GRIA2_ pre-mRNA, while the mutually exclusive Flop exon is included when SRp38 is absent – the intracellular concentrations of SRp38 and differential binding to the exons influence the decision to include Flip or Flop (Feng et al 2008) 
        * Regulation of these activators/repressors 
            * E.g. SR protein Srp38 is a general splicing repressor, but functions as a sequence dependent splicing activator when phosphorylated. 
        * Exhibit cooperative interactions with each other 
        * Action of activators and suppressors is combinatorial, and final outcome is determined by relative levels of activators vs suppressors. 
        * Action of activators/suppressors can be position-dependent, i.e. whether the regulator acts as activator/suppressor depends on location of binding site. 
            * E.g. NOVA1 can bind to ISE of _GABRG2_ to promote inclusion of exon9, but binds to ESS in exon 4 of its own pre-mRNA to exclude exon 4
            * “SR proteins enhance splicing only when they are recruited to the exon. However, they interfere with splicing by simply relocating them to the opposite intronic side of the splice site. hnRNP splicing factors display analogous opposing activities, but in a reversed position dependence.”
        * Tissue-specific alternative splicing regulators. Brain has many – e.g. NOVA1, NOVA2, nPTB 
        * Post-translational modifications E.g. “Phosphorylation of TIA1 and TIA1-related protein (TIAR) by Fas-activated serine/threonine kinase (FASTK) enhances TIA1 and TIAR-mediated recruitment of U1 snRNP to a suboptimal 5′ splice site, leading to the inclusion of CD95 exon 6” – phosphorylation of RS domains affects interactions with core spliceosomal proteins 
        * Common mechanisms 
            * “Activation by SR or hnRNP proteins increases splice site recognition at the earliest steps of exon definition, whereas splicing repression promotes the assembly of nonproductive complexes that arrest spliceosome assembly prior to splice site pairing.”
            * “SR protein splicing repression is based on stalling the progression of spliceosomal assembly after efficient formation of the E-complex” 
* Changes in spliceosome complex assembly stability? 
* Epitranscriptome regulation 
    * Chemical modification of snRNAs – Warda et al (2017) showed that the m<sup>6</sup>A writer protein METTL16 N<sup>6</sup>-methylates A43 of U6 snRNA, which is involved in base pairing with the 5’ splice sites of pre-mRNAs during splicing ⇒ possible regulator of splicing
    * Zhao et al (2014) – M<sup>6</sup>A is enriched in exonic regions flanking 5’- and 3’-splice sites that overlap with ESEs. When FTO protein was depleted in mouse pre-adipocytes,  m<sup>6</sup>A levels were enhanced, promoting recruitment of SRSF2 → increased inclusion of target exons. 
* Chromatin effects
    * Histone modifications can affect RNAP II elongation speed, which can affect splicing (see above)
        * Repressive histone marks can recruit heterochromatin-associated protein HP1-α, which slows RNAP II → change splicing patterns (Allo et al 2009) 
    * There are adapter proteins that link specific histone modifications to splicing factors
        * E.g. MRG15 is a histone-binding adapter protein that binds to H3K36me3. It recruits the splicing repressor PTB/hnRNPI (Luco et al 2010) 
    * Some chromatin binding/remodelling proteins sometimes interact with splicing factors or spliceosome components  
        * E.g. CHD1 and U2 snRNP (Sims et al 2007) 