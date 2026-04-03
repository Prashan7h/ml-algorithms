# ML From Scratch

Implementing ML algorithms from first principles, following the ML cheatsheet.

## Algorithms

| # | Algorithm | Notebook | Status |
|---|-----------|----------|--------|
| 1 | Perceptron (through origin + with offset) | notebooks/01_perceptron.ipynb | |
| 2 | SVM (hinge loss + gradient descent) | notebooks/02_svm.ipynb | |
| 3 | Linear Regression (closed form + SGD) | notebooks/03_linear_regression.ipynb | |
| 4 | Ridge Regression | notebooks/04_ridge_regression.ipynb | |
| 5 | Kernel Perceptron (RBF kernel) | notebooks/05_kernel_perceptron.ipynb | |
| 6 | K-Nearest Neighbors | notebooks/06_knn.ipynb | |
| 7 | Collaborative Filtering | notebooks/07_collaborative_filtering.ipynb | |
| 8 | K-Means Clustering | notebooks/08_kmeans.ipynb | |
| 9 | K-Medoids Clustering | notebooks/09_kmedoids.ipynb | |
| 10 | Multinomial Naive Bayes | notebooks/10_naive_bayes.ipynb | |
| 11 | Gaussian Generative Model | notebooks/11_gaussian_generative.ipynb | |
| 12 | Gaussian Mixture Models (EM) | notebooks/12_gmm_em.ipynb | |
| 13 | Q-Learning | notebooks/13_q_learning.ipynb | |

## Setup

```bash
conda create -n ml-from-scratch python=3.11 -y
conda activate ml-from-scratch
pip install -r requirements.txt
jupyter notebook
```

## Structure

```
ml-from-scratch/
├── notebooks/     # one notebook per algorithm
├── src/           # reusable helper code
├── data/          # datasets used in examples
├── models/        # saved model checkpoints
└── results/       # plots and metrics outputs
```
