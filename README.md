# [ECS 171] Machine Learning
For future reference, this repo will store my homework assignments, as well as discussions (i.e. brief coding tutorials provided by TAs), from this course, which taught me the fundamentals of machine learning through hands-on experience. Everything in this course was done using Jupyter Notebooks. Each homework directory contains two notebooks: my attempt at the assignment and the solution to the assignment provided by the professor. You will find that there are only minor discrepancies between them, if any.

The following datasets are also included:
- **auto-mpg.data**
- **churn.txt**
- **bitstrings.csv**

Below is a list of topics covered corresponding to each homework assignment:

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
- Supervised learning
- Training set vs testing set
- Fitting model, making prediction, calculating error
    - Mean Squared Error (MSE)
- Model visualization
- Logistic regression
- Evaluation metrics
    - Precision
    - Recall
- Feature scaling
    - Min-max normalization

## Homework 3
Topics covered:
- Data Preprocessing
    - Normalizing numerical data
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
- Artificial neural networks (ANN)
    - Model architecture and topology
        - Number of layers and "neurons"
    - Activation functions
        - Sigmoid
    - Loss functions
    - Optimizers
        - Stochastic gradient descent (SGD)
        - Adam
    - Model evaluation
        - Classification threshold
        - Validation set
    - Model parameters
        - Plotting weight as function of iteration (batch)
- Comparing models

## Homework 4
Topics covered:
- Hyperparameter search algorithms
    - Grid search
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

## Homework 5
Topics covered:
- Unsupervised learning
- Hierarchical clustering
    - Agglomerative clustering
        - Top-down vs bottom-up approach
    - Linkage rules
        - Single linkage
        - Complete linkage
        - Average linkage
    - Distance functions
        - Euclidean distance
        - Manhattan distance
        - Cosine distance
    - Early stopping
        - Distance threshold
- K-means clustering
