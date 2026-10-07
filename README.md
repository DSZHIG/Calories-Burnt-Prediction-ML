# Calories Burnt Prediction (ML)

This project predicts calories burned from exercise data using a Jupyter Notebook.

## Project Structure

- `calories_burnt_prediction.ipynb` - main notebook
- `exercise.csv` - exercise features
- `calories.csv` - target values
- `Calories_Prediction_Paper.pdf` - project report
- `Calories_Burnt_Prediction_Presentation.pdf` - presentation slides
- `requirements.txt` - Python dependencies

## Results

The final model is a tuned Gradient Boosting regressor:
R² = 0.9995, RMSE = 1.39 kcal, MAE = 0.96 kcal on the test set.

## Quick Start

1. Clone the repository and open the project folder.
2. Create and activate a Python virtual environment.
3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Run Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `calories_burnt_prediction.ipynb` and run cells from top to bottom.

## Notes

- The notebook uses relative file paths (`exercise.csv`, `calories.csv`), so it should run on any machine as long as these files remain in the project root.