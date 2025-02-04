# Movie Recommendation System

## Overview
This project implements a content-based movie recommendation system using TF-IDF vectorization and cosine similarity. The system suggests similar movies based on user input while handling typos with the `difflib` library.

## Features
- Preprocesses and cleans movie data
- Converts textual features into numerical vectors using TF-IDF
- Computes similarity scores using cosine similarity
- Handles user input errors using `difflib`
- Recommends similar movies based on the selected movie

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Difflib

## Data Preprocessing
- Selected relevant features for recommendation
- Handled missing values by filling null values
- Converted text data into numerical feature vectors using TF-IDF

## How It Works
1. The user inputs a movie name.
2. The system finds the closest matching movie title.
3. It computes similarity scores with all other movies.
4. The top similar movies are recommended to the user.

## Installation & Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/your-repo.git
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook or script to get recommendations.
