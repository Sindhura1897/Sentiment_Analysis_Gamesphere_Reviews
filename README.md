# Sentiment Analysis on Gamesphere Reviews

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![NLTK](https://img.shields.io/badge/NLTK-✔-green)
![Transformers](https://img.shields.io/badge/Transformers-✔-orange)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-✔-blue)

## Overview
This project performs sentiment analysis on text data to classify opinions as **positive, negative, or neutral**.

## Tools Used
- **Python**
- **NLTK**
- **Scikit-Learn**
- **Transformers (Hugging Face)**
- **Pandas**
- **Matplotlib**
- **Seaborn**

## Approach
1. **Data Preprocessing:**  
   - Removed HTML tags, special characters, and URLs from text.  
   - Tokenized sentences and removed stopwords.  
   - Applied **WordNet Lemmatization** to standardize words.

2. **Feature Extraction:**  
   - Used **TF-IDF** and **CountVectorizer** for traditional ML models.  
   - Applied **Pretrained Transformers (BERT, DistilBERT)** for deep learning models.

3. **Model Training:**  
   - Implemented **Logistic Regression, SVM, Random Forest** for baseline models.  
   - Fine-tuned **BERT-based transformers** for improved accuracy.  

4. **Evaluation & Performance Metrics:**  
   - Compared different models using **accuracy, precision, recall, and F1-score**.  
   - Visualized results using confusion matrices and sentiment distributions.  

## Results
- Achieved **90% accuracy** using fine-tuned Transformer-based models.  
- Traditional ML models performed well but were outperformed by deep learning.  
