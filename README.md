
# Text Mining and NLP APIs

RxNLP's Text Mining and NLP APIs provide access to some basic and advanced text analytics functionality over the cloud. The APIs are meant for both commercial as well as research use. We currently have a mix of academic and industry users. To use RxNLP's APIs and the wrappers for the APIs, you will have to register for a <b>[Mashape account](http://www.mashape.com)</b> and then subscribe to the [API plan](https://market.mashape.com/rxnlp/text-mining-and-nlp/pricing) that works for you. For limited or trial use, you should select the 'basic' plan with free per day requests. The <b>X-Mashape-Key</b> key that you see on mashape will be your API Key. Below you will find a list of our current APIs and links to documentation.




##Table of Contents
- [HTML2Text API](#html2text)
- [Topics Extraction API](#topics-extraction)
- [Text Similarity API](#text-similarity)
- [Sentence Clustering API](#sentence-clustering)
- [N-Gram and Word Counting API](#n-gram-and-word-counting)
- [Opinosis Review Summarization](#opinosis-summarization)
- [Finding your X-Mashape Key](#finding-the-x-mashape-key)


##HTML2Text

The [HTML2Text](https://market.mashape.com/rxnlp/text-mining-and-nlp#1-html2text) endpoint extracts only the body text of any HTML page or extracts the body text directly from a URL.
- [ [HTML2Text Documentation](http://www.rxnlp.com/api-reference/html2text-api/) ]
- [ [Test on Mashape] (https://market.mashape.com/rxnlp/text-mining-and-nlp/) ]

<hr />

##Topics Extraction

The [Topics Extraction](https://market.mashape.com/rxnlp/text-mining-and-nlp#extract-topics-themes) endpoint helps you find key topics when you have lots of text to deal with. It returns topics ranked by importance and also provides snippets containing the topics. 
- [ [Topics Extraction Documentation](http://www.rxnlp.com/api-reference/topics-and-themes-api-reference/) ]
- [ [Test on Mashape] (https://market.mashape.com/rxnlp/text-mining-and-nlp/) ]
 
<hr />

##N-Gram and Word Counting

The [N-Gram and Word Counting](https://market.mashape.com/rxnlp/text-mining-and-nlp/#3-ngramcounter) endpoint generates word and n-gram counts in any language. The words or n-grams and its frequency are returned in descending order of frequency. 

- [ [N-Gram Counter API Documentation](http://www.rxnlp.com/api-reference/n-gram-and-word-counter-api-reference/) ]
- [ [Test on Mashape](https://market.mashape.com/rxnlp/text-mining-and-nlp/) ]

<hr />
##Text Similarity 
The [Text Similarity](https://market.mashape.com/rxnlp/text-mining-and-nlp/#2-textsimilarity) endpoint computes similarity between two pieces of texts (long or short) using well known measures such as Jaccard, Dice and Cosine. 

- [ [Text Similarity API Documentation](http://www.rxnlp.com/api-reference/text-similarity-api-reference/) ]
- [ [Simple Java Wrapper for Text Similarity](https://github.com/RxNLP/text-mining-and-nlp/tree/master/java) ]
- [ [Test on Mashape](https://market.mashape.com/rxnlp/text-mining-and-nlp/) ]

<hr />
##Sentence Clustering 

The [Sentence Clustering](https://market.mashape.com/rxnlp/text-mining-and-nlp/#cluster-chunk-of-text) endpoint clusters texts such as Tweets, Customer Support Tickets, News Articles, Surveys, User Reviews and others into logical sentence groups. You get the clusters, cluster score and cluster labels. 

- [ [Sentence Clustering API Documentation](http://www.rxnlp.com/api-reference/cluster-sentences-api-reference/) ]
- [ [Test on Mashape](https://market.mashape.com/rxnlp/text-mining-and-nlp/) ]

<hr />

##Opinosis Summarization

The [Opinosis Summarization](https://market.mashape.com/rxnlp/textual-opinion-summarizer) endpoint generates short summaries of opinions and is designed to work for texts such as user reviews.  
- [ [Test on Mashape](https://market.mashape.com/rxnlp/textual-opinion-summarizer) ]
- [ [Sample Wrapper Code in Java](https://github.com/Flutifioc/Automatic-Summarization/blob/ad42d7838c3c7dd6bb2b8e547c18ad13d717cf9f/Automatic_Summarization_Maven/src/main/java/AbstractionSummarizer/AbstractionSummarizer.java) ]
- [ [Sample Code Utilizing Opinosis Summarization API in Python](https://github.com/suhashm/Meta-Crawler/blob/7c265b9b5ec50c1b8c73a9ccf1cdc403067b2436/Backend/SentimentAnalysis.py) ]
- [ [Related Paper](https://www.aclweb.org/anthology/C/C10/C10-1039.pdf) ]

<hr />


#Finding the X-Mashape Key

![Where to find your X-Mashape-Key](http://www.rxnlp.com/wp-content/uploads/2016/02/X-Mashape-Key.png "Where to find your X-Mashape-Key")

