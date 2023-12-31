# Data Engineering YouTube Analysis Project
## Overview
This project aims to securely manage, streamline, and perform analysis on the structured and semi-structured YouTube videos data based on the video categories and the trending metrics.

![image](https://github.com/samt1s/AWS_youtube_analysis/assets/96880313/d6692112-fd55-4dfb-8b8f-2ebfd0eba742)

## Project Goals
1. Data Ingestion — Build a mechanism to ingest data from different sources
2. ETL System — We are getting data in raw format, transforming this data into the proper format
3. Data lake — We will be getting data from multiple sources so we need centralized repo to store them
4. Scalability — As the size of our data increases, we need to make sure our system scales with it
5. Cloud — We can’t process vast amounts of data on our local computer so we need to use the cloud, in this case, we will use AWS
6. Reporting — Build a dashboard to get answers to the question we asked earlier

## Services we will be using

* Amazon S3: Amazon S3 is an object storage service that provides manufacturing scalability, data availability, security, and performance.
* AWS IAM: This is nothing but identity and access management which enables us to manage access to AWS services and resources securely.
* QuickSight: Amazon QuickSight is a scalable, serverless, embeddable, machine learning-powered business intelligence (BI) service built for the cloud.
* AWS Glue: A serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development.
* AWS Lambda: Lambda is a computing service that allows programmers to run code without creating or managing servers.
* AWS Athena: Athena is an interactive query service for S3 in which there is no need to load data it stays in S3.

## QuickSight Report
![image](https://github.com/samt1s/AWS_youtube_analysis/assets/96880313/bd2d71bc-4d22-4f0a-92a8-b046f116461e)

## Dataset Used
This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.


__[Link to DataSet](https://www.kaggle.com/datasets/datasnaek/youtube-new)__

