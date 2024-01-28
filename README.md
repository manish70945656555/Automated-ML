# AutoML Solution

## Project Structure

- `data_processing.py`: Script for data processing.
- `descriptive_analysis.py`: Script for descriptive and graphical analysis.
- `auto_ml.py`: Script for model selection and hyperparameter tuning.
- `deployment.py`: Script for model deployment.

## How to Run

1. Install dependencies: `pip install -r requirements.txt`
2. Run data processing: `python data_processing.py dataset.csv`
3. Run descriptive analysis: `python descriptive_analysis.py`
4. Run AutoML: `python auto_ml.py`
5. Choose deployment option: `python deployment.py --option AWS`

## Dependencies

- pandas
- scikit-learn
- seaborn
- matplotlib
- tpot
- joblib
