
# Day 24 — Binary Search Variants

**Programming Language:** Python

### 1. Find First and Last Position — LeetCode 34

- **Technique:** First and Last Occurrence Binary Search
- **Approach:** Perform binary search twice. Find the first occurrence by continuing towards the left after a match and find the last occurrence by continuing towards the right.
- **Time Complexity:** O(log n)
- **Auxiliary Space:** O(1)
- **Special Case:** Target is absent or appears only once.

### 2. Count Occurrences of Element — GeeksforGeeks

- **Technique:** Binary Search with First and Last Occurrence
- **Approach:** Find the first and last positions of the target using two binary searches. Calculate the total occurrences using the difference between the positions.
- **Time Complexity:** O(log n)
- **Auxiliary Space:** O(1)
- **Special Case:** Target does not exist in the array.

### 3. Floor and Ceiling in Sorted Array

- **Technique:** Modified Binary Search
- **Approach:** Use separate binary searches to find the greatest element smaller than or equal to the target and the smallest element greater than or equal to the target.
- **Time Complexity:** O(log n)
- **Auxiliary Space:** O(1)
- **Special Case:** Target is smaller than the minimum element or greater than the maximum element.

### Learning Outcomes

- Understood first and last occurrence binary search.
- Practiced finding duplicate elements in sorted arrays.
- Learned to count occurrences without linear traversal.
- Implemented floor and ceiling using binary search.
- Improved understanding of modified binary search techniques.
- Practiced logarithmic-time searching.

### Restrictions Followed

- Avoided `bisect_left` and `bisect_right`.
- Implemented first and last occurrence manually.
- Used `low + (high - low) // 2` for midpoint calculation.
- Used iterative binary search.
- Implemented all searching logic from scratch.
