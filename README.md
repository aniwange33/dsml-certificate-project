Movie Recommender System
This project aims to build a movie recommender system using three different techniques: popularity-based, content-based, and collaborative filtering. The system utilizes a dataset containing information about movies, including titles, genres, and user ratings.

Dataset
The dataset consists of two main tables:

Movies Data:
Contains information about movies such as title, genre, and release year.
Columns: movieId, title, genres.
Ratings Data:
Records user ratings for different movies.
Columns: userId, movieId, rating.
Techniques Implemented
1. Popularity-Based Recommender
   Recommends movies based on their popularity among users.
   Factors in average ratings and number of reviews.
   Allows users to specify a genre and minimum reviews threshold.
2. Content-Based Recommender
   Recommends movies similar to a specified movie based on their genres.
   Users provide a movie title, and the system returns movies with similar genres.
3. Collaborative Filtering Recommender
   Recommends movies based on the preferences of similar users.
   Computes similarity between users based on their ratings.
   Users input their ID, and the system recommends movies they might like.
   How to Use
   Install Dependencies:
   Ensure you have Python installed, along with required libraries such as Pandas, NumPy, Seaborn, and Matplotlib.
   Download the Dataset:
   Obtain the Movies.csv and Ratings.csv files containing movie data.
   Run the Script:
   Execute the main script and follow the prompts.
   You can choose which recommendation technique to use and provide necessary inputs.
   Usage Examples
   Popularity-Based Recommender:
   Enter a genre, minimum reviews threshold, and number of recommendations.
   Content-Based Recommender:
   Enter a movie title and the number of recommendations desired.
   Collaborative Filtering Recommender:
   Provide a user ID, number of recommendations, and the threshold for similar users (k).
   Example Output
   For each technique, the system returns a list of recommended movies based on the user's input.
   Future Improvements
   Implement more sophisticated algorithms for recommendation.
   Enhance the user interface for better user experience.
   Incorporate additional features such as user preferences and movie metadata for better recommendations.
   
Credits:
   This project was developed by Aniwange Tertese Amos as part of my Data Science and Machine Learning Internship program with
Edureka.
   