# 🚢 Titanic Survival Prediction

This is a beginner-friendly machine learning project that uses the Titanic dataset to predict whether a passenger survived the Titanic disaster based on various features like age, gender, ticket class, and fare.

## 📌 Project Objectives

* Load and explore real-world datasets using Pandas
* Perform data cleaning and preprocessing
* Conduct Exploratory Data Analysis (EDA)
* Build and evaluate classification models
* Understand feature importance in predictions

---

## 📂 Dataset

* **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)
* Files used: `train.csv`

---

## 🛠️ Technologies Used

* **Language**: Python
* **Libraries**:

  * Pandas & NumPy (data manipulation)
  * Matplotlib & Seaborn (visualization)
  * Scikit-learn (machine learning)

---

## 🧪 Steps Performed

1. **Data Loading**
   Loaded the dataset using `pandas.read_csv()` and checked structure with `.info()` and `.describe()`.

2. **Data Cleaning**

   * Filled missing values in `Age` and `Embarked`.
   * Dropped the `Cabin` column due to too many missing values.

3. **Feature Encoding**

   * Converted `Sex` to numeric.
   * Applied one-hot encoding to `Embarked`.

4. **Model Building**

   * Selected features and target variable.
   * Trained a Random Forest classifier using `scikit-learn`.

5. **Model Evaluation**

   * Evaluated accuracy using a test split.
   * Visualized feature importance.

---

## 📊 Results

* Achieved decent prediction accuracy using Random Forest
* Learned how feature selection and cleaning impact model performance

---

## 📌 Next Steps

* Improve the model with hyperparameter tuning
* Try other classifiers like Logistic Regression and XGBoost
* Submit predictions on Kaggle test set

---

## 📎 License

This project is open for learning and sharing. Feel free to fork and contribute.


