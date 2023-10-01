This project aims to demonstrate real-time data streaming by building a stock market data processing engine. It begins with CSV data extraction through simulation in Python. The data is then ingested into Apache Kafka, where a Producer generates real-time data for the Consumer to process it. The consumed data is stored in JSON format in an AWS S3 Bucket. This data processing pipeline is deployed on an EC2 instance, using Jupyter Notebook for code development. AWS Glue is used to crawl and catalog the S3 data, which can be queried in Athena. Finally, the data is visualized in Power BI by connecting to Athena through ODBC, enabling real-time reporting and analysis.

# Stock Market Data Architecture
![sm-dp](https://github.com/riti215/Stock_Market_Data_Pipeline_and_Analysis/assets/57587827/e4ed4ad6-8068-4b60-8cb1-24299812e037)

# Technology used
1. Programming Language - Python, SQL
2. File format - CSV, JSON
3. Amazon Web Service (AWS) - S3 (Simple Storage Service), Athena, Glue Crawler, Glue Catalog, EC2
4. Apache Kafka
5. Microsoft Power BI

# Stock Market Data Visualization
![image](https://github.com/riti215/Stock_Market_Data_Pipeline_and_Analysis/assets/57587827/81c5bdcf-dbdb-433a-9454-0dca00bcb8ef)
