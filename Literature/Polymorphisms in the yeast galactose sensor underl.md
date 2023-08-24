# Polymorphisms in the yeast galactose sensor underlie a natural continuum of nutrient decision phenotypes

Author: Lee, K.B. et al
Note type: Source
Reference: Lee, K. B., Wang, J., Palme, J., Escalante-Chong, R., Hua, B., & Springer, M. (2017). Polymorphisms in the yeast galactose sensor underlie a natural continuum of nutrient-decision phenotypes. PLOS Genetics, 13(5), e1006766. https://doi.org/10.1371/journal.pgen.1006766
Source type: Journal

TLDR: Genetic variation in yeast galactose sensor result in different ways the yeast respond to changes in nutrient levels in their environment. 

# Abstract (TLDR)

- When cells decide which nutrients to use, they decide based on their own preferences and what’s available
- These preferences are genetically encoded. Different cells have different preferences because of variation in the underlying genes.
- The authors varied the amount of glucose and galactose in the environment and found that the sugar concentration at which cells decide to express galactose-responsive (GAL) genes is different across 36 different yeast (S. Cerevisiae) strains
- They used bulk segregation analysis (crossing phenotypically different strains) and allele replacements to determine that variation in the *GAL3* galactose sensor gene was responsible for differences in *GAL* expression
- This sensor allows cells to “perceive” the environment
- *GAL3* does this by modulating diauxic lag (I.e. time required for cells to switch from using glucose to galactose) which is a selectable trait

# Background

- Cells exist in environments where they can choose from a variety of nutrients
- Cells can vary in which nutrients to use and the efficiency at which they use them
- But they are selected to optimize the use of nutrients in their environment
- When cells make decisions about which nutrients to use, they detect what nutrients are available via signaling pathways
- They can then change their behavior by activating different transcriptional networks via transcriptional regulators/factors
- Different species have big differences in which genes and sites are bound by the same transcriptional regulator, and even in the regulator itself
- The process of decision making, involving signaling pathways and regulatory networks, can evolve over time

# Methods

## Determining glucose/galactose concentration at which GAL pathway is induced

- Measure GAL1promoter-YFP reporter response in different concentrations of glucose against a background of constant galactose concentration
- YFP fluorescence measured by flow cytometry
- All query strains were co-cultured with a reference strain to account for well-to-well variability and variability in glucose titration
- The decision threshold is defined as the concentration at which 50% of cells have greater-than-basal expression of GAL pathway
    - Reflects WHEN a cell decides to induce pathway rather than HOW STRONG the response is once induced

## Bulk segregation analysis used to identify which gene is responsible for variation in the decision threshold

1. Eight strains of diverse phenotype and phylogeny were crossed in a round-robin style to sample the genetic variation in the parental strains
    1. If we cross all possible pairs of a range of different strains, we should get progeny with a wide range of genotypes 
2. From the progeny produced, pick the 5% least and 5% most induced cells via FACS 
3. Sequence each group in bulk to determine the parental allele frequencies in each pool 
4. Use MULTIPOOL software to determine which alleles had a statistically significant difference in frequency between the two groups 
    1. LOD score is a measure of the statistical significance — higher LOD score ⇒ greater significance 

Νone: The basis of this technique is that this creates two groups of individuals with extremely opposite phenotypes. Then analyze if the frequencies of any alleles are significantly different between the two phenotypes. 

E.g. we want to find out what allele contributes to height. We can compare the genes of a group of really tall people and really short people. Tall people may tend to have allele A while short people tend to have allele B. So we can say that allele A contributes to height. 

BSA is a way to *generate* the pool of tall ppl and pool of short ppl and then analyze them. 

[https://www.wikiwand.com/en/Bulked_segregant_analysis](https://www.wikiwand.com/en/Bulked_segregant_analysis)

# Results

## TLDR

- When glucose levels are high, yeast cells repress the GAL pathway as glucose is preferred as a carbon source
- When only galactose is present, cells activate GAL genes
- But when both glucose and galactose is present, cells have a more complex response and have to check the ratio of glucose and galactose
- The glucose concentration at which cells induce GAL genes can vary a lot between different yeast strains
- A large proportion of this variation can be explained by differences in *GAL3* alleles
- *GAL3* affects the length of diauxic lag which in turns affects the threshold for switching nutrient usage in yeast
- Since diauxic lag is known to be a selectable trait, this means that nutrient decision making in yeast can be affected by selective pressures.

## Longer

- Roop eat al and Peng eat al also studied the GAL pathway, and found that other GAL pathway genes may underly variation
    - A reason for the different results could be because the other studies compared different species of Saccharomyces, while Lee et al compared different *S. Cerevisiae* strains — differences in evolutionary distance
    - There is a hypothesis that on short timescales, phenotypic changes are more likely to be caused by nonsynonymous coding sequence mutations that are more pleiotropic, while at longer timescales, *cis* regulatory mutations are enriched that are less pleiotropic
        - But the authors didn’t really find any difference in pleiotropy between the genes identified
    - Another possible reason could be that the other authors studied different phenotypes which are controlled by different GAL pathway components
        - But the authors believe that the phenotypes should be highly correlated
- Variation in the GAL pathway is likely to be due to selection and not drift
    - GAL pathway has undergone selection between *S. Cerevisiae* and *S. Bayanus*
    - Several genes in GAL pathway in *S. Cerevisiae* are enriched for nonsynonymous polymorphisms ⇒ genes are under purifying selection
    - GAL3 variation is the main driver of phenotypic variation despite there being many mutational targets in the GAL3 pathway
- GAL3 alleles affect specifically the glucose-galactose diauxic lag and not lag between other carbon sources
    - In natural environments, mutations that affect all types of diauxic lag are more detrimental than more specific ones
- A trait can be affected by multiple pathways. Genes both inside and outside the pathway of interest can affect the trait.
    - While swapping the GAL3 allele between yeast strains can make their decision-making more similar to each other, there is still some variation. This difference can be attributed to other pathways outside of GAL3.
- There is a possibility that GAL3 specifically affects the decision threshold while other members of the GAL pathway affect other aspects of the broader phenotypic response e.g. diauxic lag — future work needed.
- Authors also found examples of epistasis in the GAL pathway
    - In some yeast strains tested, allele replacements did not affect decision making that much, while it significantly affected in other strains
    - Also, the authors found a “maximum” achievable decision threshold of 1% glucose in 0.25% galactose. If GAL3 alleles with decision thresholds above 0.25% glucose in 0.25% galactose are inserted into a strain with such a high decision threshold, GAL3 allele effect doesn’t raise the threshold by too much (presumably background pathways have already raised the threshold to quite a high level)

# Questions

- Phenotypic plasticity? — this is controlled by transcriptional regulation.
- Interesting that the abstract states that ecological constraints —> variation in protein. Do they mean ecological constraints in different environments? If its the same constraints, we should expect directional selection and that proteins are the same.
- Why use the YJM978xBC187 hybrids to determine the contribution of GAL3 allele variation to phenotypic variation