# Airline Sentiment Classification with BERT and Deep Learning Models

This repository contains the full implementation of a capstone research project focused on sentiment analysis of U.S. airline tweets using both traditional and transformer-based models.

## 📌 Project Overview

This project evaluates the performance and efficiency of several models on the task of sentiment classification:

- **Transformer-based**: BERT, DistilBERT, GPT-2, RoBERTa, DeBERTa, ModernBERT  
- **Traditional deep learning**: CNN, LSTM

Each model is trained and evaluated using the same preprocessing pipeline and hyperparameters to ensure a fair comparison. Metrics like accuracy, F1-score, recall, training time, and inference speed are reported.

## 🗂️ Dataset

- **Source**: [Kaggle Airline Twitter Sentiment](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment)
- **Size**: 14,640 labeled tweets (Positive, Neutral, Negative)
- **Note**: The dataset is class-imbalanced and contains informal, user-generated content.

## 🚀 Models & Frameworks

- HuggingFace Transformers: `bert-base-uncased`, `distilbert-base-uncased`, `gpt2`, `roberta-base`, `microsoft/deberta-base`, `answerdotai/modernbert-base`
- PyTorch + Transformers + Scikit-learn
- Custom CNN and LSTM architectures for comparison

## 🔧 How to Run

1. Clone the repository and navigate into it:
   ```bash
   git clone https://github.com/yourusername/airline-sentiment.git
   cd airline-sentiment
2. Install dependencies:
   ```bash
pip install -r requirements.txt
3. Place your dataset (0000.parquet) in the working directory.
4. Run the main script:
   ```bash
python Lori_Code.py
