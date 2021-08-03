The University of California, Davis  
Spring Quarter 2021  
[ECS 171] Machine Learning (w/ Professor Rafatirad)

# Purpose of Repo
For future reference, this repo will store the files that constitute my homework assignments in ECS 171. Additionally, by creating this repo (and others with similar content), I am familiarizing myself with Git and GitHub.

The following datasets (included in repo) were used for the homework assignments:
- **auto-mpg.data**
- **churn.txt**

This repo also contains various discussion notebooks (i.e. brief coding tutorials provided by TAs).

## Homework 1
Topics covered:
- Loading data
- Missing data
- Data visualization (bar plots, histograms, correlation matrix)
- Linear regression
    - Accomodate polynomial basis functions
    - Ordinary Least Squares (OLS)

## Homework 2
Topics covered:
- Training set vs testing set
- Fitting model, making prediction, calculating error
    - Mean Squared Error (MSE)
- Plotting linear regression
- Logistic regression
- Evaluation metrics
    - Precision and recall
- Min-max normalization

## Homework 3
Topics covered:
- Data Preprocessing
    - Normalizing numeric data
    - Encoding categorical data
        - Label encoding
        - One hot encoding
    - Outlier detection
        - Elliptic Envelope
        - Isolation Forest
        - Local Outlier Factor
        - One Class SVM
    - Pipelines
- Multicollinearity (strongly correlated features)
- Feed-forward multilayer perceptron (MLP) i.e. artificial neural network (ANN)
    - Model architecture and topology (number of layers and "neurons")
    - Sigmoid activation function
    - Loss function
    - Optimizer
        - Stochastic gradient descent (SGD)
        - Adam
    - Model evaluation
        - Classification threshold values
        - Validation set
    - Model parameters
        - Plotting weight as function of iteration (batch)
- Comparing models

## Homework 4
Topics covered:
- Grid search (hyperparameter search algorithm)
- Backpropagation
    - Handwritten vs programmatic (Keras) calculations
    - Effects of diffferent initializations
- Testing classifiers with novel data
- Different activation functions
    - ReLU
    - Softmax
- Different loss functions
    - Cross entropy
- Tuning hyperparameters for optimization
    - Trade-offs (e.g. hidden layer size and learning rate)
