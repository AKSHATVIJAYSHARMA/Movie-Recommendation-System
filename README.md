🎬 Movie Recommendation System

This project is a Content-Based Movie Recommendation System that suggests movies similar to a given title based on various descriptive features. It is implemented in Python using Pandas, NumPy, and Scikit-learn.

📌 What it does
The system analyzes movie data (genres, keywords, tagline, cast, and director) and recommends movies with the most similar content. It uses TF-IDF Vectorization to convert text-based features into numerical vectors and computes cosine similarity to measure how close two movies are.

✅ Key Features
Content-Based Filtering → Finds movies similar to a given movie
Feature Combination → Uses multiple attributes for better recommendations
TF-IDF + Cosine Similarity → Efficient similarity computation
Handles Missing Values → Ensures smooth processing of incomplete data
🛠️ Technologies Used
Python 3
Pandas, NumPy for data preprocessing
Scikit-learn (TfidfVectorizer, cosine_similarity) for text vectorization and similarity calculation
Jupyter Notebook for development and experimentation
📂 Project Structure
Movie Recommendation System.ipynb → Complete implementation notebook
movies.csv → Dataset containing movie information
🚀 How it Works
Loads the dataset (movies.csv)
Selects key content features (genres, keywords, tagline, cast, director)
Combines all selected features into a single text
Applies TF-IDF Vectorizer to create a feature matrix
Computes cosine similarity between all movies
Takes a movie title as input and returns the top similar movies
📖 Example
If you input “Avatar”, the system will return movies with similar genres, cast, and storyline elements.
