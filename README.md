# Exploring the Use of Machine Learning in Health Insurance Pricing :chart_with_upwards_trend:
Savitribai Phule Pune University, Pune.
Group Project [Mar- Apr 2022]

![Project Logo](project_logo.png) (if you have a logo)

Welcome to the repository for the project "Exploring the Use of Machine Learning in Health Insurance Pricing." In this project, we delve into the application of machine learning techniques to the realm of health insurance pricing. This README file provides an overview of the project, the dataset used, steps taken, and the libraries employed.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Steps Taken](#steps-taken)
- [Libraries Used](#libraries-used)
- [Usage](#usage)
- [Contributors](#contributors)

## Introduction :bulb:
The goal of this project is to investigate the potential of machine learning algorithms in predicting health insurance premiums. Traditionally, health insurance pricing has been based on actuarial tables and statistical analyses. However, with the advent of machine learning, there is an opportunity to enhance pricing accuracy by considering a broader range of factors and their interactions.

In this project, we aim to:

Explore the dataset and gain insights into the variables that might influence insurance pricing.
Preprocess and clean the data to make it suitable for training machine learning models.
Train and evaluate different machine learning algorithms for predicting insurance premiums.
Compare the performance of machine learning models against traditional pricing methods.

## Dataset :bar_chart:
The dataset used in this project contains information about individuals and various factors that could impact health insurance pricing. It includes features such as age, gender, BMI, smoking habits, medical history, and region. The target variable is the insurance premium.

The dataset consists of X entries and Y features. It is stored in a CSV file named health_insurance_data.csv.
Example snippet of the dataset:
| age |   sex  | BMI  |Children| smoker  | region | insurance_premium |
|-----|--------|------|--------|---------|--------|-------------------|
| 25  | Female | 24.3 | No     | Yes     | North  | 2300              |
| 37  | Male   | 29.8 | Yes    | No      | West   | 5800              |
| ... | ...    | ...  | ...    | ...     | ...    | ...               |

## Steps Taken :rocket:
## Project Steps

1. **Data Preprocessing:**
   - Cleaned the dataset by handling missing values.
   - Converted categorical variables into numerical representations using one-hot encoding.
   - Scaled numerical features for uniformity.

2. **Exploratory Data Analysis (EDA):**
   - Conducted exploratory analysis to understand variable distributions.
   - Explored correlations between variables.
   - Identified and handled potential outliers.

3. **Feature Selection:**
   - Utilized techniques such as feature importance to identify relevant variables.
   - Performed correlation analysis to select the most influential features for modeling.

4. **Model Selection:**
   - Explored various regression algorithms, including:
     - Linear Regression
     - Random Forest Regression
     - Gradient Boosting Regression

5. **Model Training:**
   - Split the dataset into training and testing sets.
   - Trained the selected machine learning models on the training data.
   - Fine-tuned hyperparameters using techniques like cross-validation.

6. **Model Evaluation:**
   - Evaluated the models using metrics such as:
     - Mean Absolute Error (MAE)
     - Mean Squared Error (MSE)
     - R-squared (R²)

7. **Comparison:**
   - Compared the performance of machine learning models against traditional pricing methods.
   - Demonstrated potential improvements offered by machine learning techniques.
## Libraries Used

The project utilized the following Python libraries:

- **Pandas:** Used for data manipulation and analysis.
- **NumPy:** Utilized for numerical operations on arrays.
- **Matplotlib and Seaborn:** Employed for data visualization and creating plots.
- **Scikit-learn:** Used for machine learning algorithms, preprocessing, and model evaluation.
- **(Add any other libraries you used.)**
## Usage :computer:
Clone this repository: git clone https://github.com/your-username/health-insurance-ml-pricing.git
Navigate to the project directory: cd health-insurance-ml-pricing
Install the required libraries: pip install -r requirements.txt
Run the Jupyter notebook or Python script for data preprocessing, analysis, modeling, and evaluation.

## Contributors :busts_in_silhouette:
- Mohit Jadhav(https://github.com/mohitjadhav201)
- Romit Surywvanshi

