# Spatial transcriptomics reveals molecular dysfunction associated with cortical Lewy pathology


 The DOI for the associated Zenodo data repostitory is 10.5281/zenodo.10729767  .  Please download all data and follow below instructions for directory setup to execute code to reproduce figures.




MOUSE

Create a file for storing all mouse GeoMx data and where to set up your r project: Here named GeoMx_Mouse

GeoMx_Mouse/

R.proj

probe_data_mouse.rds

ACA_Profile_.csv

top_genesets_human

top_genesets_mu

kegg_brite_all_ENTREZID.gmt

Mos_Profile.csv





HUMAN

Create a file for storing all human GeoMx data and where to set up your r project: Here called GeoMx_Hu

GeoMx_Hu/

R.proj

probe_data_Hu.RDS

Profile_human_allreg.csv_profileMatrix.csv

top_genesets_human

top_genesets_mu

kegg_brite_all_ENTREZID.gmt






CosMx

Create a file for storing all CosMx data and where to set up your r project: Here called CosMx

CosMx/

seurat_object_3mon.rds

pSyn_positve_cells.csv

cohort_3mon.rds

astats_3mon.rds



To these directories, add the matching code from this github repsitory. The GeoMx files have an analysis and a matching helper function code while CosMx only has one file.

To run GeoMx code: load in all the helper functions to your environment first from teh helper fufnctions code, then use the analysis pipeline to produce figures. 


DOI for this code repository is 10.5281/zenodo.10732492




 
