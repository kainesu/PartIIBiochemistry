# Questions 
- Describe how a microRNA can act as an oncogene.
- How might miRNAs act as tumour suppressors?
- ==Cancer is an epigenetic disease. Discuss==

[[B7 Small RNAs]]
# miRNA in cancer
## Post-transcriptional regulation of miRNA expression 
- Different miRNAs regulate each others' expression 
- E.g. Let-7 and lin-28 are in a double negative feedback loop with each other 
	- #experimental_evidence In vivo functional assays
	- #experimental_evidence let-7 accumulates in lin-28 mutants
	- LIN28 in turn inhibits Dicer cleavage of the let-7 microRNA, eventually resulting in its uridylation and subsequent degradation ![[Pasted image 20230408231306.png|500]] ^37307f
	- #experimental_evidence Lightfoot et al (2011) – In vitro study that combined RNAse footprinting, gel shift binding assays, and processing assays. Regions in terminal loop of pre-let-7 interacts with LIN28, and a conformational change occurs upon this binding that results in unwinding of a normally double-stranded region at the Dicer processing site of pre-let-7g. 

## Functions  
### Development in C. elegans 
- Hypodermal cell lineages give rise to outer epithelial layer of C. elegans and secrete the cuticle ![[Pasted image 20230408224822.png]]
	- In each larval stage, cell division gives rise to different cell types 
	- Triple line = stop division (Adult)
- Different lin, let, or daf mutants result in heterochronic phenotypes ![[Pasted image 20230408225103.png]]
	- "Precocious" phenotypes are advanced and appear to skip stages in development 
		- E.g. lin-4(lf) mutants appear to reiterate cell divisions of L1 stage 
	- "Retarded" phenotypes appear to be slower in development 

#### Let-7 members control developmental timing 
- In some mutants, the epithelial cells continue to divide without stopping, resulting in formation of excess epithelium ![[Pasted image 20230408225209.png]]

#### Let-7 and lin-4 control an early and a late developmental switch 
![[Pasted image 20230408225241.png]]
- #experimental_evidence A lin-4 KO phenotype was similar to gain of function allele in lin-14
- #experimental_evidence Lee et al (1993) – lin-4 encodes small RNAs with antisense complementarity to lin-14 3' UTR. A 3'UTR deletion in lin-14 results in a gain of function allele 

## Cancer 
- We can group gene expression patterns of different miRNAs from different samples
- Primary tumours do not have consistent miRNA expression patterns 
- miRNAs cluster tissues with similar developmental history 
- miRNAs are deregulated in human cancer, with many down-regulated in the primary human tumours 
	- This may be because miRNAs are hallmarks of differentiated tissues. Different tissues have specific miRNAs that are particular to them, but tumour cells are trying to break free of the constraints of development. This requires downregulating miRNA expression that enforce the differentiated state 
		- #experimental_evidence see [[D7 Small RNAs and cancer#^37307f|LIN28]]

### miRNAs as tumour suppressors
e.g. let-7 (RAS, HMGA2), miR-200 (ZEB1)

- #experimental_evidence He et al (2005) – 
- #experimental_evidence Let-7 KO leads to increase in cell proliferation 
- Metastasis  ^d0aacd
	- #experimental_evidence miR-200 regulates ZEB1 (see [[D12 Invasion and Metastasis#^8cee46|Master TFs]]), which in turn regulates E-cadherin. E-cadherin is required for maintenance of the epithelial state. KO of miR-200 results in dysregulation of E-cadherin and promotes epithelial to mesenchymal transition (EMT)

### miRNAs as oncogenes 
e.g. miR-15/16 (BCL2, MCL1), miR17~92 (E2Fs, BIM, ..)

- Lin28 can act as an oncogene by inhibiting let-7 cleavage  ^b32bc0
	- #experimental_evidence LIN28 can be activated along with other genes (NANOG, OCT4, SOX2) to reprogram fibroblasts to pluripotency (human iPS cells)
- mir17-92 polyicstron is amplified in human B-cell lymphomas and promotes tumour formation; but how overproduction of mir-17-19b promotes oncogenesis is unclear 
	- #experimental_evidence He et al (2005) 

# piRNA 
- piRNAs are an animal adaptive defense mechanism against **transposons**
- piRNA systems somewhat analogous to CRISPR system in bacteria, in that piRNAs are derived from transposons encountered by the organism. Each transposon has a corresponding piRNA to direct its destruction 
- Most piRNA sequences are contained in the centromere, with some around the telomere 
- Most species have evolved parallel ways to prevent transposon activity apart from piRNA pathway 
	- In mice alone, there are multiple and redundant mechanisms for LINE1 silencing which act at different stages of development 

