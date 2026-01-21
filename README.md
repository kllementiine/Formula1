# Formula1

Semester project for Big Data & KI: exploring Formula 1 race results, feature engineering, and baseline models.

## Setup
- Install Python 3.9+ and `pip`.
- Install dependencies in one shot: `pip install -r libraries.txt`

## Workflow
- `notebooks/00_download_data.ipynb`: fetch raw CSVs (Kaggle).
- `notebooks/01_data_merge_base.ipynb`: merge/clean into a base table.
- `notebooks/02_features_model.ipynb`: build features and targets.
- `notebooks/03_model_training.ipynb`: encode, train/evaluate logistic regression and random forest, save the final model.

## Data
- Raw data: `data/raw/`
- Processed data and models: `data/processed/`
