# Manitoba Wheat Production and Rhode Island Electricity Demand
### 💡 I was asked to answer two questions for a Python assignment. Both questions were to be answered through Jupyter notebook files, I added them to this repo for version control and for anyone's review! 

## Question 1: Estimate the forecasted total production of Wheat or Canola for the year 2025 in Winnipeg and its surrounding areas. Show all thought processes and any supporting claims of data that leads up to your answer. ###

Link to notebook is [here](https://github.com/connorthornhill9/manitoba_wheat_and_RI_demand/blob/main/Scripts/Forecaster%20Take%20Home%20-%20Winnipeg%20Wheat%20Forecast.ipynb)

* I chose to answer the question specifically for *wheat* data.
* Data collection was part of the assignment and I only wanted to use a reputable data source so I elected to rely on Statistics Canada. Link to [data source](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=3210035901). 🍁
* **My goal** was to have a short example of how I would Collect, Preprocess, Explore, Feature Engineer, Select and Develop a Model.
* There was not much guidance so I decided to create a quick *gradient boosting model* to forecast wheat production.
* More work could be done on confidence intervals, however, I was farily happy with the output espcially considering the effort I made in preparing the data.

## Question 2: Attached is a record of hourly load data of the state of Rhode Island as published by ISO New England
### 1. Analyze the data and make justifications on why the peak load use was the hour that it was. 
### 2. Show work in a *.ipynb notebook  
### 3. To get you started, keep in mind that the largest factor is weather. ##

Link to notebook is [here](https://github.com/connorthornhill9/manitoba_wheat_and_RI_demand/blob/main/Scripts/Forecaster%20Take%20Home%20-%20Rhode%20Island%20Peak%20Demand.ipynb)

* I was provided with Rhode Island hourly load data to help answer the question, however, no weather data was provided.
* I collected weather data from [this](https://www.timeanddate.com/weather/usa/providence/historic?month=10&year=2024) website 🌞. I only collected weather data for days surrounding October 4th, 2024 since I had to balance my time between data collection and analysis.
* **My goal** was to provide an example on how I would conduct exploratory analysis on historical data.
* I elected to focus on feature engineering and explainin peak load based on a regression model since stakeholders find them more easy to understand (at least in my experience).

