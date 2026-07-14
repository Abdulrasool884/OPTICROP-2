# OptiCrop – Smart Agricultural Production

## Project Overview

OptiCrop is a Machine Learning-based Smart Agricultural Production System that recommends the most suitable crop based on soil nutrients and environmental conditions. The project includes data analysis, machine learning model development, documentation, and a Flask-based web application.

## Features

- Crop Recommendation using Machine Learning
- Data Preprocessing and Analysis
- Interactive Flask Web Application
- User-Friendly Interface
- Fast and Accurate Predictions
- Deployment on Render

## Input Parameters

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- pH Value
- Rainfall

## Technologies Used

- Python
- Flask
- HTML
- CSS
- Pandas
- NumPy
- Scikit-Learn
- Jupyter Notebook
- Render

## Machine Learning Model

**Model Used:**
- Random Forest Classifier

## Repository Structure

```
OPTICROP-2/
│
├── 05.Project Development phase/
│   ├── OptiCrop_Website/
│   ├── Crop_recommendation.csv
│   ├── crop_Recommendation.ipynb
│   ├── coding&Solutions.pdf
│   ├── codeLayout,Readability and Reusability.pdf
│   └── No. of Functional Features Included.pdf
│
└── README.md
```

## Run the Website

```bash
pip install -r requirements.txt
python app.py
```

Open:

```
http://127.0.0.1:5000
```

## Deployment

Build Command:

```bash
pip install -r requirements.txt
```

Start Command:

```bash
gunicorn wsgi:app
```

## Authors

- Abdul Rasool
- Tanuboddi Siva Sai Sri Sachin Reddy
- Lasya
