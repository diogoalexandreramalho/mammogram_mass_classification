# Mammogram mass: benign or malignant

We'll be using the "mammographic masses" public dataset from the UCI repository (source: https://archive.ics.uci.edu/ml/datasets/Mammographic+Mass)

This data contains 961 instances of masses detected in mammograms, and contains the following attributes:

   1. BI-RADS assessment: 1 to 5 (ordinal)  
   2. Age: patient's age in years (integer)
   3. Shape: mass shape: round=1 oval=2 lobular=3 irregular=4 (nominal)
   4. Margin: mass margin: circumscribed=1 microlobulated=2 obscured=3 ill-defined=4 spiculated=5 (nominal)
   5. Density: mass density high=1 iso=2 low=3 fat-containing=4 (ordinal)
   6. Severity: benign=0 or malignant=1 (binominal)

A lot of unnecessary anguish and surgery arises from false positives arising from mammogram results. If we can build a better way to interpret them through supervised machine learning, it could improve a lot of lives.

## Goal

The goal is to find the ML method that achieves the highest accuracy in predicting whether a mass is benign or malignant.

To achieve this, a few steps were followed:
1. Exploratory Data Analysis
2. Data Pre-processing
3. Apply different supervised machine learning methods

The methods include:
* Decision Tree
* Random Forest
* KNN
* Naive Bayes
* SVM
* Logistic Regression
* Neural Network

## Contributions
This work was inspired from the Udemy course Machine Learning in Python by Sundog, but was individually done by Diogo Ramalho.
