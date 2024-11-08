# INCUBATOR-HUB-CAPSTONE-CUSTOMER-DATA
##### A Concise Report of the Analysis of Incubator Hub's Capstone Project Customer Data

## ANALYSIS OF INCUBATOR HUB'S CAPSTONE CUSTOMER DATA

[PROJECT OVERVIEW](project_overview)

[DATA SOURCES](data_sources)

[Data Cleaning and Preparations](Data_Cleaning_and_Preparations)

[DATA EXPLORATORY](data_exploratory)

[DATA ANALYSIS](data_analysis)

[EXCEL REPORTS (PIVOT TABLES AND PIVOT CHARTS)](excel_reports)

[ANALYSIS ON SQL](analysis_on_SQL)

[SQL REPORTS](sql_reports)

[ANALYSIS ON POWER BI](analysis_on_power_bi)

[POWER BI VISUALS](power_bi_visuals)

[INFERENCE](inference)

[CONCLUSION](conclusion)

[RECOMENDATION](recomendation)


## PROJECT OVERVIEW
This Project deals with the analysis of the subscription trend of the three major subscription type of Incubator Hub's Capstone Project. It pays cognisance to the performance of each subscription per Region and the rate of cancellation of subscription by customers.

### DATA SOURCES
- Microsoft Excel [Download Here](https://www.microsoft.com)
- The Incubator Hub Capstone Customer Data Set
- 
### Data Cleaning and Preparations

##### Microsoft Excel was used to perform the following
- for Data Cleaning; in this phase, duplicates were removed, and new columns were added, also there are some data types that needed to be changed, these was also part of the task performed in this section.
- for Analysis; after ensuring the data was clean, a good number of analysis was carried out on the clean data. some of the formulas used with be updated in this report.
- Visualization; the pivot table and pivot chart is a very beautiful visualization tool in excel, this was used to ptesent the summary of the result.

    
##### SQL - (Structured Query Language)

This model was used to write queries for all necessary reports needed, but before writing the query, I imported the clean data from excel into my SQL work station. 
Here are the steps involved in importing the data.
- The excel 'xlsl' file was converted to 'csv'(comma delimited) file
- The I opened my SQL work station
- I used an existing data base to import the data
- I clicked and right clicked on the database
- I proceeded to 'task', then to 'import flat file', picked my file from the appropriate location, changed table name where necessary and clicked next.
- I changed the data types to the compatible ones for SQL
- Then the data was uploaded.
  
##### Power BI

The data used on excel was also imported to power Bi through the following steps
- Go to 'Get Data'
- click excel wook book
- pick your file
- click to preview
- then transform data

### DATA EXPLORATORY
  During the analysis of the customer data , the three analysis tools were used (excel, SQL and Power BI), thorough data exploration was done, some new columns were added in excel, for example the 'Subscription Duration' column, some other columns were added in SQL (Cancelled subscription column and Active Subscription Column) with the help of sql quesries and also in power BI, I added some conditional column and measures.
  
  The pivot table and pivot charts were used to summerise the report in excel.
   
  Differen types of visuals were generated on Power BI that gave an overview of the sales pattern as it was on excel. 
  
  Power BI visuals also provided a detailed trend in the subscription pattern in relation to the differenr subscrtion types in the different regions.
  
### DATA ANALYSIS  

##### On Excel, the following analysis were performed both with excel metrics, pivot tables and pivot charts

- To calculate the Subscription Duration
```
=F2-E2
```
- Total Revenue
```
=SUM(H2:H33788)
```
- Average Revenue
```
=AVERAGE(H2:H33788)
```
- Average Subscription Duration
```
=AVERAGE(I2:I33788)
```
- Total Revenue per Region
```
=SUMIF(C2:C33788,"Region",H2:H33788)
```
- Average Subscription per Region
```
=AVERAGEIF(C2:C33788,"EAST",H2:H33788)
```
- Total Revenue by Subscription Type
```
=SUMIF(D2:D33788,"subscriptiontype",H2:H33788)
```
- Average Revenue by Subscription Type
```
=AVERAGEIF(D2:D33788,"subscriptiontype",H2:H33788)
```
- Count of each Subscription Type
```
=COUNTIF(D2:D33788,"subscriptiontype")
```
##### Below are the pivot tables and pivot charts generated on Excel
![Screenshot 2024-11-08 205436](https://github.com/user-attachments/assets/4d5bbd35-c453-4d85-b9cd-25fa3378891e)

![Screenshot 2024-11-08 205444](https://github.com/user-attachments/assets/c653f108-cf02-4df2-a68d-51795fc30e76)

![Screenshot 2024-11-08 205305](https://github.com/user-attachments/assets/42a3e74b-1b97-4bc9-8191-1ae5fe06eb3d)

![Screenshot 2024-11-08 205103](https://github.com/user-attachments/assets/0432b4a2-dafb-49de-9bef-19cd66557315)

![Screenshot 2024-11-08 205112](https://github.com/user-attachments/assets/e703b521-ca33-4f37-8be4-ed77a81b69d4)

![Screenshot 2024-11-08 205119](https://github.com/user-attachments/assets/c10e9710-b5e6-48d0-91d9-f55269acba18)

![Screenshot 2024-11-08 205127](https://github.com/user-attachments/assets/91e36d50-f2ad-4d36-8f28-502187460a8d)

![Screenshot 2024-11-08 205153](https://github.com/user-attachments/assets/9b182e99-3024-4443-870b-491fd2712265)

![Screenshot 2024-11-08 205200](https://github.com/user-attachments/assets/c426f866-404d-43fa-a5ae-837514c451d3)

![Screenshot 2024-11-08 205208](https://github.com/user-attachments/assets/1a1a8e26-00b9-455c-b589-bb2a161abbec)

![Screenshot 2024-11-08 205321](https://github.com/user-attachments/assets/2aa82ce2-a244-41fe-a0f6-810ba1461a83)

![Screenshot 2024-11-08 205331](https://github.com/user-attachments/assets/e40d73bb-56da-413a-8bea-3743adb92dc9)

![Screenshot 2024-11-08 205352](https://github.com/user-attachments/assets/3c86bc50-b684-47bc-9533-4697427d1c09)

![Screenshot 2024-11-08 205408](https://github.com/user-attachments/assets/956ff77c-5767-417c-a5b6-63068315cf48)












