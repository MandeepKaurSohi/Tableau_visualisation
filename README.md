# Citi Bike Data Analysis: Tableau Challenge
## Overview
Congratulations on your new job as the lead analyst for the New York Citi Bike program! This Tableau project demonstrates my analysis of the Citi Bike trip history logs, focusing on uncovering key insights and presenting them through engaging visualizations.

As part of the Citi Bike program, which is the largest bike-sharing initiative in the U.S., this analysis aims to support city officials by providing actionable insights into bike utilization trends and opportunities for program improvement.

## Data Sources
This analysis uses Citi Bike trip data from September, October, and November 2024. The data includes information on ride duration, start and end stations, user types, and geographic information (latitude and longitude).

## Dataset Details
File Names:
recent_trends_citibike_dataset.csv
Contains trip data for September, October, and November 2024.
Fields in the Dataset:
Ride ID: Unique identifier for each trip.
Rideable Type: Type of bike (e.g., electric, classic).
Started At and Ended At: Timestamps of the trip.
Start Station and End Station: Station names and IDs.
Latitude and Longitude: Geographic coordinates for stations.
Member Casual: Rider type (member or casual).
# Analysis Goals
The primary objective was to create interactive and visually appealing dashboards in Tableau to address the following:

## Explore Ridership Trends:

Monthly growth rates and usage patterns.
Proportions of casual users vs. annual members.
## Identify Popular and Underutilized Stations:

Stations with the highest and lowest activity.
Recommendations to improve underutilized stations.
## Analyze Temporal Trends:

Peak hours for weekdays vs. weekends.
Daytime vs. nighttime usage patterns.
## Map Station Popularity:

Highlight station popularity using geographic markers and zip codes.
Create a dynamic map to show how station popularity changes by month.
# Visualizations and Dashboards
The project consists of three dashboards integrated into a Tableau Story:

## Dashboard 1: Monthly Trends
Visualizations:
Monthly Ridership Growth.
User Proportions (Casual vs. Member).
Top 10 Starting Stations.
Insights:
Ridership peaks in September, driven by casual users during favorable weather.
Members show consistent usage patterns across all months.

![Monthly Trends](https://github.com/MandeepKaurSohi/Tableau_visualisation/blob/main/Dashboards/Monthly_trends.png)


## Dashboard 2: Station and User Insights
Visualizations:
Station Popularity Map.
Least Utilized Stations (Bar Chart).
Peak Hour Heatmap (Day of Week vs. Hour of Day).
Insights:
Midtown Manhattan and Central Park stations are the most popular.
Stations in northern Manhattan show the least activity, indicating underutilization.
Peak hours occur during weekday mornings and evenings, aligning with commuter behavior.

![Station and User Insights](https://github.com/MandeepKaurSohi/Tableau_visualisation/blob/main/Dashboards/Station_User_Insights.png)


## Dashboard 3: Temporal and Spatial Trends
Visualizations:
Day vs. Night Station Usage (Map).
Popularity Over Time (Table).
Peak Hours for Day/Night (Bar Graph).
Insights:
Daytime trips dominate across most stations, with nighttime trips concentrated in entertainment districts.
Usage patterns shift seasonally, with activity declining in November.

![Temporal and Spatial Trends](https://github.com/MandeepKaurSohi/Tableau_visualisation/blob/main/Dashboards/Temporal_Spatial_trends.png)


# Recommendations
Expand Capacity at Popular Stations:
Add more bikes and docking spaces in high-demand areas (e.g., Midtown Manhattan).
Address Underutilized Stations:
Relocate or promote underutilized stations to improve network efficiency.
Launch promotional campaigns to attract users in low-demand areas.
Enhance Operations for Peak Hours:
Increase bike availability during weekday rush hours.
Allocate resources for weekend leisure riders.
Optimize for Seasonal Usage:
Focus on casual users during warmer months (e.g., September and October).
Reduce operational efforts for casual riders during colder months.
# How to Access the Tableau Public Story
Link to Tableau Public:
Access the Tableau Story here: [https://public.tableau.com/app/profile/mandeep.sohi2322/viz/citibike_analysis_twbx/Storytelling?publish=yes].
Features:
Interactive dashboards and visualizations.
Dynamic filters for month, user type, and station popularity.
# How to Replicate the Analysis
## Tools Used:
Tableau Desktop Public Edition: For visualizations and dashboards.
Python (pandas): For data cleaning and preprocessing.
## Steps:
Data Cleaning:
Removed missing values and duplicates.
Converted date and time fields to appropriate formats.
Calculated new fields (e.g., trip duration, day of the week, hour of the day).
Visualization:
Created interactive visualizations in Tableau, using calculated fields and filters for insights.
Story Creation:
Combined dashboards into a cohesive Tableau Story with descriptions and captions.
# Acknowledgments
Special thanks to the New York Citi Bike program for providing publicly available data for this analysis. This project is part of a learning exercise to enhance data analysis and visualization skills using Tableau.


