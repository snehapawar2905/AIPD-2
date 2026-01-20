
# 🤖 AI-Based Product Development – Practical 2

## 📌 Project Title

**Employee Attrition Prediction using PyTorch**

## 📖 Project Description

This project implements a **basic AI prototype** using **PyTorch** to predict **employee attrition**—whether an employee is likely to leave an organization based on HR-related data.

Employee attrition is a critical business problem as it impacts productivity, costs, and organizational stability. By leveraging machine learning and deep learning techniques, this project aims to build an intelligent model that assists HR teams in identifying employees at risk of leaving.


## 🎯 Objective

* Build an AI prototype using **PyTorch**
* Train the model on an HR dataset
* Predict employee attrition (Yes/No)
* Evaluate the model’s performance using standard classification metrics

## 🧠 Use Case

**Employee Attrition Prediction**

* Input: Employee demographic and job-related features
* Output: Whether the employee will **leave (1)** or **stay (0)**

## 🛠️ Tech Stack

* **Language:** Python
* **Framework:** PyTorch
* **Libraries:**

  * NumPy
  * Pandas
  * Scikit-learn
  * Torch (nn, optim)

## 📊 Dataset Description

* HR employee dataset containing:

  * Age
  * Job Role
  * Monthly Income
  * Years at Company
  * Work-life balance
  * Attrition (Target variable)
* Categorical features encoded using **LabelEncoder**
* Numerical features standardized using **StandardScaler**

## 🧪 Model Architecture

The AI prototype is implemented using a **Neural Network** in PyTorch:

* Input Layer (based on number of features)
* Hidden Layers with ReLU activation
* Output Layer with Sigmoid activation
* Loss Function: **Binary Cross Entropy**
* Optimizer: **Adam**

## 🚀 Model Training

* Dataset split into **training and testing sets**
* Model trained using backpropagation
* Epoch-based training loop
* Loss minimization using Adam optimizer

## 📈 Model Evaluation

The model is evaluated using:

* **Accuracy Score**
* **Classification Report**

  * Precision
  * Recall
  * F1-score

Sample Output:

```
Accuracy: ~85% – 90%
```

## 🔍 Results and Analysis

* The model successfully learns employee attrition patterns
* Good classification performance on unseen test data
* Indicates AI’s effectiveness in HR decision-making

## 🧩 Future Enhancements

* Hyperparameter tuning for improved accuracy
* Feature selection and engineering
* Deployment using Flask / FastAPI
* Dashboard integration for HR analytics
* Handling class imbalance using SMOTE

## ▶️ How to Run the Project

1. Install dependencies:

```bash
pip install torch pandas numpy scikit-learn
```

2. Run the notebook:

```bash
jupyter notebook Pawar\ Sneha_Prac2.ipynb
```

## 📌 Conclusion

This project demonstrates the successful implementation of a **PyTorch-based AI prototype** for predicting employee attrition. It highlights how AI can assist organizations in making data-driven HR decisions and reducing employee turnover.


## 👩‍💻 Author

**Pawar Sneha Sachin**
TY-AI&DS
