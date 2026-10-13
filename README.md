# Emotion Detector Application

An AI-powered web application built with Python, Flask, and the Watson NLP library that analyzes user-provided text to detect and quantify underlying human emotions.

---

## 📌 Project Overview

The **Emotion Detector** is a full-stack AI microservice designed to evaluate text input and output the intensity scores for key emotions:
- **Anger**
- **Disgust**
- **Fear**
- **Joy**
- **Sadness**

The application identifies the dominant emotion present in the input text and serves the formatted analysis through a clean Flask-based web interface.

---

## 🚀 Features

* **AI Emotion Analysis:** Integrates with Watson NLP Embed Emotion Predict service.
* **Formatted API Output:** Processes raw JSON responses into structured Python dictionaries with explicit dominant emotion detection.
* **Robust Error Handling:** Handles HTTP 400 bad requests and blank inputs gracefully.
* **Flask Web Server:** Microservice web server for seamless interaction.
* **Static Code Analysis Compliance:** Fully compliant with `pylint` static analysis rules (10/10 score).
* **Automated Unit Testing:** Includes test coverage via Python's built-in `unittest` framework.

---

## 🛠️ Project Structure

```text
.
├── EmotionDetection/
│   ├── __init__.py           # Package initialization module
│   └── emotion_detection.py  # Core logic for Watson NLP API calls & formatting
├── templates/
│   └── index.html            # Frontend user interface
├── static/
│   └── mywebscript.js        # Frontend AJAX handling script
├── test_emotion_detection.py # Unit tests
├── server.py                 # Flask web server and routing
└── README.md                 # Project documentation
