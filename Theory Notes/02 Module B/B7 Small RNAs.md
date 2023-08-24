# Questions 
- ==Discuss how structural biology has contributed to an understanding of the RNAi pathway.==
- Mechanisms of small RNAs
	- *==siRNAs and miRNAs specifically downregulate gene expression. Describe the mechanisms by which this is achieved.==*
	- The active small RNA species that participate in the RNAi and miRNA pathways are indistinguishable. What determines the mechanisms by which they act on mRNA targets?
	- miRNAs give rise to both translational repression and mRNA decay. Discuss.
	- siRNAs and miRNAs are key players in pathways that result in post-transcriptional down-regulation of gene expression. While these small RNAs share many similarities, their actions are distinct. Discuss.
	- What is the evidence that miRNAs target an early step in translation?
- Biogenesis of small RNAs
	- What are the molecular determinants that contribute to the precision of microRNA biogenesis and function?
	- How does the biogenesis of miRNAs differ from that of siRNAs?
 
# Functions of siRNA and miRNA 
## siRNA cause RNA interference (RNAi)
- The phenomenon by which long dsRNA causes the specific silencing of the cognate gene either via mRNA degradation 
- Such long dsRNA could come from cellular genes (e.g. transposons), transgenes, or viruses 

## miRNA cause translational repression and decay 
- ==Mechanism is distinct from RNAi==
- Bind to the 3' UTR of target mRNA 
	- In animals, miRNA binding has ==imperfect complementarity==  and is ==combinatorial==, with several miRNAs binding to a single mRNA. Multiple miRNAs that bind to the same target can act cooperatively, reducing translation synergistically. Combinatorial effect allows for specific genes to be downregulated despite off-target binding of miRNA, as a transcript targeted by a set of miRNA will have greater binding than each miRNA's off-targets. This also prevents off-target effects. 
	- In plants, miRNAs bind with ==perfect complementarity== and is **not** combinatorial 

# Structure of siRNAs and miRNAs 
![[Pasted image 20230207213536.png|375]]
![[Pasted image 20230207213838.png|375]]

| siRNA                                                  | miRNA                                                                                                                                              |
| ------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| Double-stranded                                        | Pre-miRNA is double-stranded, with bulges, mismatches, GU pairs                                                                                    |
| 2 nt overhang at 3' ends                               | Pre-miRNA has one 2 nt overhang at 3' end                                                                                                          |
| No hairpin structure                                   | Hairpin structure in pre-miRNA                                                                                                                     |
| Active siRNAs are single stranded                      | Mature miRNA is single-stranded and can correspond to either "side" of pre-miRNA (or both), i.e. miRNA is generated from both halves of the duplex |
| Generated from long dsRNA                              | Generated from bulged, mismatched hairpin pre-miRNA                                                                                                |
| Comes from exogenous dsRNA but is sometimes endogenous | Genomically encoded (endogenous)                                                                                                                   |

Since the active species of siRNA and miRNA are essentially equivalent, they are defined by their **origin**

# Biogenesis of siRNAs and mRNAs
## Transcription 
- In animals, both siRNAs and miRNAs are transcribed by RNA Pol II 
- In plants, additional RNA Pol IV and V are specifically used to transcribe siRNA 

## RNAse III enzymes generate small RNAs
- RNAse III enzymes are inolved in the generation of small RNAs, and are grouped into classes 1-3, with only classes 2 and 3 involved in small RNA production 
![[Pasted image 20230413145315.png|500]]
- ==Class 1== RNases contain only one RNase III domain. 
	- A model based on the crystal structure of RNase III from *Aquifex aeolicus* and mutagenesis studies in *E. coli* suggest that it acts as a homodimer to create two catalytic centers, with each center containing two clusters of acidic residues that coordinates a metal ion (Mg<sup>2+</sup>, Mn<sup>2+</sup>). This allows the RNase to cut RNA twice to give 9 bp products with 2 nt 3' overhangs 
	- It cuts RNA twice to give 9 bp products with 2 nt 3' overhangs 
- ==Class 2== has two carboxyl RNAse III motifs and a dsRBD, e.g. *Drosophila* Drosha 
- ==Class 3== RNases have 2 RNase domains. These include *Drosophila* Dicer1 (miRNA), *Drosophila* Dicer2 (siRNA), and human Dicer (both miRNA and siRNA) ^bbb01c

## Sources of dsRNA
- Exogenous dsRNAs
- Inverted repeat transgenes
- Viral infection
- Aberrant transcription 
- Introns ("miRtrons") – before or after excision, can be substrates for Microprocessor or Dicer  

## siRNA biogenesis 
 ![[Pasted image 20230207214103.png|225]]
1. long dsRNA processed by Dicer into siRNA 
	1. #experimental_evidence Elbashir et al (2001) – When radiolabelled dsRNA was incubated in a *Drosophila* lysate, small RNAs were generated that were identified from a denaturing gel visualised via autoradiography. Over time, increased generation of these small RNA products were observed, while the full length gradually disappeared. 
	2. Endogenous siRNAs are derived from transposon transcripts, sense-antisense transcript pairs, long stem-loop structures
	3. Exogenous siRNAs are derived from transfected long dsRNAs, siRNA duplexes, or viral RNA 
	4. In plants and worms, RNA-dependent RNA polymerases (RdRPs) are present for generation of endo-siRNAs 
