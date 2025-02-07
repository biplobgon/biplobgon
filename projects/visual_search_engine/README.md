# Visual Search for E-Commerce

## Overview
This project builds a visual search engine for e-commerce that uses computer vision to let users search for products by uploading images. It extracts visual features and matches them against a product database to find similar items.

## Business Use Case
- **Goal:** Enable image-based product search to improve the shopping experience.
- **Impact:** Increase conversion rates by providing a more intuitive and engaging search method.

## Data Collection
- **Sources:**  
  - Scraped product images and metadata from e-commerce sites.  
  - Public datasets from Kaggle.
- **Steps:**  
  1. Gather a dataset of product images.  
  2. Preprocess images (resize, normalize) and extract metadata.

## Methodology
1. **Data Preprocessing:**  
   - Process images using OpenCV and resize/normalize them.
2. **Model Development:**  
   - Use pre-trained CNN models (e.g., ResNet, VGG) to extract features.  
   - Implement similarity matching to compare feature vectors.
3. **MLOps Pipeline:**  
   - Track experiments using MLflow.  
   - Package the application with Docker.
4. **Deployment:**  
   - Build a front-end using Streamlit.  
   - Deploy on AWS (EC2/ECS) for scalability.

## Technologies Used
- **Languages:** Python  
- **Libraries/Frameworks:** PyTorch/TensorFlow, OpenCV, Scikit-learn, MLflow, Docker, Streamlit  
- **Cloud:** AWS (EC2, ECS)  
- **Version Control:** Git & GitHub

## How to Run
1. Clone this repository.
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt