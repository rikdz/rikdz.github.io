---
title: "A Controllable Model of Grounded Response Generation"
authors: "Zeqiu Wu, Michel Galley, Chris Brockett, Yizhe Zhang, Xiang Gao, Chris Quirk, Rik Koncel-Kedziorski, Jianfeng Gao, Hannaneh Hajishirzi, Mari Ostendorf, Bill Dolan"
collection: publications
permalink: /publication/2020-control
excerpt: '"We posit that both grounding knowledge and lexical control are essential to generating reliable information. We therefore introduce a generation framework called controllable grounded response generation that incorporates both components."'
date: 2020-5-1
venue: 'Pre-print'
paperurl: 'http://rikdz.github.io/files/2020-control.pdf'
---

Abstract:

Current end-to-end neural conversation models inherently lack the flexibility to impose semantic control in the response generation process. This control is essential to ensure that users' semantic intents are satisfied and to impose a degree of specificity on generated outputs. Attempts to boost informativeness alone come at the expense of factual accuracy, as attested by GPT-2's propensity to "hallucinate" facts. While this may be mitigated by access to background knowledge, there is scant guarantee of relevance and informativeness in generated responses. We propose a framework that we call controllable grounded response generation (CGRG), in which lexical control phrases are either provided by an user or automatically extracted by a content planner from dialogue context and grounding knowledge. Quantitative and qualitative results show that, using this framework, a GPT-2 based model trained on a conversation-like Reddit dataset outperforms strong generation baselines.

[PDF](http://rikdz.github.io/files/2020-control.pdf)

Bibtex:
{% raw %}
```
@misc{wu2020controllable,
      title={A Controllable Model of Grounded Response Generation},
      author={Zeqiu Wu and Michel Galley and Chris Brockett and Yizhe Zhang and Xiang Gao and Chris Quirk and Rik Koncel-Kedziorski and Jianfeng Gao and Hannaneh Hajishirzi and Mari Ostendorf and Bill Dolan},
      year={2020},
      eprint={2005.00613},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```
{% endraw %}

