# Uber Data Analytics | Modern Data Engineering GCP Project

## Introduction
This project leverages Google Cloud Platform (GCP) to build a modern data pipeline for Uber data analytics. We'll utilize Mage.ai for a streamlined ETL process, store data in BigQuery for efficient analysis, visualize insights with Looker Studio, and manage everything with Cloud Storage. Expect a comprehensive data journey from raw Uber data to interactive dashboards

## Architecture 
![Project Architecture](architecture.jpg)

## Tecnology used
1. Programing Language - Python
2. Scripting Language - SQL
3. Google Cloud Platform
   - Big Query
   - Cloud Storage
   - Looker Studio
   - Computue Instance
4. Mage.AI Modern data pipeline tool

**Modern Data Pipeline Tools** :- https://www.mage.ai/

**Contribute to this project** :- https://github.com/mage-ai/mage-ai

## DataSet used
NYC Trip record Uber Ride Data
Yellow and green taxi trip record Contains anonymized data on Uber rides (pickup/dropoff locations, times, fares, distance, payment, surge multiplier).

Here is the dataset used :- https://github.com/NagsenvKhotkar/Uber-Data-Engineering-Mage-Project/blob/main/data/uber_data.csv

**More Info above dataset**

1.Original Data Source :- https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

2.Data dictionary :- https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

## Data Model
![Data Model Image.](data_model.jpeg)

## Scripts for project
1. [Extrect Python File](mage-files/extract.py)
2. [Load Python File](mage-files/load.py)
3. [Tranform Python File](mage-files/transform.py)





