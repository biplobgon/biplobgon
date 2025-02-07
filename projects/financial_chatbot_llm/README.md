# AI Chatbot for Financial Advisory

## Overview
This project builds an AI-powered chatbot designed for financial advisory, leveraging Large Language Models (LLMs) to assist users with investment queries and provide financial insights.

## Business Use Case
- **Goal:** Deliver instant, accurate financial advice via a conversational interface.
- **Impact:** Improve customer engagement and reduce response times for financial inquiries.

## Data Collection
- **Sources:**  
  - Financial news articles, investment reports, and curated FAQs.
  - Web scraping using BeautifulSoup or pre-collected datasets.
- **Steps:**  
  1. Gather and clean textual data related to financial markets.
  2. Build a corpus for training and fine-tuning the chatbot.

## Methodology
1. **Data Preprocessing:**  
   - Clean and preprocess text data for model fine-tuning.
2. **Model Development:**  
   - Fine-tune a pre-trained LLM (e.g., GPT-3 or Llama) on financial advisory data.  
   - Use LangChain to manage conversational flows.
3. **MLOps Pipeline:**  
   - Track model experiments using MLflow and automate deployment with GitHub Actions.
4. **Deployment:**  
   - Deploy the chatbot as an API on AWS Bedrock or Lambda.  
   - Build a user-friendly interface using Streamlit.

## Technologies Used
- **Languages:** Python  
- **Libraries/Frameworks:** Hugging Face Transformers, LangChain, MLflow, Streamlit  
- **Cloud:** AWS (Bedrock, Lambda)  
- **Version Control:** Git & GitHub

## How to Run
1. Clone this repository.
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt