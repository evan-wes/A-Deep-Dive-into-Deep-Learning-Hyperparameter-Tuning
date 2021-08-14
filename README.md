# A Deep Dive into Deep Learning Hyperparameter Tuning

The primary goal of this project is to develop strategies for tuning the large number of parameters and hyperparameters controlling various aspects of neural network construction and training. As such, the underlying dataset is less important. For this project, I used the `Cover_Type` dataset from the UCI machine learning repository: [https://archive.ics.uci.edu/ml/datasets/covertype](https://archive.ics.uci.edu/ml/datasets/covertype). I picked this dataset because it contains a mix of continuous and boolean features (over fifty in total), and has multiple outputs. 

**~~~ This project is a current work in progress ~~~**

## Path to completion:

1. Initial exploratory analysis and feature engineering ------------------------------------------ [$\checkmark$] 

2. Develop framework for automatic looping over pa------------------------------------------- [$\checkmark$]

    a. Custom model building function to build and compile tensorflow model <br>
        &nbsp; &nbsp; with arbitrary parameters -------------------------------------------------------- [$\checkmark$]
    
    b. Custom functions to save metrics and training history at every step to <br>
        &nbsp; &nbsp; recover from kernal freezes/crashes --------------------------------------------- [$\checkmark$]

3. Identify all adjustable parameters and suitable value or ranges to test: --------------------- [$\checkmark$]

    a. Training parameters for tuning (batch size and initial number of epochs) ----- [$\checkmark$]

    b. Model architecture (number and size of hidden layers) ------------------------ [$\checkmark$]

    c. Hidden activation function ------------------------------------------------------- [$\checkmark$]

    d. Optimization parameters (optimizer, learning rate) ---------------------------- [$\checkmark$]

    e. Dropout parameters (dropout probabilities for input and hidden layers) ----- [$\checkmark$]

4. Cross-validation of final set of candidate optimum parameters ----------------------------- [&nbsp; &nbsp;]

    a. Tuning number of epochs for each candidate optimal parameter set --------- [&nbsp; &nbsp;]

## Deep learning techniques used:
 - Neural networks

## Primary python libraries used:
 - Visualizations:
   - `matplotlib`
   - `seaborn`
 
 - Data analysis:
   - `numpy`
   - `pandas`

 - Neural networks:
   - `tensorflow`
   - `keras` 

 - Model performance analysis:
   - `sklearn`

