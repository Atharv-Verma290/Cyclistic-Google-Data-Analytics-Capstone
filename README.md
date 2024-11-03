# Cyclistic-Google-Data-Analytics-Capstone

## Cyclistic Bike-Share Case Study

This project is a case study analyzing bike usage patterns to inform Cyclistic’s marketing strategy. The study follows a structured data analysis process to understand how casual riders and annual members use Cyclistic bikes differently, aiming to convert casual riders into annual members.

## Project Summary

Cyclistic, a fictional bike-share company based in Chicago, has a strategic goal to maximize annual memberships. This case study was conducted to help Cyclistic's marketing team develop a targeted campaign to encourage casual riders to become annual members. The analysis covers the following steps:

1. **Ask**: Define the business task, focusing on understanding bike usage differences between casual riders and members.
2. **Prepare**: Gather and prepare Cyclistic's historical trip data, ensuring data integrity and handling privacy concerns.
3. **Process**: Clean and transform the data, including handling inconsistencies and calculating metrics like ride duration.
4. **Analyze**: Explore trends and patterns in bike usage by user type, performing descriptive analysis to identify key insights.
5. **Share**: Develop data visualizations and a report to communicate findings to the executive team.
6. **Act**: Present actionable recommendations based on data insights to support marketing strategies aimed at increasing memberships.

## Deliverables

- A clear statement of the business task
- Description of data sources and data cleaning documentation
- Summary of findings and visualizations
- Three key recommendations for converting casual riders into members

## Tools

This project utilized:
- **SQL**: Data cleaning and transformation
- **R/RStudio**: Data aggregation and analysis
- **Data Visualization tools**: PowerPoint and R for final visualizations

## Data Source
The dataset can be accessed from [Divvy Trip Data](https://divvy-tripdata.s3.amazonaws.com/index.html). This dataset includes trip details such as trip duration, start and end times, station locations, and user membership types. 

## Data Processing
SQL is used to process the data.
1. The data is combined for each month into a single year table.
2. Irrelevent columns like start and end station information, ride id are dropped.
3. Timestamp data is split into date, time, month, hour, time of day, season for analysis.
4. Trip duration is calculated from start and end time.

## Analysis and Insights
The data analysis and visualization is done using R and RStudio in the [Cyclistic_2023_data_viz.Rmd](https://github.com/Atharv-Verma290/Cyclistic-Google-Data-Analytics-Capstone/blob/main/Cyclistic_2023_data_viz.Rmd) 

## Recommendations

Three recommendations and visualizations based on this analysis are included in the [report](https://github.com/Atharv-Verma290/Cyclistic-Google-Data-Analytics-Capstone/blob/main/cyclistic%202023%20case%20study%20report.pptx) to guide Cyclistic's marketing strategy.

---

This project demonstrates practical data analysis skills, focusing on data preparation, analysis, and effective communication of insights. It serves as a portfolio case study showcasing an end-to-end data-driven approach to business problem-solving.
