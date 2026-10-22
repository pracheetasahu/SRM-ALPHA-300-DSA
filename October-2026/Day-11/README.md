# Day 11 — Fixed-Size Sliding Window

**Language:** Python

### 1. Maximum Average Subarray I — LeetCode 643
- **Approach:** Calculate the first window's sum, then slide the window by subtracting the outgoing element and adding the incoming element. Track the maximum sum and divide by `k`.
- **Time Complexity:** O(n)
- **Space Complexity:** O(1)
- **Edge Case:** The window size equals the array length.

### 2. Max Sum Subarray of Size K — GeeksforGeeks
- **Approach:** Maintain a running sum for each window of size `k` and update the maximum whenever a larger sum is found.
- **Time Complexity:** O(n)
- **Space Complexity:** O(1)
- **Edge Case:** All elements have the same value.

### 3. Mean of Array After Removing Some Elements — LeetCode 1619
- **Approach:** Count element frequencies, remove the smallest and largest 5% of values, and calculate the mean of the remaining elements without built-in sorting.
- **Time Complexity:** O(n + U), where U is the value range.
- **Space Complexity:** O(U)
- **Edge Case:** All elements have the same value.

### Restrictions Followed
- Did not calculate `sum(nums[i:i+k])` inside a loop.
- Used a running sum for fixed-size windows.
- Avoided built-in sorting in the third problem.
