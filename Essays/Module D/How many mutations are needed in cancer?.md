**How many mutations are needed in cancer?**

* Mutations = driver mutation
- Cancer is actually far less frequent than expected given the rate of mutation and number of cells in a human – one of the reasons may be that nascent tumour cells actually have to mutate more than 1 gene to successfully develop into a tumour
- Evidence from comparative genome hybridisation studies show that many solid human cancers have multiple regions of gene loss and gain
* Needed in cancer 
    * Needed for initial malignant transformation?
    * Needed for proliferation?
    * Needed for survival? At what point along cancer development? 
    * Which tissues? Solid vs liquid? 

# **Only 1 mutation?** 

* What is cancer...? A single mutation could be sufficient for tumour transformation of a single cell, but would it be enough for it to proliferate before immune cells kill them?
* In GEMMs, knockout of p53 is sufficient to drive tumour growth
    * Alteration in expression or signalling of such nodes could be sufficient to drive cancer 
    * E.g. Activation of MycER<sup>TAM</sup> is sufficient to drive proliferation _in vivo_ in mice 

# **More than 1 mutation is generally needed**
In general, it is quite rare that only 1 mutational event cause cancer 

## A single oncogene is not sufficient to overcome inhibitors of cell proliferation 
- Overexpression or hyperactivity of a single oncogene may be insufficient to cause tumour formation as individual oncogenes are unlikely to cause the full spectrum of cancer hallmarks on its own under in vivo conditions
- “Mutations in _BRAF_ and _NRAS_, originally qualified as drivers, could not fully explain melanoma oncogenesis, as these same mutations have been found at similar rates in benign nevi" (Adjiri et al 2017)
	- Hypothesised that lack of tumourigenesis due to RNAi, or another mutation could be needed to drive tumourigenesis. 
- E.g. Myc and Ras – both must be oncogenic to transform cells in culture 
	- Land et al (1983) found that neither Ras nor Myc were able to transform rat embryo fibroblasts on their own, but when both oncogenes were introduced into the fibroblasts at the same time, the cells were able to yield fibrosarcomas after injection into mice  
	- The authors explain this observation by stating that, while the Ras oncogene is a strong inducer of refractile morphology, anchorage independence, and growth factor secretion, and weak in its ability to immortalise cells, the Myc oncogene is good at immortalising cells while weak at inducing refractility, anchorage independence and growth factor secretion (likely as they act via different signalling pathways) 
	- Concurrent mutation in both genes thus allows for maintenance of a fuller spectrum of cancer hallmarks that allows for successful tumour formation and maintenance
- After formation of tumour, maintenance of the tumour requires maintenance of a favourable tumour microenvironment → extrinsic and intrinsic hallmarks of cancer likely controlled by different genes e.g. immune evasion
	- E.g. in hematopoietic tumorigenesis, Ras is thought to suppress immune surveillance, allowing for cells overexpressing Myc to form tumours (Mahauad-Fernandez & Felsher 2020)
- In addition, cells have regulatory pathways that sense and suppress oncogenic activity via cell cycle arrest and DNA repair or apoptosis, such that cells with a single mutated oncogene are unlikely to survive and proliferate 
	- This occurs via activation of tumour suppressors if oncogenic signalling above a threshold level is sensed 
	- E.g. elevated Myc expression can induce apoptosis via p53 signalling – high levels of Myc activity increases E2F transcription factor activity, and this increased activity is sensed by Alternate Reading Frame (ARF) protein. ARF then inhibits a p53-specific ubiquitin ligase, Mdm2, from ubiquitinating p53. This prevents the degradation of p53, allowing it to trigger cell cycle arrest and/or apoptosis 
- As such, for a mutation in Myc to lead to tumour formation, there may also have to be a mutation in p53 that occurs simultaneously or within a short time frame to prevent apoptosis 
	- #experimental_evidence Ulz, Ellen & Speicher (2016) found that there is a highly significant co-occurrence of MYC amplification with mutations in the TP53 gene in the TCGA breast cancer data set
	- #experimental_evidence  in murine melanoma, oncogenic H-RasV12G only causes tumours in mice that also have a deletion in p16 (which causes growth arrest in response to high levels of oncogenic Ras signalling)

