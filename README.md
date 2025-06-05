# 🏥 Healthcare Insurance Cost Prediction

This project demonstrates how to predict healthcare insurance costs using Python and machine learning techniques. It encompasses the entire workflow from data preprocessing and exploratory data analysis to building and evaluating a regression model.

## 📂 Repository Contents

- `Healthcare_Insurance_Prediction.ipynb` — Jupyter Notebook containing the complete implementation.

## 📊 Dataset Overview

The dataset includes the following features:

- **Age**: Age of the primary beneficiary
- **Sex**: Gender of the insurance policyholder (male/female)
- **BMI**: Body Mass Index
- **Children**: Number of dependents covered by the insurance
- **Smoker**: Smoking status (yes/no)
- **Region**: Residential area in the U.S. (northeast, southeast, southwest, northwest)
- **Charges**: Individual medical costs billed by health insurance

*Note: The dataset is sourced from [Kaggle's Medical Cost Personal Datasets](https://www.kaggle.com/datasets/mirichoi0218/insurance).*

## 🛠️ Technologies Used

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## 📈 Project Workflow

1. **Data Loading**: Importing the dataset using pandas.
2. **Data Preprocessing**:
   - Handling missing values (if any)
   - Encoding categorical variables
   - Feature scaling (if required)
3. **Exploratory Data Analysis (EDA)**:
   - Visualizing distributions and relationships between features
   - Identifying correlations
4. **Model Building**:
   - Splitting data into training and testing sets
   - Implementing Linear Regression using scikit-learn
5. **Model Evaluation**:
   - Calculating metrics such as R² Score and Mean Absolute Error (MAE)
   - Visualizing actual vs. predicted values

## 🚀 Getting Started

### Prerequisites

Ensure you have the following libraries installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
