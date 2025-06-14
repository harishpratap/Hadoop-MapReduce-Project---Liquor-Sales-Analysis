# Hadoop-MapReduce-Project---Liquor-Sales-Analysis
Introduction
Objective


In this case study, you will learn about the principles of hands-on data processing and analysis using a detailed data set on liquor sales spanning 2020 to 2025.



This assignment aims to give you practical experience in processing large data sets using tech stacks such as AWS RDS, HBase and Hadoop MapReduce. You will apply the techniques covered in the project modules and gain insights into the complexities of business data analytics. By the end of this assignment, you should have developed a robust understanding of the following concepts:

Data ingestion processes using cloud-based tools such as AWS RDS and HBase
Data cleaning and preparation to ensure high-quality analysis
Applying MapReduce to solve real-world analytics problems
Creating actionable insights and recommendations based on the analysis


This hands-on approach will bridge the gap between theoretical learning and practical implementation, preparing you for real-world challenges in the field of data analytics.


Business Value


The liquor industry is a significant contributor to the retail economy, particularly in regions where sales are highly regulated and tracked. For liquor businesses, understanding sales trends is vital to maintaining competitive advantage, meeting customer demand and ensuring efficient operations. As an analyst, you are tasked with analysing detailed liquor sales data from 2020 to 2025 to uncover patterns and insights that can drive strategic decision-making. The objective is to identify trends in consumer preferences, regional sales performance and product popularity, enabling stakeholders to optimise inventory management, boost profitability and enhance customer satisfaction.
Assignment Tasks
The video below will take you through the various tasks and its sub-tasks for this assignment.

Play Video5997944
The tasks for the assignemnt are listed below.

1. Data Ingestion and Preparation

The data set provided, ‘Liquor Sales Data Set’, contains detailed sales records from 2012 to 2020. Your first task is to ingest the data into appropriate systems and prepare it for analysis.
Upload the data set into AWS RDS, ensuring proper schema definition as per the data dictionary.
If applicable, split the data set into smaller chunks to optimise ingestion and processing.
Transfer data from AWS RDS to HBase using Apache Sqoop, defining an HBase schema with suitable column families and row keys.
Validate the integrity of the ingested data in both systems to ensure consistency.
2. Data Cleaning

Before performing any analysis, clean the data set to ensure accuracy and consistency in the results.

Remove rows with missing or incomplete values.
Handle inconsistent or erroneous data (e.g., incorrect formatting and invalid values).
Standardise categories and correct data formats where necessary.
Eliminate duplicate records to maintain data integrity.
3. Batch Processing Using MapReduce

Revenue and Sales Analysis
Calculate total revenue per store.
Identify top-selling liquor categories by calculating total ‘Bottles_Sold’ and ‘Sale_Dollars’.
Aggregate sales by county to determine the total ‘Sale_Dollars’ and sales volume (litres and gallons) for each county.
Store and Vendor Performance
Perform store performance analysis by ranking stores based on total revenue, total volume sold and average sales per transaction.
Rank vendors based on total revenue and volume sold, using the ‘Vendor_Name’ and ‘Sale_Dollars’ fields.
Time-Based and Trend Analysis
Analyse trends in liquor sales over time (monthly/yearly revenue and volume sold) using the ‘Date’ field.
4. Conclusion and Recommendations [10 marks]

The final insights and recommendations should follow the following format:

Provide recommendations to optimise store operations and sales strategies based on the total revenue and sales performance analysis.
Provide suggestions on identifying the most profitable liquor categories and prioritising their promotion to increase sales.
Propose data-driven strategies to enhance vendor performance by identifying top-performing vendors and scaling their operations.
Propose recommendations for adjusting sales and marketing efforts based on sales trends over time and county-level sales insights.
 
You are also required to present the overall approach of the analysis in a report document along with the the problem statement and the analysis approach.

 

IMPORTANT NOTE: You will need to create an appropriate schema before uploading the data sets to AWS RDS (you can find the data dictionary in the previous segments). The steps on how to create an AWS RDS instance can be found in the Additional content of the 'Introduction to Cloud Computing and AWS Setup' module and the steps to work with RDS in the link shared in the next segment)

 

In the starter notebook, attached below, you will find headings, subheadings and checkpoints stating the tasks you need to perform. The marks associated with each checkpoint will also be mentioned in the notebook. Keep in mind not to edit the cells with marking schemes and questions.
