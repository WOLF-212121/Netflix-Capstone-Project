# **🎬 Netflix Recommendation System | SVD-Based Movie Recommender**
![Netflix_Logo](images/netflix_logo.png)
![Netflix_Recommendation](images/netflix_recommendation_engine.png)

---
# Overview 
This project is a personalized movie recommendation system that suggests the Top 10 movies per user based on their historical ratings.
Built using the Surprise library and Singular Value Decomposition (SVD) algorithm, 
the system is designed to help users discover movies they'll likely enjoy—just like Netflix!

---
# Problem Statements 
1. Find out the list of most popular and liked ratings.
   most popular and liked ratings = rated maximum times

2. Create a model that finds the best-suited movie for one user in every rating.

3. Find what movies received the best and worst ratings based on user rating.

    list the movies having :

	  best ratings --> 5 ratings

	  worst ratings --> 1 rating
   
---
# 📌 Features

✅ Predicts top 10 movie recommendations for each user ID

✅ Utilizes SVD from Surprise for collaborative filtering

✅ Performs data preprocessing using Pandas

✅ Joins and cleans multiple datasets to map movie names with IDs

✅ Extracts insights from the rating distribution and movie popularity

---
# 🧠 Project Highlights

Model: Surprise SVD (Matrix Factorization)

Top-rated Movie: Pirates of the Caribbean: The Curse of the Black Pearl

Most Common Rating: 4 stars

Data Insight: Ratings of 4 were the most common, followed by 3 and 5.

---
# 🗂️ Dataset

User-movie ratings file (user ID, movie ID, rating)

Movie metadata file (movie ID, title)

Ratings dataset used for training and predictions

Note: The dataset is a simulated version of Netflix-style user preferences.

---
# 🧪 Libraries Used

pandas – Data manipulation and preprocessing

numpy – Numerical operations

surprise – Model building with SVD

matplotlib – Visualization (optional, for insights)

---
# 💡 Future Improvements

Add content-based filtering to enhance cold-start recommendations

Include genres, tags, or user demographic data

Deploy via Streamlit for interactive use


dataset link -- https://drive.google.com/file/d/14UWjvNZ5pLNtuM4IWMkRHWB1zCDmSOVW/view?usp=sharing
