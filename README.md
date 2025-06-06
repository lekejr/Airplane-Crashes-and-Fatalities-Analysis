# Aviation Incident Analysis Report

## Table of Contents
1. [Introduction](introduction)  
2. [Objective](objective)
3. [Dataset Overview](dataset-overview)
4. [Methodology](methodology)
5. [Research Questions](research-questions)
6. [Processes](processes)
7. [Insights](insights)
8. [Key Findings](key-findings)
9. [Conclusion](conclusion)

## Introduction
Air travel is one of the most efficient modes of transportation but it is not immune to accidents. While rare airplane crashes often result in significant fatalities and property loss. This analysis project investigates historical airplane crash data to uncover trends patterns and insights that can support safety planning and aviation policy development.

![Screenshot (487)](https://github.com/user-attachments/assets/dfb87fc6-ffba-4283-8e26-d2116d1cc1d2)

## Objective
The primary goal of this dashboard is to analyze airplane crashes and their fatal outcomes by evaluating the aircraft types involved, the operating carriers, and crash locations. The dashboard aims to answer specific questions around crash frequency, fatality distribution, and safety trends across decades.

## Dataset Overview
The dataset used contains records of airplane crashes and incidents from various time periods. Each record provides information on:
- Total number of people onboard  
- Number of fatalities  
- Type of aircraft  
- Airline operator  
- Geographic location of crash  
- Date of occurrence  
- Maximum fatalities in a single incident  

The dataset offers a wide view into both commercial and military aviation history.

## Methodology
This analysis was performed using Power BI with the following steps:
- Data cleaning and validation to correct errors in aircraft names and operator data  
- Creation of calculated columns including average and maximum fatalities  
- Application of DAX functions for aggregations and metrics  
- Development of interactive visuals such as bar charts pie charts and map visualizations  
- Implementation of filters to explore data by aircraft type and operator  

## Research Questions
1. Which aircraft types are associated with the most fatalities  
2. Which airline operators have recorded the most crashes  
3. Which locations have the highest fatality counts  
4. How have fatalities changed over time  
5. What is the most deadly incident in the dataset  
6. How do crash rates vary by operator and aircraft type  

## Processes
- Imported the dataset into Power BI for analysis  
- Cleaned and standardized the dataset by correcting typos and inconsistent naming formats  
- Transformed raw data by creating calculated measures including total onboard and average fatalities  
- Visualized data using a combination of pie charts bar graphs line charts and geospatial maps  
- Enabled interactive filtering to drill down by aircraft type or airline operator  

## Insights
- The **Douglas DC-3** aircraft recorded the highest number of fatalities across all types  
- **Aeroflot** and **Military** operators are among the top contributors to total fatal crashes  
- Locations such as **Tenerife** and **Mt. Osut** recorded significantly higher fatalities than other regions  
- The time series shows a higher frequency of deadly crashes between 1970 and 1990  
- The highest number of fatalities in a single incident is **583**  
- Most crashes involved aircraft types used in both commercial and military contexts  

## Key Findings
- Total passengers onboard across all crashes: **144.55K**  
- Total fatalities: **105.48K**  
- Average fatalities per crash: **20.02**  
- Highest fatalities in one crash: **583**  
- Total aircraft types analyzed: **2.409K**  
- Total fatal crash locations: **4.304K**  
- Total operator entries in the dataset: **2.470K**  

## Conclusion
This dashboard highlights critical trends in aviation safety using historical crash and fatality data. Key factors contributing to fatalities include aircraft type, operator reliability, and geographic patterns. With the ability to interactively explore the data users can draw informed insights into aviation risks and develop strategies to enhance safety standards. The analysis serves as a valuable tool for researchers aviation regulators and industry stakeholders.
