# Questions
- Applications of model systems
	- Select a model system and discuss how it has been employed to advance our knowledge of a specific process contributing to human cancer.
	- *==How can the study of laboratory organisms inform us about cancer in humans?==*
	- ==What are “driver” and “passenger” mutations in cancer? Discuss experiments to distinguish between them using a model system.==
		- Spontaneous mutation -> sequence tumour -> which are more frequent
		- GEMMs -> introduce that driver mutation only 
		- or mutate cell cultures
		- lentivirus crispr array 
	- What is the difference between a driver and passenger mutation? Describe an experiment to distinguish between them using both an in vitro model system and an autochthonous mouse model.
	- You have sequenced a cancer genome and identified a somatic mutation that you think may be a driving event in cancer. You have the same cancer cell line available in the laboratory. Discuss several in vitro and in vivo experiments you can do to confirm that the mutated gene has oncogenic potential.
	- How has the study of Drosophila development contributed to our understanding of cancer?
- Advantages and limitations of different cancer models
	- *==What are the advantages and limitations of model systems for our understanding of cancer in humans?==*
	- Describe hallmarks of cancer that can be modelled in autochthonous systems but not in in vitro culture systems.
	- Yeast do not get cancer and therefore have not contributed to cancer research. Discuss.
	- The only valid experimental model for understanding cancer is the human patient. Discuss.
		- "Flawed, but can't deny that many oncological discoveries were done in non-human models, and yet were applicable"
		- Models could be valid in terms of chemistry (e.g. DNA), fundamental molecular processes (e.g. cell cycle)
		- However, they may not be as valid in other aspects e.g. gene interactions, microenvironments, systemic effects (endocrine, metastasis)

# List of models
- E. coli 
- S. cerevisiae 
- C. elegans 
- Drosophila 
- Zebrafish 
- Mice 
- Human tissue culture
	- Fibroblasts 
	- Cancer cell lines (general and personalised, i.e. taken from the patient)
- Organoids (can be personalised)
- Humans
	- GWAS
	- Cohort studies 
	- Clinical trials 

# Goals of using model systems
1. Make accurate *in vivo* copies of human cancers in a controllable, perturbable, and experimentally tractable animal 
2. Model oncogenic processes (proliferation, apoptosis, invasion, inflammation, tumour microenvironment, angiogenesis) *in vivo*
	1. We cannot model the full lifespan of a human that leads to cancer, but we can model specific processes
	2. Genotype to phenotype linkage must be easily made for screening 

## Desirable properties in a model system 
The perfect model of human cancer would recapitulate
1. Sporadic initiation in authentic cell of origin 
	1. but we don't know what is the authentic cell of origin for many cancer cells [[D11 Cancer Stem Cells#Cell of Origin of CSCs]]
2. Progressive accumulation of mutations in pathways that reflect their human cancer counterparts
	1. But we don't know why some mutations are more c
3. Responses of human cancers to cancer therapies 
	1. In mice models, we often get higher therapeutic efficacy than is mirrored in human patients as the cancers are simpler and artificial 
4. Yet exhibit rapid, controllable, and reproducible tumour genesis, tumour evolution, and metastasis 
	1. Rapid enough to be done within lifespan of investigator

Not all of these properties can be achieved, so compromises have to be made 

# Applications of model systems 
- Differentiate driver and passenger mutations
- Understand consequences and molecular interactions of oncogenic mutations 
- Identify therapeutic entry points into disease 
- Pre-clinical, IND enabling, and clinical data 

## Testing therapeutics 
- #experimental_evidence TGN1412 (Theralizumab) is an antibody raised against CD28, a T-cell co-activator, to stimulate T-cell killing of leukemia cells (B-CLL). Tested in mice, rats, macaques. But it didn't work in humans.  

