AI-Powered Personalized OTT Recommendation System

An AI-based movie recommendation system developed using Machine Learning techniques in Google Colab. This project recommends personalized movies based on genres and user preferences using content-based filtering.

 Project Overview

The main objective of this project is to build a smart OTT recommendation system that suggests movies similar to the user’s interests using AI and Machine Learning algorithms.

The system analyzes movie genres and recommends the most relevant movies using TF-IDF Vectorization and Cosine Similarity.

Machine Learning Concepts Used
Recommendation System
Content-Based Filtering
TF-IDF Vectorization
Cosine Similarity
Technologies Used
Python
Google Colab
Pandas
NumPy
Scikit-learn
 Dataset Used

MovieLens Dataset

Dataset Source:

MovieLens Dataset

Files Used:

movies.csv
ratings.csv
Features
Movie recommendation system
Personalized movie suggestions
Genre-based filtering
Similar movie prediction
Easy-to-use interface
AI-powered recommendation logic
Project Structure
AI-OTT-Recommendation-System/
│
├── AI_OTT_Recommendation_System.ipynb
├── movies.csv
├── ratings.csv
├── README.md
└── requirements.txt

💡 How It Works
Load MovieLens dataset
Preprocess movie genre data
Convert text data using TF-IDF
Calculate similarity using cosine similarity
Recommend top similar movies
📸 Sample Output

Input:

Toy Story (1995)

Output:

Jumanji
A Bug's Life
Toy Story 2
Monsters Inc
Finding Nemo
📈 Future Enhancements
Add Streamlit web interface
Add movie posters using TMDB API
Add user login system
Add mood-based recommendation
Deploy using Render or Streamlit Cloud
