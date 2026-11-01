# SMS Smishing Detection with Machine Learning

Capstone project – MBA in Artificial Intelligence & Big Data, University of São Paulo (ICMC-USP), 2024.
Advisor: Prof. Diego Furtado Silva.

## Problem
Fraudulent SMS (smishing) uses malicious links to steal data and money. The goal: a high-precision,
low-cost filter that blocks fraudulent messages before delivery.

## Approach
- Dataset: 1 million real, anonymized SMS messages (raw data not included in this repository)
- 50 features engineered from URLs, compared with feature extraction by an LLM agent (ChatGPT)
- 15 models benchmarked: Random Forest, XGBoost, LightGBM, Extra Trees, SVM, KNN, MLP, LSTM, Stacking and others

## Results
| Model | Accuracy | F1 Score | AUC-ROC |
|---|---|---|---|
| Random Forest | 94.6% | 0.946 | 0.988 |
| Stacking | 94.5% | 0.945 | 0.990 |
| XGBoost | 94.5% | 0.945 | 0.989 |
| LSTM | 91.0% | 0.910 | 0.991 |

## Stack
Python · pandas · scikit-learn · XGBoost · LightGBM · TensorFlow/Keras · NLTK · spaCy · LLMs

## Author
Cristiano Franco – [LinkedIn](https://www.linkedin.com/in/cristianomf)
