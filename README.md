# Day-4-Internship-task4
🔍 Logistic Regression on Breast Cancer Data — Binary classification model with evaluation and visualization using scikit-learn.

# Logistic Regression - Breast Cancer Classification

## 📝 Description
This project demonstrates binary classification using **Logistic Regression** on the Breast Cancer dataset.  
The goal is to classify tumors as **Malignant (1)** or **Benign (0)** using various cell features.

## 🛠️ Tools & Libraries
- Python
- Pandas
- Scikit-learn
- Matplotlib / Seaborn

## 📈 Steps Performed
1. Data Cleaning and Preprocessing
2. Train/Test Split and Feature Scaling
3. Logistic Regression Model Training
4. Evaluation: Accuracy, Confusion Matrix, ROC-AUC
5. Visualizations: ROC Curve and Sigmoid Function

## 📂 Files
- `data.csv`: Input dataset
- `Logistic_Regression_Breast_Cancer.ipynb`: Jupyter Notebook with full code
- `README.md`: Project summary and instructions

## ✅ How to Run
```bash
pip install pandas scikit-learn matplotlib seaborn
jupyter notebook Logistic_Regression_Breast_Cancer.ipynb

📈 Left: ROC Curve
Shows the trade-off between True Positive Rate (sensitivity) and False Positive Rate.

The curve bows toward the top-left → better performance.

AUC = 0.997: Excellent separability between malignant and benign cases.

🧮 Right: Sigmoid Function
Logistic regression outputs probability from the sigmoid:
​
 
The red dashed line at 0.5 is the default threshold.

P > 0.5 → class 1 (Malignant)

P ≤ 0.5 → class 0 (Benign)

🛠️ Threshold Tuning (Optional)
You can adjust the threshold (e.g., to 0.3 or 0.7) to:

Reduce false negatives (important in cancer diagnosis).

Increase sensitivity or specificity depending on domain needs.

📊 Confusion Matrix
[[70  1]
 [ 2 41]]
TN (True Negatives): 70

FP (False Positives): 1

FN (False Negatives): 2

TP (True Positives): 41


