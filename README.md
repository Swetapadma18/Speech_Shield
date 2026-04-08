A Machine Learning and NLP-based web application that detects hate speech, offensive language, and neutral text from user input.
The system analyzes linguistic patterns and classifies text using trained ML models to promote safer online communication.

📌 Project Overview
Online platforms often face problems with toxic or abusive language.
Speech Shield helps address this by automatically analyzing text and identifying harmful content.

The system uses Natural Language Processing (NLP) and Machine Learning algorithms to classify text into:

Hate Speech

Offensive Language

Neutral / Non-Hate Speech

The application includes a simple web interface where users can input text and instantly see the classification result.

🎯 Objectives
Detect hate speech in textual content.

Classify text into hate, offensive, or neutral categories.

Apply NLP preprocessing techniques.

Train a machine learning classification model.

Provide an interactive web interface for analysis.

⚙️ Technologies Used
💻 Programming Language
Python

🤖 Machine Learning
Scikit-learn

Pandas

NumPy

🧠 Natural Language Processing
NLTK

TF-IDF Vectorization

🌐 Web Development
HTML

CSS

JavaScript

Flask

🧠 System Workflow
User Input Text
       ↓
Text Preprocessing
       ↓
Tokenization & Cleaning
       ↓
TF-IDF Feature Extraction
       ↓
Machine Learning Model
       ↓
Prediction (Hate / Offensive / Neutral)
       ↓
Result Display with Confidence Score
📊 Dataset
The model is trained using a labeled hate speech dataset containing tweets and comments.

Dataset Columns
Column	Description
tweet	Text content
label	Category of speech
Labels
Label	Meaning
0	Hate Speech
1	Offensive Language
2	Neutral Speech
🚀 Features
✅ Hate speech detection using NLP
✅ Machine learning classification model
✅ Text preprocessing pipeline
✅ Confidence score for predictions
✅ Simple and interactive web interface
✅ Extendable for voice-to-text detection
