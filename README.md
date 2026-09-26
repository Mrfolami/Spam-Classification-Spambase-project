The project focuses on analysing the Spambase dataset, preparing high‑dimensional data for machine learning, and applying PCA to reduce dimensionality while retaining 99.5% variance.

Project Overview
The Spambase dataset contains real‑world email features labelled as spam or not spam.
This project uses Python (Jupyter Notebook) to:

Characterize the dataset

Clean and prepare high‑dimensional data

Perform exploratory data analysis (EDA)

Apply PCA to reduce dimensionality

Explain the curse of dimensionality

Prepare the dataset for ML classification

All analysis and documentation are completed in Jupyter Markdown.

Dataset Characterization
The project includes a detailed breakdown of:

Number of observations

Number of attributes

Presence/absence of missing values

Feature types and distributions

Implications of dataset size and dimensionality

This characterization guides the preparation and PCA strategy.

Data Preparation & EDA
The notebook implements:

Cleaning and renaming

Handling missing values

Scaling and normalization

Multiple EDA visualizations

Rationale for each preparation step

Visualizations highlight feature behaviour, correlations, and spam vs non‑spam patterns.

Principal Component Analysis (PCA)
The PCA section includes:

Variance retention analysis

Identification of minimum components for 99.5% variance

Dimensionality reduction

Interpretation of PCA results

Discussion of how PCA improves ML performance

Curse of Dimensionality
The project explains:

What the curse of dimensionality means

Why high‑dimensional data becomes sparse

How it affects distance‑based algorithms

Why dimensionality reduction is essential for this dataset

Technologies Used
Python

Pandas

NumPy

Matplotlib / Seaborn

Scikit‑learn (PCA)

Jupyter Notebook (.ipynb)
