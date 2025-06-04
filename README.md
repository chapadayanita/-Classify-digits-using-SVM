# 🌸 Iris Binary Classification using Support Vector Machine (SVM)

This project demonstrates a simple **binary classification** task using **Support Vector Machine (SVM)** on the well-known **Iris dataset**.

## 📁 Dataset

The dataset used is the built-in **Iris dataset** from scikit-learn. It originally contains 3 classes of iris flowers:
- Setosa (0)
- Versicolor (1)
- Virginica (2)

In this project, we focus on **binary classification**, using only:
- **Setosa (0)**
- **Versicolor (1)**  
*(Class 2 - Virginica - is removed)*

## 🛠️ Technologies Used

- Python
- scikit-learn

## 🔍 Workflow

1. **Load the Iris dataset** using `sklearn.datasets`
2. **Filter** the data for binary classification (classes 0 and 1 only)
3. **Split** the dataset into training and testing sets
4. **Train** an SVM model with a linear kernel
5. **Evaluate** the model using classification metrics

## ⚙️ Model Used

- **Algorithm**: Support Vector Classifier (SVC)
- **Kernel**: Linear  
*(You can also try `'rbf'` or `'poly'` for experimentation.)*

## 📊 Evaluation

The model is evaluated using the **classification report**, which includes:
- Precision
- Recall
- F1-score
- Accuracy
