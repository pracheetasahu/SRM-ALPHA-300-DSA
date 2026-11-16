# Day 16 – Sliding Window on Strings

## Overview

Practised sliding window techniques on strings by maintaining character information incrementally without using Counter or other library shortcuts.

## Problems Completed

### 1. Longest Substring Without Repeating Characters
- Approach: Used a sliding window with a dictionary to track the last occurrence of each character. Moved the left pointer when a repeated character appeared inside the current window.
- Time Complexity: O(n)
- Space Complexity: O(min(n, k))
- Edge Case: A string containing only repeated characters, such as `"bbbbb"`.

### 2. Longest Repeating Character Replacement
- Approach: Maintained character frequencies in a dictionary and expanded or contracted the window depending on the number of replacements required.
- Time Complexity: O(n)
- Space Complexity: O(k)
- Edge Case: A string with all identical characters and k = 0.

### 3. Find All Anagrams in a String
- Approach: Maintained the frequency of characters in the pattern and current window. Updated the window frequency as the pointers moved and compared the frequency dictionaries.
- Time Complexity: O(n × k) in the worst case
- Space Complexity: O(k)
- Edge Case: The pattern is longer than the input string.

## Concepts Practised

- Sliding window on strings.
- Dictionary-based character tracking.
- Incremental frequency updates.
- Expanding and shrinking windows.
- Handling repeated characters.
- Finding anagrams using frequency matching.

## Learning Outcome

Improved understanding of variable-size and fixed-size sliding windows while maintaining character information without relying on external libraries.
