# Titanic Survival Prediction with Random Forest

This repository contains a machine learning model developed to predict the survival of Titanic passengers using data from the famous Kaggle dataset. The project focuses on using Random Forest as a classifier and includes basic steps for data analysis and preprocessing.

## Key Features
- Loading and initial analysis of the training and testing datasets.
- Implementation of a `RandomForestClassifier` model from the `sklearn` library.
- Model parameter tuning to optimize performance.
- Use of simple approaches, such as majority choices, to handle missing or categorical values.

## Technologies Used
- `pandas` for data manipulation.
- `numpy` for mathematical calculations.
- `scikit-learn` for machine learning model development.

## How to Use
1. Clone this repository.
2. Ensure the `train.csv` and `test.csv` files are available in the same folder as the notebook.
3. Run the notebook to train the model and generate predictions.

## Results
- The model achieved a score of 0.76 on Kaggle.

## Next Steps
- Experiment with other classifiers. (Done)
- Implement cross-validation to improve generalization. (Done)
- Enhance the model's performance to increase the Kaggle score.
