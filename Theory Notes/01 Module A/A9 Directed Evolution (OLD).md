# Questions
- Enzyme catalysis
	- Discuss, with examples, how the measurement of isotope effects contributes to the explanation of enzyme catalysis.
- Protein dynamics and enzyme function 
	- What role has the dynamic conformational behaviour of proteins played in the evolution of enzyme function?
	- How compelling is the experimental evidence for conformational selection in enzyme catalysis? Discuss whether the concept of conformational selection explains the role of protein dynamics in catalysis.
- Application of protein engineering strategies 
	- An enzyme for degradation of the polymer Nylon (a polyamide, structure shown below) used in synthetic fibres is required in order to break down the enormous amount of waste arising from consumer products. Discuss possible strategies to create an enzyme catalyst for efficient Nylon biodegradation and include consideration of its practical implementation and the likelihood of your strategy being successful
	- An enzyme that degrades the polymer polyethylene terephthalate (PET, structure shown below) is needed in order to deal with the enormous amount of waste arising from consumer products that contain this polymer. Discuss possible strategies for developing an enzyme catalyst that efficiently degrades PET and include consideration of their practical implementation and likelihood of success.
	- Outline an experimental approach for the directed evolution of a phosphotriesterase (a phosphotriester-hydrolysing enzyme). Why is your suggested approach better than the alternatives?
	- ==Outline different approaches to generate functional proteins with novel properties and discuss any difficulties likely to be encountered==.
- Directed evolution approaches 
	- Many approaches are being developed for function selection using combinatorial libraries of nucleic acids and proteins. Compare and contrast these approaches and the relationship of their products to those of natural evolution in organisms.
	- Compare and contrast approaches for directed evolution of (a) proteins that bind to defined molecules and (b) proteins that catalyse chemical transformations.
	- ==Discuss to what extent the strategy chosen in directed evolution of an enzyme determines the properties of the evolved catalyst. Use examples to illustrate your view.==
- Factors affecting success of DE 
	- ==How can you increase the probability of success in directed evolution experiments?==
	- What strategies and technological approaches make it more likely to obtain functionally improved or altered catalysts by directed evolution?
	- **Comparing screening methods**. Why is the linkage of genotype and phenotype crucial for a directed evolution experiment? Discuss the advantages and limitations of methods for directed evolution with respect to the nature of this linkage.
- Rational design 
	- What aspects of enzyme catalysis explain why rational design of enzymes to catalyse novel reactions is currently difficult. Use examples to illustrate your answer.

# Enzyme catalysis
## Elucidating mechanisms 
### Metal-cation specificity switch experiments 
- Catalytically important metal-cation interactions can be identified based on different binding specificities of hard and soft metals for hard and soft ligands
- E.g. To see if an O-Mg<sup>2+</sup> interaction is catalytically important (hard-hard interaction), we can replace O with a soft ligand or Mg2+ with a soft metal, and see if it lowers the rate of reaction. Then, substitute the other interacting partner with a soft ligand/metal, and if it rescues the catalytic activity of the enzyme, this is evidence that there is direct interaction 

# Rational design 
## Challenges in rational design 
- Mutations far away from the active site can influence protein function 
	- E.g #experimental_evidence [[A9 Directed Evolution (OLD)#^94aa55|O'Maille et al 2008]] – Only 2/9 synthase amino acid residues investigated in the sesquiterpene synthases were in the active site, with the remainder scattered throughout the enzyme 
- Very small changes in structure or chemical properties can have big effects on catalysis 

# General strategy for directed evolution 

> [!image] General strategy for directed evolution ([[ZeymerHilvert_2018]]) 
> ![[Pasted image 20230421165456.png|650]]

1. Starting point – any protein that exhibits measurable activity for the reaction of interest 
	1. Existing enzyme 
	2. Low promiscuous activity of a natural enzyme 
	3. Rational engineering
	4. De novo computational design 
2. Generate DNA library via mutagenesis 
3. Screening/selection 
	1. Tight linkage of genotype and phenotype needed so that variants can be further optimised 
4. Use data from screening/selection to infer structure-function relationships 
5. From candidates, generate more variants and repeat selection, ideally using structural information gained from previous round
6. Re-iterate, using combinations of both DE and rational design. 

> [!Tip] Screening and selection are not the same
> - **Selection methods** link enzymatic activity to cell survival. This is limited by the transformation efficiency of the host organism, but allows large libraries to be surveyed in a single experiment.
> - **Screening methods** do not link enzymatic activity to cell survival. This is useful if the enzymatic activity cannot be linked to cell survival, and also provides data on the phenotypes of the variants. However, as activity of each library member has to be individually determined, throughput is lower. 

# RNA evolution 
- In RNA evolution, the genotype is the phenotype, so there is a direct genotype-phenotype linkage 
- In RNA there are only 4 monomers (A, C, G, U), so the sequence space is smaller than for proteins (which have 20 natural amino acids) – although this also means that the functional space is probably smaller as well 

