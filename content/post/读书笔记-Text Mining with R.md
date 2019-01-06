---
title: "读书笔记-A PRIMER ON PARTIAL LEAST SQUARES STRUCTURAL EQUATION MODELING (PLS-SEM)"
date: 2019-01-01T15:43:48+08:00
lastmod: 2019-01-03T15:43:48+08:00
draft: false
tags: 
categories: 
author: "Lin"

# You can also close(false) or open(true) something for this content.
# P.S. comment can only be closed
# comment: false
toc: true
autoCollapseToc: true
# You can also define another contentCopyright. e.g. contentCopyright: "This is another copyright."
contentCopyright: '<a href="https://github.com/gohugoio/hugoBasicExample" rel="noopener" target="_blank">See origin</a>'
# reward: false
# mathjax: false
---

1. # The Tidy Text Format   

  Contrasting Tidy Text with Other Data Structures  
  The unnest_tokens Function  
  Tidying the Works of Jane Austen  
  The gutenbergr Package  
  Word Frequencies  
  Summary  
2. # Sentiment Analysis with Tidy Data                                          

  The sentiments Dataset  
  Sentiment Analysis with Inner Join  
  Comparing the Three Sentiment Dictionaries  
  Most Common Positive and Negative Words  
  Wordclouds  
  Looking at Units Beyond Just Words  
  Summary  
3. # Analyzing Word and Document Frequency: tf-idf                              

  Term Frequency in Jane Austen’s Novels  
  Zipf ’s Law  
  The bind_tf_idf Function  
  A Corpus of Physics Texts  
  Summary  
4. # Relationships Between Words: N-grams and Correlations                      

  Tokenizing by N-gram  
  ContentsCounting and Filtering N-grams  
  Analyzing Bigrams  
  Using Bigrams to Provide Context in Sentiment Analysis  
  Visualizing a Network of Bigrams with ggraph  
  Visualizing Bigrams in Other Texts  
  Counting and Correlating Pairs of Words with the widyr Package  
  Counting and Correlating Among Sections  
  Examining Pairwise Correlation  
  Summary  
5. # Converting to and from Nontidy Formats                                    

  Tidying a Document-Term Matrix  
  Tidying DocumentTermMatrix Objects  
  Tidying dfm Objects  
  Casting Tidy Text Data into a Matrix  
  Tidying Corpus Objects with Metadata  
  Example: Mining Financial Articles  
  Summary  
6. # Topic Modeling       

  Latent Dirichlet Allocation  
  Word-Topic Probabilities  
  Document-Topic Probabilities  
  Example: The Great Library Heist  
  LDA on Chapters  
  Per-Document Classification  
  By-Word Assignments: augment  
  Alternative LDA Implementations  
  Summary  
7. # Case Study: Comparing Twitter Archives                                    

  Getting the Data and Distribution of Tweets  
  Word Frequencies  
  Comparing Word Usage  
  Changes in Word Use  
  Favorites and Retweets  
  Summary  
8. # Case Study: Mining NASA Metadata                                        

  How Data Is Organized at NASA  
  Wrangling and Tidying the Data  
  Some Initial Simple Exploration 129Word Co-ocurrences and Correlations  
  Networks of Description and Title Words  
  Networks of Keywords  
  Calculating tf-idf for the Description Fields  
  What Is tf-idf for the Description Field Words?  
  Connecting Description Fields to Keywords  
  Topic Modeling  
  Casting to a Document-Term Matrix  
  Ready for Topic Modeling  
  Interpreting the Topic Model  
  Connecting Topic Modeling with Keywords  
  Summary  
9. # Case Study: Analyzing Usenet Text                                         

  Preprocessing  
  Preprocessing Text  
  Words in Newsgroups  
  Finding tf-idf Within Newsgroups  
  Topic Modeling  
  Sentiment Analysis  
  Sentiment Analysis by Word  
  Sentiment Analysis by Message  
  N-gram Analysis  
  Summary  