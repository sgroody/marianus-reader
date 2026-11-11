# Marianus Reader

A reader for the Gospels in Old Church Slavonic, using the text of the **Codex Marianus** (a Glagolitic Gospel book from the late 10th or early 11th century). It is built for Russian speakers learning Old Church Slavonic, and it also has a full English interface.

**Read it here: https://sgroody.github.io/marianus-reader/**

Click any word to see:
- its dictionary form, meaning and full parse;
- grammar notes on what the form does in its sentence;
- a table of all its forms found in the Gospels;
- the Greek word it translates;
- a concordance of the word's other occurrences.

Russian and English translations can be shown beside the text or under each verse. The Slavonic can be shown in Cyrillic, Glagolitic or Latin letters.

The manuscript is incomplete. It begins at Matthew 5:24 and has other gaps, and the front page maps them.

The layout follows John H. Boyer's Greek readers (johnhboyer.com).

## Sources

- **Old Church Slavonic text and annotation:** PROIEL Treebank, `marianus` (after Jagić 1883). Haug, D. T. T. & Jøhndal, M. L. 2008, *Creating a Parallel Treebank of the Old Indo-European Bible Translations*. https://github.com/syntacticus/syntacticus-treebank-data, CC BY-NC-SA 4.0.
- **Greek text:** PROIEL `greek-nt` (Tischendorf 1869), CC BY-NC-SA 4.0.
- **Greek lexicon:** Dodson Greek–English Lexicon, public domain.
- **Translations** (via eBible.org), all public domain:
  - Russian Synodal (1876)
  - Russian Freedom Bible
  - King James Version
  - World English Bible
- **Russian glosses** were written for this project.

## Licence

Because it is built on PROIEL data, this site and its data are released under **CC BY-NC-SA 4.0** (https://creativecommons.org/licenses/by-nc-sa/4.0/). You may share and adapt it for non-commercial purposes, with attribution, under the same licence.

## Running locally

It is a static site with no build step:

```
python -m http.server 8000
```

Then open http://localhost:8000.
