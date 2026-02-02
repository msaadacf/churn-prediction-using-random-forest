# PowerClient Churn Prediction Using Random Forest Model
This project was part of a course case study where I performed end-to-end churn analysis on a real client data. 
This repository contains a single Jupyter Notebook with the all of the churn analysis I conducted. The notebook contains EDA, feature engineering, Random Forest baseline, evaluation, and feature importance.

I have not shared the full data files or the case study draft to comply with the confidentiality agreement of client as well as the provider.

## Files
- `PowerClient_Churn_Analysis.ipynb` is the main analysis notebook.
- `Recommendation_Slides.pdf` is the one-page executive recommendation summary based on analysis.
- `data/` — dataset folder (raw data not shared due to confidentiality, only data snippets are shared)

## Data access (not included)
The dataset used in this project is confidential client data, hence not provided.  
To run the notebook locally, place the following files into `data/`. You can generate a synthetic dataset based on the very few snippets of data I have provided. Please get in touch if you wish to see full datasets.

- `client_data.csv`
- `price_data.csv`

## Baseline model results (Random Forest)
Confusion matrix:
- TP = 17, FP = 3
- TN = 3283, FN = 349

Metrics:
- Accuracy = 0.9036
- Precision = 0.85
- Recall = 0.0464

Interpretation: While the precision is high, the recall is low. Model has flagged churners conservatively. 

## How to view?
Open `PowerClient_Churn_Analysis.ipynb` directly in GitHub to view the rendered outputs.
