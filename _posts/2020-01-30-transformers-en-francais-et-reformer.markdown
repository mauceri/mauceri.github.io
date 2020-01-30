---
layout: post
title:  "Transformers en français et Reformer"
date:   2020-01-30 16:20:00 +0000
categories: transformers reformer français
---
# Transformers en français et Reformer

À part l'exception notable de Camembert il n'existe pas de modèles de transfomer pré-entrainés en français. C'est vraiment un problème pour ceux qui voudraient utiliser cette architecture dans des applications tournées vers un public Français car il est extrêmement coûteux de pré-entrainer un transformer, il faut compter plusieurs milliers de dollars de location de machines GPU ou TPU.
Il est possible d'utiliser des modèles multilingues comme ceux de XLM ou XNLG mais quelque soient les performances annoncées par leurs promoteurs on peut douter qu'elles puissent égaler celles de modèles directement pré-entrainés en Français surtout pour des systèmes d'aide à l'écriture basé sur GPT ou CTRL (Conditional TRansformer Language).
Une récente amélioration des transformers baptisée reformer, semble pouvoir permettre de réduire drastiquement les coûts liés au pré-entrainement de ces architecture et ouvrir la voie à la créations de modèles Français.

[Transformers](http://www.peterbloem.nl/blog/transformers,http://nlp.seas.harvard.edu/2018/04/03/attention.html)
