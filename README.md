# LITA-CAPSTONE-SALESDATA
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
  In the initial stageof Data cleaning and preparation,the following actions were performed
  
    1. Data loading and Inspection
    
    2. handling missing variables
    
    3. Removing duplicates
    
    4. Data cleaning and formatting

### Explanatory Data Analysis
      Explanatory Data Analysis involvedd exploring the data to answer some questions such as:

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

--- Total Revenue by Region---


``` =SUMIF(D2:D50001,D49981,H2:H50001)  West =  1,512,500.00

``` =SUMIF(D2:D50001,D49983,H2:H50001)  South =  4,675,000.00

``` =SUMIF(D2:D50001,D49984,H2:H50001)  East =  2,450,000.00

``` =SUMIF(D2:D50001,D49982,H2:H50001)  North =  1,950,000.00


--- Average Sales per product---

``` =AVERAGEIF(C2:C50001,C49981,H2:H50001) 158.75- Hat

``` =AVERAGEIF(C2:C50001,C49982,H2:H50001) 326.6666667- Shirt

``` =AVERAGEIF(C2:C50001,C49983,H2:H50001) 308.75- Shoes

``` =AVERAGEIF(C2:C50001,C49985,H2:H50001) 121.6666667- Socks

``` =AVERAGEIF(C2:C50001,C49986,H2:H50001) 140- Gloves

``` =AVERAGEIF(C2:C50001,C49986,H2:H50001) 140- Jackets



##### SQL Queries to extract key insights
      
![1salesdata](https://github.com/user-attachments/assets/f9c41a98-7de7-4c5c-859f-5dec8bdfc8b1).

![2salesdata](https://github.com/user-attachments/assets/ccbf0825-c46a-4be4-a52c-9ccfb2f9c85e)

![3salesdata](https://github.com/user-attachments/assets/ecc3a9eb-9f81-4a98-9169-e80fde6f02d7)

![4salesdata](https://github.com/user-attachments/assets/67f6b8ae-90b3-47af-95c8-596b3ce4b5c0)

![5salesdata](https://github.com/user-attachments/assets/1a20492d-1fe3-4457-92df-55f4a5e0ea73)

![6salesdata](https://github.com/user-attachments/assets/900d02cc-06ac-4195-971e-968a75dc759b)

![7salesdata](https://github.com/user-attachments/assets/8e6e32a8-595d-4da7-a56d-8d28883563a3)

![8salesdata](https://github.com/user-attachments/assets/2ae2d3b7-702c-49c5-ac14-2f955282e33c)
