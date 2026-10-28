# Day 17 — Insertion Sort Implementation

**Language:** Python

### 1. Insertion Sort — GeeksforGeeks
- **Approach:** Take each element as the key, shift larger elements to the right, and insert the key into its correct position in the sorted portion.
- **Best-Case Time:** O(n)
- **Worst-Case Time:** O(n²)
- **Space Complexity:** O(1)
- **Edge Case:** The input array is already sorted.

### 2. Insertion Sort on Nearly-Sorted Array
- **Approach:** Apply insertion sort to an almost-sorted array. Elements are shifted only when they are greater than the current key.
- **Best-Case Time:** O(n)
- **Worst-Case Time:** O(n²)
- **Space Complexity:** O(1)
- **Edge Case:** Only one pair of adjacent elements is out of order.

### 3. Sort Array with 0, 1, 2 — LeetCode 75
- **Approach:** Use insertion sort to arrange the values in ascending order, placing all zeros before ones and all ones before twos.
- **Best-Case Time:** O(n)
- **Worst-Case Time:** O(n²)
- **Space Complexity:** O(1)
- **Edge Case:** The array contains only one distinct value.

### Restrictions Followed
- Did not use `.sort()`, `sorted()`, or `bisect.insort()`.
- Shifted elements manually using a loop.
- Inserted each key into its correct position.
