# AliExpress Sentiment Analysis

This project conducts sentiment analysis on reviews from AliExpress and other shopping platforms using natural language processing (NLP) and machine learning techniques. It focuses on text preprocessing, data visualization, and building a deep learning model to classify customer reviews as positive or negative or neutral.

## Key Steps

### 1. **Libraries Used**
- **Data Manipulation:** `pandas`, `numpy`
- **Visualization:** `matplotlib`, `seaborn`
- **Text Processing:** `nltk`, `gensim`
- **Modeling:** TensorFlow/Keras
- **Oversampling:** `imblearn`

### 2. **Data Preprocessing**
- **Cleaning:** Removal of HTML tags, punctuation, and special characters.
- **Tokenization:** Converting reviews into word tokens.
- **Stopword Removal:** Using NLTK's predefined stopwords.
- **Lemmatization:** Reducing words to their base form for consistency.
- **Padding:** Ensures uniform input lengths for neural network models.

### 3. **Model Building**
- **Architecture:** 
  - Embedding Layer: Word2Vec embeddings for contextual representation.
  - Bidirectional GRU: Captures sequential dependencies in both directions.
  - Dense Layers: Fully connected layers for classification.

### 4. **Evaluation**
- Metrics like accuracy and loss.

[Kaggle Notebook](https://www.kaggle.com/code/hamoi9/aliexpress-sentiment-analysis)
