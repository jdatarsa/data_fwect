# Data for the manuscript: Reasons to be fearful? Rising proportions of positive faecal worm egg counts among UK horses (2007-2023) 
# Files
## data_eqdsr_surveillance.csv
FWECT Dataset containing the quarterly data submitted to the Equine Quarterly Disease Surveillance Report between 2007 and 2023 (n=1190 rows).  
*lab*: anonymised integer reference for the laboratory submitting data  
*rowid*: database reference for data row  
*period_year*: data submission year  
*period_quarter*: data submission quarter  
*count_tested*: integer value of total tests performed by reporting laboratory  
*count_positive*: integer value of total tests detected positive by reporting laboratory  
## data_eqdsr_questionnaire.csv
Questionnaire dataset related to laboratory parameters for FWECT submissions and testing.  
Missing data is depicted by blank entries  
All laboratory ID's (*lab*) used in the study have been included with responses received up to and including lab 37 in row 19 (incl. header row).  
*method*: method/s used for diagnosis  
*volume_faeces_requested*: volume of faeces requested by laboratory for testing  
*volume_faeces_tested*: volume of faeces tested by laboratory    
*multiplication_factor_epg_estimate*: multiplication factor used in eggs per gram estimate calculation  
*epg_level_strongyle_eqr_positive*: eggs per gram level and above considered as a positive finding - strongyles  
*threshold_level*:   author classification for *epg_level_strongyle_eqr_positive* classing into ≥0 to <100 epg (level 1, referent baseline), ≥100 to <300 epg (level 2), ≥300 epg (level 3)
*epg_level_ascarid_eqr_positive*: eggs per gram level and above considered as a positive finding - ascarids  
*epg_level_advising_strongyles_treatment*: eggs per gram level and above at which treatment is advised - strongyles  
*epg_level_advising_ascarid_treatment*: eggs per gram level and above at which treatment is advised - ascarids  
