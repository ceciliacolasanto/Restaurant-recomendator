📊 #Project Summary: Restaurant Recommendation System
This project presents an AI-powered restaurant recommendation system built using Yelp reviews from Brandon, Florida. The dataset includes over 16,000 reviews from 10,426 users across 79 unique restaurants, collected between 2008 and 2022.

We implemented two main recommendation approaches:

🔍 1. Content-Based Filtering
Suggestions are generated based on restaurant attributes and the user's past preferences. The system supports:

Personal history-based recommendations: using restaurants previously liked by the user.

Similarity-based recommendations: suggesting restaurants similar to one the user already enjoys.

Keyword + rating filters: allowing users to search using custom keywords (e.g., "wine") and a minimum star rating.

This model leverages restaurant metadata (categories, ratings) and user review behavior to tailor the recommendations.

🧠 2. User Filtering (Collaborative Filtering)
We also built a recommendation engine using user-based collaborative filtering, which suggests restaurants that similar users have rated highly. This model captures hidden patterns across users to personalize suggestions even for those with limited personal history.

🗣️ Natural Language Processing
To enrich the recommendations, we applied NLP techniques:

TF-IDF and Word2Vec were used to vectorize reviews and extract the most representative review per restaurant, helping users understand the experience at a glance.

📐 Evaluation
We evaluated our collaborative filtering model using RMSE, with a result of 2.06, indicating moderate prediction accuracy. Future improvements could include adopting ALS (Alternating Least Squares) and expanding the dataset.

📊 [Download the project presentation](https://drive.google.com/file/d/1jEqj35Iz3Fuj1jU_j0qhdU161lUgu9hR/view?usp=sharing)
