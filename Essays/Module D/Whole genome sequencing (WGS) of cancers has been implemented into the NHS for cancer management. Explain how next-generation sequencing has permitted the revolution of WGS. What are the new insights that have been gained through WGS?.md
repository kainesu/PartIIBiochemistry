**Whole genome sequencing (WGS) of cancers has been implemented into the NHS for cancer management. Explain how next-generation sequencing has permitted the revolution of WGS. What are the new insights that have been gained through WGS?**

# **Introduction**

Cancer is commonly considered to be a genetic disease. Mutations can lead to aberrant signalling and developmental programmes, which ultimately result in uncontrolled proliferation and modification of the tumour microenvironment. To fully understand the impact of these mutations on cancer progression, whole genome sequencing (WGS) has been increasingly employed to catalogue cancer mutations. This revolution in cancer genomics has primarily been driven by the development of next-generation sequencing (NGS) methods that have made it cheaper and faster to sequence whole genomes. The data obtained from WGS has shown that relatively neglected mutations, including structural variations, mutations in noncoding regions, and passenger mutations are also important to understanding cancer development. This information can be used to improve cancer diagnosis and treatment, thus improving patient outcomes. 

# **1. Next generation sequencing (NGS) has made it cheaper and faster to sequence whole genomes**

Next-generation sequencing (NGS) refers to a type of sequencing technique that allows for high throughput sequencing of nucleotides by sequencing many DNA fragments in parallel. The general principle behind these technologies is that the DNA is first fragmented by physical shearing (e.g. sonication). Then each fragment is ligated to adaptor sequences, and immobilised onto a chip. Each fragment can then be sequenced in parallel via different methods (e.g. Illumina sequencing, 454 sequencing, ion torrent sequencing) (Figure 1). Finally, sequence reads are aligned to a reference genome _in silico_ to obtain the entire genome sequence. 

![[Pasted image 20230527155803.png]]
Figure 1: Overview of next-generation sequencing (steps 1-5) followed by variant calling (steps 6-7)

With continuing advancements in NGS, it has never been cheaper or faster to sequence whole human genomes. In 2021, it costs less than 1000 USD to sequence a whole human genome, when in comparison the first human genome to be sequenced cost millions of dollars to obtain. This dramatic fall in the cost of sequencing has made it possible for whole genome sequencing (WGS) to be done at a large scale, and fast enough for the sequencing information to be clinically relevant. The amount of data that can now be acquired from genomes is massive compared to the limited amount available from more targeted microarray analysis or exome sequencing. This explosion of data has also been supported by improved computational pipelines and infrastructure. 

In cancer genomics, the main use of WGS is to detect variants, i.e. changes in the sequence of cancer DNA that is different from the germline (“original”) DNA. WGS methods are versatile in being able to detect a variety of mutations, including single nucleotide variants (SNVs), structural variants (e.g. translocations, deletions), and copy number variation (CNVs). Subsequent analysis of WGS data has provided numerous insights into the development of cancer, as discussed below. 

# **2. WGS can be used to identify novel structural variants and mutations in non-coding regions in cancer genomes **

WGS can be used to study structural variants and how they are implicated in cancer development. Previously many studies of cancer genomics have used microarrays that target specific regions of the genome. However, this method does not allow for discovery of novel mutations, and microarrays cannot detect copy-neutral structural variations. In contrast, since WGS data covers the whole genome, undiscovered mutations and diverse rearrangements can be detected.

WGS data has shown that chromosomes are often rearranged in cancer cells due to genomic instability. Paired end NGS is the standard technique used for characterising structural variants, generating short reads starting from both ends of DNA fragments. In one study, Yang et al (2013) developed the Meerkat algorithm to analyse WGS data from 140 patients across 10 tumour types, and detected numerous somatic structural variation events in each tumour. More dramatic is the phenomenon of chromothripsis, which has been observed in 2-3% of cancers and was first observed in WGS data from chronic lymphocytic leukaemia patients. In this phenomenon, hundreds of genomic rearrangements can occur in 1 or more chromosomes, leading to multiple cancer-causing amplifications, deletions, and changes in gene regulation. Such structural variations are caused by a number of different mechanisms, which can be predicted from WGS data. For example, in the Yang et al (2013) study, deletion breakpoints containing regions of microhomology were inferred to have resulted from alternative end-joining repair. By cataloguing these rearrangements and their mechanisms, the knowledge gained from WGS may be able to identify new targets for therapeutic discovery. Several previously reported chromosomal rearrangements in tyrosine kinases like BCR-ABL or transcription factors like the ETS family have been implicated in cancer cell fitness. Targeting fusion products like BCR-ABL may be a particularly effective treatment strategy as demonstrated by the efficacy of imatinib. 

