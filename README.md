# Regex Tutorial

## Summary
I will be review an email to this tutorial over Regex

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
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ for an email


## General Summary
- First Section /^([a-z0-9_\.-]+) is looking for a combination of literal characters
- Second Section @([\da-z\.-]+) is looking for another combination of literal characters for the domain name
- Third section ([a-z\.]{2,6})$/ is looking for the closing unit of the email such as the .com, .edu


## Breakdown : First Section /^([a-z0-9_\.-]+)

/^ - starting the regex

() - encapsolates the first section
[] - allows for rules to be written inside
a-z - search for any chars between a through z
0-9 - search for any chars between 0 through 9
_ - search for any underscores
\. - this is a hard stop to allow for a new search to be created within the first section
- - hyphen was place by itself to be allowed to be a search able perameter in the email ID
+ match the preceding character one or more times


## Breakdown : Second Section @([\da-z\.-]+)

@ - this is a require part of the pattern and will be looked for. 

() - encapsolates the second session section
[] - allows for rules to be written inside
\d - looking for just a-z
a-z - search for any chars between a through z
\. - this is a hard stop to allow for a new search to be created within the second section
- - looking for a hyphen in section
+ match the preceding character one or more times






A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)