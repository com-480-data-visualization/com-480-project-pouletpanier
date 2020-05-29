# Project of Data Visualization (COM-480)

| Student's name | SCIPER |
| -------------- | ------ |
|Olivier Quôc-Vinh Lam |274550 |
|Rayane Laraki |274900 |
|Stanislas Michel Jouven |260580 |

[Milestone 1](#milestone-1-friday-3rd-april-5pm) • [Milestone 2](#milestone-2-friday-1st-may-5pm) • [Milestone 3](#milestone-3-thursday-28th-may-5pm)

## Milestone 1 (Friday 3rd April, 5pm)

**10% of the final grade**
### 2.1: Dataset:

Here are the 5 selected datasets for the project:

[Covid 19](https://data.europa.eu/euodp/en/data/dataset/covid-19-coronavirus-data)

[Covid 19 in South Korea](https://www.kaggle.com/kimjihoo/coronavirusdataset)

[Covid 19: mitigation measures](http://epidemicforecasting.org/containment)

[SARS](https://www.kaggle.com/imdevskp/sars-outbreak-2003-complete-dataset)

[Ebola](https://www.kaggle.com/imdevskp/ebola-outbreak-20142016-complete-dataset) 

Preprocessing on these datasets can be evaluated in Section 2.3 when we ploted some statistics on the data.

### 2.2: Problematic:

* What am I trying to show with my visualization? 

  Our visualization will try to show as best as we can who and where people are affected by the corona virus. Is it worldwide ? Is it concentrated in some dense areas ? Also how fast the virus spreads will be shown in the visualization. Therefore our visualization will show the consequence of the corona virus on the population.

* Think of an overview for the project, your motivation, and the target audience.

  Since the corona virus is happening right now and impact our living, the whole population wants to be informed of the coronavirus. We would split our project into three parts:
  - How dangerous is this virus and how dangerous it is compared to the Ebola/ SARS disease.
  - Where and how fast the virus spreads among the world (A map showing the number of cases/deaths over time)
  - How the government decisions impact the spread of the virus
  
### 2.3: Exploratory Data Analysis

The five datasets listed in **2.1** are already very clean and need very little pre-processing.

The first dataset from the European Union Open Data shows some basic statistics, as the number of cases and the number of deaths per country and per continent for each each as well as the total population for each country.

The second dataset is based on data in South Korea. This dataset contains detailed informations on the people affected by the corona virus in South Korea. At a first look the South Korea dataset on Covid 19 seems to contain more data on South Korean people compared to the Covid 19 dataset. We specifically selected this country because the South Korean government adopted a different politic compared to the rest of the world and we want as much data as possible.

The third dataset contains all the measures that the governments (worldwide) took in order to slow down the propagation of the coronavirus. 

The last datasets represents the daily evolution of the ebola and the sars worlwide, with the number of cases/deaths/recovers per country. 

Some little statistics and plots have been done in the following Jupyter notebook : [Milestone 1 Notebook](https://github.com/com-480-data-visualization/com-480-project-pouletpanier/blob/master/milestone1.ipynb)


### 2.4: Related work:

* What others have already done with the data?

Multiple maps updated regularly with the new information incoming every time. The most famous one is the Johns Hopkins map which shows the global situation in the world but also specific statistics for each country.

* Why is your approach original?

Our approach is original as we will try to get an insight of the repercutions of politic countermeasures on the general spread of the virus and also compare the efficacity of different politics on the evolution of the pandemic.

* What source of inspiration do you take? Visualizations that you found on other websites or magazines (might be unrelated to your data).

Considering the extroardinary turn of events as the lockdown of the most part of the world and the trumendous economic crisis that we face, we wanted to elaborate results and better understand the politic decisions by working on the data from scratch. It would allow us to develop our own point of vue, maybe different that the one vehiculated by the medias.

To a lesser extent, maybe that those vizualisations of the first countries affected by the coronavirus could have helped governements to take the right decisions at the right time and prevent the global spread that we are now facing.

## Milestone 2 (Friday 1st May, 5pm)

The git hub holding the website code can be found [here](https://github.com/rlaraki/rlaraki.github.io) and the visualization of the website can be seen [here](https://rlaraki.github.io/).





## Milestone 3 (Thursday 28th May, 5pm)

The link of our website can be found here : https://rlaraki.github.io
The link of the required video can be found here: https://youtu.be/wMgqrpahrcY

### Tools
- D3.js v5
- Bootstrap v4
- topojson.js v3

### User Guide

The website is composed of a 4-buttons menu. From the choice of the selected button, a corresponding map is shown with more precise data in the right scroll view. 

The table below summarizes the functionnalities of theses buttons.

|Button|Description|
|---|---|
| Cases|The map for cases shows the cumulative number of cases per region, which are represented by the red circles. A slider on the top of map allows the user to visualise how the number of cases per region evolves by the time. The user can select a country to visualize a line plot of the evolution of the number of cases and a sankey diagram that shows the ratio of women/men that are alive/dead. For each additional selected country, a new line in the line plot is drawn and an additional sankey diagram is shown. Some lines or sankey diagram may not be shown due to the missing data for some countries.|
|Deaths|The map for cases shows the cumulative number of deaths per region, which are represented by the black circles. A slider on the top of map allows the user to visualise how the number of deaths per region evolves by the time. The user can select a country to visualize a line plot of the evolution of the number of deaths and a sankey diagram that shows the ratio of women/men that are alive/dead. For each additional selected country, a new line in the line plot is drawn and an additional sankey diagram is shown. Some lines or sankey diagram may not be shown due to the missing data for some countries.|
|Recovered|The map for cases shows the cumulative number of recovers per region, which are represented by the green circles. A slider on the top of map allows the user to visualise how the number of recovers per region evolves by the time. The user can select a country to visualize a line plot of the evolution of the number of recovers. For each additional selected country, a new line in the line plot is drawn. Some lines may not be shown due to the missing data for some countries.|
|Measures|The choropleth map for measures shows the stringency index by country over the time. The stringency index is a government measure tracker based on policy indicators such as school closures or movement restriction, record economic policy such as income support to citizens or provision of foreign and finally record health system policies such as the COVID-19 testing regime or emergency investments into healthcare. A slider on the top of the map allows the user to visualise the evolution of the strigency index over the time. The user can select a country to visualize a line plot of the number of contamination cases with little circles that represent a decision making by the government and also a line plot representing the cumulative number of tests done on the country's habitants. Some lines may not be shown due to the missing data for some countries.|



### Authors

- Rayane Laraki
- Stanislas Michel Jouven
- Olivier Quôc-Vinh Lam

