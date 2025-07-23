
# 🧠 Customer Segmentation using K-Means Clustering

This project applies **K-Means Clustering** to segment customers based on their demographic and spending behavior. The segmentation helps businesses understand different customer types and tailor their services and marketing strategies accordingly.

## 🔍 Problem Statement

Businesses often deal with a wide variety of customers with different needs. To target them effectively, it is essential to divide them into meaningful groups based on shared characteristics. This project uses unsupervised machine learning to accomplish customer segmentation.

## ✅ Objective

To implement a machine learning pipeline that clusters customers into different segments using K-Means and provides insightful visualizations for business decision-making.

---

## 🛠️ Technologies Used

- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn
- Jupyter Notebook

---

## 📊 Dataset Features

- Customer ID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

---

## 📌 Key Steps

1. **Data Preprocessing**
   - Handled missing values (if any)
   - Encoded categorical variables

2. **Exploratory Data Analysis (EDA)**
   - Visualized feature distributions
   - Analyzed relationships between features

3. **K Selection (Elbow Method)**
   - Determined optimal number of clusters

4. **Modeling with K-Means Clustering**
   - Fit K-Means algorithm
   - Visualized final clusters

5. **Insights & Business Interpretation**

---

## 📈 Visualizations

### 🔍 Elbow Method to Select Optimal K
![Elbow Graph](images/elbow_graph.png)

The Elbow Method helps to choose the number of clusters by plotting the Within-Cluster-Sum-of-Squares (WCSS) against the number of clusters. The "elbow point" is the optimal number of clusters.

### 🧭 Customer Segmentation Visualization
![Customer Segmentation](images/customer_segments.png)

This 2D plot represents customer segments based on features like Annual Income and Spending Score.

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/customer-segmentation-kmeans.git

# Navigate to project directory
cd customer-segmentation-kmeans

# Install dependencies
pip install -r requirements.txt

# Open the notebook and run
jupyter notebook kmeans_segmentation.ipynb
```

---

## 📁 Folder Structure

```
├── data/                    # Dataset files
├── images/                  # Contains elbow_graph.png and customer_segments.png
├── kmeans_segmentation.ipynb
├── requirements.txt
└── README.md
```

---

## 📌 Future Improvements

- Deploy a Streamlit web app for real-time prediction
- Compare K-Means with other clustering methods (DBSCAN, Hierarchical)
- Automate K selection using Silhouette Score or Gap Statistic

---

## 📬 Contact

For queries or suggestions, feel free to connect:

- LinkedIn: [Aditya Gupta](https://linkedin.com/in/adityag_03)
- Instagram: [@adityag_03](https://instagram.com/adityag_03)
