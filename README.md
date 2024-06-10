Breast Cancer Wisconsin (Diagnostic) Classification Models

Project Overview:

This project aims to explore the application of machine learning for the classification of breast tumors as benign (non-cancerous) or malignant (cancerous) using the Breast Cancer Wisconsin (Diagnostic) dataset from the UCI Machine Learning Repository. Two models are developed and evaluated for this task:

1.Support Vector Machine (SVM):A powerful model known for its effectiveness in high-dimensional spaces and its ability to handle complex decision boundaries.
2.Logistic Regression:A widely used linear model for classification tasks, often chosen for its simplicity and interpretability.

Dataset:

The Breast Cancer Wisconsin (Diagnostic) dataset contains 569 samples, each with 30 features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. These features describe characteristics of the cell nuclei present in the image. The dataset is relatively small and contains no missing values.

Methodology:

1. Data Preprocessing:
   - The dataset is loaded using the `ucimlrepo` package.
   - Features are standardized using `StandardScaler` to ensure they have a mean of 0 and a standard deviation of 1.
   - The data is split into a training set (80%) and a test set (20%).

2.Model Training and Evaluation:
   - Two models are trained and evaluated: SVM (with a linear kernel) and logistic regression.
   - Model performance is assessed using the following metrics:
     - Accuracy
     - Precision
     - Recall
     - F1-score

Results:

 Model: SVM             
 Accuracy:96%

 Model: Logistic Regression 
 Accuracy: 97%
            

Both models achieve high accuracy on this dataset, with logistic regression slightly outperforming SVM. The classification reports (available in the respective notebooks) provide more detailed insights into the model performance on each class (benign and malignant).
