# **🎬 Netflix Recommendation System | SVD-Based Movie Recommender**

This project is a personalized movie recommendation system that suggests the Top 10 movies per user based on their historical ratings.
Built using the Surprise library and Singular Value Decomposition (SVD) algorithm, 
the system is designed to help users discover movies they'll likely enjoy—just like Netflix!

# 📌 Features

✅ Predicts top 10 movie recommendations for each user ID

✅ Utilizes SVD from Surprise for collaborative filtering

✅ Performs data preprocessing using Pandas

✅ Joins and cleans multiple datasets to map movie names with IDs

✅ Extracts insights from the rating distribution and movie popularity

# 🧠 Project Highlights

Model: Surprise SVD (Matrix Factorization)

Top-rated Movie: Pirates of the Caribbean: The Curse of the Black Pearl

Most Common Rating: 4 stars

Data Insight: Ratings of 4 were the most common, followed by 3 and 5.

# 🗂️ Dataset

User-movie ratings file (user ID, movie ID, rating)

Movie metadata file (movie ID, title)

Ratings dataset used for training and predictions

Note: The dataset is a simulated version of Netflix-style user preferences.

# 🧪 Libraries Used

pandas – Data manipulation and preprocessing

numpy – Numerical operations

surprise – Model building with SVD

matplotlib – Visualization (optional, for insights)

# 💡 Future Improvements

Add content-based filtering to enhance cold-start recommendations

Include genres, tags, or user demographic data

Deploy via Streamlit for interactive use


dataset link -- https://drive.google.com/file/d/14UWjvNZ5pLNtuM4IWMkRHWB1zCDmSOVW/view?usp=sharing
