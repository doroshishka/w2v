# Word2Vec
## Word to Vector initial code
```
import numpy
import nltk
from nltk.tokenize import word_tokenize
import gensim
from gensim.models import word2vec
import re
import string
import preprocessor as p

coding = "utf-8"
data_path=./Users/Larisa/OneDrive/Documents/University of Wisconsin-Madison/SMAD/Russian sockpuppet project/Tweets.txt

data = []
with open(data_path) as f:
     for line in f:
	data.append(line.strip())
     
import pdb
pdb.set_trace()
```
