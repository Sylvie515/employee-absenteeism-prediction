# Employee Absenteeism Prediction & Risk Analysis  

## Overview  

This project builds an end-to-end machine learning pipeline to predict employee absenteeism and identify key risk factors associated with long-term absence using Python, Ridge Regression, XGBoost, and K-means clustering.  

## Objective  

The goal is to:  
- Predict employee absenteeism duration (in hours) using regression models  
- Predict the likelihood of long-term absenteeism (≥ 8 hours) using classification  
- Identify key drivers associated with absenteeism behavior  
- Segment employees into behavioral groups for further analysis  

## Methods  

The project applies multiple machine learning approaches:  

- **Regression Models**: Ridge Regression, XGBoost Regressor  
- **Classification Models**: XGBoost Classifier (for long-absence prediction)  
- **Clustering**: K-means for employee segmentation  

## Results  

- Achieved **AUC = 0.905** for long-term absenteeism prediction  
- Identified key factors contributing to absenteeism patterns  
- Generated behavioral segments using clustering techniques  

## Tech Stack  

- Python  
- Pandas, NumPy  
- Scikit-learn  
- XGBoost  
- Matplotlib / basic visualization  

## Project Structure  

```text
.
├── data/          # Dataset folder
├── reports/       # Proposal, progress report, and final report
├── project.ipynb  # Main notebook for data processing and modeling
└── README.md  
```
