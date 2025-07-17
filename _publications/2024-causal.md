---
title: "Formalising causal inference as prediction on a target population"
collection: publications
category: in-progress
permalink: /publication/2024-icml-causality
excerpt: 'A different way of modelling causal inference.'
date: 2025-10-01
# venue: 'NeurIPS Worksho: Explainable AI Approaches for Debugging and Diagnosis'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
# paperurl: 'http://academicpages.github.io/files/paper1.pdf'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: '<b>Höltgen, B.</b>, Williamson, R.C.: &quot;Causal modelling without counterfactuals and individualised effects.&quot; <i>ICML Workshop: Humans, Algorithmic Decision-Making and Society</i>. 2024.'
---
### Abstract:
The standard approach to causal modelling especially in social and health sciences is the potential outcomes framework due to Neyman and Rubin. In this framework, observations are thought to be drawn from a distribution over variables of interest, and the goal is to identify parameters of this distribution. Even though the stated goal is often to inform decision making on some target population, there is no straightforward way to include these target populations in the framework. Instead of modelling the relationship between the observed sample and the target population, the inductive assumptions in this framework take the form of abstract sampling and independence assumptions. In this paper, we develop a version of this framework that construes causal inference as treatment-wise predictions for finite populations where all assumptions are testable in retrospect; this means that one can not only test predictions themselves (without any fundamental problem) but also investigate sources of error when they fail. Due to close connections to the original framework, established methods can still be be analysed under the new framework.

[**preprint**](https://arxiv.org/pdf/2407.17385)
