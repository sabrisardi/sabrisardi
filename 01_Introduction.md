# Introduction 
The Industry Data Workbench (IDW) is a platform that enables organizations across industries to describe their data estate using comprehensive best in-class data models called as Industry Data Models (IDM). Industry Data Models contain a large set of entities and attributes specific to an industry for defining data, and are defined using Common Data Model (CDM) framework enabling interoperability with analytics products such as Dynamics 365, Power BI, etc. 

IDW accelerates unlocking value out of data by enabling organizations : 
1. Bring any or all of their data together and add semantics using IDM to make it self-describing,   
1. Accelerate the consumption of data for reporting/insights/analytics needs through automated ETL/ELT data flows using IDM semantics, and   
1. Integrate with a rich ecosystem of ready-to-integrate partner solutions (data enrichment or analytics) for domain specific use cases.  

This document covers the details on various product concepts, such as Industry Data Models (IDM), Common Data Models (CDM) framework, and the detailed steps for unlocking value of your data using Industry Data Workbench (IDW).

## Overview
Today, organizations generate raw data at every step of their customer or business engagement. However, an organization’s journey from converting raw data to insights is challenging because:    
1. The data is siloed i.e. it is in different data systems, defined using different data schemas or data formats, and described using different metadata    
1. Generation of meaningful insights from data involves expensive and time consuming ETL/ELT data flows for merging and transforming data.    

Industry Data Workbench enables you to bring data from multiple different data systems together into a common data lake defined using Industry Data Models. This becomes the single source for data of an organization and solves the need of ETL/ELT data flows from separate “siloed” data systems for insights generation. Next, it helps to generate semi-automated ETL/ELT data flows to transform your data for various use cases such as data warehouse/data marts for analytics or machine learning (ML) solutions. At a high level, this end to end journey of insights generation on data involves the following steps:   

- **Bring data from  multiple data systems together:**:
1.	Explore and customize Industry Data Models (IDM). You can sub-set the comprehensive data models for your organization’s needs or extend them for any specific use cases.
2.	Create data lake    deploying customized models in Azure Data Lake Storage (ADLS) Gen 2.
3.	Define low-code/no-code data transformation pipelines for unifying raw data together in the data lake.

- **Transform data for analytics/insights:**:
1.	Customize Industry Data Models for your analytics/insights generation (in-house or through integration with partner solutions).
2.	Create analytics   data store deploying customized models in Azure Synapse Analytics (SQL Data Warehouse) or Azure Data Lake Storage (ADLS) Gen 2.
3.	Leverage auto-generated data transformation pipelines for moving data to analytics data stores.
4.	Generate business reports using Power BI or integrate with in-house or partner   solutions.

## Audience
This enables the following key roles in an organization who work with data that an organization has, and contribute for effective generation of insights from the raw data:  
1.	A data architect   or database developer, responsible for designing and developing data stores, such as data lake and databases  , would explore and customize industry data models for their organizational needs.
2.	A data engineer, responsible for operating and maintaining data stack, would bring data from different sources and transform the data using ETL/ELT   pipelines. 
3.	A data analyst, responsible for analyzing data to help make business decisions, would consume data for generation of business reports   or doing a ‘what-if’ analysis.
4.	A data scientist, responsible for building analytical models, would consume data for generation of predictive and prescriptive insights for business problems.

## Scenarios  
Industry Data Workbench enables you to unlock value of your data through the core capabilities for data unification and data transformation built on Industry Data Models. Here are some of the key scenarios:  
1.	Bring your data estate together described using Industry Data Models customized to meet the needs of your business.
2.	Automate data transformation for creation of Azure Synapse Analytics (formerly, SQL Data Warehouse) and generation of Power BI reports   on top of it.   
3.	Leverage rich ecosystem of partner solutions, such as, product recommendations, demand forecasting, etc. for accelerated generation of insights on your data.   

