# Library preparation

Library preparation was performed with the Nextera XT DNA Library Prep kit (Illumina, catalogue # FC-131-1096), following the manufacturer's recommended protocol. For sequencing runs 1-3, we halved the reagent volumes for each step. For sequencing run 4, we had quite a few samples with high Ct values and a few samples that were old (from 2006), so we used full reaction volumes. The protocol below is for the half reaction volumes. To perform the full reaction (as specified in the Illumina recommended protocol), double the volumes and concentrations for each step. You can also follow this [protocol](https://support.illumina.com/content/dam/illumina-support/documents/documentation/chemistry_documentation/samplepreps_nextera/nextera-xt/nextera-xt-library-prep-reference-guide-15031942-02.pdf) from the prep kit manual.

### Pooling amplicons from pool 1 and pool 2 
1. For each sample, pool 1 and pool 2 amplicons were combined in equimolar concentrations to a total of 0.5 ng in 2.5 µl in a PCR strip tube. This generally required diluting the cleaned PCR product, re-quantifying, and using the diluted product for pooling. All reactions were brought up to 2.5 µl with water. 

### Nextera XT DNA Library prep
2. To each tube of pooled amplicons, add 5 µl of TD buffer. 

3. Add 2.5 μl of ATM to the wells containing input DNA and TD Buffer. Pipette up and down 5 times to mix, then spin down. 

4. Immediately incubate reactions in a standard thermocycler for 5 minutes at 55°C, followed by a hold at 10°C. Make sure to use a heated lid. Once the samples reach 10°C, remove from the thermocycler, spin down, and proceed immediately to step 5. 

5. Add 2.5 µl of NT buffer to each tube, pipetting up and down 5 times to mix. Spin down and incubate at room temperature for 5 minutes. This step halts the tagmentation process. 

6. To each tube, add 7.5 µl of NPM. 

7. Being careful not to touch the caps, add 2.5 µl of the i5 indices to each tube. 

8. Add 2.5 µl of the i7 indices to each tube. Pipette up and down 5 times to mix. 

9. Place tubes in a thermocycler and run the following limited-cycle PCR program. 

Ensure that the thermocycler lid is heated during the incubation. (total volume = 25 µl)

  1. 72°C for 3 minutes
  2. 95°C for 30 seconds
  3. 12 cycles of:
      1. 95°C for 10 seconds
      2. 55°C for 30 seconds
      3. 72°C for 30 seconds
  4. 72°C for 5 minutes
  5. Hold at 10°C

* After the PCR step is complete, reaction products can be stored at 4°C for up to 2 days. 

### Library cleanup with ampure beads
10. Aliquot out 15 µl of Ampure XP beads (0.6x) to a clean 1.7 ml tube.

11. Transfer all 25 µl of tagmentation product to the tube containing Ampure XP beads and vortex for 10 seconds to mix. 

12. Incubate at room temperature for 5 min. 

13. Place the tube on a magnetic particle concentrator (MPC) for 3-5 min. 

14. Wash the beads twice with 400µl of 80% EtOH. The volume of ethanol here is not critically important, as long as the entire bead pellet is submerged. 

15. Remove and discard EtOH and air dry the pellet at RT for 5-10 min. 

16. Add 10 μl of Buffer RSB (Resuspension buffer) and pipette up & down 10x to resuspend the beads. Place the tube back on the MPC for 1 min to pellet the beads, and transfer the SN to a clean microcentrifuge tube (make sure no beads are transferred).

17. Go back to step 10 and repeat for a second AMPure XP clean-up. 

18. Add 90µl of EB buffer to the 10 µl of eluted DNA. 

19. Add 70µl of Ampure XP beads (0.7x)

20. Incubate at room temperature for 5 min

21. Place the tube on a magnetic particle concentrator (MPC) for 3-5 min.

22. Wash the beads twice with 400µl of 80% EtOH.

23. Remove and discard EtOH and air dry the pellet at RT for 5-10 min

24. Add 10 μl of EB buffer and pipette up & down 10x to resuspend the beads. Place the tube back on the MPC for 1 min to pellet the beads, and transfer the supernatant to a clean microcentrifuge tube (make sure no beads are transferred).


### Quantification and QC with the Tapestation
Quantify tagmentation products with the Qubit dsDNA HS Assay kit (Thermo Fisher, catalogue # Q32854). The vast majority of tagmentation products will be 2-6 ng/ul with this half reaction protocol. 

In order to determine the average fragment length, all samples should be run on the Tapestation. At the Fred Hutch, we used the TapeStation HighSense D5K assay, which accepts DNA from 0.01 - 1 ng/ul. We generated a 1:10 dilution of each sample and submitted it to the sequencing core for analysis. 
