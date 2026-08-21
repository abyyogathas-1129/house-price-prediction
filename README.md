# 🏠 House Price Prediction

A Machine Learning project that predicts house prices using housing features such as living area, quality, garage information, basement details, and other property characteristics.

The project follows a complete machine-learning workflow, including data exploration, data cleaning, feature engineering, categorical encoding, model training, evaluation, and prediction.

---

## 📌 Project Overview

House prices depend on many factors, including the size of the property, overall quality, location-related features, number of rooms, garage facilities, basement features, and year of construction.

In this project, I developed a **House Price Prediction model using Random Forest Regression**.

The workflow includes:

- 📊 Exploratory Data Analysis
- 🔍 Missing Value Analysis
- 🧹 Data Cleaning
- 🔢 Numerical Feature Processing
- 🏷️ Categorical Feature Encoding
- 🛠️ Feature Engineering
- ✂️ Train/Test Split
- 🌲 Random Forest Regression
- 📈 Model Evaluation
- 🏠 House Price Prediction
- 📄 Submission File Generation

---

## 🎯 Objective

The main objective is to build a regression model that can learn the relationship between house characteristics and their selling prices.

The model is trained using historical housing data and is then used to predict prices for unseen houses.

---

## 📂 Dataset

The project uses the **Ames Housing dataset**, containing information about residential properties and their sale prices.

### Training Data

- **1,460 houses**
- **81 original columns**
- Target variable: `SalePrice`

### Test Data

- **1,459 houses**
- **80 original columns**
- Does not contain `SalePrice`

---

## 🧹 Data Preprocessing

The dataset contains both numerical and categorical features.

### Missing Values

Missing values were identified and handled based on the type of feature.

For numerical features, missing values were handled using appropriate statistical values such as the **median**.

For categorical features, missing values were handled using the **mode**.

### Feature Removal

Some columns were removed because they contained excessive missing values, redundant information, or were not useful for the prediction task.

Examples include:

```text
Id
PoolQC
MiscFeature
Alley
Fence
MasVnrType