WGS data has also revealed the importance of driver mutations within non-coding regions of the genome. These regions have been ignored in many previous studies of cancer genomics, which only analyse exome sequences. For example, WGS analysis by Huang et al (2013) has shown that mutations in the promoter region of telomerase reverse transcriptase (TERT) gene are frequent in melanoma. The mutations generated new binding sites for ETS transcription factors, leading to overexpression of TERT. This upregulates telomerase activity and promotes tumorigenesis by increasing telomere length, which staves off senescence in cancer cells. Other gene regulatory regions, such as super enhancers, have also been observed to undergo gene amplification, which leads to overexpression of nearby proto-oncogenes. In another analysis of WGS data from the Cancer Genome Atlas, Zhang et al (2016) reported focal amplifications of super-enhancers 3′ to Myc, and CRISPR-Cas9 mediated deletion of the super-enhancer decreased Myc expression. Hence, WGS has been crucial to identifying these additional cancer drivers, which may also be potential targets for cancer therapeutics. 

# **3. Extraction of mutational signatures from WGS data can be used to determine cancer aetiologies **

Apart from identifying new structural variants and mutations in non-coding regions, WGS data can also be used to acquire the entire catalogue of driver and passenger mutations in a tumour. From this catalogue, the aetiology of a cancer can be determined by extracting mutational signatures. A mutational signature refers to the pattern of mutations generated by a particular mutational process. The catalogue of mutations in a cancer cell are often the result of multiple mutational processes, such as DNA replication errors, mutagens, or defective DNA repair. WGS can be used to acquire this entire catalogue of mutations in a tumour, then the mutational signatures can be extracted via a non-negative matrix factorisation method (Figure 2). These mutational signatures reflect the aetiology of the cancer. WGS is uniquely suited for determining mutational signatures as it can capture more base substitutions and structural variations, increasing the statistical power of signature extraction. Many of these variants result from passenger events, which were once considered just “noise” but are now useful as imprints of mutational processes in cancer. 

![[Pasted image 20230527155821.png]]
Figure 2: Process of extracting mutational signatures from a catalogue of mutations in a tumour sample. 

Each mutational signature can then be connected to a particular aetiology, either because the mechanism of the mutational process is known (e.g. APOBEC deamination), or via validation in tumour samples with known aetiologies. For example, defective POLD1 proofreading activity results in a signature with an enrichment of C-to-A mutations with low levels of other transitions and transversions. WGS of tumours from patients with germline POLD1 mutation recovered this signature, allowing it to be identified in other cancers. 

The aetiology of the cancer can even be determined if the original driver mutation cannot be identified. In an analysis by Nik-Zainal et al (2016), some breast cancers were found to exhibit mutational signatures associated with defective double strand break repair. However, they did not appear to exhibit inactivating mutations in BRCA1/2, which usually cause these signatures. There also did not appear to be a clear relationship between mutations in other genes involved in double strand break repair and these mutational signatures. This may suggest that, rather than looking for driver mutations as signs of defective double strand break repair, mutational signatures could serve as more consistent and accurate biomarkers. Such use of mutational signatures highlights the importance of WGS in cancer diagnostics over more targeted sequencing. 

Determining the aetiologies of cancers from their mutational signatures can be useful for a number of clinical applications, especially in combination with machine learning algorithms. For example, the HRDetect algorithm was trained on breast cancer genomes to detect samples with BRCA1/2 deficiencies based on their mutational signatures. HRDetect scores were found to be predictive of patient survival and their sensitivity to a PARP inhibitor. In addition, mutational signatures can also be extracted from cell-free DNA released by tumour cells into the circulation. Despite the low coverage of the WGS data, Wan et al (2022) was able to extract the signatures via a machine learning method with limited sensitivity. These examples thus demonstrate how the information obtained from WGS data can be translated into real clinical insights. 

