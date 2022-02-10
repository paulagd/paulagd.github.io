---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}


## Graph Convolutional Embeddings for Recommender Systems

2021-07-12 (IEEE Access)

**Citation**: Paula, G. Duran, A. Karatzoglou, J. Vitrià, X. Xin and I. Arapakis (2021). &quot;Graph Convolutional Embeddings for Recommender Systems.&quot; <i>IEEE Access vol9.</i>

[Download paper here](https://ieeexplore.ieee.org/abstract/document/9481221)

**ABSTRACT**

Modern recommender systems (RS) work by processing a number of signals that can be inferred from large sets of user-item interaction data. The main signal to analyze stems from the raw matrix that represents interactions. However, we can increase the performance of RS by considering other kinds of signals like the context of interactions, which could be, for example, the time or date of the interaction, the user location, or sequential data corresponding to the historical interactions of the user with the system. These complex, context-based interaction signals are characterized by a rich relational structure that can be represented by a multi-partite graph. Graph Convolutional Networks (GCNs) have been used successfully in collaborative filtering with simple user-item interaction data. In this work, we generalize the use of GCNs for N-partite graphs by considering N multiple context dimensions and propose a simple way for their seamless integration in modern deep learning RS architectures. More specifically, we define a graph convolutional embedding layer for N-partite graphs that processes user-item-context interactions and constructs node embeddings by leveraging their relational structure. Experiments on several datasets show the benefits of the introduced GCN embedding layer by measuring the performance of different context-enriched tasks.



## Demonstration of an Open Source Framework for Qualitative Evaluation of CBIR Systems


2018-10-15 (ACMM 18')

**Citation**: Paula, G. Duran, Eva Mohedano, Kevin McGuinness, Xavier Giró-i-Nieto, and Noel E. O'Connor(2018). &quot;Demonstration of an Open Source Framework for Qualitative Evaluation of CBIR Systems.&quot; <i>ACMM 18'.</i>.'

[Download paper here](https://dl.acm.org/doi/abs/10.1145/3240508.3241395)

**ABSTRACT**

Evaluating image retrieval systems in a quantitative way, for example by computing measures like mean average precision, allows for objective comparisons with a ground-truth. However, in cases where ground-truth is not available, the only alternative is to collect feedback from a user. Thus, qualitative assessments become important to better understand how the system works. Visualizing the results could be, in some scenarios, the only way to evaluate the results obtained and also the only opportunity to identify that a system is failing. This necessitates developing a User Interface (UI) for a Content Based Image Retrieval (CBIR) system that allows visualization of results and improvement via capturing user relevance feedback. A well-designed UI facilitates understanding of the performance of the system, both in cases where it works well and perhaps more importantly those which highlight the need for improvement. Our open-source system implements three components to facilitate researchers to quickly develop these capabilities for their retrieval engine. We present: a web-based user interface to visualize retrieval results and collect user annotations; a server that simplifies connection with any underlying CBIR system; and a server that manages the search engine data. The software itself is described in a separate submission to the ACM MM Open Source Software Competition.