## A single tumour suppressor mutation is not sufficient to cause cancer
- Tumour suppressor genes are most loosely defined as genes whose inactivation promotes the incidence of cancer, however mutations in certain tumour suppressor genes alone cannot transform a cell to adopt the various hallmarks of cancer (e.g. excessive proliferation, immortalization, angiogenesis) which would allow for successful tumour formation 
- Mutation such tumour suppressor genes (e.g. caretaker genes) simply lifts the suppression on or encourages oncogenic activity in the cell without directly causing cancer hallmarks. Loss of tumour suppressor genes only leads to cancer due to accumulation of mutations in other genes 
- E.g. BRCA1/2 – involved in DS break repair, particularly DNA damage sensing and maintenance of genomic integrity
	- Germline mutations in tumour suppressor genes e.g. BRCA1/2 do not immediately cause cancer. Babies with these mutations are not born with cancer. Instead they are just predisposed to cancer, developing cancer much earlier in life than average.
	- However, in theory if no DS breaks occur in the cell, then a BRCA1/2 mutation will not lead to tumour formation as the cell is effectively like a normal cell 
	- The problem is that in reality cells do suffer numerous DS breaks that are usually repaired, but without BRCA1/2, these DS breaks remain, leading to oncogenic mutations that then drive tumour formation
- Moreover, tumour suppressor genes can often be compensated by other pathways. Even if mutation or loss in one tumour suppressor pathway occurs, there are backups to accommodate this loss 
	- E.g. p53 signals to metabolic genes via many pathways to prevent Warburg metabolism. Mutation in one of these pathways unlikely to be sufficient to cause malignant transformation

# Factors affecting number of mutations 
* Importance of the tissue of origin – some mutations can occur in some tissues without causing cancer, but do cause other diseases. There may be a tissue-dependent effect of different mutations 
    * E.g. mutations in p53 have been found in synovial cells of rheumatoid arthritis patients 
- The order of the mutations matters, and the order can be different for different tissues. 
* Apart from the tissue of origin, the exact number of mutations may depend on the stage of the cancer
    * As tumour mass grows, may need angiogenesis, other tumour microenvironment modifications to stroma to accommodate the mass 

## Increase fitness compared to other tumour cells 
* In addition, necessarily during cancer development, tumour cells acquire an increasing number of mutations due to the process of clonal evolution. 
    * Subclones in the cancer compete, requiring increasing mutations to increase their fitness over other subclones, thus allowing them to proliferate in an environment with limited resources e.g. oxygen 
    * At the same time however, it has also been observed that the frequency of certain driver mutations decreases with malignancy progression
        * E.g. “incidence of the BRAF V600E mutation in benign nevi and premalignant conditions or dysplastic nevi is more frequent (~ 70–88% and ~ 60%, respectively) than in melanoma (~ 40–45%)”

# **0 mutations?** 
* Due to aberrant interactions with tumour microenvironment that deregulate the tumour cell, rather than mutations within the tumour cell itself
    * E.g. Raaijmakers et al (2010)

# **Is there an upper limit?**
* Shlien and colleagues – “repair deficiency and the high mutational load might be the Achilles’ heel of ultra-hypermutated tumors… cells from bMMRD/polymerase cancers acquire up to 600 new mutations with each cell division. However, when 10,000 to 20,000 exonic mutations are reached, the tumors seem to hit an upper limit of the tolerable mutational load. Neither pediatric nor adult cancers with constitutional and somatic MMR/polymerase defects exceeded this mutation level [2,3,5].” 
* PARP inhibitors are synthetic lethal likely because the removal of both single strand and double strand break repair mechanisms leads to an unbearable mutational load for the tumour 

# Conclusion 
* Difficult to say how many particular mutations a cancer needs. Answer depends on the context. 
* Cancer could be a **continuum**, with the malignant disease that is diagnosed as “cancer” as an endpoint. Mutations can result in a precancerous state that do not necessarily lead to cancer but predispose an individual to cancer should the mutated cells not be removed 