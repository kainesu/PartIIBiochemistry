**To what extent is it possible to use mass spectrometry to systematically identify and study the protein complement within a cell? How might one best go about this?**

# **Intro** 
* MS is a powerful tool for studying proteomics 
* Has various applications, including identification, quantification, structural determination, localisation, and understanding protein dynamics and interactions 
    * Classical proteomics (identification and quantification) vs structural proteomics 
* However, MS is not an all encompassing tool and knowledge of its limitations is also important to know when best to use it 
* The best use of MS depends on the particular research question, nature of the protein(s) being studied, and other contextual factors that will be elaborated on below 

# 1. General principle of MS  

* Although there are various MS techniques, all rely on the general principle of measuring the m/z of ions that pass through the analyser 
* An ioniser converts the protein or peptide into an ion – this is usually via soft ionisation methods such as matrix assisted laser desorption/ionisation (MALDI) or electrospray ionisation (ESI) that do not fragment the molecules but generally retain the covalent bonds within the molecule 
* The analyser than measures the mass to charge ratio of the molecule, which could be via time of flight, or using quadripoles or orbitraps
* The quantity of the ions is measured by the ion detector 
* A mass spectrometer thus produces a _mass spectrum_ where the position of each peak corresponds to its m/z ratio, and the height correlates to quantity 

# 2. Using MS to identify proteins in a complement 

* Molecules can be identified by their m/z ratio. If the charge on the ion is known, then the mass can be calculated, and the experimenter is able to work out what combination of atoms or subunits within the molecule can explain the mass observed 
* Similarly, proteins can be identified by their m/z ratio. However, proteins are generally too large to have their mass measured via time-of-flight. Moreover, many proteins have very similar masses, and their isotopic envelopes often overlap with other proteins, making it difficult to distinguish between proteins especially when there are many different ones in a cell 
* As such, proteins generally have to be digested into peptides using trypsin before being fed into the mass spectrometer 
    * The reason trypsin is used is that it always produces peptides with a Lys or Arg at the C terminus, which have charged R groups, ensuring that the peptide can be ionised 
*  If all peptides from the cell’s proteome were fed into the MS at the same time, the resultant mass spectrum would probably be too complicated to interpret. To simplify interpretation, peptides are generally separated via a top-down or bottom-up approach
    * Top-down (protein-centric): Proteins are separated before enzymatic digestion using SDS-PAGE or even 2D-PAGE (which involves additional isoelectric focusing). After separating the proteins, ionise individual proteins intact and generate peptide fragments in MS 
    * Bottom-up (peptide-centric): Without separating the proteins, digest proteins and do LC-MS 
    * LC separates the peptides based on their hydrophobicity 
* This would provide the mass spectrum of peptides. This mass spectrum can be provided to a database to identify the proteins present (or use other computational methods). In this way, the peptides act as a surrogate for the parent protein, since the protein is identified from a subcomponent rather than using its overall structure 
* For sequencing of the primary structure, can further do tandem MS/MS to break the peptide down into its constituent amino acids, which can provide more precise information on protein identity 
    * E.g. Belov et al (2013) used this method to identify the protein components of several complexes, including phosphorylase B and GroEL, by mapping peptide fragments obtained in MS3 back to the protein sequences of each complex 
* Limitations
    * Protein inference problem – with bottom up proteomics, we cannot be certain what the specific precursor protein of the peptides are
        * Particularly a problem if the protein has different isoforms (e.g. post-translational modifications) that could produce the same surrogate peptide 
        * Sometimes PTMs are lost as well (if the peptide containing the PTM is not detected) – due to dissociation or fragmentation? (breaking of covalent bond) 
        * May also have difficulty separating homologous proteins with similar sequences, which produce degenerate peptides 
        * This can be resolved with top down proteomics which retain the PTMs 

# 3. Quantitative proteomics

* Many methods to do this 
* Simplest way – label free 
    * Extracted ion chromatogram 
    * Label-free quantitation 
    * Intensity-based absolute quantification (IBAQ) algorithm 
* Labelling allows for multiplexing i.e. quantifying proteins from different cell samples or lines, or to quantify over time 
    * SILAC – stable isotope labelling of amino acids in cell culture 
        * Variant – Super SILAC 
        * E.g. Mathieson et al (2018) – SILAC to measure protein turnover 
    * Stable isotope labelling in vitro 
    * Isobaric labelling 
        * Principle
        * E.g. Chick et al (2016) 
* Limitations 	
    * Again, cannot differentiate between isoforms, so cannot use this to quantify different isoforms… 
    * Have to assume that surrogate peptide quantity correlates well with the actual protein abundance in the cell? 
    * General limitation is the multiplexing limit, quantification accuracy and proteome coverage
        * Label-free methods generally less accurate than labeling methods 
        * Stable isotope labelling has limited multiplexing ability compared to isobaric labels (limited by number of isotopes in existence)
            * If labelling in vivo, cells have to be metabolically active 
        * On the other hand, the higher plex methods can’t be done in vivo 

# 4. Structure and protein dynamics 

* Structure 
    * Primary structure can be obtained via peptide sequencing, easier if protein can be purified first via 2D PAGE 
    * Higher order structures rely on native MS, which maintains the structure of the protein 
        * Use soft ionisation techniques, compatible buffers, optimised parameters to minimise denaturation and preserve noncovalent interactions
        * For membrane proteins, need to remove the bound membrane mimetic; incomplete removal lowers resolution  
    * Solvent accessible vs buried residues can be differentiated using HDX
        * Principle
        * Example
    * Secondary structure
    * Post-translational modifications 
    * Limitations – can’t get 3D structure easily
