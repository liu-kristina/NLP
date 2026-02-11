# NLP & Deep Learning Classification Project

## 📖 Project Overview

The purpose of this project is to build an AI-powered system capable of solving multiple classification problems, including:

- Sarcasm detection  
- E-commerce review sentiment prediction  
- A simple movie recommender system  

The project explores both traditional NLP techniques and modern deep learning approaches to compare performance and effectiveness.

---

## Methods Used

- Deep Learning  
- Natural Language Processing (NLP)  
- Word2Vec  
- LSTM  
- Transformer-based models (BERT)  

---

## Technologies

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- TensorFlow / Keras  
- Hugging Face Transformers  
- Gensim  

---

# Models & Techniques

## Word2Vec

Word2Vec is an algorithm developed by Google that converts words into dense vector representations. It maps semantically similar words close together in vector space by learning from contextual information.

### Applications
- Document retrieval  
- Machine translation  
- Autocompletion and prediction  
- Semantic similarity tasks  

In this project, a Word2Vec model was trained using the **Gensim** library.

**Source:**  
https://www.askpython.com/python-modules/gensim-word2vec

---

## FastText Embeddings

FastText is an extension of the Word2Vec algorithm. It incorporates subword information by representing words as collections of character n-grams.

Instead of treating words as atomic units, FastText:
- Learns embeddings for character n-grams  
- Represents each word as the sum of its n-gram vectors  
- Better captures prefixes and suffixes  
- Improves performance on rare or morphologically complex words  

A skip-gram model is then trained to learn the embeddings.

**Source:**  
https://paperswithcode.com/method/fasttext

---

## BERT

BERT (Bidirectional Encoder Representations from Transformers) is a transformer-based deep learning model for NLP pre-training developed by Google and trained on large corpora such as Wikipedia.

Key characteristics:
- Bidirectional contextual understanding  
- Pre-trained on large text datasets  
- Fine-tunable for downstream tasks  

DistilBERT is a smaller, faster, and more efficient version of BERT that retains most of its performance while reducing computational cost.

**Sources:**  
- https://arxiv.org/abs/1810.04805  
- https://arxiv.org/abs/1910.01108  

---

# Project Objectives

- Compare classical NLP methods with deep learning and transformer-based approaches  
- Evaluate model performance across multiple classification tasks  
- Analyze trade-offs between model complexity and efficiency  
- Build a reusable NLP classification framework  


