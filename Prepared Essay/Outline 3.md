26 Dec 2022
#comment 
- Does this outline the question? Refer to dissertation grading criteria
	- Nuance 
	- Detail (Experimental detail? Biochemistry detail?) 
- Also, need to go back and look for the primary source of some of these facts. 
- Indicate in outline where diagrams would be useful, especially in cutting down words 
- Make sure each point is supported by experimental evidence 
- Merit and criticism should be awarded to the findings from the scientific literature to demonstrate judicious use of the literature 

**Methane is a far more potent "greenhouse gas" than CO2. Can biochemistry assist in the long-term control of methane levels in the atmosphere?**
In this essay I argue that, biochemistry does have the potential to contribute to the long-term reduction of methane levels, however more research has to be done on the long-term effects, unwanted side effects, and scalability of certain solutions for them to be fully deployable in the field. Some solutions, while proven as a concept, may take too long to develop fully to address the current climate emergency. 

# Context 
- What is the effect of methane on the atmosphere
- How much more potent is it as a greenhouse gas than CO<sub>2</sub>
	- Methane is 84 times more potent than CO<sub>2</sub> in the first 20 years after release, and 28 times more potent after a century (in terms of Global Warming Potential) ([[JacksonEtAl_2019]]])
		- #citation Review 
		- #comment Explain what is global warming potential 
	- 2020 saw the largest annual increase in atmospheric CH4 since 1983 when systematic measurements started ([NOAA, 2021](https://research.noaa.gov/article/ArtMID/587/ArticleID/2742/Despite-pandemic -shutdowns-carbon-dioxide-and-methane-surged-in-2020))
	- 6th Assessment Report of Working Group 1 of Intergovernmental Panel on Climate Cange called for "Strong, rapid, and sustained reductions in methane emissions"
- A brief overview of the global methane budget – major sources and sinks 
  https://www.wikiwand.com/en/Atmospheric_methane#Media/File:The_Global_Methane_Budget_2008%E2%80%932017.png
	- Anthropogenic CH<sub>4</sub> emissions represent about 60% of the global total of ~560 Tg per year, and of these emissions, agricultural and fossil fuel sources are the main culprits. ([[JacksonEtAl_2019]])). The main sources of methane emissions from agriculture are enteric fermentation, manure, rice paddies, and residue burning ([[SmithEtAl_2021]])
		- #citation Review (both Jackson et al and Smith et al)
		- #comment [[MingEtAl_2022]] has a different figure, stating that instead, most anthropogenic methane emissions are from agriculture and *waste management*, rather than fossil fuel sources. Need to deconflict – perhaps refer to [[SaunoisEtAl_2020]] 
		- #question Of the agricultural emissions, how much is from livestock vs rice paddies?
	- #comment Include a diagram here. 
- What is "long-term methane control", and why it is important to control the levels of methane in the atmosphere 
	- Reducing methane levels to pre-industrial levels permanently 
	- Precisely because it is more potent as a greenhouse gas that it may be more efficient to tackle global warming by removing methane, since each unit of methane contributes more to global warming than CO<sub>2</sub> 
	- Removing methane has other benefits, including reducing ozone layer depletion (Revell 2016), reducing the risk of fire and reducing smells at landfills ([[Nisbet-JonesEtAl_2022]])
		- #citation Nisbet-Jones = review 
- To what level do we want to control methane at? 
	- The pre-industrial level of methane is ~750 ppb ([[JacksonEtAl_2019]]) 
	- Reducing methane concentration to that level could remove one sixth of total radiative forcing, reducing short-term warming to buy more time for the removal of longer-lived greenhouse gases such as CO<sub>2</sub> ([[JacksonEtAl_2019]])
		- #citation Review 
- Methane levels in the atmosphere can either be controlled by 
	- Reducing primary methane emissions at the source
		- Methane has a much shorter half life than CO<sub>2</sub> in the atmosphere of about 10 years, due to natural processes that remove methane from the atmosphere ( #question such as?). ==Methane oxidises into water and CO<sub>2</sub> in the atmosphere via... ?==  ^d69342
		- As such, artificial removal methods are unlikely to play as big of a role in methane control as in CO<sub>2</sub> control, since methane is already being removed relatively rapidly from the atmosphere. In fact, to significantly enhance natural processes, methane removal methods would need to be rapid enough to process the entire atmosphere in less than 10 years to compete with natural processes. However, should there be a massive increase in emissions from permafrost due to climate feedbacks (e.g. destabilisation of seafloor methane-hydrates, melting of Arctic permafrost) ([[MingEtAl_2022]]), artificial methane removal may be necessary to supplement natural processes. ([[Lackner_2020]])
	- Removing existing methane in the atmosphere 
		- [[AbernethyEtAl_2021]] showed that removing methane can help to alleviate global warming using an Earth Systems model. 

```mermaid
graph TD
id1(Sources)
id2(Methane in atmosphere)
id3(Sinks)

id4.1(Natural)
id4.2(Artificial)

id4.2.1(Biological)
id4.2.2(Chemical)
id4.2.3(Mechanical)

id1-->id2-->id3
id3---id4.1 & id4.2
id4.2---id4.2.1 & id4.2.2 & id4.2.3

````
- Various strategies exist for methane control, largely classified into biological, chemical, mechanical 
- `*` Insert various problems about non-biological solutions here `*`
- However, biochemistry may offer opportunities for effective, long-term control of methane levels via the following approaches 
	- Engineered methanotrophic bacteria 
	- Reducing enteric emissions 
- However, there are also important caveats and unknowns in current biochemistry-based solutions, necessitating further research in order for biochemical solutions to 
- To evaluate the ability of biochemical solutions to achieve long-term methane control, we will consider the following parameters 
	- Effectiveness at reducing methane levels in the atmosphere (whether by reducing methane emissions or removing methane from the atmosphere)
	- Long-termism 
	- Economic cost
	- Environmental impact 
	- Technological maturity (ranging from blue sky concepts to commercially practiced activities) – term borrowed from [[PrattTate_2018]]
	- Versatility/adaptability (?) – can it be used in different environments
	- Energy requirements 
	- Co-benefits 
	- Equitability (can we expect low income regions to use this method as well?)
	- Etc etc 

#comment Include a nice summary picture here. 
I think it could be similar to the one in my EEC report on GHGs? That I reproduced from a paper. 

# Approaches 
#comment Description of the approaches should contain biochemical details to demonstrate a good understanding of biochemistry. Focus is on how the biochemistry works and how it can contribute to long-term methane control. 

## Reducing methane emissions
- Many sources of methane emissions are difficult to control because the concentration of methane around the source is low, or because they are from essential human activities (e.g. agriculture) 
- Agricultural methane emissions are very large – 130Tg/yr, with >100Tg/yr from enteric fermentation and manure, ~30Tg/a from rice cultivation ([[SaunoisEtAl_2020]]), too large to be simply dismiss as intractable 
- For agriculture, solutions based on changing farming practices can be difficult to implement without hurting crop production ([[PrattTate_2018]]), so solutions that can be incorporated into existing practices without affecting agricultural yields would be ideal 

### Reducing enteric emissions 
- Brief explanation of what the solution is
	- Most cows live outside US and Europe. Most cows are found in the tropics and subtropics. In India alone there are 150 million small dairy farmers. 
	- The quantity of enteric methane emissions is affected by the quantity of feed, the type/quality of feed, species of ruminant, individual digestive physiology, and makeup of enteric microbes ([[SmithEtAl_2021]])
	- "Although changes in cattle diet and management, such as open grazing on nitrogen‐managed pastures (Warner et al., 2015) rather than stall feeding, can be effective in cutting emissions, these approaches... are often costly, only partly effective, or demand high skill levels by the farmer. They may be difficult to apply in nations such as South Sudan, with very high cattle population densities but low governance capacity." ([[NisbetEtAl_2020]])
	- Other methods demand high technical capacity which are often inaccessible to low income regions e.g. anaerobic digesters 
	- Difficult to persuade people to eat less meat and meat consumption is increasing in low- and middle-income countries
		- #citation Provide citation here 
- How it works 
	- Methanogenic archaea are strictly anaerobic 
	- All foregut fermenters (e.g. cattle, sheep, goats, deer) breathe out methane 
- Strengths 
	- Reduce emissions at source, which is more effective for methane considering short half-life ([[Outline 2#^d69342]])
	- Changing cattle diet and management (e.g. grazing on nitrogen-managed pastures instead of stall feeding) can be effective in reducing methane emissions, but are costly or require high skill levels, which can be difficult to apply in developing nations with high cattle populations (e.g. South Sudan), where organising such training can be difficult ([[NisbetEtAl_2020]]). Biological options could potentially provide a more affordable and accessible solution. 
- Limitations
	- What is the incentive to farmers to use these technologies? Useless if not widespread. 
	- A lot of current technologies for enteric emission reductions are still developmental or speculative, and are not immediately deployable. 
- Other considerations for long-term viability 
	- Biochemical solutions would be best if they can be incorporated into existing farming systems.
	- According to [[SmithEtAl_2021]], many of the "priority regions" for reducing enteric methane emissions and manure methane emissions are low- and middle-income countries, which would favour cheaper methods 
- Areas for further research 
	- Identification of methanogenic bacteria in the rumen, enzymes that produce methane, development of inhibitors of bacteria/enzymes, how do methanogenic bacteria produce methane  

#### Feed additives 
##### Algae 
- Strengths
	- Effective 
		- Adding algae from the genus *Asparagopsis* could reduce ruminant methane emissions by 20-98% ([[ReisingerEtAl_2021]])
- Limitations
	- There are many unknowns about *Asparagopsis* additives. 
		- There is wide variability in effectiveness (adding algae reduces emissions by... 20-98?!)
		- Persistence of methane emissions reductions over several seasons is not known ([[ReisingerEtAl_2021]])
		- *Asparagopsis* contains bromoform and bromochloromethane as the active ingredients, but they are confirmed animal carcinogens and possible human carcinogens. Residues of these active ingredients have been found in the urine and milk of livestock ([[ReisingerEtAl_2021]])
		- Unclear how *Asparagopsis* additive would affect livestock palatability, animal health 
		- Unclear how to produce *Asparagopsis* on a large scale

#### Methane inhibitors 
- How it works 
	- Methane inhibitors suppress the activity of methanogenic bacteria in the rumens of livestock ([[ReisingerEtAl_2021]])
	- Ionophores are antibiotics for methanogenic bacteria ([[SmithEtAl_2021]])
	- Halogenated compounds ([[SmithEtAl_2021]])
	- Propionate precursors (e.g. fumarate, malate) reduce methane formation by acting as alternative hydrogen acceptors [[SmithEtAl_2021]]
		- #citation Need primary 
- Strengths 
	- Effective 
		- 3-Nitrooxypropanol (3-NOP) can reduce methane emissions by about 30% in ==Total Mixed Ration== farm systems without compromising animal productivity ([[ReisingerEtAl_2021]])
			- #citation to provide primary citation 
			- #question What is Total Mixed Ration? 
- Limitations 
	- Transient effects in livestock 
		- 3-NOP may not be suitable for grazing systems, as it has a half-life of a few hours in the rumen, but could be used in slow-release formulations in dairy systems. ([[ReisingerEtAl_2021]])
		- Ionophore effect may be transitory ([[SmithEtAl_2021]])
			- #citation need primary 
		- Halogenated compounds 
	- Legality issues 
		- Ionophores have been banned in the EU ([[SmithEtAl_2021]])
			- #question Why have they been banned in the EU? Are they harmful? 
	- Side effects on animals
		- Halogenic compounds could cause reduced caloric intake ([[SmithEtAl_2021]])
			- #citation primary 
	- Cost
		- Propionate precursors are only effective at high doses ([[SmithEtAl_2021]])
			- #citation primary 
- Areas for further research 
	- Currently research is being done on using 3-NOP in young ruminants to stimulate lifetime reductions, which could be a potential long-term solution for enteric emissions ([[ReisingerEtAl_2021]])

#### Probiotics for methane reducing strains 

#### Methanogen vaccines 
- Limitations 
	- Research on methanogen vaccines is still in the development phase and has not been demonstrated in wild animals ([[ReisingerEtAl_2021]]), however methanogen targets have been identified, antibodies have been created, and have been shown to inhibit methanogen cultures *in vitro* 
		- Vaccine exists apparently? ([[SmithEtAl_2021]])
			- #citation Need primary citation 
	- Cost
	- Poor adoption rates of animal vaccines generally: Many animal vaccines are not adopted fully even when cost-effective ([[ReisingerEtAl_2021]])
		- #citation Need primary citation 

#### Cultured meat and dairy (alternative meats)
- Strengths
	- Sidesteps methane emission problem entirely by substituting methane-producing livestock 
- Limitations
	- Limited availability and affordability globally 

#### Other strategies 
-   Manipulation of rumen microbiome 
-   Use of genomics, metagenomics to examine effect of seaweed on rumen microbiome (Abbott et al 2020)
-   Antimicrobial agents (Abbott et al 2020) 
	- Saponin compounds – defaunation agents
	- Antimicrobial peptides can inhibit methanoarchaea M. stadtmanae and M. smithii in human gut microbiome 
	- Peptides and bacteriocins – few studies investigating effect on CH4 emissions, but could be a possible method 
	- Phlorotannins 
### Reducing emissions from rice fields 
#### Transgenic rice 
- How it works 
	- Su et al introduced a barley transcription gene into rice and reported increases in grain starch and decreases in methane emissions, along with diminished soil methanogens. This was attributed to lower root mass and root exudates ([[PrattTate_2018]])
		- #citation primary? 
- Limitations
	- Very much conceptual. Not known how it would affect CH4 emissions, grain yield, soil composition in the long run 

### Mitigating methanogens in soil 
- Areas for research 
	- Understanding methanogen biology 

#### Modifying redox conditions of soil 
- How it works
	- Electron accepting species (e.g. Fe3+, SO42-) compete with methanogens for hydrogen and carbon substrates 
		- E.g. gypsum (CaSO4 H2O) addition has been reported to reduce methane emissions in soils ([[StolaroffEtAl_2012]])
			- #citation primary? 
		- E.g. using ammonium sulfate instead of urea as a fertiliser reduces methane emissions ([[StolaroffEtAl_2012]])
	- Periodic drainage of field oxygenates in rice paddy soils ([[StolaroffEtAl_2012]])

#### Changing nutrient availability 
- How it works
	- Potassium and phosphorous addition favours methanotrophs in agricultural soils ([[StolaroffEtAl_2012]])
		- #citation primary? 

## Increasing methane removal 
- The main challenges facing methane removal are 
	- 200-fold lower concentration of methane compared to CO<sub>2</sub>, so rate of oxidation is lowered. 
		- More than 55% of anthropogenic methane emissions are at a concentration lower than the explosive limit of methane in air, making them incompatible for chemical oxidation processes (Ramirez et al 2012) 
			- #citation Read citation to get context. Why is explosive limit relevant to chemical oxidation process? How did the authors get to this conclusion of 55%?
	- High activation energy barrier due to strong C-H bond in methane (bond energy = 435 kJ mol<sup>-1</sup>)
		- Methane combustion is technically feasible and is widely practiced as a methane removal method for methane-rich biogas streams from landfills, wastewater treatment systems, as the energy generated from combustion recovers the energy required. However, in gas streams that are <5% CH4, combustion is not energetically feasible ([[PrattTate_2018]])
	- Economics of scaled methane oxidation 
		- [[JacksonEtAl_2019]] suggest that methane conversion is more likely to be more expensive per tonne than CO<sub>2</sub> removal, but may be more valued due to the higher GWP than CO<sub>2</sub>. Economics are currently uncertain. 
- It may be more energy efficient to remove methane by oxidising it freely in the air using catalysts rather than capturing and storing it. 
	- The methane oxidation reaction is thermodynamically favourable: CH4 + 2O2 → CO2 + 2H2O; ΔHr = –803 kJ mol–1 ([[JacksonEtAl_2019]])
	- As such, as long as the activation energy barrier can be overcome, there is minimal energy input required for oxidation. With biological catalysts, the activation energy barrier may also be overcome with minimal energy input. 
- Methane capture is likely to be more expensive than direct oxidation due to the low concentration of methane, as predicted by Sherwood's Rule, the idea that separation costs scale linearly with dilution [[Lackner_2020]]. For methane capture, the cost comes from requiring fans to blow air over the capture device to maintain a high enough concentration for capture ( #comment Need citation here), though passive methods are still possible. 
	- #question Is Sherwood's Rule legit? 
	- #question Are biochemical methods compatible with passive methods of methane removal? If so, would be a good argument for the lowered costs. 
- Methane oxidation does produce CO2 however, so have to be careful that CO2 emissions does not cancel out the global warming gain from methane removal. 
	- May need to consider other oxidation reactions that do not produce CO2, such as... (methanol production?) #question 

### Engineering methanotrophic bacteria 
- Brief explanation of what the solution is
	- Methanotrophic bacteria are bacteria that metabolise methane. 
	- Methanotrophs are largely classified as gammaproteobacteria (Type I) and alphaproteobacteria (Type II) based on the formaldehyde assimilation pathway used ([[SemrauEtAl_2010]]). However, differences between the two classes are nuanced and neither class is better than the other in methane oxidation ability. ([[StrongEtAl_2015]])
		- #citation Did strong 2015 actually say this? check 
	- Non-bacterial microbes have also exhibited methane oxidising activity, such as the yeast species *Sporobolomyces* and *Rhodoturula*,the microalgae *Chlorella*, but they are not as well researched as methanotrophic bacteria and so are not discussed here. 
- How it works 
	- Methanotrophic bacteria contain the enzyme methane monooxygenase (MMO), which oxidises methane to methanol. There are two forms of MMO, particulate MMO (pMMO) and soluble MMO (sMMO). pMMO-expressing species display higher methane affinities, and higher reaction rates at lower methane concentrations, and is expressed in the presence of copper. ([[SemrauEtAl_2010]])
	- MMO splits the O-O bond in O<sub>2</sub>. One of the O atoms is reduced to H<sub>2</sub>O, and the other is used to oxidise methane to methanol. sMMO uses NADH as the reducing agent while pMMO uses CytC. Methanol is then oxidised to formaldehyde by periplasmic methanol dehydrogenase (MDH), which is then oxidised to formate, and finally to CO2 in most methanotrophs. ([[ScheutzEtAl_2009]]). The formaldehyde may also enter other metabolic pathways (serine pathway in alphaproteobacteria, and RuMP in gamma proteobacteria) to synthesise cellular material, e.g. glyceraldehyde 3-phosphate
	  Figure 1 from [[StrongEtAl_2015]], adapted from Hanson and Hanson (1996)
	  ![[Pasted image 20221226211528.png|500]]
	  Figure 1 from Lopez et al (2013)
	  ![[Pasted image 20221226232748.png|500]]
		- In methanotrophs with both forms of MMO, copper is key to regulating expression of sMMO and pMMO, as well as their activities. pMMO is constitutive in all aerobic methanotrophs at Cu2+ concentrations of above 0.86 μmolg−1 dw, except for *Methyloferula* and *Methylocella* bacteria ([[LopezEtAl_2013]])
		- sMMO is a complex of three component proteins, a hydroxylase, a reductase, and a regulatory protein 
	- Most methanotrophs are obligate methanotrophs as well as strict aerobes, so their survival and growth depends on sufficient levels of methane and oxygen ([[ScheutzEtAl_2009]])
- Strengths 
	- Effective methane storage
		- Transporting methane often results in significant losses to the atmosphere ([[Fetzer_2022]]) Methanotrophic bacteria can sequester methane in less volatile forms (e.g. methanol) to reduce losses during transport. 
	- Can be deployed under ambient temperatures and pressures (as compared to purified enzymes)
	- Can oxidise methane at ambient atmospheric concentrations if species expresses pMMO 
		- Knief & Dunfield (2005) found that two *Methylocystis* strains were able to oxdise CH4 at atmospheric concentrations for 3 months , though they were not able to grow. A third *Methylocystis* species could grow at the low concentration of 10ppmv CH<sub>4</sub> due to expression of the pMMO2 isozyme 
		- Kolb et al (2005) also reported methanotrophs that could oxidise CH4 at atmospheric concentrations in acidic forest soils, also expressing pMMO 
	- Can be used to create valorised products using the carbon in CH4 
		- Harvesting of organic inclusion bodies in bacteria e.g. poly(3-hydroxybutyrate) ([[LaEtAl_2018]])
		- Methanotrophs are able to convert methane to useful, environmentally friendly products via downstream metabolic pathways, e.g. polyhydroxyalkanoate (PHA), polyhydroxybutyrate (PHB), which is a feedstock for bioplastics. ([[PrattTate_2018]])
		- Engineering new metabolic pathways into methylotrophs to convert methanol to butanol (U of Delaware) ([[StrongEtAl_2015]])
		- Formation of polyhydroxybutyrate to create biodegradable plastics (Chidambarampadmavathy et al., 2017; Pieja et al., 2011)
			- #citation Read 
		- Biodiesel, butanol, lactate, cosmetics, etc. (Ge et al 2014, Kalyuzhnaya 2015)
			- #citation Read 
		- Mango Materials (http://mangomaterials.com/) already converts CH4 from landfill emissions into biopolymers for commercial applications ([[PrattTate_2018]]). So possible to use CH4 from other sources too. 
	- Adaptability
		- By using a mixture of microbes, the biological oxidation system is more capable of adapting to environmental variations not present in the lab ([[LaEtAl_2018]]), compared to chemical or physical systems that may require more specific conditions for optimal activity 
	- Robustness to other volatile organic compounds present in the local atmosphere
		- Co-emission of CH4 with other volatiles may inhibit or enhance CH4 oxidation by bacteria ([[LaEtAl_2018]]). "Kim et al. (2013) observed a boost to both microbial diversity and CH4 oxidation upon the co-emission of CH4 and dimethylsulfide while co-emission of CH4 with a mixture of dimethylsulfide, butane, and toluene had a detrimental effect to CH4". H<sub>2</sub>S is also often present in many methane emitting environments (e.g. landfills, livestock facilities, wastewater treatment plants, oil and gas extraction and processing facilities)
		- #citation Read 
	- Passive system (i.e. does not require air to be blown over it), making it energy efficient  
- Limitations 
	- Ineffective if methane concentration in atmosphere is too low 
		- Global average atmospheric methane concentration (1.7ppmv) is too low to support cell growth for sMMO or pMMO-expressing cell ([[YoonEtAl_2009]]) 
	- Broad substrate range of MMO enzymes could result in competition between methane and other gases present in the atmosphere, reducing the efficiency of methane oxidation.  This not only reduces methane removal rates but also affects growth rates of methanotrophs [[StrongEtAl_2017a]]
	- Scalability – mass transfer of methane from the gaseous phase into the aqueous phase (where methanotrophs/enzymes are found) is challenging as methane has poor solubility. 
		- Currently, there is work being done to improve the scalability of biological reactors so as to improve economic feasibility and efficacy of using methanotrophic bacteria. [[Fetzer_2022]]
		- This could be partially overcome by improving the microbial affinity for methane 
	- Reduced effectiveness at sites with high ammonia concentrations
		- Some studies of methanotrophs report that NH3 inhibits methane oxidation, which Hernandez et al (2015) attributes to competition for the active site of MMO, accumulation of toxic metabolites due to nitrification reactions (e.g. hydroxylamine, nitrite), and increased salinity which has "ionic and osmotic effects". However, this is more of a problem at low methane concentrations – if there is sufficiently high concentration of methane, ammonium acts more as a nutrient ([[LaEtAl_2018]])
		- #citation Read. 
	- Controlling the environment: While biological systems are adaptable, being able to control the local environment of the bacteria could optimise enzymatic activity. Biofilters, bioreactors, biocovers activity all depend on environmental factors.  
		- Temperature, pH deviations. 
		- Diurnal temperature fluctuations can decrease CH4 oxidation rates by more than half that the maximum rate ([[LaEtAl_2018]])
		- Temperature variations could be controlled for by insulating the bacteria in a biofilter 
	- N<sub>2</sub>O production is a long-term risk as a result of denitrification reactions ([[LaEtAl_2018]], [[Nisbet-JonesEtAl_2022]]) 
		- Nitrogen compounds present in the air (e.g. ammonia from animal waste), biofilters could oxidise them to N<sub>2</sub>O, which not only has a long lifetime, but has a GWP 300 times higher than CO2 ( #comment over what timescale? )
		- Bioreactors have also been shown to emit significant volumes of N2O; Melse et al found that in one instance, more than 20% of the ammonia present was converted to N2O, which suggests that bioreactors and biofilters may be unsuitable at livestock facilities 
			- #citation needed
	- Some methanotrophic species have very slow growth rates 
		- Some DAMO species have growth rates of ~1-2 weeks ([[Silva-TeiraEtAl_2017]])
	- Unknown environmental impact 
		- Have not seen any research done on this in the literature. 
- Other considerations 
- Areas for further research + possible experiments to test 
	- Discovery and characterisation of methanotrophs 
	- Characterising active site of MMO to build synthetic mimics ([[StolaroffEtAl_2012]])
	- Enzyme engineering to enhance methanotrophic activity 
		- High affinity methanotroph species with very low half-saturation constants have been found recently and *can* consume methane at concentrations as low as 1.77ppmv, but they have limited maximum capacity to degrade methane, i.e. they are saturated at low methane concentrations ([[YoonEtAl_2009]]). There may be an opportunity to engineer enzymes that have both high affinity and high Vmax that are then transformed into methanotrophic bacteria 
			- #citation need primary
		- Some projects that are being worked on: using completely synthetic enzymes for methane activation (Arzeda Corp.), re-engineering existing enzymes for methylation (Northwestern, Lawrence Berkeley), re-engineering methane oxidation pathways (UC Davis) ([[StrongEtAl_2015]])
	- Strain engineering 
		- Some strains of methanotrophs have slow growth rates; there is an opportunity to engineer bacterial strains that have fast growth rates, have MMO with high affinity and Vmax for methane, as well as a tolerance for methane oxidation products
		- This is currently being worked on by UCLA ([[StrongEtAl_2015]])
	- How can biochemistry develop methods for extraction and valorisation of oxidised methane products/organic inclusion bodies in bacteria? – metabolic engineering 
		- Commercial production of these products from methanotrophs is often limited by high cost of production, so more research is needed on the metabolic pathways to optimise metabolite production ([[PrattTate_2018]])
	- What are the optimal conditions for MMO 
	- Cell free catalysis  
		- E.g. by GreenLight Biosciences ([[StrongEtAl_2015]])
	- How do individual methanotroph species and methanotroph communities respond and adapt to variations in environmental conditions? e.g. fluctuating CH4 concentrations, abiotic variations, competition with other microbes, co-elimination of other volatile gases (e.g. H<sub>2</sub>S) 
	- Long term monitoring of microbial communities 
	- Bottom up design of methanotrophic communities for use in biofilters/bioreactors to optimise for methane oxidation and robustness in variable environments 
		- [[Silva-TeiraEtAl_2017]] seemed to use some unspecified "biomass" and did not know the species contents of the biomass? Lack of control over the species present
	- Heterologous expression of MMOs ([[StrongEtAl_2015]]) 
		- Methanotrophs have relatively slow growth rates, so there have been attempts to express MMO genes into other bacterial expression systems for faster enzyme production
			- #citation ? 
		- However, attempts thus far have failed, and only partially active sMMO with hydroxylase activity has been obtained 
			- #citation ? 
		- For pMMO, a reason fully active proteins have not been obtained thus far could be that when it is expressed in a non-native lipid matrix, it loses interactions with essential interaction partners and cofactors [[StrongEtAl_2015]]

#### Biofiltration 
- In the IPCC 2007 assessment report, biocovers and biofilters were cited as key mitigation technologies for methane
	- #citation read primary 
- How it works 
	- Biofilters are devices containing microbes attached to packing materials, that use the metabolic activity of these microbes to treat environmental contaminants. Gaseous contaminants can diffuse into biofilms and are metabolised by the microbes in the biofilm. ([[YoonEtAl_2009]])
		- #citation primary? 
	- Biotrickling – ? 
- Strengths 
	- Effective: Can support high CH4 removal rates when optimised for O2 concentrations, moisture content, packing material, and other parameters ([[GirardEtAl_2011]]) (Park et al 2009) (Gebert et al 2003)
		- Park et al (2009) achieved the highest abatement performance for a biofilter, achieving a maximum EC of 280 g m-3h-1 at EBRT of 1.2h. Girard et al (2011) achieved similar efficiency. 
		- [[GirardEtAl_2011]] achieved removal of 45% of methane emissions using a biofilter from a swine slurry in Canada, and at concentrations as low as 250ppm 
		- #citation Read primary 
		- #question What is EC and EBRT? 
	- Versatile: Has been deployed in various environments that experience methane emissions, e.g. peatlands, rice paddy soils, landfill cover soils, animal houses, wastewater treatment plants ([[LaEtAl_2018]], [[PrattTate_2018]])
	- Long-term: If the biofilter is optimised for packing material, and a mixed culture of bacteria is used, biofilters can be deployed in the field for several years while still maintaining a high efficiency of methane removal ([[LaEtAl_2018]]) 
	- Maturity: Biofilters have been extensively tested in the field. Floating biofilters are already being manufactured by several companies for the removal of nutrient and odours from wetlands ([[PrattTate_2018]])
	- Cost: Low ([[PrattTate_2018]])
	- Low energy cost: passive air flow systems can be used 
	- Could function at low methane concentrations: A model created by [[YoonEtAl_2009]] suggested that operation at 500ppm was possible. Presumable as long as soil microbes that already survive on ambient CH4 concentrations are used, a biofilter can also extract methane at ambient concentrations. 
- Limitations 
	- Accumulation of biomass: Methanotrophic bacteria produce biomass, and excess amount of biomass will reduce efficiency of methane removal ([[LaEtAl_2018]]), which could be a long-term maintenance problem for biofilters. 
		- #question Why would excess biomass reduce efficiency of methane removal?
	- May not be viable at livestock facilities due to N2O production 
	- Scaled-up, long-term testing is needed 
	- How can bacteria and products be separated from packing material of biofilter or soil of landfill bicover for use in valorisation? ([[LaEtAl_2018]])
	- Problems at low methane concentrations 
		- At low methane concentrations, biofilters run the risk of convering ammonia to nitrous oxide (N<sub>2</sub>O) ([[NisbetEtAl_2020]])
			- Biofilters increase the amount of N<sub>2</sub>O present by up to 400% (Van der Heyden et al 2015)
			- #question Why does this occur? 
			- #citation Primary 
		- If the rate of methane oxidation is too low, methanotroph growth rate may be too slow for cells to survive in a standard trickling biofilter, as the falling water could cause cell loss that is greater than cell growth ([[YoonEtAl_2009]]). 
- Areas for research 
	- Prevention of biomass accumulation 

#### Wastewater treatment 
- Brief explanation of solution 
	- Biological wastewater denitrification systems require organic carbon which act as reducing compounds ( #comment Is this right?) to facilitate reduction of nitrate to nitrogen 
- How it works
	- Aerobic methanotrophs oxidise methane to methanol, formaldehyde, or acetate, which may then be used as a carbon source/electron donor by heterotrophic denitrifying microbes downstream. This is known as aerobic methane oxidation coupled to denitrification (AMO-D) ([[Silva-TeiraEtAl_2017]])
	- In anaerobic conditions, some microbes can couple denitrification to anaerobic methane oxidation (DAMO), including DAMO bacteria (e.g. *Candidatus Methylomirabilis oxyfera*) or DAMO archaea (e.g. *C. Methanoperedens nitroreducens*) ([[Silva-TeiraEtAl_2017]])
	- A consortium of anammox, DAMO archaea and DAMO bacteria may be used, with DAMO archaea reducing nitrate to nitrite, and annamox and DAMO bacteria competing for nitrite. (Haroon et al 2013) 
		- #citation To read
- Strengths 
	- Existing denitrification systems have to be supplemented with a costly external carbon source (e.g. ethanol) to achieve discharge limits ( #question what is a discharge limit) ([[[StrongEtAl_2015]]]), so methanotroph usage could provide a cheaper alternative by using methane as a low cost carbon source 
- Limitations 
	- Bioreactors for wastewater treatment have to be optimised for the microbial community used. In some studies, the bioreactors had to be operated for months to stimulate growth of indigenous methanorophs, leading to long start-up periods or poor methane removal ([[LopezEtAl_2013]]). This could be addressed by inoculating the bioreactor with methanotrophs from a methane biofilter or from activated sludge which already contain acclimated inocula.
		- #comment Tbh I don't fully understand this part 

#### Adding soil covers/biocovers
fig 1 from [[ScheutzEtAl_2009]]
![[Pasted image 20221226212705.png]]
- How it works 
	- A permeable material, typically made of organic matter (e.g. soil, compost, wood chips, sewage sludge) is applied to the surface of a landfill. The material should allow for effective gas transport of CH<sub>4</sub> from the landfill and oxygen from the atmosphere, as well as water retention ([[SemrauEtAl_2010]])
	- Soil covers can be seeded with methanotrophs and spread on landfills ([[Nisbet-JonesEtAl_2022]])
	- Engineered biocovers also exist and make use of specialised substrates to maximise methane oxidation ([[StolaroffEtAl_2012]])
- Strengths
	- Cheap – landfill emissions are poorly controlled and much higher in tropical developing nations ([[NisbetEtAl_2020]])
	- could be financed with carbon credits directly (Kormi et al 2018) ([[NisbetEtAl_2020]])
		- #citation Primary? 
	- Can be highly effective
		- Chanton et al found that 10-89% of landfill methane emissions can be oxidised by a biocover ([[StolaroffEtAl_2012]])
			- #citation Primary? 
		- Scheutz et al (2014) used a biocover made of cheap compost materials (e.g. garden waste, kitchen waste) and reported methane mitigation efficiency of about 80% ([[NisbetEtAl_2020]])
			- #citation Primary? 
	- Intermediate maturity – full-scale biocover projects are currently being tested in US, Germany, Denmark, Australia, Canada ([[StrongEtAl_2017a]])
	- Versatile in different climates – although methane oxidation depends on temperature, landfills are strongly exothermic. Einola et al (2007) reported that methane oxidation can continue in landfill cover soils even during cold weather. This means that biocovers can also be employed in colder climates e.g. China ([[NisbetEtAl_2020]])
		- #citation Primary? 
	- Removal of methane from landfills has the co-benefit of removing unwanted smells and reducing fire risks ([[NisbetEtAl_2020]])
- Limitations 
	- There seems to be a lot of variability in effectiveness (Chanton et al) ([[StolaroffEtAl_2012]]), so greater optimisation is needed for field applications 
		- #citation primary? 
		- CH4 oxidation in biocovers is affected by a number of environmental factors (see [[ScheutzEtAl_2009]])
- Areas for research 
	- Field emission measurements in the tropics are needed ([[ScheutzEtAl_2009]]), particularly since landfill methane emissions are poorly controlled and are much higher in tropical, developing nations (e.g. India) compared to developed nations (e.g. parts of Europe, US) ([[NisbetEtAl_2020]])

#### Use biofertilisers to enhance methanotrophy in rice paddy fields 
- Rice paddies are a significant source of CH4, and methane emissions are only likely to increase in the future given that rice production is expected to increase from 600m tonnes in 2000 to 930m tonnes by 2030 (Kubo and Purevdori, 2004)
	- #comment read primary to verify stats 
- Brief explanation of what the solution is
	- Biofertilisers are organic fertilisers that have been combined with microbes capable of beneficial functions, e.g. photosynthesis or N<sub>2</sub> fixation ([[SinghStrong_2016a]])
- How it works 
	- Improving the oxygenation of soils improves methane oxidation, as methanotrophs are aerobic. This could be done by applying biofertilisers with photosynthetic organisms ([[SinghStrong_2016a]])
- Strengths 
	- Effectiveness has been shown 
		- Pingak et al (20144) showed that applying certain diazotroph species to rice paddy soils can lower methane emissions by increasing soil oxygenation 
		- Simiilarly, Sahoo et al (2014) reported that inoculating rice plant roots with the diazotroph *Azospirillum* increased O2 in the rhizosphere, similarly achieving increased soil oxygenation 
		- Prasanna et al (2002) reported reduced methane emissions from paddy field soils treated with photosynthetic *Azolla* and/or *Synechocystis* cyanobacteria  
			- #citation Read primary 
	- These microbes could also promote plant growth at the same time, and so provide a direct benefit to farmers too 
		- E.g. plant growth promoting strains of *P illinoisensis*, *Bacillus aerius*, *B subtilis* etc. contain pmoA gene that is a subunit of pMMO 
- Limitations
	- Addition of organic substrates to soil as carriers of microbes could introduce more carbon into the soil that could be converted into CH4, though this could be addressed by introducing the desired microbes into the soil as mixtured with conventional or low-labile carbon fertilisers ([[PrattTate_2018]])
	- Long term effects on CH4 oxidation efficiency of soil is not known ([[PrattTate_2018]])
- Other considerations for long-term viability 
- Areas for further research 
	- The direct and indirect effects of biofertilisers have not been fully explored, and biofertilisers are still more conceptual; have yet to be fully optimised 
	- Relationship between methanotrophs and other soil microbes, nitrogen availability, phosphate availability is not well understood yet 

Fig.1 from [[SinghStrong_2016a]]
![[Pasted image 20221226205831.png]]

#### Promote growth of existing methanotrophs in saline soils
- Brief explanation 
	- Saline conditions in paddy soils lowers the activity, size of methanotrophic communities ([[SinghStrong_2016a]])
- How it works 
	- Pyrite can be used to reclaim saline soils (Singh et al 2010), or farmyard manure in conjunction with pyrite (Singh et al 2010), or fly ash with organic manure (Singh & Pandey, 2013)
		- #citation primary 
	- An alternative strategy could be to seed soils with salt-tolerant methanotrophs, e.g. species from *Methylmicrobium* genus 

#### Microbial fuel cells (MFCs)
- How it works
	- Produce electricity by coupling electricity production to methane oxidation 
	- Wrighton et al used *Firmicutes* species ([[PrattTate_2018]])
		- #citation primary  
	- McAnulty et al constructed a consortium of the methane-oxidising *Methanosarcina acetivorans* and *Geobacter sulfurreduens* to generate electric current from methane 
		- #citation primary 
- Limitation
	- Still very conceptual 

## In conjunction with non-biological methods  
- Trapping methane in nanoporous zeolites or porous polymer networks 
- It is likely that biochemical solutions will be used alongside non-biological ones – what is the niche biochemistry offers? 
	- For tackling biological sources of methane emissions 
	- Cost 
	- Robustness and adaptability to changing environmental conditions 

# Evaluating different technologies according to a common standard
In lieu of a standard set of criteria to evaluate methane emission technologies in the literature, I have proposed the following criteria to evaluate the above methods, with definitions as follows. 

| Technology                                    | Maturity     | Predicted cost | Effectiveness (highest estimate) |
| --------------------------------------------- | ------------ | -------------- | -------------------------------- |
| Transgenic rice                               | Low          |                |                                  |
| Microbial fuel cells                          | Low          |                |                                  |
| Biocovers                                     | Intermediate |                |                                  |
| Biofilters                                    | Intermediate |                |                                  |
| Developing bioplastics from waste CH4 streams | High             |                |                                  |

Policymakers may prioritise certain criteria above others, but the aim of this evaluation is to provide some standardisation and easy means of comparison. 

**Check Reisinger et al (2021)** Table 1 

## Maturity
- Low: Proof of concept has been shown, but has not been deployed in the field, so real world practicality and long-term effects unknown 
- Intermediate: Field testing has been done and/or technology has been used for different applications 
- Mature: Technology already exists and is actively being used in the field
	- Important because climate crisis is imminent; we cannot afford to waste time developing blue sky technologies if effective methods are already near fruition in the technology pipeline 

# Areas for future research 
Overall we can see that there are some key gaps in the research that could improve biochemical solutions, such as
- Methanotroph strain engineering 
- Enzyme engineering (does immobilisation of purified enzymes on a solid matrix work? Or too unstable?)
- Economics 
	- Scalability ([[JacksonEtAl_2019]])
	- Valorisation of oxidation products of methane
	- Only removing methane from locations with high local methane concentrations 

There needs to be better benchmarking of solutions – rate of CH4 removal is a common parameter, but what is considered to be a "good" rate of removal? 

Report by ? states that most ? methane emissions can already be removed with existing measures, is there a place for biochemistry?
-> could criticise study by saying that those solutions unlikely to be implemented, so even though in theory they could if implemented, in practice not likely. biochem can be more effective because it does not require changes in existing social or economic activity... 

# Conclusion 
- Ultimately, reducing methane emissions in the first place will be essential to the long-term control of methane in the atmosphere, however because of economic and social difficulties in achieving sufficient methane emission reductions, technologies for methane removal may also be necessary, particularly if climate feedbacks exacerbate methane emissions 
- There are existing biochemical solutions for certain sources of methane emissions (i.e. enteric), and can remove methane from the atmosphere generally but particularly better at places with high methane levels 
- Long-term viability of biochemical solutions hinges more on economics rather than technology (?) so that implemented measures can be maintained over a long period of time of at least a decade to achieve permanent reductions. 
- "For the Paris Agreement to succeed, methane needs attention"
