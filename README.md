# Sentiment-Analysis-Using-NLP
A Machine Learning project using Natural Language Processing (NLP) to classify customer reviews into Positive, Negative, and Neutral sentiments using CountVectorizer and Multinomial Naive Bayes.

# Sentiment Analysis of Customer Reviews Using NLP

## Project Overview

This project focuses on analyzing customer reviews using Natural Language Processing (NLP) and Machine Learning techniques.

The model classifies customer reviews into three sentiment categories:

- **Positive** – Expresses satisfaction or happiness.
- **Negative** – Expresses dissatisfaction or disappointment.
- **Neutral** – Expresses neither positive nor negative emotions.

The project demonstrates how raw text data can be processed, converted into numerical features, and used to train a machine learning classification model.

## Objectives

- Understand the fundamentals of Natural Language Processing.
- Perform text preprocessing and cleaning.
- Apply tokenization and stopword removal.
- Convert textual data into numerical features.
- Build a sentiment classification model.
- Evaluate model performance using classification metrics.
- Predict sentiments for new customer reviews.

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn

## Machine Learning Algorithm

**Multinomial Naive Bayes**

Multinomial Naive Bayes is used to classify customer reviews based on word frequency patterns.

**Feature Extraction:** CountVectorizer

CountVectorizer converts text into numerical representations by counting the frequency of words in customer reviews.

## Project Workflow

1. Import required libraries.
2. Create a customer review dataset.
3. Perform text preprocessing.
4. Convert text into lowercase.
5. Remove punctuation and stopwords.
6. Perform tokenization.
7. Visualize sentiment distribution.
8. Apply CountVectorizer for feature extraction.
9. Split the dataset into training and testing sets.
10. Train the Multinomial Naive Bayes model.
11. Evaluate model performance.
12. Predict sentiments for new customer reviews.

## Dataset Information

The project uses a manually created dataset containing 30 customer reviews.

| Sentiment | Number of Reviews |
|---|---:|
| Positive | 10 |
| Negative | 10 |
| Neutral | 10 |
| **Total** | **30** |

The dataset contains customer reviews and their corresponding sentiment labels.

## Text Preprocessing

The following preprocessing techniques are implemented:

- Lowercase Conversion
- Punctuation Removal
- Tokenization
- Stopword Removal

These techniques help prepare raw customer reviews for machine learning.

## Model Evaluation

The model is evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

These metrics help assess the classification performance of the trained model.

## Sentiment Prediction

After training, the model is tested using new customer reviews to predict whether the feedback is Positive, Negative, or Neutral.

## How to Run the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/RiswanCK/Sentiment-Analysis-Using-NLP.git
   ```

2. Open Google Colab.

3. Upload the project notebook (`.ipynb`).

4. Install the required libraries if needed:

   ```python
   !pip install nltk scikit-learn matplotlib pandas seaborn
   ```

5. Execute all notebook cells sequentially.

6. Explore the model evaluation results and sentiment predictions.

## Project Limitations

- The dataset contains only 30 reviews.
- The model is developed for educational purposes.
- Performance may vary when processing unseen customer reviews.
- More advanced NLP techniques could improve performance.

## Future Improvements

- Use a larger real-world customer review dataset.
- Implement TF-IDF feature extraction.
- Compare different machine learning algorithms.
- Experiment with advanced NLP techniques.
- Develop a user-friendly sentiment prediction web application.

## Conclusion

This project demonstrates the practical implementation of Natural Language Processing and Machine Learning for customer review classification.

By combining text preprocessing, CountVectorizer, and Multinomial Naive Bayes, the project provides a beginner-friendly approach to understanding how computers can analyze textual information and identify customer sentiment.

---

**Project Domain:** Machine Learning | Natural Language Processing (NLP)

**Developed Using:** Python
