# Wine Quality Prediction Using Machine Learning

A machine learning project that predicts wine quality using physicochemical properties and explores data patterns through exploratory data analysis, visualization, and model evaluation.

## Project Overview

Wine quality is influenced by multiple physicochemical characteristics, including acidity, residual sugar, chlorides, density, sulphates, and alcohol content.

This project explores these characteristics and develops classification models to predict wine quality ratings from the available dataset.

## Objectives

- Explore the relationships between wine characteristics and quality ratings.
- Clean and preprocess the dataset for machine learning.
- Perform exploratory data analysis and feature analysis.
- Train and compare multiple classification models.
- Evaluate model performance using appropriate classification metrics.

## Dataset

The dataset, `winequalityN.csv`, contains physicochemical measurements and wine quality ratings.

Features include:

- Fixed acidity, volatile acidity, and citric acid
- Residual sugar and chlorides
- Free and total sulfur dioxide
- Density, pH, and sulphates
- Alcohol content and wine type

**Target variable:** Wine quality rating.

## Technologies Used

- **Language:** Python
- **Data analysis:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Machine learning:** Scikit-learn, XGBoost, LightGBM
- **Development environment:** Jupyter Notebook

## Project Workflow

1. Load and inspect the dataset.
2. Explore distributions, correlations, and quality ratings.
3. Handle missing values and preprocess features.
4. Analyze relationships between physicochemical properties and quality.
5. Split the data into training and testing sets.
6. Train classification models.
7. Evaluate and compare model performance.
8. Analyze predictions and identify areas for improvement.

## Models and Techniques

### Classification
- Random Forest
- Support Vector Machine (SVM)
- XGBoost
- LightGBM

### Additional techniques
- Principal Component Analysis (PCA)
- K-Means clustering

PCA and K-Means are included as additional analytical techniques, where implemented in the notebook.

## Model Evaluation

The notebook evaluates classification performance using accuracy and classification reports.

Add your actual results here after verifying the notebook outputs.

| Model | Accuracy | Precision | Recall | F1-score |
|---|---:|---:|---:|---:|
| Random Forest | To be added | To be added | To be added | To be added |
| SVM | To be added | To be added | To be added | To be added |
| XGBoost | To be added | To be added | To be added | To be added |
| LightGBM | To be added | To be added | To be added | To be added |

*Report metrics using the same test split and evaluation approach for fair comparison. For multiclass classification, specify the averaging method used for precision, recall, and F1-score.*

## Repository Structure

```text
Wine-Quality-Prediction/
├── Wine_Quality.ipynb
├── winequalityN.csv
└── README.md
```

## How to Run

1. Clone or download the repository.
2. Install the required libraries used in the notebook.
3. Open `Wine_Quality.ipynb` in Jupyter Notebook or Google Colab.
4. Ensure `winequalityN.csv` is available at the path expected by the notebook.
5. Execute the notebook cells sequentially.

## Key Learning Outcomes

- Exploratory data analysis and feature analysis
- Data cleaning and preprocessing
- Supervised machine learning classification
- Model evaluation and comparison
- Data visualization and interpretation

## Author
Aryan Mathuriya
Aryan Mathuriya

[GitHub Profile](https://github.com/Aryan-Mathuriya)
