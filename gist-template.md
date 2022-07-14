# Matching an Email Regular Expression Tutorial

In this gist file, there is a tutorial on the matching email regular expression. There is a summary section, which briefly summarizes the regular expression. Then there are more specifics which have clickable links in the table of contents. 

## Summary

Matching an Email – `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`. This regular expression has all the components which match the components of an email. The following, more specific components explain the regular expression more thoroughly.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)

## Regex Components

### Anchors
The anchors here are ^ and $. They start and end the string for verification.

### Quantifiers
The quantifiers here are the last set of curly brackets and the `+` sign which connects the email. For example johndoe123@gmail.com would be broken down into "johndoe123" `+` "@gmail" `+` ".com". `{2, 6}` means the very last set of letters, `([a-z\.]`, is between 2 and 6 characters.

### Character Classes
The character class in this regex is the `\d` one. This matches any arabic numeral digit and is equivalent to `[0-9]`.

### Grouping and Capturing
There are three groups within this regex separated by the `+` sign. The first group is `/^([a-z0-9_\.-]` which starts the regex with the `^` anchor and captures the email name, for example `johndoe123`. The second group is `@([\da-z\.-]` which captures the email association, for example `@gmail`. The third and last group is the `\.([a-z\.]{2,6})$/` one, which captures the dot association, for example `.com`.

### Bracket Expressions

### Greedy and Lazy Match


## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
