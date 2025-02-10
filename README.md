# AI-Powered-Health-Assistant
# Description
The HealthCare Chatbot is an AI-powered virtual assistant that provides preliminary medical guidance and appointment scheduling. It leverages natural language processing to interpret user symptoms, suggest possible conditions, and offer basic health advice.

# Features
Analysis of symptoms and condition recommendations

Essential health advice and precautionary measures

Appointment scheduling with real-time availability tracking

Intuitive and user-friendly web interface

# Technologies Used
Python 3.8+

Flask (Web Framework)

NLTK (Natural Language Processing)

Pandas (Data Manipulation)

HTML/CSS/JavaScript (Forntend)

jQuery (AJAX requests)

# Installation

1.Set up a virtual environment:

python -m venv chatbot_env source chatbot_env/bin/activate # On macOS and Linux chatbot_env\Scripts\activate # On Windows

2.Install the required packages:

pip install -r requirements.txt

3.Download NLTK data:

python -m nltk.downloader punkt stopwords

# Usage
1.Start the Flask server:

python chatbot.py

2.Open a web browser and navigate to http://localhost:5000

3.Interact with the chatbot by typing your symptoms or health concerns

Project Structure
chatbot.py: Main application file

templates/index.html: HTML template for the web interface

static/styles.css: CSS styles for the web interface

data/: Directory containing CSV files with medical data

symptoms_conditions1.csv: Mapping of symptoms to conditions

conditions_treatments.csv: Treatments for various conditions

doctors.csv: List of available doctors

appointments.csv: Record of booked appointments

# Contributing
Contributions to improve HealthCare Chatbot are welcome. Please follow these steps:

1.Fork the repository

2.Create a new branch

git checkout -b feature/AmazingFeature

3.Commit your changes

git commit -m 'Add some AmazingFeature'

4.Push to the branch

git push origin feature/AmazingFeature

5.Open a Pull Request


# Acknowledgements
Flask

NLTK

Pandas

jQuery
