# AI Credit Scoring Model

## Overview
This project develops an AI-powered credit scoring model to assess loan risk by predicting the likelihood of default using historical financial data.

## Business Use Case
- **Goal:** Enable financial institutions to make informed lending decisions by accurately assessing credit risk.
- **Impact:** Reduce loan default rates and improve portfolio management.

## Data Collection
- **Sources:**  
  - Kaggle’s Home Credit Default dataset or similar financial data sources.
- **Steps:**  
  1. Download and explore the dataset.  
  2. Preprocess data (handle missing values, encode categorical variables).

## Methodology
1. **Data Preprocessing:**  
   - Normalize and clean the data for modeling.
2. **Model Development:**  
   - Train several models including LightGBM, Neural Networks, and use AutoML tools to select the best performer.
3. **MLOps Pipeline:**  
   - Track experiments with MLflow and automate testing/validation with GitHub Actions.
4. **Deployment:**  
   - Deploy the model on AWS SageMaker.  
   - Create a user interface with Streamlit for querying credit scores.

## Technologies Used
- **Languages:** Python  
- **Libraries/Frameworks:** Scikit-learn, LightGBM, TensorFlow/PyTorch, MLflow, Streamlit  
- **Cloud:** AWS (SageMaker)  
- **Version Control:** Git & GitHub

## How to Run
1. Clone this repository.
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
