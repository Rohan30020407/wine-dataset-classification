# Wine Dataset Classification

This project focuses on classifying different types of wine using the UCI Wine Dataset.  
It includes data preprocessing, visualization, and machine learning models to build a predictive classifier.

## Dataset
- Source: UCI Machine Learning Repository – Wine Dataset
- Features: 13 chemical properties (e.g., alcohol, malic acid, ash, flavanoids)
- Target: Wine class (3 categories)

## Approach
1. Data preprocessing and cleaning
2. Exploratory Data Analysis (EDA) with visualizations
3. Model training using:
   - Logistic Regression
   - Random Forest
   - XGBoost
4. Model evaluation using accuracy and confusion matrix

## Results
- Best Model: XGBoost
- Accuracy: ~94% (on test data)

## How to Run
1. Clone this repository:
   git clone https://github.com/Rohan30020407/wine-dataset-classification.git

2. Install dependencies:
   pip install -r requirements.txt

3. Open the notebook:
   notebooks/Wine_Dataset_improved.ipynb

## Repository Structure
wine-dataset-classification/
│
├── notebooks/
│   └── Wine_Dataset_improved.ipynb   # Main Jupyter Notebook
│
├── reports/
│   └── Wine_Dataset_Report.html      # Static report (viewable in browser)
│
├── requirements.txt                  # Dependencies
└── README.md                         # Project overview

