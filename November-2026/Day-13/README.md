
# Day 13 - Isomorphism (Bijective Dictionary Pattern)

## 1. Isomorphic Strings
- Technique: Bijective Mapping Using Two Dictionaries
- Approach: Create two dictionaries to maintain mappings in both directions between the input strings. Traverse both strings and verify that every character maintains a consistent one-to-one mapping.
- Time Complexity: O(n)
- Auxiliary Space: O(1) for a fixed character set.
- Edge Case: Two different characters in the first string map to the same character in the second string.

## 2. Word Pattern
- Technique: Word-to-Character Mapping
- Approach: Separate the sentence into words and compare each word with its corresponding pattern character. Maintain two dictionaries to ensure that both character-to-word and word-to-character mappings remain consistent.
- Time Complexity: O(n + m), where n is the pattern length and m is the sentence length.
- Auxiliary Space: O(n) for the word list and mapping dictionaries.
- Edge Case: The number of words does not match the number of pattern characters.

## 3. Find and Replace Pattern
- Technique: Pattern Matching with Bijective Dictionaries
- Approach: Check every word against the given pattern using two dictionaries. Maintain mappings in both directions and include only words that satisfy the one-to-one character relationship.
- Time Complexity: O(W × L), where W is the number of words and L is the maximum word length.
- Auxiliary Space: O(L) for the temporary mapping dictionaries.
- Edge Case: A word contains repeated characters in positions where the pattern contains different characters.

## Learning Outcomes
- Understood the concept of isomorphic strings.
- Learned one-to-one and reverse character mapping.
- Practised dictionary-based pattern matching.
- Applied bijective mapping to words and characters.
- Understood why two dictionaries are required.
- Improved dictionary lookup and traversal skills.

## Restrictions Followed
- Did not use zip().
- Did not use zip() combined with set() tricks.
- Built two dictionaries explicitly.
- Checked mappings in both directions.
- Used manual index-based traversal.
- Avoided collections.Counter and external libraries.
- Used dictionary membership checks for consistency.

## Key Concept
A valid bijection requires:
1. One source character maps to only one target.
2. One target character maps back to only one source.
3. Both mappings remain consistent throughout traversal.
