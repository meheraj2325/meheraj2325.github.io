---
title: "L-Context: Layer-wise Context Vectors for Better Text Classification Using Pre-trained Language Models"
collection: publications
category: conferences
permalink: /publication/l-context-layerwise-context-vectors-text-classification
excerpt: 'This paper introduces L-Context, a technique using layer-wise context vectors to improve text classification in pre-trained language models.'
paperurl: 'https://drive.google.com/file/d/16n6IZQ9n2au9wbJS2djriEJtUPuV97-E/view?usp=sharing'
citation: "Md Fahim, Meheraj Hossain, Sadman Rohan, Md Ashraful Amin, AKM Mahbubur Rahman, Amin Ahsan Ali. \"L-Context: Layer-wise Context Vectors for Better Text Classification Using Pre-trained Language Models.\""
---

Language models employ stacks of self-attention layers to capture rich linguistic representations. Empirical evidence indicates that each layer encodes different types of information, ranging from syntactic to semantic. However, fine-tuning these models can be computationally intensive. Conversely, classifiers based on frozen language models often struggle with performance on downstream tasks. 

To address this issue, we propose the **L-Context** method, which aggregates information from all intermediate layers of language models to generate rich, task-specific representations while keeping the model weights frozen. 

Experiments across 12 different datasets demonstrate that **L-Context** outperforms various adaptation methods and classifiers for frozen language models. Additionally, our model achieves competitive results to fully fine-tuned methods while being 2-3 times faster and requiring fewer parameters.
