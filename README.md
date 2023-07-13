# FinLit-corpus
Finnish literature corpus

This is a corpus of literary texts in Finnish collected from Project Gutenberg. The data and corresponding metadata is all in one csv file for ease of processing with Python. The original text files (utf-8) and a version of the csv file containing lemmas (obtained with the help of Turku Neural Parser) as well as the emotion intensity values for both full texts as well as other bin-sizes can be made available upon request.


The file contains the file name (Project Gutenberg id), the name of the author, the book title, the year of publication, whether it is a translated work (Boolean), tokencount, and the fulltext. Most of this information has been extracted with the help of regex from the plain text files and is therefore not guaranteed to be 100% accurate.

You can read more about the collection of the data from these papers. Please cite them if using the corpus.
The full text is available on the [ACL Anthology](https://aclanthology.org/2022.nlp4dh-1.pdf#page=20) website.

```
@article{ohman2022computational,
  title={Computational Exploration of the Origin of Mood in Literary Texts},
  author={{\"O}hman, Emily and Rossi, Riikka},
  journal={NLP4DH 2021},
  pages={8},
  year={2022}
}
```
