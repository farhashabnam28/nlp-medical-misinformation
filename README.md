# NLP Medical Misinformation Detection

This project detects **medical misinformation in text using Natural Language Processing (NLP)** and a transformer-based model.

## Project Overview
Medical misinformation can spread quickly online. This project uses a machine learning model to classify medical statements as **True** or **Misleading**.

## Features
- Text preprocessing using NLP techniques
- Transformer-based model for classification
- Binary classification (True / Misleading)
- Model prediction for new sentences
- Explainable AI for interpreting predictions

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Transformers
- PyTorch
- Streamlit (for web app)

## Dataset
The dataset contains medical statements labeled as:
- True
- Partially True
- Misleading
- False

For modeling, labels were merged into:
- **True**
- **Misleading**

## Model
The model used in this project is:

DistilBERT for Sequence Classification

It is fine-tuned to classify medical text statements.

## Example Prediction

Input:
