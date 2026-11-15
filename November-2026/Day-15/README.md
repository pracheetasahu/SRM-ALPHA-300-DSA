
# Day 15 - Pattern Matching (Naive strStr)

## 1. Find the Index of the First Occurrence (strStr)
- Technique: Naive Pattern Matching
- Approach: Traverse every possible starting position in the main string. Compare the pattern character by character using nested loops and return the first matching index.
- Time Complexity: O(n × m)
- Auxiliary Space: O(1)
- Edge Case: The pattern is empty or longer than the main string.

## 2. Repeated Substring Pattern
- Technique: Divisor Checking and Modular Indexing
- Approach: Try possible substring lengths that divide the original string length. Compare every character with the corresponding position in the candidate pattern using modulo indexing to determine whether repetition forms the complete string.
- Time Complexity: O(n²)
- Auxiliary Space: O(1)
- Edge Case: A string cannot be divided into two or more identical repeating substrings.

## 3. Rotate String (via Substring Match)
- Technique: String Concatenation and Naive Pattern Matching
- Approach: Concatenate the original string with itself to represent all circular rotations. Use the manually implemented strStr algorithm to check whether the target string occurs in the combined string.
- Time Complexity: O(n²)
- Auxiliary Space: O(n)
- Edge Case: Both strings are empty or have different lengths.

## Learning Outcomes
- Understood the naive string-matching algorithm.
- Practised nested-loop character comparison.
- Learned how to identify the first occurrence of a substring.
- Applied modular indexing to detect repeated patterns.
- Understood how concatenation represents circular rotations.
- Reused one pattern-matching algorithm in multiple problems.
- Improved early termination and boundary checking.

## Restrictions Followed
- Did not use s.find().
- Did not use s.index().
- Did not use re.search().
- Did not use built-in substring search.
- Implemented pattern matching using nested loops.
- Used modular indexing for repeated substring checking.
- Reused the manual strStr implementation for rotation checking.
- Avoided external libraries and prohibited shortcuts.

## Key Takeaways
- Naive pattern matching checks every possible starting position.
- Nested loops compare the text and pattern character by character.
- Repeated substring patterns must divide the original string length.
- Modulo indexing helps compare repeating character sequences.
- Circular rotations can be represented using the original string concatenated with itself.
