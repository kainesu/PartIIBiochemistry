**How do transcription factors find their target sites in the genome?**
(copied from BMB essay: How do sequence specific DNA binding proteins locate and dock at their cognate binding sites?)

# Introduction 
DNA binding proteins mediate numerous functions in cells, with gene expression and regulation perhaps being the most important as it determines cellular fate. As such, it is critical that DNA binding proteins are able to locate and dock at their cognate binding sites while avoiding non-specific sites to avoid misexpression of genes. This can often be a challenge because the cognate binding site for any particular protein makes up only a small proportion of total DNA in the genome. Fortunately, DNA binding proteins have evolved a number of ways to search for and bind stably to their corresponding sites. 

# Main 
To locate their targets, DNA binding proteins use a combination of **3D diffusion and facilitated diffusion**. 3D diffusion involves a “random walk” where the protein samples different sites along the DNA chain that may be located relatively far from each other. Using single molecule tracking, Normanno et al (2015) showed that TetRs tend to search for target DNA predominantly via  3D diffusion. 

# Facilitated diffusion 
However, the rate of 3D diffusion could not sufficiently explain the association rates of many DNA binding proteins which were more rapid than the theoretical diffusion limit. Notably, Riggs, Bourgeois & Cohn (1970) reported that the association rate for the lac repressor was two orders of magnitude higher than what was expected in theory. **Facilitated diffusion** turned out to be the answer to this problem. Through nonspecific interactions with DNA, such as via electrostatic or hydrophobic interactions, DNA binding proteins can accelerate their localization to cognate binding sites. This is because facilitated diffusion **restricts the dimensionality of DNA site search**, which reduces the sampling space compared to 3D diffusion. Berg, Winter & von Hippel (1981) demonstrated this by changing the salt concentration to affect non-specific DNA-protein interactions. When non-specific interactions were weakened, the time taken for the lac repressor to locate the operator decreased as well. 

## 1D sliding 
There are **three main modes of facilitated diffusion**. The first is **1D sliding**, where a protein binds to a non-specific site then slides along the DNA chain. The protein is able to test many sites for the correct sequence in a single association event. The length of each slide has to be optimised – the sliding length cannot be too short, as this would limit the number of sites to sample. On the other hand, an overly long sliding length could result in redundant searches as the protein can slide in both the forward and reverse direction, and so sample sites that it has previously passed over. The sliding length may also depend on the strength of non-specific DNA-protein interactions. The lac repressor, for example, has an average sliding distance of 45 base pairs (Hammar et al 2012). The lac repressor actually slides over its target site frequently without docking, so for such proteins it may be advantageous to have a longer slide length to improve the chances of docking. 

## Hopping 
Secondly, proteins can search for their cognate sites via **“hopping”**, which involves a series of association and dissociation events between nearby sites on the same DNA chain. This is distinct from 3D diffusion in that the protein stays in close proximity to the DNA. **Proteins usually alternate between sliding and hopping**, and experimentally this makes the two mechanisms appear similar. However, Gowers, Wilson & Halford (2005) provided evidence for a hopping mechanism using the BbvCI restriction enzyme. They incubated the enzyme with DNA containing pairs of recognition sites, either as direct repeats or as inverted repeats, then measured the processivity of digestion. Sliding would not allow the enzyme to cleave at the inverted repeat since it would have to turn around on the DNA. The study eventually found that the enzyme was indeed equally processive on both DNA fragments, suggesting that localization involves at least one dissociation and reassociation step. 

![[Pasted image 20230528132957.png]]
![alt_text](images/image1.png "image_tooltip")

