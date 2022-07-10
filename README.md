# Cryptocurrencies Analysis
## Overview
---
Our stakeholder, Martha is a senior manager for the Advisory Services Team at Accountability Accounting, one of our most important clients. Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. So, they’ve asked us to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

The data we will be working with is not ideal, so it will need to be processed to fit the machine learning models. Since there is no known output for what we is looking for, therefore, we will be using unsupervised learning. To group the cryptocurrencies, we have decided on a clustering algorithm. We’ll use data visualizations to share  findings with the board.


## Results
We have done following for this analysis
- Preprocessing of data for PCA
- Dimensionality Reduction using PCA
- K-means clustering for cryptocurrencies
- Data Visualization for effective communication

### Preprocessing of data for PCA
Only Trading currencies were kept and target variable was removed. Currencies with `null` data were excluded before PCA.

### Dimensionality Reduction using PCA
4 features were reduced to three principle comopoents to decrease complexity.

### K-means clustering for cryptocurrencies
For unsupervised learning, we are using `K-mean` clustering algorithm. We used elbow method to determine meaningful `k` value. 

### Data visualization for explainability
Suitable visualizations are built to showcase PCA 3D Cluster view.