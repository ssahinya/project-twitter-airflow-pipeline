# Twitter Data Engineering Pipeline

## Overview
This project demonstrates a real-time data engineering pipeline built to collect, transform, and store Twitter data using modern, cloud-based tools. The pipeline automates the ETL (Extract, Transform, Load) process and is designed to be scalable, cost-effective, and production-ready for analytical use cases.

## Goals
1. Automate Data Collection – Ingest real-time tweets using the Twitter API
2. Data Transformation – Clean and process raw tweet data using Python.
3. Scheduled Workflows – Orchestrate and automate the pipeline using Apache Airflow.
4. Cloud Deployment – Ensure scalability and availability by deploying on AWS EC2.
5. Cloud Storage – Store processed data securely in AWS S3 for downstream analysis.

## Technologies & Services Used
1. Apache Airflow – Orchestration tool for managing and scheduling data workflows.
2. Python – Scripting language for API integration and data transformation.
3. Twitter API (v2) – For fetching real-time tweet data.
4. AWS EC2 – Compute service for hosting and running the Airflow pipeline.
5. AWS S3 – Scalable object storage for storing transformed tweet data.

## Dataset
The data is collected from the Twitter API v2, which provides real-time tweet metadata including:
- Tweet content
- Timestamps
- Hashtags and mentions
- User details

The data is transformed into a structured format and stored in AWS S3 for further analysis or integration with BI tools or data lakes.
