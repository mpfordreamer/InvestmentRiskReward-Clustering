# InvestmentRiskReward-Clustering

## Overview
This project implements machine learning clustering techniques to categorize investments based on their risk-return profiles. Using K-means clustering, investments are classified into three categories: Low Risk Low Return, Medium Risk Medium Return, and High Risk High Return.

## Features
- Data preprocessing and normalization
- K-means clustering implementation
- Cluster evaluation using Silhouette Score and Elbow Method
- Visualization of clustering results
- Industry-specific insights

## Dataset
The dataset contains information about global startups including:
- Industry classification
- Financial metrics (Investment Amount, Valuation)
- Performance indicators (Growth Rate, ROI)
- Company details (Founding Year, Location)

## Key Findings
1. Risk-Return Categories:
   - Low Risk Low Return: 99.7% of portfolio
   - Medium Risk Medium Return: 0.2%
   - High Risk High Return: 0.1%

2. Industry Distribution:
   - HealthTech and SaaS dominate low-risk category
   - Biotech and AI lead in medium-risk segment
   - EdTech shows strong presence in high-risk category

## Requirements
- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Usage
The main analysis is contained in `[Clustering]_Submission_Akhir_BMLP_I Dewa Gede Mahesta Parawangsa.ipynb`

## Results
The analysis reveals three distinct investment profiles:
- Low Risk Low Return: Stable investments with consistent but modest returns
- Medium Risk Medium Return: Balanced investments with moderate growth potential
- High Risk High Return: Aggressive investments with high growth potential

## License
MIT License
