# Arabic Text Summarization

This project implements an Arabic text summarization system using the AraT5 model with enhanced preprocessing and evaluation metrics.

## Features

- Arabic text preprocessing and normalization
- Text summarization using AraT5 model
- TF-IDF based similarity metrics
- ROUGE evaluation metrics
- Custom Arabic text tokenization




## Model Details

- Base Model: UBC-NLP/AraT5-base-title-generation
- Training Data: AGS-Corpus dataset
- Preprocessing: Custom Arabic text normalization
- Evaluation Metrics: ROUGE scores and TF-IDF Cosine Similarity

## Preprocessing Features

- Arabic character normalization
- Diacritics removal
- Punctuation handling
- Stop words removal
- Text cleaning


## Evaluation Metrics

1. ROUGE Scores:
   - ROUGE-1 (unigram overlap)
   - ROUGE-2 (bigram overlap)
   - ROUGE-L (longest common subsequence)

2. TF-IDF Cosine Similarity:
   - Measures semantic similarity between generated and reference summaries
   - Uses custom Arabic tokenization

## Directory Structure

- `data/`: Contains dataset files "i can't upload it since its more than 900MB with tf-idf features"
- `models/`: Stores trained models
- `output/`: Training logs and outputs

