# Day 15 — Bubble Sort Implementation

**Language:** Python

### 1. Bubble Sort
- **Approach:** Compare adjacent elements using nested loops and swap them when they are out of ascending order. Each pass moves the largest remaining element to the end.
- **Time Complexity:** O(n²)
- **Space Complexity:** O(1)
- **Edge Case:** An empty array requires no sorting.

### 2. Bubble Sort with Early-Exit Optimization
- **Approach:** Use a swap flag during each pass. If no swaps occur, stop immediately because the array is already sorted.
- **Best-Case Time:** O(n)
- **Worst-Case Time:** O(n²)
- **Space Complexity:** O(1)
- **Edge Case:** The input is already sorted.

### 3. Sort Array By Parity Using Bubble Sort
- **Approach:** Compare adjacent elements and swap whenever an odd number appears before an even number. Repeat passes until the even numbers are placed first.
- **Time Complexity:** O(n²)
- **Space Complexity:** O(1)
- **Edge Case:** All elements have the same parity.

### Restrictions Followed
- Did not use `sort()` or `sorted()`.
- Implemented Bubble Sort using nested loops.
- Used manual swapping of adjacent elements.
