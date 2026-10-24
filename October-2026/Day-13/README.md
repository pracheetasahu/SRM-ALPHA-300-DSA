# Day 13 — Sliding Window and Hashmap

**Language:** Python

### 1. Contains Duplicate II — LeetCode 219
- **Approach:** Store the most recent index of each number in a dictionary. If the same number appears again within distance `k`, return `True`.
- **Time Complexity:** O(n) average
- **Space Complexity:** O(n)
- **Edge Case:** Duplicate values exist, but their indices are farther apart than `k`.

### 2. Find All Anagrams in a String — LeetCode 438
- **Approach:** Maintain character-frequency dictionaries for the target string and the current fixed-size window. Update the counts as the window moves and record matching starting indices.
- **Time Complexity:** O(n + m) average for a bounded character set
- **Space Complexity:** O(m + Σ)
- **Edge Case:** The pattern is longer than the input string.

### 3. Permutation in String — LeetCode 567
- **Approach:** Use a fixed-size sliding window and update character frequencies incrementally. Return `True` when a window has the same character counts as the target string.
- **Time Complexity:** O(n + m) average for a bounded character set
- **Space Complexity:** O(m + Σ)
- **Edge Case:** The target string is longer than the source string.

### Restrictions Followed
- Avoided `Counter`.
- Maintained dictionary counts incrementally.
- Used a sliding window for the string problems.
