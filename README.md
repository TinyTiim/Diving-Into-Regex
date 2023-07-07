# Diving-Into-Regex

This is a helpful tutorial to understand all the different regex patterns better. 

## Summary

Regex is a feature or tool within programming languages that help with pattern matching.

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

Anchors are two characters: '^' and '$'. The caret '^' represents the start position, and the dollar sign '$' represents the end position. These anchors are used to define the position of a pattern within a string.

'^' - Starting

'$' - End


### Quantifiers

Quantifiers allow us to define the number of occurrences of a pattern.

'*' - Pattern matches zero or more times

'+' - Pattern matches one or more times

'?' - Pattern matches zero or once

{} - This allows setting different limits when matching

'{n}' - 'n' Represents the exact number of times that a pattern matches 

'{n, }' 'n' Represents the close to the number of times that a pattern matches 

'{n, x }' 'n' Represents the minimum number of pattern matches, and 'x' represents the maximum



### OR Operator

The OR operator, represented by the '|' symbol, allows for specifying alternative patterns. It matches either the pattern on the left or the pattern on the right.


### Character Classes

Character classes define sets of characters to match. They are enclosed in square brackets '[]' and allow matching any single character within the defined set.

'.' - Matches with any character, excluding; '(\n)

'\d' - Matches with numbers like, '0-9'

'\w' - Matches with characters from the Latin alphabet like, '0-9', 'A-Z', and '_'

'\s' - Matches whitespace characters, including spaces, tabs, and newline characters.


### Flags

Flags are optional parameters that modify the behavior of a regex pattern. They provide additional functionality such as case-insensitive matching ('i' flag) or multiline mode ('m' flag).

'g' -

'i' -

'm' -

### Grouping and Capturing

Parentheses '()' are used for grouping patterns and capturing matched content for later use.

### Bracket Expressions

Bracket expressions '[...]' are similar to character classes but provide more advanced matching options. They allow matching characters based on collating sequences or character properties.

### Greedy and Lazy Match

By default, regex matches are greedy, meaning they try to match as much as possible. Adding a '?' after a quantifier makes it lazy, matching as little as possible.

### Boundaries

Boundaries allow matching specific positions in a string, such as word boundaries or line boundaries.

### Back-references

Back-references allow referring back to a previously captured group within the regex pattern.

### Look-ahead and Look-behind

Look-ahead and look-behind assertions allow checking if a pattern is followed or preceded by another pattern without including it in the actual match.

## Author

Github-TinyTiim
Gmail-Sophia.palomo12@gmail.com
