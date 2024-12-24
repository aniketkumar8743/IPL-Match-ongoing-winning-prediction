# IPL Match Analysis and Winning Probability Prediction 🏏
This repository contains a data-driven machine learning project that analyzes IPL (Indian Premier League) matches from 2008 to 2020. The project predicts the winning probability of ongoing matches using historical data and machine learning models.

## 📖 Overview
The IPL Match Prediction System leverages data from past IPL seasons (2008–2020) to predict match outcomes in real-time. With a 97% accuracy rate, the system forecasts the probable winning team based on current match conditions and provides a Graphical User Interface (GUI) for user-friendly interaction and real-time prediction.

## 🎯 Project Goals
Analyze IPL Matches (2008–2020):
Understand trends, team performance, and other critical metrics.
Build a Predictive Model:
Forecast match outcomes using machine learning.
Provide Real-Time Predictions:
Build a GUI to predict the winning probability of ongoing matches based on live inputs (e.g., score, wickets, overs, etc.).
## 📂 Dataset
The dataset includes:

Match details: Date, teams, venue, toss result, and match winner.
Batting statistics: Runs scored, wickets lost, balls faced, strike rates.
Bowling statistics: Overs bowled, runs conceded, wickets taken, economy rates.
Historical outcomes: Match results from IPL seasons 2008 to 2020.
## 🔍 Data Analysis
Trends in Team Performance:
Analyzed performance trends of teams across seasons.
Winning Factors:
Identified key factors like toss result, run rate, and powerplay performance influencing match outcomes.
Venue Insights:
Studied win probabilities based on venues and their characteristics.
## 🏗️ Model Architecture
Data Preprocessing:
Cleaned and transformed the data for feature extraction.
Encoded categorical variables (e.g., teams, venue).
Feature Engineering:
Included critical features like total runs, wickets, balls remaining, and net run rate.
Machine Learning Algorithms:
Tested various models, including Random Forest, Gradient Boosting, and XGBoost.
Achieved a 97% accuracy with the best-performing model.
Evaluation Metrics:
Used precision, recall, F1-score, and ROC-AUC to evaluate model performance.
## 🖥️ GUI for Real-Time Predictions
A simple and interactive Graphical User Interface (GUI) built with Python (Tkinter/Streamlit) allows users to:

Input real-time match data (e.g., current score, overs, wickets, etc.).
View the predicted winning probability for both teams.
🚀 Getting Started
Prerequisites
Python 3.x
Libraries:
pandas
numpy
scikit-learn
xgboost
matplotlib
streamlit
  
## 🧑‍💻 Usage
Analyze Historical Data:
Use the provided scripts to explore and visualize IPL match trends.
Predict Match Outcomes:
Input current match data into the GUI to view winning probabilities.
Customize the Model:
Modify the ML pipeline to experiment with new features or algorithms.
## 📊 Results
Achieved a 97% accuracy in predicting match outcomes.
Built a robust model that accounts for real-time match scenarios.
Insights from analysis help understand factors affecting team performance.

## 🤝 Contributing
Contributions are welcome! If you have ideas for improving the model or GUI, feel free to fork the repository and submit a pull request.


