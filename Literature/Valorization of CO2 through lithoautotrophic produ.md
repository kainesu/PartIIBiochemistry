# Valorization of CO2 through lithoautotrophic production of sustainable chemicals in Cupriavidus necator

Author: Nangle et al
Note type: Source
Reference: Nangle, S. N., Ziesack, M., Buckley, S., Trivedi, D., Loh, D. M., Nocera, D. G., & Silver, P. A. (2020). Valorization of CO2 through lithoautotrophic production of sustainable chemicals in Cupriavidus necator. Metabolic Engineering, 62, 207–220. https://doi.org/10.1016/j.ymben.2020.09.002
Source type: Journal

# Why C. necator as a system?

- Facultative Knallgas bacterium that deerives energy from H2 and carbon from CO2
- Genetically tractable
- Can be culutred with inexpensive minimal media components
- Non-pathogenic
- High-flux carbon storage pathway
- Fixes majority of fed CO2 into biomass
- Can be grown lithoautotrophically
    - "not limited by the thermodynamic and technological limitations of plant and cyanobacteria-based bioproduction systems"

How did they find out and select C. necator as a system for producing products 

# Aim of the study

- Produce feedstocks for heterotrophs from CO2 rather than from plant material to increase the sustainability of bioproduction
    - "While microbes hold promise for sustainable intensification of agriculture (Linder, 2019), the reliance of bioproduction
    on plants limits the global green economy—as issues of food
    security increase, the tradeoff between food and bioproducts will become increasingly difficult to make"
- Demonstrate that C. necator is versatile in producing different kinds of commercial produts
- Use C. necator to produce a plant growth enhancer to improve crop yields → reduce demand on agriculture to generate bioproducts

# Producing sucrose

- Engineer C. necator to express cyanobacterial sucrose synthesis enzymes and a sucrose porin to export the sucrose into the media
- Sucrose phosphate synthase (SPS) catalyzes conversion of UDP-glucose and fructose 6-phosphate into sucrose 6-phosphate
- Sucrose phosphate phosphatase (SPP) hydrolyzes the phosphate to yield sucrose.
- A limited density of C. necator was used to keep to laboratory H2 safety requirements and bc of culture conditions
    - However, in practice C. necator can be accumulateed to up to 90 g/L biomass
        - Would there be any toxicity issues?
            - Exporting sucrose from the cell via the porin would lower the inhibitive effects of product accumulation.

Why not a cell-free system? Would the enzymes work in solution? Or too unstable? Also I suppose cell system would allow for replication?

Would a fusion of SPS and SPP help to speed up the reaction? 

**How sucrose synthesis enzymes were chosen** 

- ****Compared titers from enzymes from different species e.g. *Anabaena cylindrica*, *Synechocystis sp.*, etc.
- *Synechocystis* enzymes were chosen as they produced the highest titers of sucrose

**Testing heterotrophs usage of sucrose produced by C. necator**

- Engineer E. coli and S. cerevisiae to have enhanced sucrose usage
    - Edit genes in E. coli
    - Directed evolution for S. cerevisiae under low sucrose conditions
- Engineered E. coli and S. cerevisiae grow in spent media from induced C. necator by two doublings, but did not grow when C. necator was not induced

**Co-culturing E. coli and C. necator**

- When engineered E. coli was co-cultured with induced C. necator, it grew to a higher density compared to wild type C. necator and uninduced engineered C. necator
- The growth of E. coli in co-culture exceeded the expected growth based on monoculture sucrose production by C. necator
    - Possibly, this is a case of a symbiotic heterotroph acting as a thermodynamic sink for feedstock production (see Hu et al 2016)
    - Co-culturing a heterotroph (E. coli) directly with a feedstock producer (C. necator) could be a way to enhance the heterotroph's growth and potential product yield
- It was also shown that E. coli can produce products (violacein, β-carotene) in co-culture with C. necator
    - This means that violacein and β-carotene were produced from CO2 and H2 as the sole sources of carbon, energy in the system!

Could E. coli and C. necator then be subjected to (directed?) co-evolution to further enhance this symbiotic relationship?  

# Producing polhydroxyalkanoate (PHA)

- C. necator was engineered to express thioesterases (TEs) with PHA synthases (phaCs)
- phaCs assemble the PHA polymer based on their intrinsic substrate specifities and enzymatic rates
- We can assemble bioplastics with tailored compositions by using different pHACs with variale specificities for different chain-length fatty acids via thioesterases
- Usually, PHA copolymers are produced from co-monomer precursors (e.g. saturated fatty acids)
- Instead of feeding these precursors, we can produce them in culture from the thioesterases

