# Webtoon Adaptation Success Prediction

This project explores which webtoon signals best predict adaptation success in Korean drama production.
It combines webtoon metadata, K-drama metadata, and adaptation history to train and compare machine learning models for ranking unadapted titles by likely success.

## Project Goal

- Build a data-driven ranking system for unadapted webtoon titles.
- Identify which features matter most for predicting popularity.
- Compare model performance across:
  - Ridge Regression
  - Random Forest
  - XGBoost

## Modeling Pipeline

![Modeling Pipeline](./Modeling%20pipeline.png)

## Project Structure

- `modeling.ipynb`: Main modeling notebook
- `adaptation-data.ipynb`: Adaptation-focused data prep and analysis
- `all-we-data.ipynb`: Webtoon dataset analysis
- `kdrama-data.ipynb`: K-drama dataset analysis
- `data/`: Cleaned and raw combined datasets used in experiments
- `pdf/`: Reference source documents

## Key Output

The final workflow produces:

- A composite popularity target
- Trained and validated models
- Feature importance insights
- Ranked predictions for top unadapted titles

## How to Run

1. Clone the repository.
2. Open the notebooks in Jupyter or VS Code.
3. Run data prep notebooks first, then `modeling.ipynb`.
4. Review output tables and ranking results.

## Read the Full Write-Up

You can read the full project article on DEV Community:

[What Predicts a Hit? I Trained 3 ML Models to Find Out](https://dev.to/carasjung/what-predicts-a-hit-i-trained-3-ml-models-to-find-out-31mj)
