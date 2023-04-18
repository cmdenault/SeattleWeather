# All About Seattle & St Louis Rainfall
A project for Seattle University's DATA3320 class, where I explore and compare how much it rains in Seattle and St. Louis. To answer the question of what city it rains more in, I used data from the NOAA of daily precipitation values for St. Louis and Seattle for 2018-2022. I then narrowed it to values of interest to us, imputed any missing data, and created a new clean data frame. Using aggregations and analysis of the clean data, graphics were created. I found St. Louis rains more by amount in general and it tends to rain in higher amounts when it does rain, but Seattle has more rainy days versus days it does not rain. 
  
  
    - links to the data: https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND
    
## Software Requirement
  Used Colaboratory, by Google
  Github
  
## Data
  Original data from the NOAA National Centers for Environmental Information.
  We can use their [website]'https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND' to request records of daily precipitation from Seattle and St. Louis (or other locations of interest) for the last 5 years (2018 - 2022)

## Data Processing 
   To clean up the data (data_preparation.ipynb): <br>
      ~ converted necessary data types <br>
      ~ narrowed st louis data to just 2018-2022 and one weather station <br>
      ~ replace seattle's missing values with the mean across years of values on that day <br>
      ~ narrow to a data frame with precipitation data 2018-2022 for st louis and seattle: clean_seattle_stlouis_weather.csv <br> <br>

## Data Analysis
   Analyze the data in the notebook- data_analysis.ipynb -to form an answer to the project's question. To do this: <br>
      ~ broke up the main question into more specific sub-questions <br>
      ~ created new dataframes and graphs with the clean data related to the sub-questions <br>
      ~ come to a conclusion with all of the graphs made <br>
    
# Authors
  Cassidy Denault, _Computer Science Major, Data Science Minor_
    
## License 
   Permitted to use, copy, modify, merge publish, distribute copies of the software.


