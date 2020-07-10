# NLP
Natural Language Processing deals with human(natural) language and process and analyze large amounts of natural language data. NLP makes it possible for computers to read text, hear speech, interpret it, measure sentiment and determine which parts are important.
## Topic Modelling
In this module we will use topic modelling which is in the context of Natural Language Processing, is a type of statistical model for discovering the abstract 'topics' that occur in a collection of documents.
For topic modelling, we use the following techniques:
#### 1. Latent Dirichlet Allocation(LDA)
LDA is used to classify text in a documnent to a particular topic. It bilds a topic per documnrt model and words per topic model, modeled as Dirichlet distributions.
The following steps are carried out :
i. The number of words in the document are determined.
ii. topic mixture for the document over a fixed set of topics is chosen.
iii. A topic is selected based on the document’s multinomial distribution.
iv. Now a word is picked based on the topic’s multinomial distribution.
#### 2. Latent Semantic Analysis(LSA)
LSA also known as Latent Semantic Index(LSI) analyzes relationships between a set of documents and the terms they contain by producing a set of concepts related to the documents and terms(term-document matrix) using Bag of Words(BoW) model. LSA assumes that words that are close in meaning will occur in similar pieces of text. LSA learns latent topics by performing a matrix decomposition on the document-term matrix using Singular value decomposition.
## Sentiment Analysis
Sentiment analysis is the interpretation and classification of emotions (positive, negative and neutral) within text data using text analysis techniques. It is done using TextBlob function which return the subjectivty and polarity of each word.
