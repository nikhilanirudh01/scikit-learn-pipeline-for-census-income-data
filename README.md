# scikit-learn-pipeline-for-census-income-data
This project demonstrates how to build a machine learning pipeline using Scikit-Learn for a binary classification task. The dataset used is the US Census Income (a9a) dataset in LibSVM format, which contains demographic and employment attributes to predict whether an individual's income exceeds $50K/year.

## Pipeline overview
- The pipeline consists of two main components: StandardScaler and Decision Tree Classifier
- Since the dataset's format is sparse, we have to convert it into a dense matrix using **.todense()** function before applying the scaler.
- **Part 1** of the code depicts the baseline performance using default decision tree parameters.
- **Part 2** optimizes the model performance by tuning splitting criteria and the tree depth.
- **Part 3** validate the model generalization on unseen data usinf appropriate hyperparameters.
