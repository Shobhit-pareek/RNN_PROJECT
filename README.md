# RNN_PROJECT

This project is a Streamlit-based web application for analyzing the sentiment of movie reviews. It uses a pre-trained RNN model to classify reviews as either Positive or Negative, providing an intuitive interface for real-time sentiment prediction

**Features**

**- User-Friendly Interface:** Enter movie reviews in plain text for instant sentiment classification.
  
**- Pre-trained Model:** Leverages a simple RNN model trained on the IMDB dataset with relu activation for sentiment analysis.
  
**- Score Display:** Outputs the sentiment and confidence score of the prediction.
  
**- Text Preprocessing:** Handles text tokenization and padding for compatibility with the model.

**How It Works:** 

**Text Preprocessing:**
Converts input text to lowercase and tokenizes it into words.
Encodes the words using the IMDB word index and pads the sequence to a fixed length of 500.

**Prediction:**
The pre-trained RNN model processes the input and outputs a probability score.
If the score is greater than 0.5, the review is classified as Positive; otherwise, it's Negative.

**Output:**
Displays the sentiment classification and confidence score.
