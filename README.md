# Customer Segmentation using K-Means Clustering

This project implements a **K-Means Clustering** algorithm to group mall customers based on their **Age**, **Annual Income**, and **Spending Score**. It demonstrates how unsupervised learning can be used to identify patterns in customer behavior.

## Objective

Segment customers of a retail store into different groups to allow better marketing and customer-targeting strategies.

---

## Dataset

- **Name**: Mall Customer Dataset
- **Source**: [Kaggle - Mall Customer Segmentation Data](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **Features**:
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

---

## Tech Stack

- **Language**: Python
- **Libraries**: 
  - pandas
  - matplotlib
  - seaborn
  - scikit-learn
  - PCA (for dimensionality reduction)

---

## Steps Performed

1. **Data Preprocessing**
   - Handled missing values
   - Selected relevant features
   - Normalized features

2. **Elbow Method**
   - Identified the optimal number of clusters

3. **Modeling with K-Means**
   - Applied K-Means algorithm
   - Clustered customer data

4. **Visualization**
   - Visualized clusters using PCA-reduced 2D space
   - Color-coded cluster groups

---

## Sample Output

- Elbow Method Plot  
- Clustered Customers with PCA  
- DataFrame with Cluster Labels

---

## Usage

You can run this notebook on Google Colab:

```python
# Upload and load CSV
from google.colab import files
uploaded = files.upload()

# Run the provided notebook or script
````

Or clone the repo and run locally using:

```bash
git clone https://github.com/your-username/kmeans-mall-customers.git
cd kmeans-mall-customers
python mall_kmeans.py
```

---

## Credits

* Dataset by [Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
