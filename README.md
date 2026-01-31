# Movie-Recommendation-System-Project

A simple Movie Recommendation System that helps users discover movies they’ll enjoy. It analyzes movie data and user preferences to suggest relevant and personalized movie recommendations, making it easier to find what to watch next.
A simple Python-based Movie Recommendation System that suggests movies similar to your favorite film. Uses natural language processing with TF-IDF and cosine similarity for content-based recommendations.

---

## Features

- Find similar movies by entering your favorite movie.  
- Handles typos and partial matches with fuzzy matching.  
- Recommends movies based on genres, cast, keywords, tagline, and director.  
- Simple command-line interface for easy use.  

---

## How It Works

1. Loads a movie dataset and fills missing values.  
2. Combines key features into a single text feature.  
3. Converts text features into numerical vectors using TF-IDF.  
4. Calculates cosine similarity between movies.  
5. Suggests movies closest to the user’s input.  

---
