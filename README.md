YouTube AdView Prediction
📌 Overview
This project aims to predict the number of ad views a YouTube video will receive based on various input features such as category, duration, likes, comments, and other metadata. The goal is to leverage machine learning techniques to develop a predictive model that can help advertisers optimize their ad performance.

📂 Dataset
The dataset consists of YouTube video metadata, including:

Video Category: The category under which the video is classified.
Duration: The length of the video.
Likes & Dislikes: User engagement metrics.
Comments: The number of comments on the video.
Views: The total number of views (used as the target variable for prediction).
Published Date: The date the video was uploaded.

🚀 Project Workflow
Data Preprocessing

Handling missing values.
Encoding categorical variables.
Feature scaling and transformation.
Exploratory Data Analysis (EDA)

Distribution analysis of numerical features.
Correlation analysis between features.
Identifying outliers and patterns.
Model Training & Evaluation

Splitting the dataset into training and testing sets.
Training regression models such as:
Linear Regression
Random Forest Regressor
Gradient Boosting Regressor
Evaluating models using metrics like RMSE, R², and MAE.
Hyperparameter Tuning
