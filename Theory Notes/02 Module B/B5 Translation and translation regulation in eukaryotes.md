Combined with Dee Scadden's notes on Translation Regulation 

# Questions 
- Translation initiation 
	- ==Discuss how structural biology has advanced our understanding of translation initiation.==
- Viruses
	- Different viruses have developed unique ways of hijacking the cellular translation machinery. Discuss how these hijacking mechanisms give viruses an advantage over host translation.
		- IRES
		- cap snatching 

## Translation regulation 
- You have identified a human protein that you suspect to have a role in gene expression. The sequence of the protein contains a predicted RNA binding domain. The protein is expressed in He-La cells, and its expression can be blocked using siRNAs. Discuss how you would address the function of this protein in mRNA translation using genome-wide approaches.
- *==How do phase separation and biomolecular condensates contribute to translational regulation?==*
- 5' UTR and 3' UTR
	- You have been given the task of optimizing expression of a protein, X, in HeLa cells using a plasmid. Explain which features of the 5’ leader and the 3’ UTR of X mRNA it would be advantageous to include and which ones it would be best to avoid.
	- *==Which features of the 5’ region of an eukaryotic mRNA determine its translational efficiency and, given an mRNA sequence, how might you test that efficiency?==*
	- Discuss the role of the 3’UTR in 5’ cap-dependent translation.
	- How do interactions between the 5’-Untranslated Region (5’-UTR) and the 3’-UTR influence eukaryotic translation?
- Discuss whether or not upstream open reading frames (uORFs) always down-regulate translation of the main ORF.
- 3' UTR  
	- *==The 3’UTR of mRNAs provides diverse opportunities for regulation of eukaryotic translation. Discuss, using experimental examples.==*
	- Discuss the role of CPEB in regulating translation during early development.
	- Compare and contrast the roles of CPEB (cytoplasmic polyadenylation element binding protein) in the regulation of translation in oocytes and in eggs.
- Modification of eIFs 
	- How does phosphorylation of eIF2α result in specific regulation of translation of particular mRNA species?
	- How do eIF-4E-binding proteins regulate translation?
- Closed loop model 
	- *==Discuss the evidence for the “closed loop model” of an efficiently translated mRNA, and briefly comment on the implications this model poses for the regulation of translation.==*
	- How can sequences downstream of a stop codon influence ribosome recruitment to the 5' cap?
		- #comment This is clearly talking about the 3' UTR and the poly(A) tail 

# Process of translation in eukaryotes 
## Overview 
- Translation should be seen as a ribosome cycle: 
![[Drawing 2022-12-25 22.09.14.excalidraw.png|425]]
- Initiation – factors bring small subunit (40S) to promoter, followed by association of large subunit (60S)
- Productive elongation 
- Termination 
- Peptide release 
- Ribosome splits into small and large subunits 
- Prevention of ribosome subunits reassociation before initiation by certain factors. Factors bind to small subunit to prevent reassociation and recruit to promoters 

## Initiation 
See [[HashemFrank_2018]] for #structural_evidence 
- Involves assembly of elongation-competent 80S ribosomes, in which the initiation codon is base-paired with the anticodon loop of initiator tRNA (Met-tRNAi) in the ribosomal peptidyl site 
	- Initiator met-tRNAi is different from met-tRNAm. tRNAi is only used for initiation, while tRNAm is only used to decode internal Met codons. Initiator met-tRNAi has different sequence and structural features, allowing it to be specifically recognised by eIF2 or excluded from binding to eEF1A 

> [!image] Overview of translation initiation (Jackson et al 2010)
> ![[Pasted image 20221225225201.png]]

### Process 
1. After being split from the 60S subunit by ABCE1 at the end of termination, the recycled 40S subunit associates with eIF1, 1A, and 3, which dissociates the small subunit from the empty p-site tRNA and from the mRNA. 
	1. eIF3 acts throughout the ribosome cycle, preventing premature 60S association before initiation is complete, and stabilising the 40S-TC interactions and mRNA binding. eIF4 binds mainly to the "back" or solvent face of the 40S ribosomal subunit, but extensions and peripheral subunits mediate contacts with other eIFs, including those bound around the P site. 
2. eIF2-TC (eIF2 ternary complex) and eIF5 then bind to form the 43S preinitiation complex (PIC)
	1. eIF2-TC is a ternary complex that consists of eIF2 + GTP + Met-tRNAi. The γ subunit of eIF2 has GTP binding activity, and GTP-bound eIF2 has high affinity for methionyl tRNA 
   ![[Pasted image 20221225222407.png|400]]
