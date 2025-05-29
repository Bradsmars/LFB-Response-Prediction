# Predictive Modeling of London Fire Brigade Response Times and Pump Deployment Patterns

## 📍 Project Overview

This project uses **machine learning** and **spatiotemporal analysis** to predict:

- 🚒 **The number of fire pumps** deployed at the time of a call
- ⏱️ **Response times** of the London Fire Brigade

The analysis is based on a dataset provided by the **London Fire and Rescue Service** (Jan–Apr 2017) and includes spatial, temporal, and incident-related attributes.

Two predictive pipelines were built:
- **Pipeline 1**: Multi-class classification for pump count using XGBoost and Random Forest
- **Pipeline 2**: Regression models for response time prediction using LightGBM, Random Forest, and a Stacking Ensemble

---

## 📁 Repository Structure

Data_science_project/
├── data/ # Cleaned and raw datasets
├── notebooks/ # Jupyter notebooks for EDA and modelling
├── models/ # Trained model files
├── figures/ # Visuals used in the report
├── report/ # Project report (PDF)
└── README.md # Project description and usage guide



🎯 Project Objectives
Identify key factors affecting response time

Determine the most important attributes for pump deployment

Use advanced machine learning and feature engineering to improve predictive performance

Leverage spatial and temporal insights for real-world emergency planning

---

📊 Results Summary
Pump Deployment:
XGBoost achieved 79.8% accuracy, outperforming Random Forest and Logistic Regression.

Response Time:
LightGBM and the Stacking Ensemble performed best, with an RMSE of 98.56 seconds and R² = 0.4575.


👥 Team Contributions
Bradley Marimbire: Abstract, Pipeline 2

Jacob Abraham Palakunnathu: Preprocessing, feature engineering, unsupervised clustering

Diana Muthoni: Pipeline 1 (coding, modelling, evaluation)


## ⚙️ How to Run the Project Locally

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/yourusername/Data_science_project.git
   cd Data_science_project