# Types of model systems 
## Yeast 
- #experimental_evidence Fission yeast have been instrumental to the discovery of numerous cell cycle regulatory proteins e.g. CDKs 
- #experimental_evidence Budding yeast have been used to show that deregulation of chromosome separation leads to a greater repertoire of mutations in tumour cells. 
	- Did genetic screen for CIN genes, or genes involved in chromosomal stability 
	- ADE2 mutation results in a red colony phenotype when grown on adenine. After subjecting the yeast to mutagenesis, pick colonies that are white or pale, as they have regained the ability to synthesise adenine. Sequence these colonies – mutation may be gain of function in ADE2, suppressor mutation, or other mechanism 

## Drosophila melanogaster 
- #experimental_evidence Screening for modifiers of metastasis using Ras<sup>V12</sup>-GFP clones. Metastasis promoting mutations results in invasion of GFP-positive cells into ventral nerve cord from the brain  
- #experimental_evidence Das et al (2013) – Chemical screening for inhibitors of Ret 
	- Drug identified in screening was effective in humans 
	- The drug used did not have an effect in mice, so in this case the fly had more predictive value than the mouse, surprisingly! 

## Organoids 
- Can be derived from the patient
	- Biobanking 
- Chemical genetics screening in organoids derived from patients 
- #experimental_evidence Organoid model of colon cancer. CRISPR-Cas9 used to introduce mutations to induce cancer in a gut organoid. 

