# worldwidebillionaireanalysis

 Worldwide Billionaire Analysis Project README


Introduction - 
This repository houses the code and resources related to a dissertation project focusing on ensemble learning techniques. The project particularly emphasises the use of XG Boost and Bagging Classifier with Logistic Regression as the models for predictive modelling. The research aims to evaluate the performance efficiency of the ensemble model through various metrics such as accuracy and area under the Receiver Operating Characteristic (ROC) curve (AUC).

Usage


After cloning the repository, you can run the Jupyter Notebook file DissertationCodeFile.ipynb to go through the research step-by-step. The notebook is well-documented and segmented into different sections, making it easy to understand and follow.

Project Structure


The project mainly consists of a Jupyter Notebook that can be broadly divided into the following sections:

Library Imports: Importing essential Python libraries for data manipulation and modelling.
Data Preparation: Loading and cleaning the dataset, feature selection, and transformations.
Model Definition: Defining the base model (Logistic Regression) and the ensemble model (Bagging Classifier).
Model Evaluation: Employing K-Fold cross-validation with 5 folds for robust performance evaluation.
Results Interpretation: Analysing the performance metrics.


Technical Overview
The notebook begins by importing necessary Python libraries like pandas for data manipulation. Subsequently, the dataset is loaded, and preliminary data cleaning operations are performed. The research focuses on selecting relevant features and applies transformations like one-hot encoding for categorical variables. Standard scaling is also utilised to ensure all features are on the same scale, thereby assisting models like Logistic Regression.

For model definition, Logistic Regression is chosen as the base model, and a Bagging Classifier is utilised to create an ensemble consisting of 50 base models. The project employs K-Fold cross-validation with 5 folds for a robust evaluation of model performance.

Performance Metrics


The research aims to gauge the efficiency of the ensemble model through metrics like accuracy and area under the ROC curve (AUC). K-Fold cross-validation is used to obtain these metrics, which are calculated and presented for each fold. The research emphasises the mean accuracy and mean AUC as key indicators of the model's effectiveness. A higher mean accuracy and mean AUC are indicative of superior model performance.
