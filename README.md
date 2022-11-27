# Overview
The objective of this project is to leverage the techniques learnt in Natural Language Processing to help determine what is the most important skill organizations are looking for in “data” related job postings. 900+ job posts of Business Analyst, Data Analyst, Data Engineer, Data Scientist were scrapped.


They were then studied using word clouds. The world clouds were improved using bag of words and TF-IDF, and finally, Gensim was used for LDA (Latent Dirichlet Allocation) and topic modeling to do the inference.

The project allows you to understand what are the key attributes that are valued and repeated the most across job descriptions in the "data" related fields. You would think that analytical skills or coding skills might be the most important skill required by companies but infact the answer is something you might not expect. Check out the Wordclouds after using TF-IDF!!


# Main Libraries Used
- pandas
- nltk
- gensim
- collections
- os
- re
- urllib
- numpy
- matplotlib
- sklearn
- wordclound