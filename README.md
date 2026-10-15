# AQI Prediction System

A machine learning-based project for predicting the Air Quality Index
(AQI) using a Python backend and a web interface.

## Project Overview

Air quality is an important environmental concern. This project explores
the use of machine learning to estimate AQI from the data and input
features used by the model. It combines Python code for model-related
processing with an HTML interface.

## Features

-   Dataset preprocessing and preparation
-   Model training workflow
-   Python backend
-   HTML-based user interface
-   AQI prediction using the trained model

## Technologies

-   Python
-   HTML
-   CSV dataset
-   Machine-learning libraries used by the project

## Project Structure

``` text
aqi-prediction-system/
├── backend.py
├── model.py
├── train_model.py
├── index.html
├── cleaned_data.csv
└── README.md
```

## Getting Started

### Prerequisites

-   Python installed
-   Git installed (optional, for cloning the repository)
-   The Python packages required by the project

### Clone the repository

``` bash
git clone https://github.com/Navyab018/aqi-prediction-system.git
cd aqi-prediction-system
```

### Install dependencies

Install the Python libraries required by the project. Check the imports
in `backend.py`, `model.py`, and `train_model.py` to identify the exact
packages.

If the project includes a `requirements.txt` file, install dependencies
with:

``` bash
pip install -r requirements.txt
```

### Run the project

The exact startup command depends on how the backend is implemented.
Check `backend.py` for the application's entry point and run the
corresponding command. Open `index.html` in a browser if the interface
is designed to run directly as a local HTML page.

## Project Files

-   `backend.py` --- backend application logic
-   `model.py` --- model-related code
-   `train_model.py` --- model training script
-   `index.html` --- web interface
-   `cleaned_data.csv` --- prepared dataset used by the project

## Possible Future Improvements

-   Add clear AQI category labels and explanations
-   Visualize historical air-quality trends
-   Improve model evaluation and prediction performance
-   Improve interface usability and accessibility

## Project Type

Academic team project.

## Repository

https://github.com/Navyab018/aqi-prediction-system

## Contributions

This project was developed as a team project. Add the team members and
describe each person's contribution here before publishing, if
appropriate.
