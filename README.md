# AI-Hiring-Predictor

# 🤖 AI Hiring Prediction System

## 📌 Overview

This project builds an end-to-end Machine Learning model that predicts whether a candidate will be **Hired** or **Rejected** based on resume data.

It simulates a real-world **AI-powered resume screening system** used in recruitment and HR analytics.

---

## 🎯 Objective

To automate the hiring decision process using:

* Skills
* Experience
* Education
* Certifications
* Job Role
* Salary Expectation
* Projects Count

---

## 📂 Project Structure

```
AI-Hiring-Predictor/
│
├── data/
│   └── hiring_data.csv
│
├── notebooks/
│   └── AI_Hiring.ipynb
│
├── README.md
```

---

## ⚙️ Tech Stack

* Python
* Pandas & NumPy
* Scikit-learn
* TF-IDF Vectorizer
* Matplotlib / Seaborn (for visualization)

---

## 🔄 Workflow

1. Data Loading
2. Data Cleaning & Preprocessing
3. Text Feature Engineering
4. TF-IDF Vectorization
5. Encoding Categorical Variables
6. Feature Scaling
7. Model Training (Random Forest)
8. Model Evaluation
9. Prediction System

---

## 🧠 Model Used

### Random Forest Classifier

**Why Random Forest?**

* Handles both numerical and text-based features
* Reduces overfitting
* Performs well on structured datasets

---

## 📊 Model Evaluation

The model is evaluated using:

* Accuracy Score
* Precision, Recall, F1-Score

---

## 🔮 Prediction System

A custom function is built to:

* Take candidate details as input
* Process the data
* Predict:

  * **Hire / Reject**
  * **Probability Score**

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/AI-Hiring-Predictor.git
cd AI-Hiring-Predictor
```

### 2. Install Dependencies

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### 3. Run the Notebook

Open:

```
notebooks/AI_Hiring.ipynb
```

---

## 💡 Key Learnings

* Handling structured + unstructured data
* Text processing using TF-IDF
* Feature engineering & scaling
* Model training and evaluation
* Building an end-to-end ML pipeline

---

## 🌍 Real-World Applications

* Resume screening systems
* HR automation tools
* Recruitment platforms
* AI-based hiring assistants

---

## 👩‍💻 Author

**Lakshmi Bhuvana Durvasula**

---

## ⭐ Final Note

This project demonstrates how AI can be used to automate hiring decisions and improve recruitment efficiency.
