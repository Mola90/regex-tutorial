# Title: Regular Expressions, a brief explenation

Regular expressions or regex for short is an arrangement of characters and symbols that define a search parameter.
unlike other methods found in JavaScript which require exact matches, regular expressions allow for for complex and 
search queries.

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.
One popular regular expression found in industry is the regex for matching an email. For this reason I will be describing all the parts of this expression.
## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Literals](#Literals)

## Regex Components

### Anchors

The email match expression starts with a caret symbol. This symbol is known as a position anchor and is used to 
indicate that any matches found need to start at this point.

The email match expression also contains '$' which indicates a position anchor specifies the end a match.
### Quantifiers
Quantifiers specify how many times a preceding element should be matched. In our example we use the + quantifier which means match patterns one or more times.

In our regular expression we have 2 quantifiers: + and {2,6}


### Character Classes
Square brackets are used to denote Character classes. Character brackets are used to create character cleasses, which
match any character from a specified set of characters. In our email match expression they are used three times.

In our regular expression there were three character classes:  [a-z0-9_\.-] , [\da-z\.-], [a-z\.]
### Literals
In regular expressions, a literal is a letter, number or symbol that represents exactly what they are. In our expression we have several: '+' and '.'
### Grouping and Capturing
Grouping is used to group parts of a pattern together. In our example the brackets are stating that lower case letters a/z, digits 0-9, _, . and - are allowed in any matches. The email matching expression has a second grouping. In this next section, the expression is matching the domain part of the email address. It is doing this by matching strings that are lower case, between a-z and are allowed to contain dots and hyphens. The last grouping pair is in the expression is for the characters that come after  the dot.  This section allows lowercase letters between a-z are allowed.

In our regular expression there were three pairs of groupings: ([a-z0-9_\.-]+) + ([\da-z\.-]+) + ([a-z\.]{2,6}).
## Author

This brief introduction to regular expression was authored by Molaligne (Mola) Dafa. He is a student at the University of Adelaide's Coding Bootcamp course. As a budding full stack developer he is an eager learner with fantastic problem solving skills. 
You can find out more about Mola through his GitHub account https://github.com/Mola90.