## Intersegmental transfer 
The third mode of facilitated diffusion is **intersegmental transfer**. The protein moves between two sites via an intermediate loop where the protein binds to two sites at the same time. This would require that the protein has two DNA binding sites, and often the protein has a tetrameric structure like the lac repressor. Apparently, sites that are ~400 bp apart are optimal for this type of transfer as shorter distances would require intervening DNA to bend (Gowers, Wilson & Halford 2005). 
![[Pasted image 20230528133011.png]]
## Caveats 
The caveat of facilitated diffusion strategies is that **these mechanisms could still slow DNA search because of the time spent bound to non-specific DNA.** Also, overcrowding of proteins on chromosomes could slow down facilitated transfer through collisions and blocking of target sites (Li et al 2009). As such, DNA binding proteins still make use of 3D diffusion which provides wider coverage of the DNA than 1D methods. In particular for eukaryotic cells, the search process is dominated by 3D diffusion. Both Chen et al (2014) and Normanno et al (2015) have demonstrated this with Sox2 and TetR respectively using single molecule tracking. A possible reason for this could be that eukaryotic DNA is less accessible due to nucleosome packaging. 

# Major groove recognition
Implementation of the above strategies would require that the** protein is able to discriminate between specific and non-specific targets**. The **major groove** of DNA is usually responsible for mediating specific interactions as it is information-rich, being more distinct between the 4 base pairs than the minor groove. It is also more readily accessible to amino acid R groups in the B form of DNA. 
![[Pasted image 20230528133021.png]]
Major groove interactions typically involve hydrogen bonding and electrostatic interactions between polar R groups and nitrogen and oxygen in DNA, although non-polar interactions are present as well. As DNA binding proteins are able to recognize bases without needing to unwind the helix, less energy is required for DNA binding. 

**The DNA major groove is recognized by a number of different DNA binding domains**. Many have helix-turn-helix motifs, with one helix acting as a recognition helix that docks into the major groove, and the other acting as a stabilizing helix that makes non-specific electrostatic contacts with the DNA backbone. Catabolite Activator Protein (CAP) in prokaryotes has such a motif, with hydrogen bonding between R180, Glu181 and R185 in the recognition helix and the major groove at the CAP binding site. Eukaryotic DNA binding domains also often contain helix-turn-helix motifs, such as the homeodomain in yeast alpha2 repressor. Other DNA binding domains include the C2H2 zinc finger, which has a ββα structure with Zn tetrahedrally coordinated between Cys residues in the β strands and His residues in the α helix. The α helix acts as the recognition helix. Another binding domain is the basic zipper, which consists of 4-5 leucine residues exactly 7 amino acids apart in an α helix. Since a-helices have 3.5 residues per turn, the leucine side chains are displayed on the same side of the α helix, allowing helices to interact via non-polar interactions to form a coiled-coil. The helix docks into the major groove to make sequence-specific interactions, and an N-terminal extension of the helix contains basic residues to interact with the DNA backbone electrostatically. 

# Minor groove recognition 
However, there are **a few DNA binding proteins that use the minor groove to identify their cognate binding sequence.** Such proteins usually obtain information from DNA conformation, often involving bending of the DNA, which gives them an “indirect readout”. For example, the TATA binding protein (TBP) recognizes the TATA element via the minor groove. When TBP binds to the TATA box, Phe residues intercalate between the end bases, which causes the DNA to bend by 80° and changes the shape of the minor groove to be wider and flatter. TBP is then able to recognize the TATA element by the way the DNA bends, as A-T base pairs are more readily distorted. Such a readout method allows TBP to bind to a variety of DNA targets with high affinity even if they do not match the TATA consensus sequence well (Bareket-Samish, Cohen & Haran 2000). Integration Host Factor (IHF) is another such protein – in its case it causes DNA to adopt a distinct conformation of alternating wide and narrow minor grooves. 

# Specificity 
Apart from being able to identify specific targets, **DNA binding proteins have to avoid non-specific off-targets as well**. To accomplish this, DNA binding proteins often have negative selector domains or subunits that weaken non-specific interactions. For example, σ1.1 in prokaryotic RNA polymerase occupies a downstream DNA binding cleft. This interaction is only displaced upon binding to the cognate promoter. In eukaryotes, the telomere-binding protein TRF1 has residues that decrease affinity for off-target sites, either through electrostatic repulsion or unmatched hydrophobic contacts (Wieczór & Czub 2017). 

