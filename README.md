## Data files for the paper:

[Ontology-based word sense disambiguation for scientific literature](http://dl.acm.org/citation.cfm?id=2458242)

[Accepted at ECIR 2013, Research track]

# Datasets

## MSH collection

* The MSH corpus used in the paper: [MSHCorpus.zip](MSHCorpus.zip). Contains abstracts with the correct senses, as well as the full list of available senses for each n-gram.
* The part of MSH collection that was used for building entity context vectors: [bio_train_abstracts.csv](bio_train_abstracts.csv). The data is stored in CSV format, each line contains the following values: (ABSTRACT_ID, NGRAM, CORRECT_CONCEPT_ID, CORRECT_NGRAM_MAIN_NAME)
* The part of MSH collection that was used for evaluation: [bio_test_abstracts.csv](bio_test_abstracts.csv). The data is stored in CSV format, each line contains the following values: (ABSTRACT_ID, NGRAM, CORRECT_CONCEPT_ID, CORRECT_NGRAM_MAIN_NAME).

## ScienceWISE (SW) collection:

* The part of SW collection that was used for building entity context vectors: [sw_train_abstracts.csv](sw_train_abstracts.csv). The data is stored in CSV format, each line contains the following values: (ARXIV_ID, NGRAM, CORRECT_CONCEPT_ID, CORRECT_NGRAM_MAIN_NAME)
* The part of SW collection that was used to build additional entity context vectors, the difference is that the abstracts do not contain ambiguous terms: [sw_noabbr_abstracts.csv](sw_noabbr_abstracts.csv).
* The part of SW collection that was used for evaluation: [sw_test_abstracts.csv](sw_test_abstracts.csv). The data is stored in CSV format, each line contains the following values: (ARXIV_ID, NGRAM, CORRECT_CONCEPT_ID, CORRECT_NGRAM_MAIN_NAME).
