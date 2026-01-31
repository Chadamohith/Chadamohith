Food Delivery Data Integration and Validation Pipeline
Project Description

This project implements a structured data integration pipeline for a food delivery platform. It focuses on ingesting data from multiple heterogeneous sources, validating schema integrity, merging datasets using relational keys, and exporting a clean, unified dataset for analysis and downstream processing.

The project demonstrates practical skills in data engineering, data preprocessing, and pipeline design using Python.

Objectives

Integrate data from multiple file formats and databases

Validate schema consistency before processing

Handle missing or inconsistent data safely

Produce a clean, merged dataset ready for analytics or machine learning

Technologies Used

Python

Pandas

SQLite3

Jupyter Notebook

Pathlib

Data Sources
Source Type	Format	Description
Orders Data	CSV	Transaction-level order details
Users Data	JSON	Customer profile information
Restaurant Data	SQLite Database	Restaurant metadata
Pipeline Workflow

Load order data from a CSV file

Load user data from a JSON file

Retrieve restaurant data from a SQLite database

Validate the presence of required columns in each dataset

Handle missing values and schema inconsistencies

Merge datasets using user_id and restaurant_id

Export the final integrated dataset as a CSV file

Key Features

Modular data loading from multiple sources

Schema validation to ensure data reliability

Robust merging using relational identifiers

Clean and structured final output

Reproducible and well-documented workflow

Output

The pipeline generates a single consolidated dataset:

food_delivery_final_output.csv


This file contains combined order, user, and restaurant information.
