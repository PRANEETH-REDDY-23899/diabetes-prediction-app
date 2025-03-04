# Diabetes Prediction App [![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/arunnthevapalan/diabetes-prediction-app/app.py)
Streamlit Web App to predict the onset of diabetes based on diagnostic measures. 
## Live Demo :[diabetes_prediction](https://diabetes-alpha.herokuapp.com/)
## kaggle notebook :[kaggle Notebook](https://www.kaggle.com/nakkapraneethreddy/pima-indians-diabetes-prediction/)

## Data

The data for the following example is originally from the [National Institute of Diabetes and Digestive and Kidney Diseases](https://www.niddk.nih.gov/) and is [available on Kaggle.](https://www.kaggle.com/uciml/pima-indians-diabetes-database) The data contains information on females at least 21 years old of Pima Indian heritage.
Since the data has been added to the `data/` directory, cloning this repository would suffice.
## Pre-requisites

The project was developed using python 3.6.7 with the following packages.
- Pandas
- Numpy
- Scikit-learn
- Pandas-profiling
- Joblib
- Streamlit

Installation with pip:

```bash
pip install -r requirements.txt
```

## Getting Started
Open the terminal in you machine and run the following command to access the web application in your localhost.
```bash
streamlit run app.py
```



## Summary
This repository acts as a guide to [this blog post] where I talk about how I use Streamlit to build Machine Learning Applications quickly. Here we use a real-world example of predicting if a patient has diabetes and built a machine learning model. A Streamlit App was then built using a step-by-step approach in this project.

## Acknowledgements

[Kaggle](https://kaggle.com/), for providing the data for the machine learning pipeline.  
[Streamlit](https://www.streamlit.io/), for the open-source library for rapid prototyping.