## Ribozyme catalytic strategies 
- Intramolecular reactions: Ribozymes use the intramolecularity of 2-OH for catalysis 
- Covalent catalysis: OH groups 
- General acid/base catalysis: RNA can tune the active site environment to alter pKa of reactive groups 
- Cofactor catalysis: Metals can be used both for stabilising charge development and activating H2O 
- Strain: Use of electrostatic interactions to destabilise the ground state of the reactant 

### Examples of ribozymes 
- Alkaline phosphatase: removes 5'-phosphates from DNA and RNA, active at alkaline pH 
  ![[Pasted image 20221227235604.png|500]]
  - Group I intron ribozymes 
	  - Catalytic mechanism: "Three metal model"
	    ![[Pasted image 20221227235802.png|300]]

## Systematic Evolution of Ligands by Exponential Enrichment (SELEX)
- A directed evolution method for RNA (and nucleotides generally)
![[Pasted image 20221228000440.png|375]]
- #experimental_evidence 
	- [[B4 RNA splicing#^1fc4aa|Tuerk & Gold (1990)]]
	- [[B4 RNA splicing#^50408d|Liu et al (1998)]]
- Related techniques: RNAcompete, RNA Bind 'n' Seq 

## Using tagged substrates for DE of catalytic nucleic acids 
![[Pasted image 20221228000855.png|275]]
1. Generate a library of nucleic acids 
	1. E.g. add random sequences around the active site of the ribozyme 
2. Pool of nucleic acids is incubated with a tagged substrate (e.g. biotinylated)
3. Nucleic acids that can react with the substrate are labelled with the tag 
4. Tag is used to purify active nucleic acids (e.g. streptavidin beads)
5. Amplify active sequences 
6. Repeat selection 

### Example 
- #experimental_evidence Evolving a polynucleotide kinase ribozyme: Lorsch & Szostak generated a partially random pool of ribozymes by adding random sequences to the beginning, middle, and end of the ATP binding site in the ribozyme. The pool was incubated with ATP-γS, and any active ribozymes were tagged by a transfer of a thiophosphate group to their 5'-hydroxyl. Active sequences could then be purified by reacting the RNA with thiopyridine-activated thiopropyl sepharose, eluted with 2-mercaptoethanol, and amplified. 
  ![[Pasted image 20221228001716.png|300]]
- #experimental_evidence RNA ligase ribozyme selection: Bartel & Szostak (1993) reported the selection of ribozymes from completely random sequences. Sequences that could catalyse the nucleophilic attack of the 5' phosphate to the 3' OH end of the substrate sequence convert the interrupted hairpin loop into a continuous one. Successful candidates could be pulled down via column, then underwent RT-PCR for amplification 
  ![[Pasted image 20221228001824.png|300]]

# Fitness landscapes 
## Directed evolution is navigating fitness landscapes 
- A fitness landscape is the mapping from genotype to phenotype fitness
- Directed evolution is an optimisation on the fitness landscape 
- Rougher the landscape, the harder it is to reach the global optimum since local optima can create traps unless a side-step or temporary decrease in fitness is permitted, or if multiple simultaneous mutations enable a jump to a new peak (i.e. [[A9 Directed Evolution (OLD)#Epistatic effects create local optima|epistasis]])
- Natural evolution can discover new protein functions via neutral or slightly deleterious mutations, but directed evolution is constrained to beneficial mutations as the number of possibly evolutionary paths becomes too many if we take neutral or deleterious steps as well, though this is not a severe limitation since many new functions can be evolved by such simple adaptive walks 
- Since the sequence space is so vast, the challenge is to find efficient ways of exploring the fitness landscape for useful sequences 

## Features of fitness landscapes 
- High dimensional, likely with many possible mutational trajectories from starting point to solution 
- Low overall density of functional sequences – most sequences do not code for any functional protein, much less the desired protein 
- Uneven distribution of functional sequences – functional sequences are often found next to other functional sequences 
	- This feature is required for evolution by point mutation to be successful. Evolution can step one mutation at a time only if there is a continuous network of functional proteins. 
- Proteins are robust to mutations, with a significant fraction of mutants retaining fold and some level of function 

## Effects of epistasis on landscape 
- Epistatic effects mean that we may have to select for combinations of mutations rather than just single mutations, since the order in which single mutations are done can affect selection 
- Different kinds of epistasis: 
	- Magnitude epistasis: both mutations are beneficial, but together show synergy 
	- Sign epistasis: 1 mutation is beneficial and 1 is deleterious on its own, but together show synergy. Sign epistasis can create local optima in fitness landscapes. The beneficial mutation can be considered as compensatory or as a form of "uphill divergence" that then allows for further more mutations. 
		
	- Reciprocal sign epistasis: both mutations are deleterious on their own, but together show synergy 
	  ![[Pasted image 20221230163631.png|550]]
- Epistasis can occur between remote and unexpected mutations, or over long distances 
	- Challenging to identify such epistatic effects – Illumina reads are too short; long-read sequencing technologies that reveal even single mutations are needed 
- Mutations that affect stability are often involved in epistatic interactions, with the effect of many mutations depending on the stability of the parent sequence
	- E.g. #experimental_evidence Wang et al (2002) – Fitness effects of active site mutations in β-lactamase depended on the presence of a stabilising M182T mutation 
	- 
	  ![[Pasted image 20221230155119.png|225]]
	- Proteins with low stability cannot accept more than a small fraction of possible mutations, because most mutations, including most activating mutations, are destabilising, while proteins with higher stability above a minimal threshold can explore more mutations
	- Neutral mutations with no effect on activity but effect on stability can be important to adaptive pathways, and often incorporating stabilising mutations helps to open new adaptive routes. 
![[Pasted image 20221229230703.png|400]] ^47d2be

# Strategies for directed evolution 
## Selecting a starting sequence 
### From existing organisms  
- Culture collections 
- Environmental gene libraries
	- Metagenomic DNA (e.g. Brain, RU Groningen)
	- Extremophiles (polluted, extreme environments)
	- Gene banks from pure or mixed cultures
- Bioinformatics and genome mining
	- Genome sequencing projects – there are many more ORFs sequenced than have been characterised for structure and function. 
	- **Functional metagenomics** – Screening sequences for function with assays (activity prediction from sequence is still not 100% accurate). 
		- Hypothesis free
		- Search for activity is not limited by sequence homology, so can find hits in unexplored sequence spaces, thus uncovering diverse and novel starting sequences 
		- Droplet screening may be uniquely suited due to its extraordinarily high throughput compared to using robots, colony screening. 
		- #experimental_evidence [[ColinEtAl_2015]] used ultrahigh-throughput screening of microfluidic picolitre droplets to screen a million-membered metagenomic library for sulfate monoester and phosphotriester hydrolases. Most hits were not predicted by sequence analysis as there were promiscuous activities. 
- Massive sequencing projects
	- Sargasso sea project (C. Venter)

### Computational de novo design
#### Rosetta suite 
1. Use quantum-mechanical methods to predict where catalytic groups should ideally be placed to achieve rate acceleration (creating a theoretical enzyme or "theozyme")
2. Calculate idealised geometry for the transition state implanted in silico into structurally known protein folds (Rosetta Design)
	1. Look in PDB for proteins that can accommodate this geometry 
	2. Optimise packing of residues on a given backbone by combining side chain orientations for various AAs deposited in a rotamer library 
	3. Assess quality of designs
	4. Rank many different active site locations in a backbone based on catalytic geometry, TS energy 
3. Optimise complementary surface in the intended binding pocket by scoring with knowledge-guided Metropolis Monte Carlo sampling approaches coupled with knowledge-based energy functions (Rosetta Match)

#### New ML methods 
- RF diffusion 

#### After computational design 
Using this method, can produce crude enzymes with weak acceleration that resemble primordial enzymes more than modern enzymes – but provides a starting point. 

After getting the in silico designs, we can experimentally characterise the top ranking designs, fine tune designs with directed evolution, and use the refined designs to improve the algorithm. 

### Evolvability
- A good parent sequence is one that is **proximal** to the desired function; it should exhibit enough of the desired function such that small improvements can be made in a high-throughput screen. It should also be **evolvable**, including sufficient stability to accommodate multiple, potentially destabilising mutations (assuming the target property is not stability) ([[RomeroArnold_2009]])
- Currently, it is not known what makes a protein more evolvable than others, though it has been speculated that the type of catalytic mechanism could be involved, or that evolvable proteins exist in closely related but functionally diverse conformations ([[RomeroArnold_2009]])
	- A good indicator of evolvability is the natural functional diversity in a protein family ([[RomeroArnold_2009]]), e.g. protein families that accept a diversity of substrates 
	- #experimental_evidence O'Maille et al (2008) investigated a fraction of the 512 possible variants having different subsets of the nine amino acid changes that interconverts reaction selectivity between a sesquiterpene synthase and its homolog. Half of the variants catalysed formation of products of both parental synthases as well as several other related synthases.  ^94aa55
- Evolvability could also be improved by improving the stability of the starting point, as the parent sequence would have a larger margin above the stability threshold to explore the sequence space 
	- #experimental_evidence Bloom et al (2006) engineered a P450 variant with higher thermostability as a starting point for DE towards new P450 substrates. The research demonstrated that the more stable variants could produce more variants with new catalytic activity as they were able to tolerate certain destabilising mutations that were necessary for the new function. 
	- Use thermophilic proteins 
	- However, protein engineers should also be cautious about using an overly stable starting point, since not every stabilising mutation acts as a global suppressor, and excess stability could reduce evolvability (e.g. by rigidifying the protein to restrict alternative conformations that are necessary for new functions)

## Generating DNA libraries for protein evolution 
### Challenges in generating protein libraries 
- The sequence space covered by a typical protein is far too large for any library to attain. For a protein with 200 amino acids, the number of possible sequences is 200<sup>20</sup> > 10<sup>260</sup> – far more than the number of atoms, molecules in the universe (10<sup>80</sup>). 
	- Sequence space covered by a library could be constrained by using structural, functional or phylogenetic information, or by optimising protein domains separately 
		- However, this runs the risk of missing activating mutations that lie outside catalytic sites and exert influence via mechanisms not obvious from structural studies ([[RomeroArnold_2009]])
- Many enzymes are composed of multiple subunits and may contain cofactors that are not present in the library under selection 
- A good library is one that gives the highest probability of finding improved proteins, thus minimising screening effort  
- The best libraries are the **most diverse ones**
- Ensuring that library generation is as random as possible – enzymes used for mutagenesis may exhibit some bias in binding site on DNA sequences, or for which nucleotides to incorporate 
	- E.g. Mu transposon used in TRIAD exhibits only a weak bias for transposition at 5'N-Py-G/C-Pu-N sequences (Emond et al 2020)

### Random methods 
![[Pasted image 20221228002526.png|475]]

#### Error-prone PCR (epPCR)
- Use polymerases with no proofreading ability, and increase error rate using particular reaction conditions (e.g. high Mg<sup>2+</sup> concentrations)
- 5-8 mutations per 1000bp in a gene per PCR (30 cycles) can be generated, with an almost negligible rate of insertions or deletions 

##### Advantages
- No knowledge of the protein is required 

### Directed methods 
![[Pasted image 20221228002612.png|500]]

#### Saturation mutagenesis 
- At specific positions in the gene, insert randomly synthesised oligonucleotide cassettes or introduce random primers 
- Number of permutations can be reduced if oligo synthesis is biased, e.g. only introduce hydrophilic amino acids 

##### Advantages
- Reduces library size (although if total randomisation is done at each position, the numbers can still get big)

##### Disadvantages
- Need to know structure of the starting protein
- Ignores influence of residues far away from the active centre that can be important 

### Recombination 
![[Pasted image 20221228002622.png|500]]

#### Family shuffling 
- Starting from a library of homologous genes, break the DNA up into fragments for shuffling. Denature the fragments to form single stranded fragments, anneal these fragments to each other, and extend the fragments to generate recombined genes. This can be repeated multiple times to shuffle the gene fragments. 
  ![[Pasted image 20221228003302.png|400]]

#### Incremental truncation for the creation of hybrid enzymes (ITCHY)
![[Pasted image 20221228003505.png|250]]

1. Generate a library of fragments via the incremental digestion of two genes 
2. Randomly ligate fragments together 

#### Family shuffling vs ITCHY 
![[Pasted image 20221228004257.png|300]]

| Family shuffling                                                                                 | ITCHY                                                                                                                                                            |
|--------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| No knowledge of structure or function is required                                                | Same                                                                                                                                                             |
| Generates a diverse library – shuffled sequences cover disparate points of the sequence space    | Same                                                                                                                                                             |
| Can be unstable – we are putting together random parts that don't necessarily work together well | Same                                                                                                                                                             |
| Need >70% DNA homology (corresponds to >90% amino acid homology)                                 | DNA homology-independent, though some structural homology is required since recombination of completely unrelated proteins is unlikely to give folded structures |
| Multiple crossovers                                                                              | Single crossovers                                                                                                                                                |
| Pool is biased towards crossovers in regions of homology                                         | No regional preference for crossovers                                                                                                                            |
| Length distribution resembles parents                                                            | Length distribution ranges from 0 to  (length of gene A + length of gene B)                                                                                      |

![[Pasted image 20221228003421.png|400]]

#### SCRATCHY 
1. ITCHY 
2. Functional selection from ITCHY library 
3. DNA shuffling using selected candidates
4. Functional selection 

![[Pasted image 20221228004714.png|450]]

#### Advantages 
- New combinations of residues can give rise to novel properties 
- Recombination can generate neutral drifts, since many mutations arising from recombination are neutral or nearly neutral, which can be important to creating new functions or robustness to mutation
- Can separate mutations beneficial to stability from those deleterious to enzyme activity, thus removing the trade-off (see [[CherryEtAl_1999]]) 

### Indel libraries 
- Indels lead to shifts in reading frame and alter the length of backbone, which can change packing and orientation of domains, thus resulting in global changes in protein conformation. In contrast, point mutations result in local changes, and so there is less diversity in the sequence space covered by substitution libraries
- In nature, the ratio of indels to substitutions is also 4 times higher in higher eukaryotes than in bacteria, which could suggest that indel mutations are important to innovation in evolution. 
- Most indels fixed in protein-coding genes are short (1-5 residues) and occur almost exclusively in loops linking secondary structure elements at the solvent-exposed surfaces of proteins 
- Short indels at oligomerisation surfaces can be important to protein stability/specificity, and rearrangements near active site can change specificity and activity. 

#### Transposon-based random insertion and deletion (TRIAD) mutagenesis 
![[Pasted image 20221229195939.png|450]]

- An engineered Mu transposon used to put transposons in entire gene at random sites. Mini-mu transposons are engineered to have type IIS restriction sites at each end. In addition, transposons for deletion libraries also have restriction sites within the transposon to allow for deletion within the target sequence 
- Then can restrict out transposon, and insert a cassette at the transposed site 
- To create a deletion, the restriction fragments could be ligated, or after cassette insertion, the cassette could be restricted at particular points within the cassette and the fragments re-ligated
- #experimental_evidence Emond et al (2020) used TRIAD to generate a library of Indel variants of *Brevundimonas diminuta* phosphotriesterase which hydrolyses the pesticide paraoxon, and screened the library for improved arylesterase activity 

##### Advantages 
- TRIAD approach can create diverse Indel variants, with TRIAD libraries covering >85% of positions in the DNA sequence of *wtPTE* (Emond et al 2020)

#### Transposon-based in-frame insertions 
![[Pasted image 20221228010634.png|575]]

- Can also be used to clone in a second cassette that is in frame 

### Comparing methods of library generation
#### Comparing random methods, directed methods, shuffling 
![[Pasted image 20221228004752.png|500]]

#### Substitution vs InDel libraries 
- While indel libraries could produce members with greater activity, fewer library members are likely to be active 
	- #experimental_evidence Emond et al (2020) compared the levels of native phosphotriesterase and promiscuous arylesterase activities for several hundred *wtPTE* variants from each TRIAD library and from a trinucleotide substitution library (TriNEx). The frequency of Indels beneficial for arylesterase activity was at least 3-fold higher than substitutions 
  ![[Pasted image 20221229160934.png|500]]

## Screening/selection methods for protein evolution 
- Screening makes use of high-throughput functional assays, while selection involves hosts with improved proteins outcompeting others 

### Key challenges 
- **Low probability of finding functional molecules** in the vast sequence space 
- **Phenotype-genotype linkage** has to be created to allow for amplification of that molecule so that it can be found
- **Creating an accurate screen/selection** – could be problematic if screen/selecting for a surrogate function that is more amenable to high-throughput assays than the actual desired function 
- **Stringency selection** – Important to avoid creating an overly stringent screen/selection. if the desired function is beyond what a single mutation can accomplish, the problem should be broken down into smaller ones, and then stringency increased over multiple rounds of screening/selection 
	- Increasing stringency over time e.g. gradually increasing substrate affinity required of variants to move onto next round of selection 
	- Instead of trying to achieve the desired product directly, try to choose intermediate target substrates 
		- #experimental_evidence Fasan et al (2007) evolved P450 fatty acid hydroxylase into a propane hydroxylase by first improving the existing weak activity on octane until there was sufficient side activity on propane.  
	- Create a generalist enzyme with broader specificity before improving activity of the generalist 
		- #experimental_evidence Escalettes & Turner (2008) evolved galactose oxidase to increase its substrate range to include both D-glucose and 1-phenylethanol, and further directed evolution of this generalist improved its activity on 1-phenylethanol 

![[Pasted image 20221228010804.png|500]]

### Functional assay 
#comment Fill this in 
- Substrate affinity 
- Substrate specificity 
- Enzymatic activity 
- 

### Phage display 
#### Principle
- Inserting extra DNA at an appropriate point in the genes of the capsid proteins of filamentous bacteriophage M13 results in the additional amino acid residues appearing as a peptide or protein insert in the capsid protein 
	- The protein can be displayed on inor coat protein p3 or major coat protein p8 
	- For both types of coat proteins, the additional amino acid sequence is inserted close to the N-terminus of p3 or p8
	  ![[Pasted image 20221229162104.png|300]]
-   This peptide/protein would be displayed on the surface of the assembled virion
-   By inserting random DNA sequences, large peptide libraries can be created
-   “Panning” to select phages displaying the peptide that can bind to the desired ligand 
-   Phage display is a selection technology (versus screening), so characterisation of individual clones is not needed → faster and more efficient 

#### Process
1.  Create phage library by inserting random DNA sequences into phage DNA in the coat protein sequence 
2.  Package DNA library into phage particles 
3.  Immobilise desired ligand on a surface 
4. Expose library to immobilise target proteins 
5.  Wash to remove non-binding phages 
6.  Purify phages that bind 
7.  Amplify binding phages by passaging through bacterial host 
8.  Re-screen 
9. Eventually subclone for soluble expression 

- Multiple rounds of screening → selection of peptide with high binding affinity
- Sequencing of selected clones allows for determination of genotype 

#### Examples
- #experimental_evidence Selection for catalysis by catalytic elution using phage display (Fastrez 2001) – Used phage display to select metalloenzymes. Active enzymes are initially inactivated by removal of an essential metal cofactor, then captured using immobilised substrate. Active phage enzymes are eluted by reactivating them with addition of metal cofactor. This works because enzymes usually have weak affinities to their products. Additionally, multiple enzyme display could result in avidity effects, which helps in selection as enzymes usually have low affinities for their substrates. 
- #experimental_evidence Selection for catalysis by reactive product (Pluckthun 2003) – Directed evolution of phage-displayed HuCAL-scFv for catalysis of phosphate monoester hydrolysis. Successfuly catalysis of DFMPP results in the formation of a reactive product, quinomethide, that forms a covalent bond with the enzyme and links it to a surface, while nonbinding and noncovalent boud phages are removed by washing. Covalently trapped phages can then be released by disulfide rediction and amplified for further selection.
  ![[Pasted image 20221229170137.png|375]]

#### Advantages
- Can display large peptide libraries (10<sup>9</sup> to 10<sup>12</sup>) 

### Colony screening  
#### Process
1. Create a DNA library consisting of randomised mutant variants of the target gene 
2. Clone mutagenised sequences into an expression vector 
3. Transform vector into *E. coli*
4. Express encoded proteins 
5. Pick colonies, culture colonies 
6. Screen cell lysate (containing gene variants) 
	1. HPLC
	2. Robotics 
7. Select positive hits and repeat screening 
	1. Screening methods must have genotype-phenotype linkage 
	2. Can be combined with robotics for higher throughput 

#### Examples
- Directed evolution of nitrobenzyl esterase to improve thermal stability for use in industrial processes 
- #experimental_evidence Joo et al (1999) reported the directed evolution of P450 from *Pseudomonas putida* to have napthalene hydroxylation activity in the absence of cofactors with 20-fold higher activity than the native enzyme. 

#### Advantages
- Simple
- Throughput up to 10<sup>4</sup>, with robotics up to 10<sup>6</sup> (though this is expensive)
- Has proven to be successful in the past

#### Disadvantages
- Musts be able to detect the product before it diffuses away from the cell 
- Because it is cell-based, the library size is limited by transformation efficiency (<10<sup>9</sup>)
- Since it is *in vivo*, toxic proteins cannot be selected for, and native *E. coli* proteins may also interfere with function 

### Ribosome display 
#### Process 
1. Transcribe DNA library *in vitro* to form mRNAs that lack a stop codon (so DNA sequence of gene should not have stop codon)
2. In vitro translation of mRNA results in mRNA-ribosome-protein complexes, since the protein and mRNA cannot dissociate from the ribosome without the stop codon triggering release 
	1. These complexes can be kept stable by using a low temperature and high Mg<sup>2+</sup> concentration 
3. Immobilise desired ligand on a surface 
4. Expose library to immobilise target proteins 
5. Dissociate mRNA-ribosome-protein complexes 
6. Elute mRNA and purify 
7. RT mNA to form cDNA, then PCR to introduce mutations, yielding a DNA pool enriched for binders that can be used in the next round of selection 
![[Pasted image 20221229170735.png|425]]

### mRNA-puromycin fusion / mRNA display 
#### Process 
1. Transcribe DNA library *in vitro*
2. Ligate a DNA-puromycin linker to the 3' end of the mRNA 
3. When mRNA is translated *in vitro*, ribosome will stall at the RNA-DNA junction 
4. Puromycin can then bind to the ribosomal A site 
5. Nascent polypeptide is transferred to puromycin, forming an mRNA-polypeptide complex linked by the DNA-puromycin linker → achieves genotype-phenotype linkage 
6. Isolate mRNA-polypeptide complex (e.g. via pull down using fusion tags on the polypeptide) and reverse transcribe RNA to DNA 
8. Use DNA-polypeptide complex for selection experiments (expose to immobilised substrate) 
9. Elute bound complexes (e.g. via competitive elution) 
10. Amplify DNA via PCR  
![[Pasted image 20221229173351.png|225]]

#### Examples 
- #experimental_evidence Keefe & Szostak (2001) used mRNA display to perform *in vitro* selection on a totally random sequence space, using a large library of > 10<sup>13</sup> candidates, for ATP-binding affinity. The selection yielded 4 new ATP-binding proteins that appear unrelated to each other or existing proteins in databases. 

### Droplet screening 
- Genotype-phenotype linkage is achieved by compartmentalisation of DNA with protein in a droplet (could be seen as an artificial cell)

#### In-vitro compartmentalisation (Tawfik & Griffiths 1998)
1. IVTT system containing a library of genes (physically) linked to a substrate for the reaction being selected is dispersed into a water-in-oil emulsion, with 1 gene per droplet 
2. Transcribe and translate genes into proteins 
3. Proteins convert substrate into a product that is linked to the gene
4. Break emulsions and quench all reactions to combine droplets 
5. Genes linked to the product are isolated and amplified, and can be characterised or subject to further rounds of selection 
![[Pasted image 20221229205346.png|325]]

##### Examples
- Cohen, Tawfik & Griffiths (2004) used *in vitro* compartmentalisation to generate a *HaeIII* methyltransferase variant that methylates a novel target site. Methylation is linked to replication by screening for the ability to methylate a restriction site on the gene encoding the methyltransferase. Active methyltransferase variants remain intact as the methylation protects the gene from digestion, while the genes of inactive ones are digested by restriction enzyme. Undigested genes could the be amplified via PCR.
  ![[Pasted image 20221229205527.png|375]]

#### Compartmentalised self-replication for polymerase evolution 
1. Express polymerase DNA library in *E. coli*
2. Compartmentalise *E. coli* with reagents (dNTPs, primers)
3. Lyse *E. coli* in water-in-oil droplets 
4. PCR cycle 
5. Polymerase with higher activity would replicate its own DNA faster than polymerase with lower activity 
6. Break open droplets and inactivate polymerases (to prevent cross-reactivity)
![[Pasted image 20221229204231.png|325]]

- In theory, CSR could be used to evolve enzymes not involved in nucleic acid reactions. If the catalytic reaction results in the production of replicase substrates or consumption of replication inhibitors, then the activity of the enzyme can be coupled to polymerase activity, resulting in replication of the genes encoding the enzymes 

##### Examples
- Ghadessy et al (2001) used CSR to evolve a *Taq* DNA polymerase with 11-fold higher thermal stability and >130-fold increase in resistance to heparin inhibitor compared to the wild type. 
- Ramsay et al (2010) performed DE using short-patch compartmentalised self replication (spCSR) on DNA polymerase variants to incorporate fluorescent dye-labelled deoxynucleotide triphosphates, Cy3-dCTP and Cy5-dCTP.  In spCSR, only a short, defined segment of the polymerase gene is replicated and evolved. 

#### Bulk droplets vs microfluidic droplets 
| Bulk droplets                                                | Microfluidic droplets                                                              |
| ------------------------------------------------------------ | ---------------------------------------------------------------------------------- |
| Large variation in droplet size that is difficult to control | Monodisperse droplets, allowing product concentrations to be determined accurately |
| Vigorous mixing required                                     | Gentle formation                                                                   |
| One-spot assays, so no time dependence possible              | Time-dependent assays possible                                                     |
| Further processing not possible                              | Processing possible, with tight control over incubation, addition, sorting         |
| Higher throughput                                            | Somewhat reduced throughput                                                                                   |

- Variation in diameter in bulk droplets is non-ideal as it affects the quality of the optical measurement of concentration. Inability to measure product concentrations accurately leads to noisy data. 
- Microfluidic droplets are ideal for directed enzyme evolution, as we can select for product formation rates
- Selection for expression: Vary expression by mutation in the promoter region (equivalent to varying protein concentration)
- Selection for catalysis: Vary incubation time 

#### Microfluidic droplet screening 
1. Expression of protein of interest in *E. coli*
2. Compartmentalisation of single cell with substrate and cell lysis agents 
3. Incubation of droplets to generate fluorescent product
4. Sorting of droplets, where hits are detected by a laser (FACS)
5. Plasmid DNA from selected droplets are electroporated into *E. coli*
	1. PCR can cause undesired DNA recombination and mutation which lowers the number of active clones after sorting
	2. Direct transformation via electroporation obviates the need for PCR amplification and cloning, which prevents mutations and amplification biases. It is also faster. 
6. Repeat cycles with increased stringency of sorting to identify improved enzyme variants 

##### Examples
- Kintses et al (2012) used microfluidic droplets to evolve the arylsulfate from *Pseudomonas aeruginosa* to have improved phosphonate hydrolase activity. 

### Comparing selection methods 
| Method            | Genotype-phenotype linkage                                        | Throughput |
| ----------------- | ----------------------------------------------------------------- | ---------- |
| Phage display     | Phage coat displays protein, encloses gene                        |            |
| Colony screening  | Gene encoded by plasmid is expressed in *E. coli*                 |            |
| Ribosome display  | mRNA and protein are tethered together via ribosome               |            |
| mRNA display      | mRNA and protein are tethered together via a puromycin-DNA linker |            |
| Droplet screening | DNA sequence and polypeptide are compartmentalised into a droplet |            |

## Evolving stepwise, or with multiple mutations? 
### For stepwise directed evolution 
- Gradually accumulating single beneficial mutations while gradually increasing selection pressure is often an effective and efficient DE strategy 
	- Many problems in the literature could be solved using simple adaptive walks involving single amino acid changes ([[TracewellArnold_2009a]])
- Proteins are able to tolerate a limited mutational load, so only mutating 1 amino acid at a time gives the protein time to "recover" stability by introducing mutations that [[A9 Directed Evolution (OLD)#Improving stability|improve stability]]

### For multiple mutations
- Probably less innovative to only go 1 amino acid at at time – may get stuck at local optima 
	- Going "1 amino acid at a time" assumes that there are intermediates that exist along the trajectory and that the path chosen in each generation does not lead to a dead end 
- Multiple simultaneous mutations may be needed to generate more innovation, e.g. to create a new catalytic activity or on activity for a substrate that the parent and its single mutants show no measurable activity 
- However, as mosts mutations are deleterious, "probability that a variant retains its fold and function declines exponentially with the number of random substitutions" ([[RomeroArnold_2009]])
- Introducing multiple mutations at once may also capture synergistic epistatic effects, but may also make it more difficult to identify improved single mutation variants, as the more common deleterious mutations can mask beneficial ones, which are often rarer 

### Alternative solutions to local optima problem 
- Use a different parent sequence/starting point 
- Use non-natural amino acids to expand the sequence space 
- Find more conservative ways to introduce multiple mutations, e.g. using computational protein design tools to identify combinations compatible with structure retention 
- [[A9 Directed Evolution (OLD)#Recombination|Recombination]] – mutations made by recombination are less disruptive and generate more functional proteins than random mutations, as well as introducing many neutral mutations 
- Evolve multiple routes in parallel to avoid negative epistatic paths 
- Introduce neutral mutations and [[A9 Directed Evolution (OLD)#^47d2be|stabilising mutations]] 
	- The high frequency of neutral mutations suggests that there are many sequences with equivalent fitness, and protein evolution may occur on "neutral networks" 
	- Neutral mutations can create new starting points for subsequent adaptive evolution 

# Approaches for specific goals 
## Novel enzymatic activity 
- Instead of trying to achieve the desired product directly, try to choose intermediate target substrates 
	- #experimental_evidence Fasan et al (2007) evolved P450 fatty acid hydroxylase into a propane hydroxylase by first improving the existing weak activity on octane until there was sufficient side activity on propane.   ^803052
- Create a generalist enzyme with broader specificity before improving activity of the generalist 
	- #experimental_evidence Escalettes & Turner (2008) evolved galactose oxidase to increase its substrate range to include both D-glucose and 1-phenylethanol, and further directed evolution of this generalist improved its activity on 1-phenylethanol 
	- Intermediates along evolutionary pathways are often enzymes that accept a much broader range of substrates, suggesting a sequence of despecialisation of an efficient, specific enzyme -> a generalise enzyme as an intermediate -> respecialisation of the generalist. 
- New activities can also arise from neutral drifts 
	- #experimental_evidence Kurtovic et al (2008) – Recombination of homologous glutathione transferases (which results in intense neutral drift) produced new activities not observed in the parent enzymes 
- To obtain enzymes with new reactions not found in nature (as opposed to just new substrates), rational design can provide a useful starting point, e.g. by engineering a rudimentary active site that can bind the transition state with higher affinity than substrates or products 
	- Subsequent directed evolution on the designed enzyme can improve activity 
	- E.g. #experimental_evidence Rothlisberger et al (2008) used computational enzyme design to create a bad Kemp elimination enzyme, but improved its Kcat/Km after 7 rounds of directed evolution

### Effect of enzyme dynamics 
- Proteins are inherently dynamic as they are long polymers with many degrees of freedom and have many weak interactions 
- Do timescales of catalysis and motion. have to be coordinated?
- How much does conformational flexibility contribute to catalysis? 

## Increased specificity 
- Eliminate variants that maintain activity on the native or other undesired substrate using negative selection 
- Positive selection to improve desired activity 
	- Specificity can arise as a side result of selection for higher activity when interactions with new substrate interfere with recognition of old substrate (e.g. as occurred with [[A9 Directed Evolution (OLD)#^803052|Fasan et al (2007)]] – selection for propane activity via positive selection alone also led to high specificity) 

#experimental_evidence Evolution of highly specific endopeptidases using positive and negative selection via FACS (Varadarajan et al, 2008)

## Improving stability 
- Introduce neutral mutations (e.g. via recombination)
- Introduce compensatory stabilising mutations ("uphill divergence")
	- e.g. [[A9 Directed Evolution (OLD)#^47d2be|Wang et al (2002)]] introducing M182T into a beta lactam 
- Introduce ancestral mutations via ancestral inference and/or consensus analysis 
	- Mutations in conserved residues usually cause large declines in stability, while reverting residues to the consensus residue can increase stability ([[MitonEtAl_2021]])
	- Ancestor proteins can have higher stability, and at some positions the ancestral residues confer higher stability than the consensus 
		- [[MitonEtAl_2021]] argue that it is precisely the higher stability and evolvability of ancestor proteins that has allowed them to diverge downhill into modern, marginally stable proteins 
- Use chaperones 
	- Chaperons assist in folding of other proteins and buffer various effects of mutations 
	- #experimental_evidence Tokuriki & Tawfik (2009) reported that GroEL/ES chaperonin overexpression can buffer the effects of deleterious mutations such that they are effectively neutral, increasing the variability of mutations a protein can tolerate and doubling the number of improved variants obtained; this was done by performing neutral drifts under overexpression of GroEL/ES, then testing the mutants for the level of buffering and mutations. Without GroEL/ES overexpression, would not be able to obtain a *Pseudomonas* phosphotriesterase variant with F306L mutation that is highly destabilising but led to large improvement in newly evolving activity. 

![[Pasted image 20221229182552.png|325]]

# Natural selection vs directed evolution 
#comment Need to fill in 
| Criteria                | Natural selection                    | Directed evolution |
| ----------------------- | ------------------------------------ | ------------------ |
| Evolution trajectory    | Neutral drift                        | Adaptive walks     |
| Selection for stability |                                      |                    |
| Source of randomisation | Substitutions, indels, recombination | Natural + ITCHY    |
| Selection strategy      |                                      |                    |
| Effect of mutation      | Mostly deleterious                   | Mostly deleterious |

> [!image] Natural evolution vs DE ([[CurrinEtAl_2015]])
> ![[Pasted image 20230422121717.png]]

- Directed evolution can be used to understand natural selection by mimicking natural evolution but on a much faster timescale #experimental_evidence e.g. [[ZahradnikEtAl_2021]] used directed evolution to identify spike protein mutations that could makes SARS-CoV-2 more infectious if they were to arise in the circulating viral population 

# Mapping the fitness landscape with sequencing 
- We need accurate long-read sequencing 
- UMIC-Seq 

# Using DE to understand the role of protein dynamics in catalysis 

# Current challenges in DE field 
- Creating new approaches of library generation 
- New strategies for exploring sequence space 
- What brings about long, successful evolution campaigns. What can we learn from nature? 
- How are sequence and functional space connected? How can we predict function from sequence? 