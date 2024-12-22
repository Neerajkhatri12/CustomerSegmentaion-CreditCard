Customer Segmentation of Credit Card Users

Project Overview

This project focuses on customer segmentation using a dataset of credit card users. The goal is to group customers based on their spending behavior and patterns to derive actionable insights. Businesses can use this segmentation to improve customer targeting, optimize resources, and design tailored marketing strategies.
Key Objectives
Perform Exploratory Data Analysis (EDA) to uncover trends and outliers in the dataset.
Preprocess the data to prepare it for clustering algorithms.
Apply the DBSCAN clustering algorithm to identify distinct customer segments.

Project Structure
This repository contains the following files:

EDA.ipynb

Contains the Exploratory Data Analysis process.
Visualizes data distribution, trends, and outliers.
Provides insights into potential segmentation patterns.
Preprocessing.ipynb

Focuses on cleaning and transforming the raw data.
Handles missing values, scales numerical features, and encodes categorical variables.
Prepares the dataset for clustering analysis.
DBSCAN_Clustering.ipynb

Implements the DBSCAN clustering algorithm.
Evaluates clustering results and visualizes customer groups.
Discusses the significance of each segment and its potential business applications.

Key Techniques and Tools

Libraries Used:

Pandas

NumPy

Matplotlib

Scikit-learn

Clustering Algorithm:
DBSCAN (Density-Based Spatial Clustering of Applications with Noise)
How to Use
Clone the repository:
git clone <repository_link>
Open the notebooks in Jupyter Notebook or JupyterLab.
Execute the notebooks in the following order:
EDA.ipynb
Preprocessing.ipynb
DBSCAN_Clustering.ipynb
Explore the results and adapt the code for your dataset.
Key Insights
Segmented customers into groups based on their credit card usage patterns.
Identified distinct customer profiles such as high spenders, low spenders, and occasional users.
DBSCAN effectively handled noise and identified clusters of varying densities.
Applications
Targeted marketing strategies.
Personalized customer experiences.
Better allocation of marketing and operational resources.
