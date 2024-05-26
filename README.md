# Flipkart Review Sentiment Analysis Using Machine Learning

This script preprocesses and performs sentiment analysis on text data in a DataFrame column named "Review". It uses NLTK for text cleaning and VADER sentiment analysis to generate sentiment scores.

## Features

- **Text Cleaning**: Converts text to lowercase, removes URLs, HTML tags, punctuation, and numbers, and applies stemming.
- **Sentiment Analysis**: Calculates positive, negative, and neutral sentiment scores for each review and determines the overall sentiment of the dataset.

## Usage

1. **Install Dependencies**: Ensure you have NLTK and pandas installed.
2. **Download NLTK Resources**: Download the VADER lexicon.
3. **Clean and Analyze Text**: The script processes the text data and computes sentiment scores, displaying the overall sentiment.

## Example

- **Input DataFrame**: Contains a column "Review" with text data.
- **Output**: A DataFrame with the original review, positive, negative, and neutral sentiment scores.

## License

This project is licensed under the MIT License.
