# 💧 Water Quality Analysis and Potability Prediction

This project analyzes water quality data and predicts whether water is potable (safe to drink) using machine learning models such as Decision Tree and Random Forest. It includes exploratory data analysis, data visualization, and model evaluation.

## 📁 Project Structure

water-quality-analysis/
│
├── water_analysis.ipynb # Main notebook for analysis and modeling
├── water_potability.csv # Dataset used for analysis


## 📊 Dataset

- **Name:** `water_potability.csv`
- **Source:** [Kaggle - Water Quality Dataset](https://www.kaggle.com/datasets/adityakadiwal/water-potability)
- **Features:**
  - pH
  - Hardness
  - Solids
  - Chloramines
  - Sulfate
  - Conductivity
  - Organic_carbon
  - Trihalomethanes
  - Turbidity
  - Potability (target variable)

## 📌 Features Implemented

- Exploratory Data Analysis with `seaborn`, `matplotlib`, `plotly`
- Missing value visualization with `missingno`
- Data preprocessing and splitting
- Classification using:
  - Decision Tree Classifier
  - Random Forest Classifier with hyperparameter tuning
- Performance metrics: Confusion Matrix, Precision Score


