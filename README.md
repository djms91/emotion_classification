#  Emotion & Sentiment Classification using NLP

##  Project Overview
This project focuses on classifying text into emotions using Machine Learning techniques. 
It predicts whether a sentence is **positive, negative, or neutral**, and also analyzes emotional patterns in text data.



##  Dataset
The dataset is manually created and contains labeled sentences with:
- Sentiment labels: Positive, Negative, Neutral  
- Emotion type labels: anger, sadness, etc. (explicit and implicit expressions)



##  Methodology

- Data Preprocessing (cleaning, label normalization)
- TF-IDF Vectorization for feature extraction
- Logistic Regression model for classification
- Handling class imbalance using `class_weight='balanced'`
- Train-test split (80-20)



## Model Used
- Logistic Regression (Scikit-learn)



##  Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-score  



##  Results
The model achieves moderate accuracy and performs well on clear sentiment expressions.
However, it struggles with implicit and unseen expressions due to limited dataset size and TF-IDF limitations.

---

##  Prediction Example
Example predictions:

- "I feel very happy today" → Positive  
- "I hate when people ignore me" → Negative  
- "I have a meeting tomorrow" → Neutral  



##  Limitations
- Limited dataset size  
- Difficulty handling sarcasm and implicit emotions  
- TF-IDF does not capture context  



##  Future Improvements
- Use Transformer models (BERT, RoBERTa)  
- Increase dataset size  
- Improve handling of sarcasm and context-based emotions  



## Project Link
https://github.com/djms91/emotion_classification



##  Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Jupyter Notebook  



##  Author
Divya jha
