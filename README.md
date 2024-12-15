# Membrane Performance Analysis and Clustering

## Introduction

This project aims to analyze the performance of reverse osmosis (RO) membranes and group them into clusters based on their characteristics and performance metrics. The project uses a dataset of RO membrane properties and performance data to perform data preprocessing, exploratory data analysis (EDA), and clustering using the K-Means algorithm.

## Dataset

The dataset used in this project is `OMD_RO_2022-11-07.csv`, which contains information about various RO membranes, including their structure, chemistry, modification, operating conditions, and performance metrics such as water permeability coefficient, solute permeability coefficient, real rejection, and observed rejection.

## Project Workflow

The project follows the following steps:

1. **Data Preprocessing:**
   - Cleaning column names
   - Removing irrelevant columns
   - Handling missing values
   - Performing label encoding for categorical variables
   - Creating new features (e.g., pressure difference)
   - Removing outliers

2. **Exploratory Data Analysis (EDA):**
   - Visualizing data distributions using histograms and box plots
   - Exploring relationships between variables using scatter plots
   - Identifying correlations between features using heatmaps

3. **Clustering:**
   - Applying the K-Means algorithm to group membranes into clusters
   - Evaluating cluster quality using inertia and silhouette score
   - Visualizing clusters using PaCMAP

4. **Cluster Profiling:**
   - Analyzing the characteristics of each cluster based on membrane properties and performance metrics
   - Identifying key features that differentiate clusters

## Requirements

- Python 3
- Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn, pacmap

## Usage

1. Install the required libraries using `pip install pandas numpy seaborn matplotlib scikit-learn pacmap`.
2. Upload the dataset `OMD_RO_2022-11-07.csv` to your Google Colab environment.
3. Run the code cells in the provided Jupyter Notebook to execute the data preprocessing, EDA, clustering, and cluster profiling steps.

## Results

The project identifies the optimal number of clusters for different clustering scenarios (based on input features, output features, and all features). It provides insights into the performance of RO membranes and their relationships with various properties. The cluster profiling results help understand the characteristics of each cluster, enabling researchers to gain a better understanding of membrane behavior and potentially design more efficient RO systems.

## Future Work

- Explore other clustering algorithms (e.g., hierarchical clustering, DBSCAN) to compare their performance.
- Develop a user interface for interactive cluster exploration and analysis.
- Apply machine learning models to predict membrane performance based on their characteristics.
