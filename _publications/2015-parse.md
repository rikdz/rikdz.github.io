---
title: "Parsing Algebraic Word Problems into Equations"
authors: "Rik Koncel-Kedziorski, Hannaneh Hajishirzi, Ashish Sabharwal, Oren Etzioni, Sienna Dumas Ang"
collection: publications
permalink: /publication/2015-parsing
excerpt: '"ALGES learns to map spans
of text to arithmetic operators, to combine them
given the global context of the problem, and to
choose the “best” tree corresponding to the problem."'
date: 2015-12-1
venue: 'TACL 2015, Volume 3'
paperurl: 'http://rikdz.github.io/files/2015-parsing.pdf'
---

Abstract:

This paper formalizes the problem of solving multi-sentence algebraic word problems as that of generating and scoring equation trees. We use integer linear programming to generate equation trees and score their likelihood by learning local and global discriminative models. These models are trained on a small set of word problems and their answers, without any manual annotation, in order to choose the equation that best matches the problem text. We refer to the overall system as Alges. We compare Alges with previous work and show that it covers the full gamut of arithmetic operations whereas Hosseini et al.(2014) only handle addition and subtraction. In addition, Alges overcomes the brittleness of the Kushman et al.(2014) approach on single-equation problems, yielding a 15% to 50% reduction in error.

[PDF](http://rikdz.github.io/files/2015-parsing.pdf)

Bibtex:
```
@article{koncel2015parsing,
  title={Parsing algebraic word problems into equations},
  author={Koncel-Kedziorski, Rik and Hajishirzi, Hannaneh and Sabharwal, Ashish and Etzioni, Oren and Ang, Siena Dumas},
  journal={Transactions of the Association for Computational Linguistics},
  volume={3},
  pages={585--597},
  year={2015},
  publisher={MIT Press}
}
```
