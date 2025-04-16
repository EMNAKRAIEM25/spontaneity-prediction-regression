# Spontaneity Prediction - Regression Model

This project aims to predict the spontaneity level of a person using 34 extracted features, including:
- 4 physiological traits (P1–P4)
- 4 eye-related traits (Y1–Y4)
- 26 facial traits (M1–M26)

It’s a **supervised regression** problem using the dataset `allFeaturesProcessedTraining.csv`.

## Files
- `ExamenIAA_EMNAKRAIEM.ipynb`: Main notebook with preprocessing, training & evaluation
- `model_gb_boosted.pkl`: Trained model
- `Resultats.csv`: Predictions

## Requirements
- Python 3.8+
- Scikit-learn
- Pandas
- NumPy
