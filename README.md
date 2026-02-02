# Bank Customer Churn Analysis Using Orange Data Mining (OWS)

# Problem Statement:

Customer churn is a significant concern for banks offering credit card services, as retaining existing customers is more cost-effective than acquiring new ones. In this project, I have addressed the customer churn problem for a hypothetical bank by analyzing credit card customers data to understand engagement patterns and customer behaviour. After understanding customer segments and behavior patterns, the next problem is to identify which customers are becoming less engaged and may leave in the near future, so the bank can act early.

Among all the customers who are about to churn, bank operators should not take the same measures for every single customer. That's because not all customers are of high value. In that sense, bank operators should allocate more resources to retain high-value customers. 

# Data Mining Techniques Used:
Association mining: It identifies pattern within large dataset to predict customer churn.

For Example: Low engagement + High months inactive --> More likely to Churn. 

Clustering: It segments customers into similar groups based on their spending behaviour. 

Regression (or) Prediction: It forecast the customers likelihood to churn.

# Exploratory Data Analysis

STEP 1: Data Cleaning: Drop useless columns, check for missing values, remove duplicated.

STEP 2: Conduct Exploratory Analysis 

Insights: 
- Age: The average age of customers is 46 years.
- Dependents: On average, each client has 2 dependents
- Months innactive on the last year: On average, customers have been inactive for 2 months in the last year.
- Credit limit: The average credit limit for customers is $8631.
- The majority of the customer base is composed of women who have a higher education, are married, and earn less than $40,000 per year.

# Data Preparation

STEP 1: Categorial encoding - To convert categorical data into numerical data

STEP 2: Split the data into train and test

# Churn Prediction

STEP 1: Several classifiers were used like Logistic Regression (used as a baseline), Decision Tree, Random Forest, and XGBoost. 

STEP 2: The training set was used for model training, while the test set was used for evaluating the performance of the models.

STEP 3: In order to evaluate the performance of the classifiers - accuracy, precision, recall, and F1-scores are measured.

STEP 4: After comparing the performance of multiple machine-learning classifiers, XGBoost is selected as the best model based on its higher recall score.

# Customer segmentation 

K-Means clustering was used to cluster the customers, and the elbow technique was applied to decide the appropriate number of clusters to use

<img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/6c87dd4d-bc83-4100-89f8-817f3f3d8022" />

# Business Implication: 

Keeping an existing customer costs is much less than finding a new one. If the bank can identify and engage customers early, it can reduce revenue loss, lower customer acquistion cost and improve long-term customer value. Even a small reduction in churn can lead to significant revenue savings because retained customers continue to generate income over time.

