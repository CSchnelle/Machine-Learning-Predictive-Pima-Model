# Pima Diabetes Prediction Model

A machine learning project that predicts the likelihood of diabetes onset 
in Pima Indian patients with 70%+ accuracy, following the end-to-end ML 
workflow from data preparation through model evaluation.

## Overview

This project applies the Machine Learning Workflow to the Pima Indians 
Diabetes dataset from the National Institute of Diabetes and Digestive 
and Kidney Diseases (NIDDK). The workflow covers:

- Data preparation and transformation
- Algorithm selection
- Model training
- Model evaluation and testing

## Dataset

**Source:** National Institute of Diabetes and Digestive and Kidney Diseases  
**Download:** [Pima Indians Diabetes Database](https://data.world/data-society/pima-indians-diabetes-database)

## Dependencies

| Library | Purpose |
|---|---|
| [scikit-learn](https://scikit-learn.org/stable/) | ML algorithms and model evaluation |
| [pandas](https://pandas.pydata.org/) | Data manipulation and analysis |
| [matplotlib](https://matplotlib.org/) | Data visualization |
| [numpy](https://numpy.org/) | Numerical computing |

## Repository Contents

- `notebook.ipynb` — Jupyter Notebook with full documented ML workflow
- `model.py` — Python source file
- `pima-indians-diabetes.csv` — Dataset file

## Usage

```bash
pip install scikit-learn pandas matplotlib numpy
jupyter notebook notebook.ipynb
```

## Results

Target accuracy: **70% or greater**
