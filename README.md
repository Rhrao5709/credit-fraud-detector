
# Credit Card Fraud Detection

A machine learning project that detects fraudulent credit card transactions using a real-world highly imbalanced dataset. The model is trained using Scikit-learn and achieves high accuracy while maintaining strong fraud detection capability.

---

## 📌 Project Overview

Credit card fraud is a major financial risk. This project builds a classification model that can automatically identify fraudulent transactions based on transaction features.

The workflow includes:

- Data loading and preprocessing  
- Handling class imbalance  
- Model training  
- Performance evaluation  
- Model saving for deployment  

---

## 📂 Project Structure

```

credit-fraud-detector/
│
├── data/
│   └── creditcard.csv
├── model/
│   └── model.pkl
├── train.py
├── requirements.txt
└── README.md

````

---

## ⚙️ Installation

Clone the repository and install dependencies:

```bash
pip install -r requirements.txt
````

---

## 🚀 How to Run

Run the training script:

```bash
python train.py
```

The trained model will be saved to:

```
model/model.pkl
```

---

## 📊 Model Performance

* Handles highly imbalanced data
* High overall accuracy (~0.99 expected)
* Suitable baseline fraud detection system

---

## 🛠️ Tech Stack

* Python
* Pandas
* Scikit-learn
* Joblib

---

## 📌 Future Improvements

* Use SMOTE for better fraud recall
* Try XGBoost / LightGBM
* Build Streamlit deployment
* Add ROC-AUC monitoring

---

## 👩‍💻 Author

Hansika Rao

```
