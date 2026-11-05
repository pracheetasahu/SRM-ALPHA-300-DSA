# Day 5 – Palindromes (Two Pointers)

## 1. Valid Palindrome
- **Technique:** Two Pointers + Character Transformation
- **Approach:** Start pointers at both ends. Skip non-alphanumeric characters, convert uppercase letters to lowercase manually using ASCII values, and compare the characters while moving inward.
- **Time Complexity:** O(n)
- **Auxiliary Space:** O(1)
- **Edge Case:** Empty string or a string containing only spaces and symbols returns True.

## 2. Palindrome Number
- **Technique:** Mathematical Reversal of Half the Number
- **Approach:** Reject negative numbers and numbers ending in zero (except zero itself). Reverse only half the digits using modulo and integer division, then compare both halves.
- **Time Complexity:** O(log n)
- **Auxiliary Space:** O(1)
- **Edge Case:** Negative numbers and numbers ending in zero are not palindromes.

## 3. Count Palindromic Substrings
- **Technique:** Expand Around Center + Two Pointers
- **Approach:** Check every possible odd-length and even-length center. Expand outward while both characters match and increase the count for every valid palindrome.
- **Time Complexity:** O(n²)
- **Auxiliary Space:** O(1)
- **Edge Case:** Repeated characters such as "aaa" produce overlapping palindromic substrings.

## Learning Outcomes
- Practiced two-pointer traversal from both ends.
- Learned to check palindromes without string reversal.
- Practiced ASCII-based lowercase conversion.
- Learned mathematical digit reversal.
- Understood odd and even palindrome centers.
- Practiced Expand Around Center.

## Restrictions Followed
- No s[::-1] used.
- No reversed() used.
- No string-based number reversal.
- No unnecessary library imports.
- Two-pointer comparisons implemented manually.
- Only primitive data structures used.
