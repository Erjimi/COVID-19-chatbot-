# COVID-19-chatbot-
The idea of this project is to use NLP to create a search chatbot that gives answers to the user by bringing the corona virus.
we created our chatbot using the Python's NLTK(Natural Language Toolkit) library.


# Pre-requisites

# NLP
The field of study that focuses on the interactions between human language and computers is called Natural Language Processing, or NLP for short. It sits at the intersection of computer science, artificial intelligence, and computational linguistics[Wikipedia].NLP is a way for computers to analyze, understand, and derive meaning from human language in a smart and useful way. By utilizing NLP, developers can organize and structure knowledge to perform tasks such as automatic summarization, translation, named entity recognition, relationship extraction, sentiment analysis, speech recognition, and topic segmentation.
  
# NLTK: A Brief Intro
NLTK(Natural Language Toolkit) is a leading platform for building Python programs to work with human language data. It provides easy-to-use interfaces to over 50 corpora and lexical resources such as WordNet, along with a suite of text processing libraries for classification, tokenization, stemming, tagging, parsing, and semantic reasoning, wrappers for industrial-strength NLP libraries.

NLTK has been called “a wonderful tool for teaching and working in, computational linguistics using Python,” and “an amazing library to play with natural language.”
Natural Language Processing with Python provides a practical introduction to programming for language processing. I highly recommend this book to people beginning in NLP with Python.

# Downloading and installing NLTK

   1 Install NLTK: run pip install nltk
   2 Test installation: run python then type import nltk

# Text Pre- Processing with NLTK
The main issue with text data is that it is all in text format (strings). However, Machine learning algorithms need some sort of numerical feature vector in order to perform the task. So before we start with any NLP project we need to pre-process it to make it ideal for work. Basic text pre-processing includes:

  Converting the entire text into uppercase or lowercase, so that the algorithm does not treat the same words in different cases as different
 
  Tokenization: Tokenization is just the term used to describe the process of converting the normal text strings into a list of tokens i.e words that we actually want.            Sentence tokenizer can be used to find the list of sentences and Word tokenizer can be used to find the list of words in strings.
  
     The NLTK data package includes a pre-trained Punkt tokenizer for English.
     
  .Removing Noise i.e everything that isn’t in a standard number or letter.
  .Removing Stop words. Sometimes, some extremely common words which would appear to be of little value in helping select documents matching a user need are excluded from the     vocabulary entirely. These words are called stop words
  .Lemmatization: A slight variant of stemming is lemmatization. The major difference between these is, that, stemming can often create non-existent words, whereas lemmas are     actual words. So, your root stem, meaning the word you end up with, is not something you can just look up in a dictionary, but you can look up a lemma. Examples of            Lemmatization are that “run” is a base form for words like “running” or “ran” or that the word “better” and “good” are in the same lemma so they are considered the same.
  
  
# TF-IDF Approach

A problem with the Bag of Words approach is that highly frequent words start to dominate in the document (e.g. larger score), but may not contain as much “informational content”. Also, it will give more weight to longer documents than shorter documents.







