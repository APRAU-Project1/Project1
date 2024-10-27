
# Machine Learning Master Class Project: Project 1

## Team Members
- **Hugo Dutra**
- **Zuzanna Rybok**
- **Mateusz Janowski**

## Overview
This project is a comprehensive exploration of machine learning techniques and their application in real-world scenarios. Through various methods of data preprocessing, feature selection, model evaluation, and optimization, we aim to develop a robust predictive model to address specific challenges within our chosen dataset.

## Table of Contents
1. [Project Description](#project-description)
2. [Dataset](#dataset)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Feature Selection Techniques](#feature-selection-techniques)
    - [Chi-Squared Test](#chi-squared-test)
    - [ANOVA](#anova)
6. [Model Evaluation](#model-evaluation)
7. [Conclusions](#conclusions)
8. [Future Work](#future-work)

## Project Description
The objective of this project is to analyze and model a dataset using machine learning algorithms. We will focus on understanding the underlying patterns within the data, applying various techniques for feature selection, and ultimately building a predictive model that can generalize well to new, unseen data.

## Targe variable
- The target variable is [vegetation_type].

## Installation
To run this notebook, you will need to install the following Python packages:
- `pandas`
- `numpy`
- `scikit-learn`
- `scipy`
- `matplotlib`
- `seaborn`

You can install the required packages using pip:

```bash
pip install pandas numpy scikit-learn scipy matplotlib seaborn
```

## Usage
Clone this repository and navigate to the project directory. You can run the Jupyter Notebook directly:

```bash
git clone [repository-url]
cd [project-directory]
jupyter notebook Project1.ipynb
```

## Feature Selection Techniques

### Chi-Squared Test
The Chi-Squared test is employed to evaluate the association between categorical variables and the target variable. By analyzing the frequency of occurrences, we identify features that are statistically significant in relation to the target variable. This process helps in selecting meaningful categorical features that enhance the model's predictive power.

### ANOVA
ANOVA (Analysis of Variance) is utilized to compare the means of numerical features across different categories of the target variable. By determining whether there are statistically significant differences between group means, ANOVA assists in identifying continuous features that contribute meaningfully to the target variable. A low p-value indicates potential correlation, helping to retain valuable features for model training.

## Model Evaluation
The performance of various models is evaluated through multiple metrics, including:
- **F1 Score**
- **Accuracy**
- **Cross-Validation**

Different models such as Logistic Regression, LDA (Linear Discriminant Analysis), and Ridge Classifier are compared based on their ability to handle unbalanced datasets and their overall predictive performance.

## Conclusions
In conclusion, our findings indicate that the **Unbalanced Ridge Classifier** is the best-performing model for our dataset, achieving a robust F1 Score and demonstrating the ability to effectively handle class imbalance. The combination of careful feature selection and appropriate model choice enhances our model's interpretability and predictive capabilities.

## Future Work
Future enhancements may include:
- Hyperparameter tuning to optimize model performance.
- Exploring ensemble methods to further improve predictive accuracy.
- Data augmentation techniques to enrich the dataset and improve model robustness.

---

Thank you for your interest in our project! For any questions or further information, feel free to reach out to the team members.
