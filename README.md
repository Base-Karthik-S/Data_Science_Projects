# Telco Customer Churn Prediction

## Overview

This project aims to predict customer churn for a subscription-based business using machine learning. It involves data collection, data preprocessing, feature engineering, model selection, and model training to build a predictive model.

## Project Structure

The project is organized into the following sections:

1. **Data Collection**: In this section, we collect and load the Telco Customer Churn dataset.

2. **Data Preprocessing**: Data preprocessing includes handling missing values, encoding categorical variables, and feature engineering.

3. **Model Selection**: We choose a machine learning model (Random Forest Classifier) for the task.

4. **Model Training**: The selected model is trained on the preprocessed data.

5. **Model Evaluation**: We evaluate the model's performance using accuracy, a confusion matrix, and a classification report.

6. **Feature Importance Analysis**: We analyze the importance of features in the model's predictions and visualize the results.

7. **Visualizations**: The project includes various data visualizations to gain insights into the dataset.

## Prerequisites

- Python (3.6 or higher)
- Jupyter Notebook
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn (You can install these using pip)

## Usage

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Base-Karthik-S/Telco-Customer-Churn-Prediction.git

2. Open the Jupyter Notebook file Telco_Customer_Churn.ipynb to run the project interactively.

3. Follow the cells in the notebook to perform data preprocessing, model training, evaluation,
   and analysis.

4. Customize the code and visuals as needed for your specific use case.

## Dataset

The dataset used in this project is the "Telco Customer Churn" dataset, which includes the following columns:

- `customerID`
- `gender`
- `SeniorCitizen`
- `Partner`
- `Dependents`
- `tenure`
- `PhoneService`
- `MultipleLines`
- `InternetService`
- `OnlineSecurity`
- `OnlineBackup`
- `DeviceProtection`
- `TechSupport`
- `StreamingTV`
- `StreamingMovies`
- `Contract`
- `PaperlessBilling`
- `PaymentMethod`
- `MonthlyCharges`
- `TotalCharges`
- `Churn` (Target Variable: Yes/No)

## License

This project is open-source and is made available under the MIT License. You are encouraged to use and modify the code and content as needed, in accordance with the MIT License terms.

## Acknowledgments

The dataset used in this project is sourced from Kaggle: [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn). Special thanks to the data providers and the Kaggle community.

Feel free to adapt and expand upon this README to provide additional information about the project, its objectives, and how to utilize it effectively.
