IMDB Review Sentiment Classifier

Project Overview

This project uses Natural Language Processing (NLP) and Machine Learning to classify IMDB movie reviews as positive or negative.

Technologies Used

- Python
- Pandas
- NLTK
- Scikit-learn
- TF-IDF Vectorization
- Multinomial Naive Bayes

Dataset

The project uses the IMDB Dataset of 50,000 movie reviews.

Dataset source: https://zenodo.org/records/7928582

Project Workflow

1. Load and explore the dataset.
2. Clean and preprocess movie reviews.
3. Convert text into numerical features using TF-IDF.
4. Train a Multinomial Naive Bayes model.
5. Evaluate the model using accuracy, classification report, and confusion matrix.

Files

- "imdb_sentiment.ipynb" — Project code and results.
- "project_output.txt" — Saved project output.

Limitations

- The model may not understand sarcasm or complex context.
- Performance may vary on reviews from other platforms.

Result

The model predicts whether a movie review expresses positive or negative sentiment.
