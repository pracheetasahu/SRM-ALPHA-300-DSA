
# Day 22 — Classic Binary Search

**Programming Language:** Python

### 1. Binary Search — LeetCode 704

- **Technique:** Iterative Binary Search
- **Approach:** Maintain low and high pointers and repeatedly calculate the middle index. Compare the middle element with the target and eliminate half of the search space.
- **Time Complexity:** O(log n)
- **Auxiliary Space:** O(1)
- **Special Case:** Empty array or target not present.

### 2. Search Insert Position — LeetCode 35

- **Technique:** Modified Binary Search
- **Approach:** Apply binary search to find the target. If it does not exist, return the low pointer as the correct insertion position.
- **Time Complexity:** O(log n)
- **Auxiliary Space:** O(1)
- **Special Case:** Target smaller than all elements or greater than all elements.

### 3. First Bad Version — LeetCode 278

- **Technique:** Binary Search on Versions
- **Approach:** Search between version 1 and n. If the middle version is bad, move the high pointer to mid; otherwise, move low to mid + 1. Return the first bad version.
- **Time Complexity:** O(log n)
- **Auxiliary Space:** O(1)
- **Special Case:** First version is bad or last version is the first bad version.

### Learning Outcomes

- Understood the working principle of Binary Search.
- Practiced calculating the midpoint manually.
- Learned to eliminate half of the search space in every iteration.
- Applied binary search to find insertion positions.
- Used binary search to identify the first bad version.
- Improved understanding of logarithmic time complexity.

### Restrictions Followed

- Avoided `bisect`.
- Avoided `bisect_left` and `bisect_right`.
- Implemented binary search manually.
- Used `low + (high - low) // 2` for midpoint calculation.
- Used iterative loops and comparisons.
- Implemented all search logic from scratch.
