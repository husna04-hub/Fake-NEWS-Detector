# 📰 Fake News Detector — ML + NLP + Transformers

## Overview
End-to-end fake news detection system comparing three 
approaches from classical ML to state-of-the-art Transformers.

## Results
| Model                    | Accuracy |
|--------------------------|----------|
| TF-IDF + Logistic Reg.   | 98.52%   |
| DistilBERT (fine-tuned)  | XX.XX%   |

## Key Findings
- Discovered and fixed data leakage (Reuters dateline bias)
- TF-IDF learned journalistic vs sensational language patterns
- DistilBERT handles short/ambiguous headlines better

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
