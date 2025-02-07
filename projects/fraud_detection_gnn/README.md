# Fraud Detection System using Graph Neural Networks

## Overview
This project leverages Graph Neural Networks (GNNs) to detect fraudulent transactions by analyzing the relational patterns within transaction networks.

## Business Use Case
- **Goal:** Provide a robust fraud detection mechanism to secure financial transactions.
- **Impact:** Minimize financial losses due to fraud and enhance overall transaction security.

## Data Collection
- **Sources:**  
  - Kaggle’s Fraud Detection datasets or similar sources.
- **Steps:**  
  1. Collect transaction data and user profiles.
  2. Build a graph structure representing transaction relationships.

## Methodology
1. **Data Preprocessing:**  
   - Clean the dataset and construct graphs using libraries like NetworkX.
2. **Model Development:**  
   - Implement GNN architectures such as GraphSAGE or GCN using PyTorch Geometric.
   - Train the model on historical fraud data.
3. **MLOps Pipeline:**  
   - Use MLflow to track experiments and containerize the solution with Docker.
4. **Deployment:**  
   - Expose the model via a FastAPI endpoint.  
   - Deploy on AWS (EC2 or Lambda) for real-time predictions.

## Technologies Used
- **Languages:** Python  
- **Libraries/Frameworks:** PyTorch Geometric, NetworkX, MLflow, Docker, FastAPI  
- **Cloud:** AWS (EC2, Lambda)  
- **Version Control:** Git & GitHub

## How to Run
1. Clone this repository.
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt