# Explainability of Transformer Models

## 🏆 Best Paper Award — CSET'26
Fine-tuned UrduBERT achieving **79.8% F1-score** with hybrid 
explainability pipeline (SHAP + Attention Rollout).

## Models Used
- UrduBERT — Urdu sentiment classification
- BERT Base — baseline comparison  
- SBERT + MBERT — multilingual experiments

## Results
| Model    | F1-Score | Accuracy |
|----------|----------|----------|
| UrduBERT | 79.8%    | 81.2%    |
| BERT Base| 71.3%    | 73.1%    |
| MBERT    | 68.9%    | 70.4%    |

## Setup
pip install -r requirements.txt

## Run API
uvicorn main:app --reload
