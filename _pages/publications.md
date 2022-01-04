---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Peer-Reviewed Journal Articles
=====

* __Tiantian Liu__, Zijin Feng, Huan Li, Hua Lu, Muhammad Aamir Cheema, Hong Cheng, Jianliang Xu. Towards Indoor Temporal-variation aware Shortest Path Query. IEEE Transactions on Knowledge and Data Engineering (__TKDE__), 14 pages, 2021. (to appear)(__CCF A__)
* __Tiantian Liu__, Huan Li, Hua Lu, Muhammad Aamir Cheema, Lidan Shou. Towards Crowd-aware Indoor Path Planning. Proceedings of the 47th International Conference on Very Large Data Bases (__PVLDB__), 2021: 1365-1377. (__CCF A__)

Peer-Reviewed Conference Papers
=====

* __Tiantian Liu__, Zijin Feng, Huan Li, Hua Lu, Lidan Shou, and Jianliang Xu, "IKAROS: An Indoor Keyword-Aware Routing System," accepted by __ICDE__ (Demo Paper). (__CCF A__)
* Harry Kai-Ho Chan, __Tiantian Liu__, Huan Li, Hua Lu. Time-Constrained Indoor Keyword-aware Routing. Proceedings of the 17th International Symposium on Spatial and Temporal Databases (__SSTD__), 2021: 74-84. (__Best paper nomination__)
* __Tiantian Liu__, Huan Li, Hua Lu, Muhammad Aamir Cheema, Lidan Shou. Indoor Spatial Queries: Modeling, Indexing, and Processing. __EDBT__ 2021: 181-192. (__CCF B__)
* __Tiantian Liu__, Zijin Feng, Huan Li, Hua Lu, Muhammad Aamir Cheema, Hong Cheng, Jianliang Xu. Shortest Path Queries for Indoor Venues with Temporal Variations. __ICDE__ 2020: 2014-2017. (__CCF A__)
* Zijin Feng, __Tiantian Liu__, Huan Li, Hua Lu, Lidan Shou, Jianliang Xu. Indoor Top-k Keyword-aware Routing Query. __ICDE__ 2020: 1213-1224. (__CCF A__)

Technical Reports
=====

* __Tiantian Liu__, Huan Li, Hua Lu, Muhammad Aamir Cheema, Lidan Shou. Towards Crowd-aware Indoor Path Planning(Extended Version). CoRR abs/2104.05480 (2021).
* __Tiantian Liu__, Huan Li, Hua Lu, Muhammad Aamir Cheema, Lidan Shou. An Experimental Analysis of Indoor Spatial Queries: Modeling, Indexing, and Processing. CoRR abs/2010.03910 (2020)


test
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
