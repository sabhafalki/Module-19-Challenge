# Module-19-Challenge Neural_Network_Charity_Analysis
# Overview of Project #
The purpose of this Project is to deep-learning neural networks to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. The Alphabet Soup  is a charitable foundation, through this analysis the foundation want to know which organization is worth donating and which are to high risk with help of the given data.

The analysis consisted of the following:
1. Preprocessing the data for the neural network model.
2. Compile, train and evaluate the model.
3. Optimize the model.


# Resources #
Software: Jupyter Notebook,Python 3.7.3, Anaconda 4.8.3, TensorFlow 2.3.1<br>
Libraries: pandas, plotly, scikit-learn,hvplot,<br>
Data Sources: charity_data.csv

# Results #
### Preprocessing the Data ###
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

