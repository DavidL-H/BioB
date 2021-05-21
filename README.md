# Type II BioB
Chapter IV of the Ph.D. - A novel and widespread Type of Biotin Synthase does not sacrifice an iron-sulfur cluster for sulfur-insertion

# Description of data
UniProtKB/Swiss-Prot and TrEMBL UniProt release 2020_05 to fetch all sequences annotated with “family:biotin family:synthase”, including phylogenetic tags
This resulted in 23268 Biotin Synthase protein sequences in the data file "201020 ALL UniProt BioBs with phylogeny"

Using ScanProSite, these sequences were assigned one or more of the following custom motifs:

TI: C-x(3)-C-x(2)-C-x(30,40)-[HSRGEAKTVD]-[VILMFYWHKTA]-C-[VILMFYWHKTA]-[VAGSTDNRKH]-[VILMFYWHKTAS]-[ASGQKI] 

TII: C-x(3)-C-x(2)-C-x(30,40)-[HSRGEAKTVD]-[VILMFYWHKTA]-S-[VILMFYWHKTA]-[VAGSTDNRKH]-[VILMFYWHKTAS]-[ASGQKI] 

TA: C-x(3)-C-x(2)-C-x(30,40)-[HSRGEAKTVD]-[VILMFYWHKTA]-A-[VILMFYWHKTA]-[VAGSTDNRKH]-[VILMFYWHKTAS]-[ASGQKI] 

TG: C-x(3)-C-x(2)-C-x(30,40)-[HSRGEAKTVD]-[VILMFYWHKTA]-G-[VILMFYWHKTA]-[VAGSTDNRKH]-[VILMFYWHKTAS]-[ASGQKI] 

TD: C-x(3)-C-x(2)-C-x(30,40)-[HSRGEAKTVD]-[VILMFYWHKTA]-D-[VILMFYWHKTA]-[VAGSTDNRKH]-[VILMFYWHKTAS]-[ASGQKI] 

NA: no motifs matched

## BioB_Uniprot_Motif_Datav2.R
All data clean-up and manipulation was done in R

## BioB_motifs_clean.csv
A cleaned-up .csv file with Identifieds, seqeunces, phyologeny and motif identifiers
