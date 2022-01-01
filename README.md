# NYC Citibike Analysis

## OVERVIEW
### Purpose:  The purpose of this analytical project was to prepare visualizations that give potential investors a look into a highly-successful NYC Citibike bike-sharing program, so they can consider proposed investment in the creation of a bike-sharing program in Des Moines, IA. Among others, we have prepared visualizations that 1) Show the length of time that bikes are checked out for all riders and genders, 2) Show the number of bike trips for all riders and genders for each hour of each day of the week, and 3) Show the number of bike trips for each type of user and gender for each day of the week.


## RESOURCES
  - Source Files: 201908-citibike-tripdata.csv, 201908-citibike-revised_tripdata.csv
  - Software:  Tableau, Python 3.7.6, Jupyter NB, Pandas Library


## RESULTS
#### The results of our analysis have been incorporated into a [story on Tableau Public](https://public.tableau.com/profile/john.ramonetti#!/vizhome/NYC_CitiBike_Visualizations/FinalPresentation?publish=yes)

Comparing visualizations for the **'Top Starting Locations'** and **'Top Ending Locations'**, we can see that the most active starting locations are also among the most active ending locations.  This is important, because we need to know whether there might be an excess or shortage of bikes at particularly stations over time.


Looking at visualizations for **'Checkout Times for Users'** and **'Checkout Times by Gender'**, we see that most rides are for 20 minutes or less, and that the vast majority of rides are less than one hour.  We also see that this pattern is the same regardless of gender.


The **'Gender Breakdown'** pie chart shows that males in NYC utilize the bikesharing program almost 3 times as often as females.  Further analysis is needed to understand why this is the case.

The heatmap of **'Trips by Weekday per Hour'** shows a clear pattern of bicycle useage 1) during the morning weekday commute (7-9 a.m.), 2) during the evening weekday commute (4-7 p.m.) except on Wednesday evenings, and 3) all day long on weekends.


The **'Trips by Gender (Weekday per Hour)'** heatmap shows that the useage pattern is true regardless of gender, although the total numbers for males is considerably higher.

The **'User Trips by Gender by Weekday'** heatmap demonstrates the following points:  subscribers are mostly male and account for most of the weekday activity,  customers' gender are often unknown,  and useage on the weekend is more evenly split between subscribers and customers.

Our **'Bike Utilization'** and **'Bike Repairs'** charts show that some bikes are used for many trips and many total hours, while other bikes are hardly used at all.  More analysis is called for to assess whether there are predictable patterns of use for high- or low-use bikes.



