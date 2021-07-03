# Note1 : all cell must be run in ORDER from top to bottom
# Note2: if some graphs are not produced for the first time, just run it again

# Preprocessing
This cell is mainly used to preprocess, split train data and validation data, use feature selection to transform the model

# Class label distribution graph
A bar chart that illustrate distribution of label in training set

# Running Models 
All models have their title on the notebook, with their relevant test result, test statistics.  There are in total 4 implemented models. Logistic regression, Random Forest(Long running time), Light GBM, Stacking(Long running time!!!!)

# Label prediction
Below each model, there is a section that can produce the corresponding predicting result, the result files are in a Kaggle format that can be found outside the file (E.g. MLR_Prediction.csv)

# Finding Models Result
To find numerical model testing result, it is contained in the cell of running model output
Below each model, it contain a ROC \AUC curve with a confusion matrix graph. Note: ROC\AUC curve can be slow for Random Forest

# Error Analysis
This cell of code contains error analysis result of two assumption, which contain two confusion matrices. First one is for modified random forest and second one is for modified logistic regression

