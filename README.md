# Jupyter-Notebook-Template
a notebook template for quick prototyping of machine learning solutions

## Below are the high level sections in the notebook and breif on what it contains

### 1. Setting up workspace and evnironments
* This section briefly just mentions to setup anaconda and create virtual environments, also commands to quickly download all the necessary packages.
* Ideally it should not be a part of notebook, but creating virtual environments is very important and this section is there for any person who missed this step.

### 2. Importing required libraries
* contains import statements for all the necessary libraries
* It includes import statements for matplotlib, pandas, numpy, sklearn regression and classification models and etc.

### 3. Load Data
* few lines of code on you can load data from csv and excel files using pandas

### 4. Quick look at the data
* code for getting a high level idea of the dataset
* code for identifying the categorical and numerical column 

### 5. Test set creation
* code for keeping a test set separate in the intial steps itself
* Human brains are good in pattern identification, hence better to keep a test set separate in the intial stages so that our decision wont get affected by the test data

### 6. Discover and Visualise the data to gain insights
* code for creating a copy of train set first so that we can play with it freely
* scatter and histogram plots for categorical and numerical attributes
* fidning correlations using Pearson's coefficient.
* alternatively you can use pandas scatter_matrix function mentioned in this section.

### 7. Experiment with attribute combinations
* this section is kept separate to focus on comibing attributes if needed
* Introducing new attribtues in this section by combining existing attributes

### 8. Prepare the data for machine learning algorithms
* This section includes step for data cleaning
* missing value treatments for numerical attributes
* encoding for categorical/text attributes
* code for creating custom transformers so that our data preparation step will be compatibe with sklearn features such as pipeline

### 9. Select and train a model
* try out varios models here and shortlist few of those
* popular classifiation and regression models code is provided from sklearn library
* cross-validation code is provided for better evaluation of models on the train set
* code for saving model is provided using "joblib" library

### 10. Fine Tune your shortlisted models
* code for grid search is provided.
* code for seeing the best parameters and estimator using grid search is provided.
* alternate option to grid search is provided which is "randomised search"

### 11. Evaluated your tuned models on the test set
* code for evaluating models on test set using different metrics is provided in this section.



That's all. If you stumbled upon this template and try to use it, then pleas do give a feedback to improve it! Thanks.
