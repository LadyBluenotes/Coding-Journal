# December 3, 2022 

## DSA Review
- Selection Sort:
    - Scans a list of elements for the smallest item and then swapping that for the one in the first position
    - Time complexity of O(n^2) & Space complexity of O(1)
    - Solving:
        - You will loop through the array, starting with the minimum being assigned to the first indexed element
        - While looping, you compare the current element to the minimum and, if smaller, you assign the minimum to the index of the new minimum
        - At the end of that loop, you would then assign the element at the looped index to where the minimum index element was (to swap)
        - Requires a temp variable in order to not lose the current element selected in the loop

## Codewars && LeetCode Done

### Medium - Leetcode
**912. Sort an Array**

## What I Learned
- Bubble sort would fail in larger data sets of the same number as it would time out. It would have to loop through exponentially, therefore would be better for smaller data sets.

#### Tomorrow's Goals