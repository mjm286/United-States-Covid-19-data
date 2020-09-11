# United States Covid-19 Dashboard

Data provided by the New York Times was used to create an interactive dashboard displaying information about the Coronavirus in the United States.
The data was analyzed using python programming. See county_level_analysis.ipynb.
Analysis includes
  - County, state and, country datasets are directly read using Pandas package from NYT's github page.
  - Data cleaning and manipulation is performed to accurately access total and daily number of cases and deaths.
  - Calculation of moving averages pertaining to daily cases and deaths.
  - Categorical assignment in the directional change of moving averages week over week.
  - export of state and county level analysis dataframes to .csv files.
  
  
The exported files were used in Tableau to show overall Country, state and county level trends. Vist my Tableau profile at https://public.tableau.com/profile/matthew.m5135#!/vizhome/USACovid-19layoutVer1/Dashboard for full interaction!
