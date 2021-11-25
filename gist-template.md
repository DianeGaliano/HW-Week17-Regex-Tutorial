# Regex Tutorial

Introductory paragraph (replace this with your text)

## Summary

A **regex**, which is short for **regular expression**, is a sequence of characters that defines a specific search pattern. 
When included in code or search algorithms, regular expressions can be used to find certain patterns of characters within a string, 
or to find and replace a character or sequence of characters within a string. They are also frequently used to validate input.

For example, the following regular expression can be used to verify that user input is a valid password:
```md
Matching a Hex Value:
`/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`
```

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors
In all regular expressions, a ^ at the beginning of the regular expression indicates we should match only at the beginning of the input string.  Similarly, a $ at the end of your regex is a placeholder for the end of the string.  For example, to require the first character is an uppercase or lowercase letter:
```md
`^#?([a-f0-9]{6}`
```
Similarly, to require the string ends with a lowercase character:
```md
`[a-f0-9]{3})$`
```
### Quantifiers
Quantifiers specify how many instances of a character, group, or character class must be present in the input for a match to be found. The following table lists the quantifiers supported by .NET.

QUANTIFIERS IN REGULAR EXPRESSIONS
|Greedy quantifier|	Lazy quantifier|	Description     |
|   :---------:   | :---------:    |    :-----------:   |
|*|	*?|	Match zero or more times.|
|+|	+?|	Match one or more times.|
|?|	??|	Match zero or one time.|
|{ n }|	{ n }?|	Match exactly n times.|
|{ n ,}|	{ n ,}?|	Match at least n times.|
{ n , m }|	{ n , m }?|	Match from n to m times.|

### Grouping Constructs
|Grouping Constructs| Description   |
|   :----------:    |   :---------: |
|`(`| Represents the start of the group|
|`)`| Represnets the end of the group|
### Bracket Expressions
|Bracket Epressions| Description    |
|   :---------:    |   :----------: |
|`[a-f0-9]{6}`| Represents the letter form a-f, or digital form 0-9 with the length of 6.|
|`[a-f0-9]{3}`| Represents the letter from a-f, or digital form 0-9 with the length of 3.|
### Character Classes
|Character Classes| Description    |
|   :---------:    |   :----------: |
### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
