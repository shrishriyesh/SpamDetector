# SpamDetector
Spam Detector made using Random forest Classification and Naive Bayes with NLP libraries and SciKitLearn.
Made use of data pipeline on scikitlearn to work on classification already performed once again using different method.
Tried Github license for the first time on a code.

DataSet Used- UCI Spam Message Collection dataset(https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection).

Steps Involved-

(1) Cleaning the data and creating a table to label the message as spam or ham.

(2) PreProcessing of the texts so as to remove punctuations and Stopwords using NLP libraries.

(3) Converted the messages into vectors using Bag Of Words model and form a sparse matrix using it.

(4) Then the term Frequency~Inverse Document Frequency is calculated using the above.

(5) Train test split is performed and the models are trained on this TF-IDF.

(6) Model gets tested and shows positive results for test dataset.

(7) Use of data pipeline of scikitlearn is also shown which helps us generalise our code.
