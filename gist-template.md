# Regex-Gist

In this assignment I will create a Github Repository which will function as a Gist to discuss what I have learned in researching Regex's or Regular Expressions.

Regular Expressions are defined on the web as patterns used to match character combinations in strings.

As I understand it, Regular Expressions are essentially used to search through a given document or any given text.

## Summary

One example of a commonly used JavaScript Regular Expression is the test() method.

The Base Code Snippet for this Method can be given as: RegExpObject.test(string) where the (string) would be replaced with the text you are searching through.

This method essentially tests for a match in string.

It will return either True or False depending upon the results.

This Regex can be combined with some of the other common Regex Components below which can be used in addition to further expand the search or narrow results.

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

Below you will see a brief summary of some of the major and most common Regex Components.

These components can be used within Regular Expressions to expand the search criteria.

### Anchors

Anchors are used to search within a specific position of a string.

Examples of such anchors are the `^` anchor which matches with characters at the very start of the string. As well as the `$` which does the same for the last.

An example of usage for this would be if you only wanted to search for a matching instance that was used at the very start or very end of the string.

### Quantifiers

Quantifiers are used to search for instances of a specific number of occurrences.

The ? (question mark) quantifier for example is used in matching instances with zero or one occurrence of the preceding pattern.

By that logic it would not return instances more than one.

### Grouping Constructs

Grouping constructs are used in searching when you need to group characters together.

They are denoted by the use of ().

An example of usage for these constructs would be when you have want to expand a search by looking for additional characters.

### Bracket Expressions

Bracket expressions are denoted by square brackets and can include individual characters or ranges of characters.

It is essentially just another formatting for searching in expressions.

### Character Classes

Character classes are used to match specific types of characters.

On example of such is the `\s` Character Class which Matches any whitespace character.

Whitespace characters are those which alter the spacing of the document. For example the enter key creates a new line, the tab key creating an indent.

The `\s` Class is used to search for instances where these characters are used.

### The OR Operator

The OR operator, denoted by `|`, is used in evaluating a boolean. If any instance of true is returned it will evaluate the boolean as true even if the other instance is false.

### Flags

Flags are used to create specific search parameters within a given Regex.

One example of such a flag is the `i` flag which is used to indicate Case-insensitive matching. This treats both Uppercase and Lowercase letters as being the same.

### Character Escapes

Character escapes as I understand them are used in Regular Expressions to search for special characters such as (%,^,&)

A / is required in front of the special characters when searching for them so as to differentiate those characters from any standard use they may have in JS Code.

## Author

Daved Strzykalski
<https://github.com/dstrzykalski>