# Business Analytics with Python: Kenvue (MGTC28H3 Group 2)

#### How are you going to approach the problem(abstract)?
All of us should look through and try to understand the data provided. Then, we should clean the data and draft some graphs to understand the data better. We should investigate different external data to see if it provides us with more information. Using the trends we have graphed and the external information we have gathered we should start to guess the need states and select 3 to explore further. 

#### What do you hope to achieve, given the data?
Given the data, we hope to correctly guess the need states, forecast figures and draw interesting insights. 

#### Who is in your group, and what is the division of labour?
The members of group 2 are Elaine, Han, Jackie and Janvi. 
The division of labour was split equally amongst the 4 members, with each member receiving an Excel file to clean. 
Cleaning total sales data was completed by Janvi, cleaning inventory data was completed by Jackie, cleaning ecomm data was completed by Hanna and cleaning factory pos data was completed by Elaine. After cleaning, the weather data we would explore was split equally. 
We each experimented with the datasets in Power BI to draw high-level analysis about any sales and seasonality trends to predict need states to narrow down external analysis using APIs.
Each of us analyzed the merged data set against relevant APIs to help discern the need states e.g. UV index, Air Pollution, Humidity, Temperature, and Precipitation.
We will also split finding the correlations and running linear regressions for specific need states' sales figures against API data to quantitatively justify our conclusions about need states. 

#### How are you going to 'clean' and organize the data?
We Pandas to convert each dataset from wide to long in two formats: 1. Years as columns 2. Need States as columns.
Merging our cleaned data sets with Pandas e.g. ecomm and Factory POS (merged file 1) and DC sales and Total sales (merged file 2) then merging merged file 1 and merged file 2 to create one long dataset with Need States as Columns
Using functions like pivot, concat, merge, column rename, melt, to_csv.
The pivot function was used to aggregate and summarize specific parts of the data we would like to focus on.

#### What external data/website are you using to aid your analysis(references)? 
https://openweathermap.org/api
https://climate.weather.gc.ca/ 
https://www.visualcrossing.com/ 

#### What technologies are involved (software, packages/libraries, techniques)?
Using Jupyterhub to clean the dataset with the Pandas library and Numpy library.
Using Power BI to help visualize data and point out any significant trends based on sales, ecomm, dc and store inventory.
Using requests library to call APIs (Air Pollution, Current Weather etc.)
