# Heart Attack Risk Prediction using Machine Learning

This project aims to predict the likelihood of a heart attack based on various medical attributes using machine learning models. It was developed as part of a university module presentation to demonstrate data preprocessing, visualization, and model evaluation in a real-world healthcare context.

## 📊 Project Overview

The dataset includes attributes such as age, cholesterol levels, resting blood pressure, and more. We apply several machine learning algorithms to train a predictive model and evaluate performance metrics like accuracy, precision, and recall.

## 🔍 Features

- Data loading and cleaning
- Exploratory data analysis and correlation heatmaps
- Feature selection and normalization
- Training with:
  - Logistic Regression
  - Decision Tree
  - Random Forest
- Model comparison and confusion matrix generation
- User input prediction interface (optional extension)

## 🧪 Technologies Used

- Python 3
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## 🗂️ Project Structure

```
heart-attack-risk-prediction/
├── dataset/
│   └── heart.csv
├── main.py
├── models/
│   ├── logistic_model.py
│   ├── decision_tree_model.py
│   └── random_forest_model.py
├── utils/
│   ├── data_cleaning.py
│   └── visualization.py
├── results/
│   └── model_accuracies.txt
└── README.md
```

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/chanuka8/heart-attack-risk-prediction.git
   cd heart-attack-risk-prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the main script:
   ```bash
   python main.py
   ```

## 📈 Sample Results

- Logistic Regression Accuracy: **85%**
- Decision Tree Accuracy: **88%**
- Random Forest Accuracy: **91%**

Confusion matrices and feature importance plots are saved to the `results/` folder.

## 📜 License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## 🙋‍♀️ Author

- [Chanuka Sandun] – Cybersecurity Undergraduate Student

---
