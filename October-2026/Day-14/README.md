# Day 14 — Sliding Window and Condition Tracking

**Language:** Python

### 1. Max Consecutive Ones III — LeetCode 1004
- **Approach:** Maintain a sliding window and count zeros. Shrink the window whenever the number of zeros exceeds `k`.
- **Time Complexity:** O(n)
- **Space Complexity:** O(1)
- **Edge Case:** `k = 0`, so no zeros can be included.

### 2. Longest Repeating Character Replacement — LeetCode 424
- **Approach:** Track character frequencies and maintain a running maximum frequency. Shrink the window when the number of replacements required exceeds `k`.
- **Time Complexity:** O(n)
- **Space Complexity:** O(1) for the uppercase English alphabet.
- **Edge Case:** All characters are identical or `k = 0`.

### 3. Longest Substring Without Repeating Characters — LeetCode 3
- **Approach:** Store each character's most recent index. When a duplicate occurs inside the current window, move the left pointer past its previous occurrence.
- **Time Complexity:** O(n) average
- **Space Complexity:** O(min(n, Σ))
- **Edge Case:** An empty string returns 0.

### Restrictions Followed
- Avoided `Counter`.
- Maintained frequency counts incrementally.
- Used a running `max_freq` for Character Replacement.
- Updated window boundaries using pointers.
