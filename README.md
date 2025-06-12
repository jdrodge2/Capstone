# 🧠 Predicting Traffic Accident Severity in Montgomery County, MD: A Data Science Capstone Project

This project was completed as part of a graduate-level data science program. It focuses on predicting driver injury severity, driver vehicle damage extent, and number of indivuals involved, using real-world data. The work covers the full data science pipeline—from data cleaning and exploratory analysis to machine learning modeling and evaluation.

📄 A full 73-page project report is available [here](https://github.com/jdrodge2/Capstone/blob/master/Final%20Manuscript%20-%20Jacob%20Rodgers.pdf).

---

## 📦 Project Structure
Notebooks:
- `data_cleaning_v2.ipynb`: Raw data wrangling, geospatial transformation, and preprocessing
- `Target_1_Models_v2.ipynb`: Modeling, training, and evaluation for Target 1
- `Target_2_Models.ipynb`: Modeling, training, and evaluation for Target 2
- `Target_3_Models_v2.ipynb`: Modeling, training, and evaluation for Target 3

---

## 🔍 Problem Statement

The objective of this project is to predict:
- **Target 1**: Driver Injury Severity (No Injury, Possible or Minior, Serious or Fatal)
- **Target 2**: Vehicle Damage Extent (No Damage or Superficial, Functional, Destroyed or Disabled) & (Drivable, Not Drivable)
- **Target 3**: Number of People Involved (1, 2, 3, 4 or more)

The dataset includes 170,000+ records with variables related to locations, time, weather/road conditions, driver/vehicle information, etc.. The task involves classification & regressions to support whether accident severity can be predicted and then likely prevented.

---

## 🛠️ Tools & Libraries

- `Python`, `Jupyter Notebooks` for environment
- `pandas`, `NumPy`, `plotly`, `matplotlib`, `seaborn` for data cleaning and visualizations
- `xgboost`, `scikit-learn` for machine learning and modeling
- `geopandas`, `shapely` for geospatial analysis
- `fuzzywuzzy` for text matching
- `scipy` for statistical testing

---

## 📊 Highlights & Key Techniques

- 🧹 Cleaned and processed over [170,000] features using custom functions
- 📌 Handled geospatial data and plotted interactive maps with Plotly & GeoPandas
- 🔍 Used fuzzy matching to reconcile inconsistent text entries
- 🤖 Built classification models including Logistic Regression, Random Forest, Naive Bayes and XGBoost
- 📈 Evaluated models using AUC, precision/recall, and confusion matrices
- 🧪 Applied statistical testing to support feature selection and interpretation

---

## 📉 Model Performance Summary

Most models performed between .75 and 0.80 for Accuracy and Weighted F1 metrics across all three target variables. For more detailed insight on model performances, please start by referencing [page 48 of the project report](https://github.com/jdrodge2/Capstone/blob/master/Final%20Manuscript%20-%20Jacob%20Rodgers.pdf)

---

## 📎 Full Report

For detailed analysis, visualizations, and discussion:
📄 [Click here to view the full 73-page project report](https://github.com/jdrodge2/Capstone/blob/master/Final%20Manuscript%20-%20Jacob%20Rodgers.pdf)

---

## ✅ Future Work

- Expand Geographic Scope: Broaden the dataset to include traffic accident records from all of Maryland or the northeastern U.S. to increase the diversity and size of observations, especially for underrepresented classes like fatal injuries.
- Deploy Models in Production: Containerize the top-performing models using Docker to support real-time severity predictions for new accident data in operational environments.
- Conduct Post-Training Feature Impact Analysis: Use feature ablation techniques to evaluate which variables most influence model outcomes—enabling stakeholders to simulate interventions and align predictions with public safety goals.

---

## 📬 Contact

*Created by Jacob Rodgers as part of the Data Science Master's Program.*  
Connect with me on [LinkedIn](https://www.linkedin.com/in/jacobrodgerstech/) or explore more at my [GitHub](https://github.com/jdrodge2).

