
# Credit Score Prediction Using Machine Learning

This project involves predicting credit scores using various machine learning algorithms. The dataset consists of credit records and application records, which are processed and analyzed to build predictive models.

## Project Overview

The goal of this project is to develop a model that can predict an individual's credit score based on their financial and application data. Various machine learning models are applied, and their performances are evaluated to identify the most accurate model for this task.

## Datasets

The project utilizes two main datasets:
- **Credit Records** (`credit_record.csv`): Contains information about monthly balance and credit history.
- **Application Records** (`application_record.csv`): Contains details about applicants, including demographic and financial information.

## Key Features

- **Data Preprocessing**: Data cleaning, feature selection, and scaling are performed to prepare the datasets for modeling.
- **Exploratory Data Analysis (EDA)**: Visualizations and statistical summaries are used to understand the distribution and relationships within the data.
- **Machine Learning Models**: Several machine learning models are implemented, including:
  - K-Nearest Neighbors (KNN)
  - Gradient Boosting Classifier
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier
- **Model Evaluation**: The models are evaluated based on accuracy and other relevant metrics to determine the best-performing algorithm.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/credit-score-prediction.git
   ```
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook credit_score.ipynb
   ```

