# Chronic Kidney Disease Prediction

A Streamlit app that uses a saved Gradient Boosting model to predict chronic
kidney disease from the entered clinical measurements and health indicators.

## Run locally

Python 3.10 is recommended. From the repository root:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
python -m streamlit run app.py
```

The app loads its scaler and trained model from `models/`, so keep both model
files alongside `app.py`. Predictions are informational and are not a
substitute for assessment by a qualified healthcare professional.