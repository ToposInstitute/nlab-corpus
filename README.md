# nLab corpus

This repository contains a "cleaned" version of the contents of the nLab (as of c. December 2020), with the intention of being used as a training corpus for various machine learning projects.
The cleaning process simply strips out any non-textual elements (such as bullet points) and converts the LaTeX mathematics into unicode, wherever possible.

- `nlab_plain_normalized.txt` is the concatenation of all the pages into one large text file.
- `nlab_plain.json` has the same content as the plaintext file, but is organised into key-value pairs, with the key being the title of the page, and the value being its contents.
- `nlab_stats.json` contains some basic statistics about the corpus, generating by [spaCy](https://spacy.io).

For licencing information, see the [nLab licence](https://ncatlab.org/nlab/show/HomePage#TermsOfUse).
