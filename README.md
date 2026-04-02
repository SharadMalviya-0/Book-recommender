# 📚 Book Recommender System

A web-based book recommendation system built with Flask that helps users discover new books based on their interests.

## Features

- **Home Page** — Displays the Top 50 most reviewed books with their ratings and cover images
- **Recommendation Page** — Enter any book name and get 4 similar book recommendations using collaborative filtering

## Tech Stack

- **Backend:** Python, Flask
- **Machine Learning:** Scikit-learn (cosine similarity)
- **Data Processing:** Pandas, NumPy
- **Frontend:** HTML, CSS (Jinja2 templates)

## How to Run Locally

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/book-recommender.git
   cd book-recommender
   ```

2. Create and activate a virtual environment
   ```bash
   python -m venv .venv
   .venv\Scripts\activate  # Windows
   ```

3. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```

4. Run the app
   ```bash
   python app.py
   ```

5. Open your browser and go to `http://127.0.0.1:5000`

## How It Works

The recommendation engine uses collaborative filtering with cosine similarity to find books similar to the one entered by the user. The model is pre-trained and stored as pickle files for fast inference.
