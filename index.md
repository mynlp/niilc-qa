---
layout : default
---

Question Answering (QA) is a principal application of natural language
processing, and many researchers have devoted their effort
intensively.  However, most QA systems developed so far involve a
blackbox process to obtain final answers.  Such systems prevent users
from judging the appropriateness of obtained answers, and their
practical usefuless have been limited.

This dataset is developed for supporting the development of QA systems
that can explain the entire process of obtaining answers.  The current
version targets simple questions that should be answered with an
encyclopedia, and questions are annotated with meta information that
supports the development of QA systems.

## Details of the data

Human annotators manually developed question texts, supposing that
they could be answered using an encyclopedia.  The development set
includes 800 questions, while the test set includes 200 questions.

In addition to questions and their answers, we manually annotated meta
information such as question types, clues to obtain answers, Wikipedia
pages in which answers can be found.  We additionally annotated SPARQL
queries for questions that can be answered using
[JWO (Japanese Wikipedia Ontology)](http://www.wikipediaontology.org)
developed in Yamaguchi Lab. at Keio Univ.

See
[Definitions for Question Answering Tagged Dataset](https://github.com/mynlp/niilc-qa/blob/master/data/NIILC-ECQA2015_AnnotationDefinition.md)
(in Japanese only) for the details of meta information and the data format.

## TODO

* Improve answer data (adding synonyms, etc.)
* Develop an evaluation script
* Extend data

## Reference

When you publish a paper using this dataset, please cite

* Satoshi Sekine.  2003.
  Development of a question answering system focused on an encyclopedia.
  9th Annual Meeting of the Association for Natural Language
  Processing. (in Japanese)

## License

This dataset is distributed under Creative Commons License CC-BY-SA.

## Acknowledgments

This work was partially supported by JST PRESTO.

