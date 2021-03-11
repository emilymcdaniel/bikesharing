# Bike Usage 
An analysis of CityBike's bike trips 
-----

CityBike is a rental bike company in NYC. Using data extracted from August 2019, we can explore the customers' demographics, duration of the rental, locations to start and end trips. Let's view the data, and see if additional growth opportunities exist.

[Bike Trip Visualized Story](https://public.tableau.com/profile/emily.mcdaniel#!/vizhome/BikeTripAnalysis-Challenge/BikeTripAnalysis?publish=yes)

## Overview of the statistical analysis:
Data was extracted from CityBike's system data. It was then run through Tableau to make calculations, compare fields, and create visuals. Some fields were unable to be properly calculated in Tableau; python was used to do basic recalculations and was then run through Tableau for 

See timedate field update [calculation](https://github.com/emilymcdaniel/bikesharing/blob/main/NYC_Citibike_Challenge.ipynb)

## Results Summary:
Bikes are used at all hours of the day, with a particular concentration around commuter hours. 
![Trips by Weekday Hours](https://github.com/emilymcdaniel/bikesharing/blob/main/Resources/Trips%20by%20Weekeday%20by%20Hour.PNG?raw=true)

CityBike is popular among females, males, and unknown genders. 
![Trips by Weekday Hours per Gender](https://github.com/emilymcdaniel/bikesharing/blob/main/Resources/Trips%20by%20Weekday%20Hours%20by%20Gender.PNG?raw=true)

People across all age groups and genders utilize the program. 
![Trips by Gender (Weekday per Hour)](https://github.com/emilymcdaniel/bikesharing/blob/main/Resources/Bike%20usage%20by%20age%20and%20gender.PNG?raw=true)

Nearly all trips last less than 1 hour; the majority under 20 minutes. 
![Trip Duration by Hour](https://github.com/emilymcdaniel/bikesharing/blob/main/Resources/Trip%20duration.PNG?raw=true)

The length of rides is about the same across all genders. 
![Ride Duration by Gender](https://github.com/emilymcdaniel/bikesharing/blob/main/Resources/Trip%20duration%20by%20gender.PNG?raw=true)

Males are most likely to utilize the program if they are subscribers; those of unknown genders are less likely to be subscribed to the program, but they do contribute to the overall usage. 
![User trips by Gender by Weekday](https://github.com/emilymcdaniel/bikesharing/blob/main/Resources/Subscribers.PNG?raw=true)

### Analysis & Additional Questions:
- There is a high turnover of bikes based on the duration of rentals lasting less than 20 minutes. Consideration for where bikes are left and the condition they are in (dirty? low power?) impacts whether another user will use the bike. Also think about how repairs or replacements factor in.
- Users can try the program as customers, and then advance their membership as a subscribers. Is there an advantage for customers or for CityBike to have subscriptions? Does it increase the company's visibility or lower the cost per ride?


### Future Analysis:
-Females do not utilize bikes as often as males. Push a survey among female subscribers to see what would they like, don't like, and what would encourage them to consider biking more often.
- Where bikes start and end their trips is significant to improve ease of access. Notice more bikes end their trips in outside Manhattan than bikes that start their trips. This is significant for bike returns and distribution. 

![Popular Start Locations](https://github.com/emilymcdaniel/bikesharing/blob/main/Resources/Start%20locations.PNG?raw=true)
![Popular End Locations](https://github.com/emilymcdaniel/bikesharing/blob/main/Resources/End%20locations.PNG?raw=true)
