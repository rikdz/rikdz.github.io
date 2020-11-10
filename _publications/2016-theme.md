---
title: "A Theme-Rewriting Approach for Generating Algebra Word Problems"
authors: "Rik Koncel-Kedziorski, Ioannis Konstas, Luke Zettlemoyer, Hannaneh Hajishirzi"
collection: publications
permalink: /publication/2016-theme
excerpt: '"Given a theme, the rewrite algorithm constructs new texts by substituting thematically appropriate words and phrases, as measured with automatic metrics over the theme text collection, for parts of the original texts. This process optimizes for a number of metrics of overall text quality, including syntactic, semantics, and discourse scores. It uses no hand crafted templates and requires no theme-specific tuning data, making it easy to apply for new themes in practice"'
date: 2016-10-1
venue: 'EMNLP 2016'
paperurl: 'http://rikdz.github.io/files/2016-theme.pdf'
---

Abstract:

Texts present coherent stories that have a particular theme or overall setting, for example science fiction or western. In this paper, we present a text generation method called rewriting that edits existing human-authored narratives to change their theme without changing the underlying story. We apply the approach to math word problems, where it might help students stay more engaged by quickly transforming all of their homework assignments to the theme of their favorite movie without changing the math concepts that are being taught. Our rewriting method uses a two-stage decoding process, which proposes new words from the target theme and scores the resulting stories according to a number of factors defining aspects of syntactic, semantic, and thematic coherence. Experiments demonstrate that the final stories typically represent the new theme well while still testing the original math concepts, outperforming a number of baselines. We also release a new dataset of human-authored rewrites of math word problems in several themes.

[PDF](http://rikdz.github.io/files/2016-theme.pdf)

Bibtex:
```
@InProceedings{koncelkedziorski-EtAl:2016:EMNLP2016,
  author    = {Koncel-Kedziorski, Rik  and  Konstas, Ioannis  and  Zettlemoyer, Luke  and  Hajishirzi, Hannaneh},
  title     = {A {T}heme-{R}ewriting {A}pproach for {G}enerating {A}lgebra {W}ord {P}roblems},
  booktitle = {EMNLP},
  month     = {November},
  year      = {2016},
  pages     = {1617--1628}
}
```
