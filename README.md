Multibyte Keyword Generator
===========================

Copyright (c) 2009-2012, Peter Kahl. All rights reserved. www.colossalmind.com

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

License
=======

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see [http://www.gnu.org/licenses/](http://www.gnu.org/licenses/).

Change Log
==========

0.9 ..... 2009-11-05
	Initial release

1.0 ..... 2010-01-19
	Improved function removeDuplicateKw() to better handle deletion of duplicate
	plural words (English), such as "class" and "classes".

1.1 ..... 2010-01-19
	Changed the function array_one_dim() to array_flatten().

1.2 ..... 2010-08-14
	Improved regular expressions in function html2txt().

1.3 ..... 2010-08-20
	Added word segmentation for character ':' in function process_text().

1.4 ..... 2011-05-08

1.5 ..... 2012-02-26

1.6 ..... 2012-02-26

1.7 ..... 2012-11-02
	Added link to repo on GitHub.

