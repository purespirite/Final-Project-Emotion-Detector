# Emotion Detection Web Application

## Introduction

This repository contains my implementation of the **Emotion Detection Web Application** developed as part of the final project.

The project demonstrates the use of **Watson NLP** for emotion detection and **Flask** for deploying the application as a web application. The application accepts a text statement from the user and analyzes it to identify different emotions such as joy, sadness, anger, fear, and disgust.

The project also includes output formatting, package validation, unit testing, error handling, and static code analysis.

## Project Objective

The main objective of this project is to develop an AI-based emotion detection application that can:

* Analyze a given text statement.
* Detect different emotions present in the text.
* Identify the dominant emotion.
* Display the results in a clear and user-friendly format.
* Handle invalid or blank input appropriately.
* Provide a web interface using Flask.
* Maintain code quality through unit testing and static code analysis.

## Technologies Used

* Python
* Watson NLP
* Flask
* HTML
* JavaScript
* CSS
* Unit Testing
* Pylint

## Project Structure

```text
Final-Project-Emotion-Detector/
│
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
│
├── static/
│   └── mywebscript.js
│
├── templates/
│   └── index.html
│
├── server.py
├── test_emotion_detection.py
└── README.md
```

## Emotion Detection

The application uses the Watson NLP emotion detection functionality to analyze text and determine the following emotions:

* Anger
* Disgust
* Fear
* Joy
* Sadness

The application also determines the **dominant emotion** based on the detected emotion scores.

## Output Format

The emotion detector returns the detected emotion scores along with the dominant emotion.

Example:

```text
{
    'anger': 0.01,
    'disgust': 0.01,
    'fear': 0.01,
    'joy': 0.95,
    'sadness': 0.02,
    'dominant_emotion': 'joy'
}
```

The exact scores depend on the input text.

## Unit Testing

Unit tests are
