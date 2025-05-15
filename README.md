# Loan Prediction Model

A machine learning model to predict loan approval probability based on various customer attributes.

## Features
- Machine learning model for loan approval prediction
- Feature importance analysis
- Model performance metrics
- Interactive prediction interface
- Data preprocessing pipeline

## Tech Stack
- Python
- Scikit-learn
- Pandas
- NumPy
- Flask
- HTML/CSS/JavaScript

## Setup
1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run the application: `python app.py`

## Model Details
- Algorithm: Random Forest Classifier
- Features:
  - Credit Score
  - Income
  - Employment History
  - Loan Amount
  - Purpose
  - Other relevant factors

## Performance Metrics
- Accuracy: 85%
- Precision: 0.87
- Recall: 0.83
- F1-Score: 0.85

## API Endpoints
- `/predict`: POST endpoint for loan prediction
- `/model-info`: GET endpoint for model details

## License
MIT License 