DATA-SCIENCE_PROJECT-2

Cyber-Security Network Intrusion Detection System.

Business objective : The research in the intrusion detection field has been mostly focused on anomaly-based and misuse-based detection techniques for a long time. While misuse-based detection is generally favored in commercial products due to its predictability and high accuracy, in academic research anomaly detection is typically conceived as a more powerful method due to its theoretical potential for addressing novel attacks.

Solution for data pipelines.

1)  Import packages which are essentialk then read respective data files.
2)  There are total 11 data files from that only one file is NORMAL and rest are ATTACK files. Set target feature of Normal to '0' and target feature of Attacks to '1'
3)  After that concat all data files into one dataframe by using pd.concat().
4)  Employ undersampling strategy onto the dataset since dataset is imbalaced.
5)  Exploratory Data Analysis - Identify the relationship between target feature and other continuous features.
6)  Drop the feature based on the data audit report - drop the feature whose value is near zero variance, highly missing, highly correaled and using business logic.
7)  After statistical analysis now it's times to seperate continuous and categorical data.
8)  To determine correlation of each variable with target variable we need to generate Heatmap.
9)  Split the data into train & test datasets. 
10) Now employ feature engineering process to reduce/select required features to process the data further.
11) We used Variance Inflation Factor technique to detect multicoliinearity in the ordinary least squared regression analysis.
12) Apply Logistic Regression - applied two approaches 
    a. Traditional approach - Overall accuracy for train data = 49%
    b. SKlearn method - Overall accuracy for train data = 96%
    For both the methods a classification report is generated. 
13) Machine Learning algorithm is applied for better precision, accuracy and recall. 
    a. Decision Tree Algorithm - Fine tuning parameters, feature importance, visualize the decision tree using graphViz package
    b. Random Forest - visualize the relative importance of features using barplot, tuning parameters.
