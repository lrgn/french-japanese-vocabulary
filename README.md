# French-Japanese vocabulary

This repository contains a list of Japanese words or terms, and their translation in French. 

## File format

The data is presented as a semi-column separated CSV file, composed of 4 column:
1. Kanji: the japanese word written with kanjis. This column will be empty in case of a furigana-only word
2. Furigana: the corresponding furigana prononciation
3. French: one or more French translation word(s) or term(s), separated by a comma and a space (", ")
4. Comment: some additional information. This column will be empty when not needed

NB: for verbs, the Kanji column contains the dictionary form, and the Furigana column contains both the dictionary and the polite forms, separated by a "・".

NB: the file is sorted before each commit using the [GNU sort](https://www.gnu.org/software/coreutils/manual/html_node/sort-invocation.html#sort-invocation) utility.

## Examples

* a normal word:
```
果物; くだもの; fruit
```

* word coming from another language:
```
; ガソリン; essence; de l'anglais "gasoline"
```

* a verb
```
食べる; たべる・たべます; manger
```
