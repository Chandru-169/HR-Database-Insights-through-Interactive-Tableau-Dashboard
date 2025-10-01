## Dashboard Recording

https://github.com/user-attachments/assets/a30a5992-4381-485a-b7b5-edce542773e1


**Intrduction:** This project focuses building a comprehensive **Power BI dashboard** to analyze personal fitness data from Google Fit, aiming to provide actionable insights. It begins with importing and cleaning the data, followed by generating calculated columns and DAX measures to track key metrics like steps, distance, calories, and active minutes. Interactive visuals such as charts and slicers enable dynamic exploration of trends across days, weeks, and months. The dashboard includes detailed daily tracking, weekly and monthly trend analysis, and highlights goal achievement status. Analytical insights reveal performance patterns and correlations, while personalized suggestions help improve consistency and effectiveness in fitness routines.

## Power Point Presentation

[Personal Fitness Activity Performance Dashboard.pptx](https://github.com/user-attachments/files/20540112/Personal.Fitness.Activity.Performance.Dashboard.pptx)


## Table of Contents

1. Project Objective
2. Data Import and Preparation
3. Calculated Columns and Measures using DAX
4. Dynamic charts and Interactive Visuals
5. Fitness Activity Monthly / WeeklyTrend Analysis
6. Daily Fitness Activity Tracker
7. Analytical Insights from the Dashboard
8. Fitness Improvement Suggestions


## Project Objective

1. To consolidate and visualize personal fitness data from Google Fit to gain actionable insights into daily, weekly, and monthly activity patterns
2. To track and evaluate key health metrics such as total steps, distance covered, calories burned, and active minutes over time
3. To monitor goal achievement by comparing actual performance against predefined fitness targets (e.g., distance, steps, calories, minutes)
4. To identify trends and gaps in physical activity across different time periods (weekdays vs weekends, months, years)
5. To enable dynamic exploration of fitness performance using interactive filters and parameter based metric selectors in Power BI
6. To support data driven decision making for improving consistency, intensity, and effectiveness of fitness routines
7. To encourage behavioral change by highlighting high and low performance periods and suggesting areas for improvement


## Data Import and Preparation

**Data Preparation &Transformation Steps are:**

1. Imported Google Fit data (.csv) into Power BI
2. Cleaned and structured the data to extract: Date, Day Name, Week, Month,Year
3. Created **calculated Columns using DAX:**
   •  Target achievement flags: Distance, Move Minutes, Calories, Steps ( “Target met” vs “Target not met”)
   •  Year-Month combination
   •  Weekend Flag for weekday/weekend analysis
4. Created **Measures / Aggregations using DAX:**
   •  Total values for Calories, Distance (km), Steps, Minutes, Hours
   •  Derived percentages of target achievement for each metric


## Dynamic charts, Interactive Visuals and Fitness Activity Trend Analysis

**A) Target Achievement Overview**

1. **Donut chart**: It shows the number of days in which Target is met Vs Target not met for each metric: Distance covered, Move Minutes, Calories burned, Steps covered based on dynamic selection using parameters created
2. **Column Chart**: It helps to conduct comparison analysis at monthly level over the selected years for each metric. Weekend flag has been utilized as a legend to distinguish the values between weekday Vs weekend
3. **Card**: Added the Card (new) visual to display each fitness activity values scored along with target achievement
4. **Slicers**: Year, Metric Selector, Weekend Flag

**B) Daily and Monthly Fitness Activity**

1. **Scatter Plot**: It shows the day wise total distance covered / calories burned / Minutes active / Hours active / Steps covered allowing users to study the selected fitness activity at day level for a given year-month combo
2. **Tree Map**: It shows the month wise total distance / calories / Minutes / Hours / Steps which helps to easily visualize which month observed the highest or lowest fitness activity
3. Both visuals are linked to common slicers and metric parameter allowing **dynamic changes to reflect simultaneously**

**C) Weekly Trend Analysis**

1. **Line chart**: It shows the weekly trend of fitness activity for each metric: Distance covered, Move Minutes, Calories burned, Steps covered in each week for any selected year
2. **Dual Metric Selector**: Allows toggling between fitness activity indicators: Calories, Distance, Hours, Minutes, Steps (E.g. Total Distance Vs Total Calories; Total Steps Vs Total Distance)
3. **Slicers**: Year, Metric Selector
4. This visual is created in such a way that “single line chart” is used and with the advantage of dual metric selector user can analyze the relation between each fitness activity over the weeks instead of looking at multiple line charts

**D) Daily Fitness Activity Tracker**

1. **Table**: Daily breakdown of Steps, Distance, Minutes, Hours, Calories. Also, Target status for each fitness activity is included
2. **Summary KPIs**: Distance Target %, Minutes Target %, Steps Target %, Calories Target %. This helps to understand the target achieved for each activity for the selected year-month combination


## Summary of Analytical Insights from the Dashboard

![image](https://github.com/user-attachments/assets/d8465727-33bd-4ab1-a00d-e41efff64741)


## Fitness Improvement Suggestions

  **1. Improve Target Consistency:** Focus on Distance and Steps targets by setting daily micro goals
  
  **2. Leverage High Performance Months:** Analyze what worked in May–June and replicate those habits in lower-performing months
  
  **3. Optimize Weekday Activity:** Introduce short, high effort sessions during weekdays to close target gaps
  
  **4. Use Weekly Reviews:** Monitor weekly trends to adjust intensity and duration

  **5. Set SMART Goals:** Walk 3 km daily, Cover 4000 Steps daily, Burn 5000 Cal weekly


## Appendix: Dashboard Screenshots

  ![image](https://github.com/user-attachments/assets/9392fdd6-14c8-4e58-a33b-65615e7c9d00)

![image](https://github.com/user-attachments/assets/20ea86d5-74db-461c-bb5e-b759460dc584)
