# Principle of NMR 

> [!summary] Summary
> - NMR produces chemical shifts for each nucleus in a molecule.
> - Chemical shifts are affected by the local chemical environment.

* For proteins to be studied in NMR experiments, they have to be labelled with spin active nuclei (<sup>13</sup>C/<sup>15</sup>N) by growing the cells in minimal medium containing <sup>15</sup>NH<sub>4</sub>Cl and <sup>13</sup>C<sub>6</sub>-glucose
* When spin-active nuclei are placed in an external magnetic field, they align themselves either against or with the field, resulting in nuclei with different energy levels 
* When this sample of spin-active nuclei is then irradiated with RF energy, the nuclei absorb this energy and "flip" between energy levels ("**resonance**"). The nuclei then to their original energy levels, emitting the absorbed energy as an RF signal, which can be measured 
* The frequency of the RF signal is indicated by the **chemical shift**. 
* The local chemical environment around a nucleus modifies the local magnetic environment it experiences, resulting in changes to the energy gaps between these energy levels, thus changing the chemical shifts. 
* NMR is thus able to give us information about the structures of molecules, and changes to chemical shifts tells us about changes in the environment around the nuclei

# Structural determination 
## Primary structure (peak assignment)
^3e4e6a
* Two main ways of spectra assignment – **through-bond experiments** and **through-space experiments **
* Both these types of experiments generate 2D NMR spectra 
	* Resolution can be further increased by spreading peaks into a 3rd or even 4th dimension 
	* Cross peaks in a 2D spectra highlight through-bond interactions (COSY/TOCSY) or through-space (NOESY), hence indicating how different protons in the protein are positioned with relation to each other 
![[image5 1.png|250]]

### Through-bond experiments 
* Relies on through-bond connections between spin-active nuclei via scalar couplings  
  ![[image2.png|175]]
* **2D`[`<sup>1</sup>H, <sup>15</sup>N`]`-HSQC experiments.** Cross-peaks link chemical shifts of all pairs of 1H and 15N nuclei connected by 1 bond 
* **13C HSQC experiments**. Cross-peaks indicate covalently bonded 1H-13C pairs
    * Peaks are not as well-resolved as in a 1H-15N spectrum because both shifts are strongly correlated with secondary structure (and hence with each other) 
* **3D HNC<sub>α</sub>C<sub>β</sub> experiment.** 
  ![[Pasted image 20221218201005.png|325]]
	- can be used to resolve a crowded 2D HSQC spectrum according to the chemical shifts of <sup>13</sup>C<sub>α</sub> and <sup>13</sup>C<sub>β</sub> within the <span style="text-decoration:underline;">same</span> amino acid residue
* **3D HN(CO)C<sub>α</sub>C<sub>β</sub>**. Similar to HNC<sub>α</sub>C<sub>β</sub> but measures chemical shifts of <sup>13</sup>C<sub>α</sub> and <sup>13</sup>C<sub>β</sub> in the amino acid of the <span style="text-decoration:underline;">previous</span> residue (the carbonyl C chemical shift is not measured) 
  ![[image9.png|225]]
- **Amino acid assignment**. Each amino acid has a different range of C<sub>α</sub> and C<sub>β </sub>shifts. 
	- Glycine residues are easily identified from 3D NMR experiments because they have no <sup>13</sup>C<sub>β</sub> and a  <sup>13</sup>C<sub>α</sub> = ~40 ppm. 
	- Pairs of <sup>13</sup>C<sub>α</sub> and <sup>13</sup>C<sub>β</sub> shifts as determined from HNC<sub>α</sub>C<sub>β</sub> and HN(CO)C<sub>α</sub>C<sub>β </sub>can be matched up to find adjacent residues in the primary sequence  
	-  Once amino acid types of three sequential residues are known, should be easy to identify their position in the primary sequence 
      ![[image1 1.png|225]]

