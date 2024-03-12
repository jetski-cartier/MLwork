# MLwork
machine learning class lab

Synthetic Data for Binary Classification
This repository contains code for generating synthetic data for a binary classification problem and training a Decision Tree Classifier to predict the classes. The synthetic dataset consists of 1500 instances with two classes: 0 or 1. Class 1 is generated using three Gaussian distributions with means [6, 14], [10, 6], and [14, 14], while Class 0 is generated using a uniform distribution with a range of 20.

Model Training and Evaluation
After generating the synthetic dataset, a Decision Tree Classifier is trained and evaluated using the generated data. The code for training and evaluating the classifier can be found in the train_and_evaluate.ipynb notebook.

Requirements
Python 3.x
NumPy
Matplotlib
scikit-learn
Usage
Clone this repository to your local machine.
Navigate to the repository directory.
Open and run the generate_data.ipynb notebook to generate the synthetic dataset.
Open and run the train_and_evaluate.ipynb notebook to train and evaluate the Decision Tree Classifier.
Analyze the results and visualization provided in the notebook.
Results
The results of the model training and evaluation, including accuracy scores and visualization of the accuracy versus maximum depth, are provided in the train_and_evaluate.ipynb notebook.
