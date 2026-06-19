# SMS&CALL Scam Detection Model

SMS&CALL is an AI-based scam and fraud detection model designed to analyze SMS messages and call transcripts. It detects suspicious communication patterns such as OTP scams, fake offers, banking fraud, phishing attempts, threatening messages, and social engineering language.

This model is part of **CyberShield AI**, a Final Year Project focused on protecting users from digital threats through AI-powered detection.

## Project Overview

The main purpose of this model is to identify whether a message or call transcript is safe or scam-related. Instead of only checking simple keywords, the model understands the meaning, intent, and structure of the text.

It can be used in:

- Scam SMS detection
- Fraudulent call transcript detection
- Cybersecurity applications
- Mobile security apps
- Real-time call content analysis
- Fraud prevention systems

## Key Features

- Detects scam and legitimate text
- Supports SMS and call transcript analysis
- Identifies OTP scams, fake offers, banking scams, and phishing content
- Trained on scam and legitimate text data
- Can be integrated with backend APIs or mobile applications
- Useful for real-world cybersecurity and fraud detection systems

## Model Training

The model was trained using scam and legitimate text datasets. The training process included:

1. Collecting SMS and call-related text data
2. Cleaning and preparing the dataset
3. Removing unnecessary noise from text
4. Tokenizing text data for model input
5. Training an NLP-based classification model
6. Evaluating the model using accuracy, precision, recall, and F1-score
7. Saving the trained model for future prediction and API integration

## How It Works

The model takes an SMS message or call transcript as input and predicts whether the content is safe or scam-related.

Example input:

```text
Your bank account will be blocked. Share your OTP immediately to verify your account.
