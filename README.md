# 📊 Big Data Analytics Assignment using PySpark

## 📌 Overview

This project presents the implementation of three key data analytics techniques using **PySpark MLlib**:

- ✅ Classification with Logistic Regression  
- ✅ Clustering using K-Means Algorithm  
- ✅ Recommendation System using ALS (Collaborative Filtering)  

All implementations are executed in **Google Colab**.

---

## 🚀 Technologies Used

- Python 🐍  
- PySpark ⚡  
- Google Colab ☁️  
- Pandas 🧮  
- Matplotlib 📈  

---

## 📂 Datasets Used

### 1️⃣ Classification

- **Dataset Name:** Titanic Dataset  
- **Source:** Data Science Dojo  
- **Link:** https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv  
- **Description:**  
  Predicts passenger survival based on features like age, fare, and class.

---

### 2️⃣ Clustering

- **Dataset Name:** Wholesale Customers Dataset  
- **Source:** UCI Machine Learning Repository  
- **Link:** https://raw.githubusercontent.com/jbrownlee/Datasets/master/wholesale-customers.csv  
- **Description:**  
  Groups customers based on spending patterns across product categories.

---

### 3️⃣ Recommendation System

- **Dataset Name:** Movie Ratings Dataset  
- **Source:** Public GitHub Dataset  
- **Link:** https://raw.githubusercontent.com/raunakramteke/Data-Science-Assignment/master/movie_ratings.csv  
- **Description:**  
  Contains user–movie–rating interactions for building a recommendation system.

---

## ⚙️ Implementation Details

### 🔹 1. Classification (Logistic Regression)

- Data preprocessing using VectorAssembler  
- Handling missing values  
- Train-test split (80:20)  

**Evaluation Metrics:**

- Accuracy  
- Precision  
- Recall  
- F1 Score  

**Visualization:**

- Confusion Matrix  
- Age vs Fare Scatter Plot  

---

### 🔹 2. Clustering (K-Means)

- Feature vector creation  
- K-Means clustering (k = 3)  

**Evaluation Metric:**

- Silhouette Score  

**Visualization:**

- Cluster Scatter Plot (Fresh vs Milk)  
- Elbow Method Graph  

---

### 🔹 3. Recommendation System (ALS)

- Collaborative Filtering using ALS algorithm  
- Train-test split  

**Evaluation Metric:**

- RMSE (Root Mean Square Error)  

**Output:**

- Top 5 movie recommendations per user  

**Visualization:**

- Actual vs Predicted Ratings Scatter Plot  
- Rating Distribution Histogram  

---

## 📊 Results

- ✔ Classification model achieved good accuracy  
- ✔ Clustering grouped customers effectively  
- ✔ Recommendation system predicted user preferences successfully  

---

## ▶️ How to Run

1. Open the notebook in **Google Colab**  
2. Install PySpark (if needed)  
3. Run all cells sequentially  
4. Ensure internet connection for dataset loading  

---

## 📁 Project Structure

📦 BDA-Assignment  
┣ 📜 BDA_ASSIGNMENT.ipynb  
┗ 📜 README.md  

---

## 🎯 Learning Outcomes

- Understanding of PySpark MLlib  
- Implementation of machine learning models on big data  
- Experience with distributed data processing  

---

## 📌 Conclusion

This project demonstrates the practical use of **classification, clustering, and recommendation techniques** using PySpark, building a strong foundation in Big Data Analytics.

---

## 👨‍💻 Author

- **Name:** D.Anusree
- **Roll No:** 16023771308
- **Course:** Big Data Analytics  
- **Institution:** Chaitanya Bharathi Institute of Technology  
