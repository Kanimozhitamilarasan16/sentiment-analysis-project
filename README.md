PROJECT TITLE:
 Drug Review Sentiment Analysis using Logistic Regression

OBJECTIVE:
 To build a machine learning model that automatically classifies drug reviews into positive or negative sentiment based on textual content.

DATSET:
 Source: Kaggle Drug Review Dataset
  Contains:
   review → patient feedback (text)
   rating → score (1–10)
   drugName, condition, etc.

TECHNOLOGIES USED:
->Python
->Pandas, NumPy
->Scikit-learn
->Matplotlib, Seaborn
->NLP (TF-IDF Vectorization)

WORKFLOW:
1.Data Loading
 Import dataset using Pandas
2.Data Preprocessing
 Convert text to lowercase
 Remove punctuation and noise
3.Create sentiment labels from ratings
4.Feature Extraction
5.Convert text into numerical form using TF-IDF
6.Model Training
 Train Logistic Regression with class balancing
7.Model Evaluation
 Accuracy score
 Confusion matrix
 Precision, Recall, F1-score
8.Prediction
 Predict sentiment for:
  Sample reviews
  User input (real-time)
MODEL PERFORMANCE:
 Accuracy: ~85%
 Performs well on positive reviews
 Balanced model improves detection of negative reviews
 
FEATURES:
 Text preprocessing using regex
 TF-IDF vectorization
 Logistic Regression classifier
 Confusion matrix visualization
 Real-time sentiment prediction
 Probability-based confidence output

LIMITATIONS:
-Cannot detect sarcasm
-Some mismatch between rating and review (label noise)
-Limited context understanding (no deep learning)

FUTURE IMPROVEMENTS:
->Use BERT / Deep Learning models
->Add lemmatization & stopword removal
->Improve handling of conflicting labels
->Build a web app interface

HOW TO RUN?
*Upload dataset to Google Colab
*Run all cells step-by-step
*Enter your own review when prompted
*View predicted sentiment and probability

EXAMPLE OUTPUT:
Review: This medicine worked perfectly, no side effects.
Predicted Sentiment: Positive
Probability of Positive: 0.91

CONCLUSION:
This project demonstrates how NLP and machine learning can be applied to analyze healthcare data efficiently. It provides a scalable solution to extract insights from patient reviews and supports better decision-making.

This project demonstrates how NLP and machine learning can be applied to analyze healthcare data efficiently. It provides a scalable solution to extract insights from patient reviews and supports better decision-making.
