# Collborative Filtering Recommender System

This is a simple collaborative filtering recommender system. It uses the a dataset (which can be downloaded from the project root directory) to train a model and then uses the model to make recommendations.
It has both `user-based` and `item-based` collaborative filtering algorithms. All the algorithms are implemented using `Apache Spark` project.

## Dataset

The dataset is available in the root directory. There are two `.csv` files in the dataset. The `ratings.csv` file contains the ratings given by the users to the movies. The `games.csv` file contains the details of the movies.

## How to run

To run the project, you need to have `Apache Spark` cluster or `PySpark` installed on your machine. You can download `PySpark` from [here](https://spark.apache.org/downloads.html). You can also use `Google Colab` to run the project. You need to just simply run the `collaborative_filtering.ipynb` file.

## Contributors

- [Amir-Int](https://github.com/Amir-Int)
- [Mahdi Rezaie](https://github.com/mahdirezaie336)
