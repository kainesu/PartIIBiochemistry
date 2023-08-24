# Questions 
- Explain how the non-malignant cells of the tumour microenvironment are important in the tumour's response to treatment.
- *==Discuss whether cancers are aberrant tissues rather than aberrant cells. / Tumours are more like aberrant organs than balls of cancer cells. Discuss.==* 
- ==Describe the principal cell types found in microenvironments of tumours and their proposed roles==.
- *==What is the best cancer target and why: the tumour cells or their microenvironment?==*
- Discuss the features of the tumour microenvironment, with focus on the immunosuppressive properties. 

# What causes cancer? 
- Driver mutations in the site/cell of origin 
- Or... tumour microenvironment? 

# Oncogenes can instruct the tumour microenvironment 
## Myc 
#experimental_evidence [[SodirEtAl_2020]] – identified signals from Myc in Myc-driven pancreatic adenocarcinoma (PDAC) in mice, activating MycER<sup>T2</sup> with tamoxifen then harvesting pancreata. Tissue extracts were interrogated with growth factor/cytokine arrays.

| Signal                                     | Effect                                           |
| ------------------------------------------ | ------------------------------------------------ |
| SHH                                        | PDAC desmoplastic deposition and maintenance     |
| CCL9                                       | Macrophage chemoattractant -> influx into tumour |
| CXCL5                                      | Ly-6B+ neutrophil influx, CXCR2 receptor ligand  |
| GAS6                                       | AXL kinase ligand                                |
| PD-L1 expression on PanIN epithelial cells | T-cell expulsion from tumour                     | 
- Inhibition of AXL kinase inhibits neutrophil influx into tumours and B-cell influx into tumour peripheries 
- T-cell expulsion from tumour prevented by blockade of PD-L1 

#experimental_evidence In lung adenocarcinomas: 

| Signal                                  | Effect           |
| --------------------------------------- | ---------------- |
| Macrophage-specific expression of PD-L1 | T-cell expulsion | 


# Cancer response to the immune system 
- Hot vs cold tumours
	- Cold = tumour with absent or excluded T cells and low pro-inflammatory cytokines
	- Hot = tumour infiltrated by T cells with inflammation signature
- Immune system can recognise cancer cells due to the presentation of tumour-associated oligopeptide antigens on MHC I (HLA) molecules 
- Often, immune cells can be either protumorigenic and antitumorigenic, forming a tumor-killing or immune suppressive microenvironment. Their action depends on ... #question? 

## Immune system overview 
![[Pasted image 20230526162402.png]]

## Immune evasion 
- Immune escape – cancer cells can evade immune detection by suppressing cell-surface display of tumor antigens 

### Strategies 
![[Pasted image 20230526163551.png]]

- Repress expression of MHC class I proteins 
	- However, loss of MHC I can provoke attack from NK cells, so some tumours may only lose one of 6 key MHC class I molecules to evade attack by NK cells 
- E.g. structural variants affects CD274 (PD-L1) genes in specific types of lymphoma, inducing the stability of PD-L1 and associated with immune escape of cancer cell 

