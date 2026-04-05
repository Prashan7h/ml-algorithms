# ML From Scratch

Implementing ML algorithms from first principles — each notebook includes math, diagrams, a real-world dataset, and fully executed outputs.

## Algorithms

| # | Algorithm | Notebook | Dataset | Status |
|---|-----------|----------|---------|--------|
| 1 | Linear Classifier + Perceptron | [01_linear_classifier_perceptron](notebooks/01_linear_classifier_perceptron.ipynb) | Breast Cancer | ✅ |
| 2 | Linear Regression + Ridge | [02_linear_regression](notebooks/02_linear_regression.ipynb) | Diabetes | ✅ |
| 3 | Kernel Perceptron (RBF) | [03_kernel_perceptron](notebooks/03_kernel_perceptron.ipynb) | Banknote Authentication | ✅ |
| 4 | K-Nearest Neighbors | [04_knn](notebooks/04_knn.ipynb) | Wine | ✅ |
| 5 | Collaborative Filtering | [05_collaborative_filtering](notebooks/05_collaborative_filtering.ipynb) | Synthetic ratings | ✅ |
| 6 | K-Means Clustering | [06_kmeans](notebooks/06_kmeans.ipynb) | Seeds | ✅ |
| 7 | K-Medoids Clustering | [07_kmedoids](notebooks/07_kmedoids.ipynb) | Seeds | ✅ |
| 8 | Multinomial Naive Bayes | [08_naive_bayes](notebooks/08_naive_bayes.ipynb) | 20 Newsgroups | ✅ |
| 9 | Gaussian Generative Model | [09_gaussian_generative](notebooks/09_gaussian_generative.ipynb) | Iris | ✅ |
| 10 | Gaussian Mixture Models + EM | [10_gmm_em](notebooks/10_gmm_em.ipynb) | Synthetic mixture | ✅ |
| 11 | Q-Learning | [11_q_learning](notebooks/11_q_learning.ipynb) | Grid World | ✅ |

## Setup

```bash
conda create -n ml-algorithms python=3.11 -y
conda activate ml-algorithms
pip install numpy scikit-learn matplotlib jupyter nbformat
jupyter notebook
```

## Structure

Each notebook follows the same structure:
1. **Introduction** — plain-English intuition
2. **The Math** — key equations with matplotlib diagrams
3. **Problem Class** — when to use it and when not to
4. **Implementation** — from scratch in NumPy on a real dataset
5. **Results** — interpretation of actual outputs
6. **Limitations** — where the algorithm breaks down
