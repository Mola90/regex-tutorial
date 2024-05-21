# Title Regular Expressions, a brief explenation

Regular expressions or regex for short is an arrangement of characters and symbols that define a search parameter.
unlike other methods found in JavaScript which requrie exact matches, regular expressions allow for for complex and 
search queries.

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.
One popular regular expression found in industry is the regex for matching an email. For this reason I be describing all the parts of this expression.
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

The email match expression starts of with caret symbol. This symbol is known as a position anchor and is use to 
assert that the any matches found need to start at this point.
### Quantifiers
Qunatifiers specify how many times a proceding element should be matched. In our example we + quantifier which means match
patterns one or more times.

### OR Operator

### Character Classes

### Flags

### Grouping and Capturing
Grouping is used to group parts of a pattern together. In our example the brackets are stating that lower case letters
a/z, digits 0-9, _, . and - are allowed in any matches. The email matching regression has a second grouping. In this next
section, the expression is matching the domain part of the email address. It is doing this by matching strings that are 
lower case, between a-z and are allowed to contain dots and hyphens.

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
