# insect-coi-qiime2
Taxonomic placement of insect COI ASV's using qiime2 classifier

#websites for reference#
https://docs.qiime2.org/2022.2/tutorials/feature-classifier/
https://forum.qiime2.org/t/building-a-coi-database-from-bold-references/16129

Required files: 
1) ASV table produced through R metabarcoding diet analsyis script, these are sequences that need to be assigned to taxa (Here: InsectCOI_asv_table1.csv)
2) reference database and marker gene speciic trained classifier (Here: bold_anml_classifier.qza) 

NOTE: if a new classifier needs to be trained, see note: "training a qiime classifier"


