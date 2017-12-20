# Reverse transcription and PCR

This protocol immediately follows vRNA extraction and covers cDNA generation and amplification with mumps-specific primers. 

### Reverse transcription
Reverse transcription is performed with the Protoscript II first strand synthesis kit. 

1. Combine 2 ul of random primers with 8 ul of vRNA in a PCR tube for each sample. Incubate at 65°C for 5 minutes. After incubation, briefly spin down and put on ice. 

2. To each reaction, add 10 ul of Protoscript II reaction mix (2x) and 2 ul of Protoscript II enzyme mix (10x). This can be made up as a mastermix and aliquoted into each PCR tube to save time. 

3. Incubate this 20 ul cDNA synthesis reaction at 25°C for 5 minutes, then 42°C for 1 hour, and then a final inactivation step at 80°C for 5 minutes. The cDNA product should be stored at -20 C.

### PCR
We used primal scheme (http://primal.zibraproject.org/) to design overlapping, 1500 bp amplicons spanning the entirety of the mumps virus genome. Amplicons overlap by ~ 100 bp. Primer sequences are listed in the table below. 

**Amplicon** | **Forward/Reverse** | **sequence** | **pool**
--- | --- | ---
mumps_1.5kb_1_F| Forward | ACCAAGGGGAAAATGAAGATGGG | pool 1 
mumps_1.5kb_1_R| Reverse | TAACGGCTGTGCTCTAAAGTCAT| pool 1
mumps_1.5kb_2_F| Forward |TTGTTGACAGGCTTGCAAGAGG| pool 2
mumps_1.5kb_2_R| Reverse | TTGTTCAAGATGTTGCAGGCGA| pool 2
mumps_1.5kb_3_F| Forward |TGCAACCCCATATGCTCACCTA| pool 1
mumps_1.5kb_3_R| Reverse | AGTTTGTTCCTGCCTTTGCACA| pool 1
mumps_1.5kb_4_F| Forward |AGTGAGAGCAGTTCAGATGGAAGT| pool 2
mumps_1.5kb_4_R| Reverse | CCCTCCATTAGACCGGCACTTA| pool 2
mumps_1.5kb_5_F| Forward |AACAACAGTGTTCCAGCCACAA| pool 1
mumps_1.5kb_5_R| Reverse | GGTGGCACTGTCCGATATTGTG| pool 1
mumps_1.5kb_6_F| Forward |TGCCGTTCAATCATGAGACATAAAGA| pool 2
mumps_1.5kb_6_R| Reverse | CGTAGAGGAGTTCATACGGCCA| pool 2
mumps_1.5kb_7_F| Forward |TGTCTGTGCCTGGAATCAGATCT| pool 1
mumps_1.5kb_7_R| Reverse | CGTCCTTCCAACATATCAGTGACC| pool 1
mumps_1.5kb_8_F| Forward |CCAAAAGACAGGTGAGTTAACAGATTT| pool 2
mumps_1.5kb_8_R| Reverse | ACGAGCAAAGGGGATGATGACT| pool 2
mumps_1.5kb_9_F| Forward |TTTGGCACACTCCGGTTCAAAT| pool 1
mumps_1.5kb_9_R| Reverse | TGACAATGGTCTCACCTCCAGT| pool 1
mumps_1.5kb_10_F| Forward |ACTCGCACAGTATCTATTAGATCGTGA| pool 2
mumps_1.5kb_10_R| Reverse | GCCCAGCCAGAGTAAACAAACA| pool 2
mumps_1.5kb_11_F| Forward |GCCAAGCAGATGGTAAACAGCA| pool 1
mumps_1.5kb_11_R| Reverse | GGCTCTCTCCAACATGCTGTTC| pool 1
mumps_1.5kb_12_F| Forward |GCGGGGCCTCTATGTCACTTAT| pool 2
mumps_1.5kb_12_R| Reverse | CCAAGGGGAGAAAGTAAAATCAAT| pool 2


We amplified cDNA using 2 primer pools: the first contained primer pairs 1, 3, 5, 7, 9, and 11, all pooled at 10 uM. The second pool contained primer pairs 2, 4, 6, 8, 10, and 12. All primers in pool 2 were pooled at 10 uM, except for primer pair 4, which was added at a 20 uM concentration. 

PCR was performed with the Q5 Hotstart DNA polymerase, with the following reaction volumes: 

**Reagent** | **1X volume**
--- | --- 
Nuclease-free water| 11.75 ul
Q5 Reaction buffer | 5 ul
10 mM dNTP| 0.5 ul
Q5 DNA Polymerase| 0.25 ul
primer pool 1 or 2| 2.5 ul
cDNA | 5 ul
**total reaction volume** | 25 ul

cycling conditons:
98 °C 30 seconds

30 cycles:
98 °C 15 seconds
67 °C 5 minutes

10 °C forever


### Amplicon cleanup
The entire PCR product was run on a 1% agarose gel, and bands were cut out and purified using the QiAquick gel extraction kit, following the manufacturer's protocol. All optional steps were performed, and the final product was eluted in 30 ul of buffer EB and quantified using the Qubit dsDNA HS Assay kit. 
