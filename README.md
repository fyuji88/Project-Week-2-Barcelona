<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Accidents & Motorbikes in Barcelona
*[Felipe Yuji Deguchi Hayashi]*
*[Sander Roos]*

*[Data Analytics Full Time, Barcelona, 3rd of July 2020]*

## Content
- [Project Description](#project-description)
- [Questions & Hypotheses](#questions-hypotheses)
- [Dataset](#dataset)
- [Database](#database)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)


## Project Description

The purpose of the project is to analyze datasets about accidents and if there is any correlation with motorbikes on the streets. This allow the data analysts to perform data exploration, data cleaning, data wrangling and hypothesis formulation.

## Questions & Hypotheses

Do the total number of motorbikes has influence over the number of accidents? Do their power/size correlates with accidents rate? What about deaths?

## Dataset

- Dataset: Transportation related accidents in Barcelona
- Source: https://opendata-ajuntament.barcelona.cat/
- Historical Data: 2016 and 2017
- Numerical Data: Accidents, Victims, Light Injuries, Serious Injuries, Deaths
- Categorical data: Neighborhood, District, Time of the day(ordinal)

- Dataset: Motorbikes registered in Barcelona
- Source: https://opendata-ajuntament.barcelona.cat/
- Historical Data: 2016 and 2017
- Numerical Data: Number of motorbikes registered
- Categorical data: Neighborhood, District, displacement capacity(cc)



## Database

The accidents dataset was was grouped by district while the motorbike dataset was one-hot coded by bike category an then grouped by district. Both sets were merged by district.

## Workflow
- 1 - Data Source Mining
- 2 - Data wrangling
- 3 - Data Analysis
- 4 - Identification of improvement points/next steps

## Organization

The project was organized by using a trello board in order to estimate a to-do list with priorities and resource estimation.

## Links
Include links to your repository, slides and kanban board. Feel free to include any other links associated with your project.

[Repository](https://github.com/fyuji88/Project-Week-2-Barcelona.git)  
[Slides](https://github.com/fyuji88/Project-Week-2-Barcelona/blob/master/group7_transportation.pptx)  
[Trello](https://trello.com/b/fcysoBiU/transportation-analysis)  
