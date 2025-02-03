# 🌸 Iris Classification using Machine Learning
![Iris Flower](https://upload.wikimedia.org/wikipedia/commons/thumb/4/41/Iris_versicolor_3.jpg/320px-Iris_versicolor_3.jpg)

## 📌 Project Overview
This project explores **classification of iris plant species** using **supervised machine learning models**. The goal is to **predict the species of an iris flower** (*Iris-setosa, Iris-versicolor, or Iris-virginica*) based on its **sepal and petal measurements**.

This repository includes:
- **Exploratory Data Analysis (EDA)**
- **Supervised Learning Models** for classification
- **Hyperparameter Tuning**
- **Model Evaluation & Comparisons**
- **GitHub version control and project structure**

## 📂 Dataset Information
The dataset used is the **Iris dataset**, one of the most well-known classification datasets in machine learning. It consists of:
- **150 instances**
- **4 numerical features**:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- **Target Variable:** *Iris Species (Categorical)*
  - *Iris-setosa*
  - *Iris-versicolor*
  - *Iris-virginica*

### 📝 Data Source
- This dataset was originally introduced by **Ronald Fisher** in 1936 and is commonly used in classification problems.
- The dataset is publicly available from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris).

## 🛠 Methodology
### 🔍 Step 1: Exploratory Data Analysis (EDA)
- **Data Inspection:** Checked for missing values, duplicates, and general dataset structure.
- **Data Visualization:** 
  - **Histograms** to explore feature distributions.
  - **Pairplot & Scatter Plots** to examine relationships between numerical features.
  - **Boxplots** to check for outliers.
  - **Correlation Matrix** to identify potential feature relationships.

### 📊 Step 2: Model Training & Evaluation
- **Train-Test Split** (80% training, 20% testing)
- **Supervised Learning Models Used:**
  - **Logistic Regression**
  - **K-Nearest Neighbors (KNN)**
  - **Support Vector Machine (SVM)**
  - **Random Forest**
- **Model Evaluation Metrics:**
  - Accuracy
  - Precision, Recall, F1-score
  - Confusion Matrix

### 🔧 Step 3: Hyperparameter Tuning
- **GridSearchCV** was used to find the best hyperparameters for **Random Forest**.
- **Cross-validation** was applied to evaluate model performance.

## 📈 Results & Key Findings
| Model                  | Accuracy | F1 Score |
|------------------------|---------|----------|
| Logistic Regression    | 96.67%  | 0.97     |
| K-Nearest Neighbors   | 100%    | 1.00     |
| SVM (Linear Kernel)    | 100%    | 1.00     |
| Random Forest         | 93.33%  | 0.93     |

### 💡 Insights
- **Petal length & width** are the most distinguishing features for classification.
- **SVM and KNN achieved 100% accuracy**, indicating that the dataset is **well-structured and linearly separable**.
- **Random Forest performed well but slightly underperformed compared to SVM & KNN.**
- **Hyperparameter tuning improved Random Forest performance.**

## 🚀 Installation & Setup
1. **Clone the Repository**
   ```bash
   git clone https://github.com/saintmarina/iris-classification.git
   cd iris-classification