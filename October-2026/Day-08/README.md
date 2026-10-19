# Day 8 — Two Pointers from Ends

**Language:** Python

### 1. Valid Palindrome — LeetCode 125
- **Approach:** Use two pointers from both ends, skip non-alphanumeric characters, and compare lowercase characters.
- **Time Complexity:** O(n)
- **Space Complexity:** O(1) auxiliary space
- **Edge Case:** An empty string or a string containing only spaces is a palindrome.

### 2. Reverse String — LeetCode 344
- **Approach:** Swap characters at the left and right pointers until they meet or cross.
- **Time Complexity:** O(n)
- **Space Complexity:** O(1) auxiliary space
- **Edge Case:** A single-character array remains unchanged.

### 3. Reverse Vowels of a String — LeetCode 345
- **Approach:** Move two pointers inward, skip consonants, and swap vowels while preserving all other characters.
- **Time Complexity:** O(n)
- **Space Complexity:** O(n) auxiliary space
- **Edge Case:** A string with no vowels remains unchanged.
