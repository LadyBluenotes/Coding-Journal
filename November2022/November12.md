# November 12, 2022 

## DSA Review
- O(n!) is factorial time which is the worst possible outcome for a program
    - This would be a nested loop for every element you are iterating over.
- To be scalable, you have to take into consideration the speed of which a program runs and how much memory it takes up.
- What makes good code?
    - Readable
    - Speed - time complexity
    - Memory - space complexity
        - Total size relative to input.
        - What causes space complexity?
            - Variables, data structures, allocations and function calls.
- There can be a trade off between time and space complexity.
- A heap is where we store variables we assign values to.
- Stack is where we keep track of our function calls.
- Data structures have different time and space complexity for the following operations:
    - Access, Deletion, Insertion, Searching, Sorting, Transversal

## What I Learned
- When trying to determine the time complexity of a method, it depends on the language and how the method works.
    - For ex: with `.length()` it could iterate over every letter in a string with one language but with JS it is a property of an object which means it runs in O(1) time.
- Arrays are stored in contiguous memory (in order) and have the smallest footprint of any data structure.
    - Arrays are best for access and push
- `.unshift()` adds to the beginning of an array and is an O(n) operation
- `.shift()` removes first array and is an O(n) operation
- `.splice()` can assist you in adding into the middle of an array
    - ex. arr.splice(index, #ofWhatYouWantToRemove, whereToPutWhatYouWantToAdd)

#### Tomorrow's Goals
- Finish Udemy DSA Array Section
- Leetcode Q's && Codewars