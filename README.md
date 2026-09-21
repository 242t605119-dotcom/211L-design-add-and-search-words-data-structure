# LeetCode 211 - Design Add and Search Words Data Structure

## Problem Description

Design a data structure that supports adding words and searching for words.

The data structure should support two operations:

- `addWord(word)` - Adds a word to the data structure.
- `search(word)` - Searches for a word.

The search also supports the `.` character. The `.` can represent any single character.

## Example

Operations:

```text
addWord("bad")
addWord("dad")
addWord("mad")

search("pad")
search("bad")
search(".ad")
search("b..")
