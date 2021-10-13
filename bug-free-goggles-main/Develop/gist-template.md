# Title (replace with your title)

Introductory paragraph (replace this with your text)

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

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
Matching an Email – 
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

### Anchors
^ anchor starts line
$ anchor ends line
### Quantifiers
first + is to match [a-z0-9_\.-] one or more times
second + is to match [\da-z\.-] one or more times
{} is to match {2,6} exactly
### OR Operator
none
### Character Classes
[\da-z\.-] matches a single character that is a digit
### Flags
no flags
### Grouping and Capturing
([a-z0-9_\.-]+) parentheses create a capturing group
([\da-z\.-]+) parentheses create a capturing group
([a-z\.]{2,6}) parentheses create a capturing group
### Bracket Expressions
[a-z0-9_\.-] matches a string that has an a 
[\da-z\.-] matches a string that has an a
[a-z\.]  matches a string that has an a
### Greedy and Lazy Match
+ in ([a-z0-9_\.-]+) are greedy operators, so they expand the match as far as they can through the provided text.
+ in ([\da-z\.-]+) are greedy operators, so they expand the match as far as they can through the provided text.
### Boundaries
none
### Back-references
none
### Look-ahead and Look-behind
none
## Author

Alexis Vega
10/11/21
https://github.com/axv50/regex-tutorial-17
 https://axv50.github.io/regex-tutorial-17/