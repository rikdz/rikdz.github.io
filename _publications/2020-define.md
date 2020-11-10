---
title: "DeFINE: Deep Factorized Input Token Embeddings for Neural Sequence Modeling"
authors: "Sachin Mehta, Rik Koncel-Kedziorski, Mohammad Rastegari, Hannaneh Hajishirzi"
collection: publications
permalink: /publication/2020-define
excerpt: '"The embedding layer can thus be thought of as a wide, shallow network consisting of a single linear transformation [that] takes a token from its orthographic form to a representation of those of its morphosyntactic and semantic properties which are relevant for modeling an arbitrary number of contexts in which the token can occur. We hypothesize that ... a shallow network would require exceptional capacity to learn a good approximation [but] a deeper network can ... with significantly fewer parameters ..."'
date: 2020-4-1
venue: 'ICLR 2020'
paperurl: 'http://rikdz.github.io/files/2020-define.pdf'
---

Abstract:

For sequence models with large vocabularies, a majority of network parameters lie in the input and output layers. In this work, we describe a new method, DeFINE, for learning deep token representations efficiently. Our architecture uses a hierarchical structure with novel skip-connections which allows for the use of low dimensional input and output layers, reducing total parameters and training time while delivering similar or better performance versus existing methods. DeFINE can be incorporated easily in new or existing sequence models. Compared to state-of-the-art methods including adaptive input representations, this technique results in a 6% to 20% drop in perplexity. On WikiText-103, DeFINE reduces the total parameters of Transformer-XL by half with minimal impact on performance. On the Penn Treebank, DeFINE improves AWD-LSTM by 4 points with a 17% reduction in parameters, achieving comparable performance to state-of-the-art methods with fewer parameters. For machine translation, DeFINE improves the efficiency of the Transformer model by about 1.4 times while delivering similar performance.

[PDF](http://rikdz.github.io/files/2020-define.pdf)

Bibtex:
{% raw %}
```
@inproceedings{mehta2020define,
  title={DeFINE: Deep Factorized Input Token Embeddings for Neural Sequence Modeling},
  author={Mehta, Sachin and Koncel-Kedziorski, Rik and Rastegari, Mohammad and Hajishirzi, Hannaneh},
  booktitle={International Conference on Learning Representations},
  year={2020}
}
```
{% endraw %}

