# RECOMMENDATION-SYSTEM
*COMPANY*: CODTECH IT SOLUTIONS
*NAME*: GUNNA PAVAN 
*INTERN ID*: CT04DN1757 
*DOMAIN* : MACHINE LEARNING 
*DURATION* : 4 WEEKS 
*MENTOR* : NEELA SANTOSH
Objective
To build a Recommendation System that predicts a user’s preferences (ratings) for items (like movies), using historical user-item interaction data.
*📘 What is Collaborative Filtering?*
Collaborative Filtering is a technique that recommends items to a user based on the preferences of similar users or similar items.
*Two main types:*
User-Based Filtering: Users similar to you liked X, so you might too.
Item-Based Filtering: You liked X, and it's similar to Y, so you might like Y.
Matrix Factorization (used here): Learns latent features that represent users and items and predicts ratings using dot-product of feature vectors.
*🛠️ Implementation Details*
*🧰 Libraries Used*
surprise: For building and evaluating recommender systems.
pandas, sklearn: For evaluation and data handling.
*📦 Dataset*
MovieLens 100k dataset (built into surprise library).
100,000 movie ratings by 943 users on 1,682 movies.
*📈 Output*
RMSE score: Indicates how close predicted ratings are to the actual ones
Sample predictions for user-item pairs.
Ready for extension into an app or dashboard (e.g., Streamlit or Flask).
*✅ Deliverables*
Python script: collaborative_filtering_recommender.py
Output: RMSE score + sample recommendation predictions
Can be adapted to different datasets (e.g., product ratings, songs, books)
