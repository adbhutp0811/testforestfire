# Forest Fire Prediction App

A Flask web application that predicts forest fire risk using a Ridge regression model trained on the Algerian forest fires dataset.

## Project Structure

- `application.py` — Flask app entry point
- `models/` — Saved model artifacts (`ridge.pkl`, `scaler.pkl`)
- `notebooks/` — EDA and model training notebooks + cleaned dataset
- `templates/` — HTML templates
- `static/` — CSS assets

## Setup

```bash
pip install -r requirements.txt
python application.py
```

## Dependencies

Flask, numpy, pandas, scikit-learn
