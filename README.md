# Summary

PoSTWITA-UD is a collection of Italian tweets annotated in Universal Dependencies that can be exploited for the training of NLP systems to enhance their performance on social media texts.


# Introduction

PoSTWITA-UD was created by enriching the dataset used for the EVALITA 2016 task of Part-of-Speech tagging of Social Media (see (Bosco et al. 2016)).
The original corpus consists of 6,438 tweets of the development set (114,967 tokens) and 300 tweets of the test set (4,759 tokens), annotated at PoS level only. 
The conversion and syntactic annotation process was carried out through alternating steps of automatic scripting and manual revision, and finally with some out-of-domain parsing experiments. Parsing results also underwent a manual revision by two independent annotators.


# Acknowledgements

The treebank development has also been possible thanks to the contribution of Fabio Tamburini (University of Bologna), who used AnIta for lemmatization and morphological analysis, and of Alberto Lavelli (FBK, Trento) and Alessandro Mazzei (University of Turin),  who worked on the parsing experiments.


# Corpus splitting

The section of PoSTWITA that has been revised so far (approximately the first half of the corpus) has been randomly split as follows:
* it_postwita-ud-train.conllu: 51,642 words (2808 sentences)
* it_postwita-ud-dev.conllu: 6,380 words (350 sentences)
* it_postwita-ud-test.conllu: 6,514 words (352 sentences)


# Basic statistics

Tree count: 3510
Word count: 64536
Token count: 61887
Dep. relations: 53 of which 17 language-specific
POS tags: 16
Category=value feature pairs: 35


# References

* Manuela Sanguinetti, Cristina Bosco, Alessandro Mazzei, Alberto Lavelli, Fabio Tamburini. 2017. Annotating Italian Social Media Texts in Universal Dependencies. In: Proceedings of the Fourth International Conference on Dependency Linguistics (Depling 2017), Pisa (Italy), pp. 229–239

* Cristina Bosco, Fabio Tamburini, Andrea Bolioli, Alessandro Mazzei. 2016. Overview of the EVALITA 2016 Part Of Speech on TWitter for ITAlian task. In: Proceedings of Evalita 2016




=== Machine-readable metadata =================================================

Data available since: UD v2.1
License: CC BY-NC-SA 4.0
Includes text: yes
Genre: social
Lemmas: automatic with corrections
UPOS: converted with corrections
XPOS: automatic with corrections
Features: automatic with corrections
Relations: automatic with corrections
Contributors: Bosco, Cristina; Sanguinetti, Manuela
Contributing: elsewhere
Contact: msanguin@di.unito.it

===============================================================================

