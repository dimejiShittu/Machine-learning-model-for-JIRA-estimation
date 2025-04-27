# Udacity AI Capstone Project - JIRA Issue Duration Estimation

## Overview
This project is part of the Udacity AWS Machine Learning Nanodegree. It tackles the problem of estimating the resolution time (in days) of software engineering JIRA issues using structured and unstructured data from issue metadata and comments.

## Files Included
- `proposal.pdf` - Initial project proposal.
- `udacity_project.ipynb` - Jupyter notebook containing the full project workflow.
- `project_report.pdf` - Final project report formatted according to Udacity capstone submission requirements.
- `README.md` - This file.

## How to Reproduce
1. Install required packages:
```bash
pip install boto3 xgboost lightgbm tensorflow
```

2. Ensure you have AWS credentials set up to access S3.
3. Run the Jupyter notebook: `udacity_project.ipynb`.

## Python Libraries
- pandas
- numpy
- scikit-learn
- xgboost
- lightgbm
- tensorflow
- matplotlib
- seaborn
- boto3

## Dataset
The dataset used was retrieved from a private AWS S3 bucket (`sagemaker-us-east-1-841403222427/GFG_FINAL 2.csv`) which was downloaded for Kaggle dataset here https://www.kaggle.com/datasets/cesaranasco/jira-dataset.

