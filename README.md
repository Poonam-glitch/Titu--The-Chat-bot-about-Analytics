# Titu -The-Chat-bot-about-Analytics
A basic chatterbox Titu who talks about Analytics.

### ""Natural language processing is the way computers understand human language.”

## Basic Pipeline in Natural Language Processing

  * Tokenization - Sentence tokenize, Word tokenize
  *from nltk.tokenize import sent_tokenize, word_tokenize*
  
  * Stemming - We have not included that here, instead we used Lemmatization
  * Lemmatization 
  
  
### Bag of Words (BoW) : Document Matrix
We cannot directly feed our text to Titu ; the text must be converted into vectors of numbers.
The bag-of-words model is method of feature extraction which preprocess the text by converting it into numeric format also known as vectors .BoW keeps count of the total occurrences of most frequently used words.
In simple terms, it’s a collection of words to represent a sentence with word count disregarding the order in which they appear.

### TF-IDF
TF-IDF stands for Term Frequency-Inverse Document Frequency
“Term frequency–inverse document frequency, is a numerical statistic that is intended to reflect how important a word is to a document in a collection or corpus.”
Term Frequency: is a scoring of the frequency of the word in the current document.
Inverse Document Frequency: is a scoring of how rare the word is across documents.

### Corpus

We have used Analytics corpus from Wikipedia. You may use any.


### How it works?

Open the notebook in browser and talk to Titu. Although he is a bit shy right now.
I am working on training him better :)