### Which strategy would a cancer employ? 
- Tumours that have a high frequency of somatic mutations tend to have greater presentation of neoantigens (e.g. melanomas, NSCLC). These are more likely to evolve ways to create an immunosuppressive environment that prevents targeting of neoantigens 
- On the other hand, tumours with low neoantigen-presenting levels (e.g. B-ALL) or do not present antigens because of downregulated antigen processing, presentation, or HLA expression are less likely to have selective pressure to evolve an immunosuppressive environment 
- This has implications for [[D14.3 Immune therapies#Considerations for choice of immunotherapy|immunotherapy]] 

## Good and bad players in the immune system 
- Tumour microenvironment contains immune cells with pro-and anti-tumour properties  
- Good players: [[D13 Tumour microenvironment#CD8 cells|CD8+ T cells]], [[D13 Tumour microenvironment#CD4 helper cells|CD4+ T cells]], [[D13 Tumour microenvironment#Natural killer cells| NK cells]], [[D13 Tumour microenvironment#Neutrophils|N2]]
- Bad players: [[D13 Tumour microenvironment#Tregs|Tregs]], [[D13 Tumour microenvironment#Myeloid-derived suppressor cells (MDSCs)|MDSCs]], [[D13 Tumour microenvironment#Macrophages|Tumour-associated macrophages]], [[D13 Tumour microenvironment#Neutrophils|N1]]

## T cells
doi:10.106/j.immuni.2013.07.012
![[Pasted image 20230411234534.png]]
- As tumour cells die, they release antigens that are presented by dendritic cells in the lymph node to T cells. T cells are then stimulated, expand, extravasate into the tumour, and kill cancer cells 
- Effector and memory cells needed for sustained tumour cell killing
	- Effector cells recognise the initial tumour 
	- Persistent memory response can guard against the evolution of therapy-resistant malignant cancer clones ![[Pasted image 20230411235536.png]]

### CD4 helper cells

> [!image] Presentation of oligopeptide antigen on MHC I, activating cytotoxic T cells (CD8+) to kill it
> ![[Pasted image 20230526160226.png]]
> Here a dendritic cell can present both MHC I and MHC II in what is called "cross presentation" to induce cytotoxic T cell precursors to mature into active cytotoxic T cells. However, all other cells in the body also have MHC I which allows cytotoxic T cell to recognise it as a target
> ![[Pasted image 20230526160407.png]]

### Tregs
- T cell regulatory cells 
- Inhibit T cell activation 
![[Pasted image 20230526170916.png|500]]
doi.org/10.3389/fimmu.2021.750542

### CD8 cells 
- Associated with good prognosis as they can block tumour progression 
- They recognise antigens presented as small peptides in the groove of surface human leukocyte antigens (HLAs) (basically the human MHC). Such antigens can be
	- Normal, non-mutated proteins that are lineage specific
	- Non-mutated shared antigens that are overexpressed in cancer
	- Mutated antigens with unique epitopes 
- Kill via the release of perforin and granzymes or via Fas-ligand-mediated apoptosis or TNF/IFNγ or TRAIL 
- Migrate due to Cxcr3-Cxcl9/10 (DCs/tumour cells) and tumour-derived CCL5

> [!image] Cytotoxic T cells using extrinsic apoptosis pathway to kill cells
![[Pasted image 20230526160650.png]]

### T cell regulation 
#### T cell activation 
- **Two-signal model** – activation of naive T cells requires **T cell receptor** (TCR) signalling (which confers specificity) AND **co-stimulatory signalling**
- TCR recognises an antigen presented by an APC MHC 
- **Tidal model.** Cell-surface interactions and subsequent intracellular signalling vary in response to environmental conditions. 
	- Initially when T cells are activated, co-stimulatory receptors on naive and activated T cells stimulate T cell activity 
	- At the peak of the tide, both co-stimulatory and co-inhibitory molecules are expressed, and the subsequent fate of the T-cell depends on external signals
	- At the end of the tide, co-inhibitory receptors are expressed to suppress T cell activities 

![[Pasted image 20230412170231.png|125]]

**Co-stimulatory interactions**
- CD28 is a costimulatory receptor that is constitutively expressed on naive helper (CD4) and cytotoxic (CD8) cells 
	- B7-1 and B7-2 are ligands for CD28 that are presented by APCs

> [!image]- T cell co-stimulatory and co-inhibitory interactions with APCs
> ![[Pasted image 20230526170850.png]]

#### T cell inhibition 
**Co-inhibition by APCs**
- Co-inhibitory receptors can negatively modulate TCR signalling 
- CTLA4 is a coinhibitory receptor 
	- Binds to both B7-1 and B7-2, which in turn induce IDO to activate Treg activation 
	- CTLA4 is induced after T cell activation to suppress T cell response 
	- When CTLA4 is upregulated, CD28 is downregulated by endocytosis, preventing further activation 
	- CTLA4 can also mediate downregulation of B7-1 and B7-2 by trans-endocytosis from the APC 
- Inhibition helps to prevent autoimmune response 
- Both co-inhibitory and co-stimulatory receptors can bind to the same ligand, resulting in competition ![[Pasted image 20230526170634.png|500]]

**By Tregs**
- Tregs block the action of cytotoxic T cells against cells that present normal antigens on MHC I 
- Tregs are CD4+ CD25+ while T helper are CD4+ CD25- 
- In lymph nodes, Tregs prevent activation of T helper cells by denderitic cells 
- Tregs release TGF-beta and IL-10 to suppress proliferation of other T lymphocyte types 

#### T cell exhaustion 
- T cells chronically exposed to an antigen (e.g. chronic viral infection, tumour microenvironment) develop an altered phenotype where they have reduced ability to proliferate, reduced effector function, and upregulation of co-inhibitory molecules 
	- Co-inhibitory receptors include PD1, CTLA4
- These T cells are less responsive to stimuli 
- Both helper (CD4) and cytotoxic (CD8) cells can exhibit T cell exhaustion
- Blocking co-inhibitory interactions is known to reduce CD8+ T-cell exhaustion, particularly the B7-H1-PD1 pathway, restoring its effector function 
	- However, blocking multiple co-inhibitors has synergistic effect
- Co-stimulatory signals can also rescue T cell exhaustion 
	- E.g. an agonist mAb specific for 4-1BB together with Il-7 can restore activity of exhausted CD8+ T cells in a model of chronic infection with lymphocytic choriomeningitis virus 

## Natural killer cells
- NK cells respond to virally infected and/or transformed cells by cell killing and production of pro-inflammatory cytokines
- NKs form immunological synapses and secrete granzymes and perforin, but can also kill by apoptotic mechanisms (e.g. Fas ligand and TRAIL)
- "Missing-self" response – NK cells can identify and respond to cancer cells that have downregulated MHC-I molecules to evade detection by CD8s 
- Balance of immunoreceptor tyrosine-based activation motifs (ITAMs vs ITIMs)

![[Pasted image 20230412172944.png|275]]

## Macrophages
- M1 type macrophages involved in wound healing and inflammation
	- Phagocytosis
	- Produce inflammatory cytokines
	- Activate anti-microbial response 
- M2 type are involved in dampening inflammation to ensure efficient repair. This is a problem for the anti-tumour response 
	- Lymphocyte suppression 
	- Tissue rebuilding, repair, remodelling 

doi.org/10.3389/fimmu.2020.01731

## Neutrophils
- N1 (anti-tumour): Phagocytosis, NETs release, inflammatory cytokines, toxin and ROS, respiratory burst, promotion of tumour cell apoptosis (TNFα, I-CAM1, FAS, ROS)
- N2 (pro-tumour): Support angiogenesis, suppress CD8 and NK cells, promoter cancer cell migration and invasion, immune surveillance and metastasis, secrete chemokines, cytokines, ROS/RNS

doi.org/10.1038/nrc.2016.52

## Myeloid-derived suppressor cells (MDSCs)
- Are inhibitory immune cells that produce large amounts of IL-10 
- Inhibit cytotoxic CD8+ and helper CD4+ activation
- Polarise TAMs to a tumour-promoting phenotype
- Induce Treg development

## Dendritic cells 
- Prime effector CD4 (helper) or CD8 (cytotoxic) cells by antigen presentation 
- Recruitment of (CXCR3+) CD8 cells by expressing CXCL9+10 
- In TME, can become dysfunctional and even promote tumour progression 

> [!image] Dendritic cell activates a Helper T (CD4+) cell
> ![[Pasted image 20230526155652.png]]


## B cells
- Protumorigenic actions
	- Inhibit cytotoxic T cells
	- Immune tolerance
	- Proinflammatory cytokines
- Antitumorigenic actions
	- Produce tumour-specific antibodies
	- T-cell priming and activation
	- Cytolytic activity

## Tertiary lymphoid structures
- Consist of T cell-rich areas containing dendritic cells and B cell-rich areas with germinal centers (GCs)
- Good prognosis in most cancers, but in breast cancer, dendritic cells not functional, so despite presence of TLS, can't evoke immune response. 

# Other components of the tumour microenvironment
- Cancers are 'organs' to which other cells are recruited and can be corrupted by transformed cells
- TME comprises of stromal cells, immune cells that interact with cancer cells

## Endothelial cells mediate angiogenesis
- Angiogenesis = generation of new vessels from a pre-existing network 
- Angiogenesis is driven by hypoxia in cancer cells that are more than 70-150 μm away from blood vessels
	- #question Why is this distance important? Point at which O2 diffusion becomes too slow? 
- Driven by VEGFA secretion, driven by tumour cells and TAMs
	- #experimental_evidence Schors et al (2006) Myc activation in pancreatic β cells induces secretion of interleukin 1β, which in turn triggers release of VEGF from islet ECM. VEGF then induces endothelial cells to proliferate 
- Tumour-associated blood vessels have excessive branching, defective pericyte coverage, poor functionality. 
	- Pericytes are perivascular stromal cells that provide structural support for blood vessels
	- Are mesenchymal cells 
	- Pericytes are lost when vessels are remodelled, leading to characteristic "vessel leakiness"
	- Low pericyte coverage correlates with poor prognosis as leaky vessels allow cancer cells to more easily metastasise. 
- Normalising angiogenesis would be ideal. 
	- Ablate all blood vessels -> hypoxic environment -> more aggressive tumour. Also more difficult to deliver therapeutic agents 
	- Too much angiogensis -> tumour can grow, metastasise 

## Sympathetic fibres
- Secrete noradrenaline locally and adrenaline through the adrenals and circulation
- Stimulate myelopoiesis in BM and spleen, lymphocyte differentiation in spleen and LN, monocyte/macrophage recruitment
- Pro-inflammatory cytokines secreted by sympathetic fibres can promote tumour growth.

## Adipocytes
- Excess adipose tissue can become inflammed and fibrotic, which changes its secretome to become pro-tumorigenic 
- IGF and insulin promote cancer growth, often through PI3K pathway converting cells to Warburg-type metabolism
	- Warburg effect = cancers relying on aerobic glycolysis due to hypoxia. Also occurs in proliferative tissue!
- *Cachexia* is characterised by systemic inflammation, atrophy of adipose tissue, and skeletal muscle wasting.

## Cancer-associated fibroblasts remodel the tumour ECM 
- Can be of mesenchymal origin, but also from tissue-resident local fibroblasts and adipocytes
- Normal fibroblasts become cancer-associated fibroblasts after activation by DNA damage, ROS, ECM, Notch/Ephrins, inflammatory signals, etc. 
- ==Deposit and remodel ECM== to increase tissue stiffness, thus promoting metastasis 
	- #question How does increasing tissue stiffness promote metastasis 
- CAFs are main source of TGFβ and also produce IL-6 and Cxcl9 to ==suppress the immune system==

## Lymphatic vessels
- Can facilitate metastasis by transporting tumour cells and pre-condition distant lymph nodes for tumour cell seeding (CXCL12)
	- Tumours drain into whichever lymph node is closest
- Immunosuppression: IFNγ-dependent production of PD-L1 inducible nitric oxide synthase, indoleamine 2,3-dioxygenase (IDO) and transforming growth factor-β (TGFβ)
- Immune response: Dendritic cells from the tumour present antigens and activate cytotoxic T cells in the lymph node, which is important for tumour immune response and immune therapies! 

## Platelets
- Cancer cells can recruit platelets 

## Tumour innervation 

# Tissue-specificity of tumour microenvironment 
- The tumour microenvironment can differ between cancers depending on their tissue of origin, in terms of the **phenotypes** and **signals** involved in instructing the environment 
	- #experimental_evidence Evan and colleagues found that Myc-driven influx of granulocytic and B lymphoid cells into pancreatic tumours, while in lung tumours the B cells are expelled. This is because in the lungs, IL23 expression is induced which excludes B cells, but it is not expressed in the pancreas. In contrast, the GAS6-pAXL pathway is activated in the pancreas to recruit neutrophil/granulocyte and B cells, but this is absent in the lungs 
- Even if tissues have a common pathway activated, the **mechanism of activation** can be different between the tissues 
	- #experimental_evidence Evan and colleagues found that in both pancreatic and lung tumours, Myc-driven PD-L1 expression can exclude CD3+ T cells. However in the pcnreas, PD-L1 is expressed cell-autonomously in Myc-expressing PanIN epithelial cells. In contrast, in the lungs PD-L1 is not expressed in the tumour cells themselves but is instead imported from recruited alveolar macrophages i


