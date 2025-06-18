🛍️ E-commerce Data Analysis using Machine Learning
📌 Project Overview
This capstone project showcases an end-to-end Data Science pipeline applied to real-world e-commerce product data. The objective is to uncover valuable insights, segment products, and build predictive models to assist businesses in optimizing their product offerings, pricing strategies, and targeted marketing.

🔍 Problem Statement
As a data analyst in a growing e-commerce company, you are tasked with leveraging data science and machine learning to:

Understand customer preferences and product trends.

Cluster similar products to enhance recommendation systems.

Predict product categories or performance indicators based on features.

🚀 Project Workflow
1️⃣ Web Scraping
Extracted structured product data from an e-commerce platform using Python's BeautifulSoup/Scrapy:

Features: Product Name, Price, Category, Ratings, Number of Reviews

Exported to a .csv file for downstream analysis.

2️⃣ Data Cleaning & EDA
Performed thorough preprocessing using pandas:

Handled missing values, duplicates, and inconsistent formatting.

Conducted Exploratory Data Analysis (EDA) with Matplotlib and Seaborn to reveal trends in pricing, ratings, and review distributions.

3️⃣ Data Storage
Loaded the cleaned dataset into a SQL database using SQLAlchemy, ensuring scalable and structured storage for future retrieval and analysis.

4️⃣ Unsupervised Learning – Product Clustering
Applied K-Means Clustering to segment products based on pricing, reviews, and ratings:

Determined the optimal number of clusters using the elbow method.

Added cluster labels to the dataset to identify product groupings.

5️⃣ Supervised Learning – Category Prediction
Built classification models to predict product categories:

Algorithms used: Logistic Regression, SVM, KNN, Random Forest, XGBoost

Evaluated models using Accuracy, F1 Score, and Confusion Matrix

6️⃣ Hyperparameter Tuning
Utilized GridSearchCV and RandomizedSearchCV to fine-tune the top models, optimizing performance and improving prediction accuracy.

