# Basic Regular Expression "Regex"

A regular expression (shortened as regex or regexp; sometimes referred to as rational expression) is a sequence of characters that specifies a match pattern in text. Usually such patterns are used by string-searching algorithms for "find" or "find and replace" operations on strings, or for input validation.

## Summary

Basic regular expressions (regex) are a fundamental tool for pattern matching and manipulation of text. They are commonly used in programming and text processing tasks. 

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
Anchors are used to specify the position in the string where a match should occur. ^ anchors to the beginning of the string, and $ anchors to the end.

### Quantifiers
Quantifiers modify how many times a character or group should be matched. Some common quantifiers are * (zero or more), + (one or more), ? (zero or one), and {n} (exactly n times).

### Grouping Constructs
In regular expressions (regex), grouping constructs, typically represented by parentheses (), serve several important purposes.  Grouping constructs make regex more powerful and flexible by allowing you to structure and control the matching process with greater precision. They are especially useful when you need to capture specific portions of text, create alternatives, or apply modifiers to complex patterns

### Bracket Expressions
Bracket expressions, also known as character classes, are a fundamental concept in regular expressions (regex). They are enclosed within square brackets [ ] and allow you to define a set of characters or character ranges that should match a single character position within a string.  Bracket expressions are very useful when you need to match characters based on specific criteria, such as letters, digits, or custom character sets. They provide a compact and efficient way to specify character patterns in regex patterns.

### Character Classes
Character classes, often enclosed in square brackets [ ], are a crucial aspect of regular expressions (regex) that allow you to define sets of characters to match a single character position within a string. They are used to specify which characters are acceptable at a particular position in a regex pattern.  Character classes are useful for specifying which characters you want to match in your regex patterns. They provide a concise and efficient way to define character patterns, making it easier to work with complex text processing tasks.

### The OR Operator
In regular expressions (regex), the OR operator, often represented as the vertical bar |, allows you to specify alternatives within a pattern. It allows you to match one of multiple alternatives.  The OR operator is useful for specifying multiple alternatives within a regex pattern. It allows you to handle situations where you need to match different strings or patterns in your input text. By grouping alternatives within parentheses, you can create more complex conditions and accurately capture the text you're interested in.

### Flags
In regular expressions (regex), flags are modifiers that can be added to the end of a regex pattern to control how the pattern matching is performed. These flags influence the behavior of the regex engine and enable various options.  The availability of these flags and their syntax can vary between programming languages and regex libraries. It's essential to consult the documentation of the specific regex library you are using to understand the flags and their usage. Flags provide flexibility in customizing regex behavior to suit the specific needs of your pattern matching tasks.

### Character Escapes
In regular expressions (regex), character escapes are sequences of characters that have a special meaning and are used to match specific characters or character categories. These escapes are introduced by a backslash \, and they are often used to match characters that would otherwise be interpreted as metacharacters in the regex pattern.  Character escapes are useful for matching specific characters or character classes without triggering their special meanings as metacharacters within the regex pattern. They allow you to work with a wide range of characters, including those with special roles in regex, in a precise and controlled manner.

## Author
Doug Gouthro

It was in the mid 90’s that I first realized that I was interested in computers. I was 11 or 12 years old when I first saw the movie "Hackers'' starring Jonny Lee Miller, Angelina Jolie, and Matthew Lillard. After seeing the movie I was hooked, I started spending all my time in the computer lab at school, I would read the Windows 95 manual while on lunch, I would even make my own laptops out of Legos and wood. As I got older my passion for computers and coding would dwindle but it never disappeared, I toyed around with HTML while styling my Myspace page. Fast forward to now and I'm finally starting my journey in coding and web development.  Please feel free to visit my portfolio and Github pages.

Portfolio - https://douggouthro.github.io/DougsPortfolio/
Github - https://github.com/DougGouthro