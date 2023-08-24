# Questions
- DNA-damaging agents are known to be carcinogenic. Give four examples of these agents, indicating the type of DNA damage they cause and the pathway(s) involved in their repair. What is the rationale behind the use of these agents in cancer therapy?
- ==What are the principal cellular responses to DNA damage? Discuss the potential consequences of their failure.==
- In what ways can the response to DNA damage be viewed as a signal transduction pathway?
- How do telomeres avoid being detected as DNA damage (see [[deLange_2009]]) and what happens when a telomere becomes so short that it can no longer function in this way? (replication senescence – see [[D2 DNA damage repair#Replicative senescence|here]] and [[Senescence#Cell cycle arrest|here]])
- What is cellular senescence and how is it suppressed in stem cells and cancer cells? 
- ==Compare and contrast how germ-line cells, stem cells, and cancer cells avoid replicative senescence.==

# Types of DNA damage
- ~10<sup>6</sup> DNA lesions per human cell per day, with ~37.2x 10<sup>12</sup> cells in our body 
- Unrepaired DNA damage can lead to genomic instability and diseases (e.g. cancer, immune deficiency, infertility, age-related diseases)
- DNA damage can be **spontaneous/endogenous** or **environmentally-induced/exogenous**

## Spontaneous DNA damage
### Base deamination 
- A, G, and C can be deaminated to form unnatural bases, which are removed by DNA glyosylases to produce an apurinic/apyrimidnic (AP) site which is processed by BER
	- E.g. C deaminates to U, which if not removed, can lead to C to T transition, which is the most common mutation. U can be removed by DNA N-glycosylases of UNG family 
		- U can base pair with adenine, which could result in a C-to-T mutational signature if the U is replaced by T to match the adenine. 
- However, deamination of 5-methyl-C at CpG islands generates T, which is not efficiently removed
![[Pasted image 20230404142747.png|400]]
### Oxidative DNA damage
- 1% of oxygen we breathe is converted into oxidative free radicals, which can cause base and sugar-phosphate damage and breakage (abasic sites, single-strand breaks)
- E.g. Guanine can be oxidised to 7,8-dihydro-8-oxoguanine (8-oxoG), which can base pair with adenine (instead of C), and this could lead to a GC to TA transversion ![[Pasted image 20230404142441.png|325]]
- E.g. Oxidation of purines can form 8,5'-cyclopurine-2'-deoxynucleosides, which are bulky and can distort the DNA helix. This can block DNA or RNA polymerase progression 
- ROS attack of sugar ring in DNA can form SSBs 
- ROS can result in lipid peroxidation.  Malondialdehyde can react with DNA bases to generate bulky adducts (e.g. pyrimido[1,2α]purin-10(3H)-one), or promote formation of intra and inter-strand linkage (ICL). This alters structure of DNA and block DNA or RNA polymerase 
- Recognised by PARP enzymes and repaired by BER 

## Endogenous alkylating compounds
- E.g. S-adenosyl-L-methionine, a cofactor for methylating compounds, can methylate bases to form lesions e.g. O<sup>6</sup>-methyl-guanine, which mispairs with T to result in G-->A transitions 

### DNA replication errors 
- Polymerases have small error rates e.g. DNA Pol β has error rate of 1/5000 bp, DNA pol ε, δ error rate on order of 1/10<sup>6</sup> bp 
- Can result in mismatches, which is repaired by mismatch repair enzymes 
	- Mutations in MMR genes can lead to Lynch syndrome 
- Strand slippage errors, particularly in microsatellite sequences, can result in indels 
	- Subsequent round of replication could expand or retract the microsatellites, e.g. Huntington disease 
- Replication through microsatellite sequences or transcription-derived R loops can also cause "replicative stress", where the replication fork collapses, promoting DSB formation 

### Formation of AP sites 
- AP sites due to spontaneous hydrolysis of glycosidic bond between base and sugar 
- Abasic sites are non-coding templates and can block DNA/RNA polymerases 
- Abasic sites can also react with guanine strands on the complementary strand to form a covalent interstrand crosslink 

## External agents that can cause DNA damage
### UV light
- Sunlight has UVA, UVB. Most damage from UVB. 
- DNA base adducts (cyclobutane pyrimidine dimers and 6-4 photoproducts) can cause major helix distortions that impair DNA replication and transcription 
- Repaired by nucleotide excision repair 

### Alkylating agents
- These are electrophilic compounds that can react with electron-rich atoms in biological molecules (e.g. N, O) to form covalent bonds with them 
- Mainly repaired by direct reversal but also by BER 

### DNA cross-linking agents
- These agents attack bases to create intra- and inter-strand crosslinks (ICLs), which block replication and transcription (See [[D1 DNA Replication#^103bbb|Fu & Walter (2011)]]), e.g. cisplatin, oxaliplatin, carboplatin 
	- Cisplatin forms intrastrand diadducts, which stall DNA replication and transcription 
- Some cellular metabolites may also cause DNA ICLs, e.g. acetaldehyde and formaldehyde( #comment elaborate)
- Intra-strand crosslinks repaired by NER
- Inter-strand crosslinks repair by Fanconi anemia pathway and homologous recombination 

### Antimetabolites 
- Anti-metabolites e.g. 5-FU and methotrexate interfere with DNA replication by substituting for natural nucleotides 

### DNA topoisomerase inhibitors 
- Topoisomerases relieve torsion in DNA by nicking the DNA
- Topoisomerase inhibitors stabilise transient cleavable DNA-enzyme complexes to physically block replication and transcription, inducing DNA single and double strand breaks
- E.g. etoposide, doxorubicin 

### Ionising radiation 
- Produces ionises molecules that attacks DNA
- Can cause base damage, DNA protein crosslinks, phosphate backbone damage, SSBs, DSBs
- DSBs repaired by end joining and homologous recombination 

## DSBs
### Physiological DSBs
- DNA sequence rearrangements to create diversity in Ig and TCRs (V(D)J recombination and class-switch recombination)
- Meiotic recombination 
- Telomeres 
- When two SSBs occur near each other or when the DNA-replication apparatus encounters a SSB or certain other lesions, double-strand breaks (DSBs) can form 

### Cytotoxicity
- Highly recombinogenic, e.g. leading to chromosome translocations
- Persistent DSB can signal either permanent cell cycle arrest or trigger apoptosis 

# DNA damage response
## DNA damage signalling
1. Damage sensor 
2. Activation of transducers (kinases)
3. Recruitment of mediators (signal amplification)
4. Activation of mobile effectors (kinases) resulting in signal spreading
5. Modification of substrates
6. Cellular responses

| Response                                      | Purpose                                                             |
| --------------------------------------------- | ------------------------------------------------------------------- |
| Induction of repair mechanisms                | Fix deleterious lesions                                             |
| Cell cycle arrest                             | Allow time for cell to repair damage                                |
| Changes in transcriptional program (e.g. p53) | Reinforce other responses                                           |
| Induction of senescence or apoptosis          | Ensure that cells damaged beyond repair do not endanger other cells | 


## Direct reversal 
### Photolyase-mediated photorepair of UV damage

- Photolyase uses visibile light and fully reduced flavin cofactor FADH- to repair major UV induced lesions in DNA without leaving any damage 

### AGT-mediated repair of alkylated G and T

## Excision of damaged, mispaired, or incorrect bases
### Base excision repair
- Primarily repairs small base lesions arising from oxidation, deamination, or alkylation 
- Damaged base is recognised by a DNA glycosylase that flips the base into its active site and excises it to produce an AP site 
	- Some DNA glycosylases also cleave the DNA backbone at the AP site as well, and in this case an SSB is generated that needs to be processed by SSB repair pathway 
- AP endonuclease recognises damage and cleaves DNA backbone 5' to the AP site, creating a strand break with priming 3' OH group 
- Short-patch (single-nucleotide) or long-patch repair the damage
	- Short-patch replaces only the damaged nucleotide; DNA Polβ fills the gap and excises the remaining 5' abasic fragment. Nick is ligated by XRCC1 
	- Long-patch BER incorporates 2-10 nucleotides in strand displacement synthesis, carried out by POLε or δ with PCNA. Resultant 5' flap removed by endonuclease FEN1, nick sealed by LIG1 
	- Choice between short and long patch is driven by relative BER protein concentrations, cell cycle phase, ATP abundance. 
- Process overlaps with processes in SSB repair 
![[Pasted image 20230125090849.png|425]]
- To repair UV damage, T4 endonuclease V can recognise CPDs and repair lesions in two reactions, 1) glycosylase activity that releases thymine generating the AP site, and 2) AP lyase activity that incises phosphodiester bond, generating an SSB repaired by BER

### Nucleotide excision repair
- NER system recognises helix-distorting base lesions 
![[Pasted image 20230125091435.png|350]]
- Two subpathways: 
	- Transcription-coupled NER targets lesions that blocks RNA polymerase, and is faster (minutes) 
	- Global genome-ER is engaged when there is recognition of a helix-distorting lesion, and takes longer (hours) 
- Pathways differ based on protein complex that recognises the damage 

#### GG-NER 
1. XPC senses damage and forms complex with UV excision repair protein RAD23B 
	1. More subtle distortions are recognised by UV-DDB complex, acting upstream of XPC-RAD23B to enhance identification of these distortions 
	2. UV-DDB also recruits DDB1-cullin 4A to the lesion to ubiquitinate XPC and UV-DDB. This stabilises XPC but degrades UV-DDB, thus increasing XPC affinity for the substrate 
2. XPC-RAD23B required for assembly of downstream NER proteins 
3. TFIIH recruitment
4. DNA is unwound by XPB and XPD 
	1. Damage is verified if XPD is stalled, indicating that there is a. bulky lesion on the target ssDNA 
5. p52 stimulates XPB activity, while p44 stimulates helicase activity of XPD 
6. 5' incision made by XPF-ERCC1 complex 
7. 3' incision by XPG generates 5' phosphate group, and this releases the damage-containing lesion 
8. Gap-filling done by DNA polymerases δ, ε, PCNA, RFC
9. Ligation of nick done by LIG1 or 3α

#### TC-NER 
Arrested RNAPII spans ~35 nucleotides, which prevents NER machinery from accessing damage site 
1. Stalling RNAPII recognised 
2. Cockayne syndrome protein B (CSB) either removes or translocates the RNAP II backwards (not certain which), giving NER machiner access to damage 
	1. If RNAPII cannot be removed, it is ubiquitinylated by NEDD4 E3 ubiquitin ligase then polyQ'ed by Elongin A and Cullin5 
3. CSB recruitment induces organisation of Cockayne syndrome A E3 ubiquitin ligase complex (CRL4) 
4. Subsequent steps, starting from TFIIH recruitment, is same as in GG-NER 

> [!note] Process of NER 
> 1. Damage recognition 
> 2. Damage verification 
> 3. Incision of DNA backbone on either side of damage to excise the lesion 
> 4. Refill the gap 
> 5. Ligate remaining nick  
> ![[Pasted image 20230529155937.png]]

#comment Unify these two diagrams (or find a more complete one?)
- Damage is excised as a 22-30 base oligonucleotide to produce a ssDNA region. Complementary strand is re-synthesised by DNA polymerases and associated factors, before ligation occurs. 
- Defects in NER can cause disease e.g. Xeroderma pigmentosum, Cockayne syndrome

### Mismatch repair
- Mismatch repair can repair mismatched nucleotides or small indels 
- Mispair or indels are recognised by heterodimers of of MutS homolog (MSH) proteins 
	- MutSα and MSH6 recognise base mismatches and indels of 1-2 nucleotides
	- MutSβ recognises larger indels 
- After recognition, the MSH complex is converted into a sliding clamp due to exchange of ADP to ATP in nucleotide binding site
- Camp diffuses along DNA and interacts with MutLα heterodimer 
- Proliferating cell nuclear antigen (PCNA) is helps to recruit MMR machinery, e.g. MSH2, MSH3, MLH1, exonuclease 1, DNA polymerases 
- The damage acted on by nuclease, polymerase and ligases 
	- If there is a 5' nick, 5' to 3' exonuclease activity of EXO1 is used to remove the mispair, creating a single-strand region 
	- 3' directed excision not well understood 
- Meiotic recombination 11 (MRE11), DNA polymerase δ and ε participate in 3' -> 5' exonuclease processing 
- Gaps are filled by POLδ, and DNA ligase 1 seals remaining nick 

> [!image] MMR
>![[Pasted image 20230529154249.png|500]]

## Single strand break repair 
- SSBs can be generated from reactions of DNA with ROS, repair intermediates, or incomplete catalytic activities of DNA binding enzymes, e.g. topoisomerase 1 – generates strand break during replication and transcription to resolve supercoiling 
- PARP1 and XRCC1 
- PARP1 detects SSBs and initiators repair at direct SSBs 
- PARP1 then recruits XRCC1 to SSBs and also assembles repair machinery as it can do DNA-activated poly(ADP-ribose)ylation 
- XRCC1 can also bind SSBs and interacts with SSB repair enzymes 
- SSBs often contain non-conventional termini, e.g. 5' AMP, 3' phosphate, 3' protein adducts, etc., so that ends have to be processed to convert them to 5' phosphate and 3' OH groups for gap filling and nick ligation 
	- E.g. 3' phosphates are processed by PNKP, TOP1-DNA intermediates are processed by tyrosyl-DNA phosphodiesterase 1, and 5' AMP processed by APTX 
- DNA gap filling by polβ and ligation by LIG3α

> [!image] SSB repair pathways 
> ![[Pasted image 20230529161954.png|500]]

## Double strand break repair 
- The type of DSB repair that can occur depends on when in the cell cycle the cell is in 
	- NHEJ can take place throughout the cell cycle 
	- HR can only occur in S or G2 phase of cell cycle as it requires copying from an intact sister chromatid 

### Signalling pathway
![[Pasted image 20230125093150.png|400]]
 - DSBs recruit ATM 
 - Replication protein A (RPA)-coated ssDNA recruit ATR
 - ATM is also important in SSBR, oxidative damage response, cell cycle checkpoints
	 - Mutation in ATM gene can lead to disease e.g. Ataxia-Telangiectasia (A-T)
- ATM/ATR target protein kinases CHK1 and CHK2, which together with ATM/ATR reduce CDK activity. This slows down or arrests cell cycle progression, so the cell has more time to complete DNA repair 
- CHK1 phosphorylates S216 on Cdc25, a phosphatasae that promotes G2 to M transition, causing arrest at G2 
- CHK2 also phosphorylates p53 on S20 to reduce binding affinity of MDM2 to p53, increasing p53 levels 
- ATM/ATR signalling also upregulate DNA repair proteins at the transcriptional, post-transcriptional and post-translational level (e.g. by modulating their phosphorylation, acetylation, ubiquitylation or SUMOylation) 
- If DNA repair is successful, then signalling ends; if DNA damage cannot be repaired, then chronic signalling DNA damage repair signalling triggers apoptosis or senescence  
- Signalling is also influenced by [[D2 DNA damage repair#Short telomeres activate senescence|chromatin structure]]
- NHEJ defects can lead to severe combined immune deficiency (SCID) as diversity generation in Igs is impaired, leading to impaired B- and T-cell development

### NHEJ
- Does not require template and involves direct ligation of broken strands 

#### Classic NHEJ 
- DSBs are recognised by Ku protein, which then recruits the kinase DNA-PKcs, XRCC4, XRCC4-like factor, DNA ligase 4 and APLF 
- DNA-PKcs holds two ends of broken DNA in close proximity to each other 
- XRCC4-XLF stabilises DNA ends by bridging them 
- End-processing of non-ligatable termini (e.g. 5'OH, 3' phosphate) have to be processed by enzymes
- After end processing, gap is filled by Pol μ or λ and nick is sealed by LIG4 ligase

#### Alternative NHEJ 
- There is also a Ku-independent NHEJ pathway known as microhomology-mediated end-joining (MMEJ) which results in sequence deletions 
- A-NHEJ engages MRN complex and CtIP, XRCC1, PARP1, LIG1 or 3 
- MRN complex and CtIP initiate end resection 
- More error prone 

### HDR
- Initiated by ssDNA generation, promoted by various proteins e.g. MRE11-RAD50-NBS1 (MRN complex)
- Error-free 
- ATM recognises DSB 
- 5' end is resectioned by CtBP1 nuclease to create a 3' ss DNA stretch 
- ssDNA protected from degradation by RPA and prevent exchange of genetic information 
- RAD51 recombinase, together with BRCA1/BRCA2 complex, displaces RPA 
- RAD51-ssDNA promotes strand invasion into a homologous duplex to form a heteroduplex DNA 
- D loop is processed so synthesise the correct DNA using the homologous strand as a template 

> [!image] DSB repair pathways
> ![[Pasted image 20230529162033.png|500]]


## Translesion synthesis
DNA damage bypass 
Leads to tolerance to DNA base damage 

# DDRs and Cancer
## DDRs are often impaired in tumorigenesis 
![[Pasted image 20230404143719.png|525]]
## Targeting DDRs for cancer therapy
### Mutational signatures
- A mutational signature is the pattern of mutations produced by a mutational process, defined by DNA damage processes and DNA repair processes
- Mutational signatures are physiological readouts of biological history of a cancer, and can be used to discern ongoing mutational processes from historical mutational processes, thus helping to identify  targets for cancer therapy 

### Synthetic lethality
- Two genes are synthetic lethal if inactivation of either gene is compatible with viability, but inactivation of both genes leads to death 
- Many cancer types have loss-in-function mutations in DNA repair genes which favours uncontrolled growth, BUT it also makes cancer cells highly susceptible to DNA damage, since they aren't able to repair the damage 
- **Combination therapies** that both increase DNA damage and DDR inhibitors can be effective in treating cancer 
![[Pasted image 20230125094257.png|475]]

- E.g. HR-deficient (A) cancer cells (e.g. BRCA-deficient breast cancer cells) are hypersensitive to PARP inhibition (B). Normally, SSBs are detected by PARP1/2 for repair. PARP inhibitors trap PARP on damaged DNA, and such SSBs with trapped PARP are converted to DSBs during replication that require HR for repair. However, HR-deficient cells will fail to repair such lesions and die. 
![[Pasted image 20230125094510.png|325]]

## Summary: DNA damage types and repair responses 

| DNA damage type          | DNA repair                                                                          |
| ------------------------ | ----------------------------------------------------------------------------------- |
| Base deamination         | Base excision repair                                                                |
| Oxidative DNA damage     | Base excision repair                                                                |
| DNA replication errors   | Mismatch repair                                                                     |
| UV damage                | Nucleotide excision repair, direct reversal, base excision repair                   |
| Alkylating agents        | Direct reversal, BER                                                                |
| DNA cross-linking agents | Intra-strand – NER. Inter-strand – Fanconi anemia pathway, homologous recombination |
| Ionising radiation       | NHEJ, HR                                                                            | 

- Double strand nature of DNA very useful for repair! There is a correct template to "refer" to for repair

![[Pasted image 20230529161520.png]]

## Remaining questions about DDR 
- How DDR factors are regulated 
- How DDR affects cellular functions 
- How same DDR stimulus can result in different responses in different cells, tissues? 

# Telomeres
## Function 
### Solution to the end replication problem 
- At the 5' end of the lagging strand, RNA primers are added by primase, from which DNA can be elongated by DNA polymerase to form Okazaki fragments. But when these RNA primers are removed, there is no way to synthesise the lagging strand sequence complementary to the small region at the end of the chromosome. This results in shortening of the chromosome with every cycle of DNA replication 
- This is only a problem for linear chromosomes e.g. in eukaryotes 
- Telomeres act as a buffer against this shortening as they are non-coding 

## Synthesis
- Telomerase reverse transcriptase (TERT) uses an RNA component (TERC) as a template to extend the 3' single stranded G-rich overhang. 
- Polymerase α/primase then initiates fill-in of the C-rich strand 
- ALT – alternative lengthening of telomeres 

![[Pasted image 20230404145942.png|350]]

## Structure
- T-loops are formed by single stranded part of the telomere repeat region invading the double stranded part of the telomere repeat region 
- Shelterin 
	- POT1 binds to single stranded part of telomere
	- Structural domains have been conserved through evolutionary history 
		- Myb domains for dsDNA binding
		- OB-folds for ssDNA binding
	- However, there are differences in composition and architecture between species 
- Shelterin and t-loop structure ensures that telomere is not recognised as DSB by DSB repair machinery 
	- TRF2 represses ATM kinase pathway, NHEJ pathway in G1 and G2 phase, and HDR
	- POT1 represses ATR pathway, NHEJ pathway in G2 phase, and HDR 
	- Ku70/80 also binds to telomeres and represses HDR, but it is also a component of NHEJ 
		- May bind to telomeres by interacting with shelterin 
		- Shelterin blocks Ku70/80 activity? 

![[Pasted image 20230529172118.png]]

![[Pasted image 20230529172304.png]]

## Replicative senescence 
- Senescence refers to a state where the cell is permanently withdrawn from the cell cycle. The cells are still viable and metabolically active, but have altered chromatin structure (senescence-associated heterochromatic foci `[`SAHFs`]`), and senescence-associated secretory phenotype (SASP)
	- This is in contrast to quiescence, which is reversible cell cycle arrest 
- Senescence is a barrier to uncontrolled proliferation 
- The length of the telomere sets a limit for the cell life cycle – a biological "clock" for the cell. When telomeres become too short, cells enter senescence 

### Changes in telomere length over the cell cycle 
![[Pasted image 20230404150419.png|525]]


### Short telomeres activate senescence 
- Loss of shelterin (TRF2, POT1) leads to telomere deprotection, in turn leading to DDR factor recruitment (see below)
	- #experimental_evidence Lange and coworkers – Introduced dominant-negative mutation of TRF2, a component of shelterin complex. This uncaps the telomere. It resulted in aberrant chromosome fusions that were visualised under a microscope. 
![[Pasted image 20230127100635.png|400]]
- Short telomeres activate senescence by being **recognised as DSBs by DDR proteins**
	- #question Why are telomeres recognised as DSBs – does not resemble DSBs? 
		  ![[Pasted image 20230404151046.png|425]] 
	- **MRN -> ATM -> γH2AX -> MDC1 cycle**. MRE11-RAD50-NBS1 (MRN) complex recognises DSB break regions. MRN complex then recruits ATM, which phosphorylates S139 on H2AX to form γH2AX. γH2AX recruits MDC1, which then recruits MRN complex, recruiting ATM which in turn recruits more MDC1. Thus γH2AX facilitates the spread of signals of DNA damage along chromatin. 
	  ![[Pasted image 20230404150734.png|550]]
		- #experimental_evidence Meier et al (2007) – Used "ChIP on chip" (=ChIP + microarrays to identify pulled down DNA) to show that γH2AX is concentrated at sub-telomeric regions in senescent cells 
		- #experimental_evidence d'Add di Fagagna et al (2003) – Fluorescent imaging of senescent human fibroblasts show that γH2AX foci are prevalent in senescent human fibroblasts 
		- #experimental_evidence MDC1, MRN complex, and γH2AX co-localise in senescent human cells 
		- #experimental_evidence DDR proteins congregate at sites of DSBs, and this requires γH2AX
	- H2AX can also be phosphorylated by other PIKKs (ATM, ATR, and DNA-PK) to form γH2AX. 
		- Different PIKKs are activated in different response pathways 
- Downstream kinases CHk1 and CHK2 are activated in senescent human cells 
	- #experimental_evidence d'Add di Fagagna et al (2003) – (see slides 28-29). When checkpoints were impaired in senescent cells by siRNA KO of CHK1 and CHK2, DNA synthesis resumed. 
- These DNA damage foci and other markers are persist in senescent cells for months or even years after a cell has senesced 

# Telomere DNA is difficult to replicate 
- The structure of telomeres promotes chromosomal stability, but their structural features also makes it challenging for the telomere DNA to be replicated during DNA replication (i.e., replication stress)

## Reasons for replication stress
- Tightly bound shelterin complex 
- G-rich regions (such as in telomeres) are prone to forming secondary structures, e.g. G-quadruplex 
- T-loop super structures 
- R loops – RNA:DNA hybrids arising from transcription of telomere repeat containing RNA (TERRA)
- Telomere attachment to the nuclear envelope 

## Resolving telomere replication stress
- Sources of replication stress have to be overcome by a host of proteins
- E.g. multiple helicases (RTEL1, RECQL4, etc.) are involved in resolving G-quadruplex structures to allow for replication 
- Many of these proteins are recruited by shelterin components, DNA replication machinery, telomerase or ssDNA 

## Other types of senescence 
- Programmed senescence
	- Occurs in normal embryonic development e.g. formation of fingers in humans 
	- Part of tissue remodelling processes
	- p21-dependent but DDR-independent 
- Non-telomeric stress-induced premature senescence (e.g. oncogene-induced, unresolved DNA damage-induced, epigenetically-induced, mitochondrial dysfunction-associated, therapy-induced)
	- See [[D3 Oncogenes and Tumour Suppressors#Oncogene-induced senescence|Oncogene-induced senescence]]

# DNA damage and cancer 
- Genome instability is fundamental to cancer
- Break/fusion cycles can cause massive genomic instability – as telomeres erode, they may get stuck together -> chromosome fusion -> improper chromosome segregation -> breakage of chromosome -> fusion of chromosomes

![[Pasted image 20230409123616.png|525]]

- Cancer cells often have upregulates telomerase 
- Some cancer cells also maintain telomere length via HR-based alternative lengthening of telomeres 
	- Sequestration of telomeres into SHelterin prevents them from engaging NHEJ-mediated fusions or activating ATM/ATR signalling 
- Mismatch repair defects can cause microsatellite instability -> risk factor for colorectal, endometrial cancer 
- Defects in DNA repair contribute to "mutator phenotype" of cancer cells
	- Defects in DNA repair are needed to avoid DDR signalling to activate apoptosis or senescence 
- Some inherited mutations in BER have been linked to cancer, e.g. UNG, MUTYH, NTHL1, POLε

## DDR pathways and cancer treatment
- Traditional cancer treatments of radiotherapy and chemotherapy function by generating DNA damage. Since cancer cells are often deficient in DNA repair, this makes them more susceptible to DNA damage 
- However, tumours can acquire resistance to these therapies by evolving improved DDR
	- E.g. glioma stem cells are resistant to radiotherapy because they have enhanced DDR 
- Drugs that inhibit DDR could enhance the effect of radio- and chemotherapy 
- DDR inhibitors could also be given to block apoptotic events in normal tissues, thus reducing off-tumour toxicity (e.g. inhibitors of CHK2?)
- In general, reduced DDR factors correlates positively with therapeutic outcomes, except for those factors also involved in promoting apoptosis, e.g. p53
- Could be exploited in synthetic lethality treatments 
	- E.g. PARP binds SSBs and base excision repair intermediates. PARP inhibitors are particularly toxic to HR-deficient cells, e.g. those impaired in BRCA1 or 2. This is due to accumulation of SSBs that then convert into DSBs during DNA replication, but the DSBs cannot be repaired due to HR-deficiency 
	- E.g. CHK1 inhibition sensitises p53-deficient cells to DNA-damaging agents more than p53-proficient cells 

# DDR deficiency and disease 
See [[TiwariWilson_2019]]