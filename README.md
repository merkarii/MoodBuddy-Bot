# MoodBuddy Chatbot

MoodBuddy is an AI-powered chatbot built with Flask, utilizing GPT-2 for generating human-like conversational responses. It can be used as a friendly companion for casual conversations or to talk about your mood.

# Getting Started
These instructions will help you set up and run the MoodBuddy chatbot on your local machine.

# Prerequisites
Python 3.6 or higher
pip (Python package manager)
# Installation
Clone this repository:
bash
Copy code
git clone https://github.com/yourusername/MoodBuddy-Bot.git
cd MoodBuddy-Bot
Create a virtual environment:
bash
Copy code
python -m venv venv
Activate the virtual environment:
bash
Copy code
source venv/bin/activate  # On Windows: .\venv\Scripts\Activate
Install the required libraries in your virtual environment:
bash
Copy code
pip install Flask nltk spacy tensorflow transformers torch
# Running the Chatbot
Start the Flask app:
bash
Copy code
python app.py
Open your web browser and navigate to:
arduino
Copy code
http://127.0.0.1:5000/
or

arduino
Copy code
http://localhost:5000/
You can now start chatting with MoodBuddy!
# Customization
You can further customize MoodBuddy by:

Fine-tuning the GPT-2 model on domain-specific data.
Implementing additional features or chatbot capabilities.
Improving the user interface and user experience.
# License
This project is licensed under the MIT License. See the LICENSE file for details.

# Acknowledgments
OpenAI for the GPT-2 model
Hugging Face for the 'transformers' library
Flask, NLTK, spaCy, TensorFlow, and PyTorch for providing essential tools and libraries
