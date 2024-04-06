# CNN classification of Fine Needle Aspiration (FNA) images
---

## Name: Pola Gnana Shekar
## Roll No: 21CS10052

### Project Overview
This project aims to develop a Convolutional Neural Network (CNN) to classify FNA (Fine Needle Aspiration) images into benign or malignant categories. The dataset, found in the "Dataset2" folder, comprises two subfolders: "FNA" (containing images) and "test" (unlabeled images for predictions).

### Dataset Structure
- FNA Folder: Contains subfolders for 'benign' (1074 images) and 'malignant' (650 images) cases.
- Test Folder: Holds 14 unlabelled images for prediction.

### Project Steps
- **Data Preprocessing**: Preprocesses the labeled images within the 'FNA' folder for training and validation.
- **Model Training and Validation**: Trains and validates a CNN using preprocessed images.
- **Performance Metrics**: Estimates, plots, and analyzes training and validation loss and accuracy functions.
- **Prediction on Unlabeled Data**: Applies the trained model to predict whether the images in the 'test' folder are benign or malignant.


### Prerequisites
Make sure you have TensorFlow installed. If not, install it using the following command:

```bash
Copy code
pip install tensorflow
```

Have the upgraded version of numpy. you can use the following command to upgrade:

```bash
Copy code
pip install --upgrade numpy
```

Ensure that the 'Dataset2' folder is in the same directory as the '21CS10052_Code.ipynb' file.

### How to Run
Execute each cell one after the other in the notebook ('21CS10052_Code.ipynb') sequentially to accomplish the following tasks:
Data preprocessing
Model training and validation
Performance metric estimation and visualization
Prediction on unlabeled test data

#### Note:
A sample output is also provided for reference as a pdf file - output.pdf