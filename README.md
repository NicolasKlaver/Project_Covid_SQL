# SQL Project: Covid 19 Data Exploration 
In this project I make a Data Exploration Analysis of the Covid 19 dataset where we look correlations to create tables and visualize the results in Tableau in a future project.


#### Skills used: 
- Joins, CTE's, Temp Tables, Windows Functions, Aggregate Functions, Creating Views, Converting Data Types.


#### Data:
- url: https://ourworldindata.org/covid-deaths


#### Files
- data_exploration.sql: contains all the first steps to understand the data.


## Examples of some Queries

##### First Query:
-  We see the maximum cases that occurred in a Location and the percentage that it represents in its Population.
https://github.com/NicolasKlaver/Project_Covid_SQL/blob/e3aab35ab2c21abac21a57b5eeb54e769e3290db/src/Data_Exploration.sql#L31-L38

##### Result:
  ![](https://github.com/NicolasKlaver/Project_Covid_SQL/blob/main/img/query_1_res.png)

##### Second Query:
- We see the global numbers of total cases, total deaths and death percentage.
https://github.com/NicolasKlaver/Project_Covid_SQL/blob/e3aab35ab2c21abac21a57b5eeb54e769e3290db/src/Data_Exploration.sql#L68-L77

##### Result:
  ![](https://github.com/NicolasKlaver/Project_Covid_SQL/blob/main/img/query_2_res.png)

##### Third Query
- We join the table of deaths and vaccinated to see the percent of people vaccinated related to its population.
https://github.com/NicolasKlaver/Project_Covid_SQL/blob/e3aab35ab2c21abac21a57b5eeb54e769e3290db/src/Data_Exploration.sql#L119-L145

##### Result:
 ![](https://github.com/NicolasKlaver/Project_Covid_SQL/blob/main/img/query_3_res2.png)





###### If you want to see the Tableau Project: [Link - Project](https://github.com/NicolasKlaver/Project_Covid_Tableau)
###### If you want to see the Dashboard: [Link - Tableau](https://public.tableau.com/app/profile/nicolas.klaver/viz/Project_Covid_16740827288160/Dashboard1)
