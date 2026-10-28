# Day 16 — Selection Sort Implementation

**Language:** Python

### 1. Selection Sort — GeeksforGeeks
- **Approach:** Scan the unsorted portion to find the smallest element and swap it with the first unsorted element.
- **Time Complexity:** O(n²)
- **Space Complexity:** O(1)
- **Edge Case:** The input array is already sorted.

### 2. Find K Smallest Elements — Selection Sort
- **Approach:** Perform the first `k` selection-sort passes to place the smallest values at the beginning of the array.
- **Time Complexity:** O(nk)
- **Space Complexity:** O(k) for the result array.
- **Edge Case:** `k = 0`, which returns an empty list.

### 3. Sort Characters By Frequency — LeetCode 451
- **Approach:** Count each character's occurrences using a dictionary, then apply selection sort to arrange distinct characters by decreasing frequency.
- **Time Complexity:** O(n + u²), where `u` is the number of distinct characters.
- **Space Complexity:** O(n + u)
- **Edge Case:** Multiple characters have the same frequency.

### Restrictions Followed
- Did not use `.sort()`, `sorted()`, or `min()`.
- Used manual scanning to find minimum or maximum values.
- Implemented selection sort with loops and swaps.
