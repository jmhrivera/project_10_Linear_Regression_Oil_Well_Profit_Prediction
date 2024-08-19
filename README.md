# project_10_Linear_Regression_Oil_Well_Profit_Prediction

## Overview
You work at the oil extraction company OilyGiant. Your task is to find the best places to open 200 new oil wells. The steps to complete this task include:

- Reading the files with the parameters collected from oil wells in the selected region: crude oil quality and reserve volume.
- Creating a model to predict the volume of reserves in new wells.
- Choosing the oil wells that have the highest estimated values.
- Selecting the region with the highest total profit for the selected oil wells.

You have data on crude oil samples from three regions. You will create a model that helps choose the region with the highest profit margin by analyzing potential benefits and risks using the bootstrapping technique.

## Requirements
- Python 3.x
- Pandas
- Numpy
- Scikit-learn
- Matplotlib

## Project Structure
- `data_preprocessing.py`: Code for loading, cleaning, and preprocessing the dataset.
- `model_training.py`: Code for training and evaluating the Linear Regression model.
- `profit_calculation.py`: Code for calculating the potential profit and applying the bootstrapping technique.
- `results_summary.py`: Code for summarizing the results and providing conclusions.

## Setup
1. Clone the repository:
```sh
git clone https://github.com/your_username/project_10_Oil_Well_Profit_Prediction.git
cd project_10_Oil_Well_Profit_Prediction
```

2. Install the required packages:
```sh
pip install -r requirements.txt
```
