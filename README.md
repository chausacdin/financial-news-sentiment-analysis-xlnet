# Financial News Sentiment Analysis using XLNet

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
