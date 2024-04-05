# bookinfo

This allows metadata to be extracted from various ebook formats:

* epub
* prc
* mobi
* pdf

The quality of that data is not gauranted. The data available from pdf files is even less consistent. I assume that this is becasue most pdfs are simply being generated from other sources

The output starts with `FILENAME:` followed by `FORMAT:`. Some of the data types will appear multiple times (such as the `CREATOR:` in the example given below) and some values will span multiple lines and include blank lines

```
FILENAME: ./The nanowrimo writing bundle/writingmemoir.epub
FORMAT: epub
COVERAGE: New York
CREATOR: Julie Lythcott-Haims
CREATOR: The San Francisco Writers’ Grotto
DATE: 2022-05-27T00:00:00Z
IDENTIFIER: 9781647009731
LANGUAGE: en
PUBLISHER: Abrams Noterie
RIGHTS: © 2022
SOURCE: urn:isbn:9781647009731
TITLE: Writing Memoir: A Book of Writing Prompts
TYPE: Text
```