2. Loading onto Argonaute protein by Dicer + Argonaute + dsRBP (RISC loading complex)
3. Strand selection by Argonaute 

### Dicer 
- **Dicer** cleaves long dsRNA into siRNAs: [[B7 Small RNAs#^bbb01c|RNAse III class 3]]
- Contains helicase domain and two RNAse III domains 
- Associates with R2D2 (*Drosophila*) or TRBP (humans) for stability,  siRNA binding specificity, and siRNA transfer to RISC 
- Drosha determines one end of miRNAs while Dicer determines the other; for siRNA, Dicer cuts both ends 
- Compared to the canonical Class I RNAses, Dicer has a mutation in RIIIb such that it does not cleave RNA at that point, so it forms longer small RNA products of ~20bp instead of ~9bp 
	- Human Dicer functions as an **intramolecular dimer** of RIIIa and RIIIb domains, which is assisted by two RNA binding domains, dsRBD and PAZ. 
		- **PAZ** is likely to be involved in **recognition of 3' overhang end** 
			- #structural_evidence XRC of human Argonaute PAZ domain bound to 2-nt overhang on 3' terminus 
		- PAZ and RNase III domain work together to act as a molecular ruler 
			- #experimental_evidence [[ZhangEtAl_2004]] used mutation analysis of Dicer and studied the effect of the mutations on dsRNA and hairpin processing. They proposed that the long RIIIa domain may be involved in measuring distance from the substrate terminus to the cleavage site, ensuring that cleavage always occurs at a set distance from the terminus 
			- #structural_evidence In XRC of *G. intestinalis* Dicer, PAZ domain was found to be 65Å away from the catalytic centre, which is the same as the length spanned by ~25 bp of dsRNA. This is the length of dsRNA produced by *G. intestinalis* Dicer. 
			- #structural_evidence In human Dicer, cryo-EM showed that the RNAse III nuclease core is reooriented with respect to the PZ domain, probably to produce shorter dsRNAs 
	- There is only one dsRNA processing center, containing two catalytic sites that generate products with ==2 nt 3' overhangs== and a phosphate-bearing 5' terminus 

![[Pasted image 20230207223703.png|425]]
Model for Dicer cleavage proposed by Zhang et al (2004)
- Dicer-2 of *Drosophila* processes siRNA precursors, while Dicer-1 processes pre-miRNAs 
	- Helicase in Dicer-2 consumes ATP to translocate enzyme along a long dsRNA, allowing for processive generation of many siRNAs from 1 long dsRNA source 
- In humans, the same Dicer is used to produce siRNA and miRNA, but Dicer has a preference for pre-miRNA over pre-siRNA 
	- #structural_evidence [[TaylorEtAl_2013]] used cryo-EM to understand the structural reason for this substrate preference. They found that Dicer has different recognition modes for each type of substrate. The N-terminal helicase domain discriminates between the two types of dsRNAs. Pre-siRNA is held between the helicase and PAZ domains, away from the enzyme catalytic core, while pre-miRNA is held near the catalytic core. However, if Dicer binds to TRBP, it allows pre-siRNA to also bind in a productive conformation 

### Dicer-interacting dsRBPs 
Perform similar roles, including 
- Stabilising Dicer 
- Binding small RNAs  
- Loading small RNAs  

#structural_evidence RNA-bound structures of different dsRBPs (e.g. TRBP) show that RNA recognition is shape-based, and not sequence-specific. The A-form helical geomtry of the dsRNA is recognised at three points, two regions of minor groove surrounding a major groove on 1 face of the helix. 

**Drosophila – R2D2**
- #experimental_evidence R2D2 co-fractionates with Dicer-2 
- #experimental_evidence R2D2 mutant flies are defective for RNAi 
- Binds to Dicer-2 for processing exogenous siRNAs 
- **Structure**. R2D2 has 2 dsRNA binding domains (dsRBD). 
- **Stabilises Dicer-2**, thus promoting siRNA production 
- **Dcr-2/R2D2 complex binds siRNAs but not dsRNAs**, and this activity is dependent on R2D2 as Dcr-2 alone does not bind siRNAs 
- **Associates with Argonaute2 (Ago2 in RISC)** to facilitate siRNA transfer from Dicer to RISC

**Drosophila – Loquacious**
- Binds Dicer-1 to process pre-miRNAs 
- For endogenous siRNAs, especially ones derived from long stem-loops, Dicer2 relies on Loquacious rather than R2D2 
- Not known how Loquacious selects Dicer2 over Dicer1 

**Humans – TRBP**
- #experimental_evidence TRBP KO impairs silencing of luciferase mRNA via siRNA 
- **Structure**. Has 3 dsRBDs 
- **Stabilises Dicer**
- **Dicer+TRBP complex binds siRNAs but not dsRNAs**, and this activity is TRBP-dependent 
- **Dicer-TRBP-siRNA associates with Ago2**, so TRBP may be RISC loading 

***Arabidopsis* – DRB1-5**
- DRB4 interacts with Dicer with DCL4
- DRB1 interacts with Dicer with DCL1 
- DRB2, 3, and 5 are somewhat redundant, while DCL2 and 3 function without a dsRBP partner 

### RISC loading
**Authentication**
Small RNAs must have the following characteristics for loading 
- 5' phosphate and 3' dinucleotide overhang – [[B7 Small RNAs#Structural basis of siRNA guide 5' terminus recognition by Argonaute]]
- Specific length – if too long or too short, it won't be incorporated 
- siRNA must be double-stranded 

**Process for siRNAs**
- In humans, loading of Ago2 minimally requires Dicer complexed with TRBP with a mature siRNA duplex
- #structural_evidence Cryo-EM structure of this RISC loading complex show that TRBP interacts with the helicase domain of Dicer, and Ago2 spans TRBP and the long arm of Dicer, forming a closed complex. When a 22-nt siRNA was modeled along the RNA-binding face of Dicer in this complex, it appeared to fit within the gap between Ago2 and Dicer. It could also be fitted between the PAZ domains of Ago2 and Dicer. 
- #experimental_evidence Tahbaz et al (2004) – Previous biochemical evidence suggested that Ago2 PIWI domain interacts with Dicer RNase IIIa domain 

**Process for miRNA**
- Human RISC loading complex = Dicer, TRBP/PACT and Argonaute
- Fly RLC = Dicer1, Loquacious, Ago1 

### Small RNA sorting to different Agos
What determines which Argonaute protein the small RNA is loaded on? 
- In flies, miRNA duplexes with central mismatches are sorted into Ago1 
	- In humans, all 4 Ago proteins AGO1-4 bind to miRNAs and only have few differences in the miRNA each can bind; so they may be redundant 
- In flies, perfectly matching siRNA duplexes are sorted into Ago2 
	- Dicer2-R2D2 favours siRNA duplex for loading onto Ago2

### Selection of guide strand 
![[Pasted image 20230415222224.png|475]]
- Only 1 strand in the siRNA/miRNA dsRNA is chosen as the guide strand/miR. The other strand is destroyed
- The strand with the **least stable 5' end** will be the strand **most likely to be incorporated into the RISC** ![[Pasted image 20230415222348.png|475]]
	- Experimentally, one can design an asymmetric siRNA where the 5' end of one strand is much less stable than the other, and so is more likely to become the guide strand, e.g. by having a mismatched base 
	- If ends have similar stability, either one could be incorporated 
- In *Drosophila*, this siRNA asymmetry is detected by Dicer-2/R2D2 ![[Pasted image 20230415222516.png|425]]
	- Dcr-2 binds to the least stable 5' end, while R2D2 binds to the most stable 5' end 
- Destruction of passenger strand is mediated by Ago2 in RISC. Passenger strand is cleaved between nt 9 and 10 when counting downstream from 5' end. C3PO endonuclease then removes the cleavage products. ![[Pasted image 20230415224900.png|425]]
- For the non-catalytic Ago1 that binds miRNA, it unwinds the miRNA 
- A "bypass" mechanism exists where if passenger strand cleavage is absent (e.g. for non-catalytic Argonautes), single stranded siRNA can still be generated in RISC 
	- #experimental_evidence Created a non-cleavable passenger strand with phosphorothioate in place of the sissile phosphate. A lag in was observed, then mRNA was cleaved normally. 
	- In bypass mechanism, a helicase unwinds the small RNA to remove the passenger strand 
	- Bypass mechanism likely to be important for removing miR* strand; as miRNA lacks perfect complementarity, unlikely to be targeted by endonucleolytic cleavage 
- For miRNA, strand selection is not that stringent, so some hairpins produce miRNAs from both strands with comparable frequency 

## miRNA biogenesis 

> [!image] miRNA biogenesis (Kim et al 2009)
> **The orientation of Drosha/DGCR8 is opposite of what Dee shows it to be; follow Dee's diagram**. ![[Pasted image 20230522205407.png]]

1. Pri-miRNA transcribed from genome by RNA Pol II; some miRNAs associated with Alu repeats may be transcribed by Pol III 
	1. Pri-miRNA contains single or clustered double-stranded hairpins with single-stranded 5' and 3' termimal overhangs and ~10 nt distal loops
	2. ~50% of mammalian miRNA loci are found in clusters that are transcribed from a single polycistronic transcription unit. 
	3. Some miRNA can also come from introns (mitrons). After splicing, the intro lariat is resolved and the debranched intron forms a hairpin that resembles pre-miRNA. 
2. Pri-miRNA processed by Microprocessor complex to give pre-miRNA 
	1. Microprocessor complex = Drosha + Pasha/DGCR8 
	2. Drosha is inactive in absence of Pasha/DGCR8 
3. Pre-miRNA associates with exportin-5 and RanGTP to be exported to the cytoplasm 
4. Dicer recognises pre-miRNA (via PAZ domain recognition of 3' overhang) and trims pre-miRNA to miRNA (same mechanism as siRNA)
5. (Plants only) HEN1 methyltransferase methylates 3' terminal nucleotide 2'OH
6. Dicer, a dsRBP (e.g. TRBP) and Argonaute protein load the diced dsRNA onto Argonaute 
	1. RISC-loading complex 
7. Argonaute PAZ and MID domains recognises 3' terminus and 5' phosphate of guide strand/miRNA* respectively
8. Strand selection 

### Drosha 
![[Pasted image 20230415220412.png]]
- Class 2 RNAse III enzyme 
- 1 compound catalytic centre with 2 catalytic sites 
- RNAse III domains interact with stem of pri-miRNA and cleaves both strands of the stem 
- The position of cleavage by Drosha dictates one end of the mature miRNA, while Dicer makes the other end 

### DGCR8/Pasha 
![[Pasted image 20230415220421.png]]
- CTT domain is sufficient to interact with and stabilise Drosha; structural data indicates that two CTTs interact with 1 Drosha 
- dsRBDs enhance pri-miRNA cleavage
- Rhed domain important for dimerisation, hemin binding, RNA binding 

### Microprocessor processing of pri-miRNA 
- Microprocessor cuts ~22 bp away from the loop/stem junction 
- Efficient processing of pri-miRNA requires a loop, a dsRNA stem longer than the mature pre-miRNA (i.e. an extra helical turn), and single stranded flanking sequences 
- #experimental_evidence EMSA and FRET studies showed that dsRBDs of DGCR8 interact with dsRNA but not ssRNA
	- This was surprising as DGCR8 binds the basal junction between the helical stem of the pri-miRNA and two strands of ssRNA, so it is unclear how DGCR8 can be positioned at the junction. 
![[Pasted image 20230415220648.png]]

#### Orientation of Microprocessor on pri-miRNA 
- For Microprocessor to cleave pri-miRNA accurately, Drosha has to be positioned so its catalytic centers are 11 bp from a clear basal junction, thus cleaving pri-miRNA at productive cleavage sites 
	- A clear basal junction has two ssRNA segments of ~5 nt that do not base pair with each other (i.e. "clear" of base pairing)
![[Pasted image 20230415221004.png|275]]
- Drosha acts as a molecular ruler that recognises the basal junction 
- Conserved motifs within pri-miRNAs are also needed for various pri-miRNAs to stop Drosha localising to the apical junction 
	- UG motif in basal junction – has binding affinity for Drosha 
	- UGU motif at 5' end of terminal loop – Drosha alone has preference for apical junction, but in complex with DGCR8, Drosha changes its cleavage site to the basal junction. DGCR8 interacts with the apical loop and apical UGU motif to block Drosha from binding to it. 
	- CNNC motif (16-18 nt from cleavage site, in 3' basal segment) – SRSF3 interacts with CNNC motif to recruit Drosha from apical junction to basal junction 
	- GHG motif (7-9) from basal junction – Motif may be recognised by Drosha, but mechanism is largely unclear 
	- Hemin cofactor – proposed to strengthen interaction between DGCR8 dimer and apical loop, and enhance interaction between DGCR8 and apical UGU 
	- m<sup>6</sup>A modifications – Placed by methyltransferase-like 3 (METTL3). m<sup>6</sup>A reader can then recruit DGCR8
![[Pasted image 20230415221528.png]]

### HEN1 (Plants only)
- #structural_evidence XRC of HEN1 shows HEN1 bound to a 22 nucleotide dsRNA via two dsRBDs that bind the same region of RNA but from opposite faces. 
- The catalytic methyltransferase domain restricts substrate length, since it has to bind the 3' terminus. The second to last nucleotide flips out of the helix to contact two residues distant from the active site. This conformation may allow the 3' nucleotide to stack on the last base pair of the helix, thus stabilising substrates with two nt overhangs 

> [!image]- Stacking interaction in catalytic domain of HEN1 (Sashital & Doudna 2010)
> The 3' nucleotide (22m) stacks onto the last base pair of the helix (20m). 21m flips out of the helix to allow this interaction. 
> ![[Pasted image 20230522195751.png]]

- At the 5' end of the RNA, an La motif also helps to restrict substrate length. Two loops interact with the 5' end
	- This is intriguing because the La protein normally interacts with the 3' end of RNA Pol III transcripts via its N-terminal domain 
- Thus the mechanism of substrate length determination is different from Dicer. 

### Regulation of miRNA biogenesis 
**Transcription factors** 
- Transcription factors can upregulate miRNA transcription 
	- E.g. myogenin is a myogenic TF that binds upstream of miR-1, miR-133 to activate their transcription during myogenesis 
	- E.g. p53 activates miR-34 family of mRNAs (see [[D7 Small RNAs and cancer]]) 

**Epigenetic control**
- miR-203 is often DNA methylated in T cell lymphoma but not in normal T lymphocytes 

**Post-transcriptional regulation**
- Interaction with Drosha
	- E.g. TGFβ can activate SMAD proteins, which interact with Drosha to stimulate Drosha processing. 
	- E.g. pri-Let-7 is expressed in both differentiated and undifferentiated ES cells, but Let-7 is detected only in differentiatede cells, so let-7 may be post-transcriptionally controlled 
- Interaction with DGCR8 
	- Drosha downregulates DGCR8 by cleaving DGCR8 mRNA, while DGCR8 upregulates Drosha by stabilising it 
- Interaction with Dicer
	- Let-7 binds to 3' UTR and coding region of Dicer mRNA in a negative feedback loop 
- Let-7 suppresses LIN28 protein synthesis, while LIN28 blocks let-7 maturation (double negative feedback control -> bistable switch)
	- LIN28 inhibits Dicer cleavage of the let-7 microRNA, eventually resulting in its uridylation and subsequent degradation 

**Small RNA turnover**
- ERI1 3'->5' exonuclease degrades siRNAs in *C. elegans*
- Small RNA degrading nucleases affect stability of miRNA in plants 

**RNA editing**
- Adenine deaminases have been observed to edit adenines to inosines in miR-142 
- Editing of pri-miRNAs or pre-miRNAs could make them poorer substrates for Drosha / Dicer processing 

**Nuclear export**
- E.g. Human miR-31, miR-128, miR-105 precursors are retained in nucleus 

## Comparison of siRNA and miRNA biogenesis 

| Criteria        | siRNA  | miRNA  |
| --------------- | ------ | ------ |
| Class III RNAse | Dicer2 | Dicer1 |

# Small RNA modes of action 

![[Pasted image 20230415221719.png]]

- siRNAs bind with perfect complementarity to the target mRNA to direct endonucleolytic cleavage of target
- miRNAs bind with imperfect complementarity to target, resulting in translational repression and decay 

## Argonaute proteins
- Subfamilies
	- Ago proteins – interact with siRNAs, miRNAs 
		- Only Ago2 has slicer activity for RNAi pathway 
	- Piwi proteins interact with [[D7 Small RNAs and cancer#piRNA|piRNA]]
- Functions 
	- Recognition of guide strand
	- Target recognition 
	- Slicer activity (Ago2
- Contain PAZ domains, which bind specifically to siRNAs at characteristic two nucleotide 3' overhangs 

![[Pasted image 20230522203736.png|500]]

### RNA induced silencing complex (RISC)
![[Pasted image 20230415221727.png|225]]
- For both siRNA and miRNA, the minimal effector is the RISC complex of an Argonaute family protein bound to a single-stranded small RNA which guides it to the target RNA via base pairing interactions
- RISC = Argonaute-small RNA complex 
- In Drosophila, siRNA RISC contains Ago2, while miRNA RISC contains Ago1 

### RNA-induced transcriptional silencing (RITS)
- Mediates transcriptional gene silencing via induction of heterochromatin formation in some organisms 

## siRNA 
- siRNAs bind with perfect complementarity to the target mRNA to direct endonucleolytic cleavage of target by Ago2 
	- #experimental_evidence Liu et al (2004) – Myc-tagged human Ago1-3 proteins were expressed in HEK293T cells with siRNA that targets firefly luciferase. Ago proteins were then immunoprecipitated, on the assumption that the siRNA was incorporated into Ago to form RISC. The immunoprecipitates were then tested for siRNA-directed cleavage with radiolabelled target RNA. Reported that only Ago2 complexes directed cleavage 
![[Pasted image 20230415222656.png]]
- mRNA is cleaved in the middle of the region complementary to the 21 nt guide siRNA, i.e. between nucleotide 10 and 11 when counting in an upstream direction from the target nucleotide paired to the 5'-most nucleotide of the guide siRNA 
	- Ago2 does not cleave its own miRNA as it does not align well with cleavage domain 
	- #experimental_evidence Elbashier et al (2001) – Radiolabelled mRNAs were targeted for siRNA cleavage. When the target region of the siRNA is moved by 1 nt, the site of cleavage is also moved by 1 nt, generating products that are 1 nt in size apart 
- Accessibility affects cleavage of target mRNA; accessibility is determined by degree of base pairing/secondary structure around the target 
- After cleavage, by Ago2, the cleavage products are destroyed by [[B6 Cytoplasmic RNA decay|normal RNA degradation processes in the cell]]
	- 5' half is degraded by the exosome (3' to 5', no decapping)
	- 3' half is degraded by XRN1 (5' to 3')

### Structural basis of siRNA guide 5' terminus recognition by Argonaute 
- 5' nt in guide RNA is bound to a highly conserved basic pocket in *Archeoglobus fulgidus* Piwi (AfPiwi) 
	- #structural_evidence Crystal structure showed that the 5' nt is stabilised by stacking with a conserved Tyr residue, and a network of H bonds and Mg2+ anchor the 5' phosphate to the conserved pocket
	- Residues 2-5 in the guide RNA interact via non-bridging phosphates with conserved in Piwi 
	- Thus, 5' end of guide siRNA forms a nucleation site for pairing with the target mRNA 
- In Argonaute, 5' termini can also tend to have a specific nucleotide due to interaction with MID domain 
	- #structural_evidence XRC of eukaryotic Argonaute MID domains have specific contacts between a rigid loop in MID and nucleobase of UMP or AMP. Electrostatic environment in loop not compatible with CMP or GMP. 
	- #structural_evidence NMR titration experiments indicate binding affinity of UMP and AMP is higher than CMP or GMP 
- The small RNA guide strand is bound to Ago such that the seed sequence has its Watson-Crick face exposed to the solvent, allowing for base pairing
	- #structural_evidence This conformation was observed in a crystal structure of *Thermus thermophilus* Argonaute with a DNA guide strand
		- The guide strand in this structure had a distortion between nucleotides 10 and 11, which may be due to interactions with two Arg residues. Upon binding to the target strand, the guide and target may form an uninterrupted helix at the cleavage site (not seen in the study)

### Structural basis of endonucleolytic activity in Ago2 
- Ago2 contains PIWI domain that folds into a structure analogous to catalytic domain of RNAse H and avian sarcoma virus integrase, suggesting that it is the catalytic domain 
	- #structural_evidence XRC of *Pyrococcus furiosus* Argonaute show that PIWI domain has RNase H-like fold
- 2 catalytic Asp residues and a third Asp/His residue (His in hAgo2) in PIWI domain needed for cleavage – catalytic triad 
	- #structural_evidence XRC of *Thermus thermophilus* Argonaute bound to a DNA mimic of guide strand and RNA target show the catalytic triad in the PIWI domain coordinating a pair of Mg2+ 
	- #experimental_evidence Liu et al (2004) – mutation of either conserved Asp to Ala in hAgo2 abolishes target cleavage but not target binding 
- Guide-target duplex has to maintain an A-form geometry by releasing the 3' end of the guide from the PAZ domain 
	- #structural_evidence in XRC of *Thermus thermophilus* Argonaute bound to 12 nt target, 3' terminus of guide is bound to PAZ domain. However, if the target is 15-nt or longer, the 3' end of the guide is released from the PAZ domain to accommodate the extension of the dsRNA beyond a full turn of the A-form helix 
	- #structural_evidence dsRNA duplex bound by *A. fulgidus* PIWI has A form architecture 
- In the absence of target RNA, the guide strand is positioned in Argonaute such that the seed region is well-ordered into a A-form helix 
	- By holding the guide strand in a helical conformation, affinity for the target RNA increases by 300-fold as it decreases the entropic cost otherwise caused by ordering of the guide upon binding to the targe 
		- #experimental_evidence Isothermal titration calorimetry experiments using *A. fulgidus* PIWI
- When the target RNA binds to the guide siRNA, it forms an A-form helix that is arranged such that the scissile phosphate of the target strand is placed adjacent to the putative catalytic site 
	- #structural_evidence Various crystal studies of catalytically inactive Argonaute complexed with guide DNA and target RNAs of various lengths. In one study, RNase H-like active site of *Thermus thermophilus* was found to have 3 Asp residues, and the scissile phosphate at the point of cleavage as adjacent to the three Asp residues 
		- Target strand was mainly positioned via interactions with guide strand 
		- Upon target binding, a conformational change between nucleotides 10-11 is seen in the guide strand. The distortion is turned into A-form helix
- At the same time, Argonaute also undergoes conformational changes upon binding to the target RNA
	- When the guide base pairs to the target RNA, the 3' terminus is released from the PAZ domain, causing Loop 2 in the PIWI domain of Ago2 to shift and bring a fourth catalytic residue into position for catalysis 
	- #structural_evidence XRC of *Thermus thermophilus* and *K. polysporous* Argonaute show this rearrangement of PAZ domain and PIWI domain loops 
	- The N-terminal domain of Argonaute blocks base pairing beyond nt 16 of the guide strand, so the entire guide-target does not form in the RISC 

### Length of dsRNA affects RNAi efficiency 
- RNAi effectiveness increases as length of dsRNA increases
	- Likely related to substrate specificity of enzyme that processes dsRNA, and the increased size of siRNA pool generated 
- For effective RNAi, dsRNA should be longer than 150 bp 

## miRNA 
![[Pasted image 20230415225631.png]]
- Induces translation initiation repression and mRNA decay (in a distinct manner from RNAi pathway)
	- #experimental_evidence lin-4 miRNA binds to imperfect complementary sequences in 3' UTR of lin-14, resulting in downregulation of lin-14 protein 
- miRNA binds to target mRNA such that first nucleotide is unpaired, seed region is complementary to target mRNA, and 3' regions of small RNA subsequently pair up (if possible) with target mRNA ![[Pasted image 20230415225830.png]]
### Structural basis for translational repression by non-Ago2 Argonautes 
- In hAgo1, catalytic His residue is not conserved, and in hAgo5, catalytic Asp residue is not conserved, so they cannot cleave mRNA. For hAgo3, it is unclear why it lacks endonucleolytic activity, but it could be due to conformational differences
- #structural_evidence Crystal structure of hAgo2 in complex with GW182 show that it has two binding pocket that can each bind a Trp residue via hydrophobic interactions. The distance between the two pockets is consistent with the distance between the Trp residues typically found in GW proteins. 

### Repression of translation initiation 
#### Evidence 
- miRNAs interfere with translation initiation
	- #experimental_evidence Pillai et al (2005) – Created RLuc mRNA constructs with 3xBulge (Let-7) binding sites. These mRNAs shifted up to lighter fractions on polysome gradients, suggesting that they were exiting polysomes earlier 
	- #experimental_evidence Bazzini et al (2012) – Used [[B5 Translation and translation regulation in eukaryotes#Ribosome profiling|ribosome profiling]] to show that miRNAs inhibit translational initiation rather than elongation. 
		- If miR-430 reduces translation initiation, lower ribosome occupancy would be expected, with a uniform density along repressed mRNAs -> observed! 
		- If miR-430 reduces elongation (causing ribosome drop-off), a graded distribution of ribosomes would be expected with fewer ribsome-protected fragments in the 3' end than 5' end -> not observed
	- #experimental_evidence Other experiments using microarrays, RNA-seq, proteomics, etc, also showed that translational repression probably occurs at initiation 
- This interference occurs upstream of eIF4E recruitment of eIF4G, possibly at the recognition step of the 5' cap by eIF4E
	-  #experimental_evidence Pillai et al (2005) – Created FLuc constructs with 3xBulge, and with 5' cap, EMCV IRES or HCV IREs. EMCV-IRES does not require 5' cap or eIF4E to drive translation. Found that EMCV-driven reporters were not repressed by let-7, so let-7 repression may be eIF4E-dependent 
	- #experimental_evidence Pillai et al (2005) – Incorporated discistronic reporters that contain both FLuc and RLuc. FLuc translation is driven by 5' cap, while RLuc translation is driven by tethering eIF4E/eIF4G to BoxB hairpins by fusing them to γN peptides. RLuc translation found to be unresponsive to miRNA repression. 
	- #experimental_evidence Matthonet et al (2007) – Used mouse Krebs-2 ascites cell extract for in vitro translation. Found that miRNAs only downregulate capped mRNAs, and that they reduce formation of 80S ribosomes on mRNAs; this repression could be overcome by adding more eIF4F (complex of eIF4E/eIF4G/eIF4A)
- Presence of poly(A) tail can enhance repression
	- Poly(A) tail it is not absolutely required, since mRNAs without a poly(A) tail are still repressed 
		- #experimental_evidence Wu et al (2006) – mRNA with histone stem loop in 3' UTR
		- #experimental_evidence Eulalio et al (2009) – self-cleaving hammerhead ribozyme 

#### Mechanism 
- Ago-RISC induce dissociation of eIF4A from from cap without affecting other eIF4F components to block assembly of eIF4F complex
	-  #experimental_evidence Pillai et al (2004) – Tethering of Ago proteins to 3' UTR can mimic miRNA-mediated repression 
	-  #experimental_evidence Fukao et al, Fukaya et al (2014) – miRNAs target eIF4A. eIF4AI and eIF4AII dissociates from miRNA-regulated mRNAs in humans, Drosophila 
- GW182 disrupts [[B5 Translation and translation regulation in eukaryotes#Closed loop model of translation|closed loop]] by interfering with interaction between PABPC1, reducing translation efficiency 
	- #experimental_evidence Behm-Ansmant et al (2006) – Tethered GW182 represses FLuc mRNA, and it can do this independently of Ago1. mRNA levels are reduced when GW182 is tethered (decay). In addition, the amount of FLuc activity is reduced per FLuc mRNA (repression). 
	- #structural_evidence GW protein TNRC6C has a disordered DUF domain which interacts with alpha-helical C-terminal domain of PABPC1 
	- But this cannot account for all repression, since mRNAs that cannot circularise (e.g. Hhr) and mRNAs without poly(A) tail are also repressed 

#### DDX6 
Mechanism unclear. 

### RNA decay 
#### Evidence of RNA decay 
- #experimental_evidence Bagga et al (2005) – *lin-41* mRNA levels are reduced by expression of let-7. This reduction depends on 3' UTR of *lin-41*
- #experimental_evidence Microarrays used to show that miRNAs result in miRNA decay 
- Deadenylation is involved in miRNA-induced mRNA decay #experimental_evidence Wu et al (2006) – β-globin with miR-125b binding sites. 
	- Found that miR-125b induces degradation of mRNA. Target mRNA undergoes shortening (corresponding to deadenylation), but not endonucleolytic cleavage (like RNAi)
	- mRNA was also cut in half with RNase H. 5' end found not to decay, but 3' end shortens over time, corresponding to deadenylation. 

#### Process 
1. **miRNA recruits Ago1 to mRNA**  
2. **Ago1 recruits GW182**. Conserved F residues in Piwi domain of Ago1 interacts with GW repeats in N-terminal domain of GW182. The W residues insert into hydrophobic pockets exposed on the surface of Ago 
3. **GW182 displaces PABPC1 from poly(A) tail**, exposing poly(A) tail to deadenylases 
4. **GW182 recruits PAN2/PAN3.** Deadenylation by Pan2/Pan3 (for long Poly(A) tails) 

- **Interaction with PAN2/PAN3**. PAN3 may bind to GW182 directly to recruit more PABPC1 via its PAM2 motif. It may also bind to PABC1 that is already bound to GW182  via the PAM2 motif. ![[Pasted image 20230417170812.png|225]]![[Pasted image 20230417170825.png|225]]

5. **GW182 recruits CCR4/NOT**. Deadenylation by CCR4/NOT (for poly(A) tails with less than 10 A's) 

- **Interaction with CCR4-NOT**. GW182 silencing domain interacts with CNOT1 of CCR4-NOT complex. This causes ==decay AND repression==, as CCR4-NOT complex can displace PABP from poly(A) tail 
	- This interaction can be direct, or indirect via CNOT9 
- **Interaction with CCR4-NOT is essential to decay**
	-  #experimental_evidence Depletion of components of CCR4-NOT partially suppresses miRNA-mediated silencing 
	- #experimental_evidence Transcriptome analysis of cells depleted of CCR4-NOT complex components show that majority of miRNA targets are upregulated
	- #experimental_evidence Overexpression of catalytically inactive CCR4, CAF1, or POP2 suppresses silencing in a dominant-negative manner 

6. **CCR4-NOT recruits DDX6, a DEAD-box helicase, which recruits decapping activators.** After deadenylation, decapping occurs, requiring decapping activators, e.g. DCP1/DCP2, EDC3, Pat 
	- DDX6 may also repress translation, but mechanism is unclear 
	- #experimental_evidence Chen et al (2014) – DDX6 KO abolishes miRNA silencing 
7. **Exonuclease degradation.** After decapping, mRNA undergoes decay by 5'-3' exonucleases, e.g. XRN1 

![[Pasted image 20230417163132.png]]

### Repression and decay can occur independently of each other, but repression occurs first 
- miRNA-mediated deadenylation/decay can occur in the absence of translation 
	- #experimental_evidence Wu et al (2006) – Inhibited translation of a β-globin mRNA with miR-125b binding sites by inserting a 40 nt stem loop in the 5' UTR, preventing 80S joining. When miR-125b was added, deadenylation rate increased even though translation was already inhibited. 
- miRNA-mediated repression can occur in the absence of deadenylation 
	- #experimental_evidence Bazzini et al (2012) – Created GFP reporters with a canonical poly(A) tail or an internal poly(A) tail (A<sub>98</sub>C<sub>10</sub>) which has significantly reduced deadenylation. Target with internal poly(A) tail was still repressed by mir430 binding even when deadenylation was reduced. 
- However, repression is initiated before decay 
	- #experimental_evidence Djuranovic et al (2012) – 
- Repression and decay each contribute differently to regulation depending on the mRNA, miRNA analysed 

### P-bodies 
- Proteins involved in miRNA-induced silencing of mRNA may also accumulate the mRNA into P bodies 

# Small mRNAs in plants 
[[Axtell_2013]]

Specifically, Dicer-like/AGO-associated small RNAs. (This is not comprehensive, but is meant to act as further reading)

## miRNAs
### Biogenesis 
[[Voinnet_2009]]

> [!image] From [[Voinnet_2009]]
> 1. Plant pri-miRNAs are mostly transcribed by RNA polymerase II (Pol II) from regions located between protein-coding gene
> 2. RNA-binding protein DAWDLE (DDL) stabilizes pri-miRNAs for their conversion in nuclear processing centers called D-bodies to stem-loop pre-miRNAs
> 3. During processing, the C2H2-zinc finger protein SERRATE, dsRBP HYL1, Dicer-like 1 (DCL1) and nuclear cap-binding complex interact to process pri-miRNA to pre-miRNA
> 4. Pre-miRNA is exported to cytoplasm (possibly via plant exportin 5 ortholog HASTY)
> 5. Pre-miRNA is methylated by HEN1 to protect it from degradation by small RNA degrading nucleases 
> 6. Guide miRNA incorporated into Ago protein
> 
> ![[Pasted image 20230522214631.png]]

### Mode of action 

> [!image] [[Voinnet_2009]]
> ![[Pasted image 20230522214703.png]]
- Most miRNA are loaded into AGO1 
	- AGO1 can slice miRNA targets
	- AGO1 can also repress translation of miRNA targets 

#### Targeting
- In plants, there is near-perfect complementarity within the critical region of nucleotides 2-13. A single mismatch is rare but tolerated. 
- Extent of complementarity between miRNA and target determines the mechanism of target suppression 

#### Reduction in mRNA accumulation 
- Target mRNA cleaved between positions 10 and 11 of the alignment by Ago protein endonucleolytic cleavage 
- In plants, AGO1 is the primary miRNA-associated slicer. 
	- #experimental_evidence Slicer-defective mutants in *Arabidopsis* cannot complement *ago1* mutants 
- Ago-catalysed slicing requires extensive complementarity between the miRNA and the target 

#### Translational repression 
- Strength of repression depends on extent of complementarity 

#### Triggering secondary siRNA production 
- Requires specific patterns of miRNA-target complementarity

#### Mimics that compete with targets of miRNA association 
- E.g. IPS1/At4 family, targeted by miR399 
- The base pairing pattern of such mimics with miRNA is different from the canonical targets, such that slicing is prevented 
	- Target mimics require central mismatches to function, otherwise they get sliced too 

## Secondary siRNAs
- siRNAs derived from double-stranded precursors whose production was stimulated by 1 or multiple upstream small RNAs
- Small RNA targeting of a transcript upstream recruits an RDR, leading to synthesis of the complementary RNA strand which is then processed into secondary siRNAs 
- Biogenesis depends on RDR6, DCL4 
- Secondary siRNAs have multiple functions
	- Target mRNAs involved in development 
	- Coordinate repression of a large gene family e.g. miR-161 mediated repression of PPR genes via cascade of secondary siRNAs in *Arabidopsis*

## NAT-siRNAs
- Arise from hybridisation of separately transcribed, complementary RNAs. 
- These RNAs are transcribed from opposite strands of the same locus
- E.g. Region overlapping *P5CDH* and *SRO5* genes in *Arabidopsis* are the source of one NAT-siRNA. This siRNA initiated phased siRNA synthesis from the *P5CDH* transcript, leading to a decrease in *P5CDH* accumulation 

# Future issues 
From [[WilsonDoudna_2013]]
1. What is the architecture of the microprocessor complex and how does it facilitate recognition of the stem-ssRNA junction? 
2. Human Dicer lacks a high-resolution structure, and there are no RNA-bound Dicer structures available for any organism. 
3. How does the RISC-loading complex perform the subtle task of strand selection? 
4. What are the structural details of key protein-protein interfaces such as Argonaute–GW protein, Argonaute-Dicer, Dicer-dsRBP, and Drosha-DGCR8? 
5. What are the spatial and kinetic properties of silencing processes downstream of RISC assembly?

# Links
- [[B5 Translation and translation regulation in eukaryotes]]
- [[D7 Small RNAs and cancer]]