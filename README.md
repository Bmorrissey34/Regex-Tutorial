# Regex Tutorial

A regular expression (shortened as regex) is a sequence of characters that specifies a search pattern in text. 
Usually such patterns are used by string-searching algorithms for "find" or "find and replace" operations on strings, or for input validation. 
It is a technique developed in theoretical computer science and formal language theory.

## Summary (Example)

Deleting Duplicate Lines From a File--

If you have a file in which all lines are sorted, you can easily delete duplicate lines. 
Simply open the file in your favorite text editor, and do a search-and-replace searching for `^(.*)(\r?\n\1)+$` and replacing with \1.


## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Author](#Author)

## Regex Components

### Anchors

-In regex, the anchors have zero width. They are not used for matching characters. Rather they match a position i.e. before, after, or between characters

- in the example the ^ and the $ are start and end anchors

### Quantifiers

-Indicate numbers of characters or expressions to match

- (.*) -- The dot and star combination simply matches an entire line, whatever its contents, if any.

### Character Classes

-Character classes distinguish kinds of characters such as, for example, distinguishing between letters and digits.

- \r - 	Matches a carriage return.

- \n - 	Matches a linefeed.

## Author

Hey my names Brendan and i am currently a student in a coding bootcamp. When completed i plan to persue a job as a full stack developer!

check out my GitHub: http://www.github.com/bmorrissey34
