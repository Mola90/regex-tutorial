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
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [literals](#literals)

## Regex Components

### Anchors

The email match expression starts of with caret symbol. This symbol is known as a position anchor and is use to 
assert that the any matches found need to start at this point.

The email match expression also contains $ which indicates a position anchor indicating the end of possible matches.
### Quantifiers

Qunatifiers specify how many times a proceding element should be matched. In our example we + quantifier which means match patterns one or more times.

In our regular expression we have 2 quantifiers: + and {2,6}


### Character Classes
square brackets are used to donote character classes. Character brackets are use to create character cleasses, which
match any character from a specified set of characters. In our email match expression they are used 3  times.

In our regular expression there were three character classes:  [a-z0-9_\.-] , [\da-z\.-], [a-z\.]
### literals
In regular expressions, a literal is a letter, number or symboll that represent exactly what they are. In our expression we have 
several: + and .
### Grouping and Capturing
Grouping is used to group parts of a pattern together. In our example the brackets are stating that lower case letters a/z, digits 0-9, _, . and - are allowed in any matches. The email matching regression has a second grouping. In this next section, the expression is matching the domain part of the email address. It is doing this by matching strings that are lower case, between a-z and are allowed to contain dots and hyphens. The last grouping pair is in the expression is for the characters that come after the the dot.  this section states lower
case letters between a-z are allowed.

In our regular expression there were three pairs of groupings: ([a-z0-9_\.-]+) + ([\da-z\.-]+) + ([a-z\.]{2,6}).
## Author

This brief introduction to regular expression was authored by Molaligne (Mola) Dafa. He is a student at the University of Adelaides Coding Bootcamp course. As a budding full stack developer he is an eager learner with fantastic problem solving skills. 
You can find out more about Mola through his GitHub account https://github.com/Mola90.
