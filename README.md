# Breast Cancer Classification using Logistic Regression

This project demonstrates a classification task for predicting whether a breast cancer tumor is malignant or benign using a logistic regression model.

## Libraries Used
- `pandas`: For data manipulation.
- `numpy`: For numerical operations.
- `sklearn`: For machine learning tasks (train-test split, scaling, logistic regression, evaluation metrics).
- `matplotlib` and `seaborn`: For visualization.

## Dataset
The dataset used in this project is a breast cancer dataset, which contains features of cell nuclei from breast cancer biopsies. The target variable is the diagnosis (`diagnosis`), which is binary: "M" for malignant and "B" for benign.

### Data Preprocessing
1. The 'id' and 'Unnamed: 32' columns are dropped.
2. The target variable (`diagnosis`) is converted into binary format: 'M' becomes 1 and 'B' becomes 0.
3. Features are standardized using `StandardScaler`.

## Steps
1. **Data Loading**: Loads the dataset from `data (2).csv`.
2. **Data Cleaning**: Removes unnecessary columns and encodes the target variable.
3. **Model Training**: Splits the dataset into training and testing sets, standardizes the features, and fits a logistic regression model.
4. **Model Evaluation**: Evaluates the model using confusion matrix, precision, recall, and ROC-AUC.
5. **ROC Curve**: Plots the ROC curve with the computed AUC value.
6. **Threshold Tuning**: Plots precision and recall scores for different classification thresholds.

## Results
- The confusion matrix, precision, recall, and ROC-AUC score are printed.
- A ROC curve is plotted to evaluate the model's performance.
- Precision and recall are plotted against different classification thresholds.

## Requirements
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn


