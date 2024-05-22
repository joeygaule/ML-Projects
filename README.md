# ML-Projects
Collection of ML projects 

# Brain Tumor Classification Using CNN

This project aims to classify brain tumors from MRI images using a Convolutional Neural Network (CNN). The project is part of a Machine Learning & Predictive Analytics course.

## Problem Statement

Accurate classification of brain tumors from MRI images can aid in timely diagnosis and treatment. The objective of this project is to develop a CNN model to classify brain tumors from MRI images into categories such as glioma, meningioma, pituitary tumor, or no tumor.

## Assumptions/Hypotheses about Data and Model

- MRI images are of sufficient quality and resolution for tumor detection.
- Different types of brain tumors have distinguishable features that can be learned by a CNN.
- The dataset is balanced and representative of the various tumor types and non-tumor cases.
- The images are labeled correctly.

## Dataset

The dataset consists of MRI images labeled as either having a tumor or not. The data is preprocessed and augmented to improve model performance.

## Model Architecture

The CNN model consists of several convolutional layers with L2 regularization, followed by max-pooling layers, a flattening layer, dense layers, and dropout layers to prevent overfitting. Hyperparameters were optimized using Bayesian Optimization.

## Results

The model achieved an accuracy of XX% on the test set. Additional evaluation metrics such as ROC-AUC, PR AUC, and a confusion matrix were used to assess model performance.

## Future Work

- Collecting more diverse data.
- Exploring other advanced architectures.
- Integrating clinical data with imaging data for a more comprehensive model.
- Discussing potential real-world deployment, including considerations for model validation and regulatory compliance.

## How to Run the Project

1. Clone the repository:
    ```bash
    git clone https://github.com/joeygaule/ML-Projects.git
    ```
2. Navigate to the project directory:
    ```bash
   https://github.com/joeygaule/ML-Projects.git
    ```
3. Open the `brain_tumor_classification.ipynb` notebook in Google Colab or Jupyter Notebook.

## NOtes

- The Presentation was uploaded and contained within the repisitory.
- Images and results may differ from ipynb file to ppt as various iterations have been made continuously.
- The dataset has been provided. 


