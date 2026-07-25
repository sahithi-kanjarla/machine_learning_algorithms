# Machine Learning Algorithms with Python

A comprehensive collection of Machine Learning algorithms implemented using **Python** and **Scikit-learn**.

This repository was created as a hands-on learning resource to understand the intuition, implementation, evaluation, and practical applications of classical Machine Learning algorithms.

---

# Repository Structure

```
Machine-Learning/

├── Supervised Learning/
├── Unsupervised Learning/
└── Model Evaluation & Tuning/
```
```
Machine-Learning/

│── README.md
│
├── Supervised Learning/
│   ├── Linear Regression/
│   ├── Polynomial Regression/
│   ├── Logistic Regression/
│   ├── Decision Tree/
│   ├── Random Forest/
│   ├── K-Nearest Neighbors/
│   ├── Support Vector Machine/
│   └── Naive Bayes/
│
├── Unsupervised Learning/
│   ├── K-Means/
│   ├── Hierarchical Clustering/
│   ├── DBSCAN/
│   └── PCA/
│___ 
    Model Evaluation & Tuning.ipynb
    
```
---

# Supervised Learning

Supervised learning is a type of Machine Learning where the model learns from **labelled data**. The objective is to predict an output using known input-output examples.

It is divided into two categories:

- Regression
- Classification

---

## Regression Algorithms

Regression algorithms predict **continuous numerical values**.

### Linear Regression

**Problem Solved**

Predicts continuous values when the relationship between features and the target is approximately linear.

**Key Concepts**

- Best Fit Line
- Residuals
- Sum of Squared Errors (SSE)
- Mean Squared Error (MSE)

**Evaluation Metrics**

- R² Score
- MAE
- MSE
- RMSE

**Advantages**

- Simple
- Fast
- Easy to interpret

**Disadvantages**

- Assumes linear relationship
- Sensitive to outliers

**Applications**

- House Price Prediction
- Sales Forecasting
- Demand Prediction

---

### Polynomial Regression

**Problem Solved**

Models non-linear relationships by creating polynomial features.

**Key Concepts**

- Polynomial Features
- Degree
- Underfitting
- Overfitting

**Important Parameter**

- degree

**Evaluation Metrics**

- R² Score
- MAE
- MSE
- RMSE

**Applications**

- Population Growth
- Temperature Trends
- Growth Curves

---

## Classification Algorithms

Classification algorithms predict **discrete class labels**.

---

### Logistic Regression

**Problem Solved**

Binary classification using probabilities.

**Key Concepts**

- Sigmoid Function
- Decision Boundary
- Probability
- Threshold

**Evaluation Metrics**

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC-AUC

**Applications**

- Spam Detection
- Disease Diagnosis
- Loan Approval

---

### Decision Tree

**Problem Solved**

Creates a tree of decision rules using if-else logic.

**Key Concepts**

- Gini Impurity
- Entropy
- Information Gain
- Feature Importance

**Parameters**

- criterion
- max_depth
- random_state

**Advantages**

- Easy to interpret
- Handles non-linear data
- No feature scaling required

**Disadvantages**

- Can overfit

**Applications**

- Loan Approval
- Medical Diagnosis
- Customer Segmentation

---

### Random Forest

**Problem Solved**

Improves Decision Trees using multiple trees.

**Key Concepts**

- Bootstrap Sampling
- Feature Sampling
- Majority Voting

**Parameters**

- n_estimators
- max_depth
- random_state

**Advantages**

- High Accuracy
- Reduces Overfitting
- Provides Feature Importance

**Disadvantages**

- Slower than a single Decision Tree

**Applications**

- Fraud Detection
- Medical Diagnosis
- Customer Churn Prediction

---

### K-Nearest Neighbors (KNN)

**Problem Solved**

Predicts based on the nearest neighbouring data points.

**Key Concepts**

- Distance Metrics
- Feature Scaling
- Lazy Learning

**Parameters**

- k (n_neighbors)

**Advantages**

- Simple
- No Training Phase

**Disadvantages**

- Slow on large datasets
- Sensitive to feature scaling

**Applications**

- Recommendation Systems
- Image Classification
- Similarity Search

---

### Support Vector Machine (SVM)

**Problem Solved**

Finds the optimal decision boundary with the maximum margin.

**Key Concepts**

- Support Vectors
- Margin
- Kernels

**Parameters**

- kernel
- C
- gamma

**Advantages**

- Works well with high-dimensional data
- Effective for complex boundaries

**Disadvantages**

- Computationally expensive
- Sensitive to parameter selection

**Applications**

- Face Recognition
- Spam Detection
- Cancer Detection

---

### Naive Bayes

**Problem Solved**

Performs probabilistic classification using Bayes' Theorem.

**Key Concepts**

- Conditional Probability
- Feature Independence

**Advantages**

- Fast
- Works well with text data

**Disadvantages**

- Assumes feature independence

**Applications**

- Spam Filtering
- Sentiment Analysis
- Document Classification

---

# Unsupervised Learning

Unsupervised learning works with **unlabelled data** and discovers hidden patterns or structures.

---

### K-Means Clustering

**Problem Solved**

Groups similar data points into K clusters.

**Key Concepts**

- Centroid
- WCSS
- Inertia
- Elbow Method

**Evaluation Metrics**

- WCSS
- Silhouette Score

**Applications**

- Customer Segmentation
- Market Analysis

---

### Hierarchical Clustering

**Problem Solved**

Builds a hierarchy of clusters.

**Key Concepts**

- Dendrogram
- Agglomerative Clustering
- Divisive Clustering
- Linkage

**Applications**

- Gene Analysis
- Customer Grouping

---

### DBSCAN

**Problem Solved**

Clusters dense regions while identifying noise.

**Key Concepts**

- Core Point
- Border Point
- Noise
- eps
- min_samples

**Evaluation Metrics**

- Silhouette Score

**Applications**

- Fraud Detection
- GPS Data Analysis
- Anomaly Detection

---

### Principal Component Analysis (PCA)

**Problem Solved**

Reduces dimensionality while preserving maximum variance.

**Key Concepts**

- Principal Components
- Variance
- Explained Variance Ratio

**Parameters**

- n_components

**Applications**

- Data Visualization
- Image Compression
- Feature Reduction

---

# Model Evaluation & Tuning

This repository also includes techniques used to evaluate and improve Machine Learning models.

## Topics Covered

- Train-Test Split
- Cross Validation
- Hyperparameter Tuning
- GridSearchCV

## Evaluation Metrics

### Classification

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC-AUC

### Regression

- R² Score
- MAE
- MSE
- RMSE

### Clustering

- WCSS
- Inertia
- Elbow Method
- Silhouette Score

---

# Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

# Learning Outcome

This repository focuses on understanding:

- The intuition behind each algorithm
- Mathematical concepts at a beginner-friendly level
- Hyperparameter tuning
- Model evaluation techniques
- Practical implementation using Scikit-learn
- Real-world use cases of classical Machine Learning algorithms

---

⭐ If you found this repository useful, consider starring it.