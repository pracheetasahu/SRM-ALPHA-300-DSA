
# Day 9 - Reverse by Chunks / Per-Word

## Problems Solved

### 1. Reverse Words in a String III
- Technique: Word Boundary Detection and Two Pointers
- Approach: Traverse the character list and identify each word using spaces as boundaries. Reverse the characters of each word independently using two pointers while maintaining the original word order.
- Time Complexity: O(n)
- Auxiliary Space: O(n)
- Edge Case: A sentence contains a single word or multiple spaces between words.

### 2. Reverse Prefix of Word
- Technique: Prefix Reversal and Two Pointers
- Approach: Find the first occurrence of the given character. Reverse all characters from the beginning of the word up to that position using two pointers. Return the original string if the character is absent.
- Time Complexity: O(n)
- Auxiliary Space: O(n)
- Edge Case: The target character does not exist in the word.

### 3. Reverse Vowels of a String
- Technique: Two-Pointer Selective Reversal
- Approach: Start pointers from both ends of the string. Skip non-vowel characters and swap only vowels until the pointers meet, preserving all other character positions.
- Time Complexity: O(n)
- Auxiliary Space: O(n)
- Edge Case: The string contains no vowels or only one vowel.

## Learning Outcomes
- Practised reversing individual words without changing their order.
- Learned to identify word boundaries during traversal.
- Applied two pointers to reverse a selected prefix.
- Understood selective character reversal.
- Practised identifying vowels in both uppercase and lowercase.
- Improved character-list manipulation and string construction.

## Restrictions Followed
- Did not use reverse slicing.
- Did not use reversed().
- Did not use list comprehension with [::-1].
- Used manual loops and two-pointer swapping.
- Used character lists for modification.
- Used join() to construct the final strings.
- Avoided external libraries and prohibited shortcuts.
