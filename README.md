# 🔔:RealVsSpam
  
An NLP model that classifies between a real or spam message
 
:dizzy:Real vs Spam Message Classifier using NLP :
 
This is a machine learning project that aims to classify text messages as either "real" or "spam". The project uses Natural Language Processing (NLP) techniques to extract features from the text messages, and trains a machine learning model on a labeled dataset to predict whether a given text message is "real" or "spam".

:dizzy:Dataset:   
 
The dataset used in this project is a collection of text messages, both real and spam, obtained from various sources. The dataset contains a total of 5,000 messages, of which 2,500 are labeled as "real" and 2,500 as "spam". The dataset is split into training and testing sets, with 80% of the data used for training the model and 20% used for testing the model.

:dizzy:Preprocessing:

The text messages are preprocessed to remove stop words, punctuation, and convert all text to lowercase. The text is then tokenized and a bag-of-words representation is used to create a document-term matrix, where each row represents a text message and each column represents a unique word in the corpus.

:dizzy:Feature Extraction:

The document-term matrix is used to extract features from the text messages using NLP techniques such as Term Frequency-Inverse Document Frequency (TF-IDF) and word embeddings. These features are used as input to train the machine learning model.

:dizzy:Model Training:

The machine learning model used in this project is a Naive Bayes classifier, which is trained on the labeled dataset to predict whether a given text message is "real" or "spam". The model is evaluated on the testing set to measure its accuracy and performance.

:dizzy:Conclusion:

The Real vs Spam Message Classifier using NLP is an effective machine learning model for classifying text messages as either "real" or "spam". The project demonstrates the importance of NLP techniques for feature extraction and classification of text data, and can be extended to other applications such as sentiment analysis and topic modeling.
