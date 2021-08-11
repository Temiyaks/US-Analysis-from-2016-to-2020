# US-Analysis-from-2016-to-2020

EXPLORATORY DATA ANALYSIS OF US ACCIDENTS

The analysis carried on Python Pandas.

Generally across the world, reducing road accidents is at the top agenda of every Government.  Reducing traffic accidents is an essential public safety challenge all over
the world; Interestingly, accident analysis has been a subject of much research in recent decades.

Looking at the severity of road accidents, I decided to analyse the accidents’ data to discover something useful. And here I am, sharing my results.

DATA.
The dataset is taken from Kaggle website. This is a countrywide traffic accident dataset, which covers 49 states of the United States. The data is continuously being collected from  2016 to  2020.

The dataset contains 2,906,610(2.90 million) rows and 49 columns(Quite a large dataset). A point to be noted is that even though the dataset contains data for only four years, there are 2.90 million accidents already.

The analysis include number of accidents by year, number of accidents by state, best time to travel by month, day and hour, accident-prone area in each state, factors responsible of the accidents like weather, wind flow, temperature, location. etc.

The significant findings from the analysis are: 
1. Most of the accidents are happening in October, November, December
2. Nighttime is safe to travel
3. Weather, temperature, and location are the factors responsible for 9% of accidents.

APPROACH
1. I removed all unnecessary features.
2. I  removed all null values that  the columns is above 50%, and fill in the rows that is below 50%. 
3. I replaced empty cell with nan values. 
4. I checked for the columns that is  highly positively correlated absolutely and drop one of the columns.


SUMMARY
The analysis shown the possible reasons and limitations to road accidents in United State. Road accidents are a main public safety issue, with much research devoted to the analysis and prediction of these rare events. The study helped us to derive factors that are responsible for accidents. From this dataset, a variety of insights concerning the location, time, weather, and points-of-interest of an accident are found. The analysis helps us understand the best month, day, and hour of the day to travel. Also, it can help us to predict what are the accident- prone areas in each state. 
Finally, this study recommends infrastructure, Policy, Administrative(Speed Limit and Car Maintenance), and Human Behavior changes(Discipline), which can help to reduce US accidents.
