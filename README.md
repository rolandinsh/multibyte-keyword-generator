Multibyte Keyword Generator
===========================

[https://github.com/peterkahl/multibyte-keyword-generator](https://github.com/peterkahl/multibyte-keyword-generator)

About
=====

This PHP class is based in large part on the "Automatic Keyword
Generator" class by [Ver Pangonilo](http://www.phpclasses.org/browse/package/3245.html) with
additional improvements, among them being better word segmentation and
ability to handle multibyte strings.

This class automatically generates META Keywords for your web pages
based on the contents of a text string. This eliminates the tedious
process of thinking what the best keywords are. The main principle of
this method is the number of occurrences of single words or multiple
words in a text string.

The string supplied to this class may contain HTML tags and
punctuations. Advantage is taken from the presence of line breaks and
punctuations to better guess the best multiple word keyphrases.

This Multibyte Keyword Generator will automatically create single word
keywords, 2-word and 3-word keyphrases. All keywords and keyphrases are
filtered to remove common (useless) words. Common words are defined
within the class and can be associated with specific language.

This class is highly configurable. One can use minimal settings and rely
on defaults. Alternatively, one can choose to obtain ANY combination of
final result: 1-word keywords, 2-word keyphrases, 3-word keyphrases.
Each option can be disabled. For example, one can configure this class
to obtain only 1-word keywords, or only 2-word keyphrases, or only
3-word keyphrases, or all, or any combination.

This class is capable of handling multilingual texts and multibyte
strings.

This class is capable of handling all European languages and is
likely to handle many others as well. You may need to define
common (useless) words for your own language if not already
part of this class.

