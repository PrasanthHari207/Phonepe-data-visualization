# Phonepe-data-visualization

## Introduction to project

PhonePe is one of India's leading digital payment platforms. Launched in December 2015, it is a subsidiary of Flipkart, which is owned by Walmart. PhonePe offers a range of financial services and products, including UPI-based money transfers, recharges, bill payments, and investments. The platform has become popular for its user-friendly interface and wide acceptance across various merchants and service providers.

Key Features and Services:

* UPI Payments: PhonePe leverages the Unified Payments Interface (UPI) system, enabling users to make instant bank transfers using their mobile numbers or virtual payment addresses (VPAs).

* Mobile Recharges and Bill Payments: Users can easily recharge their mobile phones, pay utility bills, and manage other recurring payments through the app.

* Merchant Transactions: PhonePe is widely accepted across numerous offline and online merchants, allowing users to pay for goods and services using the app.

* Financial Products: The app also offers mutual funds, gold investments, insurance products, and more, making it a comprehensive financial services platform.

* PhonePe Switch: This feature integrates various third-party apps within PhonePe, allowing users to access multiple services like food delivery, grocery shopping, and travel bookings from within the app.



### Softwares / Tools used

* Virtual code.
* Jupyter notebook.
* Python 3.11.0 or higher.
* MySQL.
* MongoDB.
* Youtube API key.

## Packages / Libraries need to be Installed

* google-api-python-client.
* pymongo.
* postgreSQL.
* pandas.
* streamlit.
 
### Imported Libraries

**Youtube API libraries**
* import googleapiclient.discovery
* from googleapiclient.discovery import build

**MongoDB library**
* import pymongo

**SQL library**
* import postgreSQL

**pandas library**
* import pandas as pd

**Dashboard library**
* import streamlit as st

### E T L Process

*ETL, or Extract, Transform, Load, is a data integration process commonly used in data warehousing and analytics. Here's a brief description of each step:

### Extract: 
*Data is extracted from various sources such as databases, files, or APIs. This step involves gathering raw data from multiple locations.

### Transform: 
*The extracted data is transformed or cleaned to fit the desired format, structure, or quality standards. This may include tasks like filtering, sorting, aggregating, or converting data types.

### Load: 
*Finally, the transformed data is loaded into a target database, data warehouse, or analytical system. This step involves storing the data in a structured way for analysis, reporting, or further processing.

*In essence, ETL is the process of gathering, preparing, and loading data from disparate sources into a centralized location for analysis and decision-making.


### E D A Process and Framework

#### Access:

* Create a connection to the MySQL server and access the specified MySQL DataBase by using pymysql library and access tables.

#### Filter the data:

* Filter and process the collected data from the tables depending on the given requirements by using SQL queries and transform the processed data into a DataFrame format.

#### Visualization

* Finally, create a Dashboard by using Streamlit and give dropdown options on the Dashboard to the user and select a question from that menu to analyse the data and show the output in Dataframe Table and Bar chart.



![GitHub Logo](https://github.com/PrasanthHari207/Youtube-data-harvesting/blob/main/streamlit.png)

## User Guide
#### Step 1. Enter the channel ID

* Search **channel_id**, copy and **paste on the input box** and click the **store data in MongoDB** button.

#### Step 2. Migrate the data to SQL

* Select the **channel name** in drop down list present in the sidebar and click the **Transfer data from MongoDB to SQL** button to migrate the specific channel data to the PostgreSQL database from MongoDB.

#### Step 3. View tables which have created in SQL

**Select the radio buttons** of the datas to view the particular **Tables** which is stored in **PostgreSQL**.

#### Step 3. Channel Data Analysis

**Select a Question** from the dropdown option you can get the **results in Dataframe format**.

