**You discover an uncharacterized transcript originating from a new transcriptional start site. How would you initially characterize the new RNA and the regulation of its expression? Which experimental techniques and computational analyses would you employ in your study?**

# Characterisation 
- Sequence and BLAST it
- What does RNA code for 
	- mRNA -> RiboSeq, cap binding assay, look at sequencing of surrounding *cis* elements 
	- lncRNA
	- small RNAs
- Secondary structure, could also be lnc
	- Predictive 
	- SHAPE
- What proteins does it interact with
	- Radio-label + cross-link
	- IP 
	- Use biotinylated nucleotides 
- Conservation of transcript
	- Phylogenetic analysis 
- KO with RNAi and look for an observable phenotype
- Determine type of RNA 
	- What pol 
	- Morpholinos 
	- Databases for prediction 
	- Secondary structure
	- Localisation 

# Regulation 
Could probably refer to [[Discuss the factors that can affect expression of transgenes in transgenic organisms.]]
## Transcription 
- Identifying *cis* regulatory elements
	- Hi-C to identify loci that loop close to the promoter – they are putative distal cis-elements
		- Mutate these loci and do RT-qPCR to see whether transcript levels are impacted
- Promoter
	- Determine promoter strength by using bioinformatics approach 
- Are there any known TFs for that promoter? 
	- Pull-down with DNA as bait, with heparin as nonspecific DNA binding protein control, and mass spec to identify possible proteins
	- KO candidates then do RT-qPCR on KO vs WT cells to determine if this affected transcript levels
	- Reintroduce the candidate to see if WT rescued 
- What is the local chromatin environment
	- Heterochromatin or euchromatin?
- Biotinylated primers to create biotinylated DNA to identify regulatory proteins that interact with DNA, thus studying how RNA expression is regulated 
- When is it expressed
	- Reporter assay – fuse upstream 2kb to a reporter gene (e.g. GFP) or to stem loops for MS2 

## Splicing 
- Sequence and do sashimi plots to look for AS events
- Alternative isoforms 
- ISS, ESS, ISS, ESE predictions *in silico*

## RNA localisation 
- Organelle 
	- If mito/chloroplast, investigate how it is coordinated with other transcripts
- Phase separation 
- See RNA localisation techniques 

## Non-coding RNA target prediction 
- if transcript codes for a small RNA or lncRNA 

## Translation 
- Is it regulated by miRNA? Which miRNA? 
	- Are there miRNA binding sites in 3' UTR?
- Ribo-seq to determine if it is being translated 
- Presence of regulatory elements like IRES, IREs

## Stability 
- What is the half-life
- Characterise deadenylation and decay via RNA-seq e.g. TAIL-Seq 