* Protein complexes (see other essay) 
    * XL-MS used in topology determination (arrangement of subunits in complex) 
        * E.g. XL-MS – used to help elucidate stacking arrangement of Rvb1/Rvb2 subcomplex in INO80 complex 
    * Subunit stoichiometry gained from native MS, shotgun MS can complement XL-MS and cryo-EM data 
* See [dynamics](https://docs.google.com/document/d/10N-271yXfy4jqhulSpuH9ZwmPiqODiHIfL648kuUbdg/edit)

# 5. Protein interactions and localisation 

* Identifying interacting partners
    * Native MS – for protein complexes and ligands 
        * Can relate different sequence polymorphisms or PTMs or isoforms to the protein complex it is in (unlike classical proteomics) 
            * E.g. Ben-Nissan et al (2017) – Used to identify two mutually exclusive phosphorylation sites in yeast fructose-1,6-bisphosphatase 1 
        * Provides direct evidence of interaction (unlike denaturing methods) 
            * Choice of activation technique used in native top-down is important – e.g. Using electron capture dissociation, can cleave polypeptide backbone bonds while preserving non-covalently bound ligands 
        * Particularly useful for characterising membrane protein-ligand binding 
            * E.g. Bolla et al (2018) Lipid binding to MurJ flippase is influenced by antibiotics  
                * When lipid is bound to MurJ, m/z of peak increases 
                * Used native MS to detect lipid II binding to MurJ. Ramoplanin disrupts lipid II binding, while vancomycin forms a ternary complex with MurJ and lipid II. 
* Cross-linking MS – Proteins cross-linked using DSSO, introduced into MS/MS, cross-linker breaks and masses of the two proteins can be measured and used to identify the proteins 
    * E.g. Vasilescu, Guo & Kast (2004) 
    * Also can be used to identify subunit connectivity 
* AP-MS 
    * Principle 
    * Example
    * Generate interaction networks from reciprocal AP-MS 
    * Limitations
        * Antibodies against endogenous proteins are of limited availability → use epitope tags, but could interfere with protein interactions/localisation 
        * Antibodies can exhibit cross-reactivity 
        * Validation required 
* Global interactome profiling 
    * Co-behaviour in biochemical fractionations (e.g. size exclusion chromatography, ion exchange chromatography) 
        * Requires extensive fractionation
            * May disrupt weaker and transient interactions
        * Possible that functionally unrelated complexes co-elute 
        * Quantification across fractions has to be consistent 
        * E.g. Wan et al (2015) – used fractionation + LC-MS/MS to study conservation of PPIs in diverse metazoan species 
    * Co-behaviour in perturbation experiments 
        * Proteins that co-behave in an assay may be functionally related or interact
        * Thermal proteome profiling 
            * Has been used to study membrane proteins, so could be used to profile membrane PPIs, which are difficult to study with AP-MS 
            * But it cannot distinguish between physical and functional PPIs
* Limitations
    * Requires high proteome depth, advanced bioinformatic analysis 
    * Average picture of protein interaction, may not capture changes in protein interaction over time/context (unless there is some experimental setup) 
* Identifying interacting surface 
    * HDX 
        * Principle
        * E.g. 
* Protein localisation 
    * Basis is identify proteins in the vicinity of the protein, but this usually will capture interacting partners as well 
    * Location of protein identified based on location of proteins it is close to 
    * Protein correlation profiling and LOPIT 
    * Proximity tagging 
        * BioID 
        * APEX labelling 
    * Can also be multiplexed with stable isotope labelling methods (e.g. SILAC) 
* Can be combined with quantitative methods to measure stoichiometry of interacting partners and interaction dynamics 
    * E.g. iBAQ can be applied to AP-MS data 
        * E.g. used to quantify human SET1/MLL complexes 

# 6. How might one best go about using MS to study protein complement? 

* Best way is to choose a method that provides the most information that can answer the particular research question, as accurately and as high throughput as possible, as easily as possible 
* Probably multiple MS techniques will be needed – classical + structural proteomics 
    * Classical proteomics -> identify and quantify proteins and different isoforms (including PTMs via top down approach) 
    * Native MS -> stoichiometry, co-occurring assemblies, ligand binding 
    * E.g. Yang et al (2016) – Native MS used to detect and quantify glyco-proteoforms for different proteins in human blood serum. Then, use bottom-up proteomics to identify heterogeneous glycosylations and locations of glycosylation.  
* Factors affecting choice of method
    * Need for multiplexing 
* Can all proteins be studied with mass spec? 
* Can all aspects of a protein be studied with mass spec? 
* Limitations 
    * Throughput 

# 7. Conclusion 

* Usefulness of MS will increase with advances in data analysis methods and sample separation methods
    * E.g. 125 endogenous complexes identified from mouse heart, human cancer cell lysates → usefulness in novel protein or complex discovery 
    * Also development of fully “online” approaches to automate sample preparation 
* MS is just one tool, cannot be used on its own to fully understand all proteins in the cell 
    * Need complementary approaches e.g. NMR, X-ray crystallography 
    * E.g. Snijder et al (2017) used native MS, cross-linking MS and cryo-EM to elucidate assembly of cyanobacterial circadian clock (called the Kai system) 
        * Stoichiometry and assembly dynamics of KaiA, KaiB, and KaiC was measured with native MS 
        * Complexes were structurally characterised via single particle cryo EM 
            * Architecture was confirmed with cross-linking experiments 
* However, where MS proves superior/has niche in is high throughput interaction, identification and sequencing (?). There are better tools for dynamics. Also hard to get a 3D structure from MS alone. 
* Applications
    * Biomarkers
    * Species identification 
    * Environmental MS (?) 