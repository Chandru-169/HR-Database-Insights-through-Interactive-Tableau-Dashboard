<img width="1030" height="182" alt="image" src="https://github.com/user-attachments/assets/2b22bd91-e3fd-4329-84a5-2126db9681da" /><img width="1892" height="236" alt="image" src="https://github.com/user-attachments/assets/c24b0a65-fa49-40e8-b510-82d00da1532f" /><img width="546" height="73" alt="image" src="https://github.com/user-attachments/assets/5b7fc69c-4866-46bc-ac0d-723019008cee" /><img width="1759" height="185" alt="image" src="https://github.com/user-attachments/assets/82dc7b5d-bdec-48ac-a29f-83549fa660bf" /><img width="676" height="102" alt="image" src="https://github.com/user-attachments/assets/1c09a176-dcb5-47f7-98d6-9d6be54910ed" />## Dashboard Recording

https://github.com/user-attachments/assets/a30a5992-4381-485a-b7b5-edce542773e1


**Intrduction:** This HR dashboard project is designed to provide leadership and HR teams with a clear, data-driven view of the organization’s workforce. By integrating and visualizing key HR metrics—such as headcount, hiring and attrition trends, diversity, compensation, and performance—the dashboard enables informed decision-making, supports strategic workforce planning, and helps identify opportunities for improvement in talent management and organizational effectiveness.

## Power Point Presentation

[HR Database Insights.pptx](https://github.com/user-attachments/files/22642717/HR.Database.Insights.pptx)

## Table of Contents

1. Project objective
2. Build Data source and Calculated fields
3. Build Dynamic charts and interactive visuals
4. Dashboard designing
5. Key analytical & Data driven insights supporting the objectives
6. Recommendations

## Project Objective

1. Provide clear, actionable HR analytics for decision-making
2. Track hiring and termination trends by year, department, and demographics
3. Reduce employee turnover through data-driven insights
4. Optimize staffing across all departments
5. Promote diversity and inclusion in hiring and retention
6. Support talent management with detailed workforce breakdowns
7. Benchmark performance and education for better training and hiring
8. Enable geographic workforce planning by state and city
9. Monitor and improve employee tenure and lifecycle
10. Deliver concise HR dashboards for leadership reporting

## Build Data Source and Calculated fields

Imported dataset (csv) into Tableau
Created calculated Fields & Hierarchy: 
   1. Total & Percentage values for Hired, Active, Terminated employees
   2. Location to distinguish between HQ and branch
   3. Length of Hire to identify the employee duration
   4. Rank field based on total hired to utilize in various charts
   5. Employee status based on hire & term dates
   6. Age groups to utilize in heat maps
   7. Hierarchy for Department – Job Title & Location: State - City

## Build Dynamic charts & Interactive Visuals

**A) Overview Visual**

1. Active Employees, Hired, Terminated: Key metrics displayed as summary cards
2. Departments: Bar chart showing total hired and terminated employees by department (e.g., Operations, Sales, Customer Service, IT, Marketing, Finance, HR)
3. Location: Pie or bar chart showing employee distribution between HQ and Branch
4. Demographics: Pie chart for gender distribution (Male/Female)

**B) Department Analysis Visual**

1. Department Breakdown: Bar chart showing hires and terminations by department
2. Job Titles: Bar chart showing total hires by job title, with color coding for top roles
3. Departmental Trends: Trends of hires and terminations by department over time

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
