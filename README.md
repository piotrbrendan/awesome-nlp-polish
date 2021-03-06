# awesome-nlp-polish
A curated list of resources dedicated to Natural Language Processing (NLP) in polish. Models, tools, datasets.

![Awesome NLP Polish Logo](/Awesome_nlp_polish.png)


## Models (Embeddings)

* [SlavicBert - multilingual BERT model. The repository contains Bulgarian+Czech+Polish+Russian](https://github.com/deepmipt/Slavic-BERT-NER) 
* Allegro BERT - It has not been publish yet (12.2019) - but there is a poster - https://conference.mlinpl.org/pdf/CfC_AllPosters.pdf
* Word2vec polish models http://dsmodels.nlp.ipipan.waw.pl/w2v.html
* FastText polish model FB - train on: [Common Crawl](https://github.com/facebookresearch/fastText/blob/master/docs/crawl-vectors.md), [Wikipedia](https://github.com/facebookresearch/fastText/blob/master/docs/pretrained-vectors.md)
* [FastText KGR10 polish model binary](https://clarin-pl.eu/dspace/handle/11321/600)
* [Universal Sentence Encoder Multilingual](https://tfhub.dev/google/universal-sentence-encoder-multilingual-large/3) - sentence embeddings, it covers 16 languages (including Polish)
* [Zalando Flair polish models](https://github.com/flairNLP/flair/blob/master/resources/docs/embeddings/FLAIR_EMBEDDINGS.md) - "pl-forward pl-backward"
* [BPEmb: Subword Embeddings includes polish](https://nlp.h-its.org/bpemb/) - easy to use with [Flair](https://github.com/flairNLP/flair/blob/master/resources/docs/embeddings/BYTE_PAIR_EMBEDDINGS.md)
* [ELMO embeddings] - todo

## Language processing resources and libs

* [Morfologik](https://github.com/morfologik/morfologik-stemming) (Java) and [pyMorfologik](https://github.com/dmirecki/pyMorfologik) (Python wrapper) - dictionary-based morphological analyzer
* [Morfeusz](http://morfeusz.sgjp.pl/download/) - morphological analyzer. See also [Elasticsearch plugin](https://github.com/allegro/elasticsearch-analysis-morfologik)
* [Stempel](https://github.com/dzieciou/pystempel) (Python port) - algorithmic stemmer. See also [Elasticsearch plugin](https://www.elastic.co/guide/en/elasticsearch/plugins/current/analysis-stempel.html)
* [scaCy for Polish](http://spacypl.sigmoidal.io/) - extend spaCy, a popular production-ready NLP library, to fully support Polish language.

## Useful articles or projects

* Github Repo with list of polish: word embeddings and language models (Word2vec, fasttext, Glove, Elmo) -  https://github.com/sdadas/polish-nlp-resources
* Polish Word Embeddings Review - Evaluation of polish word embeddings prepared by various research groups. Evaluation is done by words analogy task https://github.com/Ermlab/polish-word-embeddings-review
* [Polish Sentence Evaluation](https://github.com/sdadas/polish-sentence-evaluation)- contains evaluation of eight sentence representation methods (Word2Vec, GloVe, FastText, ELMo, Flair, BERT, LASER, USE) on five polish linguistic tasks




## Datasets


* [The KLEJ (Kompleksowa Lista Ewaluacji Językowych) benchmark is a set of nine evaluation tasks for the Polish language understanding.](https://klejbenchmark.com/index.html)
* [Wroclaw Corpus of Consumer Reviews Sentiment (WCCRS)](https://clarin-pl.eu/dspace/handle/11321/700)
* PolEval datasets - 
    * Hate speech classification -distinguish between normal/non-harmful tweets (class: 0) and tweets that contain any kind of harmful information (class: 1) [[PolEval 2019 Task6](http://2019.poleval.pl/index.php/tasks/task6)]  [[Ermlab mirror GDrive](https://drive.google.com/drive/folders/1Dp7h9FrejUGK4jOeMsuxObiwP5h4x6q6?usp=sharing)]
* [Ermlab Opineo dataset](https://github.com/Ermlab/pl-sentiment-analysis)- opineo reviews - [GDrive](https://drive.google.com/file/d/1vXqUEBjUHGGy3vV2dA7LlvBjjZlQnl0D/view?usp=sharing)
* HateSpeech corpus contains over 2000 posts crawled from public Polish web.http://zil.ipipan.waw.pl/HateSpeech
* [OSCAR or Open Super-large Crawled ALMAnaCH coRpus](https://traces1.inria.fr/oscar/#corpus) -  is a huge multilingual corpus obtained by language classification and filtering of the Common Crawl corpus. Contains 109GB or 49GB of polish text.
* [Polish Wikipedia dump](https://dumps.wikimedia.org/plwiki/) - regular monthly copy of Polish wikipedia. More then 4GB of text.
* [Polish analogy dataset](https://dl.fbaipublicfiles.com/fasttext/word-analogies/questions-words-pl.txt) - example: "Ateny Grecja Bagdad Irak" - useful for word embeddings evaluation


## Reserch papers

* "Evaluation of Sentence Representations in Polish" - Sławomir Dadas, Michał Perełkiewicz, Rafał Poswiata 2019 https://arxiv.org/pdf/1910.11834.pdf


## Contributors
People who contribute to this project.

* Krzysztof Sopyła - https://ksopyla.com [LinkedIn](https://www.linkedin.com/in/krzysztofsopyla/)


