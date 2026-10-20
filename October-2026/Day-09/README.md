# Day 9 — Two Pointers: Read and Write

**Language:** Python

### 1. Move Zeroes — LeetCode 283
- **Approach:** Use a read pointer to find non-zero elements and a write pointer to place them in the correct positions while preserving order.
- **Time Complexity:** O(n)
- **Space Complexity:** O(1)
- **Edge Case:** An array containing only zeros remains unchanged.

### 2. Remove Duplicates from Sorted Array — LeetCode 26
- **Approach:** Since the array is sorted, compare each element with the last unique element and write new unique values at the next available position.
- **Time Complexity:** O(n)
- **Space Complexity:** O(1)
- **Edge Case:** An array containing only one distinct value returns a length of 1.

### 3. Remove Element — LeetCode 27
- **Approach:** Scan the array and copy each element that is not equal to the target value into the next write position.
- **Time Complexity:** O(n)
- **Space Complexity:** O(1)
- **Edge Case:** If every element equals the target, return 0.
