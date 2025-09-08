# Diabetes Prediction Project

This notebook demonstrates a machine learning project aimed at predicting diabetes based on patient diagnostic measurements. The project follows a standard machine learning workflow, including data exploration, preprocessing, model training and evaluation, and deployment.

## Project Phases

The project is structured into the following phases:

### Phase 1: Exploratory Data Analysis (EDA)
- Loading and understanding the dataset.
- Exploring key features and their relationship with the outcome variable.
- Visualizing data distributions and correlations.

### Phase 2: Data Preprocessing
- Standardizing features to ensure they are on a similar scale.
- Splitting the dataset into training and testing sets for model development and evaluation.

### Phase 3: Model Building and Evaluation
- Implementing and training different machine learning models:
    - Logistic Regression
    - Support Vector Machine (SVM)
    - Random Forest
- Tuning model hyperparameters using GridSearchCV.
- Evaluating model performance using metrics such as accuracy, precision, recall, and F1 score.
- Visualizing confusion matrices for each model.

### Phase 4: Deployment
- Selecting the best-performing model based on evaluation metrics.
- Creating a function to predict diabetes for new patient data.

## Models Used

- **Logistic Regression:** A linear model for binary classification.
- **Support Vector Machine (SVM):** A powerful model that finds the optimal hyperplane to separate classes.
- **Random Forest:** An ensemble learning method that builds multiple decision trees to improve prediction accuracy.

## How to Use the Notebook

1.  Run each code cell sequentially to execute the project workflow.
2.  The EDA section provides visualizations to understand the data.
3.  The Data Preprocessing section prepares the data for model training.
4.  The Model Building and Evaluation section trains and evaluates the chosen models.
5.  The Deployment section includes a function to make predictions on new data.

## Dataset

The dataset used in this project is the Pima Indians Diabetes Database, which is available in the notebook environment.

## Dependencies

The following libraries are required to run this notebook:
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
