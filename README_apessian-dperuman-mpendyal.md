# Recommendation System for Movies

- In this project we are using Content-Based filtering: They recommend things depending on one. This method recommends movies based on genre, director, description, actors, etc. If a person enjoyed one item, they would also appreciate a comparable item. Dataset we are using this project is provided by MovieLens. We mainly work on recommendation part and prediction part. We are using similarity based and association filtering for recommendation and after comparison of models by pycaret library, we will be using tuned Gradient Boosting Regressor for prediction of ‘vote_average’.

- The Dataset can be found at [MovieLens](https://grouplens.org/datasets/movielens/latest/)

- To make it easy, we have downloaded it and compressed it under the name 'Data.zip'
- We mainly worked on 'movies_metadata.csv', 'movies.csv' and 'ratings.csv'

- This Project has two parts:


>> 1.   Recommendation Part
>> 2.   Prediction of 'vote_average'

1. Recommendation Part:

> - Install Libraries:
>> - numpy
>> - pandas
>> - matplotlib
>> - sklearn

> - After installing the libraries, run the notebook 'recommendation.ipynb'.

2. Prediction of 'vote_average':

> - Install Libraries:
>> - numpy
>> - pandas
>> - matplotlib
>> - seaborn
>> - pandas-profiling
>> - pycaret

> - After installing the libraries, run the notebook 'prediction_on_rating.ipynb'.

## Results:

- The Recommendation works as expected. We have created recommendation systems based on similarity, genre and association. And coming to prediction of vote_average, the trained model works with an MSE of 1.257 and R^2 of 0.12.


## References:

> [1]	https://www.kaggle.com/code/ibtesama/getting-started-with-a-movie-recommendation-system
> 
> [2]	Yang, H. (2018). Data preprocessing. Pennsylvania State University: Citeseer.
> 
> [3]	Huang, C. H., Yin, J., & Hou, F. (2011). A text similarity measurement combining word semantic information with TF-IDF method. Jisuanji Xuebao (Chinese Journal of Computers), 34(5), 856-864.
> 
> [4]	Guo, G., Zhang, J., & Yorke-Smith, N. (2013, August). A novel Bayesian similarity measure for recommender systems. In IJCAI (Vol. 13, pp. 2619-2625).
> 
> [5]	https://pycaret.gitbook.io/docs/
> 
> [6]	Gain, U., & Hotti, V. (2021, February). Low-code AutoML-augmented data > pipeline–a review and experiments. In Journal of Physics: Conference Series (Vol. 1828, No. 1, p. 012015). IOP Publishing.


