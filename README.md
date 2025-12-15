🚔 CrimeScope LA – Los Angeles Crime Analysis Dashboard
📌 Overview

CrimeScope LA is an interactive Power BI dashboard built using the Los Angeles Crime Data from 2020 to Present.
The project transforms large-scale public safety data into meaningful insights by analyzing crime trends, hotspots, demographics, and temporal patterns through dynamic and visually intuitive dashboards.

This project demonstrates the practical application of Business Intelligence, data modeling, and data visualization techniques in the domain of urban crime analytics.

🎯 Objectives

->Analyze crime trends in Los Angeles from 2020 onwards

->Identify high-crime areas and geographical hotspots

->Examine temporal crime patterns (year, month, day, time of day)

->Study crime distribution by category, weapon type, and premises

->Analyze victim demographics (age group, gender, descent)

->Build an interactive, user-friendly Power BI dashboard

🗂️ Dataset

Source: Los Angeles Open Data Portal

Dataset Name: Crime Data from 2020 to Present

Link:
https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8/about_data

The dataset includes information on crime type, date and time, location, victim demographics, weapon details, and case status.

🛠️ Tools & Technologies

->Microsoft Power BI

->Power Query (Data Cleaning & Transformation)

->DAX (Measures & Calculations)

->Star Schema Data Modeling

->Geospatial Mapping

🧱 Data Modeling

Implemented a star schema with a central Fact table

Created dimension tables for:

->Area

->Crime

->Location

->Premises

->Weapon

->Status

->Time of Day

->Age Category

->Calendar (Date Table)

->Established one-to-many relationships for efficient filtering and performance

->Used a separate Measures table to organize DAX calculations

📊 Dashboard Pages

->Overview Page: High-level KPIs and crime summary

->Summary Page: Crime trends, demographic insights, category analysis

->Map Page: Area-wise crime distribution and hotspot visualization

->Navigation buttons allow seamless movement between pages.

📈 Key Insights

->Crime peaked during the post-pandemic period (2021–2022)

->Certain areas consistently show higher crime concentration

->Property-related crimes and assaults are most frequent

->Crimes occur more often during evening and night hours

->Young and middle-aged adults form the majority of victims

🚀 Future Scope

->Integration of real-time or live data refresh

->Predictive crime forecasting using machine learning

->Integration with population and socio-economic datasets

->Advanced geospatial clustering and heatmaps

->Deployment via Power BI Service for wider access

<img width="1378" height="782" alt="Screenshot 2025-12-15 191733" src="https://github.com/user-attachments/assets/d4c92762-d76f-45d9-9dfb-3f5ce729dfb4" />
<img width="1368" height="771" alt="Screenshot 2025-12-15 191740" src="https://github.com/user-attachments/assets/7bc622b1-178c-4a77-a35f-382eee0bd7ac" />
<img width="1376" height="762" alt="Screenshot 2025-12-15 191745" src="https://github.com/user-attachments/assets/20b43ad5-0d8f-4053-883c-0a917687a8f3" />
<img width="1371" height="780" alt="Screenshot 2025-12-15 191753" src="https://github.com/user-attachments/assets/72a7e6dc-b07a-44c8-bfa4-248b0f46b029" />

