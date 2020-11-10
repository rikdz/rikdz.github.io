---
title: "Pyramidal Recurrent Unit for Language Modeling"
authors: "Sachin Mehta, Rik Koncel-Kedziorski, Mohammad Rastegari, Hannaneh Hajishirzi"
collection: publications
permalink: /publication/2018-pyramid
excerpt: '"At the heart of the PRU is the pyramidal transformation (PT), which uses subsampling to effect multiple views of the input vector. The subsampled representations are combined in a pyramidal fusion structure, resulting in richer interactions between the individual dimensions of the input vector than is possible with a linear transformation."'
date: 2018-10-28
venue: 'EMNLP 2018'
paperurl: 'http://rikdz.github.io/files/2018-pyramid.pdf'
---

Abstract:

LSTMs are powerful tools for modeling contextual information, as evidenced by their success at the task of language modeling. However, modeling contexts in very high dimensional space can lead to poor generalizability. We introduce the Pyramidal Recurrent Unit (PRU), which enables learning representations in high dimensional space with more generalization power and fewer parameters. PRUs replace the linear transformation in LSTMs with more sophisticated interactions including pyramidal and grouped linear transformations. This architecture gives strong results on word-level language modeling while reducing the number of parameters significantly. In particular, PRU improves the perplexity of a recent state-of-the-art language model Merity et al.(2018) by up to 1.3 points while learning 15-20% fewer parameters. For similar number of model parameters, PRU outperforms all previous RNN models that exploit different gating mechanisms and transformations. We provide a detailed examination of the PRU and its behavior on the language modeling tasks.

[PDF](http://rikdz.github.io/files/2018-pyramid.pdf)

Bibtex:
```
@inproceedings{mehta2018pyramidal,
  title={Pyramidal Recurrent Unit for Language Modeling},
  author={Mehta, Sachin and Koncel-Kedziorski, Rik and Rastegari, Mohammad and Hajishirzi, Hannaneh},
  booktitle={Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing},
  pages={4620--4630},
  year={2018}
}
```