## Mechanism of action in *Drosophila*
### Somatic piRNA pathway  
- piRNA is loaded onto piwi proteins (e.g.Ago3), which are related to Ago 
- Piwi proteins hold piRNA and use them as guides to destroy transposons

### Germline piRNA pathway 
- piRNAs are highly specialised for germ cells and can amplify themselves; the mechanism of amplification differs between species 
- Before letting go of the target, another piwi protein (e.g. aubergine) can bind and cut a piRNA fragment out of the target 
- The ping pong amplification cycle in *Drosophila* generates new piRNA from sense and antisense strands of the transposon 

### Biosynthesis 
1. Most piRNAs are clustered at short genomic loci 
2. Transcribed by RNAP II as long transcripts, which are then exported to the cytoplasm and processed into smaller sequences 
3. Ping-pong amplification 
	1. piRNAs in association with AGO3 or AUB in *Drosophila* (MILI and MIWI2 in mouse) recognise transposon transcripts containing clusters of identical/near identical sequences 
	2. Anneal sequences via AGO3/AUB slicer activity 
	3. Cleave sequences to produce new antisense piRNAs 
	4. New piRNAs target other piRNA-cluster transposons 

## Mechanism of action in mice 
### Germline piRNA pathway inhibits transcription of transposon 
- In mouse, piwi = miwi, mili 
- Miwi2 can transport the piRNA into the nucleus, fin the locus where the transposon comes from, and change local chromatin in an RNA-guided manner (or add DNA methylation). This prevents further transcription ![[Pasted image 20230408235731.png]]

# Studying small RNA expression 
## In-situ expression analysis 
- Use of "locked" nucleic acid, which is an artificial nucleotide that works as a probe. 
- Zebrafish 

## In vivo assay for miRNA function 
- Fluorescent proteins (e.g. GFP) used as reporters for miRNA levels
- The miRNA under study and a control miRNA are tagged with fluorescent protein 
- Ratio of miRNA of interest fluorescence and control fluorescence is a measure of miRNA transcriptional level 
- #experimental_evidence *lin-28* negatively regulates *let-7* activity 
![[Pasted image 20230408230705.png]]

## Genome wide identification of small RNAs 
1. Sequence transcriptome
	1. Isolate total RNA 
	2. Ligate RNA 3' adapter 
	3. Ligate RNA 5' adapter 
	4. RT-PCR 
	5. Gel purification 
	6. Next gen sequencing 
2. Sort and trim adaptors (computationally) 
3. Search for matches to annotated transcripts in databases 
4. Align unmatched transcripts to a reference genome of organism from which total RNA was isolated 

## Computational prediction of miRNAs from deep sequencing data 
E.g. #experimental_evidence Friedlander et al () 
- since miRNA comes from stem loop RNA that is cut by Dicer, we can discover new miRNAs in the genome by looking for adjacent regions of genome that can form a stem loop 

## Identifying target regions 
- Almost all miRNAs target the 3' UTR, so the sequence space to explore is smaller
- However it is still difficult to find miRNA targets due to **imperfect complementarity** and different **mechanisms of targeting** ![[Pasted image 20230408233946.png]]
	- #question what is the difference between these mechanisms? 
- Current algorithms are poor at predicting miRNA targeting, and even one of the best algorithms (PACMIT) only predicts 10/100 of top 100 hits correctly 
	- CLIP-Seq doesn't work as well as ChIP-Seq
		- RNA can base pair to each other and secondary structure formation thus makes cross-linking less efficient. In comparison, DNA is less sticky to other things. 
		- Argonaute proteins are also bad at crosslinking (for whatever reason) 
	- As a result, it is difficult to validate algorithms 
- An alternative method of predicting miRNA targeting is to use the principle of conservation – conserved sequences that are also known to be miRNA targeting sites in related species are more likely to be genuine miRNA targeting sites 
	- However, this makes it difficult to find miRNAs that only evolved recently, or are particular to certain species 
	- #experimental_evidence Prediction of miR-1 targeting – check for matching 8-mer sites across related species, then check which of these 8-mer sites are conserved 
	- Sequence context is also important – in the region SLC35B4, the 3' UTRs of the identified species vary greatly, yet the miRNA binding sites stay the same; in contrast the 3' UTRs for SPRED1 are more similar. In this case, the miRNA binding sites in SLC35B4 are more likely to be important since they have been conserved despite higher net rates of mutation in the surrounding region 
		- #principle The level of conservation of a gene should take into account the relative rates of mutation between species being compared. Rates of mutation differ between species and at different regions of the genome. 

# Therapies
- Antimirs – difficult to deliver 