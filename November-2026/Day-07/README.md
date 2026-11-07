
# Day 7 - Character Classification

## Problems Solved

### 1. Check if the Sentence Is Pangram
- Technique: Set Membership
- Approach: Traverse the sentence, manually convert uppercase letters to lowercase, and store English letters in a set. If the set contains 26 letters, the sentence is a pangram.
- Time Complexity: O(n)
- Auxiliary Space: O(1)
- Edge Case: Sentence contains repeated letters but misses one alphabet.

### 2. Number of Segments in a String
- Technique: Boundary Detection
- Approach: Count a segment whenever a non-space character appears at the beginning of the string or immediately after a space.
- Time Complexity: O(n)
- Auxiliary Space: O(1)
- Edge Case: Empty string or string containing only spaces.

### 3. Count Vowels and Consonants
- Technique: Character Classification
- Approach: Manually identify alphabetic characters using character ranges, convert uppercase letters using ASCII, and classify each letter as a vowel or consonant.
- Time Complexity: O(n)
- Auxiliary Space: O(1)
- Edge Case: String contains only digits, spaces, and special characters.

## Learning Outcomes
- Understand manual character classification.
- Use ASCII values with ord() and chr().
- Identify uppercase and lowercase English letters.
- Detect word boundaries using adjacent characters.
- Count vowels and consonants without built-in classification shortcuts.

## Restrictions Followed
- No ch.isalpha() for classification logic.
- No ch.isdigit() for classification logic.
- No str.translate().
- No Counter or external libraries.
- Used manual loops and character comparisons.
