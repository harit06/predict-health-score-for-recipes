# 🥗 USDA Health Score Prediction

This project focuses on predicting USDA Health Scores for recipes using deep learning models, alongside comprehensive data analytics and visualizations. Built using PySpark for scalable data preprocessing and TensorFlow/Keras for model training, this pipeline explores the impact of data quality on prediction accuracy.

---

## 📌 Project Overview

- 🔍 **Goal**: Predict USDA Health Scores for recipes based on their ingredients and cuisine types.
- 📊 **Approach**: Analyze and clean the recipe dataset using PySpark, extract features, and train a Neural Network using TensorFlow/Keras.
- 📉 **Challenge**: The dataset (sourced from Harvard Dataverse) was significantly incomplete, especially in the ingredient listings, leading to reduced model accuracy.
- 🧼 **Solution**: Custom data cleaning pipelines were developed to handle missing and inconsistent data. Results showed improved prediction accuracy after rigorous preprocessing.

---

## 🧰 Tech Stack

- **Data Processing**: [Apache Spark (PySpark)](https://spark.apache.org/docs/latest/api/python/)
- **Machine Learning**: [TensorFlow](https://www.tensorflow.org/) + [Keras](https://keras.io/)
- **Visualization**: [Matplotlib](https://matplotlib.org/), [Seaborn](https://seaborn.pydata.org/)
- **Notebook Environment**: [Jupyter Notebooks](https://jupyter.org/)
- **Dataset Source**: [Harvard Dataverse](https://dataverse.harvard.edu/)

---

## 📈 Key Features

- ⚙️ Feature engineering from raw recipe data
- 🧪 Data cleaning and deduplication using Spark
- 🍽️ Ingredient-level and cuisine-level distribution plots
- 🧠 Deep Neural Network model to predict USDA scores
- 📉 Accuracy degradation analysis due to incomplete data
- 🔄 Pipeline to improve dataset consistency and model performance

---

## 📁 Getting Started

### Requirements

- Python 3.8+
- PySpark
- TensorFlow / Keras
- NumPy
- Matplotlib
