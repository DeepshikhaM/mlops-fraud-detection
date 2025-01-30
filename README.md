# mlops-fraud-detection
End-to-End MLOps Pipeline for Fraud Detection This project implements a fraud detection system with an end-to-end MLOps pipeline. It includes data preprocessing, model training (MLflow), API deployment (FastAPI), containerization (Docker), and CI/CD automation (GitHub Actions).
# Fraud Detection MLOps Pipeline

## Overview
This project implements an end-to-end MLOps pipeline for fraud detection using machine learning.

## Features
- Data Preprocessing & Feature Engineering
- Model Training & Experiment Tracking (MLflow)
- API Deployment (FastAPI)
- Containerization (Docker)
- CI/CD Automation (GitHub Actions)

## Installation
```sh
python -m venv env
source env/bin/activate  # For Linux/Mac
env\Scripts\activate    # For Windows
pip install -r requirements.txt
```

## Running the API
```sh
uvicorn src.api.main:app --host 0.0.0.0 --port 8000
```

## Running with Docker
```sh
docker build -t fraud-detection .
docker run -p 8000:8000 fraud-detection
```

## License
This project is licensed under the MIT License.
