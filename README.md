# CHD-Prediction
This project aims to predict the risk of Coronary Heart Disease (CHD) using machine learning techniques. The system consists of a Jupyter notebook for data analysis and model training, a Flask web application for user interaction, and necessary files for deployment.

## Files Included

- **framingham.csv**: Dataset containing health data for predicting CHD risk.
- **heart_disease_prediction.ipynb**: Jupyter notebook containing data analysis, feature engineering, model training, and model evaluation.
- **flask.py**: Flask application script for serving the trained model.
- **templates/index.html**: HTML template for the web interface.
- **model.pkl**: Serialized machine learning model saved in a .pkl file.
- **scalar.pkl**

## Usage

1. **Data Analysis and Model Training**: Open and run the `heart_disease_prediction.ipynb` notebook using Jupyter or any compatible environment. This notebook includes the entire process of data analysis, feature selection, model training, and evaluation. Choose the best-performing model and save it as `model.pkl`. I have selected the Random Forest as my choice.

2. **Flask Web Application**: Run the Flask application using the `flask.py` script. This will serve as a simple web interface allowing users to input their health data and obtain a CHD risk prediction.

    ```bash
    $ python flask.py
    ```

3. **Accessing the Application**: Once the Flask application is running, open your web browser and go to `http://localhost:8080` to access the CHD prediction interface. Input the required health data and submit the form to receive a prediction.

## Requirements

- Python 3.x
- Libraries listed within the code

## Installation

1. Clone this repository:

    ```bash
    $ git clone https://github.com/your_username/heart-disease-prediction.git
    $ cd heart-disease-prediction
    ```

3. Run the Flask application:

    ```bash
    $ python flask.py
    ```

---
