# Day 6 – Palindrome Variants

## Problem 1: Valid Palindrome II (Allow 1 Deletion)
- **Technique:** Two-Pointer Comparison with Conditional Deletion
- **Approach:** Compare characters using left and right pointers. When a mismatch occurs, test both possible deletions: skip the left character or skip the right character. If either remaining range is a palindrome, return True.
- **Time Complexity:** O(n)
- **Auxiliary Space:** O(1)
- **Edge Case:** A string with two different characters can become a palindrome by deleting either one.

## Problem 2: Longest Palindrome (Count Characters)
- **Technique:** Hash Map Frequency Counting
- **Approach:** Store each character's frequency in a dictionary. Add the largest even count from every character to the result. If at least one odd frequency exists, add one character for the center.
- **Time Complexity:** O(n)
- **Auxiliary Space:** O(k), where k is the number of distinct characters.
- **Edge Case:** Every character appears an odd number of times; only one odd occurrence can be used as the center.

## Problem 3: Palindrome Permutation
- **Technique:** Odd-Frequency Validation
- **Approach:** Count all character occurrences manually using a dictionary. Count how many characters have odd frequencies. A palindrome permutation is possible only when the odd-frequency count is zero or one.
- **Time Complexity:** O(n)
- **Auxiliary Space:** O(k), where k is the number of distinct characters.
- **Edge Case:** Multiple characters have odd frequencies, making a palindrome arrangement impossible.

## Learning Outcomes
- Strengthened two-pointer palindrome checking.
- Practiced handling a single allowed deletion.
- Learned to calculate the maximum palindrome length from character frequencies.
- Understood the odd-frequency condition for palindrome permutations.
- Improved manual dictionary-based character counting.

## Restrictions Followed
- No string slicing reversal.
- No reversed() used.
- No collections.Counter used.
- No Counter arithmetic.
- No unnecessary library imports.
- Manual two-pointer and frequency-counting logic.
- Only primitive data structures used.
