# Wine_Quality_Prediction

This project demonstrates how to predict the quality of wine based on various chemical properties using machine learning. The dataset used for this project is the **Wine Quality Dataset**, which contains attributes such as fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, and others, with the target being the wine quality score.

## Project Overview

The objective of this project is to predict wine quality based on a set of chemical properties. This can help winemakers improve their products by understanding which chemical features influence quality the most.

## Dataset

The Wine Quality Dataset contains attributes like acidity, sulfur dioxide levels, pH, alcohol content, and others, which help predict the quality of wine. The dataset is available on the UCI Machine Learning Repository and includes both red and white wine datasets.

- **Link to Dataset**: [Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)

## Requirements

The following libraries are required to run the project:

- **Python 3.x**
- **Scikit-Learn**
- **Pandas**
- **Numpy**
- **Matplotlib**
- **Seaborn**

## Installation
1.Clone the repository.


```bash
     (https://github.com/maishaaibnat/MU_PDS-01_Maisha_Ibnat_PDS_ID-06_Wine_Quality_Prediction.git)
```

2.Install the required libraries
```bash
    pip install -r requirements.txt
```

## Usage

1.Load and explore the data.

2.Preprocess data, scale features, and split into training and testing sets.

3.Train a regression model to predict wine quality.

4.Evaluate model performance using metrics like Mean Squared Error and R² score.

5.Visualize the results.

## Run the main script to execute the entire pipeline:
```bash
  python main.py

```

## Running on Google Colab
You can also run this project on Google Colab for a cloud-based, no-installation setup. Follow these steps:

1.Upload the project files to Google Drive or download them directly within Colab.

2.Open a new Colab notebook.

3.Install any required libraries by running:
```bash
  !pip install -r requirements.txt

```

4.Load the dataset by uploading it to Colab or directly accessing it from a URL.

5.Copy and paste code from the main.py or run each code block individually in Colab cells.
Alternatively, you can add the following code to mount your Google Drive and access files:
```bash
from google.colab import drive
drive.mount('/content/drive')

```
6.Run the cells sequentially to complete the steps.

## Steps
### 1.Setup and Imports
Import libraries required for data handling, model training, evaluation, and visualization.

### 2.Load and Explore the Dataset
Load the Wine Quality Dataset using Pandas, perform exploratory data analysis (EDA) to understand data distributions, and check for any correlations between features.

### 3.Data Preprocessing
Handle missing values (if any), and scale the features using StandardScaler for better model performance.

### 4.Train-Test Split
Split the dataset into training and testing sets using an 80-20 ratio.

### 5.Model Selection and Training
Train a regression model, such as Linear Regression or Random Forest Regressor, to predict wine quality based on the chemical properties.

### 6.Prediction and Evaluation
Evaluate the model using metrics such as Mean Squared Error (MSE) and R² score.

### 7.Cross-Validation
Use k-fold cross-validation to assess the model's generalizability.

### 8.Visualization of Results
Plot actual vs. predicted values to visually assess the model’s performance.

## Conclusion
This project demonstrates how to build a machine learning model to predict wine quality based on chemical properties. The model's performance can be further improved by experimenting with different algorithms and hyperparameters.


