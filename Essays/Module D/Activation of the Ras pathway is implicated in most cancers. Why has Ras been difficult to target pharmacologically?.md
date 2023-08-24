**Activation of the Ras pathway is implicated in most cancers. Why has Ras been difficult to target pharmacologically?**

# Intro 
- Ras is a valuable therapeutic target. RNAi of Ras blocked *in vitro* and *in vivo* growth of Ras-mutant human cancer cell lines 
- No therapeutic agent that directly targets RAS has been clinically approved 

# Main

## Direct inhibitors of Ras have poor affinity or are too narrow in scope
- Target the nucleotide binding pocket of Ras 
	- Explain the necessity of the nucleotide binding pocket to Ras function 
	- However, GTP binds Ras with picomolar affinity, making it challenging to discover drugs that can bind with even greater affinity
- Newly discovered pockets
	- E.g. #experimental_evidence  Kessler et al (2019) discovered a new nanomolar inhibitor of the switch I/II pocket on KRAS using structure-based drug design 
	- E.g. #experimental_evidence The inhibitor SCH-54292 was found by NMR to bind to the hydrophobic pocket near Switch II; NOE suggests that the molecule binds via hydroxylamine 
		- However, hydroxylamine is not an ideal functional group for a drug because it is toxic and has poor metabolic stability.
		- It was also not potent enough to be a drug 
- Selective targeting of Ras mutants
	- Shokat group -> small molecules that bind selectively to G12C mutant form of KRAS at a pocket between alpha2 and alpha3 helices. Compounds blocked SOS1-mediateed nucleotide exchange, and decreased Ras binding to BRAF, CRAF 
	- Problem is tumour heterogeneity – G12C is not a common Ras mutation outside of lung cancer, so this is not a generally applicable solution 
- Different Ras mutations could also respond differently to different therapies. So therapies have to be mutation-specific. 
	- E.g. Patients with KRAS G13D colorectal cancer responded to cetuximab, an EGFR therapy, but patients with KRAS G12D did not. 
- Binding affinity of many early stage compounds have to be improved to be an effective drug 
	- E.g. link the compounds together 

## Targeting Ras membrane localisation could be cytotoxic 
- Explain why targeting Ras membrane localisation is important 
- FTIs developed were unsuccessful in treating pancreatic and colon cancers which are associated with KRAS or NRAS 
- But they were able to block growth of Hras-driven tumours 
	- However, HRAS mutation is not common 
- These differences were due to differences in prenylation between the Ras isoforms (tumour heterogeneity). 
	- KRAS4B and NRAS are geranylgeranylated instead of farnesylated when FTI was given. This allowed them to escape FTI-mediated inhibition 
- GGT might be inhibited as well, and genetic studies in a KRAS-G12D lung cancer mouse model indicate that blocking FTase and GGTase I could be effective. But there is caution about how toxic in normal tissues given the number of substrates these two prenylases target 
- Inhibit RCE1 and ICMT, which are also involved in prenylation? 
	- The concern here is that they could also have a very low therapeutic index as they are needed for the function of many other proteins involved in normal cell physiology. Membrane-associated with a CAAX box could potentially require these enzymes for their correct localisation. Inhibiting them could lead to tissue toxicity 
		- E.g. ICMT also needed for prenylation of Rab GTPases that regulate vesicular transport 
	- Inhibition may also have unintended effects
		- *Rce1* deletion in KRAS-G12D mouse haematopoietic cells enhanced myeloproliferative disease 
		- "*Icmt* ablation concurrent with KRAS-G12D activation in the pancreas caused increased pancreatic intraepithelial lesion formation and accelerated neoplastic progression"
- Inhibit palmitoylation and depalmitoylation 
	- HRAS and NRAS are palmitoylated
	- But KRAS4B is not palmitoylated, and this is the most commonly mutated Ras in cancers. 
	- Same issue other prenylation inhibitors in that palmitoylases/ depalmitoylases are probably involved in palmitoylation of other proteins with normal functions -> poor therapeutic index 
	- There is also insufficient understanding of which palmitoyl acyltransferases are involved in Ras palmitoylation. There are 24 known mammalian palmitoyl acyltransferases, 1 of which is known to palmitoylate Ras proteins (DHHC9-GCP16), and we do not know if there are others involved as well. If there are, then compensatory palmitoylation by other enzymes would make inhibition ineffective
