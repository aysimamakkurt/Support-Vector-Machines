# Support-Vector-Machines

Overview
This Jupyter Notebook contains various tasks focused on applying Support Vector Machines (SVM) for weather classification using a dataset collected with Luxottica's iSee glasses. The glasses are equipped with multiple sensors, recording atmospheric data every three seconds for 8 hours.

Dataset Labels
The dataset consists of four weather conditions represented by numerical labels:

0: Sunny
1: Rain
2: Cloudy
3: Mostly Clear
Contents
  Preliminary Steps
    Import necessary libraries
    Load and normalize the dataset
  Hyper-parameter Search
    Implement k-fold cross-validation for model selection
    Evaluate different kernels: Linear, Polynomial (degrees 2 and 3), and Radial Basis Function (RBF)
    Analyze the impact of hyper-parameters on model performance
  Training with More Data
    Explore the effect of increasing the training dataset size
  Boundaries Visualization
    Visualize classification boundaries of the SVM models
Running the Notebook
  Ensure all required libraries (NumPy, Matplotlib, scikit-learn) are installed in your Python environment.

