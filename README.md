# Spam-Filtering-Email-System-using-Machine-Learning

# Milestone-1-Assignment-Logistic-Regression-Linear-Regression-and-Perceptron-Classifier


# 📧 Email Spam Detection using Machine Learning

This project focuses on building and evaluating machine learning models to classify emails as **spam** or **ham (non-spam)** using a custom dataset. The models implemented include **Logistic Regression**, **Linear Regression**, and a **Perceptron Classifier**. The project includes Exploratory Data Analysis (EDA) to understand the dataset and improve model performance.

---

## 📁 Dataset

The dataset is a small, curated collection of **65 email messages**, labeled as either `spam` or `ham`. It contains two columns:

- `text`: The email message content.
- `label`: Either `spam` or `ham`.

**Class Distribution:**
- `ham`: 40 messages
- `spam`: 25 messages

---

## 🛠️ Tools & Libraries

- Python 3.x
- Jupyter Notebook
- pandas, numpy
- matplotlib, seaborn
- sklearn (Scikit-learn)

---

## 🔍 Exploratory Data Analysis (EDA)

The EDA includes:
- Distribution of spam vs. ham messages
- Analysis of email lengths by label
- Basic text preprocessing 
  
Key Insight:
> Spam emails tend to be longer and more varied than ham emails, making **message length** a useful feature for classification.

---

## 🧠 Machine Learning Models

1. **Logistic Regression Classifier**
2. **Linear Regression Classifier (thresholded for binary classification)**
3. **Perceptron Classifier**

Each model is trained and evaluated using:
- Accuracy score
- Confusion matrix

---

## ✅ Results

| Model                 | Accuracy          |
|----------------------|--------------------|
| Logistic Regression  | 54%                |
| Linear Regression    | 69%                | 
| Perceptron           | TBD (Optional)     |

---

## 📊 Presentation

A **5-slide PowerPoint presentation** summarizes:
- Project goals and thought process
- Dataset overview
- Challenges encountered
- Solutions and preprocessing
- Model results and conclusion

---

## 🚀 How to Run
1. Clone this repository or download the `.ipynb` file.
2. Install required packages:  
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
