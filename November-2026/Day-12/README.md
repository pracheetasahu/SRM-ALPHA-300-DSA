
# Day 12 - String Compression and Encoding

## 1. String Compression
- Technique: Run-Length Encoding and Two Pointers
- Approach: Traverse consecutive character groups and count their occurrences manually. Write each character followed by its frequency when the frequency is greater than one, modifying the original array.
- Time Complexity: O(n)
- Auxiliary Space: O(log n) for temporary count digits.
- Edge Case: A character occurs more than nine consecutive times.

## 2. Encode and Decode Strings
- Technique: Length-Prefix Encoding
- Approach: Encode each string using its length followed by a delimiter and the original content. During decoding, read the length and extract exactly that many characters to reconstruct the original list.
- Time Complexity: O(n), where n is the total encoded or decoded input size.
- Auxiliary Space: O(n) for the encoded or decoded output.
- Edge Case: Strings contain spaces, empty values, or delimiter characters.

## 3. Count and Say
- Technique: Consecutive Character Counting
- Approach: Start with the sequence "1" and repeatedly generate the next term by counting consecutive identical digits. Append each frequency and corresponding digit to a result list.
- Time Complexity: Proportional to the total lengths of the generated sequence terms.
- Auxiliary Space: O(L), where L is the length of the largest generated term.
- Edge Case: n = 1, where the answer is simply "1".

## Learning Outcomes
- Understood run-length encoding.
- Practised manual consecutive character counting.
- Learned in-place array compression using read and write pointers.
- Implemented length-prefix encoding and decoding.
- Understood how delimiters and length information prevent ambiguity.
- Generated sequences through repeated string transformations.

## Restrictions Followed
- Did not use itertools.groupby().
- Did not use collections.Counter.
- Used manual loops to count character runs.
- Used read and write pointers for compression.
- Used modular character conversion only where required.
- Used lists and join() for string construction.
- Avoided external libraries and prohibited shortcuts.
