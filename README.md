# Companion Python ADK
# Companion Python ADK

An interactive AI companion built using Google's Agent Development Kit (ADK), Gemini models, Flask, and custom AI-generated avatars.

This project was developed as part of the Google Developers Build with AI workshop:

Build Your First AI Companion: A Beginner's Workshop
https://codelabs.developers.google.com/companion-adk-beginner/instructions

## Overview

This application creates a conversational AI companion with:

* Google ADK (Agent Development Kit)
* Gemini 2.5 Flash
* Flask web application backend
* Interactive chat interface
* Animated avatar with lip-sync effect
* Custom AI-generated character images
* Google Cloud Shell development workflow

The companion responds to user messages through a web interface while displaying animated mouth movements during speech.

## Features

* Conversational AI powered by Gemini
* Customizable personality through prompt engineering
* Animated avatar system
* Responsive web interface
* Flask API backend
* Google ADK integration
* Google Cloud deployment workflow support

## Project Structure

```text
companion-python/
│
├── app.py                 # Flask application
├── character.py           # ADK agent definition
├── requirements.txt       # Python dependencies
├── set_env.sh             # Environment configuration
├── static/
│   ├── app.js             # Frontend logic
│   ├── style.css          # Styling
│   └── images/
│       ├── char-mouth-closed.png
│       └── char-mouth-open.png
│
└── templates/
    └── index.html
```

## Technologies Used

* Python
* Flask
* Google Agent Development Kit (ADK)
* Gemini 2.5 Flash
* HTML
* CSS
* JavaScript
* Google Cloud Shell
* Git & GitHub

## Setup

### Clone the Repository

```bash
git clone https://github.com/Ramisa1231/companion-python-adk.git
cd companion-python-adk
```

### Create a Virtual Environment

```bash
python -m venv .venv
source .venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure Environment

Set the required Google Cloud and Gemini credentials.

Update:

```bash
set_env.sh
```

with your project configuration and API credentials.

### Run the Application

```bash
source set_env.sh
python app.py
```

The application will run on:

```text
http://127.0.0.1:5000
```

## Customizations

This version includes:

* Custom AI-generated anime-style avatar
* Responsive avatar sizing improvements
* Lip-sync image switching animation
* Personalized companion behavior

## Learning Outcomes

Through this project I learned:

* Building AI agents with Google ADK
* Prompt engineering for agent personalities
* Integrating Gemini models into applications
* Flask web development
* Frontend-backend communication
* Google Cloud Shell workflows
* Git and GitHub collaboration
* AI-generated asset integration

## Acknowledgements

* Google Developers
* Build with AI Program
* Google Agent Development Kit (ADK)
* Gemini Models
* Google Cloud

## Author

Ramisa Fariha

GitHub: https://github.com/Ramisa1231
