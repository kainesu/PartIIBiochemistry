**Explain why energy is needed in translation. **

# **Introduction**

Translation is a complex process involving the assembly of translation machinery on an mRNA, as well as the polymerisation of individual amino acids into a polypeptide. Given that the entropy change in such a process is likely to be highly unfavourable, it is no surprise that translation is endergonic overall. However, the energy requirement of translation is not simply to drive a thermodynamically unfavourable reaction, but also to **regulate ribosomal assembly**, as well as ensure **unidirectionality** of translation and the **unambiguity** of the genetic code. 

# **1. Energy input is required to drive ribosome assembly in eukaryotes **

Initiation is arguably the most regulated step of translation, since the amount of wasted resources would be minimised should translation be terminated at this step. Unlike prokaryotes, where _in vivo_ ribosome assembly on the mRNA is spontaneous, ribosome assembly in eukaryotes involves many energy-releasing enzymes. These enzymes drive the coalescing of many assembly factors, providing a means of regulating translation initiation. For example, KsgA/Dim1 is a methyltransferase that binds to the 18S rRNA in the small ribosomal subunit. Its binding site overlaps with that of IF3, so dissociation of KsgA/Dim1 is required for initiation to proceed. For dissociation to occur, KsgA/Dim1 has to methylate the 18S rRNA, an exergonic process due to the release of a high energy bond in the S-adenosylmethionine cofactor. In this case, energy invested in the production of SAM is ultimately used to create a checkpoint to prevent premature translation initiation. **This methylation can only occur once unless the methylation state is actively reset by a demethylase.**

Once the translation initiation complex has assembled correctly on the mRNA, further energy input is required to “lock in” the correct assembly. In particular, the assembly of the large and small ribosomal subunit on the mRNA ribosome binding site is made irreversible by GTP hydrolysis of initiation factor (IF) 2. The energy released from GTP hydrolysis is coupled to conformational changes in the ribosome conformation that commit it to elongation. Myasnikov et al (2005) used cryo-EM to determine the structure of the 70S ribosome in different nucleotide states of IF2. They found that GTP hydrolysis causes conformational changes in IF2 and the ribosome, such as an outward shifting of IF2 from its entry site, and a rotation of the small ribosomal subunit with respect to the large subunit. This intersubunit rotation has a high activation energy barrier, such that the ribosomal complex cannot spontaneously convert back to the previous conformation, making the initiation step irreversible. Since this GTP hydrolysis event only occurs after all components of the translation initiation complex are assembled, it acts as a quality check for the assembly. Also, by committing the ribosomal complex to elongation, GTP hydrolysis prevents non-productive association of ribosomal subunits with the mRNA, ensuring that ribosomal assembly leads to polypeptide synthesis. 

# **2. Energy input ensures that translocation is unidirectional **

The unidirectionality of translation is important to the accuracy of the genetic code, as it ensures that the primary structure of the protein is colinear with its mRNA. Unidirectionality is secured by the input of energy from GTP hydrolysis, causing conformational changes that are irreversible due to the creation of an activation energy barrier. 

For example, during elongation, the ribosome undergoes a series of conformational changes during translocation that is driven by GTP hydrolysis of elongation factor (EF)-G. Following peptide bond formation, GTP-bound EF-G binds to the ribosome A site, which stimulates its GTPase activity. GTP hydrolysis induces a conformational change in the ribosome such that it translocates 1 codon along the mRNA in the 5’ to 3’ direction, and the ribosomal subunits rotate again. Currently, the mechanism for how EF-G induces translocation is unclear. It may use the free energy from GTP hydrolysis to directly drive translocation via a power stroke. Alternatively, it might use a Brownian ratchet mechanism. Either way, once the ribosome has translocated down a codon, the energy barrier of reversing the conformational changes within the ribosomal complex becomes so high that translocation is effectively irreversible. 

Shoji et al (2006) showed that the pretranslocation state of the ribosome is actually thermodynamically favoured over the posttranslocation state. In the absence of EF-G, ribosomal complexes can actually spontaneously convert from the post to pretranslocation state. This finding further demonstrates that energy input from EF-G creates an energy barrier that prevents the spontaneous reversal of the ribosome on the mRNA, ensuring the unidirectionality of translocation. 

An exception that proves this rule was found by Qin et al (2006), who found that the protein LepA can cause _reverse _translocation of the ribosome. However, LepA is a GTPase, and couples the energy from GTP hydrolysis to the induction of conformational changes in the translation elongation complex. As such, even though translocation is generally unidirectional, perhaps the more important point is that enzymes can change the energy landscape of the ribosomal complex throughout the translation process to regulate ribosomal activity. 

# **3. Energy input ensures the unambiguity of the genetic code **

The genetic code is unambiguous, meaning that each codon specifies only a single amino acid. Every mRNA isoform produces only a single polypeptide isoform each time it is translated. During codon recognition, the ribosome must check the codon-anticodon interaction such that only the cognate anticodon can bind to the codon in the A-site. This is called decoding. The challenge for the ribosome is not to distinguish cognate anticodons from non-cognate anticodons, whose binding to the codon has a large enough ΔΔG to be discriminated based on binding energy alone. The challenge is the rejection of near-cognate anticodons, where ΔG of binding is similar to the cognate anticodons. However, the ribosome is still able to achieve a very low error rate of 1 in 10000 codon-anticodon pairs. To accomplish this high level of accuracy, the ribosome makes use of the kinetic proofreading mechanism. Energy input in the form of GTP hydrolysis is used to accelerate the rate of rejection of incorrect codons, and also make the rejection pathway irreversible. This ensures that most correct anticodons are accommodated while virtually all incorrect anticodons are rejected. 

