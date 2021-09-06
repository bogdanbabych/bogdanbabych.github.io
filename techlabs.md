---
layout: default
title: Research
nav_order: 5
---


## Prof. Dr. Bogdan Babych
### Professor of Translation Studies, Head of Department of Translation, Communication and Technology
### Institute for Translation and Interpreting, Heidelberg University

[Home](index.md) | [Research](research.md) | [Teaching](teaching.md) | [Collaboration](collaboration.md) | [Techologies](techlabs.md) | [![Image](de_l_flag.png)](/de_index.html) [![Image](uk_l_flag.png)](/uk_index.html)

### Development of translation technologies and applications

#### Research and teaching experiments

1. [**cgiBLEU**](http://corpus.leeds.ac.uk/corpuslabs/lab201801cgibleu/): On-line interface to BLEU / NIST evaluation toolkit: [cgiBLEU](http://corpus.leeds.ac.uk/corpuslabs/lab201801cgibleu/)
2. [**colloc4nlg**](http://corpus.leeds.ac.uk/corpuslabs/lab201810cnlg/colloc4nlg.html) Experiments on using collocations for Natural Language Generation: [colloc4nlg](https://github.com/bogdanbabych/colloc4nlg); [web](http://corpus.leeds.ac.uk/corpuslabs/lab201810cnlg/colloc4nlg.html); [code](http://corpus.leeds.ac.uk/corpuslabs/lab201810cnlg/?C=M;O=A)
3. [**Kyiv2020**](http://corpus.leeds.ac.uk/corpuslabs/lab2020Kyiv) Kyiv Translation Summer School 2020 at Igor Sikorsky Kyiv Polytechnic Institute [presentation and materials](http://corpus.leeds.ac.uk/corpuslabs/lab2020Kyiv/)
4. [**smallSMT**](http://corpus.leeds.ac.uk/lingenio/) A prototype SMT system for [Lingenio's](https://lingenio.de/en/) [FlexNeuroTrans](https://lingenio.de/en/research/projects/FlexNeuroTrans/) project: [web interface](http://corpus.leeds.ac.uk/lingenio/) [web file interface](http://corpus.leeds.ac.uk/lingenio/indexfile.html)
5. [**Ukrainian corpus and morphological tools**](http://corpus.leeds.ac.uk/svitlana/tnt/ua/):
- [**Parameter files**](http://corpus.leeds.ac.uk/svitlana/tnt/ua/) for the [TNT](http://www.coli.uni-saarland.de/~thorsten/tnt/) part-of-speech tagger; research [paper](http://eprints.whiterose.ac.uk/100896/3/BabychExperiencing%20the%20digital%20world.pdf) with evaluation.
- [**Ukrainian news corpus**](http://corpus.leeds.ac.uk/internet2.html), 250 million words, up to 2012: [web interface](http://corpus.leeds.ac.uk/internet2.html); [downloadable .vert file](http://corpus.leeds.ac.uk/corpuslabs/lab2020Kyiv/INTERNET-UA/) (1.2GB); smaller 10 million words corpus sample: [downloadable files](http://corpus.leeds.ac.uk/corpuslabs/lab2020Kyiv/INTERNET-UA10M/).
6. [**Processing CORD19 corpus**](https://colab.research.google.com/github/iued-uni-heidelberg/cord19/blob/main/cord19download2text.ipynb#scrollTo=apx9q6HAbXkM)
This notebook downloads and reads the free cord19 corpus into one file.

The notebook is hosted at IÜD, Heidelberg University github repository [https://github.com/iued-uni-heidelberg/cord19](https://github.com/iued-uni-heidelberg/cord19).

CORD19 (covid-19) is an open-source corpus available from [https://www.semanticscholar.org/cord19/download](https://www.semanticscholar.org/cord19/download). Documentation is available at [https://github.com/allenai/cord19](https://github.com/allenai/cord19). The original files are in json format.

The output file is in plain text format; documents are separated (by default) by \<doc id="doc1000001"> ... \</doc> tags. The purpose of the plain text file is for further processing, e.g., generating linguistic annotation using the TreeTagger or the Stanford parser for part-of-speech annotation or dependency / constituency parsing.
