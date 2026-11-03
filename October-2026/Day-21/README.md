
# Day 21 — Sorting Consolidation + Dutch National Flag

**Programming Language:** Python

### 1. Sort Colors — LeetCode 75
- **Technique:** Dutch National Flag Algorithm
- **Approach:** Use three pointers (low, mid, high) to partition the array into 0s, 1s, and 2s using in-place swapping.
- **Time Complexity:** O(n)
- **Auxiliary Space:** O(1)
- **Special Case:** Array containing only one type of element.

### 2. Wiggle Sort I — LeetCode 280
- **Technique:** Insertion Sort and Swapping
- **Approach:** Sort the array manually using Insertion Sort and swap adjacent elements to achieve the wiggle pattern.
- **Time Complexity:** O(n²)
- **Auxiliary Space:** O(1)
- **Special Case:** Empty array or single-element array.

### 3. Sort Array by Increasing Frequency — LeetCode 1636
- **Technique:** Frequency Counting and Insertion Sort
- **Approach:** Count element frequencies using a dictionary and arrange elements by increasing frequency. For equal frequencies, place larger values first.
- **Time Complexity:** O(n²)
- **Auxiliary Space:** O(k), where k is the number of distinct elements.
- **Special Case:** All elements have equal frequency.

### Learning Outcomes
- Implemented three-way partitioning using the Dutch National Flag algorithm.
- Practiced manual Insertion Sort.
- Learned to create wiggle patterns through swapping.
- Applied frequency counting using dictionaries.
- Implemented custom sorting conditions without built-in sorting functions.

### Restrictions Followed
- Avoided `.sort()` and `sorted()`.
- Used manual Insertion Sort.
- Avoided built-in sorting shortcuts.
- Used manual comparisons, frequency counting, and swapping.
- Implemented all sorting logic from scratch.
