# Perceptron as Softmax Regression (End-to-End ML Project)

This project demonstrates an **end-to-end Machine Learning workflow** using a **Perceptron classifier** for multiclass classification.

The model is trained on the **Iris dataset** and shows how a Perceptron can behave similarly to **Softmax Regression** for linear decision boundaries.

---

# Project Workflow

The notebook covers the complete ML pipeline:

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Data Visualization
4. Feature Engineering
5. Train/Test Split
6. Feature Scaling
7. Model Training (Perceptron)
8. Model Evaluation
9. PCA Visualization

---

# Dataset

Dataset used: **Iris Dataset**

Features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Target Classes:

- Setosa
- Versicolor
- Virginica

Total samples: **150**

---

# Exploratory Data Analysis

EDA steps include:

- Dataset inspection
- Summary statistics
- Class distribution
- Pairplot visualization
- Correlation heatmap

These help understand relationships between features.

---

# Model

Model used:

**Perceptron (Linear Classifier)**

Why Perceptron?

- Simple linear model
- Works well for linearly separable data
- Supports multiclass classification

Although not probabilistic like Softmax Regression, the perceptron creates **multiple decision boundaries** for different classes.

---

# Training Pipeline

Steps:

1. Load dataset using `sklearn.datasets`
2. Convert dataset to pandas DataFrame
3. Perform exploratory data analysis
4. Split data into train/test
5. Standardize features using `StandardScaler`
6. Train perceptron classifier
7. Generate predictions

---

# Model Evaluation

Evaluation metrics used:

- Accuracy Score
- Confusion Matrix
- Classification Report
- PCA visualization

Example output:

Accuracy ≈ **93%**

---

# Visualization

Visualizations included:

- Pairplot
- Correlation heatmap
- PCA projection plot
- Confusion matrix heatmap

---

# Tech Stack

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---
perceptron-softmax-classifier
│
├── Perceptron_as_softmax_classifier.ipynb
├── README.md
├── requirements.txt


---

# How to Run

Clone the repository:


git clone https://github.com/yourusername/perceptron-softmax-classifier.git


Install dependencies:


pip install -r requirements.txt


Run the notebook:


jupyter notebook


---

# Learning Outcomes

This project demonstrates:

- End-to-end ML workflow
- Exploratory Data Analysis
- Feature scaling importance
- Linear classifiers
- Multiclass classification
- Model evaluation techniques

---

# Author

Devendra Kushwah

AI/ML Developer

# Project Structure
