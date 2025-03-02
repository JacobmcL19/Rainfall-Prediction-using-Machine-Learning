# Rainfall-Prediction-using-Machine-Learning

## Overview  
Predicting rainfall accurately remains a challenging task, even for meteorological departments. This project leverages machine learning techniques to predict whether it will rain today based on various atmospheric factors. By utilizing advanced ML algorithms, we aim to improve the accuracy of rainfall prediction, which traditionally required expert meteorologists.  

## Features  
- Data preprocessing and cleaning  
- Exploratory Data Analysis (EDA)  
- Handling imbalanced datasets  
- Feature selection and scaling  
- Training multiple classification models  
- Model evaluation using accuracy metrics and confusion matrices  

## Installation  

1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/Rainfall-Prediction-ML.git
   cd Rainfall-Prediction-ML
   ```  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  

## Dataset  
The dataset contains atmospheric conditions such as temperature, humidity, cloud cover, wind speed, and sunshine hours. It has been preprocessed to remove inconsistencies, impute missing values, and normalize features.  

## Technologies Used  

- **Python** – Primary programming language  
- **Pandas** – Data handling and analysis  
- **NumPy** – Numerical computations  
- **Matplotlib & Seaborn** – Data visualization  
- **Scikit-Learn** – Machine learning model implementation  
- **XGBoost** – High-performance gradient boosting  
- **Imbalanced-learn** – Handling data imbalance  

## Model Training  

The following models were trained and evaluated:  
- **Logistic Regression**  
- **XGBoost Classifier**  
- **Support Vector Classifier (SVC)**  

Data preprocessing steps:  
1. **Handling missing values** – Mean imputation  
2. **Feature scaling** – Standardization for faster and stable training  
3. **Balancing dataset** – Using Random Over Sampling (ROS)  
4. **Feature selection** – Removing highly correlated features  

## Results  

| Model                  | Training Accuracy | Validation Accuracy |
|------------------------|------------------|---------------------|
| Logistic Regression    | 88.9%            | 89.6%               |
| XGBoost Classifier     | 99.0%            | 84.1%               |
| Support Vector Classifier | 90.3%         | 88.5%               |

- The **Logistic Regression and SVC models** performed best, maintaining a low gap between training and validation accuracy.  
- A **confusion matrix and classification report** were used to evaluate model performance.  

## Usage  

Run the Jupyter Notebook:  
```bash
jupyter notebook Rainfall_Prediction.ipynb
```  
Follow the steps in the notebook to preprocess data, train models, and evaluate predictions.  
