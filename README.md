# MLB Data Science Prediction System

A data science and machine learning project developed to analyze Major League Baseball (MLB) games using real-world data obtained through the BallDontLie API.

The project implements a complete data pipeline using PySpark, including data ingestion, cleaning, feature engineering, predictive modeling, anomaly detection, and report generation. Historical game statistics are transformed into predictive features that allow a Random Forest model to estimate game outcomes and identify high-volatility matches.

## Project Objectives

* Collect real MLB game data through a REST API.
* Build an ETL pipeline using PySpark.
* Generate predictive features from historical team performance.
* Train a Random Forest classification model.
* Detect statistical anomalies and high-risk matches.
* Produce reports that can be consumed by Power BI or Tableau.

## Technologies

* Python
* PySpark
* Pandas
* Machine Learning
* Random Forest Classifier
* REST APIs
* Google Colab

## Data Pipeline

BallDontLie API → Data Ingestion → Data Cleaning → Feature Engineering → Model Training → Prediction Engine → CSV Reports

## Machine Learning Features

The model generates performance indicators such as:

* Team offensive performance
* Team defensive performance
* Average hits per game
* Average defensive errors
* Home and away team historical metrics

These variables are used to train a Random Forest model capable of estimating match outcomes and detecting unexpected results.

## Outputs

The project generates the following reports:

* Match predictions with winning probabilities
* Volatility and risk analysis
* Statistical anomaly detection
* Feature importance rankings

## Skills Demonstrated

* Data Analysis
* Data Engineering
* Feature Engineering
* Machine Learning
* ETL Pipelines
* API Integration
* Big Data Processing with PySpark
* Predictive Analytics

## Repository Structure

```text
Proyecto_MLB_DataScience/
│
├── README.md
├── Proyecto_MLB_DataScience.ipynb
├── requirements.txt
└── outputs/
    ├── predicciones_de_hoy.csv
    └── reporte_anomalias.csv
```
