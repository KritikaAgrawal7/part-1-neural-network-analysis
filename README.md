Neural Network Fundamentals and Training Behavior Analysis

Project Overview

This project focuses on building a neural network model for customer churn prediction using structured customer data. The goal of the project was to understand the fundamentals of neural networks, preprocessing techniques, model training, evaluation, and hyperparameter experimentation using TensorFlow/Keras.

The project also explores how changing neural network configurations impacts model performance.

Dataset Source

The dataset used for this assignment was taken from the Google Drive link shared in the assignment instructions.

The dataset contains customer-related information such as:

-Region
-Plan type
-Contract type
-Monthly charges
-Customer tenure
-Payment methods
-Data usage
-Support tickets
-Satisfaction score
-Churn status

Target variable:

->churn
    0 = Customer retained
    1 = Customer churned


Project Workflow

1. Dataset Understanding and Exploration

The dataset was first explored to understand:

* number of rows and columns,
* data types,
* missing values,
* statistical summary,
* churn distribution.

A visualization was also created to analyze customer churn distribution.

2. Data Preprocessing

The following preprocessing steps were performed before model training:

* removed unnecessary columns,
* separated features and target variable,
* encoded categorical variables using one-hot encoding,
* split data into training and testing sets,
* scaled features using StandardScaler.

3. Neural Network Model Building

A feed-forward neural network was created using TensorFlow/Keras.

The architecture included:

* input layer,
* hidden layers with ReLU activation,
* output layer with Sigmoid activation.

The model was compiled using:

* Adam optimizer,
* Binary Crossentropy loss function,
* Accuracy metric.

4. Model Training and Evaluation

The model was trained and evaluated using:

* training accuracy,
* validation accuracy,
* test accuracy,
* confusion matrix,
* classification report.

Training and validation accuracy graphs were also generated for performance analysis.

5. Hyperparameter Experimentation

Multiple experiments were conducted by modifying:

* number of neurons,
* hidden layers,
* network architecture.

The experiment results were compared using a model comparison table.

Results and Observations

* The neural network achieved high prediction accuracy.
* Training and validation accuracy remained closely aligned, indicating minimal overfitting.
* Additional neurons and hidden layers did not significantly improve performance because the baseline model was already performing well.
* The dataset appeared to be relatively learnable for a neural network model.