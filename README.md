# Project-Covid-19 #
## Introduction
This is a project from the N30days of learning by Microsoft, hosted by @oyinbooke. It encompasses the exploration of covid-19 data, from the collection of data (scraped from web) to the importation into Ms Excel, to the data transformation and data cleaning  with the aid of power query to the visualization of insights from the analyse.
## Project Objectives
The project was carried out for get answers to the following questions;
* Which top 5 countries have the highest prevelance of confirmed covid-19 cases?
* Which bottom 5 countries have the lowest prevelance of confirmed covid-19 cases?
* What is the annual cummulative number of confimed covid-19 cases since 2020?
* What is the monthly cummulative number of confimed covid-19 cases since 2020?
## Data Sourcing
The data imported was scraped from Johns Hopkins University's Center for Systems Science and Engineering (CSSE) [github page](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series). The data comprises of confirmed covid-19 cases, death cases and recovered cases from July 2020 to June 2022
## Data Transformation
* Upon completion of data scraping from github and importation into Ms Excel with the aid of power query, the source was further altered to ensure any update made in the data origin reflects in the imported data. 
* The data was cleaned eradicating redundancy
* The three tables were then merged together, left joining the confirmed cases tables to the recovered and death tables to give one table that was named the consolidated data
* It was then loaded into excel for further analysis.
* Upon its loading into excel, I extracted the Year, Month and day column using the year, text and day functions
![Consolidated Data](https://user-images.githubusercontent.com/105971924/188252687-d1b349e3-fd4e-4115-bc24-fbba1ac4976f.png)
![Extracted Month, Day and Year](https://user-images.githubusercontent.com/105971924/188252767-6ee1664a-0bbb-466f-a6c2-9c9649ed65c4.png)
## Analyzing of Data
Pivot tables were used to analye the top 5 countries with the highest prevelance of confirmed covid-19 cases, bottom 5 countries with the least prevelance of confirmed covid-19 cases, annual cummulative number of confimed covid-19 cases since 2020,monthly cummulative number of confimed covid-19 cases since 2020, rate of death,![Analysis Tab](https://user-images.githubusercontent.com/105971924/188252872-183b1720-5325-44c6-9797-0befe85c4f6f.png)
## Visualization
Pivot Charts were used to visualize analyses from the pivot table![COVID-19 Dashboard](https://user-images.githubusercontent.com/105971924/188253408-9cea6bff-ffef-46a6-a2e2-6c8d6a8f13a2.png)
## Insights and Finding
From the analysis carried out the following were the findings;
* Rate of death is 2%, which insinuates that only 2% of people with confirmed COVID-19 cases died due the virus
* The United States have the highest number of COVID-19 cases followed by India, Brazil, France and the United Kingdom
* North korea has the lowest number of COVID-19 cases followed by Micronesia, Antarctica, Marshall Islands and MS Zaandam
* The virus has increased by 1002% (as at June 2022) since its inception in July 2020
* Over the years, cumulatively, the highest number of confirmed cases were recorded in the month of May and the least cases were recorded in July.
