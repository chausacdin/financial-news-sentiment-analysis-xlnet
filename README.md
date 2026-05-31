# Financial News Sentiment Analysis using XLNet
![Python](https://img.shields.io/badge/Python-3.13-blue?style=for-the-badge&logo=python)
![XLNet](https://img.shields.io/badge/XLNet-Transformer-purple?style=for-the-badge)
![HuggingFace](https://img.shields.io/badge/Hugging%20Face-Transformers-yellow?style=for-the-badge&logo=huggingface)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red?style=for-the-badge&logo=pytorch)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-f7931e?style=for-the-badge&logo=scikitlearn)
![Accuracy](https://img.shields.io/badge/Accuracy-96.9%25-brightgreen?style=for-the-badge)
![Dataset](https://img.shields.io/badge/Dataset-Financial%20PhraseBank-success?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

## Description
This project fine-tunes XLNet on the Financial PhraseBank dataset to classify financial news headlines into:
- Positive
- Neutral
- Negative
The model is evaluated on unseen financial news and then applied to thousands of real-world headlines for sentiment analysis.

## Technologies
- Python
- XLNet
- Hugging Face Transformers
- PyTorch
- Pandas
- Matplotlib
- Scikit-learn

## Dataset
Financial PhraseBank
The dataset contains financial news sentences manually labeled by financial experts.

Classes:
- Negative
- Neutral
- Positive

## Model
Base Model:
xlnet-base-cased

Task:
Financial Sentiment Classification

Output Classes:
3

## Results

| Metric | Score |
|----------|----------|
| Accuracy | 96.9% |
| Precision | 97% |
| Recall | 97% |
| F1 Score | 96% |

## Example Predictions

Headline:
"Nvidia reports record quarterly earnings"

Prediction:
Positive (98%)

Headline:
"Tesla shares fall after weak delivery numbers"

Prediction:
Negative (96%)

Headline:
"Federal Reserve keeps interest rates unchanged"

Prediction:
Neutral (95%)
