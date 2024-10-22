If the predictions are not correct try adding more data in the csv file.


I have given 60 different statements in it with all three parameters equally divided, i.e., Positive, Negative and Nuetral.


This is the most primitive way of training the AI so bugs are expected and prediction might be wrong sometimes.


[import pandas as pd
import re
from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import classification_report
from imblearn.over_sampling import SMOTE
from nltk.corpus import stopwords
from nltk.tokenize import word_tokenize
import nltk]


Install and Import the following libraries for the best output.
