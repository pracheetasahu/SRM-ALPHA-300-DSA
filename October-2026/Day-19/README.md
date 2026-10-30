# Day 19 — Quick Sort

**Date:** October 19, 2026  
**Topic:** Quick Sort and Partitioning Techniques  
**Language:** Python

## Problem 1: Quick Sort
Implemented Quick Sort using both Lomuto and Hoare partition schemes. Practised selecting pivots, partitioning arrays, and recursively sorting the resulting sections.

- **Average Time Complexity:** O(n log n)
- **Worst Time Complexity:** O(n²)
- **Average Space Complexity:** O(log n)
- **Edge Case:** Empty arrays and arrays containing duplicate elements.

## Problem 2: Quick Sort with 3-way Partition
Implemented three-way partitioning to divide the array into elements smaller than, equal to, and greater than the pivot. This approach handles duplicate values efficiently.

- **Average Time Complexity:** O(n log n)
- **Worst Time Complexity:** O(n²)
- **Average Space Complexity:** O(log n)
- **Edge Case:** An array containing only identical elements.

## Problem 3: Kth Largest Element in an Array
Solved LeetCode 215 using Quickselect. Used partitioning to find the target index without sorting the entire array.

- **Average Time Complexity:** O(n)
- **Worst Time Complexity:** O(n²)
- **Auxiliary Space Complexity:** O(1)
- **Edge Case:** An array containing one element with k = 1.

## Key Concepts Learned
- Quick Sort and divide-and-conquer
- Lomuto partition scheme
- Hoare partition scheme
- Three-way partitioning
- Quickselect algorithm
- Finding the kth largest element without full sorting

## Restrictions Followed
- Did not use `sorted()`.
- Did not use `.sort()`.
- Implemented partitioning manually.
- Used recursive Quick Sort and iterative Quickselect
