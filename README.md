# Bike-Sharing Programs:  Analyzing NYC Citi Bike-Sharing Data to Pitch Bike-Sharing in Des Moines, Iowa. 

## Overview of Project
After traveling with my friend Kate to NYC this past August and having a blast riding bikes sightseeing around the city using the Citi bike-sharing bikes we thought what a great program this would be in our town of Des Moines, Iowa.  As luck would have it we now have a scheduled presentation to make a pitch to investors as a key step to bring a similar bike-sharing program to Des Moines.  

Kate suggested that I use Citi Bike data that has been released to the public for the analysis.  This sounds logical but we will also need to keep in mind that New York City is much different than Des Moines.  How we choose to analyze and present the Citi bike-sharing data will paint a solid picture, but we'll also need to relate the analyis to demographics, geography and weather of Des Moines. 

### Purpose
The purpose of this project is to convince investors that a bike-sharing program in Des Moines is a solid business proposal.  One of the key stakeholders has requested to see a bike trip analysis.  We have decided an effective tool to use for this pitch is Tableau and to create a Tableau story to present to the stakeholders.  Citi Bike-Sharing data for August 2019 will be used as the data set for analysis.  Pandas and python will be used to convert the data set "tripduration" attribute to the datetime format.

## Results

![NYC_Start_Map](https://raw.githubusercontent.com/JBro-Birds/bikesharing/master/support_images/NYC_Start_Map.png)
The map of NYC starting locations shows the high density in Manhattan which is the core city hub.  Working commuters, students and tourists would most likely be the main driver of these starting locations in the hub of Manhattan.

![Customer_Vs_Subscriber](https://raw.githubusercontent.com/JBro-Birds/bikesharing/master/support_images/Customer_Vs_Subscriber.png)
This chart shows the customer (individual sales) compared to the subscriber base by gender.  There are more subscribers than customers in the NYC bike-sharing program and males are the dominant subscriber base.  The subscriber option should be promoted in areas of high density of residents and commuters while the "customer" option would be more popular in tourist areas.

![Trip_Duration](https://raw.githubusercontent.com/JBro-Birds/bikesharing/master/support_images/Trip_Duration.png)
This chart clearly shows that most trip durations are less than an hour.  This result is expected since trip durations longer than an hour would drive most individuals to find motorised means of transportation.

![Trip_Duration_byGender](https://raw.githubusercontent.com/JBro-Birds/bikesharing/master/support_images/Trip_Duration_byGender.png)
This chart shows trip duration by gender.  Males by far take the most number of trips.

![Hours_Operations](https://raw.githubusercontent.com/JBro-Birds/bikesharing/master/support_images/Hours_Operations.png)
Bike-sharing demand is highest during traditional commuter times of 6am-10am and 4pm-8pm.

![Hours_Operations_Gender](https://raw.githubusercontent.com/JBro-Birds/bikesharing/master/support_images/Hours_Operations_Gender.png)
Bike-sharing demand by gender holds true to the overall population shown above with the highest demand between 6am-10am and 4pm-8pm.

![Number_Trips](https://raw.githubusercontent.com/JBro-Birds/bikesharing/master/support_images/Number_Trips.png)
This bar chart shows the number of trips by hour, reiterating the higher demand during traditional commuter times.  Demand remains steady late morning through mid-day while demand is very low late night and early morning as would be expected.

## Summary
Analyzing the Citi bike-sharing data set using Tableau is an effective means to build and tell the story of the NYC bike-sharing program.  The charts and visuals show key factors and drivers of the customer base, demand at specific time periods and geographic areas of higher demand.  Two other visualizations drawn from the given data set that would assist in making the pitch would be mapping the start and end location with line connectors in order to visually shape popular bike routes and mapping the start and end location by rider birth year to visually shape popular hubs by age.  Both of these types of analysis and visuals could help drive the types of businesses along more popular routes and hubs.

The NYC analysis and story can be used as a template to pitch a similar bike-sharing program in Des Moines, Iowa.  With Des Moines being a state capital city there is a central city core with high density of residents and workers.  In addition there are colleges, sports complexes and parks.  The demographics and geography of Des Moines should drive a high demand for bike-sharing.