- Upregulate phosphorylation of KRAS4B at S181, which causes Ras to dissociate from plasma membrane and move to endomembrane, and converts its activity from growth-promoting to growth-suppressing 
	- Bryostatin, a PKC agonist, can cause KRAS4B phosphorylation to translocate to endomembranes, and mouse tumour xenograft was impaired by this treatment 
	- But again, PKC is a pleiotropic protein. Agonists of PKC could have unintended side effects on the cell 
	- It is also not actually clear if phosphorylation will definitely reduce cancer growth, as another study found otherwise. 

# Targeting the Ras pathway 
- Explain briefly the downstream pathways of Ras and how they are involved in tumourigenesis 
- Targeting the downstream Ras pathways can be challenging as it is pleiotropic – off-target effects may occur 
- Complex regulatory networks support phenotypic plasticity in RAF-MEK-ERK pathway. Compensatory mechanisms lead to seemingly paradoxical outcomes for effector inhibitors. 
	- RAF-MEK-ERK pathway has a complex regulatory network, such that perturbing the activity of any of the central signalling enzymes involved can be unpredictable 
	- E.g. "Raf Paradox" – Treatment of patients with Raf inhibitors (Vemurafenib, dabrafenib) actually activated the RAF-MEK-ERK pathway. 
		- Raf actually exists as a dimer that can be homo or heterodimers between the three isoforms. When in a dimer, one Raf monomer inhibits the other by phosphorylating it. In the cell, BRAF can form a heterodimer with CRAF, and specific inhibition of BRAF resulted in activation of CRAF. This increased stimulation of the RAF-MEK-ERK pathway. 
		- As such, BRAF inhibitors should not be used in Ras cancers
			- Patient stratification / personalised medicine 
	- First generation MEK inhibitors were also developed, the majority of which acted as non-ATP competitive inhibitors of MEK1 and 2. However, MEK inhibitors also had underwhelming early clinical trials due to compensatory and feedback mechanisms induced by MEK inhibitors
	- One of the common mechanisms of acquired resistance to RAF or MEK inhibitors is reactivation of ERK, to which the obvious solution might be to use an ERK inhibitor. But ER inhibitors also paradoxically enhance MEK activation because it blocks the negative feedback from ERK to RAF. 
- Tumour heterogeneity – not all Ras effectors are important in all cancers for tumourigenesis 
	- E.g. Inhibition of PI3K pathway in a KRAS-driven mouse lung cancer model did not block tumour growth 
	- E.g. KRAS silencing in KRAS-mutant colorectal cancer cell lines did not reduce activation of AKT. Increased RTK signalling increased compensated for reducing signalling from KRAS to AKT
	- Ral pathway – e.g. RALA important for pancreatic cancer cell lines, but not RALB. In contrast, both RALA and RALB loss required to block RAS-driven lung or skin tumour growth in mouse models
- Some of the effectors themselves are hard to target directly, e.g. Ral 
- As multiple driver effectors are involved in the Ras pathway, therapies may have to target multiple effectors, but combining too many therapies could result in cell toxicity and close the therapeutic window 

# Conclusion 
- Ras has been difficult to target pharmacologically mainly due to incomplete understandings of biology in the development of various drugs 
- Ras is also situated at an important signalling node, and interacts with proteins that also have pleiotropic effects. Perturbing the activities of many of these proteins could have unintended off-target effects 
- Tumour heterogeneity is also generally a problem. There are three different Ras isoforms, KRAS, NRAS, HRAS. The isoform that is mutated and the mutation in the isoform can differ between particular cancers. Most commonly the G12 residue is mutated to another, but some other residues such as Q61, A146, G13, etc have also been observed to be mutated in Ras. To target Ras pharmacologically, the strategy may be different for each Ras and we don't always know which Ras is mutated in the tumour – whole exome sequencing has not been rolled out everywhere. Personalised medicine generally has a problem of market fragmentation. 
- On the bright side, this does suggest that as more research on Ras is done, we are more likely to develop successful treatments
- Some future directions 
	- RNAi silencing of RAS 
	- Identify tumour-selective immune recognition sites on KRAS 
	- KRAS known to stimulate expansion of immunosuppressive myeloid-derived tumour immunity – could this be exploited? 

# References
