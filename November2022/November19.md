# November 19, 2022 

## DSA Review
- Stacks and queues are linear data structures that are similar
    - Run commands like push, peek, pop
    - Can only access first or last element 
- Stacks - LIFO
    - Can only put on the last and remove from the last (like stacked plates)
    - Good to know last values
    - Important for language management (stack overflow)
    - Most languages follow this model
    - Has pop, push, and peek as functions
    - Can be built with arrays or linked lists
        - Best to use arrays as they are faster than linked lists
        - Linked lists are better for storage
- Queues - FIFO
    - Similar to lines at a store
    - First item gets access to the queue but new items are added to the end
    - Enqueue, dequeue and peek are the methods
    - Dont use an array for queues as it is inefficient
    - Can use arrays or linked lists
        - Best to use linked lists d/t the indexes linked with each item and when you unshift() an option, the indexes change
- JS doesn't have stacks and queues architecture
- Asynchronous programming
    - Callback function and a callback queue

## Codewars && LeetCode Done

## What I Learned
- A program is able to allocate memory and parse and execute scripts.
- V8 engine consists of 2 parts: memory heap and call stack
- Memory leak - resource leak that occurs when a program incorrectly manages memory allocations in a way that memory which is no longer needed is not released.
- Call stack - reads and executes scripts
    - Multiple stacks = multi-threaded
-  JS is single-threaded language that can be non-blocking
- Synchronous programming - when one function is executed after another
- Recursion is a function that calls itself
- We need a JS run-time environment that consists of Web APIs(DOM, AJAX, Timeout(setTimeout))


#### Tomorrow's Goals
- Finish Stacks && Queues in DSA Course
- LeetCode Q's