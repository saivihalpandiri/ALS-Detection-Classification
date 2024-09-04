# ALS-Detection-Classification( Advanced Data Classification Techniques for Early Detection of Amyotrophic Lateral Sclerosis)

# Overview

This project focuses on the classification of Amyotrophic Lateral Sclerosis (ALS) using machine learning techniques applied to a dataset comprising various clinical, sensory, and functional features. ALS is a progressive neurodegenerative disorder that affects nerve cells in the brain and spinal cord, leading to loss of muscle control. Early detection and accurate diagnosis are critical for effective management and treatment. By leveraging data-driven approaches, this project aims to build and evaluate models that can accurately distinguish between individuals with ALS and healthy controls.

# Dataset:

The dataset used in this project is sourced from the Kaggle platform. It includes features such as demographic information, clinical metrics, sensory scores, time-dependent clinical condition indices, and functional scores. The dataset comprises of features and a target variable, 'Diagnosis (ALS)', where:

'1' indicates the presence of ALS. '0' indicates a healthy individual.

Some important features include:

Demographic Information: ID, Sex, Age

Clinical Metrics: J1_a, J3_a, J5_a, J55_a

Sensory Scores: S1_a, S3_a, S5_a

Time-dependent Clinical Condition Index (dCCi): dCCi(7), dCCi(8), dCCi(9), dCCi(10), dCCi(11), dCCi(12)

Functional Scores: d_1, F2_i, F2_{conv}

# Installation


# Install Jupyter Notebook :
Make sure you have Python installed on your computer.

# Install Required Packages: 
Install the necessary Python packages. You can do this using your preferred method (e.g., via Anaconda, or directly using pip). The key packages you might need are:

numpy
pandas
scikit-learn
matplotlib
seaborn
imblearn
seaborn

These packages are commonly used for data analysis and machine learning.

# Download the Dataset:
Obtain the ALS dataset from Kaggle.

# Run the Analysis: 
Follow the project steps to explore the data, preprocess it, train machine learning models, and evaluate their performance.

# Review Results:
Examine the model's accuracy and other performance metrics to understand how well it classifies ALS.

# Procedure

1.Loading Necessary Libraries.

2.Loading Dataset from a CSV File or from a Table.

3. Summarization of Data to Understand Dataset (Descriptive Statistics).

4.Visualization of Data to Understand Dataset (Plots, Graphs, etc.).

5.Data Pre-processing Imbalanced Learn Techniques, Data Transformation, Cross Validation.

6.Hyper parameter Tuning to Find the Optimal Parameters for the Classification Models.

7.Applying Different Learning Algorithms on the Training Dataset.

8.Applying the AUC and ROC Curves for the best three models.

# License

This project is licensed under the Kaggle Dataset License as provided by the dataset's creator.

# Results

The trained models achieved high accuracy in classifying ALS based on the clinical, sensory, and functional features provided in the dataset. The models demonstrated effective discrimination between ALS patients and healthy controls, among the models tested, GaussianNB and Bagging Classifier demonstrated the highest performance, achieving an accuracy of 88%.
