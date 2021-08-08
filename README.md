This GitHub repository contains an exploration of text processing and analysis using Python. 

The file WordCombos.ipynb takes as input raw text and identifies the most common words and most common pair of consecutive words, and sorts them in increasing order. It also finds the frequency of a given set of words in multiple texts. This is illustrated as an example with open books saved in .txt format which can be found in the Data folder. Bar charts are produced to visualize the data using the matplotlib and pandas Python libraries. 

The file LexiconSentimentAnalysis.ipynb runs sentiment analysis on given texts to show how the positivity and negativity of a piece of writing varies across the work. This is achieved using ntlk's SentimentIntensityAnalyzer package which returns the sentiment value of a given piece of text. The results are then visualized in line graphs using matplotlib, showing how the sentiment values vary over the course of the text. As an example, pieces of text from the Data folder are split by scene, with sentiment analysis run on each scene of the text. 

The file Reword.ipynb contains a program that takes as input a piece of text and rewords it by replacing a given number of words from the text with a synonym, and returning the result, while maintaining the original punctuation and capitalizations. The input can be provided as a string with the result printed as a string, or a file path can be provided, in which case the result will be written to an output file. Synonyms for words are obtained using the PyDictionary library. 

The Data folders contain the text files that are used as samples for the above programs. 
