# Reverse transcription and PCR

This protocol immediately follows vRNA extraction and covers cDNA generation and amplification with mumps-specific primers. 

### Reverse transcription/cDNA synthesis
Reverse transcription is performed with the Protoscript II first strand synthesis kit (NEB, catalogue # E6560L). 

1. Combine 2 µl of random primers with 8 ul of vRNA in a PCR tube for each sample. Incubate at 65°C for 5 minutes. After incubation, briefly spin down and put on ice. 

2. To each reaction, add 10 ul of Protoscript II reaction mix (2x) and 2 µl of Protoscript II enzyme mix (10x). This can be made up as a mastermix and aliquoted into each PCR tube to save time. 

3. Incubate this 20 µl cDNA synthesis reaction at 25°C for 5 minutes, then 42°C for 1 hour, and then a final inactivation step at 80°C for 5 minutes. The cDNA product should be stored at -20 C.

### PCR
We used primal scheme (http://primal.zibraproject.org/) to design overlapping, 1500 bp amplicons spanning the entirety of the mumps virus genome. Amplicons overlap by ~ 100 bp. Primer sequences are listed in the table below. 

**Amplicon** | **Forward/Reverse** | **sequence** | **pool**
--- | --- | --- | ---
mumps 1.5kb 1F| Forward | ACCAAGGGGAAAATGAAGATGGG | pool 1 
mumps 1.5kb 1R| Reverse | TAACGGCTGTGCTCTAAAGTCAT| pool 1
mumps 1.5kb 2 F| Forward |TTGTTGACAGGCTTGCAAGAGG| pool 2
mumps 1.5kb 2 R| Reverse | TTGTTCAAGATGTTGCAGGCGA| pool 2
mumps 1.5kb 3 F| Forward |TGCAACCCCATATGCTCACCTA| pool 1
mumps 1.5kb 3 R| Reverse | AGTTTGTTCCTGCCTTTGCACA| pool 1
mumps 1.5kb 4 F| Forward |AGTGAGAGCAGTTCAGATGGAAGT| pool 2
mumps 1.5kb 4 R| Reverse | CCCTCCATTAGACCGGCACTTA| pool 2
mumps 1.5kb 5 F| Forward |AACAACAGTGTTCCAGCCACAA| pool 1
mumps 1.5kb 5 R| Reverse | GGTGGCACTGTCCGATATTGTG| pool 1
mumps 1.5kb 6 F| Forward |TGCCGTTCAATCATGAGACATAAAGA| pool 2
mumps 1.5kb 6 R| Reverse | CGTAGAGGAGTTCATACGGCCA| pool 2
mumps 1.5kb 7 F| Forward |TGTCTGTGCCTGGAATCAGATCT| pool 1
mumps 1.5kb 7 R| Reverse | CGTCCTTCCAACATATCAGTGACC| pool 1
mumps 1.5kb 8 F| Forward |CCAAAAGACAGGTGAGTTAACAGATTT| pool 2
mumps 1.5kb 8 R| Reverse | ACGAGCAAAGGGGATGATGACT| pool 2
mumps 1.5kb 9 F| Forward |TTTGGCACACTCCGGTTCAAAT| pool 1
mumps 1.5kb 9 R| Reverse | TGACAATGGTCTCACCTCCAGT| pool 1
mumps 1.5kb 10 F| Forward |ACTCGCACAGTATCTATTAGATCGTGA| pool 2
mumps 1.5kb 10 R| Reverse | GCCCAGCCAGAGTAAACAAACA| pool 2
mumps 1.5kb 11 F| Forward |GCCAAGCAGATGGTAAACAGCA| pool 1
mumps 1.5kb 11 R| Reverse | GGCTCTCTCCAACATGCTGTTC| pool 1
mumps 1.5kb 12 F| Forward |GCGGGGCCTCTATGTCACTTAT| pool 2
mumps 1.5kb 12 R| Reverse | CCAAGGGGAGAAAGTAAAATCAAT| pool 2


We amplified cDNA using 2 primer pools: the first contained primer pairs 1, 3, 5, 7, 9, and 11, all pooled at 10 uM. The second pool contained primer pairs 2, 4, 6, 8, 10, and 12. All primers in pool 2 were pooled at 10 uM, except for primer pair 4, which was added at a 20 uM concentration. 

PCR was performed with the Q5 Hotstart DNA polymerase (NEB, catalogue # M0493L), with the following reaction volumes: 

**Reagent** | **1X volume**
--- | --- 
Nuclease-free water| 11.75 µl
Q5 Reaction buffer | 5 µl
10 mM dNTP| 0.5 µl
Q5 DNA Polymerase| 0.25 µl
primer pool 1 or 2| 2.5 µl
cDNA | 5 ul
**total reaction volume** | 25 µl

**cycling conditons:**

98 °C 30 seconds

30 cycles:
* 98 °C 15 seconds
* 67 °C 5 minutes

10 °C forever


### Amplicon cleanup
The entire PCR product was run on a 1% agarose gel, and bands were cut out and purified using the QiAquick gel extraction kit (Qiagen, catalogue # 28706), following the manufacturer's protocol. All optional steps were performed, and the final product was eluted in 30 µl of buffer EB and quantified using the Qubit dsDNA HS Assay kit (Thermo Fisher, catalogue # Q32854). 
