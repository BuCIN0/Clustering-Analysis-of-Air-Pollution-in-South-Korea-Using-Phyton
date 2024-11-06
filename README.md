# Clustering-Analysis-of-Air-Pollution-in-South-Korea-Using-Phyton
This project investigates air pollution patterns in South Korea by applying data clustering techniques, specifically K-Means and Agglomerative clustering. The goal is to categorize pollution levels and provide insights that can aid public health strategies and environmental management.

## Overview
Air pollution in South Korea, driven by industrialization, vehicular emissions, and transboundary dust, has raised significant public health concerns. This project uses real-world data to analyze pollution levels based on six key pollutants: PM2.5, PM10, O3, NO2, SO2, and CO. The study compares K-Means and Agglomerative clustering methods to determine which algorithm better captures the patterns within the data.

## Key Features
- Data Preparation and Cleaning: Extensive data preprocessing, including handling missing values, outlier removal, and normalization, ensures robust and consistent data input.
- Exploratory Data Analysis (EDA): Visualizes pollutant distribution and identifies correlations, providing insights into pollution trends and relationships between pollutants.
- Clustering Techniques: Uses K-Means and Agglomerative clustering to group pollution data. Optimal cluster numbers are determined through metrics such as the Silhouette Score and Davies-Bouldin Index.
- Model Evaluation: Evaluates model performance, finding that Agglomerative clustering yields better-defined clusters with a higher Silhouette Score and a more compact Calinski-Harabasz Index compared to K-Means.

## Results
The project finds that Agglomerative clustering is more effective than K-Means for this dataset, offering:
- A higher Silhouette Score (0.558), indicating well-defined clusters.
- A lower Davies-Bouldin Index (0.735), suggesting better inter-cluster separation.
- A higher Calinski-Harabasz Index (40242.397), confirming compact and distinct clusters.
These results indicate that Agglomerative clustering provides a more accurate categorization of pollution levels in South Korea, which could inform better health advisories and air quality monitoring strategies.

## Technologies and Tools
- Programming Language: Python
- Data Analysis and Machine Learning: Scikit-Learn
- Data Visualization: Matplotlib, Seaborn
- Notebook Environment: Jupyter Notebook

## Dataset
The dataset used for this analysis was sourced from Kaggle and includes pollution data for South Korea from 2013 to 2022. The features include:
- PM2.5 and PM10: Particulate matter levels, key indicators of air quality.
- O3 (Ozone), NO2 (Nitrogen Dioxide), SO2 (Sulfur Dioxide), and CO (Carbon Monoxide): Major pollutants associated with health risks.

## Methodology
The project follows the CRISP-DM framework:
- Business Understanding: Defines the goal of clustering pollution data for public health insights.
- Data Understanding: Analyzes the structure and characteristics of the data, handling missing values and outliers.
- Data Preparation: Preprocesses data through standardization for consistent feature scaling.
- Modeling: Tests K-Means and Agglomerative clustering models, tuning parameters for optimal cluster differentiation.
- Evaluation: Compares models using Silhouette Score, Davies-Bouldin Index, and Calinski-Harabasz Index to select the best-performing model.
- Deployment Recommendations: Suggests a monitoring system and mobile app to share real-time pollution data with the public.

## Conclusion
This analysis demonstrates that Agglomerative clustering is more effective for categorizing air pollution levels in South Korea, providing clusters that are dense, well-separated, and easily interpretable. The findings can support the development of targeted public health strategies to mitigate the impact of air pollution.
