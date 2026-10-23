# Day 12 — Variable-Size Sliding Window

**Language:** Python

### 1. Minimum Size Subarray Sum — LeetCode 209
- **Approach:** Expand the window by adding elements. Whenever the sum reaches the target, update the minimum length and shrink the window from the left.
- **Time Complexity:** O(n)
- **Space Complexity:** O(1)
- **Edge Case:** No subarray reaches the target, so return 0.

### 2. Longest Subarray with Sum K — GeeksforGeeks
- **Approach:** Expand the window and maintain a running sum. Shrink the window whenever the sum exceeds `k`, then track the longest window with sum equal to `k`.
- **Time Complexity:** O(n)
- **Space Complexity:** O(1)
- **Edge Case:** No subarray has sum `k`.
- **Note:** This sliding-window solution assumes non-negative array elements. If negative values are allowed by the judge, a prefix-sum approach is required.

### 3. Fruit Into Baskets — LeetCode 904
- **Approach:** Maintain a frequency dictionary for the current window. When more than two distinct fruit types appear, shrink the window until only two remain.
- **Time Complexity:** O(n)
- **Space Complexity:** O(1) auxiliary space for at most two fruit types in the window.
- **Edge Case:** All fruits are the same type.

### Restrictions Followed
- Avoided `sum()` on array slices.
- Maintained running window sums.
- Used a left pointer to shrink invalid windows.
