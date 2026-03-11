# 🛍️ Customer Segmentation using K-Means Clustering

## 📌 Project Overview

This project applies the **K-Means Clustering Algorithm**, an unsupervised machine learning technique, to segment customers of a retail store based on their **purchase behavior**.
Using the **Mall Customer Dataset**, customers are grouped into different clusters based on their **Annual Income** and **Spending Score**.

Customer segmentation helps businesses understand their customers better and design **targeted marketing strategies**.

---

## 🎯 Objective

The goal of this project is to:

* Analyze customer purchasing patterns
* Identify groups of similar customers
* Apply **K-Means clustering** to form meaningful customer segments

---

## 🧠 Machine Learning Concept Used

* **Unsupervised Learning**
* **K-Means Clustering Algorithm**
* **Elbow Method** to determine the optimal number of clusters

---

## 📊 Dataset Information

The dataset used in this project is the **Mall Customers Dataset** which contains the following attributes:

| Feature                | Description                                             |
| ---------------------- | ------------------------------------------------------- |
| CustomerID             | Unique ID of the customer                               |
| Gender                 | Male / Female                                           |
| Age                    | Customer age                                            |
| Annual Income (k$)     | Customer yearly income                                  |
| Spending Score (1-100) | Score assigned by the mall based on purchasing behavior |

For clustering, the features used are:

* **Annual Income**
* **Spending Score**

---

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data processing
* **Matplotlib** – Data visualization
* **Scikit-learn** – Machine learning algorithms

---

## ⚙️ Project Workflow

1. Import required Python libraries
2. Load the dataset using Pandas
3. Select relevant features (Income & Spending Score)
4. Use the **Elbow Method** to find the optimal number of clusters
5. Apply the **K-Means Algorithm**
6. Visualize customer segments using scatter plots

---

## 📈 Results

The algorithm groups customers into **five distinct clusters**, representing different purchasing behaviors such as:

* High income – High spending customers
* High income – Low spending customers
* Low income – High spending customers
* Low income – Low spending customers
* Average customers

This segmentation helps businesses **improve marketing strategies and customer targeting**.

---

## 📂 Project Structure

```
SCT_ML_2
│
├── Mall_Customers.csv
├── kmeans_customer_segmentation.py
└── README.md
```

---

## 🚀 How to Run the Project

1️⃣ Clone the repository

```
git clone https://github.com/codewithRakz/SCT_ML_2.git
```

2️⃣ Install required libraries

```
pip install pandas matplotlib scikit-learn
```

3️⃣ Run the program

```
python kmeans_customer_segmentation.py
```

---

## 📷 Output

The project generates:

* **Elbow Method Graph**
* **Customer Segmentation Visualization**

These plots show how customers are grouped based on their purchasing behavior.

---

## 💡 Key Learnings

* Understanding **unsupervised machine learning**
* Implementing **K-Means clustering**
* Using **data visualization for insights**
* Applying the **Elbow Method** for cluster optimization

---

## 🔗 Internship Task

This project was completed as part of an **internship task focused on machine learning and customer analytics**.

---

