# Bike Usage 
An analysis of CityBike's bike trips 
-----

CityBike is a rental bike company in NYC. Using data extracted from August 2019, we can explore the customers' demographics, duration of the rental, locations to start and end trips. Let's view the data, and see if additional growth opportunities exist.
[Bike Trip Visualized Story](https://public.tableau.com/profile/emily.mcdaniel#!/vizhome/BikeTripAnalysis-Challenge/BikeTripAnalysis?publish=yes)

## Overview of the statistical analysis:
Data was extracted from CityBike's system data. It was then run through Tableau to make calculations, compare fields, and create visuals. Some fields were unable to be properly calculated in Tableau; python was used to do basic recalculations and was then run through Tableau for 

Please see time date field update calculation in [python:]()

## Results Summary:
Bikes are used at all hours of the day, with a particular concentration around commuter hours. ![Trips by Weekeday per Hour]()
CityBike is popular among females, males, and unknown genders. ![Trips by Weekeday per Hour]()
People across all age groups and genders utilize the program. ![Trips by Gender (Weekeday per Hour)]()
Nearly all trips last less than 1 hour; the majority under 20 minutes. ![Trip Duration by Hour]()
The length of rides is about the same across all genders. ![Ride Duration by Gender]()
Males are most likely to utilize the program if they are subscribers; those with unknown genders are less likely to be subscribed to the program, but they do contribute to the overall usage. ![User trips by Gender by Weekday]()



There are at least seven visualizations for the NYC Citibike analysis (7 pt)

### Future Analysis:
Where bikes start and end their trips is significant to improve ease of access. Notice more bikes end their trips in outside Manhattan than bikes that start their trips. This is significant for bike returns and distribution. 
![Popular Start Locations]()
![Popular End Locations]()
