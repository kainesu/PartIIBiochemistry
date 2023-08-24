# Programmable base editing of A•T to G•C in genomic DNA without DNA cleavage

Author: Gaudelli, N. M. et al
Note type: Source
Project: Base editing
Source type: Journal

Creates a base editor to convert A to G. 

- Evolve an adenine deaminase that converts A to I in DNA via a bacterial selection method
    - Transfect plasmids into bacteria with defective antibiotic resistance genes — contain point mutations
    - If the base editor act on DNA, then the mutation will be reversed, restoring antibiotic resistance
    - Bacterial codon-optimized BE2 was used (APOBEC1 cytidine deaminase-dCas9-UGI)
    - Defective CamR with AT to GC mutation was successfully rescued by BE2
    - Selection plasmid was then adapted for ABE activity by introducing a CG to TA mutation in CamR
    - *E. coli* TadA (ecTadA) used as a starting point for evolution
        - TadA converts A to I in single stranded RNA (ss loop of tRNA-Arg)
        - TadA does not require small molecule activators
        - TadA also can act on polynucleic acids
    - Colonies that exhibited antibiotic resistance had TadA strongly enriched for A106V and D108N mutations
        - From sequence alignment of ecTadA to *S. Aureus* tadA, D108 forms hydrogen bonds with 2'-OH group of ribose in a uracil upstream of the adenine substrate → mutating this would make binding to RNA less stable ⇒ lower energetic "opportunity cost" in binding to DNA
- Mammalian codon-optimized evolved TadA-nCas9 fusion construct created with a C-terminal nuclear localization signal (to localize construct to nucleus)
    - XTEN used as the linker (so construct is TadA-XTEN-nCas9-NLS)
    - Low but observable AT to GC editing was observed at six human genomic target sites
- To improve editing efficiency, an unbiased library of TadA*-dCas9 variants was created and further evolved under higher concentrations of chloramphenicol
    - D147Y and E155V identified
        - Predicted to lie in a helix adjacent to the TadA tRNA substrate
- Fusing TadA(2.1) to C terminus of nCas9 instead of N terminus abolishes editing activity
- Increasing the length of the linker to 32 amino acids increased editing efficiency somewhat
- Alkyl adenine DNA glycosylase (AAG) may impede ABE performance by cleaving the glycosidic bond of inosine
    - To test whether this occurs, ABE2 variants were created by fusing ABE2 to inactivated versions of enzymes involved in inosine binding (human AAG) or removal (ec Endo V)
    - However, neither fusion had altered AT to GC editing efficiency
- Editing efficiency was further improved by fusing an additional evolved or wt TadA to N terminus or through co-expression of TadA or evolved TadA with ABE2.1; directly fusing evolved TadA to N-terminus ABE2.1 improved editing efficiency the most
    - This is likely because TadA natively operates as a homodimer — one monomer catatalyzes deamination and the other acts as a docking station for the tRNA substrate
    - Introducing a second TadA unit minimizes reliance on intermolecular ABE dimerization
- Which of the two TadA* subunits is responsible for catalysis?
    - An inactivating mutation was introduced into either the N-terminal TadA* or internal TadA*
    - Variant with inactivated N-terminal TadA* retained comparable catalytic activity, while variant with inactivated internal TadA* lost all editing activity ⇒ internal TadA subunit is responsible for catalysis
- To further increase editing efficiency, third round of bacterial evolution initiated
    - Selection stringency increased by introducing two early stop codons (Q4stop, Q15stop) into KanR gene
    - Stop codons can only be corrected via an AT to GC reversion
    - Library of TadA*-2.1-dCas9 variants subjected to selection
    - Enrichment of 3 new TadA mutations: L84F, H123Y, I157F
- ABE3 have context preference — editing efficiency is higher at certain motifs (e.g. CAC) but not others (e.g. GAG)
    - Prefer editing at YAC (where Y is T or C)
    - This preference probably inherited from native ec TadA which deaminates adenine in UAC anticodon of tRNA(Arg)
