# Overview

This repository contains the implementation of an ETL pipeline using Azure Data Factory (ADF) for building data engineering solutions. The pipeline leverages various Azure technologies such as Azure Data Lake Gen2, Azure Blob Storage, Azure SQL Database, Azure Databricks, Azure HDInsight.

My goal was to learn and showcase how to build a real-world data pipeline in Azure Data Factory and expand my knowledge and skill in Data Engineering in Azure using tools like Azure Data Factory(ADF), which enables users to create, schedule, and orchestrate data pipelines that move and transform data from various sources to destinations, such as databases, data lakes, and alanytics services within Azure and beyond. ADF supports a range of data processing activities and offers capabilities for monitoring and managing the execution of data pipelines.

In an Azure Data Factory pipeline, you can use activities to interact with Azure Data Lake Gen2 and Azure SQL Database, such as:

**- Copy Activity: Move data between different data stores, including Azure Data Lake Gen2 and Azure SQL Database.**
**- Data Flow Activity: Perform data transformations directly within Azure Data Factory, including filtering, aggregating, joining and much more.**
**- Stored Procedure Activity: Invoke stored procedures in Azure SQL Database to perform specific tasks or data manipulations.**


# Features

**- Solution Architecture: Building a robust solution architecture for data engineering projects.**<br />
**- Data Integration: Integrating data from HTTP clients, Azure Blob Storage, and Azure Data Lake Gen2 using ADF.**<br />
**- Control Flow: Implementing branching and chaining activities in ADF pipelines using control flow activities such as Get Metadata, If Condition, ForEach, Delete, Validation, etc.**<br />
**- Metadata Driven Pipelines: Utilizing Parameters and Variables in Pipelines, Datasets, and LinkedServices to create metadata-driven pipelines.**
**- Debugging: Debugging data pipelines and resolving issues efficiently.**
**- Pipeline Scheduling: Scheduling pipelines using triggers such as Event Trigger, Schedule Trigger, and Tumbling Window Trigger.**
**- Transformation Logic: Creating Mapping Data Flows to implement transformation logic including Source, Filter, Select, Pivot, Lookup, Conditional Split, Derived Column, Aggregate, Join, and Sink     transformation.**
**- Dependency Management: Establishing dependencies between pipelines and triggers to orchestrate the data flow effectively.**
**- Monitoring: Monitoring data pipelines, creating alerts, and reporting metrics using Azure Data Factory Monitor.**
**- Azure Storage Solutions: Creating and managing Azure Storage Account, Azure Data Lake Gen2, and Azure SQL Database.**
**- Azure HDInsight & Databricks: Creating clusters, interacting with UI, and executing activities from ADF.**


