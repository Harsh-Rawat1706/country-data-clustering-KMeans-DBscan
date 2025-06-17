🌍## Country Data Clustering with KMeans and DBSCAN
##This project focuses on clustering countries based on socio-economic indicators such as child mortality, GDP per capita (gdpp), and import percentage. The goal is to explore patterns among countries using KMeans and DBSCAN clustering techniques.

This project focuses on clustering countries based on socio-economic indicators such as child mortality, GDP per capita (gdpp), and import percentage. The goal is to explore patterns among countries using KMeans and DBSCAN clustering techniques.
📊 Project Overview
Objectives
Preprocess and clean the country data.

Visualize relationships between key indicators.

Apply KMeans clustering using the Elbow Method.

Apply DBSCAN clustering and evaluate using Silhouette Score.

Summarize clustering results for analysis.

🧹 Data Preprocessing
Selected relevant features:

child_mortality

gdpp (GDP per capita)

import (percentage of imports)

Handled missing values and normalized the data.

Final dataset prepared for clustering.

📈 Exploratory Data Analysis
Scatter Plots:

child_mortality vs. gdpp

child_mortality vs. import

These visualizations help understand the initial distribution and relationships among features.

🧠 Clustering Algorithms
1. KMeans Clustering
Applied Elbow Method to determine the optimal number of clusters.

Visualized clusters with 2D scatter plots.

Interpreted cluster characteristics.

2. DBSCAN Clustering
Used Silhouette Score to find optimal parameters.

Identified noise points and meaningful clusters.

Compared results with KMeans clusters.

📋 Results Summary
Created summary DataFrames showing:

Number of countries in each cluster

Average values for key indicators per cluster

Cluster characteristics and interpretations

