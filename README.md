[Link to Dashboard](https://public.tableau.com/app/profile/mark.melendez/viz/Module14Challenge-TableauCitibike/CitibikeStory)

## Overview of the statistical analysis:

The purpose of this analysis is to create a dasbhoard to help visualize bikesharing data in New York City. We'll do so by parsing data obtained from Citibike and importing the text file into Tableau for analysis. We've first converted the datatype for the "trip duration" column by loading our data into Pandas, creating a dataframe, converting the datatype, replacing the trip duration column with our converted values, and finally, exported the data to be later imported into Tableau. Our goal was to highlight the the length of time that bikes are checked out for all riders and genders, display the number of bike trips for all riders and genders for each hour of each dya of the week, and to also show the number of bike trips for each type of user and gender for each day of the week.

## Results:

In the first slide of our dashboard, we can identify a trend within the trip duration and understand how long bikes are checked out for all riders - 

### Over 140k bikes were checked out for more or less 5 minutes
![image](https://user-images.githubusercontent.com/89496798/149846342-f253e8ef-b906-4a79-aeec-3fd9c36c8362.png)

Our next slide shows the top starting and ending locations for all bikes:

### Many share similar traffic from where the bikes start and end
![image](https://user-images.githubusercontent.com/89496798/149846451-ac8d9ebd-71b7-4524-90c9-f4493430615c.png)

The following slide highlights which hours by Weekday have the most activity:

### It appears common commuting times tend to be the busiest - between 7 AM to 9 AM and between 5 PM to 7 PM
![image](https://user-images.githubusercontent.com/89496798/149846560-1a3ef36a-5acf-4043-99ec-f9fcdead8507.png)

Our last slide gives a high-level overview of how our findings can be broken down by Gender - Male, Female, and Unknown:

### We can also see which user trips by Gender, within any given weekday, are customers vs. subscribers
![image](https://user-images.githubusercontent.com/89496798/149846638-6b760775-bf26-4a3b-9606-47e7af36d583.png)

## Summary:

There is a high-level summary of the results and two additional visualizations are suggested for future analysis (5 pt)
