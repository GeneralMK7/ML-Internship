If the Google Colab link does not work, use this: [Task 7 (Google Colab)](https://colab.research.google.com/drive/1v5yCgNSNba6H62VJBuLb6b6ZfDfPB-rT?usp=sharing)
# AI & ML Internship - Task 7: Titanic Survival Prediction

**Task 7** - Logistic Regression for binary classification

## What This Does
Predicts whether a Titanic passenger survived or not based on their information (age, gender, class, etc.)

## Dataset
- **Source:** Titanic Dataset (Kaggle)
- **Target:** Survived (0 = Died, 1 = Survived)

## Steps
1. Load Titanic dataset
2. Handle missing values (Age, Embarked)
3. Remove unnecessary columns
4. Encode categorical features
5. Scale numeric features
6. Train Logistic Regression model
7. Evaluate performance

## Results
- **Accuracy:** 82.46%
- **Precision:** 76.09%
- **Recall:** 73.68%
- **F1-Score:** 0.75
- **AUC Score:** 0.874 (Very Good)

## Files
- `task7.ipynb` - Main notebook with code
- Confusion Matrix visualization
- ROC Curve with AUC score

## Tools Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
