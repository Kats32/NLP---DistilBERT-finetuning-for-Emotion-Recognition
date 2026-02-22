# Emotion Recognition using DistilBERT

This project focuses on fine-tuning a pre-trained transformer model (DistilBERT) for multi-class emotion classification using a Hugging Face dataset.

## Project Objective

The goal of this project is to build an NLP model that can classify text into different emotional categories such as:

- Joy
- Sadness
- Anger
- Fear
- Love
- Surprise

Instead of training from scratch, this project leverages transfer learning by fine-tuning a pre-trained transformer model.

## Model

### Base Model: DistilBERT
### Architecture Type: Transformer-based encoder
### Task: Sequence Classification

DistilBERT is a smaller and faster version of BERT that retains most of its performance while reducing computational cost.

## Workflow (Current)

 - Load dataset using Hugging Face datasets
 - Tokenize text using AutoTokenizer
 - Encode labels
 - Set up training pipeline
 - Hyperparameter tuning
 - Detailed evaluation metrics (F1-score, confusion matrix)
 - Error analysis
 - Model optimization

## Evaluation Metrics

### Currently tracking:

- Training Loss
- Validation Loss
- Accuracy

### Planned:

- F1 Score
- Confusion Matrix
- Per-class performance analysis

## Tech Stack

- Python
- PyTorch
- Hugging Face Transformers
- Hugging Face Datasets
- NumPy
- Matplotlib

## Future Improvements

- Learning rate experimentation
- Class imbalance handling
- Model checkpoint saving
- Deployment using FastAPI
- Simple web interface for live emotion prediction

## Why This Project?

### This project demonstrates:

- Understanding of transfer learning
- Practical fine-tuning of transformer models

Real-world NLP pipeline implementation

Training and evaluation workflow design
