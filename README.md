
# 📊 Loan Approval Classification on Imbalanced Data

This project demonstrates how to perform classification on an imbalanced dataset using Python. The focus is on effective preprocessing, class balancing using oversampling (SMOTE), model training, and evaluation with metrics beyond simple accuracy.

---

## 📁 Files

- `loan_data.ipynb`: Main Jupyter notebook containing all code for data loading, preprocessing, model training, and evaluation.
- `loan_data.csv`: Input dataset used for the classification task.

---

## 🚀 Features

- Data cleaning and preprocessing
- Handling class imbalance with SMOTE
- One-hot encoding of categorical variables
- Label encoding for binary classification
- Model training using Random Forest
- Performance evaluation using:
  - Precision, Recall, F1-Score
  - ROC AUC Score
  - Confusion Matrix

---

## 🛠️ Requirements

Install required libraries with:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn imbalanced-learn
```

---

## 🧪 How to Run

1. Clone the repo or download the files.
2. Ensure `loan_data.csv` is in the same directory.
3. Launch the notebook:

```bash
jupyter notebook loan_data.ipynb
```

4. Run all cells.

---

## 🧠 Models and Techniques

- **Random Forest Classifier** with `class_weight="balanced"`
- **SMOTE** for oversampling the minority class
- **Evaluation Metrics**: ROC AUC, precision, recall, F1-score

---

## 📈 Sample Output

Confusion matrix, classification report, and ROC curve will be generated for model evaluation.

---

## ⚖️ License

MIT License
