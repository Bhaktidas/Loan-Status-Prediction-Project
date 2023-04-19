
# Loan Status Prediction Project

This project is designed to help financial institutions predict loan approval status using machine learning algorithms in Python. The project includes a set of scripts and modules for preprocessing loan data, training and evaluating predictive models, and making predictions on new loan applications.

## Project Description

The Loan Status Prediction is a Python project designed to predict the status of a loan application based on various factors. The project aims to help banks and financial institutions to accurately assess loan applications and reduce the risk of default.

The project will use machine learning algorithms, specifically classification models, to analyze the data and predict the status of a loan application based on factors such as the applicant's income, credit history, debt-to-income ratio, loan amount, loan term, and employment status.

The project will use the Pandas library to read the CSV file containing the loan data and manipulate the data. The machine learning models will be implemented using the Scikit-learn library, providing a range of powerful tools for data analysis and prediction. The project will also include error handling and data validation to ensure that the data is entered and processed correctly.

The Loan Status Prediction will be an open-source project, available on GitHub for anyone to download, use, and contribute to. The project will be compatible with Python 3.x and will run on Windows, macOS, and Linux.

The project will also include a user interface implemented using the Tkinter library, providing an easy-to-use tool for banks and financial institutions to input loan application data and receive a prediction of the loan status.

Overall, the Loan Status Prediction project aims to provide an accurate and reliable tool for predicting the status of a loan application, allowing banks and financial institutions to make informed decisions about lending and reduce the risk of default. By leveraging the power of machine learning, the project can help to optimize lending decisions and improve the financial stability of borrowers and lenders alike.

## Installation

To use the Loan Status Prediction Project, you'll need to have Python 3.x installed on your system. You can download the latest version of Python from the official Python website.

Once you have installed Python, you can download the project files from our repository:

https://github.com/Bhaktidas/Loan-Status-Prediction-Project

You can then install the required Python libraries by running the following command in the project directory:

pip install -r requirements.txt

This will install all of the necessary dependencies, including Scikit-learn, NumPy, and Pandas.


    
## Dataset
The dataset used for this project is sourced from Kaggle and contains information about loan applicants. It has a total of 614 rows and 13 columns, with the following features:

Loan ID

Gender

Married

Dependents

Education

Self_Employed

ApplicantIncome

CoapplicantIncome

LoanAmount

Loan_Amount_Term

Credit_History

Property_Area

Loan_Status (Target Variable)
## Dependencies
To run this project, you need to have the following dependencies installed on your system:

Python 3.5+,
pandas,
numpy,
matplotlib,
seaborn,
scikit-learn.
## Usage/Examples

The project evaluates the performance of various machine learning models using metrics such as accuracy, precision, recall, and F1-score. Based on the evaluation, the best performing model is selected, and its predictions are output to a CSV file named loan_prediction_results.csv.
## Conclusion
This loan status prediction project showcases how machine learning can be used to predict whether a loan applicant's loan status will be approved or not. By analyzing various features, we can create a model that can accurately predict loan status and help financial institutions make better lending decisions.
