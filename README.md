

# Food Delivery Data analysis Pipeline

## Overview

This project implements a data integration and validation pipeline for a food delivery platform. It ingests data from multiple heterogeneous sources, validates schema consistency, merges datasets using relational identifiers, and exports a unified dataset suitable for analytics and machine learning workflows.

---

## Objectives

* Integrate data from multiple file formats and databases
* Ensure schema validation and data consistency
* Handle missing or inconsistent data safely
* Generate a clean, consolidated dataset for downstream use

---

## Technology Stack

* Python
* Pandas
* SQLite3
* Jupyter Notebook

---

## Data Sources

| Data        | Format          | Description                  |
| ----------- | --------------- | ---------------------------- |
| Orders      | CSV             | Order transaction details    |
| Users       | JSON            | Customer profile information |
| Restaurants | SQLite Database | Restaurant metadata          |

---

## Workflow

1. Load order data from CSV
2. Load user data from JSON
3. Retrieve restaurant data from SQLite database
4. Validate required columns in each dataset
5. Handle missing values and inconsistencies
6. Merge datasets using `user_id` and `restaurant_id`
7. Export the final integrated dataset

---

## Features

* Multi-source data ingestion
* Schema validation before merging
* Reliable relational joins
* Clean and structured output
* Reproducible pipeline design

---

## Output

The pipeline generates the following file:

```
food_delivery_final_output.csv
```

This dataset contains merged order, user, and restaurant information.

---


