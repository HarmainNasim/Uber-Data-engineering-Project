# Uber-Data-engineering-Project
This repository contains a Data Engineering project that leverages Google Cloud to transform Uber ride flat file data into structured tables. The process involves setting up a VM instance, installing necessary Python libraries, and implementing ETL processes.

This project focuses on the practical application of data engineering principles using Uber ride data. We are working with flat file data, transforming it into structured fact and dimension tables, and performing various operations for data extraction, transformation, and loading (ETL). The project makes use of Google Cloud Services, particularly Google Cloud Storage and Google Cloud BigQuery, for storing and analyzing the data.
# Dataset:
You can access the dataset from these URLs: 
Website - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
Data Dictionary - https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

Key steps undertaken in this project:

# Data Upload:
Uber ride data is uploaded onto Google Cloud Storage and set to public access.
# Creating Virtual Machine Instance:
An instance on Google Cloud Compute Engine is created to run the necessary computations.
# Software Installation:
Installation of Python, pip, and various essential libraries including Mage, Pandas, and Google Cloud Libraries is done on the VM instance.
# Data Extraction: 
Data is loaded from the public URL created in the initial steps using Mage.
# Data Transformation:
The transformation block contains Python code (from a Jupyter notebook file) to convert the flat file data into structured dataframes.
# Data Loading:
The transformed dataframes are loaded into Google Cloud BigQuery for further analysis and querying.

This project demonstrates how to effectively utilize cloud resources for large scale data engineering tasks. It is an excellent example of setting up and managing a data pipeline from extraction to transformation and loading (ETL) using Python and Google Cloud Services.

Please refer to the specific Python scripts and commands in the repository for detailed step-by-step procedures.
