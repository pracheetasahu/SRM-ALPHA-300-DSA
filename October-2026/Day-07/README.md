# Day 7 — Array Rotation

**Language:** Python

### 1. Rotate Array — LeetCode 189
- **Approach:** Reverse the entire array, then reverse the first `k` elements and the remaining elements to rotate right.
- **Time Complexity:** O(n)
- **Space Complexity:** O(1) auxiliary space
- **Edge Case:** `k` equals the array length.

### 2. Rotate Array by K Steps (In-place)
- **Approach:** Use three reversals and reduce `k` using `k % n` before rotating.
- **Time Complexity:** O(n)
- **Space Complexity:** O(1) auxiliary space
- **Edge Case:** `k` is greater than the array length.

### 3. Reverse Array in Groups — GeeksforGeeks
- **Approach:** Reverse each group of `k` elements using two pointers and swaps. Reverse the final group even if it contains fewer than `k` elements.
- **Time Complexity:** O(n)
- **Space Complexity:** O(1) auxiliary space
- **Edge Case:** `k` is greater than or equal to the array length.
