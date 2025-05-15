# ⚽ Predicting Football Player Market Value Using Machine Learning

This repository contains the code, data pipeline, and supplementary materials for my master's thesis:

> **Title**: *"Predicting Football Player Market Value by Integrating Performance Metrics, External Factors, and Career Trajectories"*

## 📄 Thesis Summary

The project explores how machine learning can be used to predict the market value of professional football players. It combines match-level performance data, contextual external factors (club strength, injuries, UEFA participation, etc.), and unsupervised career trajectory modeling (e.g., DTW, clustering, image-based) to build robust predictive models.

Key contributions include:
- A feature engineering pipeline capturing performance, consistency, context, and player development.
- Integration of four career trajectory modeling approaches.
- An ablation study comparing the predictive value of different feature groups.
- Time series forecasting and residual analysis for advanced valuation insights.

📦 Accessing Data, Visualizations & Models
Due to GitHub's file size limitations, the following folders are hosted externally:

data/ – Cleaned datasets and original datasets
visualizations/ – Plots and images used in the thesis (t-SNE, residuals, etc.) and contextual performance score's plots of +5000 players (normalized and raw)
models/ – Trained model artifacts and predictions in pkl and csv files

You can access them all via Google Drive:
👉 [Download from Google Drive](https://drive.google.com/drive/folders/1-QEayJJ_bZqjIZ2KFzCOH4hBB6rUDEeh?usp=sharing)

After downloading, unzip and place the folders into your project root directory.

## Repository Structure
```
project-root/
├── data/ # Cleaned datasets and original datasets
├── notebooks/ # Jupyter notebooks for EDA, modeling, and evaluation
├── models/ # Trained model artifacts and predictions in pkl and csv files
├── visualizations/ # Plots and images used in the thesis (t-SNE, residuals, etc.) and contextual performance score's plots of +5000 players (normalized and raw)
└── README.md # This file
```
