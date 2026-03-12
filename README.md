# Predict-Diabetes-using-logistic-regression
# Diabetes Prediction using Logistic Regression

## 📌 Project Overview

This project predicts whether a patient is **diabetic or non-diabetic** using **Logistic Regression**, a supervised machine learning algorithm used for binary classification.

The model is trained on the **Pima Indians Diabetes Dataset**, which contains medical diagnostic measurements for predicting diabetes in patients.

The workflow includes:

* Loading the dataset from a **URL**
* Data preprocessing
* Training a **Logistic Regression model**
* Evaluating performance using **accuracy, confusion matrix, and classification report**
* Visualizing results with a **heatmap**
* Predicting diabetes for new patient data

---

## 📂 Dataset

The dataset used is the **Pima Indians Diabetes Dataset**.

**Features included in the dataset:**

| Feature                  | Description                                      |
| ------------------------ | ------------------------------------------------ |
| Pregnancies              | Number of pregnancies                            |
| Glucose                  | Plasma glucose concentration                     |
| BloodPressure            | Diastolic blood pressure                         |
| SkinThickness            | Triceps skin fold thickness                      |
| Insulin                  | 2-Hour serum insulin                             |
| BMI                      | Body Mass Index                                  |
| DiabetesPedigreeFunction | Diabetes family history function                 |
| Age                      | Age of the patient                               |
| Outcome                  | Target variable (0 = Non-Diabetic, 1 = Diabetic) |

Dataset Source:
https://raw.githubusercontent.com/jbrownlee/Datasets/master/pima-indians-diabetes.data.csv

---

## 🛠 Technologies Used

* Python
* Pandas
* Scikit-learn
* Seaborn
* Matplotlib

---

## ⚙️ Installation

Install the required libraries before running the project:

```bash
pip install pandas scikit-learn seaborn matplotlib
```

---

## ▶️ How to Run the Project

1. Clone the repository or download the Python script.
2. Open terminal or command prompt.
3. Run the script:

```bash
python diabetes_prediction.py
```

---

## 📊 Model Workflow

1. Load dataset from URL
2. Assign column names
3. Split dataset into training and testing sets
4. Train a Logistic Regression model
5. Evaluate model performance
6. Visualize the confusion matrix
7. Predict diabetes for new patient data

---

## 📈 Model Evaluation

The model is evaluated using:

* **Accuracy Score**
* **Confusion Matrix**
* **Classification Report**

Example output:

```
Accuracy: 0.77
```

Confusion matrix visualization helps understand how many predictions were correct or incorrect.

---

## 🔍 Example Prediction

Input sample:

```
Pregnancies: 5
Glucose: 120
BloodPressure: 72
SkinThickness: 35
Insulin: 80
BMI: 32.0
DiabetesPedigreeFunction: 0.5
Age: 42
```

Output:

```
Predicted Output: Diabetic / Non-Diabetic
```

---

## 📷 Visualization

The confusion matrix is displayed as a **heatmap using Seaborn** to clearly show model performance.

---

## 🚀 Future Improvements

Possible improvements for this project:

* Data preprocessing and normalization
* Feature selection
* Hyperparameter tuning
* Deploying the model using **Flask web app**
* Building a **user interface for prediction**

---

## 📄 License

This project is for **educational and learning purposes**.

---

## 👨‍💻 Author

Muhammad Suffiyan Rafi
Computer Science Student
