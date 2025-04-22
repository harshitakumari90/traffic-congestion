# Predict Traffic Congestion

A machine learning project that classifies road sections into **High**, **Medium**, or **Low** congestion levels using roadside sensor data—number of active sensors, time of day, and average vehicle speed. :contentReference[oaicite:1]{index=1}

## Features

- **Multiclass classification** with CatBoost for superior handling of categorical inputs. :contentReference[oaicite:2]{index=2}  
- **Native categorical support**—no need for manual encoding of time‑of‑day or sensor identifiers. :contentReference[oaicite:3]{index=3}  
- **Real‑time prediction** interface to input new sensor readings and receive immediate congestion level output. :contentReference[oaicite:4]{index=4}

## Technologies Used

- **Python** for scripting and data manipulation. :contentReference[oaicite:5]{index=5}  
- **Pandas** for data ingestion and preprocessing. :contentReference[oaicite:6]{index=6}  
- **CatBoost** as the core classifier for multiclass prediction. :contentReference[oaicite:7]{index=7}  
- **scikit‑learn** utilities for train‑test splitting and evaluation metrics. :contentReference[oaicite:8]{index=8}  
- **Matplotlib** for plotting the confusion matrix and visualizing results. :contentReference[oaicite:9]{index=9}

## Installation

1. **Clone** the repository:  
   ```bash
   git clone https://github.com/<username>/traffic-congestion-prediction.git
