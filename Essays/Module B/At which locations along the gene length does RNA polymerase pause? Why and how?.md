**At which locations along the gene length does RNA polymerase pause? Why and how?**

# Introduction 
Transcription is not a continuous process. Rather, in both prokaryotes and eukaryotes, RNA polymerase (RNAP) pauses at different positions along a gene, mostly to allow for regulation of transcription. These positions include the promoter region, regions proximal to the promoter, as well as at the terminus of the gene. 

# 1. At the promoter for assembly of the preinitiation complex

In the  eukaryotic stepwise model of preinitiation complex assembly, RNAP II does not immediately begin elongation once recruited to the promoter by TFIIF (Figure 1). Additional general transcription factors, TFIIE and TFIIH, have to be recruited to assemble the complete preinitiation complex, as they are required for promoter melting and clearance. Until their recruitment, RNAP II would not be able to escape the promoter and is thus stalled at the promoter until it can begin elongation. The reason RNAP II cannot escape the promoter on its own is that the Pol II PIC has very extensive protein-DNA interactions, such as interactions involving the TFIIF Rap30 subunit and the TFIIB B-finger domain. TFIIH breaks these protein-DNA interactions as the XPB helicase subunit rotates downstream DNA relative to the protein-DNA interactions to unwind the intervening DNA. Moreland et al (1999) demonstrated the TFIIH requirement for promoter escape using an XPB mutant lacking helicase activity, and a promoter with a pre-melted -9 to +1 region. Promoter escape was determined if the RNAP II was able to synthesize an 18-nucleotide 3’-O-MeG terminated RNA transcript. Compared to the wild type, the XPB mutant had much lower levels of 18nt RNA transcript synthesis, suggesting that without TFIIH activity, RNAP II is stalled at the promoter and cannot begin elongation. 

![[Pasted image 20230525002211.png]]
Figure 1: Assembly of the preinitiation complex. 

# 2. Promoter proximal pausing 

In higher eukaryotes, RNAP II may pause again after promoter escape at a region close to the promoter (+20-50). This is known as promoter proximal pausing. Kwak et al (2013) used a technique called PRO-seq to map the positions of paused elongation complexes – they used biotinylated NTPs in nuclear run-on reactions, which allowed them to identify the locations of elongation complexes to base pair resolution. This experiment demonstrated that elongation complexes accumulate immediately downstream of the transcription start site. Some genes had pausing occur at sites that were more proximal and focused, while others have more distal and broader pausing regions, and the type of pausing site depended on the arrangement of core elements within the promoter. 

At the pause region, two pausing factors, DSIF and NELF, associate with RNAP II to form the paused elongation complex (Figure 2). Using cryo-electron microscopy, Vos et al (2018) found that in the paused elongation complex, the DNA-RNA duplex has a tilted conformation, which pauses transcription because there is no DNA template base in the active site of RNAP II that can anneal to a free ribonucleotide triphosphate. NELF itself also restricts the movement of RNAP II by associating with different modules within RNAPII. 

![[Pasted image 20230525002217.png]]
Figure 2: Paused elongation complex. 

Currently, several functional explanations have been proposed for proximal promoter pausing. One reason could be that positioning a paused elongation complex helps maintain a permissive chromatin state. For example, Gilchrist et al (2008) depleted cells of NELF via RNAi and identified genes that were down-regulated by this depletion using microarrays. When ChIP was used against histone H3 at these down-regulated genes, they found an increase in H3 quantity at the promoters of these genes, which suggests that when paused elongation complexes are lost, they are replaced by nucleosomes. 

