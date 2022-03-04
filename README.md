# Phishing-Domain-Detection
Phishing is a form of fraud in which the attacker tries to learn sensitive information such as login credentials or account information by sending as a reputable entity or person in email or other communication channels Phishing is popular among
attackers because it is easier to persuade someone to click a malicious link that appears
to be authentic than it is to break through a computer's protection measures..

![phishing-detection-with-Python](https://user-images.githubusercontent.com/73115703/156777858-0d078b8e-4b4e-4ce1-aa27-e35681c71677.jpg)

**Data Collection:** 
This Data Set collected to this https://data.mendeley.com/datasets/72ptz43s9v/1 This site provide a set of phishing Data in csv format,This data Set contribtes Grega Vrbančič,This data set many columns are produced by seen the data in given link

**Feature Extraction:**
The below mentioned category of features are extracted from the dataset:
1.URL-Based Features
2.Domain-Based Features
3.Page-Based Features
4.Content-Based Features

 This all Features Taken to to the Data Set and trained with Different machine learning model, Below Features are most important features 
 
![output](https://user-images.githubusercontent.com/73115703/156782310-6c722013-e5bc-490e-837b-e2f602e45b4c.png)

**Models**

Before starting the ML model training, the data is split into 80:20 (train : test). From the dataset, it is clear that this is a supervised machine learning task. There are two major types of supervised machine learning problems, called classification and regression. This dataset comes under classification problem, as the input URL is classified as Real (1) or Fake (0). The machine learning models considered to train the dataset in this project are:

XGBClassifier
Decision Tree
Random Forest
LogisticRegression
All these models are trained on the train dataset and evaluation of the model is done with the test dataset.

**Results**

From the obtained results of the above models, XGBoost Classifier has highest model performance of 92%. So the model is saved to the file XGBClassifier

