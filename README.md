# Spreadsheets Similarity

## Problem statement

- Finding cells that have the same intent despite different wordings

### Example

These 2 strings are considered similar:

- The logging in feature is not working
- I am unable to log in

These 2 strings are not considered similar:

- The logging in feature is not working
- Website is too slow

## Research

### String similarity algorithms

- Edit distance-based: The number of edits needed to transform string a to string b
- Token-based: n-grams
- Sequence-based: Matching substrings

## References

- https://towardsdatascience.com/natural-language-processing-for-fuzzy-string-matching-with-python-6632b7824c49
