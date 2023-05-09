# World Bank's Point of View
### By - _Alice Abillu, Olisa Nwora, Sreedhar Jalasutram_
---

### Objective
The project analyzes various social and economic categorical data, between the years 1960 and 2015, percentage of Agricultural land area, Food Production Index, Carbon Dioxide emissions (in Kilotons), Electricity Production (as a percentage of total) from sources such as Coal, Natural Gas, Nuclear, Hydroelectric, Oil, Renewable sources, Government expenditure on education and the percentage of population that use Internet in the leading economies around the world. For the pupose of the project, the analysis is based on the following countries: (sourced from [Wisevoter](https://wisevoter.com/country-rankings/largest-economies-in-the-world/) )
- United States
- Nigeria
- China
- Saudi Arabia
- Germany
- Brazil
- Australia
---

### Metadata
World bank provided data for the countries and regions across the world in several different categories. The categories are termed as series_id in the world bank metadata.
For the purpose of this project, the following series_ids were used in analysis

|Series_Id         | Meaning                                                            |
|------------------|--------------------------------------------------------------------|
|AG.LND.AGRI.ZS	   | Agricultural land (% of land area)                                 |
|AG.PRD.FOOD.XD	   | Food production index (2014-2016 = 100)                            |
|EN.ATM.CO2E.KT	   | CO2 emissions (kt)                                                 |
|EG.ELC.COAL.ZS	   | Electricity production from coal sources (% of total)              |
|EG.ELC.HYRO.ZS	   | Electricity production from hydroelectric sources (% of total)     |
|EG.ELC.NGAS.ZS	   | Electricity production from natural gas sources (% of total)       |
|EG.ELC.NUCL.ZS	   | Electricity production from nuclear sources (% of total)           |
|EG.ELC.PETR.ZS	   | Electricity production from oil sources (% of total)               |
|EG.ELC.RNWX.KH	   | Electricity production from renewable sources,                     |
|                  | excluding hydroelectric (kWh)                                      |
|EG.ELC.RNWX.ZS	   | Electricity production from renewable sources,                     |
|                  | excluding hydroelectric (% of total)                               |
|IT.NET.USER.ZS	   | Individuals using the Internet (% of population)                   |
|SE.XPD.TOTL.GD.ZS | Government expenditure on education, total (% of GDP)              |


### Research Questions
Using the categories data between 1960 and 2015, this project work attempts to find answers to the questions below

1. Is there a correlation between Agricultural land and Carbon Dioxide emissions?
2. What is the trend on electricity production from renewable sources across the leading economies?
3. Which country has the least and most of its population using the Internet
4. Is there a correlation between Government expenditure on education and internet usage?
5. Which countries have the lowest and highest ratio of Agricultural land to food production comparisons
---

### Data Sets Used
World Bank provides data from hundreds of countries and regions around the world, from multiple categories such as finance, economy, energy, education, health, poverty, agriculture, employment, population, land use, foreign aid, climate change, government expenditures, literacy, mortality, and patents.

- https://data.nasdaq.com/databases/WB/data

* [United States](data/WB_DATA_USA.csv)
* [Nigeria](data/WB_DATA_NGA.csv)
* [China](data/WB_DATA_CHN.csv)
* [Saudi Arabia](data/WB_DATA_SAU.csv)
* [Germany](data/WB_DATA_DEU.csv)
* [Brazil](data/WB_DATA_BRA.csv)
* [Australia](data/WB_DATA_AUS.csv)

* [Electricity production from coal sources (% of total)](data/data_EG_ELC_COAL_ZS.csv)
* [Electricity production from hydroelectric sources (% of total)](data/data_EG_ELC_HYRO_ZS.csv)
* [Electricity production from natural gas sources (% of total)](data/data_EG_ELC_NGAS_ZS.csv)
* [Electricity production from nuclear sources (% of total)](data/data_EG_ELC_NUCL_ZS.csv)
* [Electricity production from oil sources (% of total)](data/data_EG_ELC_PETR_ZS.csv)
* [Electricity production from renewable sources, excluding hydroelectric (% of total)](data/data_EG_ELC_RNWX_ZS.csv)
* [Electricity production from renewable sources, excluding hydroelectric (kWh)](data/data_EG_ELC_RNWX_KH.csv)

---

### Tasks break down
* Filter datasets to be used
* Pull useful data from datasets
* Further refine questions
* Explore data
---

## Observations
1. Is there a correlation between Agricultural land and Carbon Dioxide emissions?

    Based on United States data, when CO2 emissions increased the percentage of agricultural land   
    decreased. The same thing occured in Austrailia as well. From the years
    2000 to 2014, the percentage of agricultural land dropped from 60% to 46% while the CO2 emiisions 
    increased from 34e^4 Kilotons to as high as 39e^4 kilotons. Based off the two countries it can be  
    seen that emissions and agricultural land are directly related.
    
2. What is the trend on electricity production from renewable sources across the leading economies?
    
   While Germany is leading the race to become a 'green' country (produce 26% of electricity from
   renewable sources), countries like Saudi Arabia are still relying on fossil fuels to meet 
   electricity demand. The race to use renewable sources to generate electricity has certainly
   started gathering momentum from the late 1990s and the trend has been mostly ticking upwards.

3. Which country has the least and most of its population using the Internet?

    Saudi Arabia has the highest population of internet users with 100% of its population being connected 
    while Nigeria has the lowest from the list with only a mere 35% being connected with the internet.
    
4. Is there a correlation between Government expenditure on education and internet usage?

    There doesn't seem to be a direct correlation with government expenditures on education and internet 
    usage. Over the years, internet usage has increased drastically across all the countries whereas the 
    amount spent on education has stayed relatively the same and in some cases dropped between the years.
    
5. Which countries have the lowest and highest ratio of Agricultural land to food production comparisons?

   The country with highest ratio of Agricultural land and Food Production is United States.
   Agricultural Land is 44% and Food Production Index is at 104.45

6. Which country has most electricity produced from renewable sources (as a % of total electricity)
   Denmark produced 65% of its total electricity from renewable sources

## Future State
To improve upon this project, the following ideas may be considered
1. Identify how much of C02 emissions are from liquid fuel consumption vs. gaseous fuel
2. Is there a correlation between greenhouse gas emissions and livestock production index
3. If the mortality rate per country related to the number of people using Internet
4. How has access to electricity influenced school enrollments