**How enzymes were chosen** 

- Two acyl carrier protein (ACP) TEs were selected – *U. californica* FatB2 (12:0 acyl-ACP TE) and an engineered chimera ("chim4") of *C. palustris* FatB1 (aa 1-218) and FatB2 (aa-219-316)
- Chim4 couples the specificity of CpFatB1 as a C8:0 acyl-ACP TE with the high activity of CpFatB2
    - Check out Ziesack et al 2018
- phAcs chosen were *P. aeruginosa* phaC1 and phaC2, *Pseudomonas spp 61-3* phaC1_Ps
- These TEs, along with the phaCs, could produce PHA copolymers **directly from CO2**

There seems to be some missing link here. How does thioesterase produce fatty acids from CO2? 

**Purification**

- PHA was purified via established NaClO- based protocols → methanolysis → gas chromoatography mass spectrometry analysis

**Further experiments with C. necator with FATB2_Uc, PhaC1_Pa**

- C. necator with vector control ΔphaC*Cn* (PAS827) (no native PHA synthase) did not produce detactable PHAs
- WT cells (PAS826) produced 100% poly(3-hydroxybutyrate) (3HB)
- Acrylic acid was also added to each case as it is a known inhibitor of 3-ketoacyl CoA thiolase in β-oxidation
    - Why specifically test acrylic acid?
- PAS828 (FatB2_Uc, phaC1_Pa) produced very little mcl-3HA (medium chain length hydroxy acids)
- PAS829 (ΔphaC_Cn, FatB2_Uc, PhaC1_Pa) produced much more (79.7% mcl-3HA) of which 64.5% was 3-hydroxyoctanoate (3HO)
- Acrylic acid dd not contribute significantly to PHA composition, and when added to PAS828, 3HO and 3HD levels decreased to undectable levels
- PAS829 produced a copolymer slightly enriched in longer-chain fatty acids when acrylic acid was added

**Further experiments with chim4 TE and phaC1_Ps**  

- PaS830 (Chim4, phaC1_Ps) produced 58.5% mcl-3HA, 48.9% of which is 3HO
- Pas831 (ΔphaC_Cn, Chim4, phaC1_Ps) – composition of mcl-3HAs compared to PAS830 was not as striking as PAS828 to PAS829 (produced 78.7% mcl-3HA with 62.6% 3HO)
- Acrylic acid had strongest effect on strain with native phaC, with accumulation of longer chain fatty acids
    - After addition of acrylic acid there was minor enrichment of mcl3HAs
    

Why Chim4 not used with PhaC1_Pa, and FATB2_Uc not used with phaC1_Ps? 

**Tuning different combinations of TEs and phaCs**

- phaC1_Pa was exchanged with paralog phaC2_Pa while maintaining UcFatB2
- PAS832 – 34.5% mcl-3HAs, 18.9% 3-hydroxydodecanoate (3HDD)
    - Addition of acrylic acid accumulated mcl-3HA to same extent as in PAS833 without acrylic acid
- PAS833 – 77.6% mcl-3HA, 42.5% hDD
    - Acrylci acid increased 3HDD formation

Why did they choose to focus on these particular polymers? 

Basically, three things they varied: 

- Combination of TE and phaCs
- Presence or absence of native phaC1_Cn
- Addition of acrylic acid (β-oxidation inhibitor) → presumably to change the length of the PHA

# Producing lipochitooligosaccharides

- LCOs are a plant growth enhancer
- Enzymes required: NodC (N-aetylglucosaminyltransferase to build LCO backbone), NodB (deacetylase for non-reducing end), NodA (acetyltransferase that attaches a fatty acid)
    - These 3 enzymes can produce a basic LCO – 5-acylated chitin backbone, oleic acid at the non-reducing terminal N-acetylglucosamine monomer
    - Named "Nod Cn-V (C_18:1)"
- The LCO was purified with HPLC and applied to seeds of different plant species, then studied germinate rate
    - Engineered LOC increased germination % for spinach but not corn, soybean
    - Sprout weight increased for spinach, corn
    - Corn yield also increased in greenhouse crop growth experiments
    - Outperformed leguminous Nod Bj-V control

# **New methods**

- Conjugating a plasmid from E. coli into C. necator
- ucrose counterselection?
- Plant culturing