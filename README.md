# Movie-Recommender-System

Simple Recommendation

The Simple Recommender makes broad recommendations to each user based on movie popularity and (occasionally) genre. The basic idea behind this recommender is that movies that are more popular and critically acclaimed are more likely to be liked by the general public. This model does not provide user-specific recommendations.

Recommender System Based on Content

The recommender we created in the previous section has some serious limitations. For one thing, it makes the same recommendation to everyone, regardless of the user's preferences. If a person who likes romantic movies (but dislikes action) looked at our Top 15 Chart, he or she would probably dislike the majority of the films. If s/he went one step further and looked at our genre charts, s/he would still not be getting the best recommendations.

To improve the personalization of our recommendations, I plan to create an engine that computes similarity between movies based on certain metrics and recommends movies that are most similar to a specific movie that a user liked. This is also known as Content Based Filtering because we will be using movie metadata (or content) to build this engine.

