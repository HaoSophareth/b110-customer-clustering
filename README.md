# B110 Session 10: Customer Segmentation with K-Means

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HaoSophareth/b110-customer-clustering/blob/main/customer_clustering.ipynb)

K-means segmentation of 32 customers on **Avg Order Value**, **Months Retained** and **Churn Risk** (standardized), reproducing the [Statistics Kingdom cluster calculator](https://www.statskingdom.com/cluster-analysis.html) in Python.

| K | SSG/SST | Silhouette |
|---|---|---|
| 2 | 0.45 | 0.36 |
| **3** | **0.65** | **0.39** |
| 4 | 0.75 | 0.40 |

**Chosen K = 3:** Loyal high spenders (8), Steady mainstream (16), At-risk regulars (8).

- `customer_clustering.ipynb`: full analysis with charts (click the Colab badge to run it, no setup needed)
- `customer_clustering_data.csv`: class dataset
