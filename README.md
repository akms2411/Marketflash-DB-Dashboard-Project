# Marketflash-DB-Dashboard-Project

The project includes the analysis of an interactive dashboard to evaluate the marketing expenses of 24.89 million $, with 78 customers and 1000 campaigns over 13 months. The dashboard visualizes the most important key performance indicators (KPIs) - expenses, views, likes with correlated ratio, clicks with click-through rate as well as the conversion rate including CAC (customer acquisition cost), CPV (customer per view), CPL (customer per like) CPC (customer per click)
This enables detailed segmentation through filter options by date, channels, campaigns, gender and age groups. The goal is to analyze the performance metrics and identify data-based optimization recommendations for the cost-performance ratio.

## Project Description

1. Design of an ERD (Entity Relationship Diagram / crow's foot) - [ERD Pic](https://github.com/akms2411/Marketflash-DB-Dashboard-Project/blob/main/images/Marketflash%20ERD%20Diagramm.png)
2. Functional ER Diagram - [ER Pic](https://github.com/akms2411/Marketflash-DB-Dashboard-Project/blob/main/images/Marketflash%20ER%20Diagramm.png)
3. Database in SQL Light / Beekeeper (Create Tables; 5 entries in each tables; JOINS)
4. Google Spreadsheet File with Data Cleaning & Check
5. Create Dashboard Mockup - [Mockup](https://github.com/akms2411/Marketflash-DB-Dashboard-Project/blob/main/images/Mockup%20Dashboard.png)
6. Create Tableau Workbook 
7. Create Dashboard in Tableau - [Performance Dashboard - Marketflash 2023 (Public Link)](https://public.tableau.com/views/MiniProjectMarketflash/Dashboard1?:language=de-DE&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
9. Finalizing Presentation

## Database Design 

[Sreadsheet](https://github.com/akms2411/Marketflash-DB-Dashboard-Project/blob/main/data/Cleaned%20Marketflash_marketing_data_2023.xlsx)

## SQL Database Design

[Marketflash DB](https://github.com/akms2411/Marketflash-DB-Dashboard-Project/blob/main/sql_db/Mini%20Projekt.db)

## Tableau Workbook

[Performance Dashboard - Marketflash 2023](https://github.com/akms2411/Marketflash-DB-Dashboard-Project/blob/main/data/Mini%20Project%20Marketflash%20.twbx)

## KPI Findings

**1. Total Expense 24.893.187$ / CAC: 319.144$**
   
   The total expense of 24,893,187 dollars over a period of 13 months shows the total investment in customer acquisition. 
   The resulting Customer Acquisition Cost (CAC) of 319,143 dollars per new customer shows the significant investment required 
   to acquire a single customer. This figure puts the total spending in relation to the number of customers actually acquired.

     
**2. Total Views 50.404.108 / CPV: 0,49$**
   
   The reach of over 50 million contacts shows the significant potential of the target group approach and illustrates the 
   scaling of the marketing activities (ads, videos or advertised content)
   The CPV of 0.49 dollars reflects the efficiency of the expenses. This key figure shows that 49 cents were invested for each individual view of the ad.
   The combination of high reach and moderate costs per view indicates a well-scaled campaign.

     
**3. Total Clicks 2.606.521 / Ratio: 10.02%**
   
   The campaigns generated an excellent response with 5,049,324 likes. The high number of likes shows a strong interaction of the target group 
   with the advertising content 
   The like rate of 10.02% results from the ratio of 5,049,324 likes to 50,404,108 views and means that for every 100 people who see an ad, 
   around 10 will give it a like. An engagement rate of over 10 percent is very high, as normal values are between 1 and 3 percent.
   The average cost of around 5 dollars per Like is acceptable in view of the high engagement rate.

     
**4. Total Likes 5.049.324 / Ratio: 5.17 %**
   
   - Positive response: measurement of satisfaction and acceptance
   - Content quality: indicator of relevant and appealing content
     
**5. Converation Rate: 1,012 %**

   - Efficiency indicator: Shows how well views are converted into actions
   - Optimization potential: Identifies opportunities for improvement


## Project Summary


## Recommendation

The data cleansing and standardization carried out forms the foundation for data-driven decisions 
and efficient marketing strategies. The combination of technical improvements and sustainable processes 
ensures long-term data quality, which is directly reflected in improved campaign results and Return of Investment (ROI).

1. Data cleansing Google Spreadsheet
   
   - Telephone numbers, standardization of formatting (international standards)
   - Gender, standardization of input formats (M/W/D)
   - Automatic assignment based on dates of birth to ensure consistent groupings for analyses
   - Validation of mandatory fields and data formats with automated error checking
   - Documentation of standards and processes with data quality checks and training for data entry
   
2. Decision support

   - Precise target group segmentation through adjusted demographic data
   - Target group-specific content through standardized age groups and correct gender data
   - Optimized communication channels through streamlined telephone numbers
   - Increased response rates through targeted approach

3. Early detection

   - Identifying best practices for future campaigns
   - Analysis of demographic-specific behavioural patterns
   - Optimization of campaign planning by target group
