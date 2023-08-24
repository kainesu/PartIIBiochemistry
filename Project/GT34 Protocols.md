# Protocols
[[Polysaccharide analysis by carbohydrate gel electrophoresis (PACE)]]

[[Raising tobacco plants]]

[[Colabfold]]

[[Hemicellulose extraction]]

[[CjMan26A digestion]]

[[Agrobacterium liquid culture]]

[[Agrobacterium infiltration]]

[[Ethanol precipitation for polysaccharide cleanup]]

[[Microsome extraction from tobacco leaves]]

[[Bradford Assay]]

[[PAGE#Running PAGE (Dupree lab system)]]

[[Western Blot]]

[[GT34 in-vitro activity assay]]

[[GT34 in-vitro competition assay]]

[[Purification of GT34 proteins]]

[[Structural analysis of GT34s]]

[
# Workflow overview (so far)
```mermaid
graph TD 
id1.1(Raise tobacco plants)
id1.2(Prepare liquid cultures of Agrobacterium)
id1.3(Agrobacterium infiltration)
id1.4(Harvesting of tobacco plants)
id1.5(Microsome extraction)

id2.1(Hemicellulose extraction)
id2.2(CjMan26A digestion)
id2.3(ANTS derivatisation)
id2.4(glucosidase and mannosidase digest)

id3.1(Cast PACE gel)
id3.2(Run PACE gel)

id4.1(in vitro reaction)

id5.1(Bradford assay)
id5.2(SDS-PAGE)
id5.3(Western Blot)

id1.1-->id1.3
id1.2-->id1.3-->id1.4--> id1.5
id3.1-->id3.2

id2.1-->id4.1-->id2.2-->id2.4-->id2.3-->id3.2
id1.5-->id4.1
id1.5--check for protein expression-->id5.1-->id5.2-->id5.3

```


```mermaid
graph TD
id1.3(Agrobacterium infiltration)
id1.4(Harvesting of tobacco plants)
id1.5(Microsome extraction)

id2.1(Hemicellulose extraction)
id2.2(CjMan26A digestion)
id2.3(β-Glucosidase and β-Mannosidase digestion)
id2.4(α-galactosidase digestion)
id3.2(Run PACE gel)

id4.1(In vitro reaction)
id4.2(with NDP-sugar)
id4.3(without NDP-sugar)

id2.1-->id4.1--MAGT activity assay-->id2.2-->id2.3-->id3.2
id2.3-->id2.4-->id3.2
id1.3-->id1.5-->id4.1
id4.1--XXT activity assay-->id3.2

```