3. eIF4F binds the cap structure of mRNA, and the the eIF4F helicase subunit eIF4A unwinds local cap-proximal mRNA secondary structure in an ATP-dependent manner, which is stimulated by eIF4B 
	1. eIF1A enhances formation of the cap-proximal complex 
	2. eIF4F is the cap binding complex that connects cap binding to the 43S complex. eIF4F is consists of eIF4E cap binding protein and eIF4A helicase scaffolded by eIF4G
		1. The 5' cap binds to eIF4E by stacking between two critical Trp residues, W56 and W102 
			1. Interaction between eIF4G and eIF4E triggers a conformational change in eIF4E, producing a stable complex with high affinity for the 5' cap 
		2. eIF4A is a non-processive DEAD-box family helicase that can unwind RNA bidirectionally in an ATP-dependent manner. eIF4F is much more active than eIF4A alone in terms of helicase activity – KO mutants of eIF4A (eIF4A-RQ, no ATP hydrolyis) are dominant negative. 
		3. eIF4A is located at the mRNA exit channel, acting as a backstop to ensure that the mRNA moves unidirectionally during scanning 
	3. eIF4G scaffold also interacts with PABP in [[B5 Translation and translation regulation in eukaryotes#Closed loop model of translation|Closed loop model]], resulting in synergistic effect of poly(A) tail and cap on translation 
4. The 43S complex (PIC) associates with the mRNA at the 5' end of the mRNA to form the 48S complex. eIF4F may directly recruit 43S via eIF3 
5. 48S complex **[[B5 Translation and translation regulation in eukaryotes#Ribosome selection of AUG – scanning ribosome model|scans]]** along the 5' UTR (requires ATP) in the 5' to 3' direction until the anticodon of Met-tRNAi interacts with the initiator AUG codon, which is usually the cap-proximal AUG 
	1. eIF1 and 1A induce a scanning competent "open conformation" 48S complex by inducing a conformational change in the 40S subunit that opens the mRNA binding channel. In apo-40S, there is a non-covalent "latch" between rRNA elements of the "head" and "body" of apo-40S that clamp around mRNA. eIF1 and 1A promote the formation of a new connection between rRNA and the ribosomal protein on the solvent side that prevents this latch from forming. As a result, the open latch makes the mRNA entry channel more accessible, allowing mRNA to dock into the channel directly 
	2. The open conformation is conducive to scanning with the TC in a metastable state that can sample successive codons that enter the P=site 
	3. eIF1 also antagonises a "closed conformation"
	4. The start codon is commonly AUG, but it may also rarely be CUG, ACG, GUG
	5. eIF1 is important in ensuring the correct initiation codon selection, with mutations in eIF1 resulting in increased initiation at non AUG codons (Pestova et al 1998) 
6. When the 48S subunit reaches the start codon, base pairing occurs in the P site between met-tRNAi anticodon and the start codon. Start codon recognition, along with eIF1 displacement from the initiation complex by eIF5 NTD, induces 48S complex to rearrange to a "closed conformation" due to the re-formation of a non-covalent "clamp" around the mRNA 
	1. Since eIF1 antagonises the closed complex, ejection of eIF1 is necessary for closed conformation. 
	2. eIF5 NTD binds the pocket vacated by eIF1, which stabilises the orientation eIF2-TC and the codon:anticodon duplex 
	3. The closed complex is incompatible with scanning, and results in tighter binding of Met-tRNA to the P-site 
	4. In the absence of eIF1 and 1A, 40S subunit stalls a short distance downstream of the cap then slowly dissociates from mRNA, probably because the 48S subunit does not have an open conformation 
8. eIF5 is a GTPase-activating protein (GAP) for GTP-bound eIF2, and induces hydrolysis of eIF2-bound GTP on recognition of the initiation codon, leading to loss of affinity for met-tRNAi so that eIF2-GDP is released. 
	1. In most proteins, the N-terminal Met is removed by methionine aminopeptidase (MetAP), and the specificity of Met cleavage depends on the nature of the next residue – if the next residue is A, C, G, P, S, T, or V, cleavage is likely to occur. 
9. eIF5B catalyses 60S subunit joining 
10. All other eIFs dissociate
11. 80S ribosome is now assembled on mRNA with AUG in P site 

## Termination 
### Ribosome disassembly 
![[Pasted image 20221225222052.png|475]]
1. Upon recognising a stop codon, termination occurs. 80S ribosome associates with eRF1 and possibly eRF3, with deacylated tRNA in the P site 
2. ABCE1 helicase splits small subunit from large subunit in an ATP-dependent manner 
3. Large subunit is ejected from mRNA, while 40S subunit is still bound to mRNA with P site tRNA 
4. eIF1, 1A, and 3 are recruited to 40S subunit during ribosome recycling. They can eject the P-site tRNA and release the mRNA from the 40S subunits. eIF3j subunit promoters the release of 40S/eIF3 from mRNA. 

# Studying translation 
## Protein-RNA interactions
See [[B1 Transcription#Application to RNA-binding proteins]]

## Translation reporting systems  
- In vitro, cell-free systems e.g. rabbit reticulocyte lysate 
	- Translation can be reported by adding *in vitro* transcribed mRNA, along with <sup>35</sup>S-Met to allow for visualisation via autoradiography on SDS PAGE 
	- alternatively, report translation using reporter assays, e.g. Firefly/Renilla luciferase assay 
- In vivo systems – cells can be transfected with plasmid DNA, or injected with *in vitro* transcribed mRNA (which may be useful for controlling mRNA levels in the cell)
	- Monitor translation in cells with <sup>35</sup>S-Met labelling or use reporter assays, as above 

> [!warning] Using heterologous systems
> Heterologous systems can be useful for reporting translation efficiency, e.g using Fluc or Rluc fused to an endogenous promoter. However, we cannot study the effect of coding regions on translation efficiency e.g. codon optimality 

## Polysome analysis 
- Highly translated mRNAs have more ribosomes bound than ones that are less translated. Different polysome species with different numbers of ribosomes can be separated via ultracentrifugation on sucrose gradients
- RNA from each fraction can be isolated and analysed with Northern Blot or by RT-PCR
- Proteins from each fraction can be separated with SDS-PAGE, then identified with Western Blot 
![[Pasted image 20221225231432.png|375]]

## Ribosome profiling 
- Basically footprinting of ribosomes on mRNA.
- Used to determine the position of ribosomes throughout the transcriptome with subcodon resolution 
- Translating ribosomes and mRNAs are purified from a cell type of interest by fixing ribosomes in place. Then polysomes are treated with nuclease to fragment translating mRNAs. Parts of the mRNA that are bound to ribosomes are protected from nuclease degradation, and so survive to purification. These ribosome footprints can then be sequenced and mapped to a reference transcriptome. The higher the number of reads, the greater the tendency for ribosomes to bind to that particular position on an mRNA transcript  
- Footprint fragments are ~28 nt
- Along a given mRNA, the 5' ends of footprint fragments start 12-13 nt upstream of the start codon, and end 18 nt upstream from stop codon, along with showing strong 3-nt periodicity 
	- The reason this occurs is that when the 40S subunit binds to AUG, the AUG is always located in the P site, and the subunit footprints 28 nt at a time 
	- And just before termination, ribosome is positioned with P site 2 codons before stop codon (ribosomes are not found positioned on the stop codon since that results in termination and ejection of the ribosome, so this is the last possible binding site on the transcript) 
	  ![[Pasted image 20221226000710.png|250]]
- From same sample, can also do mRNA-seq  
- #experimental_evidence Ingolia et al (2009) – Used ribosome profiling to monitor translation in budding yeast in rich and starvation conditions. 

![[Pasted image 20221225233519.png|500]]

### Key findings from ribosome profiling 
- mRNA seq and ribosome profiling data can be used to calculate the ratio of ribosome footprint density to mRNA density (i.e. rate of translation to mRNA abundance), which is a measure of translation efficiency. It was found that there is a 100-fold range in translation efficiency between different yeast genes, a disparity that is invisible to mRNA abundance measurements (e.g. microarrays, qPCR)
- Ribosome profiling is precise enough to determine the reading frame being translated by determining which nucleotide the ribosome begins translation from; Ingolia et al (2009) found that in yeast, 75% of the 28-nt oligomer ribosome-protected fragments started on the first nucleotide of a codon 
- Ribosomes tend to stall at particular sequences, e.g. poly Pro
- Elongation rate does not differ much between mRNAs 
- Translation initiation is heterogenous and does not always occur at the first AUG, or even at an AUG all the time
	- Alternative initiation sites could be attributed to leaky scanning, or AS variants 
- Evidence of very short uORFs upstream of the main ORFs that are initiated at AUG and non-AUG codons 
	- Many of these non-AUG uORFs are induced upon starvation 

## *In vitro* reconstitution of initiation  
- To study the role of different factors in initiation 
- Incubate different combinations of components, e.g. purified ribosomal subunits, purified initiation factors, (<sup>35</sup>S)Met-tRNAi, (<sup>32</sup>P)-mRNA, GTP, ATP (or their non-hydrolysable counterparts GMPPNP, AMPPNP)
- Then determine whether the ribosome binds to the mRNA using sucrose gradients 
- Or, determine whether it binds at the correct site using **toeprinting assay**, which is similar to footprinting assay 
	- After incubating ribosomal subunits, initiation factors, etc. with mRNA, add <sup>32</sup>P primer, dNTPs and AMV reverse transcriptase. The RT will only reverse transcribe DNA up to the point where the ribosomal subunit is bound to the mRNA. The <sup>32</sup>P-labelled cDNA can then be purified and run on a urea (denaturing) gel. The length of the cDNA indicates where reverse transcription stopped, and hence where the 48S complex has bound 
	  ![[Pasted image 20221225232854.png|575]]
	- #experimental_evidence Pestova et al (1998) first reported that eIF1 and eIF1A are essential to translation initiation using toeprint assays. 

## Determining rates of translation efficiency 
- Pulse labelling of protein and mRNA 
	- #experimental_evidence Schwanhäusser et al (2011) used pulse labelling of proteins and mRNA to determine the rates of translation at a genome wide scale. The rates for proteins were determined using SILAC and for mRNAs using 4-thiouridine (4sU) incorporation into nascent mRNAs. H/L ratio / time gives a measure of protein half-life, while ratio of newly synthesised/total RNA to pre-existing RNA/total RNA gives a measure of mRNA half-life. 
	- [[A1 Mass Spectrometry and Proteomics#Stable isotope labels]]
	  ![[Pasted image 20221227175250.png|300]]

## Translation Complex Profile sequencing (TCP-seq)
### Procedure
1. Cryolysis to break upon cells 
2. Cross link RNA to protein using formaldehyde 
3. Ultracentrifugation of lysate in a density gradient and extract the fraction containing the 80S ribosome bound to RNA, polysomes 
5. RNAse digest to get ribosome protected footprints 
6. Run a second density gradient to separate SSU (small subunit) fraction from RS fraction 
7. Deep sequencing of RNA bound to SSU and RS fractions and map to transcriptome 
![[Pasted image 20221227181635.png|325]]
### Findings 
#experimental_evidence Archer et al (2016)
- Scanning is unidirectional from 5' to 3' 
- The scanning SSU footprint is greater than that of the complete ribosome (RS) can be up to 75 nt, which is beyond the width of SSU alone. Footprint patterns suggests interactions between SSU and mRNA emerging from the exit channel which promote forward movement 
- Multiple SSUs may scan the same 5' UTR once, as it was observed that longer 5' UTRs harbour more SSU 

## Selective TCP-seq 
- This method is used to determine the positions on mRNAs where initiation factors join the ribosome to act and where they leave. 
- Combines immunoprecipitation of eIFs with TCP-seq in human cells (Bohlen et al 2020). Following ultracentrifugation of human cell lysate into SSU and RS fractions, each fraction was treated with eIF-ribosome IP, then the pulled down RNA was deep sequenced 
  ![[Pasted image 20221227155413.png|625]]

# Sequence-dependent translation regulation
## Overview 
- Translation needs to be regulated to allow for rapid responses to stimuli 
- Schwanhäusser et al (2011) reported that the cellular abundance of proteins is controlled mostly at the level of translation
	- There is poor correlation between mRNA and protein levels 
- In early development, translational regulation is more important than transcriptional regulation. Transcription is not possible in early development, as chromatin is highly compacted to allow for rapid division. Instead, mRNA inherited from the oocyte is translated to synthesis proteins in the developing embryo. 
	- E.g. in *Xenopus* oocytes, no transcription occurs during oocyte (meiotic) maturation from oocyte to egg because the chromosomes are highly condensed. There is also no transcription in early embryogenesis until the mid-blastula transition 
- Translational regulation is also important for localised regulation of gene expression (see [[B2 RNA localisation]])
	- E.g. Transcription in the nucleus is too distal to the tips of dendrites or axons. Faster responses in gene expression can be achieved by regulating translation of mRNA that has been localised to the tips. 
- Translation initiation should play a dominant role in translation regulation since it results in less resource waste 
- Sources of mRNA regulation 
	- Transcript abundance 
		- Transcriptional efficiency 
		- Rate of degradation 
	- Translational efficiency
		- 5' cap 
		- polyA tail 
		- 5' UTR
		- 3' UTR 
		- uORFs 
		- mORFs 
		- mRNA structure 
		- miRNAs 
		- Epitranscriptomics 

## Ribosome selection of AUG – scanning ribosome model  
- The scanning ribosome model explains how the ribosome selects which AUG to initiate translation from 
- The 43S complex binds proximally to the 5' cap and scans unidirectionally until it encounters the first AUG in an <u>optimal context</u>, i.e. when it recognises a Kozak sequence 
	- The Kozak sequence is the consensus sequence for protein translation initiation. The nucleotides in the Kozak sequence stabilise interactions with components of the 48S initiation complex (specifically eIF2A and 18S rRNA)
	- Kozak sequence = GCC(A/G)CC<u>AUG</u>G
	- #experimental_evidence Kozak (1986) made point mutations around an upstream, out-of-frame ATG codon in a cloned preproinsulin gene, and it affected the efficiency of initiation at the ATG compared to the normal start site. 
- #experimental_evidence  for scanning ribosome model 
	- If an additional AUG is inserted upstream of the normal initiation site, initiation occurs at the newly introduced AUG 
	- Uncapping reduces initiation efficiency but first AUG is still selected 
	- 40S ribosomes do not bind to circularised mRNA unless it has an IRES 

### Exceptions to scanning model 
- If first AUG is very close to the cap (<10 nt), initiation can occur at a downstream start site 
  ![[Drawing 2022-12-27 01.22.39.excalidraw.png|425]]
- Downstream secondary structures at an appropriate distance (~18nt) improves the recognition of a poor context AUG
	- A strong stem-loop structure just downstream of start codon stalls the scanning 40S subunit, which increases its dwell time and thus decreasing the likelihood of leaky scanning through near-cognates or AUG in poor context 
  ![[Pasted image 20221227012506.png|350]]
- Under certain contexts where AUG is followed by a short ORF before the main ORF 
- Use of non-AUG near cognate codons – if they have optimal context and/or secondary structure at an appropriate distance downstream 
- CUG can usually be decoded by met-tRNA<sub>i</sub> when used as the start codon, but during the synthesis of antigenic precursors for loading on MHC complexes, leucyl-tRNA can be engaged by a scanning PIC. This relies on the noncanonical initiation factor eIF2A instead of eIF2 

## Factors affecting translation initiation efficiency 
### RNA secondary structure can block scanning 
- RNA secondary structure can be inhibitory to translation as they can block the 43S complex from scanning down the mRNA 
- The extent to which the secondary structure inhibits translation is affected by 
	- GC content of RNA – more GC, more difficult to unwind, more inhibitory 
	- Hairpin length – longer hairpins are more difficult to unwind and so are more inhibitory 
	- Cap-proximity of hairpin – the closer the hairpin is to the cap, the more inhibitory it is 
- However, if an AUG is found within a hairpin, it will be used preferentially to downstream AUGs as long as it is the cap proximal one. This is because the scanning ribosome unwinds secondary structure (using eIF4F helicase subunit, eIF4A), and does not just skip over AUGs in hairpins
	- 43S complex without eIF4F can scan unstructured mRNA. In vivo most mRNA has secondary structure so eIF4F becomes essential 
	- #experimental_evidence Pestova & Kolupaeva (2002) showed that the 43S complex (40S, eIF1, eIF1A, eIF2-TC and eIF3) can bind to the 5' end of an unstructured 5' UTR, and  scan along it to locate the initiation codon. They engineered GUS mRNA to have a 5' UTR with a (CAA)<sub>19</sub> sequence that does not contain secondary structure. Toeprinting assay was then used to check for scanning. 

![[Pasted image 20221227152037.png|575]]

### Other factors 
- Accessibility of structure – lack of cap-proximal structure 

## Cap-independent initiation
- Most cellular mRNAs and viral mRNAs are translated by the scanning ribosome mechanism 
- However, some (mainly viral RNAs) are translated by a mechanism of direct 40S subunit entry at a lengthy internal ribosome entry site (IRES) in the 5' UTR of the viral mRNA that is far from the 5' end
	- Some cellular mRNAs may also have IRESs, e.g. BiP, FGF, VEGF, c-myc, Hox, *APAF1*
- #experimental_evidence Chen & Sarnow (1995) demonstrated that initiation can start from a picornavirus IRES using a bicistronic mRNA assay. When a picornavirus IRES was inserted at the 5' end of a downstream cistron, both cistrons were successfully translated. 
  ![[Pasted image 20221227155905.png|550]]

### Mechanism of initiation in viruses 
- The mechanism of initiation differs between virus strains
- Cap-independent internal initiation allows viruses to suppress translation of capped host cell mRNAs without suppressing their own translation 
- In **picornaviruses** (e.g. **EMCV**), initiation on IRES requires all canonical initiation factors except eIF4E (since it is the cap binding protein) and the full length eIF4G can be replaced by its C-terminal P100 or P50 fragments. eIF4G/p50/p100 (as part of eIF4 complex) binds tightly to the IRES J and K 3-way junction, then recruits 43S complex to the vicinity of the initiation codon via interaction with eIF3 ![[Pasted image 20230517222416.png]]
	- Many picornaviruses (including EMCV) encode a protease that cleaves eIF4G into a C-terminal p100 fragment and N-terminal fragment that contains the eIF4E binding site. This prevents translation initiation for capped host cell mRNAs, since eIF4G is no longer able to scaffold the cap-binding eIF4E to form the eIF4F complex, thus preventing recruitment of 43S complex to the cap. However, internal initiation of translation of viral RNA is still possible, since IRES initiation only requires p50/p100, and for many IRESs initiation is actually stimulated. 
  ![[Pasted image 20221227160929.png|350]]
- For **HCV and pestivirus** IRES, the 40S subunit can bind to the IRES at the correct AUG in the absence of eIF4(A,G,E), eIF1, eIF1A, or ATP, but does require eIF2-TC, as well as eIF5 and 5B for joining of the large and small ribosomal subunits. The IRES binds eIF3 but not to recruit 40S, but rather to prevent its assembly into a 43S complex, thus reducing cellular translation. ![[Pasted image 20230517222432.png]]
- **Discistrovirus** (e.g. cricket paralysis virus) IRES is intergenic, and can directly recruit 80S without any initiation factors or initiator tRNA. ![[Pasted image 20221227161723.png|175]]
	- Instead of initiator tRNA occupying the ribosome P site, the IRES forms a triple pseudoknot structure that occupies the P site. ![[Pasted image 20230517222445.png]]
	- An Ala-tRNA is delivered to the A site by eEF1A/GTP/Ala-tRNA complex, and a pseudo-translocation event that requires eEF2 and GTP transfers the Ala-tRNA to the P-site. 



### Cap-independent initiation in HOX 5' UTR 
- Cellular IRES-like structures allow for translation when cap-dependent translation is compromised 
- In the 5' UTR of a subset of Hox mRNAs, there is a translation inhibitory element (TIE) as well as an IRES-like element. TIE blocks cap dependent translation. 
  ![[Pasted image 20221227162421.png|475]]
 - #experimental_evidence Xue et al (2015) engineered a monocistronic Fluc reporter fused to a beta globin 5' UTR with TIE embedded to show that TIE inhibits translation. In addition, they used a bicistronic mRNA assay to demonstrate that the IRES-like element allows for internal translation initiation. 
   ![[Pasted image 20221227162618.png]]
   
   ![[Pasted image 20221227162607.png|375]]
- However, virus-like IRES elements are arguably rare, and the mechanisms of recruitment are not as well understood as viral IRES. Rather than initiating from an IRES, Shatsky et al (2018) suggest that uncapped mRNAs are scanned from the 5' end, with RNA elements acting as binding platforms for other factors, and so act more as "cap-independent translation enhancers" (CITEs) rather than IRESs. Such a mechanism could be useful when cap-recognition is inhibited, or when eIF2 activity is reduced 
	- E.g. N6-methyladenosine modification can act as a CITE. #experimental_evidence Meyer et al reported that eIF3 tends to bind to N6-methyladenosine within GAC motifs 

## Upstream ORFs and re-initiation 
- Translation re-initiation is the phenomenon where the small ribosomal subunit remains attached to the mRNA following termination of translation, and resumes scanning on the same mRNA molecule to initiate again (re-initiate) at a downstream start site. 
- Re-initiation of translation can occur after a short upstream open reading frame (uORF)
	- 40-50% of mammalian mRNAs have uORF(s), and many encode proto-oncogenes, TFs, growth factors, retroviral mRNAs 
	- Requires rapid translation of the uORF, suggesting that the critical parameter for reinitiation is ribosome transit time, rather than uORF length 
- Rarely, reinitiation can occur after a long ORF, but this only occurs with a few specific mRNAs, so a specific cis-acting RNA sequence may be required 

### Mechanism of reinitiation 
- uORF start codons lack Kozak sequences, suggesting that uORF initiation occurs via leaky scanning. 
	- #experimental_evidence Chew et al (2016) used ribosome profiling studies to sequence uORFs 
- Efficient reinitiation requires eIF4F (and particularly, eIF4G p50) to participate in the primary initiation event at the uORF initiation codon 
	- #experimental_evidence Poyry et al (2004) – Created a reinitiation construct with a uORF and mORF. Then tested efficiency of re-initiation in constructs with a scanning-dependent 5'UTR and different viral IRESs that require only a subset of initiation factors. Found that re-initiation does not occur if eIF4F complex is absent. 
	- However, reinitiation can occur in the absence of eIF4F if the 5' scanning UTR was replaced with an unstructured (CAA)<sub>19</sub> 5'UTR (removing the need for eIFA) and if eIF4G p50 was present, suggesting that eIF4G is the critical component of eIF4F for re-initiation 
- This implies that the 40S/eIF3/eIF4G interaction is not disrupted immediately when initiation occurs, but persists briefly, and if this interaction persists until uORF translation is completed, it can retain the 40S subunit on the mRNA post-termination to promote continued scanning 
	- #experimental_evidence Bohlen et al (2020) used selective TCP-Seq to show that eIF3B, eIF4G1, and eIF4E remain bound to 80S ribosomes as translation begins, and have a decay half-length of ~12 codons, allowing them to be retained on the ribosome post-termination for reinitiation 
![[Pasted image 20221227165238.png|625]]

### Factors affecting reinitiation efficiency 
- **Time taken to translate uORF** is the critical parameter for reinitiation efficiency. This could be affected by 
	- Length of uORF
	- Rate of ribosome elongation through uORF 
- **Distance between uORF and mORF**: After termination of uORF translation, the 40S subunit that resumes scanning will initially lack any associated eIF2-TC, but it can acquire a ternary complex during the course of scanning. If uORF and mORF are further away from each other, there is a greater probability that the scanning 40S can acquire eIF2-TC, increasing reinitiation efficiency 
- **Concentration of eIF2-TC**: if the concentration of available eIF2-TC is low, the 40S subunit may scan more than 200 nt before acquiring Met-tRNAi, and could bypass several AUG codons on the way, which decreases reinitiation efficiency. 

### Effect on mORF initiation 
- Having one or more uORFs in an mRNA downregulates translation of the mORF if the uORF start codon is recognised by scanning 48S 

## 5' UTR and cap 
- Regulation in 5' UTR is rarer than in 3' UTR 
Some examples: 

### Terminal Oligo Pyrimidine tract (TOP) mRNAs 
- TOP mRNAs are repressed in quiescent cells and translationally activated in serum-stimulated cells via a poorly defined mechanism involving mTOR 
- These mRNAs contain an oligopyrimidine tract at the 5' terminus, the 5' TOP motif, that starts with C (whereas most mRNAs have G or A as first transcribed nt)
  ![[Pasted image 20230121172105.png|250]]
- TOP mRNAs encode components of translational machinery, e.g. ribosomal proteins, translational elongation factors 

### Autoregulation of PABP
- PABP can inhibit translation of its own mRNA via an A-rich tract in its 5' UTR (mimics poly(A) tail)
- Presumably, prevents scanning? #question 

![[Pasted image 20230121172220.png|475]]

### Iron response elements (IREs)
- Some mRNA (e.g. ferritin mRNA) contain iron response element (IRE) hairpins (usually multiple) in the 5' UTR which recruits iron regulatory protein (IRP)
	- In ferritin, the IRE is usually ~40nt from the 5' end – the distance is important for the function of the IRE 
- IREs can also be found in 3' UTR of some proteins (e.g. transferrin receptor), often in multiple copies depending on the particular mRNA 
- Presence of stabilised IRE hairpin in the 5' UTR blocks translation. However, the IRE itself is not stable enough, and has to be stabilised by IRE binding proteins (i.e IRPs 1&2) 
	- IRP1 has two functions – it acts as an IRE binding protein but also as a cytoplasmic cis-aconitase. When iron levels are low, there are insufficient iron-sulfur clusters present, resulting in dissociation of the iron-sulfur clusters from IRP. The conformation changes such that it cannot act as an aconitase but can bind to IRE, thus blocking the translation of ferritin and reducing iron sequestration 
	- IRP2 binds to IRE when iron levels are low, but is degraded when iron levels are high 
	- IRP 1 and 2 act in different tissues in mice, and double knockout is lethal to the embryo 

#### IRE in 5' UTR (e.g. ferritin)
- Low iron levels – IRP/IRE interaction decreases translation by preventing 43S recruitment to eIF4F complex by steric hindrance 
	- Cap-proximal position of IRE (less than 40nt) is important for this mechanism – if too far away then it cannot block 43S recruitment 
		- #experimental_evidence Paraskeva et al (1999) – used CAT reporter mRNAs with IREs at various distances (34-100 bp) from the cap and translated the mRNAs *in vitro* with rabbit reticulocyte lysate. As the distance between the cap and IRE increased, the IRP became less effective at blocking translation 
	- The effect is also **purely steric** and generalisable as any cap-proximal block composed of stem-loop and binding protein will impede 43S recruitment 
		- #experimental_evidence If IRE is replaced with a different stem loop (e.g. U1 snRNA, MS2 hairpin), repression of the reporter mRNA expression can be observed if the cognate protein is present (e.g. U1A protein, MS2 coat protein) as they also can prevent 43S recruitment to eIF4F complex via steric hindrance. There is a similar position effect (i.e. short distance from cap is necessary)
- Under high iron levels, IRP1 is converted into an aconitase containing Fe-S cluster, and IRP2 is degraded by proteosome, allowing translation to occur
	![[Pasted image 20230121174936.png|500]]

#### IRE in 3' UTR (e.g. transferrin receptor)
- Transferrin receptor mediates uptake of iron 
- Low iron conditions – binding of IRP to multiple IREs in 3' end increases its translation by protecting the TfR1-mNRA from endonucleolytic cleavage and degradation  
- High iron conditions – IRP1 is converted into an aconitase containing Fe-S cluster, and IRP2 is degraded by proteosome, allowing for mRNA degradation 

## Poly(A) tail 
### Functions 
- Enhance translation 
- Control translation in development
- Determine mRNA stability [[B6 Cytoplasmic RNA decay]]

### Poly(A) tail enhances translation 
- Cytoplasmic polyadenylation is required for translation activation 
	- #experimental_evidence Barkoff et al (2000) injected a fusion luciferase reporter + cyclin B1 3' UTR-poly(A) mRNA into oocytes, followed by progesterone to induce maturation of oocytes to eggs. The reporter mRNA was polyadenylated and its translation was stimulated in eggs (i.e. when progesterone was injected).  ^b4ef15
- #experimental_evidence Gallie (1991) – Electroporated luciferase mRNAs into CHO cells. mRNA with poly(A) tails exhibit higher rates of translation 
- Acts synergistically with cap at 5' end of mRNA (due to [[B5 Translation and translation regulation in eukaryotes#Closed loop model of translation|Closed loop model]])
	- #experimental_evidence Gallie (1991) – Luciferase mRNAs with both cap and tail had higher translation efficiency than sum of translation efficiencies of mRNAs carrying either modification by itself 

### Poly(A) tail synthesis
- Cytoplasmic polyadenylation is catalysed by ==GLD2==, a poly(A) polymerase, and ==CPSF== (Cleavage and Polyadenylation Specificity Factor)
- The activities of GLD2 and CPSF depend on the presence of CPEs (U-rich cytoplasmic polyadenylation elements (==CPEs==) in the 3' UTR and ==CPEBs== (CPE binding proteins). CPEBs bind to CPEs and recruit polyadenylation machinery (GLD-2, CPSF) to specific mRNAs when CPEB is **phosphorylated**
	- CPEs have the sequence U<sub>4-6</sub>A<sub>1-2</sub>U<sub>1-2</sub> e.g. UUUUAAU 
	- #experimental_evidence Hake & Richter (1994) first identified CPEs via RNA affinity chromatography
	- #experimental_evidence Depletion of CPEB from egg extract abolishes polyadenylation, as does injection of CPEB antibody in oocytes from *Xenopus*
	- **The number and location of CPE elements dictates the timing of polyadenylation, and thus translation, during meiotic maturation**. During *Xenopus* development, mRNAs that are activated early have 1 CPE (e.g. B4 histone or *c-mos*), while mRNAs that are activated late (i.e. at or after GVBD) have at least 2 CPEs, one of which overlaps with the hexanucleotide polyadenylation signal (AAUAAA) (e.g. cyclin B1). This is because the CPE-binding protein prevents CPSF from accessing mRNA early when `[`CPEB`]` is high, and only after GVBD is CPEB degraded after phosphorylation of its PEST box sequence, allowing access of mRNA to CPSF for polyadenylation. This allows for regulation of mRNA levels through time.  
	- #experimental_evidence [[B5 Translation and translation regulation in eukaryotes#^b4ef15|Barkoff et al (2000)]] – when CPE or hexanucleotide prevents was mutated, prevented polyadenylation and translation activation without decrease in mRNA levels. On the other hand, if progesterone was not injected (i.e. oocyte not matured), repression of translation is seen that is only lifted when the CPE adjacent to the hexanucleotide is mutated 
	  ![[Pasted image 20230127221900.png|425]]
- Polyadenylation signal  

### PABPs 
- **Structure** consists of 4 RNA recognition motifs (RRMs) and a variable C-terminal tail 
- Can interact with eIF4G N-terminus via RRM2 
![[Pasted image 20230122170915.png|650]]

## Closed loop model of translation 
- Simultaneous interaction of eIF4G with eIF4E and PABP physically links the ends of the mRNA 
- This results in synergistic increase in translational efficiency (may be related to promotion of [[B5 Translation and translation regulation in eukaryotes#How eIF4G/PABP interaction stimulates translation initiation|80S ribosome assembly or ribosome recycling]])
![[Pasted image 20230122171905.png|650]]
### Mechanism 
- eIF4G undergoes an allosteric change upon binding to eIF4E, resulting in a positive effect on interaction between 4E and the cap (i.e. 4E binds better to the cap)
- RRMs 1-2 of PABP bind to the N-terminus of eIF4G 

### How eIF4G/PABP interaction stimulates translation initiation 
- Promote 40S recruitment by increasing the affinity of eIF4F for the cap 
	- #experimental_evidence Kahvejian et al (2005) – Depletion of PABP impairs assembly of 80S ribosome initiation complex. Created ribosome initiation complex profiles (using sucrose gradients) of control extract, PABP-depleted extract, and depleted extract with PABP added back. PABP-depleted extracts exhibited reduced 80S ribosome complex formation and 40S recruitment, but this was rescued when PABP is added back. Rescue is not seen when PABP M161A mutant is added back. 
- Promote 60S subunit joining 
- May promote ribosome recycling 

### Evidence for closed loop model 
- #experimental_evidence Piron et al (1998) – Rotavirus mRNAs are capped and lack poly(A) sequences, but have a protein NSP3 bound to the 3' end. NSP3 was found to interact with eIF4GI by screening a Y2H library and confirmed by co-IP of eIF4GI with NSP3 from rotavirus-infected cells. Co-IP also showed that the amount of PAB pulled down with 4G decreases over time while that of NSP3 increased over time, suggesting that NSP3 outcompetes PAB for binding to 4G  over the course of infection. 
- #experimental_evidence Wells et al (1998) – Observed closed loop of mRNA using atomic force microscopy when incubated overexpressed eIF4E, eIF4G, and PABP together with mRNA. 
- #experimental_evidence Safaee et al (2012) – Found that there is strong positive cooperativity for the formation of the ternary complex of poly(A), eIF4G, and PABP. Using **EMSA**, found that there is a substantial increase in binding between PABP and poly(A) RNA when an N-terminal fragment of eIF4G was used, suggesting that eIF4G enhances binding between PABP and poly(A). The EMSA results were confirmed using **isothermal titration calorimetry**, which indicated that the affinity of PABP RRM for poly(A) increased when 4G fragment is present. **Small-angle X-ray scattering** was used to illustrate that the conformation of PABP RRM domains change upon interaction with poly(A), facilitating their interaction. 
- #experimental_evidence Karim et al (2006) – Constructed a luciferase mRNA that did not have a poly(A) tail but had MS2 binding sites in the 3' UTR. Also constructed MS2-PABP fusion proteins which could bind to the MS2 binding sites. This system was able to enhance translation. However, when PABP had M161A mutant that prevented interaction with eIF4G, RNA translation was not enhanced. 
- #experimental_evidence Kahvejian et al (2005) – Showed that the PABP-poly(A) interaction enhances interaction of eIF4E with the cap. Prepared mammalian cell-free extracts, either depleted of PABP or not, then added back WT or M161A PABP. Then, assayed each extract for eIF4E binding to mRNA by chemically crosslinking proteins to mRNA, treating with RNase A, then running on SDS-PAGE. Higher intensity band indicates greater eIF4E binding,. When cell-free extract depleted of PABP had wild type added back, there was more intense band. This suggests that the interaction between PABP and eIF4G is also critical for interaction of 4E with the cap. 

### Other proteins can interfere with closed loop interaction 
- In place of the PABP-eIF4G-eIF4E complex, other protein complexes can bridge the 5' cap and 3' UTR of mRNA to prevent closed loop formation and thus repressing translation 
- In the examples below, note that a weak cap-binding protein that does not bind eIF4G interacts with cap – this results in the cap-binding protein only inhibiting specific mRNAs, and allowing its cap binding to be regulated 
![[Pasted image 20230127232351.png]]

| Species         | Target mRNA | Protein X | Protein Y | Protein Z |
| --------------- | ----------- | --------- | --------- | --------- |
| Xenopus         | Cyclin B1   | CPEB      | 4E-T      | eIF4E-1b  |
| D. melanogaster | Nanos       | Smaug     | Cup       | eIF4E-1a  |
| D. melanogaster | Oskar       | Bruno     | Cup       | eIF4E-1a  |
| D. melanogaster | Caudal      | Bicoid    | (Bicoid)  | 4E-HP     |

#### CPEB
- Apart from its role in polyadenylation, CPEB also can repress translation by forming a "repressive closed loop" – CPEB can interact with 4E-T (and other components of a large mRNP complex) which in turn interacts with eIF4E1b bound to the 5' cap 
	- eIF4E1B is the important isoform for repressive closed loop
- Subsequently when CPEB is phosphorylated, it dissociates from 4E-T and recruits polyadenylases, resulting in polyadenylation and thus translational activation. The phosphorylated CPEB is subsequently degraded 
![[Pasted image 20230127225509.png|450]]
- #experimental_evidence Minshall et al – Used co-immunoprecipitation and gel filtration assays to show that in *Xenopus* oocytes, CPEB is in a very large mRNP complex with several RNA binding proteins, as well as eIF4E1b and 4E-T
	- eIF4E1b is structurally similar to the canonical eIF4E(1a) but with low affinity for eIF4G and 5' cap 
	- 4E-T (4E-transporter) promotes nuclear import of eIF4E

#### Bicoid protein can repress caudal mRNA by disrupting closed loop formation 
- Bicoid binds to the Bicoid-binding region (BBR) in the 3' UTR of *caudal* mRNA, as well as 4EHP (*Drosophila* eIF4E homologous protein), which binds to the 5' cap weakly but does not interact with eIF4G. As such, bicoid-4EHP can form a closed loop that prevents eIF4G-eIF4E forming the loop, preventing translation 
![[Pasted image 20230127231508.png|450]]

#### *Bruno* and *Smaug* proteins repress translation of *oskar* and *nanos* mRNA respectively by forming repressive closed loops with Cup 
- Cup contains a canonical eIF4E binding site, so it **competes with eIF4G** for eIF4E binding 
- Cup is a homolog of vertebrate 4E-T and interacts with the 5' cap via eIF4E 
- Bruno and Smaug interact with Cup and also with BRE and SRE elements respectively in the 3' UTR of the target mRNA 
![[Pasted image 20230127232141.png|425]]

## 3' UTR 
- Regulatory elements are mostly located in the 3' UTR 
	- Many involved in closed loop model (see [[B5 Translation and translation regulation in eukaryotes#Closed loop model of translation]])

### Advantages of regulating via 3' UTR
- No limit to the length of the 3' UTR – the 5' UTR is constrained as the ribosome has to scan from the cap to find AUG. Thus, 3' UTR can have several motifs that each bind to a different regulatory protein/microRNA 
- As there is no limit, all regulatory sequences could be localised to the 3' UTR, facilitating coordination of regulation 
- Regulation in 3' UTR more easily allows regulation of poly(A) tail length 
- Even if there were binding sites for several different proteins in the 5' UTR, in practice the most 5' proximal protein/RNA interaction would be dominant as it will affect ribosome scanning 

### CPEB 
Paradigm 3' UTR-binding protein 

## Codon usage
- Ribosome profiling suggests that ribosome density along mRNA can vary 

### Codon optimality 
- Optimal codons are translated more rapidly than less optimal ones 
- Depends on 
	- Codon rarity 
	- tRNA availability 
		- #experimental_evidence "In E. coli, codons corresponding to highly abundant tRNAs are translated as much as sixfold faster than their synonymous tRNA counterparts that occur at lower concentrations"
		- However, the availability of tRNAs may be different for different positions along the same mRNA 
			- #experimental_evidence Cannarozzi et al (2010) observed that rapidly induced genes tend have clusters of codons translated by the same cognate tRNA. It was hypothesised that codons at the A site can use recycled tRNAs from codons that were just translated, increasing the efficiency of translation 
				- This hypothesis requires that diffusion of recycled tRNA is slow enough compared to rate of translation elongation, perhaps necessitating coupling of recycling machinery to the ribosome. 
		- tRNA pool has also been observed to be different in different tissues, so genes may be translated at different efficiencies 
- Important to take both demand and supply into account – even if a given tRNA is highly expressed, if codons for that tRNA are also highly represented in transcriptome under the particular cellular conditions, then translation efficiency would not be as high as it otherwise would be
- There should be evolutionary pressure on highly expressed genes to have more optimal codons to reduce the time ribosomes spend on them
- ==However, rare codons may also have less secondary structure formation which increases translation efficiency. So there is a tradeoff between codon optimality and secondary structure formation== 

### Charge 
- Positively-charged residues (Arg, Lys) interact with negatively charged exit tunnel walls; electrostatic interactions reduce translation rate 
	- #experimental_evidence Ribosome profiling suggests that regions with highest ribosomal occupancy on mRNA due to positive charges in nascent peptide 

### Frameshift 
- Stretches of consecutive AAA (coding for Lys) codons can cause frameshift
- When ribosome stalls on AAA (due to positive charges), it triggers ribosome sliding, and the A site tRNA cannot differentiate between the correct frame and the incorrect frames since they are all AAA 
- When translation is resumed, ribosome is out of frame, and usually it will quickly encounter an out-of-frame stop codon, resulting in nonsense-mediated decay of the mRNA 

### Effects of decoding on post-translational processes
- Speed of codon decoding may affect folding – faster translation, less time for folding, more misfolding errors? 
	- #experimental_evidence Komar et al (1999) – 16 consecutive rare codons were replaced by synonymous optimal ones in an *E. coli* gene. This increased translation speed but ay have reduced folding, deduced by 20% decrease in enzyme specific activity 
		- Need a direct measure of folding to definitively prove this 
	- Another hypothesis is that rare codons are used to temporally separate protein domains so each can fold independently of each other 
		- #experimental_evidence Boundaries between domains are enriched with rare codons (Thanaraj and Argos, 1996)
- Speed of codon decoding may also affect recognition by SRP – slower decoding, enhanced recognition by SRP 
	- Clusters of rare codons 35-40 codons downstream of SRP binding site, which is the length of nascent peptide that can span ribosome exit tunnel, would slow down translation for SRP recognition 

## Secondary structure can affect elongation 
- #experimental_evidence Kudla et al (2009) synthesised a library of 154 GFP genes that vary randomly at synonymous sites without changing the amino acid sequence. When GFP genes were expressed in ***E. coli***, there was 250-fold variation in expression level. GFP mRNA with tighter structure at the 5' end 
- #experimental_evidence Pseudoknot in infectious bronchitis virus 1a/1b mRNA slows down ribosome dynamics by slowing down swivelling of 30S head in direction of 3' end of mRNA, a movement essential for translocation 

## Efficiency of peptidyl transfer 
- Proline is a poor A-site acceptor of the peptidyl group during peptidyl transfer, and Pro-rich sequences on the mRNA can stall translation 
- This requires specialised translation factors, EF-P and eIF5A in bacteria and eukaryotes respectively to alleviate stalling 
- Unclear why Pro reactivity is low, but could be steric properties of proline 

## Programmed regulatory stalling 
- Some mRNAs contain peptide sequences that induce stalling 
- E.g. human cytomegalovirus uORF2 of gp24, bacterial SecM 
- Stalling sequences cause a misalignment of reactive groups at the peptidyl transferase center of the ribosome 
	- Caused by interaction of nascent peptide with ribosomal exit tunnel walls, particularly at constriction formed by ribosomal proteins uL22/uL24 
	- This interaction is relayed to peptidyl transferase center by a relay system 

# Sequence-independent translation regulation 
## Modification of initiation factors 
### eIF2α
- eIF2α kinases are activated in the Integrated Stress Response (ISR), which is a response to diverse stresses, e.g. viral infection (dsRNA), ER stress, amino acid starvation (uncharged tRNA), low heme 
- eIF2α kinases are activated commonly by autophosphorylation and oligomerisation 
  ![[Pasted image 20221227165900.png|500]]
- Kinases phosphorylate eIF2α on Ser51, which blocks recycling of eIF2-GDP by eIF2B as it converts eIF2 from a substrate to an inhibitor of its GEF, eIF2B 
  ![[Pasted image 20221227170802.png|500]]
- Blocking of recycling decreases the availability of eIF2-TC, which attenuates initiation globally 
- However, translation of certain mRNAs is stimulated by low levels of eIF2-TC due to uORFs in special contexts; these mRNAs have two uORFs of appropriate type and position 
	- E.g. The 5' UTR of Activating Transcription Factor (ATF) 4 and 5 mRNAs have 2 uORFs that are translated more during ISR and eIF2α phosphorylation. This is because when there are low eIF2-TC levels, after translation of uORF1, ribosomes are more likely to bypass uORF2 initiation codon and instead initiate at the mORF start codon. uORF2 in ATF4 and 5 are relatively long uORFs that also overlap with the mORF, allowing for this type of genetic control. 
		- #experimental_evidence Vattem & Wek (2004) mutated the initiation codon of each uORF in ATF4 to AGG so that they are nonfunctional for translation initiation. AT4-Luc reporter plasmids containing uORF1 and/or uORF2 mutants were introduced into mouse embryo fibroblast (MEF) cells. When uORF1 initiation codon was mutated, there was a fall in ATF4-Luc expression. But when uORF2 initiation codon was mutated, there was an increase in ATF4-Luc. 
	  ![[Drawing 2022-12-27 17.16.52.excalidraw.png|475]]
	- E.g GCN4 is a TF for amino acid biosynthetic enzymes, and its translation is upregulated under starvation conditions. It has 4 uORFs and reinitiation is sensitive to eIF2-TC levels in cells, with sequences flanking uORFs influencing reinitiation efficiency. 
	  ![[Pasted image 20221227173645.png|500]]
		- uORF1 and uORF2 are permissive for downstream reinitiation. AU-rich sequences 3' to the stop codon of uORF1 favour resumption of scanning, as interaction of eIF3 with the nucleotides at the 5' side of uORF1 stabilises association of the post-termination 40S with the mRNA 
		- On the other hand, uORF4 inhibits reinitiation as the GC-rich sequence around uORF4 triggers ribosome release 
			- In non-stressed cells, TC is abundant, so rescanning PIC can rebind TC rapidly to reinitiate at this inhibitory uORF, preventing translation of the mORF 
			- Optimum context around start codon in uORF4 minimises leaky scanning in non-stressed cells 
		- In stressed cells, reduced levels of eIF2-TC allows 40S ribosomes to bypass the inhibitory uORFs and reinitiate at the mORF instead. 
		- #experimental_evidence Ingolia et al (2009) used ribosome profiling to show that there was a decrease in ribosome occupancy of repressive uORFs as well as increased translation of the mORF under starvation conditions. 

### eIF4F 
- 4E binding proteins (4E-BPs) are phosphorylatable regulators of eIF4E/eIF4F function. 
- 4E-BP binding to eIF4E competes with eIF4G binding to eIF4E, since 4E-BP and eIF4G share similar binding sites for eIF4E, YXXXXLφ) 
- Phosphorylation of 4E-BPs in the PI3K/AkT/mTOR signaling pathway affects whether it can bind to eIF4E; binding only occurs in the dephosphorylated state. 
- 4E-BP undergoes a conformational change upon phosphorylation which occludes the 4E-binding site by sequestering it into a partly buried β-strand, blocking accessibility to eIF4E  ^4857a5
	- #structural_evidence Bah et al (2014) used NMR NOE data to construct a model  

## Ribosome turnover 
- Ribosome turnover is limited by availability of free ribosomes 
- Ribosome stalling can result in ribosome queueing and even falling off, which inhibits translation initiation 

## Phase separation 
*How do phase separation and biomolecular condensates contribute to translational regulation?*
- P bodies and stress granules may form under stress due to accumulation of unfolded proteins. Heat shock proteins bind to unfolded proteins. Since heat shock proteins have been shown to interfere with aggregation of QN-rich domains, stress thus promotes aggregation and LLPS 
- Assembly factors required under one stress condition may not be needed in another
	- E.g. TIA-1 is involved when cell is exposed to arsenite but not other stresses like heat shock 

### Function of phase separation 
- It is unclear why condensates are needed when the activities in the condensates can be performed outside a condensate structure, e.g. deletion of P bodies in metazoans does not affect miRNA-mediated repression, targeted decay, NMD, or translational repression during stress 
	- mRNP granules could have other [[Phase separation#Functions of phase condensates|functions]] too 
- Granule formation could increase local concentration of factors
	- e.g. if Dcp2 concentration is limiting, concentrating Dcp2 in P bodies could facilitate interaction with mRNA
	- e.g. concentration of translation initiation factors in stress granules could facilitate initiation 
- Granule formation could also sequester excess mRNAs in the cytosol, maintaining a proper stoichiometry between mRNAs and translation machinery. Excessive mRNAs could lead to competition for translation factors, reducing translation efficiency 
	- Allow for rapid detection and response to stress 
- Control timing of translation 
	- E.g. Aggregation of RBP Rim4 in yeast may be involved in translational repression of B-type cyclin, Clb3, thus controlling timing of cell cycle 

### P-bodies
#### Translational repression 
- P bodies are kept separate from other RNPs by specific and multivalent protein-protein and protein-RNA interactions. P body proteins bind multiple partners, forming a proteome network. Additionally, most P body proteins bind RNA, and each RNA in turn bridges numerous proteins. These dense and specific interactions promote P body condensation. 
- #experimental_evidence [[HubstenbergerEtAl_2017]] proposed a model where proteins bind specific ZIP code elements in mRNAs to target them to P bodies, where they are translationally repressed due to the presence of mRNA regulatory proteins and an absence of translation machinery. **mRNAs that encode proteins with regulatory functions are stored in P bodies**, from which they can be rapidly mobilised for translation, while constitutively translated mRNAs that are excluded from P bodies encode housekeeping functions 
  ![[Pasted image 20221220201949.png|575]]
  - P body condensation may also be regulated in conjunction with developmental stages, where mRNA is released from P bodies at particular timepoints in development to allow for their translation and hence progression through development. 
	  - E.g. #experimental_evidence Sankaranarayanan et al (2021) found that disrupting P bodies in mature *Drosophila* oocytes with 1,6-hexanediol resulted in reduced association of MS2-labeled *bcd* mRNA with the P bodies, suggestsing release of *bcd* mRNA. Moreover, upon treatment of mature oocytes with activation buffer, which activates mature oocytes, the P bodies and *bcd* mRNAs dispersed, and there was a loss of association between P bodies and *bcd* using smFISH analysis 
  - P body condensation may also stabilise low affinity interactions or increase enzyme activity (e.g. DDX6 helicase) by locally concentrating RNA binding proteins and their mRNA targets 
  - P bodies contain proteins that repress translation, e.g. DDX6, eIF4E-T, LSM14A. These three assembly factors bind to each other. Also contains PUM2, FMR1, AGO1-3, etc. 
  - P bodies can also contain miRNAs that repress mRNA translation 
  - Translation initiation factors and ribosomal proteins are excluded, except eIF4E in mammalian P bodies, as it can associate with eIF4E-T in P bodies that inhibit eIF4E function 

#### RNA turnover 
- E.g. Decapping complex Dcp1/Dcp2, 5' to 3' exonuclease Xrn1, CCR4/NOT deadenylase
- E.g. proteins involved in NMD 
- E.g. miRNA, siRNA 
- #experimental_evidence Blocking 5' deccay pathway by mutating/silencing XRN1 enlarges PBs
- #experimental_evidence Reporter RNAs with poly(G) tract that blocks decay accumulate in PBs

#### Determination of mRNA fate in P bodies 
- RNA decay may not be the major function of P-bodies 
	- #experimental_evidence XRN1-mediated decay of mRNA was monitored in live cells using an mRNA sensor called 3' RNA end accumulation during turnover (TREAT). RNA decay intermediates were not observed in PBs, even when decay motif ARE was added to 3' UTR
- Instead, P-bodies more likely to act as storage for mRNAs (i.e. sequestration) where they are translationally repressed
	- #experimental_evidence Translation of PB-localised mRNAs increase when PBs disrupted 
	- Accumulation of mRNA in PBs when decay was blocked may be due to accumulation of RNAs that condensed with the untranslated RNAs in PBs 
- Function of P-bodies could be different between different cell types or under different conditions or in different organisms 
	- Many experiments used HEK293 cell line or yeast only 
	- Yeast PBs only form under stress conditions e.g. osmotic stress 

#### mRNA found in P-bodies 
- P-bodies contain diverse mRNAs; 1/3 of of coding transcriptome can be found in P-bodies
- These mRNAs tend to encoded regulators, while PB-excluded mRNAs encode housekeeping proteins 
	- E.g. Histone mRNAs are excluded from PBs, while histone methyltransferase mRNAs tend to be included in PBs 
	- Separation of regulators and housekeeping proteins that may otherwise be involved in the same process or even same complex 
	- #experimental_evidence See [[HubstenbergerEtAl_2017]]
- Features of P-body mRNAs
	- mRNA with specific 3' UTRs, e.g. apoB, actin, let-7 miRNA binding motif 
	- mRNA with particular motifs e.g. AU-rich element
	- Abundant but poorly translated, with low translation yield 
	- Short poly(A) tails – no direct evidence yet, but DDX6 prefers short poly(A) tails, and DDX6 is often found in P bodies 

### Stress granules 
#### Translation initiation components 
- Stress granules form when translation initiation is blocked, e.g. under stress conditions, drug inhibition of translation, initiation factor knockdown, etc. But not all blocks cause stress granule formation 
- Contain translation initiation factors eIF4E, eIF4G, eIF4A, eIF4B, PABP, eIF3, eIF2, 40S subunit 
- Contains mRNPs stalled during translation 
- SGs can also contain other proteins e.g. RNA helicases, regulators of mRNA stability, etc. depending on condition 

#### mRNAs in stress granules 
- Short, and efficiently translated mRNA (associated with ribosomes) tend to be excluded
- While long and poorly translated mRNA (low association with ribosomes) tend to be included 
- #experimental_evidence [[KhongEtAl_2017]] purified stress granules from yeast and mammalian cells, then did RNA-seq to determine the transcriptome of stress granules. smFISH was used to validate identified mRNAs to SGs. They found that essentially every mRNA can be targeted to SGs, but the proportion of each transcript species targeted varies from <1% to >95% upon SG formation. 
- Since SGs can contain a diverse but overall small amount of mRNA, formation of SGs should not affect bulk mRNA 
	- SGs probably will only affect function of mRNAs that are efficiently sequestered 

### Formation of mRNP condensates
#### P bodies 
- For yeast P bodies, pre-existing protein complexes may be recruited to mRNA to nucleate P-body formation 
	- E.g. Dcp1/Dpc2/Dhh1/Edc3 or Dcp1/Dpc2/Dhh1/Scd6 may be recruited as a complex, along with a complex of Pat1/Xrn1/Lsm1-7p 
		- Edc3, Dcp2, Scd6 and Dhh1 can interact with Pat1 to form a larger complex
		- Since Pat1-Lsm1-7p complex can bind 3' end and decapping enzymes bind 5' end, mRNPs may form a [[B5 Translation and translation regulation in eukaryotes#Closed loop model of translation|closed loop]] that then assemble to form P bodies
- P bodies then form from the aggregation of mRNP complexes 
	- In yeast, aggregation depends on self-interaction domain in Edc3 and glutamine/asparagine-rich domain in Lsm4 
	- Edc3 self-interaction domain is conserved in animals as well 
	- In animals, multiple proteins contain Q/N-rich domain e.g. GW182 and Ge-1/Hedls (part of decapping complex in animals), and depletion of either protein decreases P body formation in human and *Drosophila* cells 
	- Pat1 contributes to aggregation as it is a scaffold that interacts with multiple proteins in the P body 
	- Interaction with mRNA may promote P body formation (otherwise, complexes can interact and P bodies can form all the time?)

> [!image] Model for P body assembly in yeast (Decker & Parker 2012)
> ![[Pasted image 20230518210023.png]]

#### Stress granules 
- Self-aggregation of QN-rich domains in RNA binding proteins TIA-1 and TIA-R 
- G3BP dimerisation 

#### Regulation of formation 
- By specific conditions in the cell 
	- E.g. mRNA with fused ApoB 3'UTR move to PBs after insulin treatment 
	- E.g. TOP sequence-containing mRNAs move to PBs after arsenite treatment 
- By post translational modification of mRNP proteins 
	- PTMs are more rapid to add and remove than new protein synthesis. This allows for rapid response to stress, since disassembly of condensates upon PTM of mRNP component would lead to translation activation of the stalled ribosomes. In other words, condensates may sequester mRNA poised for translation for rapid response.

#### Interactions between P bodies and stress granules 
- When yeast are deprived of glucose, stress granules assemble on pre-existing P bodies. 
	- Possibly, when mRNA in yeast exits translation, they first form a P body, then mRNA targeted for re-entry into translation load translation initiation factors to form stress granules. 
- Stress granules can also form independently of P bodies 
	- E.g. in mammalian cells and sodium azide stress in yeast, stress granules form while P bodies do not 
	- Depleting some factors in mammalian cells blocks P body formation but not stress granules 

#### mRNA cycle hypothesis 
- mRNA in polysomes undergoes rounds of initiation, elongation, termination to produce protein 
- If defects in translation initiation and/or termination occur, mRNAs in polysomes recruit proteins that repress initiation, leading to mRNP assembly and P body formation 
- Those mRNAs that stall at initiation but fail to recruit P body factors may accumulate in stress granules
- mRNAs may prefer to accumulate in stress granules, P bodies or polysomes 

> [!image] Proposed model of mRNA cycle by Decker & Parker (2012) 
> ![[Pasted image 20230518215802.png]]

### Post-translational modifications may tune translation regulation, deadenylation
- #experimental_evidence [[KimEtAl_2019]] found that in minimal condensates of FMRP and CAPRIN1, phosphorylation of FMRP results in higher *in vitro* deadenylation rate by CNOT7 than CNOT7 in buffer. CNOT7 rate in FMRP-phosphorylated CAPRIN1 was comparable to in buffer 

### Remaining questions 
- What is the function of decapping activators and how do they recruit decapping enzyme? 
- What is the function of P bodies and stress granules? Why do they form? 
- How do mRNPs transition between polysomes, P bodies, and stress granules? 

## Small RNA silencing of translation 
See [[B7 Small RNAs]]


