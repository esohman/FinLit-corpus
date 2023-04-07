# FinLit-corpus
Finnish literature corpus

This is a corpus of literary texts in Finnish collected from Project Gutenberg. The data and corresponding metadata is all in one csv file for ease of processing with Python. The original text files (utf-8) and a version of the csv file containing lemmas (obtained with the help of Turku Neural Parser) can be made available upon request.

As the file is too large for GitHub it can be accessed via [Gigasheet here](https://app.gigasheet.com/spreadsheet/fulldf-csv/c73af2ec_8220_4932_ab28_4d03e6342177).


The file contains the file name, name of the author, the book title, year of publication, whether it is a translated work, wordcount, and the fulltext. Most of this information has been extracted with the help of regex from the plain text files and is therefore not guaranteed to be 100% accurate.

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
