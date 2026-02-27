# AI-Based Customer Segmentation System

## 📌 Overview

This project implements an AI-driven customer segmentation system using the K-Means clustering algorithm. The objective is to group customers into distinct segments based on their annual income and spending behavior. Such segmentation helps businesses understand customer profiles and design targeted marketing strategies.

The system demonstrates how Artificial Intelligence and Machine Learning can be applied to real-world business analytics problems using simple and interpretable techniques.

---

## 🎯 Objective

* To segment customers into meaningful groups based on income and spending patterns
* To analyze customer behavior using data visualization
* To demonstrate the practical application of unsupervised machine learning in business decision-making

---

## 🛠️ Tech Stack

* Python
* Pandas
* Scikit-learn
* Matplotlib

---

## 📂 Project Structure

```text
customer-segmentation/
│── customers.csv          # Dataset containing customer details
│── segmentation.py        # Main Python script with ML model & graphs
│── README.md              # Project documentation
```

---

## 📊 Dataset Description

The dataset contains the following attributes:

| Column Name   | Description                                       |
| ------------- | ------------------------------------------------- |
| CustomerID    | Unique identifier of each customer                |
| Age           | Age of the customer                               |
| AnnualIncome  | Yearly income (in thousands)                      |
| SpendingScore | Score assigned based on spending behavior (1–100) |

---

## 🧠 Machine Learning Algorithm Used

### K-Means Clustering

K-Means is an unsupervised learning algorithm used to group similar data points together. In this project, customers are clustered based on their annual income and spending score to identify different types of customers automatically.

The model divides customers into three segments:

* High-value customers (high income, high spending)
* Moderate customers (average income and spending)
* Low-value customers (low income, low spending)

---

## 📈 Data Visualizations

To analyze customer behavior effectively, the following four key graphs are generated:

1. **Scatter Plot (Main AI Segmentation)**
   Displays clustered customers based on income and spending score.

2. **Income Distribution Histogram**
   Shows the distribution of customers across different income levels.

3. **Spending Score Distribution Histogram**
   Visualizes how customers vary in their spending behavior.

4. **Cluster Count Bar Chart**
   Represents the number of customers in each cluster segment.

These visualizations provide a comprehensive understanding of customer segmentation patterns and support data-driven decision-making.

---

## 🚀 How to Run the Project

### Step 1: Install Required Libraries

```bash
pip install pandas matplotlib scikit-learn
```

### Step 2: Ensure Dataset Placement

Place the file `customers.csv` in the same directory as `segmentation.py`.

### Step 3: Run the Script

```bash
python segmentation.py
```

### Step 4: Output

* Console output showing customer cluster assignments
* Four graphical visualizations:

  * Customer Segmentation Scatter Plot
  * Income Distribution
  * Spending Score Distribution
  * Cluster Count Bar Chart

---

## 💼 Real-World Applications

This AI-based customer segmentation system can be used in:

* E-commerce recommendation systems
* Retail customer behavior analysis
* Banking and financial customer profiling
* Targeted marketing and promotional strategies

---

## 📚 Learning Outcomes

* Understanding of unsupervised machine learning concepts
* Hands-on experience with K-Means clustering
* Data preprocessing and feature scaling techniques
* Visualization of machine learning results for interpretation
* Practical exposure to real-world business analytics use cases

---

## 👨‍💻 Author

Devmalya Bhattacharjee
Debolina Roy
Attreyee Biswas
Bhumi Ghosh
Agriya Vaibhavi
Ashvini Bhagat
Ankita Kumari
