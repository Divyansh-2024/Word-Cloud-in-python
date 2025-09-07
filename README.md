IMDB Movie Reviews Word Cloud

This project creates a visual representation of text data using the IMDB Movie Reviews dataset. By generating a Word Cloud, the project highlights the most frequent words in the reviews, where word size reflects the frequency of occurrence.

The visualization provides quick insights into the language patterns of movie audiences — for example, commonly used adjectives, expressions of sentiment, and recurring terms in positive or negative reviews.

📂 Dataset

The dataset used is IMDB-Dataset.csv, which contains:

review → The actual text of the movie review.

sentiment → The sentiment label (positive or negative).

🛠️ Process Overview

Data Preparation

Extracted all reviews from the dataset.

Removed punctuation, numbers, and special characters.

Converted all text to lowercase.

Removed stopwords (e.g., the, is, and).

Word Cloud Generation

Created using the WordCloud library.

Word size is determined automatically based on frequency.

Visualization

Displayed using Matplotlib for easy analysis.
