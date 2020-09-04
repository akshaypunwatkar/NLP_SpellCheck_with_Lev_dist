# Natural Language Processing - Spellcheck algorithm using Levenshtein Distance

* Using Dynamic programming, edit distances between corrputed words and possible replacement in the dictionary are calculated via Levenshtein Distance. 
* Replacement options with the smallest edit distance is used as a replacement.
* In case, multiple replacement options are available, replacement options which has the most occurance in the corpus is used as the replacement.

## Version 1.0

This version is build using dictionary under [NlTK](https://raw.githubusercontent.com/dwyl/english-words/master/words_alpha.txt).
A corrupted version of Jane Austin was used to test the algorithm. And the algorithm was tested over 500 lines. 
