# SDOH Tables in PMAP

## Purpose
There are SDOH tables in PMAP under the PMAP_Dictionaries_Projection. 
I created an Rmd file [SDOH_Table_Link.Rmd] (https://github.com/SKATElin215/precision-rehab/blob/main/SDOH_Table_Link.Rmd) that can be run in RStudio to pull data from the projection and then link your own cohort data to SDOH variables of interest.

Let's get started!

## Set up config file
You will need a .csv file that holds information about the variables you want to pull in. I have created a generic file that can be modified as follows:
1. Download [SDOH_Link_Config_Generic.csv] (https://github.com/SKATElin215/precision-rehab/blob/main/SDOH_Link_Config_Generic.csv) and open it with your favorite .csv editor.
2. Replace the *** next to server with your projection's server name
3. Go into SQL server under PMAP_Dictionaries_Projection and review the dbo.sdoh_dict_bgl_2010_census and dbo.sdoh_dict_bgl_2020_census tables. These are dictionary tables that give you information about what variables are available in the tables. 
