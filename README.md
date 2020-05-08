# covid-and-inequality
Final project for Alex Lyford's Statistical Learning class at Middlebury College. Collaborators are Bea Lee '20.5, Chica Morrow '20, Jennifer Ko '21, Olivia Jin '20.


## Data Dictionary

* year: year
* fips: county fips code
* County: county
* population: county population
* stateFIPS: state fips code
* State: state

* Evictions: number of evictions in county as of 2016
* County_eviction_rate: (total number of eviction filings in county)/(county population)
* State_eviction_rate: average of county eviction rates in state
* US_eviction_rate: (total number of eviction filings in US)/(US population)
* Evictions_greater_state: 1 if county eviction rate is greater than state average, 0 otherwise
* Evictions_greater_US: 1 if county eviction rate is greater than US average, 0 otherwise

* covidCases: number of reported COVID cases in county
* covidDeaths: number of reported COVID deaths in county
* County_covid_cases_rate: (total number of reported COVID cases in county)/(county population)
* County_covid_death_rate: (total number of reported COVID deaths in county)/(county population)
* State_covid_cases_rate: average of county reported COVID case rates in state
* State_covid_death_rate: average of county reported COVID death rates in state
* US_covid_cases_rate: (total number of reported COVID cases in US)/(US population)
* US_covid_death_rate: (total number of reported COVID deahts in US)/(US population)


## Data Sources

Aggregated COVID cases & deaths from CDC and state & local public health agencies: https://usafacts.org/visualizations/coronavirus-covid-19-spread-map/ 

County-level eviction filing cases as reported by states:
https://evictionlab.org/

US population as of 4/30/2020:
https://www.census.gov/popclock/
