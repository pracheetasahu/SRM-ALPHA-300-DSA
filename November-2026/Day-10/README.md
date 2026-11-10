
# Day 10 - Split, Trim, Rejoin

## Problems Solved

### 1. Length of Last Word
- Technique: Reverse Traversal and Boundary Detection
- Approach: Traverse the string from the end, skip trailing spaces, and count characters until the previous word boundary is reached.
- Time Complexity: O(n)
- Auxiliary Space: O(1)
- Edge Case: Input contains multiple trailing spaces or only one word.

### 2. Shortest Distance to a Character
- Technique: Two-Pass Traversal
- Approach: Perform a left-to-right traversal to calculate distances from previous occurrences. Then perform a right-to-left traversal and update distances using the nearest next occurrence.
- Time Complexity: O(n)
- Auxiliary Space: O(n)
- Edge Case: The target character occurs at the beginning or end of the string.

### 3. Goal Parser Interpretation
- Technique: Manual String Parsing
- Approach: Traverse the command using an index and identify the patterns G, (), and (al). Append their corresponding interpretations to a result list and join the output.
- Time Complexity: O(n)
- Auxiliary Space: O(n)
- Edge Case: Command contains only G or repeated () patterns.

## Learning Outcomes
- Learned to remove trailing spaces through manual traversal.
- Practised extracting the last word without split().
- Understood two-pass distance calculation.
- Applied index-based parsing to interpret encoded commands.
- Compared manual word extraction with built-in split().
- Practised efficient string construction using join().

## Restrictions Followed
- Implemented manual traversal instead of relying only on split().
- Did not use unnecessary string manipulation shortcuts.
- Did not use reversed() or reverse slicing.
- Used loops and index-based conditions.
- Used lists and join() for result construction.
- Avoided external libraries and prohibited shortcuts.
