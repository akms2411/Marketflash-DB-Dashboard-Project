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

## Tableau Dashboard

![Dashboard](https://github.com/akms2411/Marketflash-DB-Dashboard-Project/blob/main/images/Dashboard%201.png)

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

**3. Total Likes 5.049.324 / Ratio: 10,02% / CPL: 4,93$**
   
   The campaigns generated an excellent response with 5,049,324 likes. The high number of likes shows a strong interaction of the target group 
   with the advertising content 
   The like rate of 10.02% results from the ratio of 5,049,324 likes to 50,404,108 views and means that for every 100 people who see an ad, 
   around 10 will give it a like. An engagement rate of over 10 percent is very high, as normal values are between 1 and 3 percent.
   The average cost of around 5 dollars per Like is acceptable in view of the high engagement rate.
   
**4. Total Clicks 2.606.521 / Rate: 5,17% / CPC: 9,55$**
   
   These more than 2.6 million clicks on the ads show the specific interest of users who responded to the advertising content. 
   The high number of clicks shows that the target group is interested in the product. The click-through rate of 5.17 percent 
   represents a high value. This CTR results from the ratio of 2,606,521 clicks to 50,404,108 views and means that for every 100 people who see an ad, around 5 click on it. 
   The cost per click of 9.55 dollars shows the investment for each individual click on the ads. 
     
**5. Converation Rate: AVG 1,012% / Conversion: 510 / CAC: 118 $**

   With a conversion rate of 1.01%, 510 conversions were generated. With customer acquisition costs of 118$ per new customer.
   
   - Before: 50,000,000 Views × 1.016% = 508,000 conversions
   - After: 50,000,000 Views × 0.912% = 456,000 conversions
   - Loss: 52,000 conversions less


## Project Summary

The analysis shows both strengths and potential for improvement. While the high engagement rates (like rate 10.02%, CTR 5.17%) 
indicate high-quality content and a well addressed target group, the low conversion rate of 1.01% shows a need for optimization in the conversion funnel.
The data cleansing and standardization carried out forms the foundation for data-driven decisions and efficient marketing strategies. 
The combination of technical improvements and effective processes ensures long-term data quality, which is directly reflected in improved campaign 
results and Return of Investment (ROI).
The dashboard provides a solid foundation for data-driven marketing decisions and enables continuous optimization of campaign performance.

## Recommendation

1. Data cleansing & Checking
   
   - Telephone numbers, standardization of formatting (international standards)
   - Gender, standardization of input formats (M/W/D)
   - Automatic assignment based on dates of birth to ensure consistent groupings for analyses
   - Validation of mandatory fields and data formats with automated error checking
   - Documentation of standards and processes with data quality checks and training for data entry
   
2. Decision support

   - Optimization of landing pages and the conversion process to increase the conversion rate
   - A/B testing of various call-to-actions and landing pages
   - In-depth analysis of the most successful campaigns to scale best practices
   - Review of target group segmentation for even more precise targeting

3. Early detection

   - Identifying best practices for future campaigns
   - Analysis of demographic-specific behavioural patterns
   - Optimization of campaign planning by target group
  
