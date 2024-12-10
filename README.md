This project explores a Movie Recommendation System built using Graph Neural Networks (GNNs). Two models were implemented and evaluated:

LightGCN: Focuses solely on the graph structure without utilizing node features.
Custom Model: Incorporates both graph structure and node features to enhance recommendations.
The system predicts the top-𝑘 recommendations for users and evaluates the performance of both models using the following metrics:

Precision@20: Measures the proportion of relevant movies in the top-20 recommendations.
Recall@20: Measures the proportion of relevant movies retrieved out of all relevant movies.
nDCG@20: Evaluates the ranking quality of the recommendations, assigning higher importance to correctly ranked relevant movies.
