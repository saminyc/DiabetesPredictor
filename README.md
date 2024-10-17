## **Diabetes Prediction Model**

**Description:**

This project aims to predict the onset of diabetes using a decision tree classifier. It takes patient data as input and outputs a prediction of whether the patient is likely to develop diabetes.

**Data:**

The dataset used for this project is the Pima Indian Diabetes Dataset. It contains 768 instances with 8 attributes (features) and a class label (outcome).

**Preprocessing:**

* **Data loading:** The dataset was loaded from a CSV file named "diabetes.csv".
* **Data exploration:** The data was explored using `head()`, `info()`, `describe()`, and visualization techniques to understand its characteristics.
* **Handling missing values:** No missing values were found in the dataset.
* **Handling duplicates:** No duplicate instances were found.
* **Feature selection:** The following features were used as input to the model: Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, and Age.
* **Target variable:** The target variable was "Outcome", indicating whether the patient has diabetes (1) or not (0).

**Model:**

* **Algorithm:** A decision tree classifier was used for the prediction task.
* **Hyperparameters:** The default hyperparameters of the `DecisionTreeClassifier` were used.
* **Training and evaluation:** The data was split into training and testing sets (80/20 ratio), and the model was trained on the training set. The performance was evaluated on the testing set using accuracy.

**Results:**

* **Evaluation metrics:** The model achieved an accuracy of **[0.746]** on the testing set.

**To use this project:**

1. **Clone the repository:** `git clone [https://github.com/saminyc/DiabetesPredictor/]`
2. **Run the model:** `python main.py`
