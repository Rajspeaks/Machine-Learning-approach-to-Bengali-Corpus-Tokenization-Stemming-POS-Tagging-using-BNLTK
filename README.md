# Machine Learning approach to Bengali Corpus Tokenization | Stemming | POS Tagging using BNLTK 

BNLTK Means Bengali Natural Language Toolkit developed by [Asraf Patoary](https://github.com/ashwoolford). By using BNLTK, we can tokenize, stemming, tagging parts of speeches categories on Bengali Words. 

## Installation:

```
pip install bnltk
```

## Methodology

- First we have installed BNLTK.
- Imported Tokenizers from bnltk & tokenized a Bengali Sentence by splitting into individual words. Then applied the same on a larger Bengali Corpus to tokenize Bengali words.
- Imported BanglaStemmer() from bnltk to apply stemming on Bengali Words. Repeated 2 times the same on different words.
- Downloaded the Datafile from bnltk before moving for further execution.
- Imported PosTagger from bnltk & applied on a Bengali small sentence & tagged each Bengali words into different Parts of Speech categories. Repeated the same 2 times more on larger Bengali Corpora. 


## Tools & Library requirements:

- Google Colab/Jupyter-Notebook
- BNLTK Library


### Reference:

1. https://ashwoolford.github.io/bnltk-documentation/
2. https://github.com/ashwoolford/bnltk


### Mentor:

Prof. Sandipan Ganguly


### Developer:

Rajdeep Das

