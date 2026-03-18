#  Breast Cancer Detection with Missing Value Treatment & Machine Learning

##  Overview

This project predicts breast cancer (benign vs malignant) using multiple machine learning algorithms. It focuses on handling missing values, preprocessing data, and comparing different models to achieve high accuracy and reliability.

---

##  Key Highlights

*  Handled missing values in the dataset (Bare Nuclei column)
*  Applied data preprocessing and feature scaling
*  Trained and compared multiple machine learning models
*  Achieved high classification accuracy (~97%)
*  Evaluated models using accuracy and classification reports

---

##  Tech Stack

* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn

---

##  Dataset

* **Dataset:** Wisconsin Breast Cancer Dataset (WBCD)
* Features are computed from digitized images of breast mass
* Target values:

  * `2` → Benign
  * `4` → Malignant

---

##  Workflow

### 1. Data Loading

* Loaded dataset using Pandas
* Cleaned and standardized column names

### 2. Missing Value Treatment

* Identified missing values in **"Bare Nuclei"** column
* Converted values to numeric format
* Handled missing entries to ensure clean data

### 3. Data Preprocessing

* Feature scaling using StandardScaler
* Split the dataset into training and testing sets

### 4. Model Training

Trained and evaluated the following models:

* Logistic Regression
* Naive Bayes (GaussianNB)
* Support Vector Machine (SVM)
* Random Forest
* K-Nearest Neighbors (KNN)
* Decision Tree
* Extra Trees Classifier
* Gradient Boosting
* AdaBoost

---

##  Results

* Achieved **~97% accuracy** on best-performing models
* Ensemble models like Random Forest and Gradient Boosting performed best
* Used classification reports for evaluation

---

##  How to Run

### Option 1: Google Colab

1. Upload the notebook to Google Colab
2. Mount Google Drive (if dataset is stored there)
3. Update dataset path
4. Run all cells

### Option 2: Local Setup

Install dependencies:

```
pip install pandas numpy scikit-learn
```

Run:

```
jupyter notebook
```

---

##  Output

* Accuracy scores for each model
* Classification reports
* Model comparison

---

##  Key Learnings

* Importance of handling missing values in real-world datasets
* Comparison of different ML algorithms
* Impact of preprocessing on model performance
* Effectiveness of ensemble methods

---

##  Future Improvements

* Add visualization (confusion matrix, ROC curves)
* Hyperparameter tuning
* Deploy using Flask / FastAPI
* Build real-time prediction interface



