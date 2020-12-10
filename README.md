# Citi-Bike-Analytics uisng Tableau

<img src = "https://github.com/DSB011/Tableau-Homework---Citi-Bike-Analytics/blob/master/Images/citi-bike-station-bikes.jpg">

## Overview

Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. 
However, while the data is made public on the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage and has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have a number of questions on the program, so the first task is to build a set of data reports to provide the answers.

## Objective

The task is to aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena. I designed 15 visualizations for each discovered phenomena. I took the dataset for the year 2017 and cleaned the data in jupyter notebook
and merged the new data and exported in csv format and used it in Tableau Public Desktop to create the visualizations.

## Dataset

The [Trip_Dataset](https://s3.amazonaws.com/tripdata/index.html) was taken from [Citibike](https://www.citibikenyc.com/) website which included trip duration, start time and date, 
stop time and date,start station name, end station name, station ID, Station Lat/Long, Bike ID, user type(Customer = 24-hour pass or 3-day pass user; Subscriber = Annual Member), gender(Zero=unknown; 1=male; 2=female), year of birth.

## Visualizations

The visulaizations were created based on the following questions.
1. How many trips have been recorded total during the chosen period?
2. By what percentage has total ridership grown?
3. How has the proportion of short-term customers and annual subscribers changed?
4. What are the peak hours in which bikes are used during summer months?
5. What are the peak hours in which bikes are used during winter months?
6. What are the top 10 stations in the city for starting a journey? (Based on data, why do you hypothesize these are the top locations?)
7. What are the top 10 stations in the city for ending a journey? (Based on data, why?)
8. What are the bottom 10 stations in the city for starting a journey? (Based on data, why?)
9. What are the bottom 10 stations in the city for ending a journey (Based on data, why?)
10. What is the gender breakdown of active participants (Male v. Female)?
11. How effective has gender outreach been in increasing female ridership over the timespan?
12. How does the average trip duration change by age?
13. What is the average distance in miles that a bike is ridden?
14. Which bikes (by ID) are most likely due for repair or inspection in the timespan?
15. How variable is the utilization by bike ID?

Created a Tableau Dashboard and a Story based on the above questions.<br> 

<img src = "https://raw.githubusercontent.com/DSB011/Tableau-Homework---Citi-Bike-Analytics/master/Images/Tableau_visualization.png"> <br>

<img src = "https://github.com/DSB011/Tableau-Homework---Citi-Bike-Analytics/blob/master/Images/Tableau_story.png"> <br>

## Tech Environment Used
Jupyter Notebook, Tableau Public Desktop.


