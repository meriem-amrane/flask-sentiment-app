📊 Flask Sentiment Analysis App

A lightweight Flask web application that performs sentiment analysis on text inputs using Natural Language Processing (NLP) and Machine Learning.
It provides both a web interface for interactive use and a REST API for seamless integration with external applications.

🚀 Features

🌐 Web Interface with a clean form for text input.

⚡ Real-time Sentiment Prediction (Positive / Negative / Neutral).

🔌 REST API Endpoint for programmatic access.

🤖 Pre-trained ML Model built with Python & NLP libraries.

📊 Visualization Support (sentiment distribution on bulk uploads).

🛠️ Tech Stack

Backend: Flask (Python)

Frontend: HTML, CSS, Bootstrap (Jinja2 templates)

ML/NLP: scikit-learn, NLTK (or spaCy depending on model)

Data Handling: Pandas, Pickle

Environment: GitHub, Virtualenv

📂 Project Structure
flask-sentiment-app/
│
├── app.py                 # Main Flask application
├── Models/                # Trained ML models (Pickle files)
├── templates/             # HTML templates (Jinja2)
├── static/                # CSS, JS, and images
├── data/                  # Sample datasets for testing
├── requirements.txt       # Dependencies
└── README.md              # Project documentation

⚙️ Installation & Usage
1. Clone the Repository
git clone https://github.com/meriem-amrane/flask-sentiment-app.git
cd flask-sentiment-app

2. Create a Virtual Environment

python -m venv venv

source venv/bin/activate   # On Mac/Linux

venv\Scripts\activate      # On Windows

4. Install Dependencies

pip install -r requirements.txt

5. Run the Application

python app.py
