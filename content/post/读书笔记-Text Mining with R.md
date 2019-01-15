---
title: "读书笔记-Text Mining with R"
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

tidytext

- [vignettes](https://cran.r-project.org/web/packages/tidytext/vignettes/tidytext.html)
- 

[作者博客](https://juliasilge.com/)

# 1. The Tidy Text Format   

tidy text : a table with one token per row. 

token: a meaningful unit of text, such as a word, that we are interested in using for analysis 

## Contrasting Tidy Text with Other Data Structures  

## The unnest_tokens Function  
## Tidying the Works of Jane Austen  
## The gutenbergr Package  
## Word Frequencies  
## Summary  

# 2. Sentiment Analysis with Tidy Data                                          

## The sentiments Dataset  
## Sentiment Analysis with Inner Join  
## Comparing the Three Sentiment Dictionaries  
## Most Common Positive and Negative Words  
## Wordclouds  
## Looking at Units Beyond Just Words  
## Summary  

# 3. Analyzing Word and Document Frequency: tf-idf                              

$$
i d f ( \text { term } ) = \ln \left( \frac { n _ { \text { documents } } } { n _ { \text { documents containing term } } } \right)
$$

 ## Term Frequency in Jane Austen’s Novels  

## Zipf ’s Law  
Zipf ’s law states that the frequency that a word appears is inversely proportional to its rank. 

## The bind_tf_idf Function  

## A Corpus of Physics Texts  
## Summary  

# 4. Relationships Between Words: N-grams and Correlations                      

- [ggraph](https://github.com/thomasp85/ggraph)
- [widyr](https://github.com/dgrtwo/widyr)

N-grams: tokenizes by pairs of adjacent words rather than by individual ones. 

## Tokenizing by N-gram  

## ContentsCounting and Filtering N-grams  
## Analyzing Bigrams  
## Using Bigrams to Provide Context in Sentiment Analysis  
## Visualizing a Network of Bigrams with ggraph  
## Visualizing Bigrams in Other Texts  
## Counting and Correlating Pairs of Words with the widyr Package

![](http://bit.ly/2TLJPql)  

## Counting and Correlating Among Sections  
## Examining Pairwise Correlation  
## Summary  

# 5. Converting to and from Nontidy Formats                                    

[CRAN Task View: Natural Language Processing](https://cran.r-project.org/web/views/NaturalLanguageProcessing.html) lists a large selection of packages that take other structures of input and provide nontidy outputs.

## Tidying a Document-Term Matrix  

## Tidying DocumentTermMatrix Objects  
## Tidying dfm Objects  
## Casting Tidy Text Data into a Matrix  
## Tidying Corpus Objects with Metadata  
## Example: Mining Financial Articles  
## Summary  

# 6. Topic Modeling       

![](http://bit.ly/2TPZMMp)

## Latent Dirichlet Allocation 

two principles 

- Every document is a mixture of topics 
- Every topic is a mixture of words 



## Word-Topic Probabilities  

## Document-Topic Probabilities  
## Example: The Great Library Heist  
## LDA on Chapters  
## Per-Document Classification  
## By-Word Assignments: augment  
## Alternative LDA Implementations  
## Summary  

# 7. Case Study: Comparing Twitter Archives                                    

## Getting the Data and Distribution of Tweets  
## Word Frequencies  
## Comparing Word Usage  
## Changes in Word Use  
## Favorites and Retweets  
## Summary  

# 8. Case Study: Mining NASA Metadata                                        

## How Data Is Organized at NASA  
## Wrangling and Tidying the Data  
## Some Initial Simple Exploration 129Word Co-ocurrences and Correlations  
## Networks of Description and Title Words  
## Networks of Keywords  
## Calculating tf-idf for the Description Fields  
## What Is tf-idf for the Description Field Words?  
## Connecting Description Fields to Keywords  
## Topic Modeling  
## Casting to a Document-Term Matrix  
## Ready for Topic Modeling  
## Interpreting the Topic Model  
## Connecting Topic Modeling with Keywords  
## Summary  

# 9. Case Study: Analyzing Usenet Text                                         

## Preprocessing  
## Preprocessing Text  
## Words in Newsgroups  
## Finding tf-idf Within Newsgroups  
## Topic Modeling  
## Sentiment Analysis  
## Sentiment Analysis by Word  
## Sentiment Analysis by Message  
## N-gram Analysis  
## Summary  



-------------------

- [monkeylearn](https://github.com/ropensci/monkeylearn)
  - [vignettes](https://monkeylearn.com/)
  - [monkeylearn](https://monkeylearn.com/)官网

- [pattern.nlp](https://github.com/bnosac/pattern.nlp)
  - R package to perform sentiment analysis and Parts of Speech tagging for Dutch/French/English/German/Spanish/Italian
    