**Once a DNA binding protein has docked at its cognate binding site, the DNA-protein complex may be further stabilized by non-specific interactions.** Prokaryotic RNA polymerase has mobile pincers to enclose 20bp of downstream DNA. Also, the yeast alpha2 repressor forms hydrogen bonds between arginine residues and minor groove acceptors, on top of the specific hydrogen bonds formed with the major groove. 
![[Pasted image 20230528133033.png]]
**Other proteins may be necessary to stabilize the DNA-protein complex**. This regulates the binding activity of the protein. For example, RNA polymerase can only bind to the lac promoter with high affinity in the presence of CAP. The α C-terminal domain of RNA polymerase interacts with DNA-bound CAP, which recruits it to the promoter. Trans-activating factors in eukaryotes also play a similar role, with factors bound at the enhancer and the promoter directly interacting with looping of the intervening DNA. 

# Conclusion 
The way in which DNA binding proteins seek out and bind to their cognate binding proteins is a complex process, and models for DNA binding are continually evolving. The numerous features that DNA binding proteins possess confer a high degree of affinity and specificity for their cognate sites despite having to search a large sample space. Studying these localization mechanisms will help in our understanding of gene expression and regulation. 



# Discarded
* Proteins locate their DNA target sites through a combination of 3D diffusion and 1D facilitated diffusion 
    * E.g. Chen et al (2014) showed that Sox2 locates targets through a combination of 3D diffusion and 1D facilitate diffusion via single molecule imaging – using TMR-labelled Sox2
* 3D diffusion 
    * Higher protein concentrations favour 3d diffusion over facilitated
        * Wang et al (2013) reported that the percentage of lac repressors that bind to operator via 3D diffusion alone increased when they increased the concentration of lac repressor
    * At cellular concentrations in E. coli, RNAP is able to search for target site relatively quickly using 3D diffusion alone while lac repressor relies on facilitated diffusion – RNAP is more abundant in the cell than lac repressor
        * TFs like lac repressor tend to be expressed in low numbers – so rely more on facilitated diffusion?  
    * The rate of 3D diffusion is also affected by nuclear architecture. Proteins are often sampling for target sites in a dense environment e.g. nucleus, nucleoid 
* **Facilitated diffusion **Many proteins seem to locate target DNA faster than can be accounted for by 3D diffusion alone. Non-specific binding accelerates binding to specific sequences 
    * 1D sliding 
        * During sliding, every site is tested – in one association event, the protein can test many sites 
        * Sliding length depends on strength of non-specific DNA-protein interactions (Halford & Marko 2004) e.g. for lac repressor, sliding length is ~100bp 
        * Sliding length has to be optimised – Sliding length cannot be too short since it would limit the number of sites to sample. However, since the protein can slide in either direction there is a chance of redundant searches if the sliding length is too long (Gowers, Wilson & Halford 2005) 
        * The lac repressor frequently slides past its target site without docking, so having more non-specific interactions is optimal for docking as fast as possible (Hammar et al 2012) 
    * 1D hopping: Protein “hop” from one site to another site nearby in the chain (a rapid series of dissociation and association events)  but occasionally to a sequence distant site in the same chain and even more rarely to another DNA chain 
        * Proteins alternate between sliding and hopping. Experiments to distinguish between sliding and hopping: 
            * FRAP experiments show that repair endonuclease transfers between sites of DNA damage via free solution (Halford & Marko 2004 - ref 65) 
            * In another experiment (Halford & Marjo 2004 - ref 17), a circular DNA was converted to a catenane where the non-specific DNA formed the larger ring and specific DNA the smaller ring. There was no significant difference in search rate between protein + normal plasmid and protein + catenane even though binding to cognate site in catenane would definitely require 3D diffusion 
    * Berg et al demonstrated that non-specific interactions are important in locating binding sites. By changing the salt concentration to affect the strength of non-specific interactions, they changed the time it took for DNA binding proteins to locate the target DNA 
    * Intersegment transfer (helped by tetramer structure where protein has two binding surfaces e.g. Lac) – protein moves between two sites via an intermediate loop where the protein binds to two sites concurrently 
        * Apparently sites ~400bp apart are optimal for this form of transfer – shorter distances would require intervening DNA to bend (Gowers, Wilson & Halford 2005)  
    * However, these mechanisms could also slow DNA search because of time spent bound to non-specific DNA 
        * To search for the cognate site quickly, the protein cannot spend too much time bound to non-specific DNA
        * 3D diffusion still has a role in sampling different sites on the DNA – increasing coverage
        * Overcrowding on chromosomes could slow down facilitated transfer through collisions and blocking of target sites (Li et al 2009) 
    * In eukaryotic cells, nonspecific binding may actually be quite inefficient because of other DNA binding proteins or histones that are bound to the DNA – this has been shown for TetR (Normanno et al 2015), LacI (Elf et al 2007), and Sox2 (Chen et al 2014) 
        * For LacI in bacteria, the limiting step is diffusion; for TetR in human cells it is the association to nonspecific sites 
        * In contrast for prokaryotic cells, transient non-specific binding appears to dominate the search process (Stracy et al 2021) 