# **4. WGS data can be used to reconstruct the evolutionary history of a cancer **

Tumours are highly heterogeneous, with different subclonal populations. Processes of clonal expansion, mutation, and subsequent selection influence population structure. WGS data can be used to reconstruct the phylogenetic histories of tumours, thus providing insight into the dynamics of tumour evolution. The number and genomic makeup of the subclonal population can be determined by clustering somatic variants according to the number of reads across that base, and the fraction of reads that report the variant. One cluster should correspond to the set of mutations found in all tumour cells, while others would each correspond to a different subclonal population. The use of WGS is thus important by capturing a higher number of somatic variations in the cancer, which allows for more accurate clustering and thus identification of different subclonal populations. Subsequently, the evolutionary relationships between subclonal populations can be determined by comparing the variant allele fractions in each population (Figure 3). In addition, the order in which the mutations are acquired can be inferred from their relative frequencies – mutations that are more frequent are likely to have been acquired earlier. The sequencing of passenger mutations by WGS is thus important in this case as they do not affect the fitness of the subclone. As such, they are not under selection, so their frequency should only be affected by how early they appear in the evolutionary timeline. 

Such phylogenetic reconstruction from WGS data has been used to infer key principles of cancer evolution. For example, Gundem et al (2015) analysed WGS data of metastases from 10 prostate cancer patients and reconstructed their phylogeny. They found that the evolutionary relationships between the primary tumour and secondary tumour, and between secondary tumours are complex. One or multiple rare subclones in the primary tumour were found to seed secondary sites, which repudiates the idea that the primary tumour as a whole is metastatic. Metastases were also found to seed each other, either in a linear way where a metastasis seeds one site before the next, or in a branched way where the metastasis seeds multiple other secondary tumours at the same time. Hence, WGS data can be used to provide important insights into how cancer evolves without having to actually monitor the development of the tumour over time. 

![[Pasted image 20230527155833.png]]
Figure 3: Simplified schematic of phylogeny reconstruction from WGS data. 

# **Conclusion** 

Sydney Brenner once said, “Progress in science depends on new techniques, new discoveries and new ideas, probably in that order”. Indeed, the development of NGS technologies has revolutionised the amount of data that can be mined from cancer genomes, with whole genomes being sequenced at a large scale. However, equally important are the computational pipelines that are used to analyse these genomes – many cancer genomes are available publically, so it is not the data itself that is remarkable but rather the answers we can get from them. These include discovering the importance of structural variation and non-coding regions, the surprising usefulness of passenger mutations, and the ways in which cancers evolve. From these discoveries, new ideas for cancer diagnosis and treatment have emerged that are likely to improve patient survival. In the future, the information gained from these WGS studies may be further augmented by studies on the epigenome and chromatin packaging, which cannot be identified by WGS alone. The development of long-read sequencing methods (e.g. PacBio, Oxford Nanopore) could also help to improve the accuracy of sequencing in repetitive regions, which would in turn improve the accuracy of variant calling algorithms. Indeed, WGS will likely be a mainstay in modern cancer research. 

# Discarded 

WGS is a wholesale / one-stop solution – don’t need multiple assays to test for MMR deficiency, HR deficiency, etc. which in the past may have required multiple tests (e.g. using PCR to map microsatellites in MMRD)

Limitations 



* Changes to epigenome, chromatin packaging cannot be identified by WGS alone; DNA needs to be prepared in a specific way e.g. ChIA-PET 
    * Some paediatric cancer patient lack any genetic alterations in their genomes, and it is suspected that the cancer is driven by epigenetic alterations that affect developmental programmes 
* Short reading sequencing (E.g. Illumina) can make repetitive regions difficult to sequence as they cannot be aligned to the reference genome easily → mutation calling errors 
* Long read sequencing (e.g. PacBio, nanopore) can improve accuracy in these areas but they are more expensive 
* Accuracy depends on sequence depth in each genomic region, alignment to reference genome, and algorithm used to call variants (indel has high level of inconsistency while SNV and SVS are more consistent between different variant calling pipelines) 
* Differentiating driver and passenger mutations? 

