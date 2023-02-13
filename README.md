# Movie-Recommender System
Project for class SOEN-471 (Big Data Analytics)

## Project Summary
A recommendation system is a tool that plays an important role in modern society and is used by many applications to provide suggestions to users based on some dataset. It can be used to help users choose a book to read, a restaurant to dine in, or even what videos to watch. As the streaming industry keeps growing year after year, movie recommendation systems are used to predict what movies a user would like based on their movie history. Such recommendation systems are beneficial for organizations that collect data from large amounts of customers and wish to effectively provide the best suggestions possible. This leads us to ask ourselves what movies can a system recommend to us given a list of movies. Furthermore, can a system recognize what type of movies I like based on my watching history and recommend movies that will be enjoyable? 

The dataset that will be used to implement the movie recommender is a Movie Lens dataset (link: https://www.kaggle.com/datasets/grouplens/movielens-20m-dataset). The dataset consists of movies released on or before July 2017 and contains metadata for about 45,000 movies. The metadata concerns information such as the genre of the movie, the release date, the production company, the language, the description, the ratings done by its viewer, the movie cast, and the keywords associated with the movie. Those features will be used to construct a movie model and calculate similarity to suggest movies that the users may like. 

Two different algorithms will be used to implement the recommender system. The first one is a content-based model where a user can input one or multiple movies. The system will recommend movies based on similar features, such as genres, actors, language, and release date. The second algorithm is a collaborative-based algorithm, which will use user ratings, a feature provided by the dataset, to create different profiles based on movies that they have rated. Based on the profile, the system will recommend a movie that corresponds to their taste based on their past ratings. 

Finally, the results of both algorithms will then be compared in terms of accuracy and efficiency. It is expected that more meaningful recommendations will be found using the collaborative-based algorithm because the detailed personas developed will provide more data points, enabling greater accuracy while making recommendations. Further improvements may be given to address limitations discovered during the comparison. 
