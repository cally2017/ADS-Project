# ADS-Project
<b>How do annual users and non-annual users use Divvy differently?</b>

My application is targeting to marketing teams of the Chicago bike sharing program. 
The marketing team want a have a campaign to attract casual users to become annual users, 
so the team want to know when the peak time is the non-annual users use Divvy bikes, 
and which location should the team reach out for their campaign. By using this application,
the team will know when and where to do their business effectively.
In this project, I am using the 2019 dataset to create a web application with useful visualizations. 
I choose the year of 2019 since it is the latest whole year that I can find the data. 
Metrics using for the visualizations are hours in a day, days in a week, months in a year, locations of Divvy bike using between annual members and non-annual members. 
I am going to apply filters such as annual users/non-annual users and from/to. Python/Flask is used for this project.

Dataset origin:
Divvy is a bike sharing system in Chicago. It provides about 700 bike stations with thousands of bikes to service riders. 
The data is tracked by Divvy system and released monthly for public use at https://ride.divvybikes.com/system-data. 
This data is for researchers or curious people to bring it to life.
Chicago bike station dataset: https://data.cityofchicago.org/Transportation/Divvy-Bicycle-Stations/bbyy-e7gq/data

The dataset has five following files.
-	Divvy_Trips_2019_Q1.csv: 365,069 records and 12 fields
-	Divvy_Trips_2019_Q2.csv: 1,108,163 records and 12 fields
-	Divvy_Trips_2019_Q3.csv: 1,640,718 records and 12 fields
-	Divvy_Trips_2019_Q1.csv: 107,054 records and 12 fields
-	Divvy_Bicycle_Stations.csv: 1419 records and 8 fields
After cleaning (manipulating, appending, and merging), I have a dataset with 3,818,004 records and 12 fields.
