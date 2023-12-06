# Supervised Machine Learning - Classification
## Goal
To explore the practical application of ML by trying to predict poisonous mushrooms, noticing the trade off between accuracy and safety. 

## Overview 
We are interested in keeping Catalonian mushroom foragers safe from poisonous mushrooms, and therefore our aim is to completely eliminate Type II errors.

## Context
In general, the aim of fine-tuning and perfecting the algorithms is to get our accuracy to close to perfection. However, this time around the emphasis is on Error Types and the delicate dance between accuracy and safety.

1. Are there any ML algorithms that by default err on the side of caution?
2. Can we achieve 0 hospital cases with adjusting tresholds and exploring ROC curves?

### Task: 
* Import mushroom database
* Explore and analyze features
* Experiment with several ML models
* Experiment with tresholds while keeping an eye on accuracy
* Explore ROC curve
* Test our algorithm on data it has never seen before
* Rinse and repeat

## Deliverables
The **Google Colab Notebook** for trying out different ML algorithms is found [here]() with a supporting Medium article that outlines my thinking process and practical takeaways more in detail [here](https://medium.com/@ubp0528/poisonous-mushrooms-striking-a-balance-between-accuracy-and-safety-with-machine-learning-80b77112e6dd).

## Skills & Tools
1. Data Reading & Cleaning 
2. Data Splitting 
3. Building a Preprocessor
4. LazyPredict & Modelling
5. Error Analysis
6. Tresholds and ROC Curve analysis

## Note to the Reader about my choice of models to try:
My aim after running LazyPredict was to ** experiment with algorithms based on various mathematical models**. 
RandomForest is a Decision Tree-based classifier, Label Propagation is a semi-supervised learning model, LGBM is a gradient boosting method, KNN groups data into “neighborhoods” based on similarities, while SVC looks for and calculates distances for the optimal hyperplane to divide the data into classes. 
By exploring various methods based on different mathematical models, I was curious whether any one of them would be more or less prone to a certain error type. 
