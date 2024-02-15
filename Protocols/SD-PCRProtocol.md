# Tidal Marsh Sparrow Diet PCR Protocol
#### Will Rumfelt
#### 14 February, 2024

### Protocol to amplify a marker region of arthropod COI DNA for sequencing and metabarcoding analysis

Fecal sample DNA should be extracted prior to this protocol using Zymo Quick-DNA Fecal/Soil Microbe DNA Miniprep kits, following the "Tidal Marsh Sparrow Diet DNA Extraction Protocol." (Can be found in the `SD-ExtProtocol.md` file.)

This project involves 2 PCR steps before pooling samples and sequencing. The first PCR step is covered in this protocol and done in the “clean” room in the Kovach lab to target the CO1 region of the genome using ANML primers (Jusino et. al. 2019) with the Nextera overhang added to the 5’ end. The second PCR is performed by the Genome center at UNH and will add the Illumina indices and flow cell binding oligos to the amplicons needed for sequencing.

### ANML COI Primer Sequences:

Nextera overhang sequence in **bold**

Forward: 5' **TCGTCGGCAGCGTCAGATGTGTATAAGAGACAG**GGTCAACAAATCATAAAGATATTGG 3’

Reverse: 5' **GTCTCGTGGGCTCGGAGATGTGTATAAGAGACAG**GGWACTAATCAATTTCCAAATCC 3’


### PCR Recipe

We use a pre-made Master Mix for this PCR, which includes the Taq polymerase. Note: you will need enough Master Mix for all the samples + one negative control + ~10% extra for pipetting error (1 extra reaction for every 10 samples).

Multiply the volume of each PCR reagent by the number of reactions you are running to determine how much to add. Then pipette this amount of each reagent into a 1.5ml tube. Example below, but also use the spreadsheet for ease of calculating (`SparrowFecalSeqPCR-Mixing.xlsx`)

### Master Mix recipe for a 96-well plate with extra for pipetting error:

| Reagent | Volume per Rxn | # of Rxns | Total Volume |
| ------- | -------------- | --------- | ------------ |
| AccuStart II PCR SuperMix  | 13 µL | 110 | 1430 µL |
| LCOI4910 - Forward Primer (50 uM) | 1 µL | 110 | 110 µL |
| COI - CFMRa - Reverse Primer (50 uM) | 1 µL | 110 | 110 µL |

#### 25 µL reactions: 10 µL DNA + 15 µL Master Mix

## Cycling conditions:

Allow the block to heat up prior to inserting samples to thermocycler.

**Hot start 94C for 60 s**

**5 cycles of:**

94C 60 s

45C 90 s

72C 90 s

**30 cycles of:**

94C for 60 s

50C for 90 s

72C or 60 s

## Step-by-Step Protocol

1.	Turn on PCR machine to warm up before you enter the clean room.
2.	The samples, primers, and master mix all need to thaw before you set up the reactions.
3.	Once thawed, briefly vortex and centrifuge samples, primers, and master mix.
4.	Assemble the master mix according to the recipe for the number of samples you are doing. Vortex and briefly centrifuge master mix, and set aside.
5.	Pipette 10 uL DNA into each PCR tube or 96-well PCR plate well, carefully & changing tips between each sample.
6.	Using a single/multichannel pipette, aliquot 15 uL of the master mix to each well of the tube or plate, changing tips between each sample.
7.	Secure a lid (for strip tubes) or seal (for 96-well plates) on the samples. If you are using strip tubes, be sure to mark 1) the order in which the strip tubes go, if using multiple tubes, and 2) the top of the tubes, to ensure that you do not lose track of where each sample is. 
8.	Bring the samples to the PCR room and place in the thermal cycler, and start the program. 
9.	Put all samples and reagents into the appropriate containers and clean the hood.
10.	Once samples are done DO NOT bring them back into the clean room. Put them in either the small, post-PCR fridge in the main lab, or a freezer.
