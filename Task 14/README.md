## If the google colab link does not work, use this: [task 14 (Google Colab)](https://colab.research.google.com/drive/1M77MtVYd1sar0NHE2hzMbrLCYx8ua8-H?usp=sharing)
# Titanic Survival Prediction 🚢

## 📌 Overview

This project predicts whether a passenger survived the Titanic disaster using machine learning models.

---

## 📊 Models Used

* Logistic Regression
* Decision Tree
* Random Forest
* Support Vector Machine (SVM)

---

## 📈 Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Train vs Test Accuracy (to check overfitting)

---

## 🧠 Model Selection

To select the best model:

* Models with high **overfitting (large gap)** were removed
* Remaining models were compared using **F1 Score**

👉 **Best Model: Logistic Regression**

Reason:

* Good test accuracy
* Low overfitting
* Best balanced performance

---

## 💾 Model Saving

The best model was saved using:

```python
import joblib
joblib.dump(model, "best_model.pkl")
```

---

## 📌 Conclusion

SVC performed best for this dataset as it provides a good balance between performance and generalization.

---
