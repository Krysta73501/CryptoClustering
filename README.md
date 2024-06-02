# CryptoClustering

# Introduction
This project focuses on clustering various cryptocurrencies based on their market data using machine learning techniques. The analysis includes data preprocessing, normalization, and the use of clustering algorithms to group cryptocurrencies together. The goal is to find patterns and trends in the cryptocurrency market.

# Usage
Load the Data: The dataset should be placed in the Resources directory and named crypto_market_data.csv.
Run the Notebook: Open the Jupyter notebook Crypto_Clustering.ipynb and execute the cells sequentially.

# Dependencies
pandas
hvplot
numpy
scikit-learn
matplotlib

# Documentation
Data Loading: The data is loaded into a Pandas DataFrame from a CSV file.
Normalization: Data is normalized using StandardScaler from scikit-learn.
KMeans Clustering: The optimal number of clusters is determined using the elbow method by plotting inertia values for different k-values.
PCA Visualization: PCA is used to reduce the dimensionality of the data for visualization purposes.

# Troubleshooting
Data File Not Found: Ensure that the crypto_market_data.csv file is in the Resources directory.
Module Not Found: Install missing dependencies using pip install.

# Contributors
Krysta Sharp

# Acknowledgements
This project was developed with the assistance of ChatGPT 3.5, an AI language model by OpenAI to help correct any coding errors .
