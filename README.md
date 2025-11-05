# Fake News Detection 

# Overview
A Natural Language Processing (NLP) model that detects fake news articles using textual features and machine learning techniques.

# Technologies Used
- Python
- Pandas, NumPy, Scikit-learn
- TfidfVectorizer (feature extraction)
- Logistic Regression (classification)

# Approach
1. Combined real and fake news datasets.
2. Preprocessed text by removing stopwords and punctuation.
3. Converted text into numerical features using TF-IDF.
4. Trained Logistic Regression and evaluated model accuracy.

# Results
Achieved an accuracy of ~90% on the test dataset with good precision and recall values.

# Future Work
- Test with deep learning (LSTM or BERT)
- Add live news verification via API.
