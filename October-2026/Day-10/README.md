# Day 10 — Two Pointers from Both Ends

**Language:** Python

### 1. Merge Sorted Array — LeetCode 88
- **Approach:** Compare the largest remaining elements of both sorted arrays and place the larger value at the end of `nums1`. Continue backward until all elements from `nums2` are merged.
- **Time Complexity:** O(m + n)
- **Space Complexity:** O(1) auxiliary space
- **Edge Case:** One of the arrays is empty.

### 2. Squares of a Sorted Array — LeetCode 977
- **Approach:** Compare the squares of the leftmost and rightmost elements and fill a new result array from the end with the larger square.
- **Time Complexity:** O(n)
- **Space Complexity:** O(n)
- **Edge Case:** The input contains only negative numbers or is empty.

### 3. Sort Array By Parity — LeetCode 905
- **Approach:** Use two pointers from opposite ends. Move past correctly placed even and odd values and swap elements that are on the wrong sides.
- **Time Complexity:** O(n)
- **Space Complexity:** O(1) auxiliary space
- **Edge Case:** All elements are even or all are odd.

