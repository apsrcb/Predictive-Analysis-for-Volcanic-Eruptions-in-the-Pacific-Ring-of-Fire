# Predictive Analysis for Volcanic Eruptions in the Pacific Ring of Fire

## Project Description

This project aims to predict volcanic eruptions and visualize volcanic activity data using machine learning algorithms and data visualization techniques. The goal is to build predictive models that can classify volcanic eruptions based on historical data and provide insights into eruption patterns in the Pacific Ring of Fire. The Pacific Ring of Fire is a region with a high concentration of active volcanoes and frequent seismic activity, making it an ideal location for studying volcanic behavior.

Volcanic eruptions pose significant risks to communities and the environment, and predicting them accurately can help in disaster preparedness and response. The project focuses on developing machine learning models that can predict eruptions in the Pacific Ring of Fire, based on features such as location, magnitude, eruption type, and other relevant attributes.

## Table of Contents

- [Project Description](#project-description)
- [Technologies Used](#technologies-used)
- [Data](#data)
- [Machine Learning](#machine-learning)
- [License](#license)

## Technologies Used

- Python
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow
- Keras

## Data

The project uses historical volcanic activity data for the Pacific Ring of Fire. The data includes attributes such as location, magnitude, eruption type, and more.

## Machine Learning

The data is preprocessed, relevant features are selected, and the dataset is split into training and testing sets. Four machine learning models are trained and their accuracy is evaluated:

- Support Vector Machine (SVM) classifier
- Logistic Regression classifier
- Random Forest classifier
- Gaussian Process classifier

Test data is loaded from the CSV file `philippinestest.csv`, and volcanic eruption predictions are made using the trained Random Forest classifier. The results are displayed for each data point, indicating whether eruption activity is detected or not.

## Authors

- [@rithikabadam](https://github.com/rithikabadam)
- [@sindhoori-kaza](https://github.com/sindhoori-kaza)
