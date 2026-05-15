NorthStar Databases and Analytics Project
Overview

This repository contains the complete analytical and database implementation developed for the Databases and Analytics module based on the NorthStar Urban Mobility and Logistics case study.

The project investigates operational inefficiencies, customer complaints, delivery failures, maintenance risks, and operational disruptions using an integrated analytical environment combining:

SQL within R
R statistical analytics
Python data processing
MongoDB Atlas NoSQL implementation

The investigation focuses on transforming fragmented operational datasets into meaningful organisational intelligence capable of supporting operational monitoring, business decision-making, and scalable analytical processing.

The GitHub repository was organised into several structured folders to improve organisation and reproducibility. The notebooks folder contains the Google Colab notebooks used for SQL/R analysis, Python analytics, and MongoDB Atlas implementation. The data folder stores the raw, cleaned, and processed datasets used throughout the investigation. The images folder contains SQL/R outputs, Python analytical visualisations, and MongoDB Atlas screenshots.

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

The project uses multiple interconnected operational datasets provided within the NorthStar case study environment.

Datasets include:

Customers
Orders
Deliveries
Drivers
Vehicles
Hubs
Complaints
Incidents
App Events
Data Dictionary

These datasets were integrated to analyse relationships between:

delivery performance
customer dissatisfaction
operational incidents
route overrides
maintenance risks
organisational inefficiency
SQL in R Analysis

SQL queries were executed within the R environment using SQLite integration.

The relational analysis focused on:

Delivery delay analysis by hub
Failed deliveries and complaint relationships
Vehicle maintenance risk analysis
Complaint severity analysis
Operational incident evaluation
Service-type performance comparison
Python Analytics

Python was used for:

data preprocessing
missing value handling
feature engineering
operational risk scoring
dataset integration
analytical visualisation

Several engineered operational indicators were developed, including:

delay flags
failure flags
complaint indicators
maintenance risk variables
route override risk indicators
operational risk scores
MongoDB Atlas Implementation

MongoDB Atlas was implemented to support flexible document-oriented storage for semi-structured operational records.

The implementation includes:

Atlas cloud database setup
BSON document modelling
CRUD operations
aggregation pipelines
indexing strategies
explain plan analysis
query optimisation

The primary implemented collection was:

customer_cases

This collection integrates:

customer data
order data
delivery data
vehicle information
driver information
complaint histories
incident records
operational risk indicators
event timelines
Key Findings

The investigation identified several important operational patterns within NorthStar:

Certain hubs recorded significantly higher delay rates
Vehicle maintenance issues strongly influenced failed deliveries
High-severity complaints were closely associated with delivery disruption
Operational incidents increased customer dissatisfaction
Fragmented systems reduced organisational visibility
MongoDB improved flexibility for handling event-driven operational records
MongoDB Features Demonstrated

The MongoDB implementation demonstrates:

document-oriented modelling
nested BSON structures
CRUD functionality
aggregation pipeline analysis
operational risk querying
indexing optimisation
explain plan evaluation
Google Colab and GitHub Integration

All analytical workflows were developed using Google Colab notebooks and stored within this GitHub repository to support:

reproducibility
transparency
version control
structured analytical documentation
Author

Abdul Azoor
BSc (Hons) Information Technology
University of West London

Academic Purpose

This repository was developed strictly for academic and educational purposes as part of the Databases and Analytics module coursework.
