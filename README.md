# Dementia Detection

Neurodegenerative diseases like dementia and Alzheimer's represent a major danger to our healthcare system. Clinical evaluations, which may or may not be able to identify the modest cognitive changes that occur in the early stages of the disease, have historically played a major role in diagnosis procedures.

This repository contains Python Notebook for a project focused on predicting Dementia. It includes two main parts:

1.	Data Analysis and Preprocessing: In this part, we analyze the dataset and prepare it for machine learning and deep learning. It covers data visualization, resizing, color space conversion, normalization, and data splitting. The details are available in the Dementia_Detection (3 algorithms).ipynb" notebook.
2.	Model Building and Evaluation: In this part, we build a machine learning model for dementia prediction. The main focus is on using Convolutional Neural Network (CNN) to create a predictive model. The model is trained, evaluated, and tested for its performance.


# Data
The dataset used in this project contains images around 5000 images and consists of two files: Training and Testing. Both files consist of four classes.
1. MildDemented
2. VeryMildDemented
3. NonDemented
4. ModerateDemented

# I. Comparative Analysis- Logistic Regression, SVM, CNN
# Data Analysis and Preprocessing
- Data exploration and description.
- Data visualization to understand feature distributions and relationships.
- To standardize image format and quality, applied techniques such as Resizing Color Space Conversion, Normalization
- Upsampling techniques
- Data splitting for training and testing.


# Model Building and Evaluation
- Exploration of different models (including Logistic Regression and SVM) and selection of the Convolutional Neural Network (CNN) model.
- Model training and optimization.
- Evaluation metrics, including precision, recall, accuracy.

# II. Segmentation Based Approach
-Preprocessing Techniques- Gray-scale conversion, Median filter, Morphological operations
-Processing Stage- Threshold segmentation, Complementing, Watershed segmentation
-Post Processing Stage- Maximum Stable Extremal Regions and K-means Clustering
-Evaluation metrics- PSNR, SSIM MSER Count for stage detection
