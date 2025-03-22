# Wine-Recognition-Data-Analysis
This project aims to classify different types of wine using machine learning, specifically the K-Nearest Neighbors (KNN) algorithm. The project utilizes the Wine dataset from the UCI Machine Learning Repository.<br>


1. Data Loading and Preprocessing:
The Wine dataset is loaded into a Pandas DataFrame.
Categorical features are converted to numerical values using Label Encoding.
Data is checked for missing values and duplicates.
Descriptive statistics are generated to understand the data distribution.
Outliers are identified and removed for better model performance.<br>

2. Exploratory Data Analysis (EDA):
Feature correlation is visualized using a heatmap.
Pair plots and box plots are used to explore relationships between features and classes.
Violin plots are used to analyze the distribution of specific features across different wine classes.<br>

3. Model Building and Evaluation:
The dataset is split into training and testing sets.
Features are scaled using StandardScaler for better KNN performance.
A KNN classifier is trained using the training data.<br>

The model's performance is evaluated using accuracy, classification report, and confusion matrix metrics.<br>

Dataset Link: https://archive.ics.uci.edu/ml/machine-learning-databases/wine/wine.data

Feel free to download the code and data.