Large scale cancer discovery 

WGS data → bioinformatics → can understand cancer without having to sample it yourself / observe it directly → accessibility 

Future 



* Need correlation of WGS with proteome so that protein abundance information might be obtained from WGS as well 
* Long read sequencing – more reliable SV detection and resolution of repeats 
* Quantification of inter- and intra-tumour heterogeneity – tumours consist of subclones with different driver mutations, so clonality also has to be taken into account. Maybe target more common driver mutations first since they are likely to be most fit? 
* Continue compiling databases, computational approaches – combine information from WGS and clinical outcomes 
* Supports elucidation of mechanisms behind cancer progression 

**Deleted **



        * Profiling neoantigens for immunotherapy
        * Predict response to immune therapy. 
            * Mutation in PD-L1 cancers will respond to anti-PDL1 agents e.g. in lymphomas 
    * Large scale whole genome sequencing – sequencing thousands of cancer samples (* not necessarily WGS) 
        * E.g. 100k genome project in UK 
        * Identify genes, non-coding regions that are mutated across different cancers across tissues 
            * E.g. p53 is highly prevalent across human cancer tissue → can treat for p53 generally, don’t need to use tissue-specific treatment? 
            * Unexpected driver mutations e.g. mutations in components of spliceosome found in myelodysplasia, chronic lymphocytic leukaemia, AML, and uveal melanoma

Arguably the most notable chromosomal rearrangement implicated in cancer is the BCR-ABL fusion in chronic myelogenous leukaemia. Here, the tyrosine-protein kinase _ABL1_ was fused downstream to the _BCR _gene due to reciprocal translocation between chromosomes 9 and 22. The hybrid kinase that results from this fusion is constitutively active. The increase in signalling to cell cycle regulators thus leads to excessive proliferation. Rearrangements in other genes, such as RET kinase in non-small cell lung cancer or in ETS transcription factors in prostate cancer, can also lead to similar constitutive activation. Targeting these fusion products may be an effective treatment strategy, as demonstrated by the efficacy of imatinib, a competitive inhibitor of the BCR-ABL kinase. Hence, WGS analysis has identified driver chromosomal rearrangement events in tumours that could serve as new targets during therapeutic discovery. 



* These rearrangements can have implications for proliferation 
    * E.g. kinase rearrangements – chromosome fusions have resulted in constitutive activation of kinase signalling, e.g. RET in NSCLC 
    * E.g. transcription factor fusions – duplication of MYBL1 gene discovered from WGS. reported in ~30% of paediatric low-grade gliomas 
    * E.g. retrotransposon insertions in cancer – Retrotransposons are widespread, possibly mobile elements in human germline. They are usually suppressed by epigenetic mechanisms, but their activation could lead to tumorigenesis 
        * E.g. Lee et al (112) analysed WGS data and found an average of 28 insertions in colorectal genomes; the genes affected by insertion tend to contain point mutations and had downregulated mRNA levels.
* Fusion products may be good therapeutic targets e.g. imatinib and BCR-ABL fusion in chronic myelogenous leukemia 
* WGS can also uncover the mechanisms (Lee 25) and temporal dynamics (Lee 26) of SVs
* Chromothripsis is one mechanism for structural variants 
    * Massive, localised genomic rearrangement 
    * Chromothripsis  = 1 or a few chromosomes in 1 cell produce many clustered structural variants; form due to fragmentation of DNA that is then rejoined inaccurately by DNA repair pathways 
    * E.g. chromothripsis signatures found in cancers in patients with inherited p53 mutations 
* However detection sensitivity of SVs from WGS data is still not 100% accurate as many SV events are complex (example?); this can be especially difficult if the SV event is rare 
* WGS can also be used to uncover mutations in non-coding regions in cancer 
    * As opposed to whole exome sequencing or targeted microarrays
* WGS data has suggested that mutations in non-coding regions can also contribute to tumorigenesis 
    * E.g. mutations in promoter regions of telomerase reverse transcriptase gene (TERT) 
    * E.g. Brd4 – super enhancer associated with cancer 
        * Copy number gains of noncoding regions containing super-enhancers near oncogenes e.g. Myc associated with overexpression of these genes (46) 
    * E.g. Mutations in 3’ UTR tend to occur in cancer driver genes – affect miRNA binding, increases RNA stability and thus protein expression 
    * E.g. oncogenic, tumour suppressor miRNAs
    * siRNAs 
