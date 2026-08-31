# Heart Disease Prediction ML Project

<p align="center">
  <img src="output/target_distribution.png" alt="Target Distribution" width="700" />
</p>

This project trains and compares multiple machine learning models to predict heart disease from the provided heart attack dataset.

## What it does

- Loads `Heart Attack Data Set.csv`
- Cleans and scales the data
- Splits the dataset into training and test sets
- Trains and compares these classifiers:
  - Decision Tree
  - Random Forest
  - AdaBoost
  - Gradient Boosting
- Prints performance metrics such as accuracy, precision, recall, and F1-score
- Generates visualisations and saves outputs in the `output/` folder

## Project Files

- `heart_disease_ml.py` - main script for training, evaluation, and visualisation
- `Heart Attack Data Set.csv` - dataset used by the model
- `output/` - generated charts and results

## Requirements

- Python 3.9 or later
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Installation

If you do not already have the dependencies installed, run:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## How to Run

From the project folder, run:

```bash
python heart_disease_ml.py
```

## Notes

- Make sure `Heart Attack Data Set.csv` stays in the same folder as the Python script.
- The script will create the `output/` folder automatically if it does not already exist.

## Output

When the script runs, it prints dataset information, model comparison results, and patient-level predictions in the terminal. It also creates plots for data exploration and model analysis.

## Disclaimer

This project is for educational and demonstration purposes only. It should not be used as a medical diagnosis tool.
