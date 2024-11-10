# Credit-Card-Fraud-Dtetection

This project aims to detect fraudulent transactions in credit card data using anomaly detection techniques. Since fraudulent transactions are rare, this problem requires identifying outliers in the data, making it suitable for unsupervised learning methods like Isolation Forest and Local Outlier Factor.

**Project Overview**

Credit card fraud detection is a crucial application in financial security, where accurately identifying fraudulent transactions can protect users and financial institutions. This project explores a dataset of credit card transactions, applies data preprocessing and visualization, and builds a model to detect fraudulent activities.

**Project Workflow**

1. Import Libraries

The project utilizes:

pandas and numpy for data manipulation.


matplotlib and seaborn for visualization.

scikit-learn for implementing machine learning models and metrics.

2. Load and Explore the Dataset

The dataset includes credit card transactions labeled as either normal (0) or fraudulent (1). Initial steps involve:


Loading the dataset.

Sampling 10% of the data to improve processing time.

Checking data distribution and basic statistics.

3. Data Visualization

Visualize features to understand patterns and detect class imbalance:


Histograms: Displays the distribution of each feature.

Correlation Matrix: Shows correlations between features and highlights multicollinearity.

4. Identify Fraud Cases

Separate fraudulent and valid transactions to determine the outlier fraction—a measure of fraud instances relative to valid transactions.

5. Build the Model

This project applies two unsupervised outlier detection methods:


Isolation Forest: Effective for detecting anomalies by isolating observations.

Local Outlier Factor: Identifies anomalies based on the local density deviation of data points.

6. Evaluate the Model

Each model is evaluated using metrics such as:


Accuracy: The proportion of correctly classified transactions.

Classification Report: Provides precision, recall, and F1-score for fraud and valid classes.

Error Count: The number of misclassified transactions.