<p id="gdcalert5" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image5.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert6">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image5.png "image_tooltip")
(Redding & Greene 2013) 



* Specific interactions usually use major groove
    * Major groove is information rich as the major groove side is more distinct between the 4 base pairs than the minor groove side 
        * Draw diagram (see slide 15) 
    * Major groove interactions typically involve hydrogen bonding and electrostatic interactions between polar R groups and N/O in DNA, but non-polar interactions are present as well 
    * Major groove in B DNA is readily accessible to amino acid side chains of DNA binding proteins
    * Don’t need to open up helix to access bases to recognize sequence → less energy needed 
* However, there are a few DNA binding proteins that use the minor groove 
    * Obtain information from conformation – “indirect readout” that often involves DNA binding (Bewley, Gronenborn & Clore, 1998) 
    * E.g. TATA Binding Protein recognizes the TATA element to initiate basal transcription. Beta helix recognizes via minor groove 
        * Interaction between TBP and DNA mainly involves non-polar interactions 
        * Intercalation of Phe residues between bases 1-2 and 7-8 causes 80° bending and unwinding by 120° → minor groove widened & flattened 
        * Apart from Phe, other non-polar R groups in binding site interact with DNA bases via hydrophobic interactions
        * Specificity arises through “conformation effects” – i.e. TBP recognizes the TATA element by the way the DNA bends upon binding, as A-T bp are more readily distorted 
        * This also allows TBP to bind to a variety of DNA target with high affinity even if they do not match the TATA box consensus sequence well (Bareket-Samish, Cohen & Haran 2000) 
        * More severe bending of DNA correlated with more stable protein-DNA complex (Starr et al 1995) 
        * Flanking sequences may also be important signals (Bareket-Samish, Cohen & Haran 2000) 
    * E.g. IHF causes DNA to adopt a U-turn 
        * IHF causes DNA to have a distinct conformation of alternating wide and narrow minor grooves
* May need a cofactor to bind in an accurate manner 
    * E.g. σ subunit confers promoter recognition to prokaryotic RNAP, general transcription factors for eukaryotic RNAP 
    * GTFs assemble a “preinitiation complex” with promoter and Pol II in a stepwise manner – TFs recruited sequentially 
        * TFIID → TFIIA → TFIIB → TFIIF + Pol II → TFIIE, H 
    * At TATA box promoters, TBP without TBP Associated Factors (TAFs) sufficient for basal transcription; at non-TATA box promoters, or for activator-dependent transcription, TAFs required (as co-activators) 
