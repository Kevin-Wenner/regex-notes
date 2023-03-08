# Regex Notes

Regex, shor for regular expression are not specific to any programing language and syntax for the most part tranfers amongst many of them.

## Summary

Regex allows us to search through text and find specific characters or grouping of characters in order.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors
do not matach with any characters or belong to any token family. Instead they assert something about the matched string. Some example types of anchors are ^, $, \A, \D, |. Specifying assertions allows for lest time looking for matches outside of specified interest.
### Quantifiers
specify the instances of the character, quantity, group, or class that must be present to match. 
### OR Operator
|, matches characters of either left or right of the operator
### Character Classes
allows to match characters within classes. 
- subtraction, match characters that belong to one, but not another
- intersection, match characters that belong to both one and another
- union, match characters that belong to either
### Flags
changes the search behavior of regex. examples
- i, case-insensitive
- g, global, search for all occurrences
- s, Dot all, makes . match newlines
- m, multiline, makes broundry characters match every beging and end line rather than whole string
- y, sticky, starts search from the beging of lastindex property
- u, unicode, expression assume individual characters
### Grouping and Capturing
parentheses are used to groupa part of a regular expression together
### Bracket Expressions
indicates a set of characters to match, allows a match of any single character within them
### Greedy and Lazy Match
greedy, matches with as many as possible and lazy, which matches with as few as possible
### Boundaries
the places between characters. Used in combination with \w will be the space between words
### Back-references
allows call backs on stored matches
### Look-ahead and Look-behind
- Lookahead, (?=foo), asserts that foo will immediately follow current position
- Lookbehind, (?<=foo), foo preceeds current position
- Negative Lookahead, (?!foo), foo does not immediately follow current position
- Negative Lookbehind, (?<!foo), foo does not immediately preceed current position
## Author
- [Kevin-Wenner](github.com/Kevin-Wenner)

