📱 Smartphone Price Prediction & Feature Analysis
This project explores a dataset of smartphone specifications to understand what features influence pricing. It includes exploratory data analysis (EDA), feature engineering, visualization, and machine learning models to predict smartphone prices.

🔍 Project Objectives
Understand relationships between smartphone features and price

Visualize key trends (e.g. RAM vs Price, Brand vs Price)

Build predictive models (Linear Regression, Decision Tree Regressor)

Identify important features using feature selection methods

📁 Dataset
Source: Kaggle (Smartphone Specifications & Prices)

Features include: brand, model, RAM, internal memory, battery, camera specs, 5G, NFC, etc.

Target variable: Price

🛠️ Key Steps
✅ Data Cleaning & Preparation
Handled missing values

Converted units (e.g., GB, mAh)

Created new features like Price_per_GB

📊 Exploratory Data Analysis (EDA)
Histograms, boxplots, scatterplots, and heatmaps

Grouped data by brand and RAM

Analyzed trends using Seaborn visualizations

🧠 Machine Learning
Train-test split (80/20)

Standardized features using StandardScaler

Trained models:

Linear Regression

Decision Tree Regressor

🏆 Feature Selection
Used SelectKBest with f_regression

Visualized top contributing features

Interpreted model coefficients and importances

📈 Results
Found strong relationships between RAM, Storage, and Price

Decision Tree performed better than simple regression on this dataset

Top 3 features selected using SelectKBest

💾 Output & Visualizations
All key plots were saved using plt.savefig(), including:

Price distribution

Correlation heatmap

RAM vs Price

Brand comparison

Feature importance chart

📚 Tools & Libraries
Python

Pandas, NumPy

Seaborn, Matplotlib

Scikit-learn

🚀 How to Use
Clone this repo

Run the Jupyter notebook smartphone_analysis.ipynb

Install requirements if needed (pip install -r requirements.txt)

Explore the saved plots or modify the analysis for deeper insights
