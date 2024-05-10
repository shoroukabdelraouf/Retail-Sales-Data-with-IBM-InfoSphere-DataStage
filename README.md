# Retail-Sales-Data-with-IBM-InfoSphere-DataStage
## Project Description:  
This project showcases the development of a star-schema-based sales analysis data warehouse for a fictitious national department store using IBM InfoSphere DataStage. The aim is to demonstrate a typical data warehousing flow, including modeling, ETL processes, and the creation of data marts to meet specific business needs. 
    
- Industry Scenario: Retail
- Dimensions: Customer, Store, Product
- Fact Table: Transactions

  ## Project Description:   
 - Modeling Process and Data Translation:  
       State the modeling process.  
       Translate logical data model to physical data model.    
       Loading samples into files (attached files provided).  
- ETL Solution Development:  
       Utilize ETL tool to create solution for loading data into files or databases.  
       Read source data and perform transformations to meet business needs.  
- Data Mart Requirements:
  Need for a data mart named "RETAIL_DATA_MART" displaying transactions for each customer categorized as "citizen" or "foreign".  
  Include information on purchased products and stock with file name.  
  Apply transformations such as converting customer names to uppercase and representing date in display column instead of using dim date table.  
- Business Needs Analysis:  
- Analyze "RETAIL_DATA_MART" to fulfill the following requirements:  
   Display count of transactions for each customer per store.  
   Identify the customer type (citizen or foreign) with the maximum profit.  
- DataMart Creation:  
Create a data mart named "ACTIVATION_SALES_DATA_MART" based on the analysis  
- Bonus Calculation:  
Determine bonus for customers who make profit using the equation: Annual_Incomek$ * SpendingScore * 100.  

