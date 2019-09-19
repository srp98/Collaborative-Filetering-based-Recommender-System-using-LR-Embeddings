# Collaborative-Filtering-based-Recommender-System-using-LR-Embeddings

A Recommender System based on collaborative filtering implemented in Keras using Low Rank Embeddings

The general idea is to compare how well an NN would perform in this setting, we are using embeddings to make reasonable distinctions between words. This is the same as Low Rank Matrix Factorization where we construct a matrix of users and ratings given the movies formed by dot product.

## Requirements

The following are the main libraries and the dependencies bound to them are what the notebook requires to run.

- Python 3.6+

- TensorFlow 1.14

- Numpy

- Pandas
  
- Matplotlib

## Dataset

The dataset used is [MovieLens 100k Dataset](https://grouplens.org/datasets/movielens/100k/) a stable benchmark dataset containing 100,000 ratings from 1000 users on 1700 movies.

## References

This video from Stanford Machine Learning course explains the idea behind the methodology employed in this notebook. [Video](https://www.coursera.org/lecture/machine-learning/vectorization-low-rank-matrix-factorization-CEXN0)
