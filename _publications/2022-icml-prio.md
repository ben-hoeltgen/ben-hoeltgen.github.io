---
title: "Prioritized Training on Points that are Learnable, Worth Learning, and Not Yet Learned"
collection: publications
category: conferences
permalink: /publication/2022-icml-prio
excerpt: 'An online batch selection algorithm for time-efficient training of large ML models.'
date: 2022-10-01
venue: 'ICML'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
# paperurl: 'http://academicpages.github.io/files/paper1.pdf'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: 'Mindermann, S., Brauner, J., Razzak, M., Sharma, M., Kirsch, W.,  Xu, W., <b>Höltgen, B.</b>, Gomez, A.N., Morisot, A., Farquhar, S., Gal, Y.: &quot;Prioritized training on points that are learnable, worth learning, and not yet learned.&quot; <i>ICML</i>. 2022.'
---
### Abstract:
Training on web-scale data can take months. But much computation and time is wasted on redundant and noisy points that are already learnt or not learnable. To accelerate training, we introduce Reducible Holdout Loss Selection (RHO-LOSS), a simple but principled technique which selects approximately those points for training that most reduce the model’s generalization loss. As a result, RHO-LOSS mitigates the weaknesses of existing data selection methods: techniques from the optimization literature typically select "hard" (e.g. high loss) points, but such points are often noisy (not learnable) or less task-relevant. Conversely, curriculum learning prioritizes "easy" points, but such points need not be trained on once learned. In contrast, RHO-LOSS selects points that are learnable, worth learning, and not yet learnt. RHO-LOSS trains in far fewer steps than prior art, improves accuracy, and speeds up training on a wide range of datasets, hyperparameters, and architectures (MLPs, CNNs, and BERT). On the large web-scraped image dataset Clothing-1M, RHO-LOSS trains in 18x fewer steps and reaches 2% higher final accuracy than uniform data shuffling. 

[**PDF**](https://proceedings.mlr.press/v162/mindermann22a/mindermann22a.pdf)

So many options,

so much potential, hiding

in calibration.

