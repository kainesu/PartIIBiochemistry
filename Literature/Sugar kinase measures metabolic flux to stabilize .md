# Sugar kinase measures metabolic flux to stabilize nutrient sensing

Note type: Source
Project: TORC1 signalling
Source type: Journal

TLDR

- Problem: Cells infer environmental nutrient availability by sensing internal nutrient concentrations. However, upregulation of metabolic enzymes would interfere with nutrient sensing by decreasing internal nutrient concentrations.
- In yeast, this problem in the galactose-utilisation pathway is resolved via an enzyme, Gal1p, that both catabolises galactose and transmits signals proportional to its enzymatic flux (”flux sensing”)
- Gal1p is able to do this because it intrinsically couples cataysis and signaling, as the rate of both reactions depends on the rate of galactose binding.

Method 

1. Construct a simple model to show the conflict between metabolism and signalling 
2. Prove the model empirically using Gal1p, but unexpectedly increased Gal1p activity led to increase GAL signalling 
3. Further test this by titrating with Gal1p analog SpGal1p which has the same metabolic function but no signalling function – SpGal1p shows same results as simple model (metabolism and signalling in conflict) 
4. To further confirm that this result is caused by Gal1p signalling to Gal80p, Gal80 coding sequence replaced by Gal80 from a diff species that binds less tightly to Gal1p, and also mutated Gal1p to reduce binding affinity → Both these perturbations reduced the extent to which Gal1p levels increase GAL signaling 

In flux sensing, cells sense “flux-sensing metabolites”, metabolites whose concentration is proportional to their flux. Mechanisms for maintaining the proportionality of metabolite concentrations with metabolic flux has been proposed to require a complex interplay of metabolic and transcriptional regulation. In gal1p, this mechanism could be

- measurement of phosphate tranasfer from ATP to galactose
- Gal1p binding to Gal80p is galactose dependent → rate of Gal1p signalling and flux depends directly on same molecular species, i.e. the Gal1p-galactose complex
- In contrast, the canonical galactose sensor Gal3p measures internal galactose concentration

Testing whether Gal1p senses galactose flux 

- A flux sensor will have signalling independent of sensor concentration, while a concentration sensor has signalling dependent on sensor concentration
- Construct strains where both endogenous galactose sensors (GAL1, GAL3) are deleted
- Also deleted enzymes involved in feedback mechanisms (GAL80, GAL2, GAL7, GAL10) as these feedback mechanisms affect galactose flux
- GAL signaling and galactose flux was measured while titrating GAL1 expression and external galactose concentration
    - All measurements fall along the same line no matter the concentration of GAL1 ⇒ flux-sensor
- GAL signaling and galactose flux was also measured while titrating the canconical galactose sensor Gal3p
    - Deletion of endogenous GAL1 gene abolishes galactose flux → SpGal1 expressed to supply complementary galactokinase activity
    - GAL signalling increased with flux, but relationship between flux and signaling depends on Gal3 levels ⇒ concentration sensor

- In systems where transcriptional feedback is intact, flux sensor can be differentiated from a concentration sensor when the sensor level is high
- When the sensor level is high, the flux sensor signaling is independent of sensor levels due to
    - Higher sensor levels increasing number of sensor proteins
    - Higher sensor levels decreases internal nutrient concentration due to catalytic activity of flux sensor
- Concentration sensors do not decrease internal galactose concentration ⇒ at high sensor levels, sensor signalling is still dependent on sensor levels
- At very high sensor levels, signaling downstream is saturated so any further increase in sensor level will not change signalling output
- At low sensor levels, the rate of galactose uptake exceeds galactose metabolism → intracellular galactose concentration is independent of galactokinase levels (rather it depends on galactose uptake rate)

Constructing strains with only flux sensing or concentration sensing 

- Strain lacking flux sensing has unstable GAL signalling
- Strain lacking concentration sensing has stable GAL signalling
- in the absence of galactose flux (i.e. no galactokinase expression), concentration sensing alone leads to stable GAL signalling

*As long as there is flux, flux-sensing is needed to stabilising signalling.