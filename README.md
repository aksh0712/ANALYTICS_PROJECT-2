DATA-SCIENCE_PROJECT-2

Cyber-Security Network Intrusion Detection System.

Business objective: The research in the intrusion detection field has been mostly focused on anomaly-based and misuse-based detection techniques for a long time. While misuse-based detection is generally favored in commercial products due to its predictability and high accuracy, in academic research anomaly detection is typically conceived as a more powerful method due to its theoretical potential for addressing novel attacks.

Solution for data pipelines.

1)  essential Import packages then read respective data files.
2)  There are a total of 11 data files from that only one file is NORMAL and the rest are ATTACK files. Set the target feature of Normal to '0' and the target feature of Attacks to '1'
3)  After that concat all data files into one data frame by using pd.concat().
4)  Employ an undersampling strategy onto the dataset since the dataset is imbalanced.
5)  Exploratory Data Analysis - Identify the relationship between the target feature and other continuous features.
6)  Drop the feature based on the data audit report - drop the feature whose value is near zero variance, highly missing, highly correlated, and using business logic.
7)  After statistical analysis now it's time to separate continuous and categorical data.
8)  To determine the correlation of each variable with the target variable we need to generate a heat map.
9)  Split the data into train & test datasets. 
10) Now employ a feature engineering process to reduce/select required features to process the data further.
11) We used the Variance Inflation Factor technique to detect multicollinearity in the ordinary least-squared regression analysis.
12) Apply Logistic Regression - applied two approaches 
    a. Traditional approach - Overall accuracy for train data = 49%
    b. SKlearn method - Overall accuracy for train data = 96%
    For both methods, a classification report is generated. 
13) A Machine Learning algorithm is applied for better precision, accuracy, and recall. 
    a. Decision Tree Algorithm - Fine tuning parameters, feature importance, visualize the decision tree using GraphViz package
    b. Random Forest - visualize the relative importance of features using barplot, and tuning parameters.
