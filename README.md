# SafeInsights – Diabetes Prediction Using Machine Learning

## About the Project

SafeInsights is a Machine Learning project that predicts whether a person is likely to have diabetes based on medical attributes such as glucose level, blood pressure, BMI, age, and other health-related information.

The project uses supervised Machine Learning classification algorithms to analyze medical data and predict the diabetes outcome.

## Objectives

- Predict diabetes outcomes using medical data.
- Apply Machine Learning classification algorithms.
- Understand data preprocessing and feature scaling.
- Evaluate model performance using classification metrics.
- Generate predictions for individual input records.

## Machine Learning Algorithms

### 1. Logistic Regression

Logistic Regression is a supervised Machine Learning algorithm used for binary classification. It estimates the probability of an outcome and classifies a person as diabetic or non-diabetic based on the model's prediction.

### 2. Decision Tree Classifier

Decision Tree is a supervised Machine Learning algorithm that learns decision rules from training data. It uses features such as glucose level, BMI, and age to make predictions by following branches in a tree structure.

## Technologies Used

- **Programming Language:** Python
- **Data Processing:** Pandas, NumPy
- **Machine Learning:** Scikit-learn
- **Data Visualization:** Matplotlib, Seaborn
- **Development Environment:** Jupyter Notebook

## Dataset

This project uses the Pima Indians Diabetes Dataset.

The dataset contains medical attributes that can be used to predict diabetes outcomes.

### Input Features

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

### Target Variable

The target column is `Outcome`.

- `0` – Non-diabetic
- `1` – Diabetic

## Project Workflow

1. Import the required Python libraries.
2. Load the dataset into a Pandas DataFrame.
3. Explore the dataset and understand its features.
4. Separate input features and the target variable.
5. Split the dataset into training and testing sets.
6. Apply feature scaling using StandardScaler where required.
7. Train the Logistic Regression and Decision Tree models.
8. Generate predictions using the trained models.
9. Evaluate model performance using appropriate metrics.
10. Accept individual medical inputs and generate a prediction.

## Data Preprocessing

Data preprocessing prepares the dataset for Machine Learning.

- Inspect the dataset and its structure.
- Separate features (`X`) from the target (`Y`).
- Split the data into training and testing sets.
- Standardize features when required by the algorithm.

StandardScaler transforms features using statistics learned from the training data. The same fitted scaler should be used to transform test data and new inputs.

## Model Evaluation

The models can be evaluated using the following metrics:

- **Accuracy:** Measures the proportion of correct predictions.
- **Precision:** Measures how many positive predictions are correct.
- **Recall:** Measures how many actual positive cases are identified.
- **F1-Score:** Combines precision and recall into a single metric.
- **Confusion Matrix:** Shows correct and incorrect classifications for each class.

These metrics provide a better understanding of model performance than accuracy alone.

## Making Predictions

The project supports predictions for individual input records.

The prediction process involves:

1. Providing medical feature values in the expected order.
2. Converting the input into a NumPy array.
3. Reshaping the input for a single prediction.
4. Applying the fitted scaler if the selected model requires scaled input.
5. Passing the processed input to the trained model.
6. Interpreting the predicted outcome.

The output is interpreted as:

- `0` – Non-diabetic prediction
- `1` – Diabetic prediction

## Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/kumargarg82561/SafeInsights-Diabetes-Prediction.git
```

### 2. Navigate to the Project Directory

```bash
cd SafeInsights-Diabetes-Prediction
```

### 3. Install Dependencies

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

### 4. Run Jupyter Notebook

```bash
jupyter notebook
```

Open the project's diabetes prediction notebook and execute the cells in order.

Ensure that the dataset file is available at the path specified in the notebook.

## Project Structure

```text
SafeInsights-Diabetes-Prediction/
│
├── README.md
├── Diabete.ipynb
└── diabetes.csv
```

*Note: Update the notebook and dataset filenames in this structure if they differ from the actual files in your repository.*

## Future Improvements

- Compare the performance of Logistic Regression and Decision Tree.
- Tune model hyperparameters to improve generalization.
- Improve data preprocessing and feature selection.
- Develop a simple web interface for user input and predictions.
- Explore additional evaluation techniques.

## Disclaimer

This project is intended for educational and learning purposes only. Predictions generated by this model should not be used as a substitute for professional medical advice, diagnosis, or treatment.

## Author

**Kumar Garg**

GitHub: [kumargarg82561](https://github.com/kumargarg82561)
