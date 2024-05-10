# CryptoClustering: Unsupervised Learning with Cryptocurrency Data

## Project Overview

This project involves using Python and unsupervised learning techniques to predict how cryptocurrencies are affected by 24-hour or 7-day price changes. The analysis is divided into several parts: data preprocessing, clustering using K-means algorithm, and comparing clustering results with original data and PCA data.

## Project Structure

### Part 1: Data Preparation
- **Crypto_Clustering.ipynb:** Jupyter notebook for data preprocessing, clustering, and analysis.
  - Load the `crypto_market_data.csv` into a DataFrame.
  - Explore and visualize the cryptocurrency market data to understand its structure and distribution.
  - Use StandardScaler() from scikit-learn to normalize the data.

### Part 2: Elbow Method and K-means Clustering
- **Crypto_Clustering.ipynb:** Jupyter notebook continuation for clustering analysis.
  - Perform the elbow method to find the optimal k value for K-means clustering using the original scaled data.
  - Cluster cryptocurrencies using K-means algorithm with the best k value from the previous step.

### Part 3: PCA and K-means Clustering
- **Crypto_Clustering.ipynb:** Jupyter notebook continuation for PCA and clustering analysis.
  - Conduct Principal Component Analysis (PCA) on the original scaled data to reduce dimensionality.
  - Find the best k value using the elbow method on the PCA data and cluster cryptocurrencies using K-means on the PCA data.

## Repository Structure

The repository is structured as follows:

- **README.md:** Overview of the project, its structure, and usage instructions.

- **Crypto_Clustering.ipynb:** Jupyter notebook containing Python code for the project.
  
- **Resources/:**
  - `crypto_market_data.csv`: CSV file containing cryptocurrency market data.

- **.gitignore:** File to exclude sensitive files and folders like API keys or cache files from version control.

## Tools Used

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Scikit-learn

## Conclusion
This project showcases the application of unsupervised learning techniques, such as K-means clustering and Principal Component Analysis (PCA), to analyze cryptocurrency market data. By following the steps outlined in the Jupyter notebook, users can gain insights into how cryptocurrencies behave in terms of price changes over different time periods.
