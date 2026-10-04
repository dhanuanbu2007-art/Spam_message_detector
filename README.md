# Spam Message Detector

## Project Overview

The Spam Message Detector is a Natural Language Processing (NLP) and Machine Learning application designed to identify unwanted or promotional messages. It uses the Multinomial Naive Bayes algorithm to classify messages into two categories: Spam and Not Spam.

## Features

* Detects spam and normal text messages.
* Uses machine learning for text classification.
* Displays prediction results with confidence scores.
* Provides a simple and interactive user interface.
* Supports real-time message analysis.

## Technologies Used

* Python
* Google Colab
* Gradio
* Scikit-learn
* CountVectorizer
* Multinomial Naive Bayes

## How It Works

1. The user enters a text message.
2. The application processes the text using CountVectorizer.
3. The trained Naive Bayes model analyzes the message.
4. The application displays whether the message is Spam or Not Spam.
## Input

A text message entered by the user.

**Example:**
"Congratulations! You won a free prize. Click here to claim now."

## Output

* **Classification:** Spam
* **Confidence Score:** Model-generated score.
* **Result:** The message is identified as potentially unwanted or promotional content.

The application displays whether the message is classified as Spam or Not Spam.


## Applications

* SMS spam detection
* Unwanted message filtering
* Basic text classification
* Message security awareness

## Note

This project uses a small sample dataset for demonstration purposes. Predictions may not always be accurate for real-world messages.

## Application Type

Text and Speech Analysis (TSA)
