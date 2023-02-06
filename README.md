# MovieRecSystem
Movie Recommendation system using the movieLens dataset

dataset available at: https://grouplens.org/datasets/movielens/

The code performs a data analysis of movie ratings using various libraries in Python, such as pandas, numpy, and matplotlib, among others. It uses the scikit-learn library for model selection, performance evaluation, and classification using machine learning algorithms like Logistic Regression, Decision Tree Classifier, K-Nearest Neighbors, Linear Discriminant Analysis, Naive Bayes, and Support Vector Machine. The code loads two datasets, "movies.csv" and "ratings.csv" and gives a summary of the data. It then creates a histogram to get an idea of the distribution of ratings and performs data cleaning and formatting. The code also checks for missing values and groups the data by movie title to find the mean rating. It creates a recommendation dataframe by pivoting the data based on userId and title. Finally, the code finds films similar to the movie "Fight Club" by calculating the correlation between the movies and the movie "Fight Club." To ensure accurate predictions, the code only keeps movies that have been rated at least 50 times.

I used collaborative filtering
