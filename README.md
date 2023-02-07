# Unsupervised Text Classification

## About the data

The data is the Youtube comments from various news channels on the issue of Russia Ukraine war which are scraped using Selenium. 

## Data cleaning 

The next step that has been carried out is text preprocessing. Following steps have been carried out:-
1. Extracting usernames from the comments
2. Carrying out the initial cleaning using regex. We have removed the duration as well as days, weeks, or months in which the comment has been made. Then we have corrected the quotation marks as well as unncessary commas and other punctuations
3. Creation of stopwords list that we needed apart from the already present list, and removing the words that gave negative connotation from the stopword list
4. Removing punctuations
5. Removing all the numerics and floating point numbers
6. Removing stopwords and performing lemmatization
7. Keeping only those comments that are more than one word 
8. Removing non English comments
9. Developing a word cloud