Non-cognate codons are generally rejected efficiently at the first step of decoding, _initial selection_, as the binding energy between the codon and anticodon is low and the ternary complex of tRNA-EF-Tu-GTP dissociates without additional GTP input. In contrast, near-cognate anticodons are still able to bind to the anticodon and trigger GTP hydrolysis by EF-Tu in the same way as cognate anticodons. However, the rate of GTP hydrolysis for near-cognate anticodons is much slower than for the cognate anticodons. Mechanistically, this is due to differences in their interactions with the decoding center nucleotides G530 and A1492-A1493 of the rRNA. The cognate anticodon interacts with these nucleotides in such a way that creates excess binding energy. This energy is coupled to a series of conformational changes in the tRNA and the ribosome, including 30S domain closure, which positions EF-Tu in the ribosome for GTPase activation. The interaction of the near-cognate anticodon with the codon does not result in excess binding energy, and so does not trigger these conformational changes, such that GTP hydrolysis by EF-Tu is not catalysed. At the same time, the rate of dissociation of the near-cognate anticodon from the codon is faster than for the cognate anticodon. The end result is that cognate codons proceed to the second proofreading step more frequently than near-cognate ones. Hence, energy input in the form of binding energy allows catalysis to occur for the cognate anticodon but not the near-cognate one. This results in differences in reaction rates that discriminate between cognate and near-cognate anticodon. 

That being said, some near-cognate anticodons still proceed to the proofreading step at a low level of frequency. At this step, EF-Tu-GDP dissociates from the ribosomal complex, and the tRNA may be accommodated, where the A-site acceptor stem moves towards the peptide transfer centre for peptide bond formation. The tRNA may also be rejected, where it dissociates from the complex. Once rejected, the tRNA cannot reassociate with the ribosomal complex as it is not bound to EF-Tu-GTP, making rejection irreversible. Near-cognate anticodons undergo rejection at a higher rate than cognate anticodons, as they have weaker interactions with the decoding centre and do not trigger 30S domain closure. Conversely, cognate anticodons undergo accommodation at a much higher rate than near-cognate ones. Since the proportion of anticodons that are accommodated is related to the ratio of the rate of accommodation:rejection, near-cognate anticodons are overwhelmingly rejected, and cognate ones are mostly accepted. 

![[Pasted image 20230526005923.png]]
Figure 1: Summary of decoding process. 

Hence, we can see that kinetic proofreading is achieved by the input of energy. The irreversibility of accommodation/rejection is due to the energy input from GTP hydrolysis, while differences in rate are due to differences in the conformational changes in the ribosomal complex following GTP hydrolysis. However, it is worth noting that these differences in conformational changes were ultimately because of differences in the binding energy in the codon-anticodon interaction. In other words, the kinetic proofreading mechanism serves to enhance the discriminatory effect of this small difference in binding energy by using additional energy.  

# **Conclusion**

Translation is one of the most energy intensive processes in the cell, but for good reasons. The consequences of producing incorrect proteins can be devastating to a cell, so the energy investment is worthwhile to ensure that translation occurs accurately. This energy is mostly coupled to numerous irreversible conformational changes within the ribosomal complex. Interestingly, some of these conformational changes may technically be reversible, as the reverse processes may in fact be thermodynamically favourable. However, the investment of energy results in an activation energy barrier that is sufficiently high to prevent these reverse processes. Further inputs of energy would be required to lower this activation energy barrier, which the cell does only when appropriate. Overall, the process of translation exemplifies the way cells manipulate the energetics of chemical reactions, allowing them to exist in a state of disequilibrium. 



* How much of the cell’s energy is used for translation? 
* Overall, translation is an endergonic process, assembling translation machinery and combining individual amino acids to form polypeptides, reducing entropy 
    * Initiation requires energy 
        * Scanning 
    * Anabolic process
* Which parts of the process of translation require energy? 
    * Removal of secondary structures 
    * Force generation by EF-G drives translocation  
    * EF-Tu drives binding of aa-tRNA to ribosomal complex 
    * IF recycling 
* Fundamentally, why can translation only occur when there is sufficient cellular energy? 
    * Unidirectionality 
        * “Commitment” to translation 
    * Accuracy of translation 
        * Fidelity 
        * Distinguishing cognate and near cognate amino acids 
    * Regulation
        * LLPS?? Lmao 
        * Is translation a sensor for energy levels in cells? How sensitive is it? 
            * Requires energy – don’t want excessive translation that is more than what 
    * Needed for conformational changes that allow for translation to occur/ribosome dynamics  
        * Rearrangements in structure of ribosome 
            * E.g. accommodation 
    * Does dissociation require energy? 
        * Yes, termination – e.g. eRF3 GTP hydrolysis and triggers release 
    * Translation in different contexts…? 
        * E.g. stress? 
    * GTP. How is it generated in cells? 
    * Translation as an energy landscape? How does the energy requirement change over the course of translation? 
* Linking translation and energy metabolism in cells
    * Role for mTOR

Structural perspective? 
