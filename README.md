# Spam-classification

There are five programs: tokenize, porterStemmer, euclid_vector, log_classifier, test, 
classify_new_email, and 

Tokenize and porterStemmer were taken from public files, tokenize is used to tokenize
paragraphs and porterStemmer is for stemming words. The author and credit for the 
porterStemmmer code is given in the file. Same for tokenize. 

The first file to run is euclid_vector. It first finds the bag of words of the entire 
training set, and then creates a euclidean vector representation for all of the files.
This step takes about 77 seconds to find the bag of words, and then about 21 minutes to 
find the entire bag of words.

Next, the second file is log_classifier. This is the logistic classifer function. It uses
gradient descent to find the optimal weights.

The final file, classify_new_email, classifies new emails. You just have to input the 
name of the file into the function. 

