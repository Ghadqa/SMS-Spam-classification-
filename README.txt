# Spam Detection in SMS Messages

## Overview

This project implements a spam detection system for SMS messages using machine learning techniques. It processes a dataset of labeled SMS messages to classify new messages as 'ham' (non-spam) or 'spam'. The system employs natural language processing (NLP) methods and various classification algorithms to achieve accurate detection.

## Features

- **Data Preprocessing**: Cleans and prepares the SMS dataset for analysis.
- **Feature Engineering**: Extracts relevant features from text data, including word count and presence of currency symbols or numbers.
- **Model Training**: Utilizes multiple classification algorithms to train the model.
- **Evaluation**: Assesses model performance using accuracy and precision metrics.
- **Prediction**: Allows users to input new SMS messages for spam classification.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/spam-detection.git
   cd spam-detection

2. **Install Dependencies**: Ensure you have Python 3.x installed. Then, install the required packages:
pip install -r requirements.txt
Download the Dataset: Place the spam.csv dataset in the project directory. You can download it from https://archive.ics.uci.edu/dataset/228/sms+spam+collection
3. **Usage
Run the Script: Execute the main script to train the model and evaluate its performance: python SMS Spam classification.ipynb

Predict New Messages: To classify a new SMS message, use the predict_spam function:

from SMS Spam classificationimport predict_spam

message = "Congratulations! You've won a $1000 gift card. Call now to claim your prize."
result = predict_spam(message)
print(result) 
 # Output: This is a SPAM message.