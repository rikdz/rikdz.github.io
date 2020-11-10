---
title: "Text Generation from Knowledge Graphs with Graph Transformers"
authors: "Rik Koncel-Kedziorski, Dhanush Bekal, Yi Luan, Mirella Lapata, Hannaneh Hajishirzi"
collection: publications
permalink: /publication/2019-kggen
excerpt: '"The main contributions of this work include: 1) We propose a new graph transformer encoder that applies the successful sequence transformer to graph structured inputs. 2) We show how IE output can be formed as a connected unlabeled graph for use in attention-based encoders. 3) We provide a large dataset of knowledgegraphs paired with scientific texts for further study."'
date: 2019-6-14
venue: 'NAACL 2019'
paperurl: 'http://rikdz.github.io/files/2019-kggen.pdf'
---

Abstract:

Generating texts which express complex ideas spanning multiple sentences requires a structured representation of their content (document plan), but these representations are prohibitively expensive to manually produce. In this work, we address the problem of generating coherent multi-sentence texts from the output of an information extraction system, and in particular a knowledge graph. Graphical knowledge representations are ubiquitous in computing, but pose a significant challenge for text generation techniques due to their non-hierarchical nature, collapsing of long-distance dependencies, and structural variety. We introduce a novel graph transforming encoder which can leverage the relational structure of such knowledge graphs without imposing linearization or hierarchical constraints. Incorporated into an encoder-decoder setup, we provide an end-to-end trainable system for graph-to-text generation that we apply to the domain of scientific text. Automatic and human evaluations show that our technique produces more informative texts which exhibit better document structure than competitive encoder-decoder methods.

[PDF](http://rikdz.github.io/files/2019-kggen.pdf)

Bibtex:
{% raw %}
```
@inproceedings{koncelkedziorski:naacl19,
  title={Text {G}eneration {F}rom {K}nowledge {G}raphs with {G}raph {T}ransformers},
  author={Rik Koncel-Kedziorski and Dhanush Bekal and Yi Luan and Mirella Lapata and Hannaneh Hajishirzi},
  booktitle = {NAACL-HLT},
  year={2019}
}
```
{% endraw %}

