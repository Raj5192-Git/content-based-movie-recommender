# Movie Recommendation System using Cosine Similarity

## Project Overview
This project implements a content-based movie recommendation system that suggests similar movies based on user input. The system uses cosine similarity to measure the similarity between movies using their features and recommends movies that are most alike.

## Problem Statement
With the rapid growth of online streaming platforms, users often face difficulty in choosing movies of their interest. This project aims to solve this problem by building a recommendation system that suggests relevant movies based on similarity rather than popularity.

## Dataset
- Source: Movie dataset (CSV)
- Contains movie-related features such as:
  - movie title
  - genres
  - overview / description (if applicable)
  - other metadata used for similarity computation

## Methodology
1. Data loading and preprocessing  
2. Feature extraction using text-based techniques  
3. Vectorization of movie features  
4. Similarity computation using cosine similarity  
5. Recommendation generation based on highest similarity scores  

## Algorithm Used
- Cosine Similarity (Content-Based Filtering)

## How Cosine Similarity Works
Cosine similarity measures the angle between two vectors and determines how similar they are. Movies with smaller angles (higher cosine similarity scores) are considered more similar and are recommended to the user.

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Jupyter Notebook  
