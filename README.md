# Supervised ML – House Price Prediction

## 📌 Project Overview

This project is a **Supervised Machine Learning regression project** focused on predicting residential house prices.

The project is based on the **HomeVista Properties** assignment, where the objective is to build a machine learning system that can predict the market price of a house using historical property data.

A **Linear Regression** model is used to predict the target variable, `SalePrice`, after performing data preprocessing and feature preparation.

## 🎯 Problem Statement

A real estate company, **HomeVista Properties**, operates across multiple cities and handles thousands of residential property sales every year. The company wants to automate its house pricing process.

The objective is to develop a regression model that can predict the market price of a house based on its physical features, location, and condition.

## 📊 Dataset

The project uses the dataset:

`HousePricePrediction.csv`

Each row represents a residential property and contains information about its physical, construction, and location-related characteristics.

### Features

| Feature | Description |
|---|---|
| `Id` | Unique identification number for each house |
| `MSSubClass` | Type of dwelling involved in the sale |
| `MSZoning` | General zoning classification |
| `LotArea` | Lot size in square feet |
| `LotConfig` | Lot configuration |
| `BldgType` | Type of dwelling |
| `OverallCond` | Overall condition rating of the house |
| `YearBuilt` | Original construction year |
| `YearRemodAdd` | Year of remodeling or additions |
| `Exterior1st` | Exterior covering of the house |
| `BsmtFinSF2` | Type 2 finished basement square feet |
| `TotalBsmtSF` | Total basement area in square feet |
| `SalePrice` | Final selling price — **Target Variable** |

## 🎯 Target Variable

The model predicts:

```text
SalePrice
```

This makes the problem a **regression problem**, because the model predicts a continuous numerical value.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 🔄 Machine Learning Workflow

The project follows an end-to-end supervised machine learning workflow:

```text
Data Loading
     ↓
Data Exploration
     ↓
Data Preprocessing
     ↓
Categorical Feature Encoding
     ↓
Feature Selection
     ↓
Train-Test Split
     ↓
Linear Regression Model
     ↓
Prediction
     ↓
Model Evaluation
```

## 🧹 Data Preprocessing

The notebook performs preprocessing to prepare the property data for machine learning.

Categorical variables are converted into numerical representations using **one-hot encoding**, allowing them to be used by the Linear Regression model.

The dataset is also prepared by separating the independent variables from the target variable, `SalePrice`.

## 🔀 Train-Test Split

The dataset is divided into training and testing sets.

The training data is used to train the Linear Regression model, while the testing data is used to evaluate how well the model performs on unseen data.

## 🤖 Machine Learning Model

The project uses **Linear Regression** from Scikit-learn.

Linear Regression attempts to model the relationship between the input property features and the target house price.

The general form of the model is:

```text
y = β₀ + β₁X₁ + β₂X₂ + ... + βₙXₙ
```

Where:

- `y` = predicted house price
- `β₀` = intercept
- `β₁ ... βₙ` = model coefficients
- `X₁ ... Xₙ` = input features

## 📏 Feature Scaling

The notebook also explores feature scaling as part of the machine learning workflow.

Feature scaling can help place numerical variables on comparable scales when required by a machine learning workflow.

## 📈 Model Evaluation

The notebook evaluates the regression model using regression performance metrics.

The evaluation helps determine how effectively the Linear Regression model predicts house prices on unseen test data.

## 📁 Project Structure

```text
Supervised-ML-House-Price-Prediction/
│
├── house_price_predictor.ipynb
├── HousePricePrediction.csv
└── README.md
```

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/Supervised-ML-House-Price-Prediction.git
```

### 2. Navigate to the project folder

```bash
cd Supervised-ML-House-Price-Prediction
```

### 3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
house_price_predictor.ipynb
```

## 💡 Key Learning Outcomes

Through this project, I practiced:

- Understanding supervised machine learning
- Regression problem formulation
- Data loading and exploration
- Data preprocessing
- Handling categorical variables
- One-hot encoding
- Feature preparation
- Train-test splitting
- Linear Regression
- Feature scaling
- Making predictions
- Evaluating a regression model

## 🚀 Future Improvements

Possible improvements to this project include:

- Comparing Linear Regression with other regression algorithms
- Performing more detailed feature engineering
- Applying cross-validation
- Hyperparameter tuning for suitable models
- Comparing multiple evaluation metrics
- Improving model performance through feature selection

## 👨‍💻 Author

**Santosh Dash**

Data Analyst | Python | SQL | Power BI | Machine Learning

---

⭐ If you find this project useful, feel free to star the repository.
