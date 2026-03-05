# English to Hindi Neural Machine Translation using RNN with Attention

## Project Overview

This project implements a Neural Machine Translation (NMT) system that
translates English sentences into Hindi using a deep learning model.

The system is built using an Encoder–Decoder architecture with an
Attention mechanism implemented in PyTorch. The model learns contextual
relationships between words in two languages to generate meaningful
translations.

The project demonstrates how sequence-to-sequence deep learning models
can be applied to natural language processing tasks.

---

## Objectives

The primary objectives of this project are:

- Build a neural machine translation system using deep learning
- Implement an encoder-decoder architecture for sequence translationM
- Apply attention mechanisms to improve translation quality
- Train the model using bilingual parallel sentence datasets
- Evaluate translation quality using BLEU score

---

## Dataset

The model was trained using an English-Hindi parallel dataset consisting
of sentence pairs.

Each entry in the dataset contains:

English Sentence → Hindi Translation

# Example 

Hello → नमस्ते  

How are you → आप कैसे हैं


## Model Architecture

The model uses a sequence-to-sequence architecture consisting of:

### Encoder
Processes the English sentence and converts it into a hidden vector
representation.

### Decoder
Generates the Hindi translation word-by-word using the encoded context.

### Attention Mechanism
Allows the model to focus on important words in the source sentence
during translation.

---

## Machine Learning Pipeline

The project follows these steps:

1. Text preprocessing
2. Tokenization
3. Vocabulary creation
4. Sequence padding
5. Encoder-decoder model training
6. Teacher forcing during training
7. Model evaluation using BLEU score

---

## Technologies Used

- Python
- PyTorch
- NumPy
- Natural Language Processing (NLP)
- Jupyter Notebook

---

## Results

The trained model demonstrates the ability to generate context-aware
Hindi translations from English sentences using neural sequence models.

Although simple compared to large transformer-based models, this project
illustrates the fundamental concepts behind neural machine translation.


---

## Future Improvements

Possible improvements include:

- Implementing Transformer models
- Training on larger datasets
- Using pretrained language embeddings
- Deploying the model as an API or web application

---

## Author

Mohammed Ashrar Shaikh  
Data Analytics & Machine Learning Enthusiast  
Mississauga, Ontario, Canada  

LinkedIn: https://linkedin.com/in/asrarshaikh1509
---

