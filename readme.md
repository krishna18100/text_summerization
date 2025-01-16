# Text Summarization Using Frequency-Based Approach

This project demonstrates an extractive text summarization technique using Python and the Natural Language Toolkit (NLTK). The method identifies key sentences from a given text by calculating word frequencies and sentence scores.

## Features
- Tokenizes the input text into words and sentences.
- Removes stop words to focus on meaningful content.
- Computes word frequencies and assigns scores to sentences.
- Generates a concise summary by selecting sentences with scores above a calculated threshold.

## Dependencies
The project uses the `nltk` library for natural language processing. Install it using:
```bash
pip install -r requirements.txt
