### CITI BIKE TRIP DATA ANALYSIS (Jan 2019 and Jan 2020)
**Tableau Public Workbook**: [Citi Bike Trip Analysis](https://public.tableau.com/profile/aastha.arora#!/vizhome/CitiBikeTripAnalysisJan2019vsJan2020/CitiBike)


Citi Bike is a privately-owned public bicycle sharing system serving the New York City boroughs of the Bronx, Brooklyn, Manhattan, and Queens, as well as Jersey City, New Jersey. (Source: Wikipedia)

The data for this analysis is collected from (https://www.citibikenyc.com/system-data)

The dataset for two months was combined and cleaned using Python before making the visualizations in Tableau.
Visualizations are based on New York City data for two months - Jan 2019 and Jan 2020. Dataset does not include the data for Jersey City.


#### RESEARCH QUESTIONS

* How many trips have been recorded total during the period?
* By what percentage has total ridership grown?
* How has the proportion of short-term customers and annual subscribers changed?
* How are the number of bike rides spread across the week?
* What are the top 10 stations in the city for starting and ending a bike trip?
* What are the bottom 10 stations in the city for starting and ending a bike trip?
* How does the bike ridership change by gender?
* How does the average trip duration change by age?


#### ANALYSIS

**Bike Trips**

In Jan 2019, there were 967,269 recorded Citi Bike trips. This number increased to 1,240,596 in Jan 2020 (increase of 28.26%)


**User Types**

Citi Bike has two tiers of users: customers who pay for one and three day passes, and subscribers who pay an annual fee for unlimited bike use. The bulk of the user base are annual subscribers. In Jan 2019, bike rides by subscribers were 95.85% of the total bike rides in the month. In Jan 2020, the percentage for subscribers was 92.36% and percentage for customers were 7.64%.


**Peak Hours**
The peak hours during which most bike rides start are different for weekdays and weekends. On weekdays, peak hours are 8 am, 5 pm and 6pm whereas on the weekends (Saturday and Sunday), the peak hours were in the afternoon between 12 pm to 2 pm.


**Station Use**
The most popular stations for beginning and ending a trip are largely the same, as are the least popular stations. Stations with most bike rides are close to the busy subway stations and MTA bus stops.


**Bike Ridership**
There are three categories for gender: male, female, and unknown. Most riders are male, in the age group of 25-59 years.

![](https://github.com/Aastha-Arora/Citi-Bike-Trip-Analysis/blob/master/Images/rides_by_gender.png)

Bike ridership was also analyzed over the days of the week. It was observed that on average, people is the age group of 40-59 years use citi bikes more on weekdays compared to weekends.


**Trip Duration**
Average trip duration for women is greater than the average trip duration for men.
Also, the average trip duration over the weekend is greater than the average trip duration over the weekdays.  This trend was observed across almost all categories of age for both males and females.

<ins>Note:</ins> To analyze the bike ridership and trip duration, the age of bike riders was classified in four categories
* Youth (Age < 25)
* Young Adults (Age 25 to 39)
* Middle-aged Adults (Age 40 to 59)
* Old Adults (Age 60+ years)


#### TABLEAU STORY PREVIEW
![](https://github.com/Aastha-Arora/Citi-Bike-Trip-Analysis/blob/master/Images/citibike_analysis.gif)