## Patient-derived xenografts (PDX)
Growing human cancers in mice. 
1. Isolate patient's cancer 
2. Cut it up 
3. Introduce small amounts of it into a genetically immunocompromised mice (so it won't reject the human tissue)
![[Pasted image 20230409123046.png]]


## Transgenic mice 
- Fundamental mechanism by which oncogene is activated is quite similar between mice and humans 

### Tissue-specific promoters 
- Oncogenes can be targeted to specific tissues using tissue-specific promoters, resulting in development of cancer in that tissue. In this case, the biology of the model depends on the biology of the promoter. 
	- E.g. RIP-TAg – RIP is a rat insulin promoter to drive gene expression in pancreatic beta islet cells. TAg is SV40T/t. Thus drives expression of tumour virus gene in pancreas 
	- E.g. Oncomouse – MMTV promoter (mammary glands) driving Ras/Myc -> breast cancer 
	- E.g. TRAMP – probasin promoter (lipocalin transporter in prostate) with SV40/Tt -> prostate cancer 
	- E.g. Eµ-Myc – IgH enhancer -> Myc. Drives Burkitt's lymphoma 

### Gene knockouts 
- Using heterozygous or homozygous deletion of tumour suppressor genes from germline, resulting in gene being absent from all somatic cells 
	- E.g. p53 KO, Rb KO, p19<sup>ARF</sup>, p16<sup>INK4A</sup>, PTEN KO 

### Genetically engineered mice models (GEMMs)
- Contain inducible transgenic oncogenes and dominant negatives to switch oncogenes on and off at will 
- Toggleable systems (Tet, ER) are more rapidly turned on (minutes) and are reversible, but may be more leaky than deletion. Also advantage over deletion system is that the timing of deletion can be chosen, so it can be done when the mice is fully developed instead of throughout the mouse ontogeny (when it may be ectopic)
- Deletion systems (Cre, Flp, CRISPR) are slower and are not reversible, but are less leaky 

#### Tet system
- Tet On system (default "off") – Transgene on when Tet is present, off when absent. ![[Pasted image 20230409130521.png|425]]
- Tet Off system (default "on") – Repressor is built into the transgene, so gene is turned off when there is Tet, while gene is turned on when there is no Tet ![[Pasted image 20230409130424.png|400]]

#### Estrogen receptor (ER) system
- "Switchable" variants of oncoproteins and tumour suppressors
- ER<sup>TAM</sup> system – Target protein is fused to a modified hormone binding domain of the estrogen receptor. When tamoxifen is added, it binds to ER and displaces ER from inactive association with Hsp90 and translocates to nucleus, allowing the attached protein to act in the nucleus  ![[Pasted image 20230409130804.png|375]]
- ER system is advantageous over Tet as it regulates activity of the Myc protein rather than at the transcriptional level like Tet. This ensures that th level of activated gene product is predictable and consistent 
	- This is particularly important of Myc as different levels of Myc can result in different biological outputs 

#### Cre-Lox and Flp-frt site-directed recombination
- Conditional Cre-Lox transgenics and knockouts for sporadic, hit-and-run gene activation/deletion
- Cre recombinase is a site-specific recombinase used to excise DNA lying between two recombinase recognition sites, called loxP sites 
- Cre has type 1 topoisomerase-like activity that catalyses site-specific recombination between loxP sites, such that DNA flanked by loxP sites is excised ("floxed")
- Flp-frt system is similar, where Flp recombinase is used to recombinse sequence between Frt sites

#### CRISPR-Cas deletions 
- Use CRISPR system to delete

#### Combining switches 
![[Pasted image 20230409131144.png]]
- In this common switchable Myc construct, multiple switches can be combined to control expression of a gene 
	- Constitutive expression is blocked by a stop sequence
	- When tissue is treated with Cre, it removes stop sequence 
	- ER<sup>TAM</sup> allows for toggleable activity 
- To make activation tissue-specific, just use a tissue-specific promoter 

## Autochthonous cancer models 
- Endogenous or in situ tumour that evolves from normal cells in an animal (e.g. chemically induced tumours, viral induced tumours), which is in contrast to tumour models in which exogenous tumour cells are implanted into the animal (xenografts) 
- Models spontaneous occurrence of tumours and full range of cancer hallmarks  
- #experimental_evidence **Modelling tumour microenvironment**. Tumour cells invoke a local inflammatory environment that drives tumour progression. 
- #experimental_evidence **Modelling angiogenesis**
- #experimental_evidence **Modelling immune evasion**. Tumour cells induce secretion of repulsing chemokines that prevent cytotoxic T cell function; testing therapeutics target immune checkpoints  
- #experimental_evidence **Modelling systemic responses**. Tumour derived factors that recruit immune cells to the TME and instruct metastasis; Abscopal effect (treating primary tumour causes secondary tumour to shrink, reason unclear )

## Humans 
- Clinical trials 
- #experimental_evidence Clinical trials of combination therapy involving herceptin + EGF inhibitor found to be effective in treating breast cancer 

# Advantages and limitations
## In vitro systems 
### Disadvantages
- Culture conditions are optimised for cell/tissue proliferation and survival, which is not representative of the biological context 
	- Serum with mitogens and survival factors
	- Poorly controlled oxygen within the culture medium
	- Abnormally high levels of nutrients and supplements
	- Enforced biosynthetic "Warburg" metabolism 
- Do not recapitulate tumour environment or systemic effects 
	- Problematic for testing certain drugs that target tumour microenvironment/systemic effects ![[Pasted image 20230409165306.png]]

## Saccharomyces cerevisiae 
### Advantages
- Simple and tractable genetics, easy to manipulate 
- Conductive to genetic screening, as mutations can be introduced, phenotype analysed and mutation recovered easily (high throughput)
- Some genes conserved, e.g. MSH2 (driver of HNP colon)

## Drosophila melanogaster 
### Advantages
- Multicellular 
- Genetically tractable – CRISPR/Cas9 
- Conducive to genetic screening – can introduce stable mutations and recover them
	- E.g. rough eye phenotype is a result of overexpression of Ret receptor tyrosine kinase in the eyes of *Drosophila* (driven by GMR promoter). Ret mutations drive a rare multiple endocrine neoplasia (MEN type 2A)
- Many cancer pathways in humans are conserved e.g. Wnt, EGFR, BMP, Notch, Hh/Gli 

## Tissue cultures
### Advantages 
- Cheap
- Experimentally tractable 
- Conducive to screening 
- Frontline model for cell autonomous hypothesis testing 

### Disadvantages 
- Tumours are tissues, not cell monocultures
- 2D, while tumours are 3D. A superstructure, tumour microenvironment is needed around the tumour for them to grow 

## Organoids 
### Advantages
- Can be morphologically and architecturally very similar to original tumour (e.g. colorectal cancer)

### Disadvantages 
- Gut organoids have to be broken up and reseeded to recapiculate turnover 
- Liver organoids are really a model of an inflammed liver, as we have to inflamme the liver and obtain cells that can divide 
- There could be heterogeneity between organoids generated from biopsies taken from different parts of the tumour 

## Invertebrate systems 
e.g. flies, nematodes 

### Advantages
- Cheaper
- Less ethically problematic

### Disadvantages
- Invertebrate systems don't really get cancer 
	- Little, if any, tissue regeneration, so there are few opportunities for mutation and clonal growth 
	- Short life span, so not enough time to accumulate somatic mutations
	- Small size, so there are imnsufficient number of cells in which mutations can accumulate 

## Mice 
### Advantages
- Short lifespans 
- Breed quickly
- Well understood genome 
- Genetically related to humans, share many homologous genes and orthologous anatomies (though not all)

### Disadvantages
- Ethical issues 
- Highly regulated – 3Rs of reduce, refinement, replacement 
- Difficult to handle – messy, smelly, unpleasant
- Difficult to control experimentally
- Difficult to perturb experimentally
- Expensive 
- Less genetic variation than humans – mice models are inbred 
- Experimental therapeutics often exhibit higher therapeutic efficacy in mice than in human patients 
- Different rates of tumour evolution in humans vs mice 
	- Mice have a far greater cancer risk per cell per unit time than humans 
- Humans and mice have differences in stromal signalling, and we often have to work out what the human equivalent of signalling pathway is in the mice one. Some often do not have equivalents e.g. GlyCAM, Caspase 10. 
- Differences in telomere maintenance by telomerase – mice have very long telomeres compared to humans, so there is more protection from telomere erosion, such that cells reach senescence and genomic instability differently from humans [[D2 DNA damage repair#Telomeres]] 
- Tumour suppressor pathways in mice are different from in humans 
	- Oncogenes cause [[D3 Oncogenes and Tumour Suppressors#Intrinsic tumour suppression|intrinsic tumour suppression]]. Ras is inhibited by two loci, p14<sup>ARF</sup> and p16<sup>INK4A</sup>, which are in the same loci in both humans and mice. In small proportions of human or mouse cancers, one of these ORFs gets corrupted but not the other. In mouse cancers, the p14<sup>ARF</sup>/p53 pathway is lost more often, so this is more important for tumour suppression. In human cancers, p16<sup>INK4A</sup> is lost more often. So although these two mechanisms seem to be redundant, there are seems to be differences in mice and humans as well. We don't know why and we don't know what the implications of these are for cancer. 
- Mice and humans have different diets and carcinogen exposure e.g. mice don't smoke 
- Differences in gross and microanatomies – not always clear how one organ maps onto the other sometimes  
	- E.g. prostate – don't know how regions within human prostate map to regions within the mouse. But we know that if the prostate becomes hyperplastic in mice, it doesn't affect urethra like in humans as it doesn't wrap around urethra. 
	- E.g. Large vs small intestine – if APC KO'ed in humans, higher rate of colon cancer, but in mice, cancer develops in small intestine instead 
	- E.g. Rb – Rb KO in humans causes retinblastoma, in mice causes pituitary carcinoma 
	- E.g. p53 – KO causes carcinoma in humans, but lymphoma in mice 
- Differences in pharmacokinetics and pharmacodynamics 
- Other differences in biology 
	- E.g. saccharine causes bladder cancer only in male rates as they express an enzyme that converts saccharine to a mitogen 
	- E.g. absestos and smoking do not cause lung cancer in mice, but clearly do in humans 

## Mouse PDXs
### Advantages
- May more accurately capture the whole tumour with its landscape 
- Capture the tumour cell-autonomous variability, heterogeneity and genetic complexity of human cancers 
- Has good predictive value for cancer therapeutics 

### Disadvantages 
- Very expensive 
- Tumours are often put somewhere where they can be easily assayed and measured, usually under the skin and not within the tissue where the tumour was taken from. This means the tumour is in a foreign somatic environment, and is not biologically representative of the native tumour microenvironment and systemic effects 
- Engraftment frequency and growth rate is variable among cancers 
- Many of the tumours used do not propagate within mice, so have to select for cells that can propagate, which biases the experiment -> not representative of patient 
- Recipient mice have to be immunocompromised, so the immune response to the cancer is not representative of a human cancer 
- There are many differences and incompatibilities between mouse and human stromal signalling (i.e. differences in receptor and ligands)
- It takes time for the tumour to grow in the mouse, during which time the patient's cancer would have probably evolved while the tumour sample taken is evolving in a different environment in the mouse. 

## Autochthonous mouse models 
### Advantages 
- Can be used to model tumour microenvironment/systemic effects that in vitro systems cannot 

## Transgenic mice – tissue-specific promoter
### Disadvantages
- Expression in all cells of target tissue, but in cancers, expression is more heterogeneous 
- Promoter is differentiation-state dependent, resulting in artifactual feedback; The transgenic oncogene often causes de-differentiation, which turns off the very promoter that is driving them. When the cell de-differentiates, oncogene expression decreases, and promoter starts again and oncogene is expressed again. This results in intermittent expression/negative feedback. 

## Transgenic mice – gene KOs 
### Disadvantages 
- Adaptive reprogramming may occur during embryogenesis
	- E.g. Rb KO mice can still survive as p107 and p130 can take the role of Rb; KO of all three it not possible as it results in embryonic lethality 
- Total loss of some tumour suppressor genes can be embryonic lethal, e.g. PTEN, so future cancer development cannot be assessed 
- Tumour suppressor is deleted from both tumour and normal tissues, but in real human cancers, the tumour suppressor gene is not deleted from normal tissues (though exception would be cancers caused by genuine germline mutations in humans, e.g. BRCA1/2?)
- Germline heterozygous KOs allow for sporadic loss of remaining functional allele, but there is no control over when or whether this happens ![[Pasted image 20230409125840.png|400]]
## Transgenic mice – GEMMs
### Advantages 
- Used to investigate requirement of a gene for tumour **maintenance** and asses their validity as a therapeutic target 
- Can also be used to assess how gene expression changes in different **contexts** (e.g. in tumour environment, after tumour regresses, before tumour develops) and **over time** (e.g. restoring protein activity in adult, restoring protein activity in a mouse with tumour) 
	- E.g. When p53 was restored in a "naive" adult p53-deficient mice, it resulted in no discernible phenotype from a wt mice 
	- E.g. Restoring p53 in a mouse with glioblastoma eliminated the tumour, suggesting that tumours require continuous absence of p53 
	- E.g. Acute Myc activation induces and maintains KRas<sup>G12D</sup> pancreatic cancer; when Myc turned off, cancer regresses 
- Reversible switchable for ectopic and endogenous oncogene and tumour suppressor gene expression 
- Sporadic initiation of driver oncogenic events (gain and loss of function)
- Rapid execution (with CRISPR technologies)
- Further humanisation of mouse oncogenic processes
- Can allow for non-invasive imaging of tumours and disseminated disease – for use in longitudinal studies (helps to address 3Rs)
	- Intravital imaging 
- Cre KOs can be useful for following cell lineages -> understanding cancer phylogeny, evolution 

# Comparisons 
## Conservation of oncogenes/tumour suppressors 
![[Pasted image 20230409172611.png|500]]

# Links 
- Limitations of mouse models. [[D11 Cancer Stem Cells#Reconciling the evidence]]