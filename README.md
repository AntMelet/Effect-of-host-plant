# Effect-of-host-plant-on-X.-saxesenii

Description:
In this study, we investigated the effect of the host tree on the life history, behaviour and fungal community of an ambrosia beetle, Xyleborinus saxesenii.
We bred beetles in different experimental groups. We measured various traits of the life history of the beetles and their behaviour. We also sampled the nest material to identify the fungi that develop in X. saxesenii nests.

In this repository, you will find the data we collected. The files are organised in three folders:

1) Life history and behaviour:
This folder contains the raw data related to the preference assays, life history traits and behaviours of the beetles. The data are organised in different files

Preference: beetles were offered the choice to nest in beech or spruce artificial medium. Out of 65 beetles, 27 died and did not nest in any medium

SuccessRate: this file provides a record of the success or failure of all nests that were initiated during the study
-	colony: each nest had a unique label. Labels are the group of the nest associated with a number
-	group: nests belonged to three groups identified “B”, “BB” and “BS”
-	condition: the state of the nest ten days after initiation
-	condition_num: a value reflecting the state of the nest after ten days in numerical format (0 = nest had failed, 1 = nest was successful)
-	medium: the tree used to prepare the artificial medium in which the nest was dug

Development: this file provides a record of the eggs, larvae, pupae, adult beetles and dispersers observed in the nests at the days of observation
-	colony: each nest had a unique label. Labels are the group of the nest associated with a number
-	group: nests belonged to three groups identified “B”, “BB” and “BS”
-	medium: the tree used to prepare the artificial medium in which the nest was dug
-	date: the date of observations. The first observation was conducted on the day of initiation of the nest. 
-	age: age of the nest at the time of observation (the difference between the date of observation and the date of initiation of the nest)
-	eggs: number of eggs observed in the nest
-	larvae: number of larvae observed in the nest
-	pupae: number of pupae observed in the nest
-	adults: number of adult females observed in the nest
-	dispersers: number of dispersers observed leaving the nest
  
Natural history: this file provides a record of the first times eggs, larvae, pupae, adults and dispersers were observed in the nests. The time of end of the nests, and the total number of dispersing females for each, are also recorded
-	ID: each nest had a unique label. Labels are the group of the nest associated with a number
-	date_colony: The date of initiation of the nest
-	group: nests belonged to three groups identified “B”, “BB” and “BS”
-	medium: the tree used to prepare the artificial medium in which the nest was dug
-	first_egg: the date we observed eggs in the nest for the first time
-	start_egg: the age of the nest when we observed the first eggs
-	first_larva: the date we observed larvae in the nest for the first time
-	start_larva: the age of the nest when we observed the first larva
-	first_pupa: the date we observed pupae in the nest for the first time
-	start_pupa: the age of the nest when we observed the first pupa
-	first_adult: the date we observed adult females in the nest for the first time
-	start_adult: the age of the nest when we observed the first adult female
-	first_disperser: the date we observed dispersers leaving the nest for the first time
-	start_disperser: the age of the nest when we observed the first disperser
-	nest_end: the date we observed dispersers leaving the nest for the last time
-	start_end: the age of the nest when we observed the last disperser
-	total_dispersers: the total number of dispersers that left the nest

Behaviour: this file provides a record of the behaviours observed in the nests
-	colony: each nest had a unique label. Labels are the group of the nest associated with a number
-	group: nests belonged to three groups identified “B”, “BB” and “BS”
-	medium: the tree used to prepare the artificial medium in which the nest was dug
-	larva_rest: number of times larvae were observed resting
-	larva_walk: number of times larvae were observed walking
-	larva_dig: number of times larvae were observed digging
-	larva_feed: number of times larvae were observed feeding
-	larva_clean: number of times larvae were observed cleaning
-	larva_groom: number of times larvae were observed grooming
-	larva_ball: number of times larvae were observed balling
-	larva_cannibalise: number of times larvae were observed cannibalising
-	adult_rest: number of times adult females were observed resting
-	adult_walk: number of times adult females were observed walking
-	adult_dig: number of times adult females were observed digging
-	adult_feed: number of times adult females were observed feeding
-	adult_clean: number of times adult females were observed cleaning
-	adult_shuffle: number of times adult females were observed shuffling
-	adult_groom: number of times adult females were observed grooming
-	adult_copulate: number of times adult females were observed copulating
-	adult_cannibalise: number of times adult females were observed cannibalising
-	adult_block: number of times adult females were observed blocking
-	larva_social: number of times larvae were observed displaying any social behaviour
-	larva_total: total number of larval behaviours recorded
-	adult_social: number of times adult females were observed displaying any social behaviour
-	adult_total: total number of adult behaviours recorded

2) Fungal community analysis:
This folder contains the sequences obtained form metabarcoding the fungal community associated with X. sasenii, the reference sequences used for taxonomic identification, the script used to process the raw sequences and the results of the script.

Host plant_bioinformatic script.docx: this file details the script used to process the raw sequences. The script uses Usearch v11. The script produces a number of files during the process, these files are not included in this folder. Only the final results are included in the form of 2 files: HostPlantLSUtax and HostPlantLSUzotus_table

HostPlantLSUtax: this file associates each zotu to a taxonomic output. Not every zotu is identified to the species level

HostPlantLSUzotu_table: this file associates the zotu and samples. Each cell indicates how many sequences of every zotu were found in every sample

HostPlantLSUmetadata:  this file was manually constructed, to associate each sample to the metadata relevant for this study

LSUprimers.docx: this file details the forward and reverse primers used for this study

ref_LSU_sequences.fasta: this files provides the first database used for the taxonomic assignation of the sequences

sequences_NCBI_tax.fa: this file provides the second database used for the taxonomic assignation of the sequences

3) Growth of fungi in different media:
This folder contains the data from a pilot experiment. We tested the growth of some fungi commonly associated with X. saxesenii, in artificial media that contains a lot of nutrients or not, and were autoclaved or not.

Growth of fungi in different media: Growth of the fungi, 5 days after inoculation.
ID: a unique code to identify each assay
Group: each group had a code. This code has the informations about the fungus, the presence of nutrients and the autoclaving of the medium before inoculation
Fungus: the fungus being tested
Autoclaved: was the medium autoclaved before the inoculation of fungus
Nutrients: does the medium contain additional nutrients, or only sawdust, agar and water
Treatment: each treatment had a code. This code has the informations about the presence of nutrients and the autoclaving of the medium before inoculation
Medium: the plant used to produce the sawdust in the medium
Replicate: a number identifing the replicate for the different groups
Area: surface covered by the inoculated fungus after 5 days of growth. Surface expressed in square millimeters

Sequences: this folder contains all raw sequences, including the sequences from the samples, positive and negative controls

