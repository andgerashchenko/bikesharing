# Citybike analysis
## Overview
The purpose of the analysis is to solidify a business proposal for bike-sharing program. The bike trip analysis will be shown to stakeholders in order to proof sustainability and perspective of the project. The whole analysis can be found by this link [Citibike analysis](https://public.tableau.com/app/profile/andrew.g6415/viz/Citibike_16267998413540/Citibankbikesanalysis#1)

## Results
- During the analysis we created several plots, reflecting current situation in the business. On the first page performed data showing distribution of rides between genders during the every day of week and the quantity of rides relatively to its duration. [Checkout times for Users by Gender](https://github.com/andgerashchenko/bikesharing/blob/main/Resources/checkout%20times.png)

- In order to determine peak hours and days of week, the following plots were made: [Trips per hour and weekday for Genders](https://github.com/andgerashchenko/bikesharing/blob/main/Resources/trips%20each%20hour%20by%20weekday.png)
Here you can see how many rides occure in particular hour on each weekday, separated by genders. For clearer understanding different types of plots has been used.

- Next set of plots gives picture of what weekday is mostly popular for bike sharing among different types of customers and genders: [Checkout chance by weekday](https://github.com/andgerashchenko/bikesharing/blob/main/Resources/trips%20by%20weekday.png)
The pie chart shows percentage probability of bike checkout for each group. Second plot shows the same analysis in absolute values in comparison between groups using colors.

- The last page compares plots showing starting and ending locations, using map and colored bubbles reflecting more or less popular stations: [Start/End Locations](https://github.com/andgerashchenko/bikesharing/blob/main/Resources/locations.png)
 
## Summary
Deep understanding of how the business operates is crucial for effective management and proper investment. In this particular case we need to know how to distribute additional stations, where to point maintanance teams and how to build marketing strategy. 
From first set of plots ([Checkout chance by weekday](https://github.com/andgerashchenko/bikesharing/blob/main/Resources/trips%20by%20weekday.png)) we can see how long people ride the bikes more often. So the charts shows that 3 to 10 minutes is most likely ride duration. That means that bikes usually don't travel too far. Which is confirmed by other plots ([Start/End Locations](https://github.com/andgerashchenko/bikesharing/blob/main/Resources/locations.png)). Here we can clearly see that starting and ending locations not very differ in terms of volume of rides. This also means that the most wearout bikes will concentrate in the same areas, which is easier for maintenance.

Next page ([Trips per hour and weekday for Genders](https://github.com/andgerashchenko/bikesharing/blob/main/Resources/trips%20each%20hour%20by%20weekday.png)) shows what time during the day on what weekdays people rides more. During the working days, Monday to Friday, peak hours stand out clearly. This is when people take bikes to get to work in the morning and back home in the evening. Those are likely subscribers, because they ride every day. And on the weekend the charts smooth out the peaks. Here we also can determine the least popular time, which is about 2am to 4am. This time is the most suitable for maintenance.

From the all scope of built plots we can assume that bike sharing is more often uses by male customers. This informations can be used in marketing purposes, but it is likely insufficient. Therefore we can make couple more charts with demographic data. Such as bar chart of Birth Year, Gender and Amount of rides. Also detecting of most weared bikes is very important. So we can use Bikeid data, against trip duration in orders to find those bikes.
