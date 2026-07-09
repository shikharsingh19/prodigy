# 🛍️ Customer Segmentation using K-Means Clustering

A Machine Learning project that implements the **K-Means Clustering algorithm from scratch using Python** to segment mall customers based on their purchasing behavior. The project clusters customers according to features such as **Annual Income** and **Spending Score**, providing insights for targeted marketing strategies.

---

## 📌 Project Overview

Customer segmentation helps businesses understand different groups of customers based on their purchasing patterns. This project demonstrates how the **K-Means Clustering** algorithm works without relying on Scikit-Learn's implementation.

The project includes:

- Loading the Mall Customers dataset
- Manual implementation of K-Means
- Euclidean Distance calculation
- Random centroid initialization
- Cluster assignment
- Centroid updates
- Iterative optimization until convergence
- Cluster visualization using Matplotlib

---

## 🚀 Features

- K-Means algorithm implemented from scratch
- Euclidean Distance calculation
- Random centroid initialization
- Automatic centroid updating
- Cluster visualization
- Interactive selection of number of clusters
- Uses real customer shopping data

---

## 📂 Project Structure

```
Customer-Segmentation-KMeans/
│
├── customer_segmentation.py
├── Mall_Customers.csv
├── README.md
└── requirements.txt
```

---

## 📊 Dataset

The project uses the **Mall Customers Dataset**.

### Features

| Feature | Description |
|----------|-------------|
| CustomerID | Unique customer ID |
| Gender | Male/Female |
| Age | Customer age |
| Annual Income (k$) | Annual income in thousand dollars |
| Spending Score (1-100) | Spending behavior assigned by the mall |

Example:

| CustomerID | Gender | Age | Annual Income | Spending Score |
|------------|--------|-----|---------------|----------------|
| 1 | Male | 19 | 15 | 39 |
| 2 | Male | 21 | 15 | 81 |
| 3 | Female | 20 | 16 | 6 |
| 4 | Female | 23 | 16 | 77 |

---

## 🛠 Technologies Used

- Python 3.x
- NumPy
- Pandas
- Matplotlib

---

## ⚙️ K-Means Workflow

```
Load Dataset
      │
      ▼
Select Features
      │
      ▼
Initialize Random Centroids
      │
      ▼
Calculate Euclidean Distance
      │
      ▼
Assign Data Points to Nearest Centroid
      │
      ▼
Update Centroids
      │
      ▼
Repeat Until Convergence
      │
      ▼
Visualize Final Clusters
```

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Customer-Segmentation-KMeans.git
```

Move to the project folder:

```bash
cd Customer-Segmentation-KMeans
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash
python customer_segmentation.py
```

When prompted:

```
Enter the number of clusters:
```

Example:

```
Enter the number of clusters: 3
```

---

## 📈 Algorithm

The implementation follows these steps:

1. Initialize **K** random centroids.
2. Compute the Euclidean distance between every data point and each centroid.
3. Assign each point to its nearest centroid.
4. Compute new centroids by averaging all points in each cluster.
5. Repeat until the centroids no longer change or the maximum number of iterations is reached.

---

## 📊 Output

The project displays:

- Cluster assignments
- Updated centroids after every iteration
- Scatter plot of clustered customers
- Final centroid positions

---

## 💼 Applications

- Customer Segmentation
- Targeted Marketing
- Recommendation Systems
- Business Intelligence
- Market Basket Analysis
- Sales Strategy

---

## 🔮 Future Improvements

- Elbow Method for optimal K selection
- Silhouette Score evaluation
- 3D visualization
- PCA for dimensionality reduction
- Animated clustering process
- Compare with Scikit-Learn KMeans
- Streamlit web application
- Interactive dashboard

---

## 🤝 Contributing

Contributions are welcome!

Feel free to fork this repository, create a feature branch, and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Shikhar Shauryamaan Singh**

B.Tech CSE (AI & ML)

Machine Learning | Data Science | Python | Artificial Intelligence

---

⭐ If you found this project useful, consider giving it a star on GitHub!
