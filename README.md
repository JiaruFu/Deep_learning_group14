# Deep_learning_group14
Using deep learning model (CNN...) to fit data 


Text transformation needs to download spaCy’s models
https://spacy.io/usage/models

python -m spacy download en_core_web_sm
import spacy
nlp = spacy.load("en_core_web_sm")


Before run the code, you should download the 'GoogleNews-vectors-negative300.bin' from https://drive.google.com/uc?id=0B7XkCwpI5KDYNlNUTTlSS21pQmM&export=download to the same path  with that of code (if it does not work, see the way below (!)). Maybe you should add the following code and run it before run the Jupyter Notebook code: 

import nltk 
nltk.download('punkt') 
nltk.download('stopwords')

pre_trained model download: (!)
https://github.com/eyaler/word2vec-slim/blob/master/GoogleNews-vectors-negative300-SLIM.bin.gz
if the above not working, try:
https://s3.amazonaws.com/dl4j-distribution/GoogleNews-vectors-negative300.bin.gz
and then unzip this file; put it in the same directory as the cnn file. 
May need to change the path inside the file based on where you put it.
