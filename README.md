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

## Repository Structure

## Repository Structure
project-root/
├── data/ # Cleaned datasets, not included in this repo
├── notebooks/ # Jupyter notebooks for EDA, modeling, and evaluation
├── models/ # Trained model artifacts and predictions
├── visualizations/ # Plots and images used in the thesis (t-SNE, residuals, etc.)
└── README.md # This file
