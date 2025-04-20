
# Credit Card Fraud Detection Model 🚨💳

![fraud detection](https://img.shields.io/badge/Project-Fraud--Detection-brightgreen) ![Python](https://img.shields.io/badge/Language-Python-blue) ![License](https://img.shields.io/badge/License-MIT-lightgrey)

This repository contains a machine learning model to detect fraudulent credit card transactions using real-world anonymized data. The model was developed as part of a data analytics internship at IBM and aims to aid financial institutions in reducing loss due to fraud.

🔗 **Live Project Update**: [Check out my LinkedIn post](https://www.linkedin.com/posts/peter-ajith-cherian-a22415278_ibm-linktree-activity-7241331399876624384-8REb?utm_source=share&utm_medium=member_desktop&utm_rcm=ACoAAEOxaHoB18TBCDIsR3fJdYfudRpYGVJRSbE)

## 🧠 Objective

Credit card fraud is a significant challenge in the banking and financial services industry. This project implements and compares multiple ML models to accurately classify fraudulent transactions based on historical data.

## 📊 Dataset

- Source: [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- 284,807 transactions, 492 frauds (highly imbalanced)
- Features are numerical, PCA-transformed (V1-V28), along with `Time` and `Amount`

## ⚙️ Tools & Technologies

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook
- Google Colab

## 📈 Model Pipeline

1. **Data Cleaning & Preprocessing**
   - Normalization
   - Handling imbalance with under/oversampling
2. **Exploratory Data Analysis (EDA)**
   - Fraud patterns and trends
3. **Model Training & Evaluation**
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - XGBoost
   - Support Vector Machine (SVM)
   - Performance Metrics: Accuracy, Precision, Recall, F1-Score, AUC-ROC
4. **Hyperparameter Tuning**

## 📌 Key Results

- Best performing model: **[Insert Model Here]** (based on AUC-ROC)
- Achieved a good balance between precision and recall despite imbalanced data
- Highlighted importance of recall in fraud detection systems

## 🧪 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/pathrossse/Credit-Card-Fraud-Detection-Model.git
   cd Credit-Card-Fraud-Detection-Model
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   Open `CreditCardFraudDetection.ipynb` in Jupyter Notebook or Colab.

## 📎 Project Structure

```
├── CreditCardFraudDetection.ipynb
├── requirements.txt
├── README.md
└── dataset/
    └── creditcard.csv
```

## 📣 Acknowledgements

- Special thanks to **IBM** for the mentorship and guidance during the internship.
- Inspired by the real-world challenge of fraud prevention in financial services.

## 🧑‍💼 Author

**Peter Ajith Cherian**  
[LinkedIn](https://www.linkedin.com/in/peter-ajith-cherian-a22415278/) | [GitHub](https://github.com/pathrossse)

---

📢 *If you find this project useful or insightful, feel free to give a ⭐ and share your thoughts!*
```

---

Let me know if you’d like to include visuals (like a confusion matrix or ROC curve), a license section, or a deployment guide.
