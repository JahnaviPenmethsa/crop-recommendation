#  Crop Recommendation System (IBM Cloud Project)

##  Project Overview
This project aims to recommend the most suitable crop to grow based on environmental and soil conditions using machine learning. Built entirely on IBM Cloud, the solution leverages Watson Studio and AutoAI to process data, build models, and deploy predictions.

## Tools & Technologies Used
 Component            Description 

IBM Watson Studio         Used to create and manage the ML pipeline 
IBM AutoAI                Automatically built and optimized ML models 
IBM Cloud Object Storage  Hosted datasets for analysis 

## Problem Statement
Agriculture is a vital sector, and selecting the appropriate crop for given conditions can significantly impact yield. This system assists farmers and agronomists in making data-driven decisions by recommending crops based on:
- pH level
- Rainfall
- Temperature
- Humidity
- Nutrient content (N, P, K)

## Dataset Used
- Source: Kaggle / IBM Sample Dataset
- Records: ~2,200
- Features:
  - `N` – Nitrogen
  - `P` – Phosphorous
  - `K` – Potassium
  - `Temperature` – in °C
  - `Humidity` – in %
  - `pH` – soil pH
  - `Rainfall` – in mm
  - `Label` – Recommended crop


## Project Workflow
    A[Data Upload to IBM Cloud Object Storage]
    B[AutoAI Model Building]
    C[Model Evaluation and Selection]
    D[Model Deployment as Web Service]
    E[REST API Testing]
    F[Recommendation Output]

    A --> B --> C --> D --> E --> F
