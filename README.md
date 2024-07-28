# Project Overview: San Francisco Bikeshare Data Analysis Using BigQuery

## Project Objective

The primary objective of this project was to analyze the San Francisco Bikeshare data available in the BigQuery public dataset. By leveraging SQL queries, I aimed to gain insights into the usage patterns, station distribution, and demographic trends within the bikeshare system. The analysis helps understand key aspects such as the distribution of stations across different regions, the frequency of trips based on subscriber type, and gender-based trip patterns.

## Data Source
The data for this project was sourced from the BigQuery public dataset, specifically the bigquery-public-data.san_francisco_bikeshare dataset. This dataset includes detailed information about bikeshare stations, trips, and regions within the San Francisco area.

## Key Analyses and Findings

1. Station Distribution by Region

<img width="682" alt="Screenshot 2024-07-28 at 10 11 35 PM" src="https://github.com/user-attachments/assets/26ebd589-4c07-4061-a695-8d516401edca">

- This query joins the station information with region data to identify the number of bikeshare stations in each region.
- The results highlight the regions with the highest and lowest number of bikeshare stations, providing insights into the distribution and accessibility of the bikeshare system across different regions.

2. Trip Count by Subscriber Type

<img width="677" alt="Screenshot 2024-07-28 at 10 13 28 PM" src="https://github.com/user-attachments/assets/1934268e-01e6-477c-a028-1581aa4c1be7">

- This query aggregates the number of trips based on the subscriber type (e.g., regular subscribers vs. casual riders).
- The analysis reveals which type of users contribute most to the overall trip count, which can inform marketing and service strategies for the bikeshare program.

3. Most Popular Start Stations

<img width="674" alt="Screenshot 2024-07-28 at 10 15 25 PM" src="https://github.com/user-attachments/assets/8abf1733-0962-45cd-b717-4a3d6974c027">

- This query identifies the stations where the highest number of trips start.
- Understanding the most popular start stations can help in optimizing station placement and ensuring bikes are available where demand is highest.

4. Gender-Based Trip Patterns

<img width="678" alt="Screenshot 2024-07-28 at 10 17 12 PM" src="https://github.com/user-attachments/assets/02352222-9a6f-43e9-8ba7-bbf55578bb57">

- This query analyzes the number of trips started and ended by male and female users from each station.
- The results provide insights into gender-based usage patterns, which can help in tailoring services and improving gender inclusivity in the bikeshare program.

## Conclusion

Through this project, I successfully utilized BigQuery and SQL to perform a comprehensive analysis of the San Francisco Bikeshare data. The insights derived from the data provide valuable information on station distribution, user demographics, and trip patterns. These findings can be instrumental for stakeholders in making data-driven decisions to enhance the bikeshare program’s efficiency, accessibility, and user satisfaction.











