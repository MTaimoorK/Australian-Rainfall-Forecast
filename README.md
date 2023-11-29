# _Australian Rainfall Prediction_

_Author: Muhammad Taimoor Khan_

## Overview

Welcome to the "Australian Rainfall Prediction" project! This repository contains the code and analysis for predicting rainfall patterns in Australia. Leveraging machine learning models, the project aims to provide accurate and actionable insights for weather forecasting.

## Project Structure

- `Australian_Rainfall_Forecast.ipynb`: Notebook that contains Python scripts for data preprocessing and machine learning model training.
- `weather_data.csv`: Dataset used in the analysis.
- `README.md`: Overview of the project, its goals, and key findings.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/MTaimoorK/australian-rainfall-prediction.git

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt

## Explore the Code

  - Review the Jupyter Notebooks in the code/ directory for detailed analysis.
  - Execute scripts for data preprocessing and model training.

## Results
### Linear Regression:

- **Mean Absolute Error:** 0.256
- **Mean Squared Error:** 0.116
- **R2 Score:** 0.427

### K-Nearest Neighbour:

- **Accuracy Score:** 0.818
- **Jaccard Index:** 0.425
- **F1-Score:** 0.597
- **Log Loss:** N/A

### Decision Tree:

- **Accuracy Score:** 0.756
- **Jaccard Index:** 0.401
- **F1-Score:** 0.572
- **Log Loss:** N/A

### Logistic Regression:

- **Accuracy Score:** 0.837
- **Jaccard Index:** 0.509
- **F1-Score:** 0.675
- **Log Loss:** 0.380

### Support Vector Machine:

- **Accuracy Score:** 0.846
- **Jaccard Index:** 0.535
- **F1-Score:** 0.697
- **Log Loss:** N/A

## Future Enhancements
Explore potential areas for improvement and future enhancements, such as incorporating real-time data or exploring additional machine learning algorithms.

## Contribution
Feel free to contribute by forking the repository and submitting pull requests. Bug fixes, feature enhancements, and additional analyses are all welcome!
