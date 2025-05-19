# Explainable Depression Detection from Social Media Using LSTM

## Description  
Explainable depression detection using LSTM and attention-based NLP models on social media text. This tool classifies posts as depression-related or not, providing interpretable insights to support early mental health interventions.

## Abstract  
Depression is a widespread mental health disorder with severe impacts, requiring timely detection for effective treatment. Traditional ML methods face challenges like limited annotated data and low interpretability. This study develops an explainable LSTM-based model that captures sequential patterns in social media text and uses attention mechanisms to reveal decision factors. Evaluated on a public Mental Health dataset, the model demonstrates high accuracy and interpretability, making it a valuable tool for automated depression screening.

## Proposed System  
- Long Short-Term Memory (LSTM) and Gated Recurrent Unit (GRU) networks capture sequential dependencies in text data.  
- Attention mechanisms enhance model transparency by highlighting important features.  
- Provides scalable and interpretable depression detection from social media content.

## Requirements  
- Python 3.8  
- Flask==3.0.3  
- numpy==1.24.3  
- joblib==1.4.2  
- tensorflow==2.13.0

## Usage  
Run the application with:  
```bash
python app.py
