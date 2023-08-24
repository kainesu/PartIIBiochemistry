# Prime editing

Author: wikipedia
Note type: Source
Source type: Article

Prime editing writes new information into a targeted DNA site, allowing for indels and base conversions without needing DSBs or donor DNA templates. 

Uses a fusion protein of dCas9 + reverse transcriptase + pegRNA (prime editing guide RNA) 

# Components

- Prime editing guide: identifies target sequence to be edited and encodes new genetic information to replace targeted sequence
    - single guide RNA (sgRNA) that contains a primer binding site (PBS) → specifies target
    - Reverse transcriptase template sequence → encodes new genetic information
    - PBS allows 3' end of nicked DNA strand to hybridize to pegRNA
- Fusion protein of Cas9 nickase fused to M-MLV RT

# Mechanism

1. sgRNA binds to complementary target sequence 
2. Fusion protein nicks the other DNA sequence (i.e. PAM strand) to expose a 3'OH group 
3. PBS binds to 3' end of PAM strand 
4. 3'OH group used to prime reverse transcription of RT template portion of pegRNA 
5. This creates two DNA flaps — 3' flap containing newly synthesized sequence, and 5' flap containing original unedited sequence 
6. 5' flap cleaved by endonucleases 
7. 3' flap ligated — reannealed double strand has mismatches which are repaired naturally by mismatch repair. If information in the edited strand is copied into the complementary strand, the edit is permanently installed. 
    1. To favour using edited strand as the template, an additional sgRNA can be introduced that is complementary to the edited sequence such that Cas9 nickase will nick the unedited strand. Nicking the unedited strand causes cell's natural repair mechanisms to copy information in edited strand to complementary strand. 
![[Untitled 12.png]]