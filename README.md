# Text-Summarizer

Text Summarization Tool Using Python

## Term Frquency - Inverse Document Frequency (tf-idf)

Tf-Idf is a numerical statistic that is intended to reflect how important a word is to a document in a collection or corpus. (Wikipedia)

* term-frequency of a word (tf) = 1 + log(frequency of word) 
* inverse-document-frequency of a word (idf) = log(Total Number of Documents in the Corpus / Number of Documents in which the word appears)

**tf-idf = tf * idf

## Sentence Scoring

* Score of a sentence = sum(tf-idf of all words in the sentence)

## Decision Condition

* Select the top 'n' sentences to represent the summary of the document. 
* In the given project, n = 50% of total number of sentences 


Dataset used: Reuters-21578, Distribution 1.0
