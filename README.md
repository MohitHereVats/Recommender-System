# Recommender-System-
Movies Recommender
A system to recommend movies according to ratings provided by users using Collaborative Filtering Learning Algorithm.
Description: 
This system will implement the collaborative filtering learning algorithm and apply it to a dataset of movie ratings.
This dataset consists of ratings on a scale of 1 to 5. The dataset has n(u) = 943 users, and n(m) = 1682 movies.
The matrix Y (a num movies X num users matrix) stores the ratings y(i,j) (from 1 to 5).
The matrix R is an binary-valued indicator matrix, where R(i,j) = 1 if user j gave a rating to movie i, and R(i; j) = 0 otherwise.
The objective of collaborative filtering is to predict movie ratings for the movies that users have not yet rated, that is, the entries with R(i,j) = 0.
This will allow us to recommend the movies with the highest predicted ratings to the user.

How it works?
Step 1: Modify 'recommender' script to input your own ratings against different movies.
Step 2: Run 'recommender' script in your Octave/Matlab command window.
Step 3: This run 100 iterations, first to train & then outputs the movies best suited for you (recommended).
