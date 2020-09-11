# The SPARKS Foundation Repository
@ Author - Sandip Dutta

This repository is for storing code related to internship at The SPARKS Foundation
1. **Student_data (TASK - 1)** - This folder contains data for some students. Task is to predict whether score increases if number of hours of study increases. We performed EDA and fitted a linear Regression model for this data. The accuracy came to be about 95 % based on r2 score metric.

2. **iris_Unsupervised (TASK - 2)** - This folder is for the iris data analysis using KMeans and DBSCAN algorithm. First plots were generated and features visualised. Then DBSCAN was applied and we got the optimum number of clusters as 3. Then we shifted to K Means(after scaling the data). We determined the ideal number of clusters using elbow method and it too came out to be 3. Lastly, we plotted a confusion matrix to see the classification.

3. **Decision Tree (TASK - 3)** - In this task we were to explore Decision Tree Algorithm using sklearn on IRIS dataset. First we splitted the data into train and validation part. Then we fitted a `DecisionTreeClassifier` on the dataset. For visulaising it, we used matplotlib. Then we plotted decision surfaces for two features and checked the accuracy of the model. Decision tree gave a good f1-score(near to 1.00).

4. **Business Analytics (TASK - 4)** - In this *final task*,  we were to analyse a business data. First, The data was analysed using pandas. Then EDA was performed using Seaborn and Matplotlib. Next We did some Hypothesis tests like `chi2_contingency` and `kendalltau` using `scipy.stats`. Finally we fitted a `RidgeRegression` model from sklearn. The final accuracy came to about 0.995.
