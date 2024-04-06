# Cancer Type Prediction with Machine Learning
This project is focused on using machine learning models to predict cancer types based on gene expression data. The project includes the following steps:

## Data Preprocessing:
The dataset containing gene expression information for cancer patients is loaded and preprocessed. It involves handling missing data, encoding categorical features, and splitting the data into training and test sets.

## Model Training: 
Three machine learning models are trained on the preprocessed data:
- Support Vector Machines (SVM) with various kernels (Linear, RBF, Poly, Sigmoid).
- Random Forest Classifier.
- Neural Network with hyperparameter tuning.

## Model Comparison: 
The performance of each model is evaluated using metrics such as accuracy, precision, recall, F1-score, and confusion matrices. This step involves comparing the strengths and weaknesses of SVM, Random Forest, and Neural Network models in predicting cancer types.

## Instructions
To execute the code and reproduce the results, follow these steps:

### 1. Install Dependencies
Use the provided requirements.txt file to install the required Python packages. Run the following command:

```bash
pip install -r requirements.txt
```

### 2. Run the Python Scripts
Run the Cells in the Jupyter notebook one by one in the given order.

- Data Importing and Manipulation: The code related to Data preprocessing is in the first cell of the Jupyter Notebook.

- Data Encoding: The code related to Data Encoding is in the second cell of the Jupyter Notebook.

- SVM Models: The code related to SVM models is in the third cell of the Jupyter Notebook.

- Random Forest: The code for Random Forest is in the fourth cell of the Jupyter Notebook.

- Neural Network: The code for the Neural Network model is in the fifth cell of the Jupyter Notebook.

### 3. View the Results
The evaluation results, including accuracy, precision, recall, F1-score, and confusion matrices, will be displayed in the console. Additionally, the best hyperparameters for the Neural Network model will be printed.

### 4. Additional Files
The output obtained from running the code is provided in the output.pdf file for reference.
