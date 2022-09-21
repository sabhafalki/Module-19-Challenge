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
- The columns EIN and NAME are identification information and have been removed from the input data.
- The column IS_SUCCESSFUL contains binary data refering to weither or not the charity donation was used effectively. This variable is then considered as the target for our deep learning neural network.
- The following columns APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT are the features for our model.
- Encoding of the categorical variables, spliting into training and testing datasets and standardization have been applied to the features.

### Compiling, Training, and Evaluating the Model ###
- I selected 120 neurons with a sigmoid function for my first layer, 50 nuerons with a ReLU function for the second, and 18 neurons with for the third, and a sigmoid function for the outer layer. I chose to change the activation function for the first layer because it increased the model's performance.
- I only achieved an accuracy of 69% and was not able to achieve the target model performance.
- I tried to increase the model performance by dropping more columns, creating more bins for rare occurances in columns, decreasing the number of values in some bins, adding more neurons to the hidden layers, using a differnet activation function, and increasing the number of epochs.

### Summary ###
- The deep learning neural network model did not reach the target of 75% accuracy. Considering that this target level is pretty average we could say that the model is not outperforming.
- A random forest model could solve this classification problem by randomly sampling the preprocessed data and building several smaller, simpler decision trees. Some benefits of using a random forest model include how robust it is against overfitting of the data because all of the weak learners are trained on different pieces of the data, it can be used to rank the importance of input variables, it is robust to outliers and nonlinear data, and it can run efficiently on large datasets.
