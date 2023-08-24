# RNA targeting with CRISPR-Cas13

Author: Abudayyeh, O., Gootenberg, J., et al.
Note type: Source
Project: RNA editing
Source type: Journal

- Evaluated 15 Cas13a orthologues for protospacer flanking site (PFS) preference using an ampicillin resistance assay
    - Assay monitors Cas13 mediated cleavage of the ampR (β lactamase) transcript — the less colonies that survive, the higher the activity
- Analysis of sequenced PFS distributions from LwaCas13a showed that most LwaCas13a PFS sequences were depleted
- LwaCas13a retains in-vitro cleavage activity with spacer lengths as short as 20nt, and may retain binding activity below 20nt
- Can Cas13a cleave transcripts in mammalian cells?
    - Cloned mammalian codon-optimized LwaCas13a into mammalian expression vectors with msfGFP fusions on C or N terminus and either a dual-flanking nuclear export sequence or nuclear localization sequence to evaluate expression and localization
    - msfGFP-LwaCas13a expresses well and localizes effectively to cytoplasm or nucleus according to localization sequence
- What is the in vivo cleavage activity of LwaCas13a?
    - Using a dual luciferase reporter system — *Guassia* luciferase (Gluc) and *Cypridinia* luciferase (Cluc) under different promoters on the same vector
    - One transcript acts as the LwaCas13a target and the other as a dosing control (i.e. a control to normalize for dose)
    - LwaCas13a-msfGFP-NLS had highest level of knockdown (lowest luminescence), and knockdown level was comparable to position-matched short hairpin RNA controls
        - short hairpin RNA acts as a control for accessibility and sequence in target region
    - Knockdown is most efficient with spacer length of 28nt and is dose-responsive to input protein and guide vector amounts
- Knockdown can be abolished by mutating catalytic domain of LwaCas13a
- Evaluate range of efficiency of LwaCas13a knockdown (of target) by tiling guides along the length of 4 transcripts
- LwaCas13a knockdown compared to RNAi by comparing top 3 guides with position-matched shRNAs
    - 5/6 top guides had higher levels of knockdown
- Target accessibility affects targeting efficacy
- LwaCas13a can process its own pre-crRNA, possible to streamline delivery of multiplexed LwaCas13a guides
    - Targeting system delivered as a CRISPR array with 28 nt guides flanked by 36 nt direct repeats
- LwaCas13a specificity is sensitive to mismatches between the guide and target RNA — when mismatches are introduced into gRNA, knockdown efficiency falls
- Transcriptome-wide mRNA sequencing performed to search for off-target effects of LwaCas13a knockdown
    - LwaCas13a had much lower off-site targeting than shRNA
- Lack of collateral RNA degradation as suggested by multiplexed leave-one-out and RNA-sequencing analyses
- Catalytically dead LwaCas13a (dLwaCas13a) is created and binding quantified using RNA immunoprecipitation
    - Could be used as a transcript imaging platform
        - To reduce background noise due to unbound protein, a negative feedback system was incorporated that uses zinc finger self-targeting and KRAB domain repression — unbound fusion protein binds to transcript to repress further transcription.