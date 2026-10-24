
This repository contains the EU-acquis Entity Corpus described in <url><b>https://aclanthology.org/2026.emnlp-main.2491/</b></url>

There are two sub-corpora: GOLD - fully human-annotated corpus, and SILVER - semi-automatically created corpus.

# GOLD

The format of the GOLD corpus file is as follows:

Each line contains a single entry consisting of 6 tab-separated elements

<b>[file-name]</b>  <b>[text snippet]</b> <b>[start-offset]</b> <b>[end-offset]</b> <b>[entity-type]</b> <b>[nominal]</b>

The field <b>text snippet</b> contains the text fragment that contains the entity mention, labelled with the entity type <b>[entity-type]</b>.

The value of <b>nominal</b> is either true or false depending on whether the mention of the entity is nominal or named.

The start and end offsets are at character level.

# SILVER

The format of the SILVER corpus file is similar:

Each line contains a single entry consisting of 5 tab-separated elements

<b>[file-name]</b>  <b>[text snippet]</b> <b>[start-offset]</b> <b>[end-offset]</b> <b>[entity-type]</b>

Please note that the version of SILVER corpus described in the paper is this one: https://github.com/jpiskorski/eu-acquis-ner/blob/main/SILVER_EU_acquis_entity_corpus_ver.1.0.zip 

Version 2.0 of the corpus was created by fine-tuning the way how the extractions of the Knowledge- and Claude-based systems
were merged (not described in the paper) and by discarding a large number of numerical expressions included in tables in annexes
in one of the documents. There is also a slight difference in the raw document set.

#  EXPLOITATION OF THE CORPUS

EU-acquis Entity Corpus can be used for research purposes.

Please use the following [BIB](https://github.com/jpiskorski/eu-acquis-ner/blob/main/citation.bib) file for citation.



