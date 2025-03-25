# Sentimental-analysis
Sentiment analysis of iPhone 14 customer reviews using CNN and LSTM models in TensorFlow.
# Sentiment Analysis on iPhone 14 Customer Reviews

This project performs sentiment analysis on customer reviews of the iPhone 14 using deep learning models (CNN and LSTM). The application is built using **Streamlit** for deployment.

## Features
- Predict sentiment (Positive, Neutral, Negative) from text reviews.
- Choose between CNN and LSTM models.
- Uses a pre-trained tokenizer for text processing.
- Implements a keyword-based classification approach.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/sentiment-analysis.git
   cd sentiment-analysis
   ```

2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

3. Ensure you have the trained models (`cnn_sentiment_model.h5` and `lstm_sentiment_model.h5`) and the tokenizer file (`tokenizer.json`) in the project directory.

## Running the Streamlit App

Run the following command:
```sh
streamlit run app.py
```

## Project Structure
```
📂 sentiment-analysis
 ┣ 📜 app.py               # Streamlit app script
 ┣ 📜 cnn_sentiment_model.h5  # Trained CNN model
 ┣ 📜 lstm_sentiment_model.h5 # Trained LSTM model
 ┣ 📜 tokenizer.json       # Tokenizer file for text processing
 ┣ 📜 requirements.txt     # List of dependencies
 ┣ 📜 README.md            # Project documentation
```

## Usage
1. Enter a text review in the input box.
2. Select a model (CNN or LSTM).
3. Click the **Predict Sentiment** button.
4. View the predicted sentiment result.

## Requirements
- Python 3.7+
- TensorFlow
- NumPy
- Streamlit

## Contributing
Feel free to raise issues or submit pull requests for improvements.


