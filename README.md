# Data Engineer Workshops
🔖 Workshops from Road to Data Engineer **'R2DE'** course from [Data TH.com — Data Science ชิลชิล](https://www.facebook.com/datasciencechill)

<img width="890" alt="Screen Shot 2567-01-27 at 23 04 45" src="https://github.com/thitirat-mnc/Data-Engineer-Workshop-R2DE/assets/134206687/25cd5e7a-2c7a-42fe-bc9a-7038d4cb562f">

> [!NOTE]
> picture from [data.th](https://school.datath.com/)

## 🖇️ Week 1 Data Collection with Python 
-	MySQL Database connection using PyMySQL
-	REST API data collection using Package Requests

## 🖇️ Week 2: Data Cleansing with Spark
-	Data Profiling
-	Exploratory Data Analysis (EDA)
-	Data Anomalies Check – syntactic, semantic, missing values, outliers
-	Data Cleansing using Spark SQL

## 🖇️ Week 3: Data Lake, Cloud Computing with Google Cloud Platform (GCP)
-	Bash command line in Cloud Shell
-	Create Bucket and Upload Data into Google Cloud Storage (Data Lake), using gsutil command through Cloud Shell; Python code through Python SDK library
-	Storage Object Lifecycle

## 🖇️ Week 4: (Automated) Data Pipeline Orchestration using Apache Airflows and DAGs (ETL)
<img width="890" alt="image" src="https://github.com/thitirat-mnc/Data-Engineer-Workshop-R2DE/assets/134206687/0de18539-85f0-45cd-9d61-9d385412b529">

> [!NOTE]
> picture from [data.th](https://school.datath.com/)
-	Create a Google Cloud Composer Cluster for running Apache Airflow
-	Create Airflow DAG definition file, instantiation
-	Build Task by creating BashOperator and PythonOperator
-	Setting up Dependencies
-	TaskGroup in DAG

<img width="600" alt="image" src="https://github.com/thitirat-mnc/Data-Engineer-Workshop-R2DE/assets/134206687/c4c18673-84e7-43a9-894c-b274c0ba51ca">

> [!NOTE]
> picture from [data.th](https://school.datath.com/)

## 🖇️ Week 5: (Serverless) Data Warehouse with BigQuery
-	Normalization VS Denormalization Concept (Tradeoff between Storage and Time usage in joining tables)
-	Denormalization for Data Warehouses (optimize performance for frequent querying)
-	Normalization for Databases 
-	Columnar Storage / Column-oriented Database

<img width="450" alt="image" src="https://github.com/thitirat-mnc/Data-Engineer-Workshop-R2DE/assets/134206687/21154fa3-6671-4758-9c6e-daeeaf3cf2f5">

-	Data Mart for different business units -> altogether become Data Warehouse
-	View VS Materialized View
-	Index & Partitioning
-	Automatic Data Importing through BashOperator -> bq load command
-	Automatic Data Importing through AirflowOperator -> GCSToBigQeryOperator on Airflow