### Through-space experiments 
* **Based on Nuclear Overhauser effect (NOE)** – used to measure short-range distances in protein structures. A detectable distance connection can be found between two H if they are less than 5Å apart 
  ![[image10 1.png|200]]
* **2D NOESY**. Crosspeaks show that one nucleus is close in space to another 
    * The closer two protons are to each other, the larger NOE 
    * NOEs can be spread (“edited”) into a third chemical shift dimension (<sup>13</sup>C or <sup>15</sup>N) in proteins isotopically labeled with <sup>13</sup>C and <sup>15</sup>N to provide higher spectral resolution 

## Secondary structure determination 
* NMR spectra of alpha helices are generally less well dispersed than beta sheets as there are a wider variety of environments in beta sheets 

## 3D structure determination 
^2fca58
### Generalised approach 
1. **Do resonance assignments** (see [[A4 NMR#Primary structure (peak assignment)|peak assignment]])
2. **Obtain structural restraints** from various NMR experiments (see below) 
3. **Computationally generate** an ensemble of 3D structures that are consistent with all experimental distance restraints 
	1. Computer software takes into account NMR-derived experimental structural constraints, along with other restraints based on the covalent structure of the protein (bond lengths, bond angles) and known atomic properties (atomic radius, mass, partial charge, etc.) 
	2. However, some parts of the structure may be poorly restrained, which could be due to protein dynamics or being under-restrained 
4. **Overlay all structures** in the ensemble to produce a resolved structure

![[image15.png]]

### Proton-proton distances 
Through-space experiments (e.g. NOESY) 

### Dihedral angles 
- Measure spin-spin coupling
- Database searches based on the chemical shifts (e.g. TALOS) 

 > Scalar couplings between nuclei that are separated by three covalent bonds vary in a predictable way depending on the dihedral angle about the bond connecting the nuclei” (Kwan et al 2011) 

### Hydrogen bonds
- H/D exchange experiments
- Measure spin-spin couplings across H bonds 

### Residual dipolar couplings (RDCs)
- Can bused to supplement NOE data when long-range NOEs are not abundant, due to lack of protons are lack of tertiary structure
- Highly sensitive to structural changes
- Measured from changes in scalar couplings and are dependent on orientation between bond vector and direction of magnetic field 
- #experimental_evidence Maudlin et al (2009) – used RDC values to show that MTX or TMP binding has little effect on holoenzyme structure
- #experimental_evidence Lange et al (2008) – used RDC values to refine solution structures of ubiquitin restrained by NOE data → ensemble of structures obtained comprises complete range of crystallographically observed structural changes upon interaction with binding partners ⇒ conformational change occurs prior to a binding event (conformational selection) rather than after (induced fit) 

### Paramagnetic relaxation enhancement 
- Introducing a paramagnetic moiety into the protein (e.g. nitroxide radical attached to cysteine) broadens the NMR signal of nuclei close to the paramagnetic centre, allowing for identification of nuclei close to moiety
- On 1H-15N HSQC, affected peaks may decrease in size (amplitude) or even disappear 
- Can be used as long-range distance restraints for structure calculations 
- Can be used to characterize short-lived encounter complexes
	- #experimental_evidence interaction between cytochrome _c_ and adrenodoxin
	- #experimental_evidence Mackereth (2011) – identification of two conformations of the RNA-binding RRM domains of U2AF65 which were distinguished by PREs in one domain after introducing a paramagnetic MTSL label in the other domain by SDM 
- Pseudo contact shift – introducing certain paramagnetic moieties can affect chemical shift of nearby nuclei to provide distance, angular information 

## Using NMR to study protein folding 
### Measure extent of folding 
* Folded proteins have more unique chemical environments within the protein than unfolded proteins → wider range of chemical shifts on NMR spectrum 
    * In unfolded proteins, all amides exposed to similar chemical environment (i.e. exposed to solvent) 
* In a folded protein, each residue is in a distinct chemical environment, such that the signals (e.g. H<sup>N</sup> nuclei signals) are at different chemical shifts (i.e. “well-dispersed”) 
* “High field” methyl signals (i.e. methyl signals at low chemical shift) are indicative of a folded protein – in a folded protein, methyl groups in hydrophobic side chains are docked up next to aromatic side chains → creates chemical shift changes 

### Measure stability of protein 
* Record a series of 1D <sup>1</sup>H or <sup>15</sup>N-HSQC spectra over time –appearances of new signals over the time course suggests degradation or unfolding 

### Studying folding pathways 
* #experimental_evidence 15N HSQC NMR was used to discover that α-lactalbumin undergoes a single transition between molten globule and folded states, while β-microglobulin does not fold in such a manner 

### Screening the effects of mutations 
* Introduce mutation into the protein, then observe effect of NMR spectrum – if signals become less well-dispersed, suggests that folding was affected 
    * 1H 1D and 15N-HSQC spectra can provide a simple assessment of how mutation affects folding 
* Can use NMR to understand how localized the effect of the mutation was – as each peak in the NMR spectrum reflects the local chemical environment 
    * The extent of changes in the NMR spectrum can indicate how critical the residue is to structure or dynamics of the  
* E.g. #comment Need to add an example here lmao 

# Using NMR to identify protein interactions 

## Protein-observed NMR 
* Allows for determination of binding affinity and binding mode, but is more laborious, so use for follow-up on hits 
* Requires larger quantities of protein, and protein must be isotopically labeled 
- #experimental_evidence Friberg et al (2012) developed inhibitors against myeloid cell leukemia by screening a library of fragments with SOFAST <sup>1</sup>H-<sup>15</sup>N HSQC

### Techniques 
#### H/D exchange
- When protein is dissolved in D<sub>2</sub>O, H/D exchange occurs in the amide backbone unless protected by H bonding  (e.g. protein-protein interactions)
    * Can watch signal in HSQC disappear when H exchanges for D → H signals that remain on HSQC are involved in interactions
    * #experimental_evidence Polshakov et al (2006) used HD exchange to study the interaction between apo-DHFR of _Lactobacillus casei_ and its complexes with trimethoprim (TMP), folinic acid and coenzymes (NADPH/NADP+). Signals that disappeared from the spectrum upon exposure to D<sub>2</sub>O correspond to protons that are not protected by interaction with the binding partner but are exposed to the solvent. 
        * Ligand binding causes more sites to become strongly protected, and this effect is spread throughout the protein because ligand binding makes the protein more rigid 

#### 2D NMR experiments  
- Titrate ligand against protein and observe changes in position and intensity of chemical shifts on 2D spectra (e.g.<sup>1</sup>H-<sup>15</sup>N HSQC spectra) 
	* Peaks from residues involved in ligand binding will have a change in peak position or intensity 
	* These chemical shift/intensity changes during titration can be fitted to determine K<sub>d</sub>
	* #experimental_evidence  interaction between phosphorylated kinase-inducible activation domain (pKID) and KIX domain of the CREB transcription factor was investigated by titrating KIX to <sup>15</sup>N-labeled pKID and analyzing <sup>15</sup>N-HSQC signal changes 
* Efficiency of ligand binding can be determined by comparing the spectra of different protein-ligand complexes – this can be used to identify high energy or intermediate states of the protein that are not identifiable from static views obtained from XRC/Cryo-EM
	* #experimental_evidence Solt et al (2017) showed that the size of the chemical shift upon agonist binding to β<sub>1</sub>AR is correlated with agonist efficacy 

#### NOE experiments for structures of complexes 
* Structures of complexes can be obtained by preparing NMR samples where only one of the components in the complex is isotopically labeled 
* Then run NOE experiments to observe which NOEs are within 1 subunit and those that involve both subunits, thus determining how the two subunits bind to each other 
* #experimental_evidence Zhang et al (2009) used this method to determine the structure of the S5a:K48-linked diubiquitin complex as well as its interactions with Rpn13 

## Ligand-observed NMR 
### Principle 
* Rather than observing chemical shifts in the protein, we can observe changes in chemical shifts in the ligand when bound to the target protein 
* When the ligand is in its free form, it has sharp peaks in the 1H spectrum. Upon addition of protein, peaks in the NMR spectrum broaden due to reduced tumbling (chemical exchange) when the ligand binds to the protein. Sharp peaks of the known ligand are restored if a fragment competes for binding. Thus, this method can be used for fragment-based drug discovery. 
	*  #experimental_evidence  [[A7 G proteins#Fragment-based drug discovery for Ras|FBDD for Ras]]
* Since no isotopic labelling of protein required, it is higher throughput than protein-observed NMR

### Techniques  
#### Saturation Transfer Difference (STD) spectroscopy
- Relies on NOE transfer of magnetisation from protein to ligand.
- Protein methyl groups are saturated by irradiating methyl signals
- Eventually, cross-saturation of the bound ligand causes the signal intensity to decrease (saturation transfer) 
    * Does not give information on binding mode ⇒ cannot distinguish between specific and non-specific binding interactions → need to follow-up on hits. 

#### Cross-saturation spectroscopy 
- If two interacting partners are labelled with different isotopes, nuclei on one partner can be selectively irradiated, and the effects on <sup>15</sup>N-HSQC spectrum of other partner can be observed
- Cross-saturation will only be observed for nearby nuclei vs in chemical shift mapping experiments where chemical shift changes can also be observed for residues far from the site of the interaction

#### WaterLOGSY 
* Fragments that bind to to the target protein are identified by positive resonances, and those that do not have negative resonances. Bound ligands in waterLOGSY are identified by peak inversions

# Using NMR to study protein dynamics
* Proteins are dynamic molecules with many different conformational states. 
* Transitions between different states can take place at different speeds ("timescales") depending on the activation energy barrier between the states
	* Enzymes have evolved to catalyze reactions at rates that fall within a relatively narrow range – k<sub>cat</sub> values generally fall in the range of 100-10000 s<sup>-1</sup> ⇒ protein motions in the μs to ms range may be important to enzyme function 
* NMR methods are able to capture a wide range of conformational changes that occur at different timescales 
![[image18.png|400]]

- Many of these NMR methods are based on the principle of **chemical exchange**. If two conformational states exchange with each other at a faster rate than the NMR timescale, then line broadening occurs as the chemical shifts of the peaks corresponding to each conformational state average out. This can occur even if one of the conformational states is sparsely populated. 
![[image6.png|475]]

## Fast motion (ps-ns) – Studying backbone dynamics and interactions 
### <sup>15</sup>N nuclear spin relaxation 
- After exciting the nuclei with an RF pulse, the nuclei relax back to their original energy states over time 
- Faster molecular motions lead to shorter relaxation times, while slow molecular motions lead to faster relaxation times. 
* 3 parameters measured – Longitudinal relaxation time (T<sub>1</sub>), Transverse relaxation time (T<sub>2</sub>), {<sup>1</sup>H}-<sup>15</sup>N NOE 
    * **Longitudinal relaxation time** is the time taken for the excited nuclei to return to their original energy state. 
    * **Transverse relaxation time** is the time taken for the nuclei to lose coherence, i.e. lose synchrony with each other. Synchrony between the nuclei occurs at the start of the NMR experiment when the nuclei are first excited. 
    * **{<sup>1</sup>H}-<sup>15</sup>N NOE** is the change of intensity in the <sup>15</sup>N signal when <sup>1</sup>H<sup>N</sup> (H attached to N) is irradiated. This signal is highly sensitive to rapid local motions. 
* T<sub>1</sub> and {<sup>1</sup>H}-<sup>15</sup>N NOE directly report on ps to ns time scale motions 
    * Can be used to detect the global motion of the protein (e.g. tumbling, brownian motion) which occurs on an nanosecond timescale
    * Can be used to detect local motion in internal sites in the protein (e.g. libration of NH-N bond vector around an axis) which occurs on a picosecond timescale 
* T<sub>2</sub> is affected by conformational changes on μs-ms timescale 
	* Most sites should have a similar value due to global motion of the protein, but local dynamic regions should have larger values of T2 due to rapid local motions at ps timescale 
* Each parameter can be measured for each amino acid residue in a protein to identify highly dynamic local regions within the protein and also measure the rate of these conformational changes. 

#### Model free relaxation analysis 
![[image14.png|350]]
* In this method, the relaxation rates measured are analysed without assuming a certain model of of the motion involved (compare with [[A4 NMR#Relaxation dispersion|Relaxation dispersion]])
* The relaxation rates are then fitted to a mathematical function described by the several key parameters
* One of these parameters, the **order parameter** S<sup>2</sup>, describes the relative contributions from local and global motion at a particular backbone site
    * If S<sup>2</sup> ~1.0 ⇒ global motion dominates => more restricted local motion
    * S<sup>2</sup> ~ 0.0 ⇒ local motion dominates (local region is more dynamic than the protein as a whole) 
    * If S<sup>2</sup> is not close to 1.0 or 0.0, suggests an “exchange contribution” (R<sub>ex</sub>) which is an indication of exchange between multiple conformational states 
* #experimental_evidence  in DHFR, “Well-structured” regions have S<sup>2</sup> values ~0.8, while regions with S<sup>2</sup> ~ 0.6 indicate backbone flexibility within the three loop regions or at the N- and C-termini 
* #experimental_evidence Maudlin et al (2009) – DHFR binding to substrate-mimetic drugs, anti-cancer agent methotrexate (MTX) and antibiotics trimethoprim (TMP) resulted in changes in ps-ns backbone amide and side-chain methyl group dynamics → holoenzyme became more rigid 

### Chemical shift prediction and molecular dynamics
* Chemical shifts can be predicted from protein structure coordinates with reasonable accuracy, and the differences between experimental and such back-predicted shifts can be used to guide calculation of models of protein structures 
* Chemical shift changes can also be used to predict the structures of transiently populated states 
    * E.g. Neudecker et al (2021) – Took into account backbone chemical shifts to restrain structure calculations → predicted the structure of the folding intermediate of the Fyn SH3 domain 
* MD simulations describe the trajectory of a protein by solving Newton’s laws of motion for all of its constituent atoms and recording their coordinates as a series of consecutive snapshots 
    * Limitation – MD simulations have to be calibrated with experimental data 
    * Chemical shift data can be incorporated into MD simulations 

### Paramagnetic relaxation enhancement
See [[A4 NMR#^2fca58|3D structure determination]]
Can be used for both fast and slow conformational changes. 

## Slow motion (μs-ms) 
* Slow time scale motions are important for catalysis 
    * E.g. Analysis of multiple species in catalytic cycle of dihydrofolate reductase
* Inhibition may not simply involve competition for a binding site, but also disruption of motion at a distal site 
    * E.g. In protein-drug complexes of DHFR with anti-cancer drugs, there are slow motion dynamics in the drug/substrate-binding site that resemble those in the holoenzyme, while slow motions in the cofactor-binding site appear quenched 

### T2 measurements 
See [[A4 NMR#<sup>15</sup>N nuclear spin relaxation|15N nuclear spin relaxation]]

### Relaxation dispersion 
- Relaxation dispersion experiments are used to characterise exchange between different conformational states of a molecule.  
- In the different conformational states, the molecule has different chemical shifts, which in turn affect nuclear spin relaxation rates
- **These spin relaxation rates (longitudinal or transverse) are measured in response to varying experimental parameters**, which can be the relaxation delay (Carr-Purcell-Meiboom-Gill, or CPMG) or spin-lock field strength (R1p). Varying this parameter varies the effect of chemical shifts on the spin relaxation rates. 
- **The data is then fitted to an exchange model**, which involves determining the rate of exchange (kinetics), populations of the two states (thermodynamics), and the chemical shift differences between the two states (structure), such that the difference between the experimentally acquired data and model-predicted relaxation rates is minimised 
- Extraction of these parameters thus provides information about the conformational states that the molecule exists in. 
* #experimental_evidence Boehr et al (2006) used CPMG-RD experiments to characterize the chemical exchange between different intermediate states in the DHFR catalytic cycle 
    * The enzyme in each intermediate state also has access to a minor state – these minor states are accessed 1 or 2 more times before the next step in the catalytic cycle, which suggests that the enzyme needed to access a minor state that resembles the following ground state in the catalytic cycle before transitioning into the following ground state 
        * In fact, the chemical shift difference between the DHFR ground states E:THF:NADP+ and E:THF (which follows it in the catalytic cycle) was found to be similar to the chemical shift difference between the major and minor conformational states of E:THF:NADP+ ⇒ minor state of E:THF:NADP+ likely adopts a similar structure to E:THF (Boehr et al 2006) 
* #experimental_evidence Maudlin et al (2009) used CPMG-RD experiments for the DHF holo-enzyme in the presence of MTX, TMP to show that drug binding slows motion in the substrate binding pocket and prohibits functional conformational changes in the loop regions 
* #experimental_evidence Carroll et al (2012) showed with CPMG-RD experiments that when E. coli DHFR was bound to a series of competitive inhibitors with varying affinities, the rate of access of the alternative conformation correlated well with inhibitor affinity 
    * Since the association rate of the inhibitors with the enzyme were similar ⇒ accessing the alternative conformation may be the limiting step for ligand dissociation 

### <sup>15</sup>N HSQC
* Counting signals can reveal a dynamic process – e.g. The <sup>15</sup>N-HSQC of the YPM antigen from _Yersinia pseudotuberculosis_ only has 100 signals despite 140 being expected, due to several loops undergoing conformational exchange at the μs-ms timescale 
    * Notably, these loops were well-ordered in XRC ⇒ if the activation barrier to movement is comparable to the amount of thermal energy in the sample, then protein dynamics can be missed in crystal structures 

### Real-time NMR 
* Slow changes can be followed directly in real time by acquiring consecutive NMR spectra
* E.g. <sup>19</sup>F NMR to follow sidechain indole signals from <sup>19</sup>F-labelled Trp residues as DHFR refolds following denaturation 
* E.g using <sup>19</sup>F NMR to monitor the response of TM6 and TM7 of β<sub>1</sub>AR. M283 in the tip of TM6 difficult to study via NMR due to low peak signal in <sup>13</sup>C-<sup>1</sup>H NMR, so use <sup>19</sup>F instead

## Even slower motion (>ms) 
### H/D exchange 
- Amide protons are exchanged very slowly with D because most amides from structured parts of a folded protein are involved in intramolecular hydrogen bonding – an unfolding event is required to break the hydrogen bonds for H/D exchange to occur 
- Dependence of amide proton exchange on the level of denaturant can indicate which regions fold independently of other parts of the protein 

### ZZ exchange experiments 
* #experimental_evidence Bosco et al (2002) used ZZ-exchange experiments to show that cyclophilin A catalyzes the cis/trans isomerisation of the Gly89-Pro90 peptide bond in the N-terminal domain of the HIV-1 capsid. 

### 2D EXSY for studying alternative binding modes
* EXSY = Exchange Spectroscopy – basically NOESY when used to detect chemical and conformational exchange 
* In 2D EXSY, signals on the spectrum indicate particular binding modes and cross-signals indicate which binding modes interconvert 

# Membrane protein NMR 
- #experimental_evidence VDAC-1 structure determination – using solution NMR with TROSY, deuteration, and methyl protonation to improve resolution
	- Another study used solution NMR and X-ray crystallography together, with XRC being used to obtain an accurate but low res (4Å) structure that was then used to refine the NMR structure 
	- A subsequent NMR study with VDAC-1 embedded in nanodiscs was done to show that the N-terminal helix of VDAC-1 moves to regulate the opening of the channel. 
- #experimental_evidence β<sub>1</sub> adrenergic receptor – using both uniform labelling and selective labelling (via post-translational labelling) 
	- #question What is the advantage of using selective labelling over uniform labelling? Is it for peak assignment? 

# Causes of poor NMR spectra
* Protein aggregation
* Incomplete folding – molten globule state → slow interconversion between various tertiary structures, but secondary structures are still intact
* Protein is folded incorrectly
* Inclusion of overly long unfolded tails → viscous drag on protein tumbling 
    * Getting the right length or construct of protein is important! 
* Protein is too large – challenging to acquire spectra of proteins larger than ~50kDa and in general most NMR-derived structures are for proteins of ~30 kDa
    * As size of molecule increases, tumbling time increases → NMR excited state becomes more short-lived → transfer of magnetization through scalar couplings becomes less efficient → poor quality triple resonance experiments (broader, low intensity signals) → lower sensitivity and resolution → difficult to do resonance assignment 
    * Also, large proteins have more nuclei resulting more signals → spectra become more complex, and overlapping signals make peak assignments difficult (particularly if they are broad!) 
* Macromolecules with extended shapes have broader lines than more globular molecules of the same mass 
* Composition and concentration of buffer components – there is no simple and rapid way of screening buffers similar to how XRC screens crystallization conditions, as the only way to tell if the spectra will be good is to acquire a spectrum 
* NMR is only useful for diamagnetic species – paramagnetic species can distort nearby signals. This can make it difficult to study many enzymes with metal cofactors 
	* e.g. For LPMOs, NMR cannot be used to study the Cu(II) form which is paramagnetic 
	* In this case, EPR spectroscopy has been used to exploit the paramagnetism of Cu(II) 

# NMR developments
## Optimising buffer conditions 
* Automatic NMR sample changers – would help with screening NMR buffers 
* “In-cell” NMR aims to replicate _in vivo_ conditions as far as possible – changes in the structure of the protein in the cell investigated by monitoring chemical shifts in 15N-HSQC spectrum 
    * E.g.  Sakai et al (2006) used in-cell NMR spectroscopy in _Xenopus laevis _oocytes to study <sup>15</sup>N-labelled ubiquitin and calmodulin and their interactions within the cell. 

## Improving the size limit of NMR 
* Deuteration – express protein in D<sub>2</sub>O or <sup>2</sup>H-glucose to deuterate sidechains 
    * This improves spectral quality (sharper lines, better sensitivity + resolution) as it weakens the dipole-dipole interactions between neighboring protons  
* Transverse Relaxation Optimised Spectroscopy (TROSY)-based methods slows down relaxation (T<sub>2</sub>), which results in sharper peaks 
    * E.g. TROSY-based methods were used to solve structure of malate synthase G, which is 82 kDa 
    * Combining deuteration and TROSY allows for structural studies up to 150 kDa!
* Methyl protonation – reintroduce protons for Ile, Leu, Val, Ala while other amino acid side chains are deuterated 

## Solid state NMR 
* Protein solid state NMR is useful for solving the structures of hard-to-crystallize proteins, e.g. integral membrane proteins, natural aggregating proteins (fibrillar, amyloid) 
    * Solid state NMR was used to solve the structure for the integral membrane KcsA potassium channel, Alzheimer’s disease-related peptide Aβ(1-40) 
* Can be thought of as an extreme form of solution NMR where the molecules have stopped tumbling 
* Proteins in solid samples can be 
    * Oriented e.g. in a crystal
    * Uniaxially oriented (e.g. in stacked phospholipid bilayers)
    * Unoriented e.g. in a powder 
* Depending on the orientation of the molecule in the applied magnetic field, the NMR results (e.g. chemical shift, dipolar interactions) will differ  
![[image8.png|475]]

- If we spin the microcrystalline solid at a “magic angle” (magic angle spinning), the rapid reorientation averages anisotropic interactions to zero, which allows signals to be resolved → sharper peaks  
  ![[image13 1.png|500]]
    * However with MAS, we are not able to obtain information on how membrane proteins are oriented in a bilayer, so we need to orient the samples in a membrane to obtain that information. This can be done mechanically with glass/polymer plates, or magnetically 

> [!Note]- Advantages of solid state NMR (Bostock et al 2019)
> “NMR linewidths, an important factor for NMR data analysis, are normally proportional to the tumbling rate (τc− 1), so large molecules which have slow tumbling rates (τc− 1 ~ 0.75 kT/πr3η, where r = molecular radius and η = viscosity) will give large linewidths, which preclude structural analysis. In solNMR, the molecule needs to tumble rapidly and isotropically in solution on the NMR time scale (~ 10− 1–10− 6 s). Thus, all orientational information is lost as a consequence of isotropic tumbling, but fast tumbling averages dipolar interactions to zero and chemical shifts to isotropic values, resulting in sharp NMR resonances. Although transverse relaxation optimised spectroscopy (TROSY) and deuteration techniques provide the possibility to study biomolecules with sizes exceeding a molecular mass of 100 kDa by solNMR [39], [40], traditional solNMR is of limited use for structural studies on large proteins, membrane proteins and solid materials, because long correlation times or restricted motions result in incomplete averaging of the anisotropic interactions leading to the broadened spectrum. Also, in the case of membrane proteins, it is generally difficult to keep these proteins active at high concentration at room temperature for the experimental time required to gain spectra with high signal-to-noise ratio and resolution. SSNMR can overcome these averaging limitations to provide structural and dynamic information on proteins and their bound ligands [41], [42]. The technique is designed to elucidate structural parameters of slowly tumbling or solid-phase samples at atomic resolution. It is also useful for orientational studies, and has no theoretical limit of size [41], [42].
> 
> Unlike solNMR, the resolution and sensitivity of SSNMR are affected by the size and orientation-dependence of the nuclear spin interactions, i.e. the chemical shielding and the homonuclear and heteronuclear dipolar spin–spin couplings. These interactions are not averaged to zero, usually generating line-broadening for resonance SSNMR spectra of a static sample. Sample orientation or high spinning of a sample at the magic angle spinning (MAS), together with isotopic labelling, can improve both resolution and signal-to-noise ratio.
> 
> SSNMR has been developing rapidly for in particular, the study of membrane proteins and other non-soluble or large biological molecules, since crystals and rapid isotropic tumbling are not necessary. It has the potential to gain accurate internuclear distances and orientations which give information about molecular structures [43]. SSNMR has been employed to provide structural and mechanistic insights of many membrane proteins including GPCRs, reviewed [44], [45], [46], for example rhodopsin [37], [47], H1 receptor [38], sensory rhodopsin II [48], bacteriorhodopsin [49], [50], [51], [52], and phage-coat proteins [53], [54], [55].”

# Links to other topics
- NMR can be used to study [[B1 Transcription#NMR chemical shift|DNA-protein interactions]]
- Studying [[A7 G proteins#NMR|G proteins]] dynamics 
- Solid state NMR used to study structures of [[C6 Cell walls, energy, materials#^1f1359|cellulose]] and [[C6 Cell walls, energy, materials#^8b723a|xylan]]
- NMR can be used to guide directed evolution – see [[BhattacharyaEtAl_2022]]
- [[B5 Translation and translation regulation in eukaryotes#^4857a5|Bah et al (2014) used NOE data]] to study how 4E binding proteins interact with eIF4E 
