
# Day 23 — Binary Search on Answer

**Programming Language:** Python

### 1. Sqrt(x) — LeetCode 69

- **Technique:** Binary Search on Answer
- **Approach:** Search for the largest integer whose square is less than or equal to x. Store the valid midpoint and continue searching the right half to find the integer square root.
- **Time Complexity:** O(log x)
- **Auxiliary Space:** O(1)
- **Special Case:** x = 0 or x = 1.

### 2. Guess Number Higher or Lower — LeetCode 374

- **Technique:** Binary Search with API Condition
- **Approach:** Use the guess API to compare the middle value with the hidden number. Eliminate half of the search space based on whether the guess is higher, lower, or correct.
- **Time Complexity:** O(log n)
- **Auxiliary Space:** O(1)
- **Special Case:** Hidden number is the first or last possible number.

### 3. Valid Perfect Square — LeetCode 367

- **Technique:** Binary Search with Square Condition
- **Approach:** Calculate the square of the middle value and compare it with the given number. Search the appropriate half until an exact square is found or the search space becomes empty.
- **Time Complexity:** O(log n)
- **Auxiliary Space:** O(1)
- **Special Case:** Number is 1 or is not a perfect square.

### Learning Outcomes

- Understood the concept of Binary Search on Answer.
- Practiced building condition checks inside binary search.
- Implemented integer square root without built-in functions.
- Used API-based comparisons to find a hidden number.
- Learned to identify perfect squares using binary search.
- Improved understanding of logarithmic time complexity.

### Restrictions Followed

- Avoided `bisect`.
- Avoided `math.isqrt()`.
- Used manual binary search implementation.
- Calculated midpoint using `low + (high - low) // 2`.
- Built condition checks manually.
- Implemented all searching logic from scratch.
