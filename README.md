# 📰 Fake News Detector — ML + NLP + Transformers

## Overview
End-to-end fake news detection system comparing three 
approaches from classical ML to state-of-the-art Transformers.

## Results
| Model                  | Test Accuracy | Real Headlines | Notes                    |
|------------------------|---------------|----------------|--------------------------|
| TF-IDF + Log. Reg.     | 98.52%        | ❌ Fails       | Learned dataset shortcuts|
| DistilBERT (fine-tuned)| 94.60%        | ✅ Works       | Generalizes correctly    |

## Key Insight
Higher benchmark accuracy ≠ better real-world model.
TF-IDF learned source formatting patterns (Reuters dateline).
DistilBERT learned actual linguistic patterns of fake vs real news.

## Tech Stack
Python, Scikit-learn, HuggingFace Transformers,
PyTorch, Pandas, Matplotlib

## Project Structure
├── fake_news_detector.ipynb   ← main notebook
├── README.md
└── requirements.txt

## How to Run
1. Download dataset from Kaggle (link below)
2. Open notebook in Google Colab
3. Runtime → T4 GPU → Run All

## Dataset
Kaggle: fake-and-real-news-dataset by Clément Bisaillon
