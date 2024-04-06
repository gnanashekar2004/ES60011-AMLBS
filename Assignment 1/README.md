## NAME: POLA GNANA SHEKAR
## ROLL NO: 21CS10052

# Assignment 1 - Exploratory Data Analysis and Classification
This project explores a dataset using Python, pandas, and scikit-learn. The dataset, named `framingham.csv`, contains information related to heart disease risk factors and outcomes. The project involves data preprocessing, exploratory data analysis (EDA), and classification tasks.

# Dependencies/ Requirements
Before running the code, ensure you have the following libraries installed:
Python (3.7+)
pandas
matplotlib
seaborn
scikit-learn
imbalanced-learn (imblearn)

You can install these dependencies using pip:
  ```bash
  pip install pandas matplotlib seaborn scikit-learn imbalanced-learn
  ```
- All the requirements needed for running the code are listed in the `requirements.txt` file.
- To install the required dependencies, you can use the following command:
  ```bash
  pip install -r requirements.txt
  ```
Make sure to have the data set file in the same folder as of the jupyter notebook.

# Implementation
To implement the code, follow these steps in the same order as they appear in the Jupyter Notebook:

- Import Data: Run the block of code for importing the dataset and visualizing it.

- Explore and Visualize Data: Run the code to explore and visualize the dataset. This step includes handling missing values, basic statistics of numeric columns, and visualizations of data distributions and correlations.

- Feature Selection by PCA: Execute the code for feature selection using Principal Component Analysis (PCA). This step involves dimensionality reduction to improve efficiency.

- Train and Test Split: Run the code for splitting the dataset into training (80%) and testing (20%) sets. This is crucial for evaluating model performance.

- Resampling: Execute the code for applying resampling techniques such as SMOTE, ADASYN, and RandomUnderSampler to address class imbalance.

- Pipeline and Measuring Accuracies: Run the code for creating pipelines for different classifiers (Logistic Regression, Decision Tree, KNN, and SVM) with resampling techniques. This step also includes hyperparameter tuning using GridSearchCV and measuring accuracy.

- Printing the Final Results: The final results, including accuracy scores and classification reports for each model and resampling strategy, will be printed in the Jupyter Notebook.

# Sample Output
A sample output of the code execution has been provided in the `Output.pdf` file. You can refer to this file to see the results of running the code.

# Code Description and Analysis
The code is thoroughly documented using comments within the Jupyter Notebook, explaining each step and its purpose. Additionally, the strengths and weaknesses of Logistic Regression, Support Vector Machines (SVM), Decision Tree, and KNN for predicting Heart Disease are discussed in the `report.pdf` file. The report also identifies the most suitable model based on accuracy and efficiency.
