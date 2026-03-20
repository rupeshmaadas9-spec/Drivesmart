🚗 DriveSmart: Rental Car Price Prediction System

DriveSmart is an end-to-end data science project that scrapes car rental prices from Kayak, analyzes pricing patterns, and builds machine learning models to predict daily rental rates. The goal is to help consumers identify good deals and give rental companies pricing insights.

📌 Project Overview

DriveSmart is built as a multi-phase pipeline that transforms raw web data into actionable pricing insights and predictive intelligence for smarter rental decisions.

⚙️ Tech Stack

Python · Pandas · NumPy · Selenium · BeautifulSoup · Scikit-learn · XGBoost
(Future: FastAPI · Streamlit · Airflow)

🏗️ Project Phases

🔹 Phase 1: Web Scraping & Data Collection

Automated data extraction from Kayak using Selenium and BeautifulSoup across multiple locations and date ranges.
Outputs structured datasets for downstream analysis.

🔹 Phase 2: Exploratory Data Analysis (EDA)

Data cleaning, preprocessing, and feature engineering to uncover pricing patterns, trends, and booking behaviors.

🔹 Phase 3: Machine Learning Modeling

Development and evaluation of regression models to predict rental prices, with XGBoost selected as the best-performing model.

🔹 Phase 4: Deployment (Planned)

Design of a production-ready system including API-based model serving, user interface for predictions, and automated data pipelines.

🎯 Key Outcome

A scalable system that enables:

Rental price prediction

Deal evaluation

Data-driven booking decisions

🚀 Future Scope

Real-time data pipelines

Multi-city/global expansion

Advanced model optimization

Interactive dashboards
