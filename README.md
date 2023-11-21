# Loan Eligibility Prediction Model

This repository contains a predictive model that determines the eligibility of an individual for a loan based on various parameters such as Gender, Married status, Dependents, Education level, Self-Employment status, Applicant Income, Coapplicant Income, Loan Amount, Loan Amount Term, Credit History, and Property Area.

## Dataset

The dataset used for this prediction model consists of the following parameters:

- Gender
- Married
- Dependents
- Education
- Self_Employed
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Property_Area

## Data Analysis

The analysis of the dataset involves the use of several visualization techniques to better understand the distribution and relationships of the parameters. The following techniques are applied:

### Boxplot

Boxplots are used to visualize the distribution of numerical data and identify potential outliers in parameters such as ApplicantIncome, Education, LoanAmount.

### Histogram

Histograms are employed to illustrate the frequency distribution of numerical data, providing insights into the distribution of ApplicantIncome, CoapplicantIncome, LoanAmount, LoanAmount_log.

### Pie Chart

A pie chart is generated to visualize the distribution of Prediction of loan eligibility.

## Data Preprocessing

The dataset undergoes a series of preprocessing steps to ensure its suitability for model training. These steps include:

### Data Cleaning

Any missing or inconsistent values within the dataset are addressed and cleaned to enhance the quality of the data.

### Data Normalization

Normalization is applied to scale numerical data, ensuring that all features contribute equally to the model training process.

## Model Training

The loan eligibility prediction model is trained using a suitable machine learning algorithm, taking into account the preprocessed and normalized dataset.

## How to Use

To use the loan eligibility prediction model, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies .
3. Run the provided Jupyter Notebook or Python script to train the model and make predictions.

## Dependencies

Ensure you have the following dependencies installed:
1.numpy.
2.pandas.
3.matplotlib.
4.seaborn.
5.scikit-learn.


## Contribution

Feel free to contribute to the development of this loan eligibility prediction model by opening issues or submitting pull requests.

Happy coding!
