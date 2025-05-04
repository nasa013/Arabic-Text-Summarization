# Arabic Text Summarization

This project implements an Arabic text summarization system using the AraT5 model with enhanced preprocessing and evaluation metrics.

## Features

- Arabic text preprocessing and normalization
- Text summarization using AraT5 model
- TF-IDF based similarity metrics
- ROUGE evaluation metrics
- Custom Arabic text tokenization

- **Modern PyQt5 GUI for Arabic summarization**
  - True right-to-left (RTL) support for Arabic
  - Paste or type Arabic text directly
  - Upload `.txt` files (UTF-16 LE supported)
  - Generate and view summaries in RTL



## Model Details

- Base Model: UBC-NLP/AraT5v2-base-1024
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

## GUI Usage

### Requirements
- Python 3.7+
- PyQt5

Install PyQt5:
```bash
pip install PyQt5
```

### Running the GUI
```bash
python gui.py
```

### GUI Features
- Enter or paste Arabic text (RTL)
- Upload `.txt` files (UTF-16 LE encoding supported)
- Click "شعبلي الدنيا" to view the summary in RTL
- Modern, user-friendly interface with Comic Sans MS font and gray/blue palette
 

## Directory Structure

- `data/`: Contains dataset files (not included here due to size, >900MB with tf-idf features)
- `models/`: Stores trained models
- `output/`: Training logs and outputs
