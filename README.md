# SafeInsights - Diabetes Prediction

## Project Overview

SafeInsights is a Machine Learning project developed to predict whether a person is diabetic or non-diabetic based on medical attributes. The model is built using Python and Scikit-learn and uses the PIMA Indians Diabetes Dataset.

The project demonstrates the complete Machine Learning workflow, including data preprocessing, feature scaling, model training, and prediction.

---

## Features

- Data loading and preprocessing
- Exploratory Data Analysis (EDA)
- Feature scaling using StandardScaler
- Train-Test Split
- Machine Learning model training
- Diabetes prediction system
- Prediction on custom input data

---

## Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Scikit-learn

---

## Dataset Information

The dataset contains the following features:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

Target Variable:

- Outcome
  - 0 → Non-Diabetic
  - 1 → Diabetic

---

## Project Workflow

```text
1. Import Required Libraries
2. Load Diabetes Dataset
3. Analyze Dataset
4. Separate Features and Labels
5. Standardize Data
6. Split Dataset into Training and Testing Sets
7. Train Machine Learning Model
8. Evaluate Model Performance
9. Build Prediction System
```

## Project Structure

```text
SafeInsights-Diabetes-Prediction/
│
├── Diabetes.ipynb
├── diabetes.csv
├── README.md
└── requirements.txt
```

## Installation

### Clone the Repository

```bash
git clone https://github.com/kumargarg82561/SafeInsights-Diabetes-Prediction.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Project

```bash
jupyter notebook
```

Open `Diabetes.ipynb` and run all the cells.

---

## Sample Prediction

The model takes the following input:

```python
input_data = (6,148,72,35,0,33.6,0.627,50)
```

Output:

```text
The person is diabetic.
```

---

## Author

**Kumar Garg**

- GitHub: https://github.com/kumargarg82561

---

⭐ If you found this project useful, don't forget to star the repository!
