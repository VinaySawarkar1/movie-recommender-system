# Movie Recommendation System

##### This is a project that uses the TMDB dataset to create a movie recommendation system. The project is implemented using Python.

## Data Preprocessing
We started by preprocessing the TMDB dataset. We added tags to some of the columns, specifically the overview, genres, keywords, cast, and crew columns. This allowed us to extract more information about each movie and make better recommendations.

## Vectorization
We then used CountVectorizer to convert the preprocessed data into vectors. CountVectorizer is a method for converting text data into numerical vectors. We used this to represent each movie as a vector, which allowed us to perform similarity calculations.

## Recommendation
We used cosine similarity to calculate the similarity between each pair of movies. This allowed us to find movies that are similar to each other and make recommendations based on the user's input. The user can enter a movie title, and the system will return a list of movies that are similar to it.

## Results
We evaluated the performance of the recommendation system by comparing the recommended movies to the user's actual preferences. The system achieved very good accuracy, which indicates that it is able to make good recommendations based on the user's input.

## Conclusion
Overall, this project demonstrates the power of using data preprocessing, vectorization, and similarity calculations to create a movie recommendation system. By using these techniques, we were able to create a system that can make accurate recommendations based on the user's input.
