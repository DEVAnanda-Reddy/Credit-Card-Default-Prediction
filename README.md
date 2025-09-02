# Credit-Card-Default-Prediction

A machine learning project to predict credit card defaults using classification models and provide business insights.

## Project Overview

This project analyzes credit card client data to predict the probability of default using various machine learning models. It includes:

* Data preprocessing
* Feature selection
* Model training and evaluation
* Hyperparameter tuning
* Saving the best model for future use

The goal is to provide actionable insights for management and generate daily defaulter reports.

## Folder Structure

```
Credit-Card-Default-Prediction/
│── data/             # Raw CSVs and processed datasets
│── models/           # Saved ML models (.pkl)
│── notebooks/        # Jupyter notebooks
│── requirements.txt  # Python dependencies
│── README.md         # Project documentation
│── main.py           # Optional: production-ready script
```

## Installation

1. Clone the repository:

```bash
git clone https://github.com/DEVAnanda-Reddy/Credit-Card-Default-Prediction.git
```

2. Navigate to the project folder:

```bash
cd Credit-Card-Default-Prediction
```

3. Create a virtual environment and install dependencies:

```bash
python -m venv venv
# Linux/Mac
source venv/bin/activate
# Windows
venv\Scripts\activate
pip install -r requirements.txt
```

## Usage

1. Place your CSV dataset in the `data/` folder.
2. Open the Jupyter notebook in `notebooks/` to explore, train models, and generate reports.
3. The best model will be saved automatically in the `models/` folder.

## Requirements

All required Python packages are listed in `requirements.txt`.
