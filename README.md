# Heart Disease Prediction using Logistic Regression

    This repository contains a Python project that utilizes logistic regression to predict the presence of heart disease in patients based on their physical features. The model is trained and evaluated on a dataset containing 14 attributes, such as age, sex, cholesterol levels, and more.

## Dataset

    The dataset used in this project was obtained from the UCI Machine Learning Repository: Heart Disease Dataset. It contains 14 attributes, including the target variable, which indicates the presence (1) or absence (0) of heart disease.

## Attributes

    age
    sex
    chest pain type (4 values)
    resting blood pressure
    serum cholestoral in mg/dl
    fasting blood sugar > 120 mg/dl
    resting electrocardiographic results (values 0,1,2)
    maximum heart rate achieved
    exercise induced angina
    oldpeak = ST depression induced by exercise relative to rest
    the slope of the peak exercise ST segment
    number of major vessels (0-3) colored by flourosopy
    thal: 3 = normal; 6 = fixed defect; 7 = reversable defect
    target: 0 for no presence of heart disease, 1 for presence of heart disease

## Project Overview

    Data exploration and visualization: The dataset is first explored for missing values and relationships between features. Pair plots and heatmaps are created to visualize correlations between features.

    Data preprocessing: The dataset is split into training and testing sets, and the features are scaled using StandardScaler.

    Model training and hyperparameter tuning: A logistic regression model is trained using GridSearchCV to find the optimal values for hyperparameters such as C, penalty, and l1_ratio.

    Model evaluation: The model is evaluated on the test set using various metrics, such as confusion matrix, classification report, precision-recall curve, and ROC curve.

    Prediction: The trained model is used to make predictions for new patients based on their physical features.

## Usage

    Clone this repository.
    Ensure that you have Python 3.x installed, along with the required libraries mentioned in the code (numpy, pandas, seaborn, matplotlib, scikit-learn).
    Run the Python script to train and evaluate the logistic regression model.

## Dependencies

    numpy
    pandas
    seaborn
    matplotlib
    scikit-learn

### Contributing

    Contributions are welcome. Please open an issue or submit a pull request to suggest changes or improvements.


### Credits

    Mete Turkan
    linkedIn : linkedin.com/in/mete-turkan
    Inst : m_trkn46
