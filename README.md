# Movie-Recommendations
The Movie Recommendation Project is a data-driven system designed to provide personalized movie recommendations to users based on their viewing history and preferences. The system is built using Python and employs two different algorithms, K-Nearest Neighbors (KNN) and Cosine Similarity, to provide user-based and genre-based recommendations, respectively.

The first algorithm, KNN, is used to identify users with similar movie preferences and recommend movies based on their viewing history. This user-based recommendation model analyzes a user's historical movie ratings and compares them with other users' ratings to identify similar patterns. It then recommends movies that these users have rated highly but that the original user has not yet seen.

The second algorithm, Cosine Similarity, is used to provide genre-based recommendations. This model analyzes the similarities between the genres of the movies that the user has rated and recommends movies that have a similar genre profile. This approach allows the system to recommend movies that are similar in style and tone to the user's existing movie preferences.

The project also includes a generic model with IMDB logic that uses various metadata such as movie title, genre, and ratings to make movie recommendations. This approach is particularly useful for new users who do not have a substantial viewing history or have not yet established clear movie preferences.
To enhance the user interface and provide data visualizations, the project uses Tableau for creating interactive dashboards and R for calculating correlations and statistical analysis. 

In summary, the project showcases the use of KNN and Cosine Similarity algorithms for user-based and genre-based recommendations, respectively, along with a generic model with IMDB logic. The system is designed to be flexible and customizable to cater to different user preferences and movie genres.
