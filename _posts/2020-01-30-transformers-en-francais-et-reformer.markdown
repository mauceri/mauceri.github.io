---
layout: post
title:  "Transformers en français et Reformer"
date:   2020-01-30 16:20:00 +0000
categories: transformers reformer français
---
# Transformers en français et Reformer

À part l’exception notable de Camembert, il n’existe pas de modèles de transfomer préentrainés en français. C’est vraiment un problème pour ceux qui voudraient utiliser cette architecture dans des applications tournées vers un public français, car il est extrêmement coûteux de préentrainer un transformer, il faut compter plusieurs milliers de dollars de location de machines GPU ou TPU sur AWS ou GCP. Il est possible d’utiliser des modèles multilingues comme ceux de XLM ou XNLG mais quelque soient les performances annoncées par leurs promoteurs on peut douter qu’elles puissent égaler celles de modèles directement préentrainés en Français surtout pour des systèmes d’aide à l’écriture basés sur GPT ou CTRL (Conditional TRansformer Language). Une récente amélioration des transformers baptisée reformer, semble pouvoir permettre de réduire drastiquement les coûts liés au préentrainement de ces architecture et ouvrir la voie à la création de modèles français.

[Transformers](http://www.peterbloem.nl/blog/transformers), [Attention](http://nlp.seas.harvard.edu/2018/04/03/attention.html)  
[CamemBERT](https://camembert-model.fr/#download)   
[XLM](https://arxiv.org/pdf/1901.07291.pdf)  
[XNLG](https://arxiv.org/pdf/1909.10481.pdf)  
[CTRL](https://blog.einstein.ai/introducing-a-conditional-transformer-language-model-for-controllable-generation/)  
[OSCAR](https://traces1.inria.fr/oscar/)  
