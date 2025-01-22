# Plankton-LakeVombsjon-Scania
Data from eutrophic lake sampling in southern Sweden 2018-2020


#Description of the data and file structure

Data in file ‘EW_Data_All’ is presented in the order it appears in the manuscript, see below for more information. Data in ‘EW_Data_Stats’ can be used in combination with the provided R scripts. There are separate scripts for the ordination (principal component analysis) and multiple linear regression analyses.

Sheets in excel file ‘Supplementary1:
Table1: Combined surface water temperature from our own sampling and from Sydvatten
Table2: Temperature (surface and bottom), DO (bottom) and RWCS from Sydvatten
Table3: Monthly average outflow and cumulative precipitation from SMHI.
Table4: Nutrient data
Table5: Chlorophyll-a (fluorometry) and phytoplankton community composition (AlgaeLabAnalyser)
Table6: Cyanobacteria and dinoflagellate biomass
Table7: Zooplankton biomass
Table8: Results from principal component analysis with environmental variables
Table9: Results from principal component analysis with zooplankton variables
Table10: AUC (Area under the curve) calculations
Table11: Results from Multiple Linear Regression analysis with model averaging

Relevant abbreviations:
(C): degrees celsius
mg ww/L: milligrams wet weight per litre (see manuscript for description)
mg dw/L: milligrams dry weight per litre (see manuscript for description)
AUC: area under the curve
RWCS: Relative water column stability
DO: dissolved oxygen
NA: Not available. Both NA and empty cells indicate that corresponding data was not collected and/or analysed for that specific sampling occasion. 

#Sharing/Access information 

Temperature and dissolved oxygen profiles for the deepest part of the lake was provided by the drinking water plant Vombverket, Sydvatten AB.

Precipitation data was downloaded from SMHI for station number 53410 (license CC BY): 
https://www.smhi.se/data/meteorologi/ladda-ner-meteorologiska-observationer/#param=precipitation24HourSum,stations=core,stationid=53410

Outflow data was downloaded from SMHI for station number 2018 (license CC BY): 
https://vattenweb.smhi.se/station/

Total global radiation data was downloaded from the European Joint Research Centre (JRC) (license CC BY):
https://data.jrc.ec.europa.eu/dataset/jrc-marsop4-7-weather_obs_grid_2015

# Code/Software

Code is written in R markdown with description/comments in text. The code is linked to the attached excel file ‘EW_Data_Stats’. Packages needed to run the code are included in the code. Code was written in R studio version 1.3.1093. For version of packages see manuscript.


