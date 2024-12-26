# RUSHI VARMROA (25PGAI0142)
# Text Classification Project

This project implements a text classification system using FastAPI for serving a machine learning model. Below is the directory structure and purpose of each component.

## Directory Structure

```plaintext
text_classification/
├── app/
│   ├── main.py       # FastAPI app
│   ├── routes.py     # API routes
├── model/
│   ├── train.py      # Model training
│   ├── predict.py    # Prediction logic
├── requirements.txt   # Dependencies
└── README.md          # Documentation


## Install dependencies:

```bash
pip install -r requirements.txt

## Deployment
```bash
uvicorn app.main:app --reload

