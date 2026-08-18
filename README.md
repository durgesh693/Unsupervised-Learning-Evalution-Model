# Unsupervised Learning Model Evaluation

This project demonstrates how to evaluate clustering models using commonly used
**internal evaluation metrics**. The notebook uses synthetic datasets and
different clustering algorithms to understand cluster quality and compare models.

## Topics Covered

- **Inertia (WCSS)** — measures the within-cluster sum of squared distances.
- **Elbow Method** — helps select a suitable number of clusters for K-Means.
- **Silhouette Score** — evaluates how well-separated and cohesive clusters are.
- **Davies-Bouldin Index (DBI)** — evaluates cluster similarity; lower values are better.
- **Calinski-Harabasz Score (CH Score)** — evaluates between-cluster separation
  relative to within-cluster dispersion; higher values are better.
- **Model Comparison** — compares clustering approaches such as K-Means and
  Gaussian Mixture Model (GMM).

## Algorithms Used

- K-Means
- DBSCAN
- Gaussian Mixture Model (GMM)

## Dataset

The notebook creates synthetic datasets using `sklearn.datasets.make_blobs`.
This makes it possible to experiment with clustering and evaluation metrics
without requiring an external dataset.

## Visualizations

The notebook includes scatter plots and metric-based visualizations to inspect
the generated clusters and evaluate different clustering configurations.

## Project Structure

```text
.
├── unsupervised_learning_evalution_model.ipynb
├── README.md
└── requirements.txt
```

## Installation

Create and activate a virtual environment if desired, then install the
required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

Open the notebook in **Jupyter Notebook**, **JupyterLab**, or **Google Colab**
and run the cells sequentially.

```bash
jupyter notebook unsupervised_learning_evalution_model.ipynb
```

## Learning Objective

The main objective of this notebook is to understand that clustering models
should not be evaluated only by looking at the clusters visually. Different
evaluation metrics provide quantitative ways to assess cluster compactness,
separation, and overall structure.

## Note

This repository is focused on learning and practicing **unsupervised clustering
model evaluation** using the techniques implemented in the notebook.
