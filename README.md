# Covid19 Dynamic Dashboard

The interactive Tableau dashboard is here. The information below will detail the project's goal, tool used, and a comprehensive user guide for the dashboard


## Project Goals

SARS-CoV-2 (COVID19) has been a main part of our lives in the past 3 years.
Given the daily coronovirus dataset, 
our goal is create a dynamic dashboard that can effectively detail the infection,death,vaccination informations for all countries.




## Dataset  

The Dataset was taken from OurWorldInData. The dataset set was partition into two (Death&Contact information, Vaccination information).
The first dataset (Covid-19.csv) contains 165181 entries with 26 features. The second dataset (CovidVaccination.csv) contains 165181 entries with 45 features.
Both datasets span from 1/20/2020 to 2/28/2022 and have unique identifier that can be used for various joins for later analysis

*Note: The dashboard will be updated every two months with the available data.

## Tools

| **Tools**                    | **Purpose**                   | **Link**                                                                                          |
|------------------------------|-------------------------------|---------------------------------------------------------------------------------------------------|
| SQL Server Management Studio | Data Preparation & Processing | https://docs.microsoft.com/en-us/sql/ssms/sql-server-management-studio-ssms?view=sql-server-ver15 |
| Tableau Public               | Data Visualization            | https://public.tableau.com/en-us/s/                                                               |
| Microsoft Excel              | Data Export                   | https://www.microsoft.com/en-us/microsoft-365/excel                                               |


## User Guide

The dashboard is divided by 5 sections.

  1. Covid Mortality Heat Map
  * The heatmap serves two functions, the dynamaic filtering and mortality rate in relations to
  other countries. You can either click into the map to filter the region/location you want or directly search
  the location in the search bar on the top left corner. To return back to World View, please reselect the country that was filtered.The heat map ranges from 0 to 6+. Countries with higher
  mortality rate will be associated with a darker red color. 

  2. Quick Covid statistics.
  * This selection provides the population, total inflection amount, inflection rate, total mortality, mortality rate, total vaccine given(both shots + booster) and fully vaccinated rate.

  3. Percent Population Vaccinated.
  * The bar graph is broken down into three selections. First bar is the population that recieved at least one dose. Second bar is the population that receive two doses(Fully Vaccinated).
  The last bar represent the population that recieved the booster shot. Hovering over bar will show you the respective precentage.

  4. Mortality Over Time
   * The time series histogram is from 1/20/2020 to 2/28/2022 and paritioned by weeks. It displays the running total mortality amount. Hovering 
  over the bar will show you the respective running total.

  5. Inflection Over Time

  * The time series histogram is from 1/20/2020 to 2/28/2022 and paritioned by weeks. It displays the running total inflection amount. Hovering 
  over the bar will show you the respective running total.

    



