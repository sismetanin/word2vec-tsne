# Google News and Leo Tolstoy: Visualizing Word2Vec Word Embeddings using t-SNE

This repository contains the source code for visualizing high-dimensional Word2Vec word embeddings using t-SNE. The visualization can be useful to understand how Word2Vec works and how to interpret relations between vectors captured from your texts before using them in neural networks or other machine learning algorithms. As a training data, we will use articles from Google News and classical literary works by Leo Tolstoy, the Russian writer who is regarded as one of the greatest authors of all time.

![MSA](static/war-and-peace.gif)

## Data
The pre-trained model trained on part of Google News dataset (about 100 billion words) is available at [https://code.google.com/archive/p/word2vec/](https://code.google.com/archive/p/word2vec/) (and also described in [1]). The model contains 300-dimensional vectors for 3 million words and phrases.

Tolstoy's novels in Russian are available at  [https://www.litres.ru/lev-tolstoy](https://www.litres.ru/lev-tolstoy).

## References
1. L. Maate and G. Hinton, "Visualizing data using t-SNE", Journal of Machine Learning Research, vol. 9, pp. 2579-2605, 2008. 
2. T. Mikolov, I. Sutskever, K. Chen, G. Corrado and J. Dean, "Distributed Representations of Words and Phrases and their Compositionality", Advances in Neural Information Processing Systems, pp. 3111-3119, 2013. 
3. R. Rehurek and P. Sojka, "Software Framework for Topic Modelling with Large Corpora", Proceedings of the LREC 2010 Workshop on New Challenges for NLP Frameworks, 2010.


## Documentation and How to report bugs
* Gensim documentatiob: [https://radimrehurek.com/gensim/](https://radimrehurek.com/gensim/). 
* Scikit-learn documentation: [http://scikit-learn.org/stable/documentation.html](http://scikit-learn.org/stable/documentation.html). 
* If you find any issues, please open a bug here on GitHub.

## License
See [LICENSE](LICENSE).