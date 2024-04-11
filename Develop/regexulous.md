# Regexulous

A string of characters called a Regular Expression, or Regex for short, is used to match patterns in a string. These expressions may be used in practically any programming language, including JavaScript, and are very helpful for extracting data from text that follows a precise pattern, such as phone numbers, emails, etc.

## Summary

I will be briefly explaining different regular expression, or regex, components. So let's say you want to search for the word 'DOG' using Regex, you would need to input this string of code for it to be possible.
  
```shell	 
\bd?o?g\b	 
```	 
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

Anchors align a string's beginning and ending points. In this instance, to match the beginning of a string, use a Caret '^', and to match end of a string, use the Dollar Sign '$'.

### Quantifiers

You can indicate the number of characters or character classes that need to match using quantifiers. For instance, you can match one or more occurences using a Plus Sign '+', or you can use an Asterisk '*' or a Question Mark '?' to match zero or more occurences of a character and character class.

### OR Operator

OR operator allows you to match either of the specified alternatives. It acts as a logical “or” between different patterns. For example, if we want to find words that contain either "color" or "colour", using the Pipe Symbol '|', we can write colo(u|o)r to match the word in a code.

### Character Classes

You can designate particular character sets that can be utilized in a search pattern by using character classes. To match any number (0–9), for instance, use \d; to match any alphabetic letter (a–zA–Z0-9), use \w.

### Flags

Flags can also be used by regexes to change how they behave. With the help of these flags, you may modify the behavior of the regex, enabling it to match on many lines or making it case-insensitive.

### Grouping and Capturing

Regexes are not limited to matching text strings; they can also capture all or part of a match and group them together. If you wish to save a portion of the matched text for later use, this is helpful. For instance, using the the Parenthases

### Bracket Expressions

Bracket expressions allow you to specify a set of characters that you want to match. You enclose these characters within Square Brackets '[]'.

### Greedy and Lazy Match

A greedy quantifier tries to match as much as possible while still satisfying the pattern, but a lazy quantifier, on the other hand, matches as little as possible while still satisfying the pattern.

### Boundaries

Word boundaries, or just Boundaries, are defined as positions that are either followed by a character and not preceded by one, or that are preceded by a character and not followed by one.

### Back-references

Back-references serve as a functionality enabling the referencing and reusing of text captured by a capturing group within the same regex pattern. This feature offers a robust method for identifying repeated patterns and verifying intricate text structures.

### Look-ahead and Look-behind

The application of look-ahead and look-behind is beneficial in situations where we need to find a pattern that is dependent on the preceding or succeeding context.

## Author

My name is Emilia Stewart, and I am a Full Stack Web Developing student. My GitHub link is [MerlinRose2000](https://github.com/MerlinRose2000), and please feel free to reach out me through my email, [em-rstewart@hotmail.com](mailto:em-rstewart@hotmail.com).
