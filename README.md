# Flight Cancellation Analysis

This project presents an in-depth analysis of U.S. domestic flight cancellations and delays from 2009 to 2018. Using PySpark for large-scale data processing, we explore patterns by airline, airport, season, and cancellation reason. Visualizations and predictive models highlight key trends and operational insights.

## 📊 Features

- Cancellation trends by airline and airport
- Monthly, seasonal, and yearly delay patterns
- Breakdown of cancellation reasons (Weather, Carrier, NAS, Security)
- Average departure delays by hour and airport
- Predictive modeling using Gradient-Boosted Trees, Random Forest, and Logistic Regression

## 🧰 Tools & Technologies

- Python & PySpark
- Pandas & Matplotlib
- Jupyter Notebook
- Kaggle Datasets
- scikit-learn

## 📁 Dataset Sources

- [Airline Delay and Cancellation Data 2009–2018](https://www.kaggle.com/datasets/yuanyuwendymu/airline-delay-and-cancellation-data-2009-2018)
- [2015 Flight Delays and Cancellations](https://www.kaggle.com/datasets/usdot/flight-delays)

## 🔍 Notebooks

- `01_data_preprocessing.ipynb`
- `02_exploratory_analysis.ipynb`
- `03_delay_cancellation_modeling.ipynb`

## 📈 Results Summary

- Weather is the top cause of cancellations, peaking in winter
- Regional carriers and busy hubs face more disruptions
- Delay patterns improve gradually after 2015
- Machine learning models (GBT, RF) achieve strong classification of delays

## 📅 Last updated: 2025-05-07
