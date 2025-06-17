# FLOWSA Data
Added .csv versions of FBA and FBS. Original data in parquet format are available on [EPA Data Commons](https://dmap-data-commons-ord.s3.amazonaws.com/index.html?prefix=flowsa/#flowsa/).

### Flow-By-Activity (FBA)
1. EPA Wasted Food Report
   - [EPA_WFR_2018_v1.3.0_4efcd5a](https://github.com/USEPA/flowsa/blob/master/flowsa/methods/flowbyactivitymethods/EPA_WFR.yaml)
   - Data Commons [parquet](https://dmap-data-commons-ord.s3.amazonaws.com/flowsa/FlowByActivity/EPA_WFR_2018_v1.3.0_4efcd5a.parquet)
2. EIA Manufacturing Energy Consumption Survey
   - [EIA_MECS_Energy_2018_v2.0.0_c31283d](https://github.com/USEPA/flowsa/blob/master/flowsa/methods/flowbyactivitymethods/EIA_MECS_Energy.yaml)
   - Data Commons [parquet](https://dmap-data-commons-ord.s3.amazonaws.com/flowsa/FlowByActivity/EIA_MECS_Energy_2018_v2.0.0_c31283d.parquet)

### Flow-By-Sector (FBS)
1. Food Waste method 1 - EPA's Wasted Food Report
    - [Food_Waste_national_2018_m1_v2.0.0](https://github.com/USEPA/flowsa/blob/master/flowsa/methods/flowbysectormethods/Food_Waste_national_2018_m1.yaml)
    - Data Commons [parquet](https://dmap-data-commons-ord.s3.amazonaws.com/flowsa/FlowBySector/Food_Waste_national_2018_m1_v2.0.0_49331eb.parquet)
2. Food Waste method 2 - National Commercial Non-Haz Waste (CNHW), with residential FW from EPA Wasted Food Report
    - [Food_Waste_national_2019_m2_v2.0.0](https://github.com/USEPA/flowsa/blob/master/flowsa/methods/flowbysectormethods/Food_Waste_national_2018_m1.yaml)
    - Data Commons [parquet](https://dmap-data-commons-ord.s3.amazonaws.com/flowsa/FlowBySector/Food_Waste_national_2018_m2_v2.0.0_49331eb.parquet)
3. Water method 1 - USGS NWIS
   - [Water_national_2015_m1_v2.0.1](https://github.com/USEPA/flowsa/blob/master/flowsa/methods/flowbysectormethods/Water_national_2015_m1.yaml)
       - [Water_Common](https://github.com/USEPA/flowsa/blob/master/flowsa/methods/flowbysectormethods/Water_common.yaml)
   - Data Commons [parquet](https://dmap-data-commons-ord.s3.amazonaws.com/flowsa/FlowBySector/Water_national_2015_m1_v2.0.1_165eb33.parquet)

# StEWI Data
CSV examples for a facility (eGRID), flowbyfacility (TRI), and flowbyprocess (GHGRP) examples.
