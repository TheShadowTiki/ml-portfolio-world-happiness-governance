# Cornell ML Portfolio: World Happiness Governance Project

This repository is part of my Cornell Machine Learning portfolio and features a project analyzing the World Happiness Report dataset. The project applies the full machine learning workflow to explore how governance quality relates to citizen wellbeing, using both unsupervised and supervised learning methods.

## Overview

The goal of this project is to uncover patterns in governance and their relationship to social and economic factors contributing to happiness. Using governance-related indicators such as **Democratic Quality**, **Delivery Quality**, **Confidence in National Government**, and **Perceptions of Corruption**, countries are clustered into three distinct government types. These clusters are then predicted using happiness and wellbeing features including **GDP per capita**, **social support**, **healthy life expectancy**, **freedom to make life choices**, **generosity**, and **emotional affect measures**.

This project demonstrates:
- Data cleaning and exploratory data analysis (EDA),
- Clustering with K-Means to identify latent government types,
- Supervised modeling with Logistic Regression and Random Forest,
- Hyperparameter tuning with cross-validation,
- Visualization and interpretation of results to connect governance styles with wellbeing outcomes.

## Key Findings

- **Cluster 0 (High-Democracy, Strong Governance):** Highest GDP, social support, life expectancy, and positive affect.  
- **Cluster 1 (Moderate Governance, Corruption Challenges):** Mid-level wellbeing, highest negative affect, lower freedom.  
- **Cluster 2 (Low-Democracy, Weak Governance):** Lowest wellbeing across nearly all measures despite comparable freedom to Cluster 1.

The tuned Random Forest classifier performed best, with **GDP per capita, life expectancy, and social support** emerging as the strongest predictors of government type.

## Files

- `world_happiness_governance_clusters.ipynb`: Main notebook containing the full analysis, models, and results.
- Plots and visualizations are generated within the notebook.

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/TheShadowTiki/ml_portfolio_world_happiness_governance.git
   ```
2. Open the notebook in Jupyter:
   ```bash
   jupyter notebook world_happiness_governance_clusters.ipynb
   ```
3. Run the notebook to reproduce the analysis and results.

---

This project demonstrates end-to-end application of machine learning for data exploration, clustering, supervised modeling, and insight generation, and forms part of my Cornell Machine Learning portfolio.
