# Formula One Race Result Prediction

This project aims to predict the results of Formula One races using machine learning techniques. The dataset used for this project is the Formula 1 World Championship (1950-2021) dataset from `Ergast API`. You can use the web scraping code from `record_datagathering.qmd`. 

## Getting Started

To run this project, you will need to have Python 3 and the following Python packages installed:

- numpy
- pandas
- scikit-learn
- scipy
- seaborn
- matplotlib

You will also need to have software installed to run and execute a Jupyter Notebook.

Once you have installed the required packages, you can clone this repository using the following command: 
    `git clone https://github.com/rdr-190100/f1_analysis.git`

## Data

The dataset used in this project contains the results of every Formula One race from 1950 to 2021. The dataset has been preprocessed and cleaned, so there is no need for additional data cleaning.

The dataset contains the following columns:

- raceId
- year
- round
- circuitId
- name
- date
- time
- url
- driverId
- constructorId
- grid
- position
- positionText
- positionOrder
- points
- laps
- time
- milliseconds
- fastestLap
- rank
- fastestLapTime
- fastestLapSpeed
- statusId

## Exploratory Data Analysis

Before building the machine learning model, we performed exploratory data analysis to gain insights into the dataset. Some of the visualizations we created include:
- Histograms of the number of races per year and the number of races per circuit
- Bar charts of the top 10 drivers and constructors by total number of points
- Heatmap of the correlation between features

## Machine Learning

### Supervised Learning

The following supervised learning techniques on the dataset were performed:

- Naive Bayes' Classifier
- Decision Tree
- Support Vector Machine

### Unsupervised Learning

The following unsupervised learning techniques on the dataset were performed:

- Clustering

## Results

The results of the machine learning model's accuracy are as follows:

- Naive Bayes' Classifier: 0.75
- Decision Tree: 0.78
- Support Vector Machine: 0.96

## Future Work

Some ideas for future work include:

- Using more advanced machine learning techniques, such as neural networks or ensemble methods


