# Day 18 — Merge Sort

**Date:** October 18, 2026  
**Topic:** Recursive Merge Sort

## Problems Completed

### 1. Merge Sort
- Implemented recursive division and merging without using built-in sorting.
- **Time Complexity:** O(n log n)
- **Space Complexity:** O(n)
- **Edge case:** Empty arrays and single-element arrays.

### 2. Merge Two Sorted Arrays
- Merged two sorted arrays using two pointers and manually appended remaining elements.
- **Time Complexity:** O(n + m)
- **Space Complexity:** O(n + m)
- **Edge case:** One or both input arrays are empty.

### 3. Count Inversions in an Array
- Used modified merge sort to count inversions efficiently.
- Added the number of remaining left-half elements whenever a right-half element was smaller.
- **Time Complexity:** O(n log n)
- **Space Complexity:** O(n)
- **Edge case:** Duplicate elements do not form inversions with each other.

## Key Learning
Merge sort uses divide and conquer. Its merging process can also solve counting problems, such as counting inversions, efficiently.

## Restrictions Followed
- Did not use `sorted()`.
- Did not use `.sort()`.
- Did not use `heapq.merge()`.
- Implemented recursive splitting and merging manually.
