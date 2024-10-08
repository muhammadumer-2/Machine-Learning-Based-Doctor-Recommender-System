# Machine Learning-Based Doctor Recommender System

## Overview
This project is a Machine Learning-based Doctor Recommender System designed to help users find the most suitable doctors based on various attributes. The system collects data from the oladoc.com website, processes it, and uses a machine learning model to provide personalized recommendations to patients.

## Features
- **Data Collection**: Web scraping using Python's Beautiful Soup to extract doctor information from oladoc.com.
- **Data Preprocessing**: Cleaning, normalization, and transformation of the raw data to ensure high-quality data for machine learning.
- **Machine Learning Model**: A binary classification model that recommends doctors based on key attributes such as patient satisfaction (over 95%) and experience.
- **User-Friendly Interface**: Patients can input preferences (location, specialty, etc.) and receive personalized recommendations.
- **Feedback Mechanism**: Users can provide feedback and rate the system's recommendations for continuous improvement.

## Project Structure

- data_collection.py # Web scraping script for collecting doctor data
- data_preprocessing.py # Data cleaning and preprocessing script
- model_training.py # Script for training the machine learning model
- app.py # Flask application for running the web interface
- templates/ # Contains HTML templates for the web application
- static/ # Contains CSS and other static files for the frontend
- requirements.txt # List of dependencies required for the project


## Functionalities

### Admin
- Collect and preprocess doctor data.
- Train and manage the machine learning model.
- Monitor feedback provided by users.

### User
- Input preferences for doctor search (specialty, location, fees, etc.).
- Receive a list of recommended doctors.
- Provide feedback and rate the doctor recommendations.

## Tools and Technologies

- Python: The core programming language used in the project.
- Beautiful Soup: For web scraping doctor data.
- scikit-learn: For building the machine learning model.
- Flask: For developing the web-based user interface.
