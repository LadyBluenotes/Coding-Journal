# December 2, 2022 

## DSA Review
- Sorting
    - There are many but a few that hold importance for interview purposes:
        - Bubble Sort
        - Insertion Sort
        - Selection Sort
        - Merge Sort
        - Quick Sort
    - One of the most improtant functions computers perform
- Sorting is about O(n log n)
- All algorithms have their uses and when theyre most efficient
- Elementary sorts - bubble, insertion, selection
- More complex sorts - merge, quick
- Bubble sort:
    - On each run through, you 'bubble up' the highest number in the pair before starting at the beginning and repeating until the entire array is sorted
    - Simple but least effective
        - Time complexity O(n^2)
        - Space complexity O(1) (not using new memory)

## Codewars && LeetCode Done

### Medium - Leetcode
**75. Sort Colors**

## What I Learned
- With Javascript, `.sort()` converts the numbers to a string and then convert them to the character code and sorts them based on that (the unicode)
    - Time and space complexity of the sort cannot be guaranteed as it is implementation dependent 
    - For `.sort()` to work you would have to write `.sort((a,b) => return a-b)`
- Frameworks will implement their own sorting algorithms

#### Tomorrow's Goals