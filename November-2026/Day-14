
# Day 14 - Common Prefix and Suffix

## 1. Longest Common Prefix
- **Technique:** Horizontal String Comparison
- **Approach:** Select the first string as the reference and compare its characters with the corresponding positions in all remaining strings. Stop at the first mismatch or when a string ends, then construct the common prefix.
- **Time Complexity:** O(N × L)
- **Auxiliary Space:** O(L)
- **Edge Case:** All strings begin with different characters, resulting in an empty prefix.

## 2. Longest Common Suffix
- **Technique:** Reverse Index Comparison
- **Approach:** Start from the last character of each string and compare corresponding positions across all strings. Store matching characters and manually reverse them to obtain the suffix in its original order.
- **Time Complexity:** O(N × L)
- **Auxiliary Space:** O(L)
- **Edge Case:** The strings have different lengths and one string is shorter than the matching suffix.

## 3. Check If Prefix of String
- **Technique:** Linear Prefix Validation
- **Approach:** Verify that the proposed prefix does not exceed the original string length. Traverse the prefix and compare each character with the corresponding position in the original string, stopping immediately when a mismatch occurs.
- **Time Complexity:** O(P)
- **Auxiliary Space:** O(1)
- **Edge Case:** The prefix is longer than the original string or contains a character that differs at the first position.

## Learning Outcomes
- Developed an understanding of common character sequences.
- Practised comparing multiple strings using nested loops.
- Learned backward indexing for suffix identification.
- Applied manual character matching without built-in shortcuts.
- Understood early termination during string comparison.
- Improved index handling and boundary validation.

## Restrictions Followed
- No os.path.commonprefix().
- No zip(*strs).
- Used explicit loops for character comparisons.
- Used backward indexing for suffix detection.
- No reverse slicing or reversed().
- Used manual character processing.
- Used lists and join() for result construction.
- Avoided external libraries and prohibited shortcuts.

## Key Takeaways
- Prefix matching begins from the first character.
- Suffix matching begins from the last character.
- Both approaches stop immediately when a mismatch occurs.
- Prefix validation requires checking only the proposed prefix length.
- Manual indexing provides control over comparison and termination.
