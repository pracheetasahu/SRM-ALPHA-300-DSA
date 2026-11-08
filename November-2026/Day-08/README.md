
# Day 8 - Reverse Operations

## Problems Solved

### 1. Reverse Words in a String
- Technique: Manual Word Extraction and Two Pointers
- Approach: Traverse the input and extract words manually without using split(). Store the words in a list and reverse their order using two pointers before joining them with single spaces.
- Time Complexity: O(n)
- Auxiliary Space: O(n)
- Edge Case: Input contains multiple spaces or only whitespace.

### 2. Reverse String II
- Technique: Two Pointers and Segment Reversal
- Approach: Convert the string into a character list and process blocks of 2k characters. Reverse the first k characters of each block using two pointers.
- Time Complexity: O(n)
- Auxiliary Space: O(n)
- Edge Case: The remaining characters are fewer than k.

### 3. Reverse Only Letters
- Technique: Two Pointers and Character Classification
- Approach: Place two pointers at opposite ends of the string. Skip non-letter characters and swap only English letters until the pointers meet.
- Time Complexity: O(n)
- Auxiliary Space: O(n)
- Edge Case: The string contains only special characters or digits.

## Learning Outcomes
- Practised manual string reversal.
- Learned to extract words without split().
- Applied two-pointer swapping techniques.
- Understood partial reversal of string segments.
- Practised ASCII-based English letter identification.
- Learned to preserve non-letter characters during reversal.

## Restrictions Followed
- Did not use s[::-1].
- Did not use reversed().
- Did not use s.split()[::-1].
- Did not use str.translate().
- Used manual traversal and two-pointer techniques.
- Used character lists for in-place-style swapping.
- Used join() to construct the final strings.
