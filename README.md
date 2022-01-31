## Description

This project takes text files and creates n-gram linear models from them. It consists of the following programs: 

### `ngram_count`

Collects unigrams, bigrams, and trigrams from a given text file. Returns a text file listing the n-grams in order of frequency within an n-gram chunk (unigram, bigram, trigram). 


### `build_lm`

Takes a text file listing the n-grams and returns a linear model (in ARPA format) built using n-gram counts without smoothing. 

### `ppl`

Calculates the perplexity of a test data given a linear model. Uses interpolation for smoothing. 