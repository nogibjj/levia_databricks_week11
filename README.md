# Databricks Data Pipeline Project

## Overview
This project demonstrates the creation of an end-to-end data pipeline using Databricks. It involves ingesting, transforming, and analyzing data, specifically focusing on a dataset provided in the Databricks tutorial.

## Pipeline Steps

### Step 1: Ingest the Raw Data
This step involves loading the raw data into a Databricks table for processing. It utilizes the Auto Loader feature for efficient data ingestion.
![ingest](https://github.com/nogibjj/levia_databricks_week11/blob/main/images/ingest_data.png)

### Step 2: Prepare the Raw Data
In this step, the raw data is transformed. This involves filtering out unnecessary columns and adding new fields to the dataset.
![preapre](https://github.com/nogibjj/levia_databricks_week11/blob/main/images/prepare_data.png)

### Step 3: Query the Transformed Data
This step focuses on analyzing the transformed data using SQL queries to extract meaningful insights.
![query](https://github.com/nogibjj/levia_databricks_week11/blob/main/images/query.png)

### Step 4: Create a Databricks Job to Run the Pipeline
A Databricks job is configured to automate the steps of data ingestion, processing, and analysis.
![create](https://github.com/nogibjj/levia_databricks_week11/blob/main/images/create_pipeline.png)

### Step 5: Schedule the Job
Finally, this job is scheduled to run at specified intervals, ensuring that the pipeline operates continuously and automatically.
![schedule](https://github.com/nogibjj/levia_databricks_week11/blob/main/images/schedule.png)


## Demonstrating the Pipeline
- **Ingestion**: Data from the dataset is ingested and stored in a table.
- **Preparation**: Data is then prepared by selecting necessary columns and adding a timestamp.
- **Analysis**: Various analytical queries are run on the prepared data to extract insights.
- **Job Creation**: Finally, a Databricks job is created to orchestrate these steps.

## Usage
To use this pipeline:
1. Set up a Databricks cluster.
2. Create and run the provided notebooks in the order: ingestion, preparation, analysis.
3. Configure the Databricks job to automate the pipeline.

## Note
This project is based on the Databricks tutorial. Adaptations may be necessary for different datasets or specific use cases.
Reference: https://docs.databricks.com/en/getting-started/data-pipeline-get-started.html
