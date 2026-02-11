Project Intro/Objective
The purpose of this project is to build an AI-powered system to be do classification problems ranging from detecting sarcasm, predicting E-Commerce reviews, and a simple movie recommender system with basic NLP techniques. 

Methods Used
Deep Learning
NLP
Word2Vec
RNN-LSTM
Technologies
Python
Pandas, google colab
The dataset
News Headlines dataset for Sarcasm Detection is collected from two news websites.

TheOnion: sarcastic versions of current events.
HuffPost: real (and non-sarcastic) news headlines.
Each record consists of three attributes: is_sarcastic: 1 if the record is sarcastic otherwise 0 headline: the headline of the news article article_link: link to the original news article. Useful in collecting supplementary data

FastText Embeddings
An extention of Word2Vec algorithm. FastText embeddings exploit subword information to construct word embeddings. Representations are learnt of character -grams, and words represented as the sum of the -gram vectors. This extends the word2vec type models with subword information. This helps the embeddings understand suffixes and prefixes. Once a word is represented using character -grams, a skipgram model is trained to learn the embeddings.

Source: https://paperswithcode.com/method/fasttext

BERT and DistilBERT
A small, fast, cheap and light Transformer model based on the BERT architecture. The BERT transformer is a based deep learning technique for natural language processing (NLP) pre-training developed by Google on the entire Wikipedia dataset. BERT stands for Bidirectional Encoder Representations from Transformers.

source: https://arxiv.org/abs/1910.01108 https://arxiv.org/pdf/1810.04805.pdf
