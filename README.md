# Embedding-package

## About 
This project allows you to train word embedding on your own data set. It incorporates embedding methods such as 'Glove','Skip-gram' or 'CBOW' and train word embeddings specific to dataset. Morever, this word embeddings can be used as tensorflow layer API too.  

If you want to build a NLP model, word embeddings are the building blocks for most of the NLP model. Current trend give us two option:  
1. Train word embedding along with your final NLP model from the scratch. It is generally used in small and simple models. In this case, as model stacks huge no of layers, vanishing gradients become significant and cause poor training of word embedding.  Example- Tensorflow's Embedding API   
2. Use pre-trained embedding, trained on different dataset. Most of the industrial and real word soltions use this option. It has minor drawback. i.e when our dataset contains words which aren't present in pre-trained embeddings, embedding quality degrades.  Example FastText,GloVe,Word2vec.  

This work addresses this issue by allowing us to train word embedding on specific data and then use this trained embedding as tensorflow layer API and train along with model. 



