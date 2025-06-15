# 🎯 Movie Recommendation System

A content-based recommendation system built using TF-IDF and cosine similarity to recommend movies based on user input. The model uses textual metadata (such as genre, director, cast, etc.) to compute similarity between movies.

## 📌 Features

- Content-based filtering using metadata
- Cosine similarity to compute movie similarity scores
- Clean, well-commented code for easy understanding
- Interactive user input to test recommendations

## 🗂️ Dataset

The project uses the `movies.csv` dataset containing metadata such as:
- Movie Title
- Genre
- Director
- Cast
- Overview

Ensure the dataset is present in the same directory as the notebook or adjust the path accordingly.

## 🚀 How to Use

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/movie-recommendation-system.git
    cd movie-recommendation-system
    ```

2. Install required libraries:
    ```bash
    pip install pandas numpy scikit-learn
    ```

3. Run the Jupyter notebook:
    ```bash
    jupyter notebook
    ```

4. Open the notebook and run all cells to see the recommendations based on your input.

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn (TF-IDF Vectorizer & Cosine Similarity)

## 🧱 Project Structure

