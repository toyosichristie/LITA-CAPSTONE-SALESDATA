# LITA-CAPSTONE-SALESDATA
```
## Project Title- Sales Performance Analysis for a Retail Store
### Project Overview
  In this project, the task is to analyse the Sales performance of a retail store. To explore the datasetand uncover key insights such as top-selling products, regional performance, and monthly sales trends for an optimum decision making.

### Data Sources
  The primary source of data is Salesdata. xlsx. This is a data given as capstone project in partial fulfillment of A 3-month Data Analysis training with Ladies in Tech Africa (LITA) the Incubator Hub.

### Tools Used
- Microsoft Excel [Download Here](https://www.microsoft.com)
  
    1. Data cleaning
  
    2. Analysis
  
    3. Visualisation
       
- SQL- Structured Querying Language for Querying of Data.
- Power BI for Data Visualisation.
- GitHub for Portfolio Building.

### Data Cleaning and Preparation
  In the initial stage of Data cleaning and preparation,the following actions were performed:
  
    1. Data loading and Inspection
    
    2. Handling missing variables
    
    3. Removing duplicates
    
    4. Data cleaning and formatting

### Explanatory Data Analysis
      Explanatory Data Analysis involvedd exploring the data to answer questions such as:

- Summarize total sales by product, region and month using pivot tables.
- Use Excel formulas to calculate Metrics such as average sales per product and total revenue by region.
- Write SQL queries to extract key insights.
- Create a Power BI dashboard that visualises the insights found in Excel and SQL.

 ### Data Analysis
  Here the line of codes, functions, queries, DAX expressions used during the analysis  

--- Pivot Tables Visualisation ---


  ![image](https://github.com/user-attachments/assets/8fb64504-0fda-481a-95a9-5465710dc1cd)

![image](https://github.com/user-attachments/assets/9e930c7d-d7af-42c1-ad7b-f1e95e4e9bb5)

![image](https://github.com/user-attachments/assets/15a490a3-0198-43c6-ab7b-e201bb65dea8)

![image](https://github.com/user-attachments/assets/2a36f236-a0db-42a9-8da2-36820d12fc4b)

![image](https://github.com/user-attachments/assets/e35249ba-77f8-4d84-9270-97409a605f84)

##### Metrics using Excel Formulas


#### SQL queries to extract key insights

```SELECT PRODUCT,SUM(Sales)
AS TotalSales
FROM Salesdata
GROUP BY Product
```

***Total Sales for each product category***
![1salesdata](https://github.com/user-attachments/assets/33e23a07-13de-4932-b65f-1b127edb4823)


***Number of Sales transactions in each Region***

![2salesdata](https://github.com/user-attachments/assets/c190fdd4-63b9-46d7-96bf-174dd88611e4)


***Highest selling product by Total Sales value***

![3salesdata](https://github.com/user-attachments/assets/7a2fcd12-afbb-4025-96ad-c60e7a06e877)


***Total Revenue per Product***

![4salesdata](https://github.com/user-attachments/assets/d41c6848-d919-4b30-beb7-00f1f925e991)


***Monthly Sales totals for the current year***

![5salesdata](https://github.com/user-attachments/assets/feef1fb2-f24d-4cfb-8733-0da69e92ce85)


***Top 5 customers by total purchase amount***

![6salesdata](https://github.com/user-attachments/assets/b415f0d1-0115-40c0-962e-deb7732430a3)


***Percentage of total sales contributed by each Region***

![7salesdata](https://github.com/user-attachments/assets/14f0a45c-7b96-494a-823f-dd4b179b860c)


***Products with no Sales in the last quater***
![8salesdata](https://github.com/user-attachments/assets/86d8b6fb-df9a-4501-a63e-289bf6703c6a)





