# Bioinformatics Drug Discovery using Machine Learning

This project focuses on applying machine learning techniques in the field of bioinformatics to aid in drug discovery. The project involves collecting and preprocessing bioactivity data from the ChEMBL database, as well as the computation of molecular descriptors using the Padel Descriptor software. The collected dataset is then used to build regression models for predicting the potency of compounds against a target protein, specifically acetylcholine esterase.

## Key Features:
- **Data Collection:** The project demonstrates how to retrieve bioactivity data from the ChEMBL database using Python, utilizing the ChEMBL web resource client library.
- **Data Preprocessing:** The collected bioactivity data is preprocessed to handle missing values, label compounds, and calculate molecular descriptors.
- **Exploratory Data Analysis:** The project covers exploratory data analysis techniques using visualizations and statistical analysis, providing insights into the dataset.
- **Model Building:** Several machine learning algorithms, such as Random Forest, are built and compared for their predictive performance using the lazy predict library.

## Tools & Libraries:
- **Pandas:** Data manipulation and analysis.
- **Scikit-learn:** The library is used for machine learning tasks, including model building and evaluation.
- **Padel Descriptor:** A software used for calculating molecular descriptors based on the provided SMILES notation of compounds.
- **Seaborn and Matplotlib:** These libraries are used for data visualization.
