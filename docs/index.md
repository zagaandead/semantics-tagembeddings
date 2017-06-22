# Learning Word Embeddings from Tagging Data: A Methodological Comparison

This repository contains the generated embeddings from the KDML submission ["Learning Word Embeddings from Tagging Data: A Methodological Comparison"](nolink)
by
by
[Thomas Niebler](http://www.dmir.uni-wuerzburg.de/staff/niebler),
Luzian Hahn and
[Andreas Hotho](http://www.dmir.uni-wuerzburg.de/staff/hotho).

## Overview
In our work, we compared the three embedding algorithms Word2Vec, GloVe and LINE with regard to their applicability
on tagging data from folksonomies and the semantic quality of the produced embeddings.

## Reference Implementations
### Word2Vec
For LSML, we used a modified implementation from the one in the [metric_learn](https://github.com/all-umass/metric-learn) package.

### GloVe
We used the [published code of GloVe](https://nlp.stanford.edu/projects/glove/) to create the tag embeddings of
dimension 100. We used the predefined values of alpha=0.75 and x_max=100.

### LINE


## Vector Embeddings
These are the resulting embeddings.

### Delicious
The Delicious tagging dataset is [publicly available](http://www.zubiaga.org/datasets/socialbm0311).
The generated word embeddings are published in this repository. 

### BibSonomy
The BibSonomy tagging data can be retrieved from [the BibSonomy homepage](https://www.kde.cs.uni-kassel.de/bibsonomy/dumps/).
We also provide the generated word embeddings as a public download in this repository. 

### CiteULike
The CiteULike tagging data can be retrieved from [CiteULike](http://www.citeulike.org/faq/data.adp).
We provide the generated word embeddings as a public download in this repository.

## Human Intuition Datasets
The Human Intuition Datasets (HIDs) can be retrieved as preprocessed pandas-friendly csv files 
[here](http://www.thomas-niebler.de/dataset-collection-for-evaluating-semantic-relatedness/)
or from the corresponding original locations.
* [WordSimilarity-353](http://www.cs.technion.ac.il/~gabr/resources/data/wordsim353/wordsim353.html)
* [MEN collection](https://staff.fnwi.uva.nl/e.bruni/MEN)
* [MTurk Dataset](http://www.kiraradinsky.com/Datasets.html)
* [Bib100](http://dmir.org/datasets/bib100/)