Secondly, pausing the elongation complex allows for rapid activation of gene expression. As the elongation complex has already been assembled, the gene can be quickly switched on upon the binding of transcription activators that associate with P-TEFb. Compared to the process of assembly of the preinitiation complex followed by promoter melting and clearance, this is a faster way to activate the gene. [[more details here](https://www-nature-com.ezp.lib.cam.ac.uk/articles/ng.2007.21)] 

Thirdly, the paused elongation complex represents an additional point of regulation for transcription in eukaryotes as RNAP II has to be released from pausing in order for transcription to continue. In paused genes, at least two transcription activators  would be required, one that recruits general transcription factors (e.g. SP1), and another that releases the elongation complex from pausing (e.g. Myc). 

Fourthly, pausing provides a time window to check for and ensure correct 5’ processing of the RNA. 5’ capping usually occurs during the early stage of transcription when the RNA product is 20-30nt in length, and it has been found that most RNAs produced by paused elongation complexes are capped. Rasmussen et al (2003) demonstrated this with _Drosophila_ heat shock proteins. In _Drosophila _cells, nuclear run on assays found a set of transcripts between 20-30 nt long that existed in both heat shocked cells and non-heat shocked cells, suggesting that the RNA polymerase has paused early in elongation. These short transcripts were largely 5’ capped – using tobacco acid pyrophosphatase which removes 5’ caps, the transcripts were found to be reduced in length when run on a gel. Pausing may also ensure that the RNAP II C-terminal domain (CTD) is appropriately phosphorylated for binding by 3’ RNA processing factors. In particular, P-TEFb not only releases the complex from pausing, but also phosphorylates the paused Pol II, which may couple pause release to Pol II phosphorylation. 

# 3. At the end of the gene during termination

At the end of the gene, termination occurs in prokaryotes to stop transcription of the gene, allowing RNAP to dissociate from the template DNA and release the RNA product. This can occur in a Rho-independent or Rho-dependent manner. 

In rho-independent termination (Figure 3), RNAP pauses when it reaches the 3’ end of the gene due to the formation of a GC rich hairpin that is followed by a series of A residues. The RNA forms a GC rich hairpin, and the RNA and template DNA dissociate due to the weak base pairing between the run of U residues in the RNA and the dA tract in the DNA. 

![[Pasted image 20230525002223.png]]
Figure 3: Rho-independent termination

In rho-dependent termination (Figure 4), the Rho protein is required for transcription to end. The protein binds to the end of the RNA chain, then translocates along the RNA until it reaches RNAP to induce dissociation. In this case, RNAP pauses at a hairpin structure near a C-rich region, which gives Rho factor time to catch up to RNAP. 

![[Pasted image 20230525002231.png]]
Figure 4: Rho-dependent termination

Pausing of RNAP during termination may also serve to regulate the transcription at a downstream gene. This can occur when the termination site is near or overlaps with the promoter of a downstream gene. Palmer et al (2009) describe this phenomenon, known as _occlusion_, in the bacteriophage λ promoter pair P<sub>R</sub> and P<sub>RE</sub>. RNAP that began transcription from the P<sub>R</sub> promoter was able to inhibit transcription from the P<sub>RE</sub> promoter by pausing at the Rho-dependent terminator, tR1. They confirmed this pausing by using KMnO<sub>4</sub> footprinting, which can identify the position of RNAP by chemically labeling ssDNA regions. As termination at tR1 occurs at three positions located over the P<sub>RE</sub> promoter, pausing of RNAP during this process occludes P<sub>RE</sub>. 

![[Pasted image 20230525002234.png]]
Figure 5: RNAP pausing resulting in occlusion of the P<sub>RE</sub> promoter.

Occlusion may also occur in mammalian cells – Racanelli et al (2008) suggested that occlusion may occur between tandem promoters of the mouse FPGS gene. 

# **Conclusion**

RNAP II pauses at various points along the gene length, mainly for regulatory reasons, allowing genes to achieve a wide range of transcriptional activity. Disruptions to RNAP pausing can even lead to cellular dysfunction, [such as in cancer](https://www-nature-com.ezp.lib.cam.ac.uk/articles/ncomms15908), which highlights the importance of this regulatory mechanism. Future research on RNAP II pausing could continue to focus on pauses that occur during elongation, which was once thought to be a fully processive activity. In particular, questions remain on what determines the locations of pausing sites during elongation, whether there are other types of paused complexes, how promoter proximal pausing is regulated, and the physiological significance of this regulation. 


---

# Other points (from supo) 

* **Promoter**
* Abortive initiation
    * How to detect?
    * Nuclear run on assay
        * BrdU – lower resolution
    * Precision run-on assay sequencing (PRO-seq)
        * Biotinylated pull down for sequencing
        * Biotin is a large molecule – cannot extend RNA further after addition of a biotinylated nucleotide
* **Promoter proximal**
* During transcription
    * RNA repair in case of misreading – TFIIS (eukaryotes), NusA/NusG (prokaryotes)
* **Termination**
    * Attenuation
* DNA damage
* In exons for splicing
* Transcription roadblock (heterochromatin)
* Steric hindrance between multiple RNAP
* Critical view of ChIP-seq data – are other techniques needed?
* Differences in pausing between different species 

Bolded = discussed in my essay 

See Pro-Seq (Kwa et al 2012) study for more examples of pausing 

# **Unused stuff: **

There are two reasons RNAP may pause near the promoter. Firstly, in prokaryotes, RNAP may pause at an operon during a regulatory process known as attenuation, which causes premature termination of transcription. This is best illustrated with the example of the _Trp_ operon, which encodes enzymes in the biosynthetic pathway to produce tryptophan. The operon contains a leader region that encodes a leader peptide with two consecutive Trp codons, as well as 3 stem-loop forming regions (Figure 2). Elements 3 and 4 are followed by a poly(U) track and form a rho-independent terminator hairpin. 


![[Pasted image 20230525002337.png]]
Figure 2: Diagram of the Trp operon. 

As transcription and translation can occur simultaneously in prokaryotes, a ribosome can begin translation of the leader region as soon as RNAP has transcribed it. However, when levels of Trp are high, the ribosome can quickly translate the leader peptide and then falls off the mRNA, allowing the terminator hairpin (3:4) to form to terminate transcription. 

In eukaryotes, pausing near the 3’ end of the gene also facilitates transcriptional termination. Ashfield  et al (1994) identified a sequence downstream of the poly(A) signal in some genes known as a MAZ element which consists of G<sub>5</sub>AG<sub>5</sub> which interacts with the MAZ protein. 

**3. In the middle of the gene **

RNAP may pause yet again in a more downstream region of the gene, midway through elongation. 

Middle of the gene 



* Transcriptional pausing 
    * Due to cotranscriptional splicing in yeast ([Alexander et al 2010](https://www-sciencedirect-com.ezp.lib.cam.ac.uk/science/article/pii/S1097276510008439))
    * Pausing in exons to facilitate splicing ([Carillo et al 2010](https://www-sciencedirect-com.ezp.lib.cam.ac.uk/science/article/pii/S1097276510008427)) 
        * Slower elongation favors inclusion of exons ([de la Mata 2003](https://www-sciencedirect-com.ezp.lib.cam.ac.uk/science/article/pii/S1097276503003101)) 
    * To allow proper RNA folding ([Hein et al 2014](https://www-nature-com.ezp.lib.cam.ac.uk/articles/nsmb.2867))