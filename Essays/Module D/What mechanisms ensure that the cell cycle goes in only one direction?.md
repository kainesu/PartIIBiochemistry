**What mechanisms ensure that the cell cycle goes in only one direction?**
(Combine BMB essay + MZ's essay)

# **Introduction**

Progression through the cell cycle requires the coordinated activity of many different regulatory molecules. However, as all reactions are generally in equilibrium, the cell needs to take steps to ensure its unidirectional transition from one cell cycle phase to the next, as reversal or repetition of cell cycle events would be highly disruptive to cellular activities and hence viability. Cells make use of multiple molecular mechanisms and systems of activation to ensure cell cycle irreversibility. These include positive feedback loops, sequential degradation and coordinate phosphorylation/ dephosphorylation of regulatory molecules. 

# **1. Ultrasensitivity in signalling pathways allow for a switch-like transition from one cell cycle stage to the next**

To ensure the unidirectionality of the cell cycle, the CDK response to mitogenic signalling has to be "all-or-nothing". This is achieved via ultrasensitivity, whereby a system exhibits a sharp, sigmoidal response when the value of some parameter crosses a particular threshold. This results in a switch-like transition between two different states. 

[diagram of ultrasensitivity]

There are multiple mechanisms by which ultrasensitivity can be produced in the cell cycle. 

## Multiple phosphorylation 
Some cell cycle regulators contain multiple phosphorylation sites of differing affinities. The phosphorylation sites with high affinity are phosphorylated first by Cdks. This is because Cdks can phosphorylate them rapidly enough to compete with the action of dephosphatases, even when Cdk activity is low. On the other hand, phosphorylation sites with low affinity or only phosphorylated when the Cdk activity is high. In the case of Wee1, phosphorylation of the high affinity sites by cyclin B:cdk1 has no effect on its activity, while phosphorylation of the low affinity sites inhibits Wee1. This results in Wee1 activity exhibited a bistable response to cdk1 activity, since the level of active Cdk1 has to cross a particular threshold for the inhibitory sites to be phosphorylated. As Wee1 itself inhibits Cdk1, this double negative feedback loop results in a robust switch that facilitates the transition from G2 to M phase. 

Moreover, if phosphorylation is cooperative, where phosphorylated substrates are more likely to be phosphorylated again, the hypersensitive response becomes even more steep. in the case of APC/C, cyclin B:cdk1 phosphorylates APC/C first on the APC3 subunit. This creates a new binding site for Cdk1's own Cks subunit, causing Cdk1 to bind more tightly and recognise other phosphorylation sites with lower affinity, such as the one between APC1 and APC8. When this site is phosphorylated, polo kinase 1 can proceed to phosphorylate an adjacent site. Together, this displaces the autoinhibitory part of APC/C, activating the E3 ligase. As APC/C only becomes active when all sites are phosphorylated, there is again a threshold level of kinase activity needed for it to become active, thus generating another bistable response in the system. As APC/C drives the metaphase to anaphase transition, this again ensures a switch-like transition between different parts of the cell cycle. 

## Stoichiometric inhibitors
Stoichiometric inhibitors are another way to impose a threshold for signalling on the system. For example, when G1 cyclins accumulate in response to mitogenic signalling, their activity is inhibited at first due to p21 inhibition of CDKs. However, once G1 cyclins reach a concentration above that of p21, CDK activity can be seen since the excess CDK is not inhibited. An implication of this finding is that regulation of p21 levels can affect cell cycle progression. In fact, upon detection of stress, p53 is known to upregulate the expression of miRNAs that enhance the accumulation of p21, effectively arresting the cell cycle by raising the threshold for CDK activity. Hence, switches in the cell cycle can also be regulated by the cell in response to various stresses. 

**PP2A-B55δ is controlled by stoichiometric inhibitor ENSA**

## Competing substrates 
Cdks often have multiple substrates and these substrates can have different affinities for their cognate Cdk. Only when all higher affinity substrates are phosphorylated will the lower affinity substrates be phosphorylated. Without the high affinity substrates, Cdk activity cannot compete with the activity of phosphatases which immediately remove any phosphate groups on substrates. Phosphorylation of high affinity substrates "draws away" the phosphatases, thus improving the net rate at which lower affinity substrates are phosphorylated. This was shown in experiments in *Xenopus* egg extract. Yeast Sic1, a substrate for CDKs, was added to the egg extracts, and this resulted in response of Wee1 activity to cyclin-CDK activity even sharper. Yeast Sic1 is presumable the higher affinity substrate for cyclin-CDK. 

## Ultrasensitivity and feedback loops 
Ultrasensitivity is built into different kinds of feedback loops in the cell cycle. Positive feedback loops, such as between Cdc25 and CDK, or double negative feedback loops between Wee1 and CDK results in bistability. On the other hand, negative feedback loops such as between APC/C-Cdc20 and CDKs can result in oscillations. 

![[Pasted image 20230528133239.png]]
# **2. Sequential degradation of regulatory molecules ensures that each cell cycle transition is irreversible**

To prevent each cell cycle transition from reversing or repeating, the regulatory molecules that induce the occurrence of each cell cycle stage have to be degraded. Following the G2 to M transition, cyclin B is destroyed by APC/C which is maintained in the active state throughout G1. At the metaphase/anaphase transition, APC/C forms a complex with Cdc20 which targets cyclin B for degradation by acting as an E3 ubiquitin ligase that ubiquitinates cyclin B, allowing proteasomes to recognise and degrade it. This reduces cyclin B:Cdk1 activity. An experiment to demonstrate this involved in vitro chemical methylation of ubiquitin, which prevented the formation of ubiquitin chains, hence inhibiting cyclin B destruction. 
![[Pasted image 20230528133249.png]]
At the same time, APC/C targets securins for degradation, allowing sister chromatids to separate and the cell to progress to anaphase. The result is that anaphase proceeds at the same time as the previous mitotic stages are inhibited, preventing repeated rounds of mitosis. 

Subsequently, APC/C is activated by Cdh1 which confers a wider range of substrate specificities. Not only can it ubiquitinate cyclin B and securin, it can also target Cdc20 itself, Polo kinase and Aurora B kinase for degradation. Degradation of Cdc20  prevents anaphase from reversing by preventing other APC/C from binding to  Cdc20. APC/C continues to be active in G1 to target any remaining cyclin B for degradation, ensuring that another M phase does not occur. Again, progression through the cell cycle is linked to degradation of a molecule involved in a previous cell cycle stage to ensure that cell cycle transitions are unidirectional. 

Moreover, the APC/C:Cdh1 complex has differing affinities for each of its substrates. These differences in affinity can affect the order in which it interacts with substrates – higher affinity substrates tend to be interacted with first, followed by lower affinity ones. In this case, APC/C:Cdh1 has higher affinity for cyclin B and securin, and lower affinity for Polo kinase and Aurora B kinase. Apart from the APC/C:Cdc20 complex having a more limited range of substrates, this difference in affinity results in cyclin B and securin being degraded first, while Polo and Aurora B kinase are only degraded later and can persist until cytokinesis is complete. This ensures that separation of the chromosomes in anaphase (via securin degradation) occurs before cytokinesis (mediated by Polo and Aurora B kinase). Eventually, Polo and Aurora B kinase are degraded as well to prevent cytokinesis from repeating. 

# **3. Coordinated activity of opposing kinases and phosphatases ensures that orderly activation of regulatory molecules occurs**

Many regulatory molecules involved in the cell cycle are activated or deactivated by phosphorylation or dephosphorylation. As such, the order in which they are phosphorylated affects the order in which they become active. Tight regulation of phosphorylation/ dephosphorylation is achieved through circuits of kinases and phosphatases that interact with each other and can each be phosphorylated or dephosphorylated. 

In the G2/M transition, the action of cyclin B:Cdk1 is opposed by the phosphatase PP2A-B55. PP2A-B55 dephosphorylates cdc25 and wee1, resulting in deactivation of cdc25 and activation of wee1, promoting the phosphorylation and inactivation of cyclin B:Cdk1. As the cell enters M phase, rising levels of cyclin B:Cdk1 inactivate PP2A-B55 which prevents conversion of cyclin B:Cdk1 into the inactive state, reducing the reversibility of the G2/M transition. This is achieved by a system of regulatory molecules involving Greatwall kinase, α-endosulfine (ENSA), and PP1. cyclin B:Cdk1 phosphorylates Greatwall to activate it, which in turn phosphorylates ENSA such that it binds to and inactivates PP2A-B55. Although free PP2A-B55 can dephosphorylate ENSA, as ENSA is in great excess over PP2A-B55 and is constantly rephosphorylated by Greatwall, eventually all PP2A-B55 will be bound in an inactive form. Even after cyclin B:Cdk1 is degraded during mitosis, PP2A-B55 continues to be inhibited as there is still existing phosphorylated Greatwall and ENSA that take time to dephosphorylate. 
![[Pasted image 20230528133302.png]]
As the cell exits mitosis, cyclin B inhibition via degradation is accompanied by reactivation of PP2A-B55 which amplifies cyclin B inhibition, ensuring that the cell does not re-enter mitosis. During mitotic exit, the PP1 phosphatase auto-dephosphorylates to become active – it is also inactivated by cyclin B:Cdk1 via phosphorylation. PP1 dephosphorylates Greatwall, preventing it from continuously phosphorylating ENSA, hence allowing PP2A-B55 to escape inhibition. 

The reciprocal effects and inhibition of such kinase-phosphatase pairs accentuate the switch-like transitions in the cell cycle. It also creates redundancy in the signalling pathway such that the cell cycle order is resilient to mutations or other breakdowns in function of any one regulatory molecule. 

# **Conclusion**

Given the global effects that cell cycle transitions have on the cell, it is no surprise that cells have developed sophisticated systems of regulation for the cell cycle to ensure its orderly progression. Apart from affecting cell viability, control of the timing of cell cycle events also allows cells to co-inhabit multicellular systems where mistimed proliferation can result in tissue dysfunction. Understanding of these regulatory mechanisms is important as it would also allow us to understand what happens when orderly progression does not occur, such as in cancer. 