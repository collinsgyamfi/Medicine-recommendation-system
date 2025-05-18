
# Medicine Recommendation System
## Objective
The Medicine Recommendation System is designed to help pharmacists and other health professionals find effective alternative medicines based on their current prescription. By leveraging data-driven similarity analysis, it provides safe and relevant options, supporting informed healthcare decisions and improving access to suitable treatments

## Overview
This project implements a Medicine Recommendation System using Natural Language Processing (NLP) techniques with the `nltk` library. The system processes a dataset of medicines, performs data cleaning, feature extraction, and builds a Flask application to serve the model.

## Table of Contents
- [Installation](#installation)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Model Training](#model-training)
- [Flask Application](#flask-application)
- [Usage](#usage)
- [Contributing](#contributing)


## Dataset
The dataset used in this project is `medicine.csv` from kaggle, which contains information about various medicines. The dataset includes features that will be utilized for recommendations.

## Data Preprocessing

1. **Data Cleaning**: 
   - Removed duplicates and irrelevant entries.
   - Handled missing values.

2. **Text Processing**:
   - Used tokenization and stemming for text normalization.

3. **Feature Extraction**:
   - Employed CountVectorizer to convert text data into numerical format.

## Model Training
1. Saved the trained model as a `.pkl` file for future use.

## Flask Application

1. Created a Flask app to serve the trained model.
2. Developed an HTML interface for user interaction.
3. Implemented routes for model prediction based on user input.

## Usage

1. Run the Flask application:
   ```bash
   python app.py
   ```

2. Open your web browser and navigate to `http://127.0.0.1:5000/` to access the application.

3. Enter the required details in the interface to get medicine recommendations.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for discussion.

