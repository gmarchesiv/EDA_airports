# EDA_airports

This repository explores commercial airplane flight delays in the United States from 2011 to 2020. The notebook is designed to be a quickstart guides performing EDA with the most common Python methods and functions. 

The data was downloaded from the Bureau of Transportation Statistics website https://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp.  

The EDA notebook loads the data and performs a series of commands to format, clean, feature engineer and perform exploratory analysis.

The corresponding csv files are:

•	airline_delay_causes.rar  
•	airport_latlong.csv

The first dataset contains flight statistics for all airports in the United States. Each observation is reported by month, year, airport, and airline. Flights can be categorized as on time, delayed, canceled or diverted. Flight delays are attributed to five causes: carrier, weather, NAS, security, and late aircraft. The second csv contains the latitude and longitude of all US airports to merge into the main dataset. The notebook also exports the clean dataset, which contains 157,906 observations.

The follow-up analysis is performed through a series of visualizations in gmarchesiv/Visualizations_airports. 

