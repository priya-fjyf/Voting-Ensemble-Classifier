# 🎓 Student Performance Prediction using Ensemble Voting Classifier

This project builds a machine learning model to classify student performance using a Voting Ensemble of Decision Tree, Random Forest, and SVC.

---

## 📊 Dataset Overview

- **Samples**: 1000 students and 8 rows 
- **Features**: 8 (gender, attendence, parental education, etc.)
- **Target**: Performance class (0 to 4)

---

## 🧠 Models Used

- Decision Tree
- Random Forest
- SVC  
Combined via **VotingClassifier (hard voting)**

Preprocessing handled via `Pipeline` & `ColumnTransformer`.

---

## ✅ Results

- **Accuracy**: 93%
- **F1 Score**: 1.00 for all classes
- Evaluated using **cross-validation and GridSearchCV** and `classification_report`

---

## 📌 Highlights

- GridSearchCV for hyperparameter tuning
- PCA-based decision boundary visualization
- Clean & reusable pipeline structure

---

## 🚀 How to Use

1. Clone this repo or open the notebook on Kaggle
2. Run all cells step-by-step
3. Review results and visualizations

---

## 👩‍💻 Author

**Priya** — *ML enthusiast & data explorer*

---

⭐ Star this repo if you found it helpful!





