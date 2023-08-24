21 Dec 2022
#comment 
- Does this outline the question? Refer to dissertation grading criteria
	- Nuance 
	- Detail (Experimental detail? Biochemistry detail?) 
- Also, need to go back and look for the primary source of some of these facts. 
- Indicate in outline where diagrams would be useful, especially in cutting down words 
- Make sure each point is supported by experimental evidence 

**Methane is a far more potent "greenhouse gas" than CO2. Can biochemistry assist in the long-term control of methane levels in the atmosphere?**

# Context 
- What is the effect of methane on the atmosphere
- How much more potent is it as a greenhouse gas than CO<sub>2</sub>
	- Methane is 84 times more potent than CO<sub>2</sub> in the first 20 years after release, and 28 times more potent after a century (in terms of Global Warming Potential) ([[JacksonEtAl_2019]]])
		- #citation Review 
		- #comment Explain what is global warming potential 
	- 2020 saw the largest annual increase in atmospheric CH4 since 1983 when systematic measurements started ([NOAA, 2021](6] NOAA. Despite pandemic shutdowns, carbon dioxide and methane surged in 2020. https://research.noaa.gov/article/ArtMID/587/ArticleID/2742/Despite-pandemic -shutdowns-carbon-dioxide-and-methane-surged-in-2020,))
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
		- As such, artificial removal methods are unlikely to play as big of a role in methane control as in CO<sub>2</sub> control, since methane is already being removed relatively rapidly from the atmosphere. In fact, to significantly enhance natural processes, methane removal methods would need to be rapid enough to process the entire atmosphere in less than 10 years. However, should there be a massive increase in emissions from permafrost due to climate feedbacks (e.g. destabilisation of seafloor methane-hydrates, melting of Arctic permafrost) ([[MingEtAl_2022]]), artificial methane removal may be necessary to supplement natural processes. ([[Lackner_2020]])
	- Removing existing methane in the atmosphere 
		- [[AbernethyEtAl_2021]] showed that removing methane can help to alleviate global warming using an Earth Systems model. 
	- #comment ==Methane has a short half-life, does this have any implication for methane control strategies? I think it affects the speed at which methane has to be removed from the atmosphere for solutions to be effective, but should check this out.==

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

Include a nice summary picture here. 
I think it could be similar to the one in my EEC report on GHGs? That I reproduced from a paper. 

# Approaches 
#comment Description of the approaches should contain biochemical details to demonstrate a good understanding of biochemistry. Focus is on how the biochemistry works and how it can contribute to long-term methane control. 

## Reducing methane emissions
Solutions are ordered in terms of immediacy, so 
- Biochemical research on reducing methane emissions
- Applications currently undergoing testing 
- Applications being deployed in the field right now 

### Solution 1
- Brief explanation of what the solution is
- How it works 
- Strengths 
- Limitations
- Other considerations for long-term viability 
- Areas for further research 

### Reducing enteric emissions 
- Brief explanation of what the solution is
	- Most cows live outside US and Europe. Most cows are found in the tropics and subtropics. In India alone there are 150 million small dairy farmers. 
	- The quantity of enteric methane emissions is affected by the quantity of feed, the type/quality of feed, species of ruminant, individual digestive physiology, and makeup of enteric microbes ([[SmithEtAl_2021]])
	- "Although changes in cattle diet and management, such as open grazing on nitrogen‐managed pastures (Warner et al., 2015) rather than stall feeding, can be effective in cutting emissions, these approaches... are often costly, only partly effective, or demand high skill levels by the farmer. They may be difficult to apply in nations such as South Sudan, with very high cattle population densities but low governance capacity." ([[NisbetEtAl_2020]])
	- Other methods demand high technical capacity which are often inaccessible to low income regions e.g. anaerobic digesters 
	- Difficult to persuade people to eat less meat and meat consumption is increasing in low- and middle-income countries
		- #citation Provide citation here 
- How it works 
- Strengths 
	- Reduce emissions at source, which is more effective for methane considering short half-life ([[Outline 2#^d69342]])
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
	- Research on methanogen vaccines is still in the development phase and has not been demonstrated in wild animals ([[ReisingerEtAl_2021]]), however methanogen targets have been identified, antibodies have been created, and have been shown to inhibit methanogen cultures *in vitro*. Vaccine exists apparently? ([[SmithEtAl_2021]])
		- #citation Need primary citation 
	- Cost
	- Poor adoption rates of animal vaccines generally: Many animal vaccines are not adopted fully even when cost-effective ([[ReisingerEtAl_2021]])
		- #citation Need primary citation 

#### Cultured meat and dairy (alternative meats)
- Strengths
	- Sidesteps methane emission problem entirely by substituting methane-producing livestock 
- Limitations
	- Limited availability and affordability globally 

### Reducing methane emissions from rice paddies 
#### Use biofertilisers to enhance methanotrophy in fields 

## Increasing methane removal 
- The main challenges facing methane removal are 
	- 200-fold lower concentration of methane compared to CO<sub>2</sub>, so rate of oxidation is lowered. 
		- More than 55% of anthropogenic methane emissions are at a concentration lower than the explosive limit of methane in air, making them incompatible for chemical oxidation processes (Ramirez et al 2012) 
			- #citation Read citation to get context. Why is explosive limit relevant to chemical oxidation process? How did the authors get to this conclusion of 55%?
	- High activation energy barrier due to strong C-H bond in methane (bond energy = 435 kJ mol<sup>-1</sup>)
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
	- Methanotrophic bacteria are bacteria that metabolise methane 
- How it works 
	- Methanotrophic bacteria contain the enzyme methane monooxygenase (MMO), which oxidises methane to methanol. There are two forms of MMO, particulate MMO (pMMO) and soluble MMO (sMMO). pMMO-expressing species display higher methane affinities, and higher reaction rates at lower methane concentrations, and is expressed in the presence of copper. 
		- #question Are there other enzymes, metabolic pathways? 
	- Aerobic methanotrophs oxidise methane to methanol, formaldehyde, or acetate, which may then be used as a carbon source by heterotrophic denitrifying microbes downstream. This is known as aerobic methane oxidation coupled to denitrification (AMO-D) ([[Silva-TeiraEtAl_2017]])
	- In anaerobic conditions, some microbes can couple denitrification to anaerobic methane oxidation (DAMO), including DAMO bacteria (e.g. *Candidatus Methylomirabilis oxyfera*) or DAMO archaea (e.g. *C. Methanoperedens nitroreducens*) ([[Silva-TeiraEtAl_2017]])
		- A consortium of anammox, DAMO archaea and DAMO bacteria may be used, with DAMO archaea reducing nitrate to nitrite, and annamox and DAMO bacteria competing for nitrite. (Haroon et al 2013) 
			- #citation To read
- Strengths 
	- Effective methane storage
		- Transporting methane often results in significant losses to the atmosphere ([[Fetzer_2022]]) Methanotrophic bacteria can sequester methane in less volatile forms (e.g. methanol) to reduce losses during transport. 
	- Can be deployed under ambient temperatures and pressures (as compared to purified enzymes)
	- Can be used to create valorised products using the carbon in CH4 
		- Harvesting of organic inclusion bodies in bacteria e.g. poly(3-hydroxybutyrate) ([[LaEtAl_2018]])
		- Formation of polyhydroxybutyrate to create biodegradable plastics (Chidambarampadmavathy et al., 2017; Pieja et al., 2011)
			- #citation Read 
		- Biodiesel, butanol, lactate, cosmetics, etc. (Ge et al 2014, Kalyuzhnaya 2015)
			- #citation Read 
	- Adaptability: By using a mixture of microbes, the biological oxidation system is more capable of adapting to environmental variations not present in the lab ([[LaEtAl_2018]]), compared to chemical or physical systems that may require more specific conditions for optimal activity 
	- Robustness to other volatile organic compounds present in the local atmosphere: Co-emission of CH4 with other volatiles may inhibit or enhance CH4 oxidation by bacteria ([[LaEtAl_2018]]). "Kim et al. (2013) observed a boost to both microbial diversity and CH4 oxidation upon the co-emission of CH4 and dimethylsulfide while co-emission of CH4 with a mixture of dimethylsulfide, butane, and toluene had a detrimental effect to CH4". H<sub>2</sub>S is also often present in many methane emitting environments (e.g. landfills, livestock facilities, wastewater treatment plants, oil and gas extraction and processing facilities)
		- #citation Read 
	- Passive system (i.e. does not require air to be blown over it), making it energy efficient 
- Limitations 
	- Ineffective if methane concentration in atmosphere is too low 
		- Global average atmospheric methane concentration (1.7ppmv) is too low to support cell growth for sMMO or pMMO-expressing cell ([[YoonEtAl_2009]])
	- Scalability
		- Currently, there is work being done to improve the scalability of biological reactors so as to improve economic feasibility and efficacy of using methanotrophic bacteria. [[Fetzer_2022]]
	- Reduced effectiveness at sites with high ammonia concentrations: NH3 inhibits methane oxidation, which Hernandez et al (2015) attributes to competition for the active site of MMO, accumulation of acidic metabolites due to nitrification reactions, and increased salinity which has "ionic and osmotic effects"
		- #citation Read. What does ionic and osmotic effects refer to? 
	- Controlling the environment: While biological systems are adaptable, being able to control the local environment of the bacteria could optimise enzymatic activity 
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
	- Enzyme engineering to enhance methanotrophic activity 
		- High affinity methanotroph species with very low half-saturation constants have been found recently and *can* consume methane at concentrations as low as 1.77ppmv, but they have limited maximum capacity to degrade methane, i.e. they are saturated at low methane concentrations ([[YoonEtAl_2009]]). There may be an opportunity to engineer enzymes that have both high affinity and high Vmax that are then transformed into methanotrophic bacteria 
			- #citation need primary
	- Strain engineering 
		- Some strains of methanotrophs have slow growth rates; there is an opportunity to engineer bacterial strains that have fast growth rates, have MMO with high affinity and Vmax for methane, as well as a tolerance for methane oxidation products
	- How can biochemistry develop methods for extraction and valorisation of oxidised methane products/organic inclusion bodies in bacteria? – metabolic engineering 
	- What are the optimal conditions for MMO 
	- How do individual methanotroph species and methanotroph communities respond and adapt to variations in environmental conditions? e.g. fluctuating CH4 concentrations, abiotic variations, competition with other microbes, co-elimination of other volatile gases (e.g. H<sub>2</sub>S) 
	- Long term monitoring of microbial communities 
	- Bottom up design of methanotrophic communities for use in biofilters/bioreactors to optimise for methane oxidation and robustness in variable environments 
		- [[Silva-TeiraEtAl_2017]] seemed to use some unspecified "biomass" and did not know the species contents of the biomass? Lack of control over the species present

#### Biofiltration 
- How it works 
	- Biofilters are devices containing microbes attached to packing materials, that use the metabolic activity of these microbes to treat environmental contaminants. Gaseous contaminants can diffuse into biofilms and are metabolised by the microbes in the biofilm. ([[YoonEtAl_2009]])
		- #citation primary? 
- Strengths 
	- Versatile: Has been deployed in various environments that experience methane emissions, e.g. peatlands, rice paddy soils, landfill cover soils, animal houses, wastewater treatment plants ([[LaEtAl_2018]])
	- Long-term: If the biofilter is optimised for packing material, and a mixed culture of bacteria is used, biofilters can be deployed in the field for several years while still maintaining a high efficiency of methane removal ([[LaEtAl_2018]])
- Limitations 
	- Accumulation of biomass: Methanotrophic bacteria produce biomass, and excess amount of biomass will reduce efficiency of methane removal ([[LaEtAl_2018]]), which could be a long-term maintenance problem for biofilters. 
		- #question Why would excess biomass reduce efficiency of methane removal?
	- May not be viable at livestock facilities due to N2O production 
- Areas for research 
	- Prevention of biomass accumulation 

#### Bioreactors 

#### Adding soil covers 
- How it works 
	- Soil covers are seeded with methanotrophs and spread on landfills ([[Nisbet-JonesEtAl_2022]])
- Strengths
	- Cheap 

## In conjunction with non-biological methods  
- Trapping methane in nanoporous zeolites or porous polymer networks 
- It is likely that biochemical solutions will be used alongside non-biological ones – what is the niche biochemistry offers? 
	- For tackling biological sources of methane emissions 
	- Cost 
	- Robustness and adaptability to changing environmental conditions 

# Areas for future research 
Overall we can see that there are some key gaps in the research that could improve biochemical solutions, such as
- Methanotroph strain engineering 
- Enzyme engineering (does immobilisation of purified enzymes on a solid matrix work? Or too unstable?)
- Economics 
	- Scalability ([[JacksonEtAl_2019]])
	- Valorisation of oxidation products of methane
	- Only removing methane from locations with high local methane concentrations 

# Conclusion 
- Ultimately, reducing methane emissions in the first place will be essential to the long-term control of methane in the atmosphere, however because of economic and social difficulties in achieving sufficient methane emission reductions, technologies for methane removal may also be necessary, particularly if climate feedbacks exacerbate methane emissions 
- There are existing biochemical solutions for certain sources of methane emissions (i.e. enteric), and can remove methane from the atmosphere generally but particularly better at places with high methane levels 
- Long-term viability of biochemical solutions hinges more on economics rather than technology (?) so that implemented measures can be maintained over a long period of time of at least a decade to achieve permanent reductions. 
