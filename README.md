# Spam Classification

This project performs Emails classification using Natural Language Processing (NLP). It includes thorough preprocessing, multiple vectorization techniques, LStm, GRU, and comparison of their impact on model performance.

___


## 🧹 Preprocessing Steps

We applied the following custom preprocessing functions:

- ✅ Remove special characters  
- ✅ Remove non-ASCII characters
- ✅ Remove punctuation  
- ✅ Convert text to lowercase    
- ✅ Replace numbers with text
- ✅ Trim whitespaces, Get Tokens  
- ✅ Remove stopwords  
- ✅ Lemmatize words and verbs

> Preprocessing code is implemented using Python, regex, and NLTK.

---

## ✍️ Text Representation Methods

We used three popular vectorization methods to represent text numerically:

- **Count Vectorizer**: Basic bag-of-words model  
- **Frequency (TF)**: Term frequency normalized  
- **TF-IDF**: Adjusts weights based on word rarity across documents
- **Embedding Layer**

## 🤖 Models Used

- ANN
- LSTM
- GRU
