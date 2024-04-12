# Temporal Matrix Factorization

We compare the performance of probabilistic matrix factorization [(PMF)](https://proceedings.neurips.cc/paper_files/paper/2007/file/d7322ed717dedf1eb4e6e52a37ea7bcd-Paper.pdf) and temporal matrix factorization [(TempMF)](https://doi.org/10.1109/TCSS.2017.2772295) on a subset of the [MovieLens 25M](https://grouplens.org/datasets/movielens/25m/) dataset.

- [`pmf_example.ipynb`](pmf_example.ipynb) includes our initial implementation of PMF using Keras
- [`tempMF.ipynb`](tempMF.ipynb) includes on final implementation of PMF and TempMF using Pytorch. The trained parameters are saved to [`weights/`](weights)
- [`results.ipynb`](results.ipynb) generates the plot of our results
