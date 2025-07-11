# iris-flower
To build a basic classification model that predicts the species of an iris flower based on features like petal length, petal width, sepal length, and sepal width.
Steps Performed:
1.Import the Dataset
Load the Iris dataset using sklearn.datasets.

2.Convert to DataFrame
Transform into a pandas DataFrame for easier handling and analysis.

3.Exploratory Data Analysis (EDA)

Display the first few rows.

Use Seaborn to create pairplots.

Plot histograms to visualize feature distribution.

4.Data Splitting
Split the dataset into training and testing sets using train_test_split.

5.Model Training with KNN
Train a KNeighborsClassifier with k=3 initially.
Try different values of k (1 to 10) to compare performance.

6.Model Evaluation

Predict test set results.

Calculate accuracy score.

Display confusion matrix using heatmap.
