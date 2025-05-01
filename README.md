# Capstone Case Study - Cyclistic

This exploratory analysis case study is towards Capstone project requirement for [Google Data Analytics Professional Certificate](https://www.coursera.org/professional-certificates/google-data-analytics) using R. It’s originally based on the case study "'Sophisticated, Clear, and Polished’: [Divvy and Data Visualization](https://artscience.blog/home/divvy-dataviz-case-study)" written by Kevin Hartman. The case study involves a fictional bike share company's data of its customer's trip details over a 12 month period (October 2023 - September 2024).

## Scenario

Cyclistic is a **fictional bike-share company** in Chicago, launched in 2016. The company has expanded to a fleet of over 5,800 bikes and nearly 700 docking stations across the city. Cyclistic attracts riders with flexible pricing options, offering single-ride passes, full-day passes, and annual memberships. However, financial insights show that annual members bring in more profit, prompting the marketing team to explore strategies to convert casual riders into annual members.

### Key Stakeholders:

-   Lily Moreno: Director of Marketing, responsible for marketing campaigns and member growth strategies.
-   Cyclistic Marketing Analytics Team: Data analysts who collect and analyze data to guide marketing efforts.
-   Cyclistic Executive Team: Approves or rejects marketing strategies and initiatives based on data-driven insights.

### Business Task

To support Cyclistic’s marketing goal of converting casual riders into annual members, the objective of this analysis is to determine how annual members and casual riders use Cyclistic bikes differently. By identifying key usage patterns and preferences, this analysis will help the marketing team design a data-driven strategy aimed at encouraging casual riders to commit to annual memberships.

#### Key Deliverable:

-   Business Task Statement: A clear and concise definition of the business problem and objectives.
-   Data Source Description: An outline of all data sources used in the analysis, including relevant details and any limitations.
-   Data Cleaning Documentation: A record of the data preparation process, detailing any cleaning, filtering, or transformations applied to ensure data quality.
-   Analysis Summary: A synthesis of findings on the differences in usage between casual riders and annual members.
-   Visualizations and Key Findings: Graphs, charts, and visuals that effectively present the analysis results and highlight key patterns and insights.
-   Top Three Recommendations: Actionable recommendations based on the analysis to help Cyclistic convert casual riders into members.

**Determine the credibility of the data:**

Data has been downloaded from [here](https://divvy-tripdata.s3.amazonaws.com/index.html). All trip data is in comma-delimited (.CSV) format with 13 columns.The time period in consideration is October 2023 - September 2024. Due to the fact that this is a case study using public data, we are going to assume the given dataset is original, comprehensive and it has been properly cited.

This data will allow us to analyze and compare trip duration, bike type usage, trip start and end times, and frequency of rides between casual riders and annual members, supporting the business task of identifying key differences in how these customer segments use Cyclistic bikes.

Note: The datasets have a different name because Cyclistic is a fictional company. The data has been made available by Motivate International Inc. under this [license](https://divvybikes.com/data-license-agreement). The data-privacy issues prohibits from using rider's personally identifiable information.

