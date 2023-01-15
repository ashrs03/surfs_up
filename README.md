# SURFS_UP 

## Overview of the statistical analysis

Investor's main concern before venturing into new territory is to understand the market, climatic conditions whether htey are condusive to the business and the market size. W. Avy liked the analysis including looking at seasonal variation in temperature for Oahu, but wanted more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

To analyze Hawaii's weather data, SQLAlchemy was used to query the SQLite database.

## Results
Baseline analysis of climate in Oahu included looking at the precipitation data for year 2016 and 2017, fiding the list of stations available in the dataset, query to find minimum and maximum temperature at most active station, looking at temperature data and plotting the parameters in a plot/ chart for graphical illustration. 
Link of the analysis steps are at http://localhost:8888/notebooks/surfs_up/climate_analysis.ipynb

### To answer specific questions that W.Avy has, further analysis was conducted and the analysis steps for this are in:
https://github.com/ashrs03/surfs_up/blob/main/SurfsUp_Challenge.ipynb

Summary statistics for the analysis for temperatures in June are
![image](https://user-images.githubusercontent.com/42523379/212569543-3c06502c-81aa-4c65-b1cc-1fb5cb447ec5.png)

June Temperature plot 
![image](https://user-images.githubusercontent.com/42523379/212569573-bed031a6-5b51-4827-ac57-878128a1f645.png)

Summary statistics for Dec are
![image](https://user-images.githubusercontent.com/42523379/212569526-7f20464f-bb1e-4c78-96d2-b187396a8a59.png)

December Temperature plot 
![image](https://user-images.githubusercontent.com/42523379/212569594-2db2e2e9-4622-4489-a1b8-a6a5405a60bc.png)


## Summary
June temperature by precipitation
![image](https://user-images.githubusercontent.com/42523379/212569605-58124b8d-b96a-4401-ad74-576a1e847f1e.png)

Dec temperature by precipitation
![image](https://user-images.githubusercontent.com/42523379/212569640-c501151b-93f2-4480-8742-6889ee5769e1.png)

