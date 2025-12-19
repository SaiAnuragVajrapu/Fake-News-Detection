# Fake News Detection using Machine Learning

This project focuses on detecting fake news articles using Natural Language Processing (NLP) and Machine Learning techniques. The model classifies news as **Fake** or **Real** based on the textual content.



## Project Overview

Fake news has become a major challenge in the digital era. This project applies text preprocessing, feature extraction, and supervised machine learning algorithms to automatically identify fake news.

The complete implementation is provided with:
- Data loading
- Text cleaning
- Feature extraction
- Model training
- Model evaluation



## Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **NLTK**
- **Scikit-learn**



## Workflow

1. **Data Loading**
   - Load the fake news dataset (CSV format)

2. **Text Preprocessing**
   - Lowercasing
   - Removing punctuation and stopwords
   - Tokenization
   - Stemming / Lemmatization

3. **Feature Extraction**
   - TF-IDF Vectorization

4. **Model Training**
   - Machine Learning classifier (Logistic Regression / Naive Bayes)

5. **Model Evaluation**
   - Accuracy score
   - Confusion matrix
   - Classification report



## Model Performance

The trained model is evaluated using standard classification metrics such as:
- Accuracy
- Precision
- Recall
- F1-score

These metrics help measure how effectively the model distinguishes between fake and real news.



##  How to Run the Project

1. Clone the repository:
```bash

   git clone https://github.com/your-username/fake-news-detection.git
   
```

2.Navigate to the project directory:
 ```bash

   cd fake-news-detection

 ```

3.Open the notebook:
 ```bash

  jupyter notebook fake-news-detection-project.ipynb

 ```


4.Run all cells sequentially.

## Future Enhancements

-Use deep learning models (LSTM / BERT)

-Deploy the model as a web application

-Add real-time news input support

-Improve accuracy with larger datasets


