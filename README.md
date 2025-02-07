<h1 align="left">Sonar Rock vs Mine Prediction</h1>

###

<p align="left">This repository contains a machine learning project that predicts whether an object detected by sonar is a rock or a mine using logistic regression. The dataset used in this project is the Sonar dataset, which contains 208 samples with 60 features each, and the target variable is either "R" (Rock) or "M" (Mine).</p>

###


<h2 align="left">Project Overview</h2>

###

<p align="left">The goal of this project is to build a logistic regression model that can classify sonar signals into two categories: Rock (R) or Mine (M). The model is trained on a dataset containing 208 samples, each with 60 features representing the energy within a particular frequency band.</p>

###

<h2 align="left">Key Steps:</h2>

###

<p align="left">Data Loading: The dataset is loaded using pandas.<br><br>Data Preprocessing: The data is split into training and testing sets.<br><br>Model Training: A logistic regression model is trained on the training data.<br><br>Model Evaluation: The model's accuracy is evaluated on both the training and testing datasets.<br><br>Prediction: The model is used to predict whether a new sonar signal is a rock or a mine.</p>

###

<h2 align="left">Results</h2>

###

<p align="left">The logistic regression model achieved the following accuracy scores:<br><br>Training Accuracy: 83.42%<br><br>Testing Accuracy: 76.19%<br><br>These results indicate that the model performs reasonably well on the training data but has room for improvement on the testing data, suggesting potential overfitting.</p>

###
