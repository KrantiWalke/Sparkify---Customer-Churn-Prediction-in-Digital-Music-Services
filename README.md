# Sparkify - Customer Churn Prediction in Digital Music Services with Spark

## Table of Contents
- [Project Motivation](#project-motivation)
- [Summary of Results](#summary-of-results)
- [Libraries and Dependencies](#libraries-and-dependencies)
- [File Structure](#file-structure)
- [Credits](#credits)

## Project Motivation
The purpose of this project is to tackle the issue of customer churn at Sparkify, a digital music service akin to Spotify and Pandora. Understanding and predicting customer churn is vital for maintaining a stable and growing user base in subscription-based services. By analyzing user activity and engagement data, this project seeks to identify key indicators and patterns that signal a high likelihood of churn, thereby enabling targeted customer retention strategies.

## Summary of Results
The project involved applying various machine learning models, such as Logistic Regression, Random Forest, Gradient Boosting, and Decision Tree, to predict customer churn. Given the imbalanced nature of the dataset, with fewer instances of churn, the models were evaluated based on both accuracy and the F1-score, with a higher emphasis on the latter. Gradient Boosting emerged as the top-performing model in terms of both metrics, even after hyperparameter tuning. Analysis of feature importance revealed that user interaction metrics, such as the number of page visits and total listening time, were critical in predicting churn.

For a more in-depth discussion and analysis, check out the accompanying Medium article: [Link to Medium Article]

## Libraries and Dependencies
This project utilizes the following libraries and frameworks:
- Python 3.5 or higher
- Spark for large-scale data processing
- Pandas for data manipulation
- NumPy for numerical operations
- Matplotlib for data visualization
- scikit-learn for machine learning models
- pyspark.sql for Spark SQL operations
- pyspark.ml for Spark's machine learning library
![](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![](https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apache-spark&logoColor=white)
![](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=matplotlib&logoColor=white)
![](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![](https://img.shields.io/badge/pyspark.sql-FFCA28?style=for-the-badge&logo=apache-spark&logoColor=black)
![](https://img.shields.io/badge/pyspark.ml-FFCA28?style=for-the-badge&logo=apache-spark&logoColor=black)

## File Structure
- `Sparkify-Churn Prediction.ipynb`: The main Jupyter notebook containing the Spark implementation for the churn prediction analysis.
- `images/`: A folder containing various charts and images utilized in the notebooks.

## Credits
Special thanks to:
- [Udacity](https://www.udacity.com/) for providing the educational platform and dataset for this project.
- Various online resources such as [KDnuggets](https://www.kdnuggets.com/2019/05/churn-prediction-machine-learning.html) for insights into churn prediction methodologies.
- [Analytics Vidhya](https://medium.com/analytics-vidhya/introduction-to-the-gradient-boosting-algorithm-c25c653f826b) for a comprehensive introduction to Gradient Boosting algorithms.
