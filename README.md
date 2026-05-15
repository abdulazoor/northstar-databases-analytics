NorthStar Databases and Analytics Project
Overview

This repository contains the complete analytical and database implementation developed for the Databases and Analytics module based on the NorthStar Urban Mobility and Logistics case study.

The project investigates operational inefficiencies, customer complaints, delivery failures, maintenance risks, and operational disruptions using an integrated analytical environment combining:

SQL within R
R statistical analytics
Python data processing
MongoDB Atlas NoSQL implementation

The investigation focuses on transforming fragmented operational datasets into meaningful organisational intelligence capable of supporting operational monitoring, business decision-making, and scalable analytical processing.

Technologies Used
Python
Pandas
NumPy
SQL (SQLite within R)
R Programming
MongoDB Atlas
PyMongo
Google Colab
GitHub
Project Objectives

The main objectives of this project are:

Analyse delivery delays and operational inefficiencies
Identify customer complaint and incident patterns
Evaluate vehicle maintenance risks
Investigate hub-level operational performance
Integrate structured and semi-structured datasets
Implement a MongoDB Atlas document-oriented database
Demonstrate CRUD operations and aggregation pipelines
Apply indexing and query optimisation techniques
Support operational intelligence using integrated analytics

Repository Structure
northstar-databases-analytics/
│
├── README.md
│
├── notebooks/
│   ├── 01_SQL_R_Analysis.ipynb
│   ├── 02_Python_Analytics.ipynb
│   └── 03_MongoDB_Implementation.ipynb
│
├── data/
│   │
│   ├── raw/
│   │   ├── customers.csv
│   │   ├── orders.csv
│   │   ├── deliveries.csv
│   │   ├── drivers.csv
│   │   ├── hubs.csv
│   │   ├── vehicles.csv
│   │   ├── complaints.csv
│   │   ├── incidents.csv
│   │   ├── app_events.csv
│   │   └── data_dictionary.csv
│   │
│   ├── cleaned/
│   │   ├── cleaned_deliveries.csv
│   │   └── cleaned_complaints.csv
│   │
│   └── processed/
│       ├── northstar_processed_dataset.csv
│       ├── mongodb_high_risk_cases.csv
│       ├── complaint_escalation_analysis.csv
│       ├── hub_analysis.csv
│       ├── vehicle_maintenance_analysis.csv
│       └── route_override_analysis.csv
│
├── images/
│   │
│   ├── sql_r/
│   ├── python/
    └── mongodb/
