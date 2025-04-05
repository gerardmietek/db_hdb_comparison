
# DBSCAN vs HDBSCAN – Clustering Comparison

This project demonstrates and compares the performance of **DBSCAN** and **HDBSCAN** on synthetic datasets using Python and visualizations.

## 🧠 Overview

Both DBSCAN and HDBSCAN are density-based clustering algorithms. This notebook showcases how each algorithm performs, particularly in terms of cluster detection, noise recognition, and adaptability to varying densities.

## 📊 Comparison Table

| Feature | DBSCAN | HDBSCAN |
|--------|--------|---------|
| **Parameters** | `eps`, `min_samples` | `min_cluster_size`, `min_samples` (optional) |
| **Cluster Detection** | Flat | Hierarchical |
| **Density Adaptation** | Fixed | Variable |
| **Noise Handling** | Moderate | Excellent |
| **Performance on Varying Densities** | Weak | Strong |
| **Speed** | Faster on small datasets | Slightly slower |
| **Result Stability** | Sensitive to parameters | More robust due to hierarchy |

## 📸 Visual Examples

Below are screenshots from the notebook showcasing the clustering results of each algorithm:

### DBSCAN Clustering
![DBSCAN Example](images/dbscan_result.png)

### HDBSCAN Clustering
![HDBSCAN Example](images/hdbscan_result.png)

> 📎 *Ensure you have the images saved in a folder named `images/` within your project directory for them to display properly.*

## 📦 Dependencies

- Python 3.x
- `scikit-learn`
- `hdbscan`
- `matplotlib`
- `numpy`

Install the required packages using:

```bash
pip install -r requirements.txt
```

## 🚀 Running the Project

To view the analysis, open the `.html` file in your browser or run the original Jupyter Notebook:

```bash
jupyter notebook dbscan_hdbscan_comparison.ipynb
```

## 📁 Files Included

- `dbscan_hdbscan_comparison.html` – HTML export of the notebook
- `README.md` – This file
- (Optional) `images/` – Folder with screenshot plots

## 📌 Notes

- HDBSCAN is generally more robust for real-world noisy datasets.
- DBSCAN can be faster and simpler but may require more careful parameter tuning.

---

© 2025 – Your Name
