# Finding Model Countries for Renewable Energy Use

## Introduction

The World Bank's Sustainable Energy For All (SE4All) Database provides country level historical data for access to electricity and non-solid fuel, share of renewable energy in total final energy consumption by technology, and energy intensity rate of improvement.

The SE4All database can be found at
http://databank.worldbank.org/data/reports.aspx?source=sustainable-energy-for-all&Type=TABLE&preview=on#

## Summary

To determine countries whose renewable energy use could be modeled, each country’s renewable energy share of total energy consumption in 2015 and total energy consumption in 2015 were mapped, revealing an inverse relationship between renewable energy share and total energy consumption. Each country’s per capita energy use in 2015 was then mapped with corresponding bar graphs coloring each country by geographic region and income level, revealing high income, European countries as having the highest per capita energy use in the world. Because high income, European countries might not be relevant models to most of the world, a final map displaying each country’s change in per capita energy use between 1990 and 2015 was created, with interactive geographic region and income level features. This final map allows for any country to search for countries with similar levels of income and/or of similar geographic region in order to determine countries of similar circumstances that increased per capita renewable energy use. 

The data visualizations can be found at:
https://public.tableau.com/profile/michael.gysel#!/vizhome/SustainableEnergyforAll/ModelCountriesforRenewableEnergyUse?publish=yes

## Design

Global energy use, population, and income data was utilized to determine countries with high per capita renewable energy use and the highest increases in per capita renewable energy use (I will refer to these two metrics as renewable energy use). As a result, maps were used to visualize the global differences in renewable energy use and bar graphs were used to visualize the countries with the highest renewable energy use. Interactive features for geographic region and income level were used in the final graphic to narrow the visualization to countries of specific geographic/income attributes. Because maps were used, color encodings were used to display the relative renewable energy use of each country. While I initially just used map visualizations, feedback included the difficulty of visualizing the top-5 countries by renewable energy use. As a result, I decided to include supporting bar graphs, where coloring each bar by geographic region or income level clearly displayed the attributes of countries with the highest renewable energy use. 

## Feedback

As discussed above, the main feedback I received was the difficulty in viewing the top-5 countries by renewable energy use. The second piece of feedback I received related to the first sheet of the story, where I did not initially include the second map of total energy consumption in 2015, by country. While it is somewhat clear from the first map that countries with the highest renewable energy share also use the least energy, the second map makes this observation much clearer.

## Python Libraries: The code in this repository assumes the following Python libraries are installed:
* numpy
* pandas
