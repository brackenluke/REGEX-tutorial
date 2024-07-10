# REGEX-tutorial
regex tutuorial md file, read this to understand more about regex

## Summary
Regex, or regular expression, is a series of characters that can define search patterns. Can be used in string-searching algorithms. Mostly used for "find" and "find and replace operations. This technique is used mostly in theorical computer science.

Below is a code string using regex showing a regular expression for an email.

^([a-zA-Z0-9_\-\.]+)@([a-zA-Z0-9_\-\.]+)\.([a-zA-Z]{2,5})$ 

Follow along in the tutorial to learn more.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)


## Regex Components
Regexes are made up of different components. These compents work as a team to define a search pattern. Examples are listed below for the most common components: anchors, character classes, quantifires, and alternation.

### Anchors
^ Matches the beginning of the string
$ Matches the end of the string

/^ABC.*xyz$/
In the above example, you can use this regex to match any string that starts with “ABC” and ends in “xyz”.

### Quantifiers
A Quantifier gives you the ability to specify how many of a character or character class you want to be matched. Using * or +, you can match zero or more occurances of the preceding character or character class, or one or more occurences respectively.


### OR Operator
 Just like in java, the "or" operator works similary. The "or" operator within a regular expression is defined using the |. It will look for components on either sides of the |.

### Character Classes
When using Character Classes, it allows you to define specific groups of characters that you would use for a search pattern. Check the example below.

Use \d to match any digit (0-9), or \w to match any alphanumeric character (a-zA-Z0-9).

### Flags
Flags, or expression flags, change the way an expression is interpreted. For Example, the i flag ignores type case, and the m flag, or multiline flag, will cause the beginning and end anchors to match the start and end of a line.

### Grouping and Capturing
Example: (ABC), or (?:ABC). The first example will capture groups with multiple tokens useful for extracting a substring or using a back reference. (?:ABC), will capture multiple tokens together without creating a capture group.

### Bracket Expressions
Bracket expressions are enclosed in square brackets. They are a regular expression that matches a single character or gathered elements.

### Greedy and Lazy Match
Greedy matches will match and element as many times as possible and lazy matches will match elements as few occurances as possible. 

## Author
Luke Bracken
From San Antonio, learning coding. Contact for any questions https://github.com/brackenluke.
