# Telecom Customer Churn Prediction

## Project Overview:
The "Telecom Churn Dashboard" in Tableau is a data visualization project designed to analyze and understand customer churn patterns in the telecom industry. 
The dashboard provides a comprehensive overview of customer churn, helping telecom companies identify factors that contribute to customer attrition and develop strategies to retain valuable customers.<br>

## Problem Statement:
In the telecom industry, customers have the flexibility to select from a range of service providers and frequently change operators.  This dynamic market experiences an average annual churn rate of 15-25%. Considering the significantly higher cost of acquiring new customers compared to retaining existing ones (5-10 times more), customer retention has become a top priority.
The Primary objective of telecom industry operators is the retention of high profit customers. To address customer churn, telecom companies must proactively predict which customers are at a higher risk of leaving. <br>

## High level architecture diagram:
![Flowcharts (1)](https://github.com/ashwinjai/Telecom-Customer-Churn-Prediction/assets/36980518/1d7a25be-fce6-4366-afa1-43ce7bdb8280)

## Data Ingestion:
The raw data is stored in the local file system, and an AWS Linux-based instance is launched to establish a connection and transfer the on-premise data to an S3 bucket. The S3 bucket serves as a storage container for the raw data. Subsequently, a connection is set up from Tableau to access the data in the S3 bucket, enabling data feeding to the Tableau engine for chart development and visualization. <br>

