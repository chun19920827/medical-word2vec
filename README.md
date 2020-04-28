# A Word2Vec model trained with Chinese medical corpus.
Word2Vec model has been widely used in medical NLP tasks. 
Although new types of language model such as BERT are popular in recent years, the method of Word2Vec still has application value.<br>
It has been proved that the model trained with medical corpus can achieve better performance than the model with general corpus. 
However, it's pity that there are few public Word2Vec model trained with Chinese medical corpus.
Here we release a Word2Vec Model trained with sufficient Chinese medical corpus. 
Our model can be directly used in Chinese medical NLP tasks, so that researchers don't need to collect medical text and train the model from the beginning.
## Download
Waiting for update
## Chinese Medical Corpus
Corpus | # of words
------------- | -------------
Medical textbooks |	13.93M
Medical science articles | 455.83M
EMRs | 456.07M
Clinical guidance and expert consensus | 4.31M
Chinese wiki articles | 212.81M
Total | 1142.95M


## Training Parameters
* Type: CBOW
* Vector Size: 400
* Window Size: 5
* Minimum Word Count: 1
* Negative Sampling: 10
