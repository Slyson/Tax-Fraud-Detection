# Credit Card Fraud Detection

This code focuses on detecting credit card fraud using a dataset of credit card applications. It applies various techniques, including outlier detection using Local Outlier Factor (LOF) and logistic regression for classification. The code also includes data preprocessing steps such as data cleaning, feature engineering, and scaling.

## Dependencies

Make sure you have the following dependencies installed:

- scikit-learn
- numpy
- pandas
- matplotlib

You can install these dependencies using pip:

```
pip install scikit-learn numpy pandas matplotlib
```

## Dataset

The code uses a credit card application dataset from <a href"https://www.kaggle.com/datasets/mishra5001/credit-card/versions/1">Kaggle</a> (`application_data.csv`). Make sure to provide the correct file path for the dataset in the code.

## Usage

1. Ensure that the required dependencies are installed.

2. Provide the correct file path for the credit card application dataset (`application_data.csv`) in the code.

3. Open the code in a Python environment, such as Jupyter Notebook or any Python IDE.

4. Run the code cells sequentially to perform the following steps:
   - Load and explore the dataset.
   - Visualise and analyse the data.
   - Preprocess the data by handling missing values and dropping unnecessary columns.
   - Encode categorical variables using one-hot encoding.
   - Scale the data using MinMaxScaler.
   - Perform outlier detection using Local Outlier Factor (LOF).
   - Train a logistic regression model using cross-validation.
   - Evaluate the models using classification reports and ROC curves.

5. Customise the code as needed:
   - Modify the data preprocessing steps to handle specific requirements of your dataset.
   - Adjust the parameters of the models to optimise performance.

6. Analyse the results and evaluation metrics obtained from the classification models to assess credit card fraud detection performance.

## Licence

This project is licensed under the [Apache Licence 2.0](http://www.apache.org/licenses/).
