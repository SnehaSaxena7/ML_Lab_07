# ML Lab 07 – Mini Projects on Unsupervised Learning Applications

## MCA III Semester – Session 2026–2027

## Objective

The objective of this lab is to implement clustering techniques on real-world datasets, perform customer and data segmentation, visualize clustering results, and analyze useful insights.

## Projects

### Project 1: Customer Segmentation using K-Means Clustering

Customer segmentation is performed using the following features:

* Age
* Annual Income
* Spending Score
* Purchasing Behavior

### Techniques Used

* Data preprocessing
* Feature scaling using StandardScaler
* K-Means Clustering
* Elbow Method
* Silhouette Score
* Data visualization

### Project 1 Output

The customers are divided into different clusters based on their characteristics. The clusters can help in identifying different customer groups for targeted marketing and customer analysis.

---

### Project 2: News Article Clustering System

News articles are grouped according to their textual similarity.

### Techniques Used

* Text preprocessing
* TF-IDF Vectorization
* K-Means Clustering
* Hierarchical Clustering
* Silhouette Score
* 2D cluster visualization

### Project 2 Output

Similar news articles are grouped into common clusters. This demonstrates how unsupervised learning can be used to organize and analyze large collections of textual information.

---

## Technologies and Libraries

* Python 3.11+
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* SciPy

## Folder Structure

```text
ML_Lab_07/
│
├── ML_Lab_07.ipynb
├── README.md
│
└── datasets/
    ├── customer_dataset.csv
    └── news_articles.csv
```

## Evaluation

The clustering models are evaluated using the Silhouette Score. The Elbow Method is also used to determine a suitable number of clusters for K-Means.

## Conclusion

The two mini projects demonstrate the practical application of unsupervised learning techniques. K-Means clustering is used for customer segmentation, while TF-IDF with K-Means and Hierarchical Clustering is used for news article clustering.

These projects provide practical understanding of clustering, feature scaling, text feature extraction, visualization, and cluster evaluation.
