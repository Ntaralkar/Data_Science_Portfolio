## A Simple Recommender System in Python

In this project, I have tried to built a simple recommendation system in python.

### What is a recommender system?

A recommender system is a simple algorithm used to provide the most relevant information to a user by discovering patterns in a dataset. The algorithm rates the items and shows the user the items that they would rate highly. An example of recommendation in action is when you visit **Amazon** and you notice that some **movies** are being recommended to you or when **Netflix** recommends certain movies to you. They are also used by Music streaming applications such as Spotify and Deezer to recommend music that you might like.

### Different types of recommendation engines

There two main types of recommendation systems are **content based** and **collaborative** filtering recommender system. 

#### Collaborative Filtering:

* The behavior of a group of users is used to make recommendations to other users. Recommendation is based on the preference of other users.
* A simple example would be recommending a movie to a user based on the fact that their friend liked the movie.

There are two types of Collabrative models:

1. Memory-based methods:

* Memory-based techniques are simple to implement and the resulting recommendations are often easy to explain. They are divided into two further categories.

- User-based collaborative filtering: In this model products are recommended to a user based on the fact that the products have been liked by users similar to the user.

- Item-based collaborative filtering: These systems identify similar items based on users’ previous ratings.

2. Model-based methods: 

* Model-based methods are based on matrix factorization and are better at dealing with sparsity. They are developed using data mining, machine learning algorithms to predict users’ rating of unrated items. 
* In this approach techniques such as dimensionality reduction are used to improve the accuracy.

- Content based Filtering

It uses meta data such as genre, producer, actor, musician to recommend items say movies or music. Such a recommendation would be for instance recommending Infinity War that featured Vin Disiel because someone watched and liked The Fate of the Furious.

- Datasets used for building recommender systems

In this project, the data is used from [MovieLens Dataset](https://grouplens.org/datasets/movielens/). This dataset was put together by the Grouplens research group at the University of Minnesota. It contains 1, 10, and 20 million ratings. Movielens also has a website where you can sign up, contribute reviews and get movie recommendations. You can find more datasets for various data science task from Dataquest’s data resource.

Lets start building a simple recommendation system in python.
