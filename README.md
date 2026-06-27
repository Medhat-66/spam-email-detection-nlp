# Spam Email Detection — NLP Classification

Classifying emails as spam or ham using NLP techniques and ML models.

## Results

| Model | BOW | TF-IDF | Word2Vec |
|---|---|---|---|
| Logistic Regression | 98.07% | 98.16% | 94.30% |
| Naive Bayes | 96.04% | 95.56% | — |
| SVM | 97.00% | 98.36% | 95.07% |
| Neural Network | — | 98.36% | — |

## Dataset
- Spam Mails Dataset (Enron-1) — Kaggle
- 5,171 emails — 71% ham, 29% spam

## Techniques Used
- **Text Preprocessing:** Lowercasing, Regex Cleaning, Stopword Removal, Porter Stemming
- **Text Representation:** BOW, TF-IDF, Word2Vec (100-dim embeddings)
- **ML Models:** Logistic Regression, Naive Bayes, SVM
- **Deep Learning:** Keras Neural Network (Dense 256→128→1 with Dropout)

## Libraries
Python, NLTK, Gensim, Scikit-learn, TensorFlow/Keras, Pandas, Matplotlib
