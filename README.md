# Module-19-Challenge Neural_Network_Charity_Analysis
# Overview of Project #
The purpose of this Project is to create a report that includes which cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment, so that they can help the customers by offering a new cryptocurrency investment portfolio.The data need to be processed to fit the machine learning models by using unsupervised learning.To group the cryptocurrencies,clustering algorithm is used.

The analysis consisted of the following:
1. Preprocessing the Data for PCA.
2. Reducing Data Dimensions Using PCA.
3. Clustering Cryptocurrencies Using K-means.
4. Visualizing Cryptocurrencies Results.

# Resources #
Software: Jupyter Notebook <br>
Libraries: numpy, pandas, plotly, scikit-learn,hvplot,<br>
Data Sources: crypto_data.csv

# Results #
### Preprocessing the Data for PCAs ###
- The **crypto_df** DataFrame, We perfrom certain steps to preprocessing the data.<br>

![crypto_df](/Image/crypto_df.png)<br>

- After that, Standardize the data with StandardScaler() to removing the mean and scaling to unit variance.<br>

![Standard](/Image/Standard.png)<br>

### Reducing Data Dimensions Using PCA ###
- PCA is a statistical technique to speed up machine learning algorithms when the number of input features (or dimensions) is too high. PCA reduces the number of dimensions by transforming a large set of variables into a smaller one that contains most of the information in the original large set.<br>

![PCA](/Image/PCA.png)

### Clustering Cryptocurrencies Using K-means ###
- K-means is an unsupervised learning algorithm used to identify and solve clustering issues. Done creating a new **clustered_df** DataFrame.<br>

![clustered_df](/Image/clustered_df.png)<br>

- Elbow curve is used etermine optimal value of k.we conclude that the optimal number of clusters for the data is 4.<br>

![Elbow](/Image/Elbow.png)<br>

### Visualizing Cryptocurrencies Results ###
- scatter_3d plots represents individual data in three-dimensional space.<br>

![3D-Scatter](/Image/3D-Scatter.png)<br>

