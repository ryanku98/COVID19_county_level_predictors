# COVID19_county_factors
 On a crusade to find county-level factors as potential indicators to predict COVID19 infection and death rates.

### Limitations ###
#### Old Census Data ####
Data specifically from the USCensus is quite out of date, with the latest data reported in 2010:
- Land data: 2010 survey
- Water data: 2000 survey
- Housing data: 2005-2009
- Age data: 2009 estimates based on 2000 census
- Race data: 2010 census

#### COVID19 Case Reporting ####
Reporting guidelines for COVID19 are few and far between. Reporting by certain states can be unreliable at best and inaccurate at worst. Because of these inconsistencies, the data will be stratified by state to keep the reporting guidelines as consistent as possible.

#### NYTimes Data Formatting/Collection ####
NYTimes seems to consolidate certain data for unknown reasons. The main example of this is combining the 5 NYC counties (Bronx, Kings, NY, Queens, Richmond) into one collection of data. Normally I would just remove this irregularity, but as we all know, NYC was the worst off by far in the world, and any insight that this data could possibly provide could be crucial. As such, I simply had to combine the data for the 5 counties into one (generally speaking, summing the absolute data columns and averaging the percentage data columns).

