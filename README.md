# CRM - Lead and Opportinity Dashboard
Dashboard Link - Customer Relationship Management
1)Oppurtunity Dashboard
2)Lead Dashboard

https://app.powerbi.com/groups/me/reports/129499e1-0aa0-4c21-9342-d5812a278c57?ctid=0abc8a22-567e-4918-b31c-0bdf83a88a27&pbi_source=linkShare


## Problem Statement

This dashboard helps the customers  understand their leads and Opportinity better. The two dashboard namely Lead and Opportinity helps to increase business sales by achieving KPI's and analyzing trends.



### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : Achieved KPI's for Opportinity dashboard like Win rate, Loss rate, Active Opportinity and Expected Amount by Opportinity type.
- Step 5 : For calculating these KPI's used DAX formulas  like 
Win rate = SUM('Opportunity Table'[Won - Copy])/COUNT('Opportunity Table'[Won - Copy])
Count of Won for False = 
CALCULATE(COUNTA('Opportunity Table'[Won]), 'Opportunity Table'[Won] IN { FALSE })
Count of Won for True = 
CALCULATE(COUNTA('Opportunity Table'[Won]), 'Opportunity Table'[Won] IN { TRUE })

Step 6 : Performed Trend analyzing these factors :
(a)Running Total Expected Vs Commit Forecast Amount over Time
(b) Running Total Active Vs Total Opportunities over Time
(c) Closed Won Vs Total Opportunities over Time
(d) Closed Won vs Total Closed over Time

- Step 7 : Achieved KPI's for Lead dashboard like Total Lead
 (a)Expected Amount from Converted Leads 
 (b)Conversion Rate 
 (c)Converted Accounts
 (d)Converted Opportunities
 (e) Lead By Source
 (f) Lead By industry

- Step 8 : In the report view, under the view tab, theme was selected.
- Step 9  : Visual filters (Slicers) were added.
- Step 9  : Two dashboards were created by Displaying all these KPI's and trends by using different visuals.

 - Step 18 : The report was then published to Power BI Service.
 
 

# Snapshot of Dashboards (Power BI Service)

![Opp dashboard](https://github.com/pavankumarbr2437/Test/assets/145674009/2c719d1b-bd57-46c8-a6cd-f1aa7fb5e09d)

![Lead dashboard](https://github.com/pavankumarbr2437/Test/assets/145674009/925b6f23-6b50-4b7f-a96d-f68fea7ef93f)

 
 
# Insights

Identified a 90% decrease in the count of Opportunity IDs over 7 years, starting to trend down as of 2023.