* Many DNA binding proteins are dimers or tetramers to speed up the search rate (see tutorial notes) 
* Many dimeric DNA binding proteins have helix-turn-helix motifs that recognize 2 “half-sites” separated by 1 helical turn 
    *  σ factor domains 2 and 4
    * Lac repressor – N-terminal helix-turn-helix motifs of one dimer recognizes operator by docking into major groove 
    * CAP
        * 7aa “positioning” or “stabilizing” helix 2 makes non-specific electrostatic contacts with the DNA backbone 
        * 4aa beta turn 
        * 9 aa “recognition helix” 3 docks into the major groove, with sequence specific recognition by H-bonding e.g. between R180, Glu181, R185 side chains and base pairs, and van der Waals interactions 
            * R185, E181 recognize a GC base pair in the major groove 
* Eukaryotic DNA binding domains – sequence specific binding usually through docking of an alpha helix (recognition helix) into major groove
    * Homeodomain: Helix-turn-helix. H bonds form side-chains in helix 3 base pairs in major groove e.g. yeast alpha2 repressor. 
    * C2H2 zinc fingers: beta-beta-alpha structure, with Zn tetrahedrally coordinated between Cys residues in beta strands and His residues in alpha helix. Zn stabilizes the beta-beta-alpha structure, and recognition helix docks in major groove e.g. TFIIIA 
        * Each Zn finger can recognize 3-4 base pairs 
        * Binding sites not typically palindromic 
    * Basic zipper/leucine zipper/bZip: 4-5 Leu residues exactly 7aa apart in an alpha helix. Since alpha helices have 3.5 amino acids per turn, leucine side chains are displayed on the same side of the alpha helix → non-polar side chains interact to form a coiled-coil 
        * N-terminal extension of helix is basic to interact with P via nonspecific electrostatic interactions . Helix docks into major groove to make sequence-specific contacts 
    * Basic helix-loop-helix (bHLH) 
        * Similar to bzip but each subunit has two helices separated by a loop E.g. MYOD 
        * One helix NTD has electrostatic interactions with DNA 
        * Other helix acts as recognition helix that recognizes major groove 
    * Transcription activator-like effectors (TALEs) 
* Preventing non-specific interactions (negative selectors) 
    * RNAP: σ1.1 interacts with σ4 to prevent DNA binding (autoinhibitory) → specific promoter recognition only enabled when a part of holoenzyme 
        * In holoenzyme, 1.1 occupies a downstream DNA binding cleft → reduces non-specific DNA binding; interaction is displaced upon promoter binding
    * TRF1 has residues that decrease affinity for off-target sites (Wieczór & Czub 2017) 
        * Off-target binding is made unfavourable via electrostatic repulsion (D422) or unmatched hydrophobic contacts (V418) 
* In the first place, binding site has to be accessible to binding – chromatin packaging 

Dock



* After reaching target site, proteins also need to explore different configurations to dock 
    * Protein flipping (Ganji et al 2016) 
* Nonspecific and specific interactions: Non-specific interactions help to stabilize binding to DNA
    * E.g. RNAP has mobile pincers/jaws that enclose 20bp of downstream DNA in an elongating complex vs sigma subunit reduces non-specific binding
    * E.g. Apart from interactions between recognition helix and major groove, yeast alpha2 repressor has additional H bonds from Arg to minor groove acceptors 
* May interact with other proteins that increase binding affinity for the DNA → stabilize DNA-protein complex 
    * E.g. RNAP alpha CTD interacts with DNA-bound CAP which promotes RNAP binding 
    * Trans-activating factors – direct interaction between factors bound at enhancer and promoter with looping of intervening DNA 
        * Experiment (p134) – SV40 enhancer and beta-globin promoter on separate DNA fragments with biotin attached at end 
* Importance of being in the correct orientation e.g. CAP – requires binding of cAMP (inducer) to induce folding of 3 additional turns of helix in the dimerization domain → recognition helices rotated by 60° and brought 7angstroms closer → now in correct conformation for DNA binding 

DNA binding proteins: 



* RNAP
* Lac repressor 
* CAP 
* TFIID