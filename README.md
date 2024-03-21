# YouTube_Campaign
<img align="center" src="Youtube.jpg">

## Introduction

### Purpose: For all company marketing department who wants to run an their company ad- campaign on Youtube.

## Marketing Platform: Youtube

### Business Questions: How to categorise videos, based on their comments and statistics
### What factors affect and answers the question: How Popular a Youtube video will be? 

### Why Youtube? 
### Most visited platform in the world, to be precise 2nd most visited.
### So easy to target more people in short span of time, thus we can get more customers

## Goals and Success Criteria: 
### How my customer measure success?
The establishment of efficient mechanisms for data ingestion from diverse sources, implementing an Extract, Transform, Load (ETL) system to convert raw data into the appropriate format, and creating a centralized data lake for storage. And the Marketing Team will have better insights on Viewers interactions and which category has large audience. This will help them to better strategize for better youtube campaigns. 

### What Experience I gained:
1.	Building Data Lake from scratch using Amazon S3
2.	Lake House Architecture design
3.	Data Lake vs Data Warehouse
4.	Data Lake Design and how its partition affects cost- performance
5.	AWS Data Catalogue
6.	ETL Jobs using AWS Glue Spark
7.	Amazon SNS for altering
8.	SQL using Amazon Athena and Spark SQL
9.	Script to ingest changes incrementally and schema evolution.
10.	BI Dashboards in Amazon QuickSight.

### Project Goals
Data Ingestion — Build a mechanism to ingest data from different sources

ETL System — We are getting data in raw format, transforming this data into the proper format

Data lake — We will be getting data from multiple sources so we need centralized repo to store them

Scalability — As the size of our data increases, we need to make sure our system scales with it

Cloud — We can’t process vast amounts of data on our local computer so we need to use the cloud, in this case, we will use AWS

Reporting — Build a dashboard to get answers to the question we asked earlier

### Data Architecture:
<img align="center" src="Img/Imag1.png">

### Services used:

Amazon S3: Amazon S3 is an object storage service that provides manufacturing scalability, data availability, security, and performance.

AWS IAM: This is nothing but identity and access management which enables us to manage access to AWS services and resources securely.

QuickSight: Amazon QuickSight is a scalable, serverless, embeddable, machine learning-powered business intelligence (BI) service built for the cloud.

AWS Glue: A serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development.

AWS Lambda: Lambda is a computing service that allows programmers to run code without creating or managing servers.

AWS Athena: Athena is an interactive query service for S3 in which there is no need to load data it stays in S3.
### Dataset Used
This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for 

many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count 

are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.

https://www.kaggle.com/datasets/datasnaek/youtube-new