- To overcome context preference, 4th round of evolution initiated by focusing mutagenesis on TadA residues that were predicted to interact with the nucleotides upstream and downstream of the target A
    - Selection criteria: Library of variants must convert a non-YAC target (GAT) to restore antibiotic resistance
    - Enriched mutation of A142N
    - While in bacterial cells this mutation resulted in higher editing efficiency, in mammalian cells editing efficiency was lower than 3rd generation ABE
    - 5th round of evolution to increase ABE performance and broaden target sequence compatibility
        - Subject variant library to CamR H193Y selection (i.e. must repair H193Y to restore antibiotic resistance), using higher doses of chloramphenicol *and* only allowing ABE to be expressed for half the duration of previous rounds of evolution — select for ABEs with faster kinetics
        - Consensus set of mutations: H36L, R51L, S146C, K157N
        - But when these mutations were introduced into ABE3.1, they also decreased overall editing efficiency in mammalian cells
- Possibly, while the accumulation of mutations improves catalytic activity, it worsens the structural docking activity of TadA
    - In a homodimer, one TadA has a catalytic role and the other has the docking role — the E. coli may have had higher editing efficiency as it endogenously expresses wt TadA without the mutations that could perform the docking role
    - What if the TadA* subunit responsible for docking (i.e. N terminus TadA) was replaced with wt TadA? This construct had much improved editing efficiency
- A library of this heterodimer was subjected to the non-YAC target selection.
    - Two mutant genotypes emerged: N72D + G125A and P48S + S97C
- 6th round of evolution: remove any non-beneficial mutations and detect any previously undetected beneficial mutations through DNA shuffling
    - some beneficial mutations may have been masked by negative epistasis with other mutations
    - Evolved TadA*-dCas9 variants from each of the previous 5 rounds of evolution were shuffled along with wt TadA and selected for spectinomycin resistance
    - This enriched two mutations P48S/T and A142N
    - ABE6.3 (ABE5.3 + P48S) had highest editing efficiency
    - P48 predicted to lie near substrate adenosine 2'-OH in TadA structure; mutating P to S may improve compatibility with deoxyadenosine
    - Also found that ABEs containing A142N improves editing of adenines closer to PAM than at position 5
- 7th round of evolution: to overcome ABE6 editors reducing editing efficiencies at target sequences with multiple adenines near targeted A
    - New unbiased libraries of TadA*6 targeted to KanR (Q4stop - TAT and D208N - TAA)
    - Enriched mutations: W23L/R, P48A, R152H/P
    - Introducing these mutations separately or together into ABEs improved editing efficiency especially at targets with multiple As
    - R152P residue predicted to contact C in UAC anticodon loop of tRNA substrate — substitution of R for P may remove base-specific enzyme-DNA interaction → broaden target sequence compatibility

**Characterizing late stage (5-7) ABEs**

- Used 17 human genomic targets with target A at position 5 or 7 of protospacer, which includes all possible NAN sequence contexts
- Editing efficiency increased from ABE5 to ABE7
- To determine the base editing activity window, a human genomic site was chosen with an alternating 5'-ANANAN-3' such that it can be targeted with either of two sgRNAs that either place an A at every odd position or at every even position in the protospacer
    - Activity window is 4-6 nucleotides wide
    - Precise editing window boundaries varies from target to target
- Late stage adenines edit nearby adenines more processively, while early stage ones edited adenines more independently
- Indel frequencies are very low, similar to untreated cells
    - May be due to activity or abundance of inosine excision enzymes being low compared to UNG → minimal base excision repair
- To detect off-target edits, it was assumed that off-target ABE editing occurred at the same off-target sites as Cas9 nuclease
    - ABE7s produced less off-target editing at only 4/12 of the known Cas9 off-targets
    - At the loci where Cas9 had off-target editing, editing efficiency was higher than the loci where ABE had off-target editing
    - At the loci where Cas9 had off-target editing, although 7 of these had at least one adenine within the ABE activity window, 3/7 were not detectably edited by ABE7s
    - In general ABE7 variants less prone to off-target genome modification than Cas9 nuclease
- ABEs do not edit RNA at a detectable level
- No apparent ABE toxicity

ABE7.10 best for general A•T to G•C base editing. When the target adenine is at
protospacer positions 8–10, ABE7.9, ABE7.8, or ABE6.3 may offer higher editing efficiencies than ABE7.10, although conversion efficiencies at these positions are typically lower than at protospacer positions 4–7. 

# Reference

Gaudelli, N. M., Komor, A. C., Rees, H. A., Packer, M. S., Badran, A. H., Bryson, D. I., & Liu, D. R. (2017). Programmable base editing of A•T to G•C in genomic DNA without DNA cleavage. Nature, 551(7681), 464–471. [https://doi.org/10.1038/nature24644](https://doi.org/10.1038/nature24644)