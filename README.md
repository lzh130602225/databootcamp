# Ames Housing Price Prediction

This project predicts house sale prices in Ames, Iowa. The notebook explains how we checked the data, compared regression models, and revised our submissions from V1 to V11. The final model blends Ridge, Extra Trees, and Huber gradient boosting.

Our V11 Kaggle submission scored **33,765.45286 public RMSE** and **23,767.77978 private RMSE**. Earlier scores and the reasons for each model change are in the notebook.

## Files

- `ames_housing_v11.ipynb`: model development and results
- `train.csv`, `test.csv`, `sample_soln.csv`: competition data and submission template
- `ames_submission_v11.csv`: final predictions submitted to Kaggle
- `ames_submission_v10.csv`: preceding submission for comparison
- `requirements.txt`: Python packages

## Run

Install the packages in `requirements.txt`, then run the notebook from top to bottom with the CSV files in the same folder. The final cell writes `ames_submission_v11.csv`. The target is `SalePrice`, predictions follow the row order of `test.csv` and use the IDs in `sample_soln.csv`, and `solns.csv` was not used.
