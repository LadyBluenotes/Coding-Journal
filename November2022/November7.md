# November 7, 2022 

## DSA Review
- Stacks are used with LIFO principles 
    - Add to the back of an array and pop off on the back of the array, as well.
- Queues are used with FIFO principles
    - Add to the back of an array and shift off the front of the array.
- Arrays in JS behave differently than arrays in some other languages:
    - They are dynamic meaning you do not have to assign a length for them to take up in memory (they will grow as the elements do and shrink as the elements are removed) while you can't add to static arrays as their lengths are already determined.
    - JavaScript has many methods compared to other languages - things like include, pop, push, length, etcetc.

## Codewars && LeetCode Done

### 8KYU - Codewars
**The Wide-Mouthed frog!**
**Reversed Words**

### 7KYU - Codewars
**Changing letters**
**Switcheroo**

### 6KYU - Codewars
**Write Number in Expanded Form**
**Create Phone Number**

### Easy - Leetcode
**242. Valid Parentheses** /Amazon Q/
**1662. Check If Two String Arrays are Equivalent**
**2011. Final Value of Variable After Performing Operations**

### Medium - Leetcode
**1689. Partitioning Into Minimum Number Of Deci-Binary Numbers**

## What I Learned
- `.includes()` will check an array and return a boolean about whether or not what is passed through is present.
- `.indexOf()` returns the position of the first occurrence of what is passed through.
    - Will return -1 if not found.
    - Is case sensitive.
`.filter()` will call a callback function once for every element in an array and creates a new array of all the values that return true and skips on those that are false.
`.push()` adds to an array starting from back
    - Used in scenarios where we want to create a stack (LIFO) & queue(FIFO)
- `.pop()` removes last item in an array.
- With valid parentheses:
    - When we have to make sure there are pairs, it can be useful to use an array to push one part of the pair into an array to compare if there is another. 
    - When encountering the other half of an array, we can check the front of the stack and, if present, we will continue and, if not present, we will return false.
    - At the end, to ensure that all the values are valid, you check to make sure that the new array does not have any items in it and if it does, we would return false and, if it doesn't, we would return true.

#### Tomorrow's Goals
- Minimum 2 6kyu codewars
- Minimum 2 leetcode medium