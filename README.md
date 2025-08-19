# scikit-learn-pipeline-for-census-income-data
This project demonstrates a ML pipeline using scikit-learn to classify income levels based on demographic and employment data from the US Census dataset. The dataset is in LIBSVM format, which is sparse and has to be pre-processed. 

## Objective
- Build a cassification pipeline using Decision Tree CLassifier (DTC).
- Normalize the fratures using StandardScaler.
- Cross-validation to rvaluate baseline performance.
- Use GridSearchCV for hyperparameter tuning.
- Perform model validation using train-test split.

## Tools and Techniques
- Google Colab
- Python: scikit-learn, standardScaler, DTC, GridSearchCV, cross_val_Score, train_test_split

## Structure of Code
Part 1: Pipeline with cross validation
- converting sparse data to dense format.
- build a pipeline with StandardScaler and DecisionTreeClassifier.
- Use 5 fold cross-validation.

Part 2: Hyperparameter Tuning
- defining the parameter grid for criterion and max_depth.
- Find best model config using GridSearchCV.
- Find the cross validation score.

Part 3: Train-Test Split Evaluation
- split the data into trainng and testing
- Use grid search on training data to fit the pipeline.
- Evaluate the best model on scaled test data.

## Conclusion
The primary motive behind this work was to build a ML pipeline that reflects model development and evaluation. The dataset used in this project was sparse, the workflow was divided into three phases. 
