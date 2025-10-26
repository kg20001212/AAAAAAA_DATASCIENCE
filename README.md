# Flight Delay Prediction — On-premises and On-Cloud (AWS SageMaker)

## Project Overview
This project aims to predict whether a flight will be delayed by more than 15 minutes using machine learning.  
It implements two pipelines:
- **On-premises (Part A):** A local data science workflow using Jupyter Notebook and Scikit-learn.
- **On-Cloud (Part B):** The same pipeline replicated and deployed on **Amazon SageMaker**.

## Files in This Repository
- `onpremises.ipynb` — Data preprocessing, EDA, and baseline model training (Logistic Regression).
- `oncloud.ipynb` — Model training and evaluation on AWS SageMaker.
- `requirements.txt` — Python package dependencies.
- `README.md` — Documentation for setup and usage.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/<kg20001212>/<Assignment2>.git
