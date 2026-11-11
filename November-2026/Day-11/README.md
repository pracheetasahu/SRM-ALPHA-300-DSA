
# Day 11 - String Rotation

## Problems Solved

### 1. Rotate String
- Technique: Modular Indexing and Circular Traversal
- Approach: Try every possible starting position in the original string. Compare each character with the goal string using modular indexing to simulate circular rotation.
- Time Complexity: O(n²)
- Auxiliary Space: O(1)
- Edge Case: Both strings are empty or have different lengths.

### 2. Shift 2D Grid
- Technique: Array Flattening and Modular Mapping
- Approach: Convert the 2D grid into a 1D list. Move each element to its new position using (index + k) % total, then reconstruct the original grid dimensions.
- Time Complexity: O(m × n)
- Auxiliary Space: O(m × n)
- Edge Case: A grid containing only one element or a shift value larger than the total number of elements.

### 3. Rotate String by K
- Technique: Direct Index Mapping
- Approach: Reduce k using modulo string length and calculate the destination index for every character. Place each character into its rotated position and join the result.
- Time Complexity: O(n)
- Auxiliary Space: O(n)
- Edge Case: k is zero, greater than the string length, or the string is empty.

## Learning Outcomes
- Understood circular string traversal.
- Practised modular arithmetic for rotation.
- Learned to check rotations without concatenation shortcuts.
- Applied flattening and reconstruction of 2D arrays.
- Understood the difference between checking a rotation and performing a rotation.
- Improved index mapping and array manipulation skills.

## Restrictions Followed
- Did not use s in (s + s).
- Did not use reverse slicing.
- Did not use reversed().
- Used modular index calculations.
- Used manual loops for character placement.
- Used lists and join() for string construction.
- Avoided external libraries and prohibited shortcuts.
