# insect-coi-qiime2
Taxonomic placement of insect COI ASV's using qiime2 classifier

#websites for reference#
https://docs.qiime2.org/2022.2/tutorials/feature-classifier/
https://forum.qiime2.org/t/building-a-coi-database-from-bold-references/16129

Required files: 
1) ASV table produced through R metabarcoding diet analsyis script (InsectCOI_asv_table1.csv), these are sequences that need to be assigned to taxa
2) reference database and marker gene speciic trained classifier (bold_anml_classifier.qza) (if new classifier needs to be trained, see note: "training a qiime classifier")


