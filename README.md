# Algerian Forest Fire Prediction using Machine Learning

## Project Description

This project focuses on predicting forest fire occurrence in Algeria
using Machine Learning techniques. The model is trained on the Algerian
Forest Fires dataset and deployed using Flask to provide predictions
based on input features.

The goal of this project is to demonstrate an end-to-end Machine
Learning workflow including data preprocessing, model training,
evaluation, and deployment using a web application.

------------------------------------------------------------------------

## Dataset Information

-   Dataset: Algerian Forest Fires Dataset
-   Source: UCI Machine Learning Repository
-   Region: Algeria
-   Features include temperature, humidity, wind speed, rain, and fire
    weather indices.
-   Target: Fire occurrence (Fire / No Fire)

------------------------------------------------------------------------

## Technologies Used

-   Python
-   NumPy
-   Pandas
-   Scikit-learn
-   Flask
-   HTML (for UI, if applicable)

------------------------------------------------------------------------

## Project Structure

    algerianforestfire/
    │
    ├── app.py                  # Flask application
    ├── model.pkl               # Trained machine learning model
    ├── requirements.txt        # Required Python libraries
    ├── templates/              # HTML templates
    │   └── index.html
    ├── static/                 # CSS / JS files
    ├── notebooks/              # Jupyter notebooks for training and analysis
    └── README.md               # Project documentation

------------------------------------------------------------------------

## Machine Learning Model

-   Algorithm Used: Linear Regression / Logistic Regression
-   Data preprocessing includes:
    -   Handling missing values
    -   Feature scaling
    -   Train-test split
-   The trained model is saved using `pickle` and loaded into the Flask
    app.

------------------------------------------------------------------------

## How to Run the Project

### 1. Clone the Repository

    git clone <repository_url>

### 2. Navigate to the Project Directory

    cd algerianforestfire

### 3. Create and Activate Virtual Environment

    python -m venv venv
    venv\Scripts\activate

### 4. Install Required Dependencies

    pip install -r requirements.txt

### 5. Run the Flask Application

    python app.py

### 6. Open Browser

Go to:

    http://127.0.0.1:5000

------------------------------------------------------------------------

## Output

The Flask web application accepts user inputs related to weather
conditions and predicts whether a forest fire is likely to occur.

------------------------------------------------------------------------

## Conclusion

This project demonstrates how a Machine Learning model can be trained
and successfully deployed using Flask. It provides a practical
understanding of real-world ML deployment and end-to-end project
workflow.

------------------------------------------------------------------------

## Author

Jaya Sri Ambavarapu
