# Australia Rain Prediction using Logistic Regression

This repository contains a Jupyter Notebook that demonstrates the use of logistic regression to predict rainfall in Australia. The goal of this analysis is to forecast whether it will rain on the following day based on various meteorological features.

## Table of Contents

- [Overview](#overview)
- [Data](#data)
- [Dependencies](#dependencies)
- [Notebook Structure](#notebook-structure)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project aims to predict the likelihood of rainfall in Australia using logistic regression, a common classification algorithm. The notebook outlines the process of data exploration, preprocessing, model training, and evaluation.

## Data

The dataset used in this notebook is from [Kaggle's Australia Weather Dataset](https://www.kaggle.com/jsphyg/weather-dataset-rattle-package). It includes daily weather observations from various locations in Australia.

### Features

- `Date`: Date of observation
- `Location`: Weather station location
- `MinTemp`: Minimum temperature in degrees Celsius
- `MaxTemp`: Maximum temperature in degrees Celsius
- `Rainfall`: Amount of rainfall in mm
- `Evaporation`: Evaporation in mm
- `Sunshine`: Sunshine duration in hours
- `WindGustDir`: Direction of the strongest wind gust
- `WindGustSpeed`: Speed of the strongest wind gust in km/h
- `WindDir9am`: Wind direction at 9am
- `WindDir3pm`: Wind direction at 3pm
- `WindSpeed9am`: Wind speed at 9am in km/h
- `WindSpeed3pm`: Wind speed at 3pm in km/h
- `Humidity9am`: Humidity at 9am
- `Humidity3pm`: Humidity at 3pm
- `Pressure9am`: Atmospheric pressure at 9am
- `Pressure3pm`: Atmospheric pressure at 3pm
- `Cloud9am`: Cloud cover at 9am
- `Cloud3pm`: Cloud cover at 3pm
- `Temp9am`: Temperature at 9am
- `Temp3pm`: Temperature at 3pm
- `RainToday`: Whether it rained today (Yes/No)
- `RainTomorrow`: Target variable indicating whether it will rain tomorrow (Yes/No)

## Dependencies

The notebook requires the following Python packages:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install the required packages using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Notebook Structure

The Jupyter Notebook is structured as follows:

1. **Introduction**: Overview of the project and objectives.
2. **Data Loading**: Importing and inspecting the dataset.
3. **Data Preprocessing**: Handling missing values, encoding categorical variables, and feature scaling.
4. **Exploratory Data Analysis (EDA)**: Visualizations and analysis to understand data patterns and relationships.
5. **Model Building**: 
   - **Splitting Data**: Training and testing set creation.
   - **Training the Model**: Implementing and training the logistic regression model.
   - **Hyperparameter Tuning**: Adjusting model parameters for better performance.
6. **Evaluation**: Assessing model performance using metrics like accuracy, roc-curve, precision, recall, and F1-score.
7. **Results**: Interpretation of the results and insights.
8. **Conclusion**: Summary of findings and potential next steps.

## Usage

To run the notebook, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/Bilal-ahmad8/Data-Science-Portfolio.git
   ```

2. Navigate to the directory:

   ```bash
   cd Data-Science-Portfolio/Australia\ Rain\ Prediction\ using\ Logistic\ Regression
   ```

3. Launch Jupyter Notebook:

   ```bash
   jupyter notebook Australia_Rain_Predictions.ipynb
   ```

4. Open the notebook and execute the cells to run the analysis.

## Results

The notebook demonstrates how logistic regression can be used to predict rainfall. Key results include:

- Model accuracy and performance metrics.
- Visualizations of feature importance and model predictions.
- Insights into the factors influencing rainfall predictions.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request with your improvements. Ensure that your code adheres to the existing coding style and includes relevant tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