* Complemented by transcriptome analysis (RNA-seq) 
    * Determine effect of intronic mutations on transcript abundance 
        * E.g. changes to alternative splicing 
    * Assumes that transcriptome is proportional to proteome 
* E.g. WGS of liver cancers detected integration of HBV DNA genome 
* Using WGS important for inferring mutational signatures as it captures more base substitutions → more statistical power 
* Understand genomic instability processes
    * E.g. POLE or POLD1 exonuclease domain mutations. (Lee 142, 169) 
    * E.g. Nucleotide excision repair defect – WGS data suggest that somatic mutation frequency is lower in highly expressed genes  
* Infer cancer aetiology using mutational signatures  – Multiple mutational processes are at work in cancers, e.g. DNA replication errors, mutagens, defective DNA repair. Each mutational process generates a particular pattern of mutations called “mutational signatures”. WGS allows for acquisition of all mutations, both driver and passenger, and the pattern is analysed via non-negative matrix factorisation to identify mutational signatures
    * Each mutational signature can then be connected to a particular aetiology because of the mechanism by which each mutational process causes mutation 
        * E.g. Signature 6 arises from mismatch repair deficiency 
        * E.g. Signature 22 = aristolochic acid 
        * E.g. Kataegis – localised cluster of patterned mutations. Can be caused by APOBEC mutations, TLS DNA polymerase, etc. 
        * Aetiology can be identified even if the causative agent or driver mutation cannot be found. 
            * E.g. Nik-Zainal et al (2016) – Some breast cancers exhibited mutational signatures associated with inactivating BRCA1 or BRCA2 mutations, yet did not appear to exhibit these mutations. Using mutational signatures may serve as a better biomarker than finding the original mutation itself, thus highlighting the importance of WGS rather than just targeted sequencing. 
    * Mutational signature identification requires sensitive variant calling 
    * Machine learning algorithms can assist in rapid identification of aetiologies 
    * MMRD is associated with microsatellite instability, where short repetitive sequences called microsatellites expand or shrink. NGS can be used to analyse microsatellite length distributions to determine whether MMRD has occurred 
        * Can do targeted deep sequencing of clinically validated MSI loci, or screen reads for MSI sites captured during WGS 
* Mechanism of mutational processes
    * E.g. APOBEC deamination mutations were biased to lagging strand 
* Determine cell of origin of cancer – Polak et al (2015) showed that “cell type of origin of a cancer can be determined based on the distribution of mutations along its genome”

**4. WGS can provide clinical insights for improved diagnostics and precision medicine **



* Diagnostics 
    * Circulating tumour DNA – when cancer cells die, they release their genomic DNA into circulation. Liquid biopsies can acquire this DNA for sequencing and identify somatic mutations 
        * Could particularly be helpful for detecting tumours with metastatic potential _before_ the metastasis has occurred to treat patient with anti-metastasis therapeutics e.g. MMP inhibitors 
* Precision medicine – which treatments would be most effective for a particular patient? What is the prognosis? 
    * Targeting driver mutations
        * E.g. Jones et al (2010) – tongue adenocarcinoma sequenced and found that overexpression of RET oncogene was a potential driver. Patient was treated with kinase inhibitors targeting RET, which caused tumour regression 
        * Rosenthal et al (2016) – N of One approaches to mutation signature characterisation 
        * E.g. use mutational signatures to identify primary driver and primary site of cancer 
    * Targeting genomic instability
        * Genomic instability can result in cancer susceptibility. Some cancer genotypes are particularly susceptible to certain cancers. E.g. PD-L1 immunotherapy response is more effective in cancer cells with mismatch repair deficiency (MMRD), synthetic lethality using PARP inhibitors in homologous recombination deficiency (HRD) cancers 
        * E.g. HRDetect 
            * WGS study in 93 breast cancers – HRDetect associated with response to platinum-based chemotherapy 
    * Prediction of cell-of-origin of cancer 
        * Polak et al 