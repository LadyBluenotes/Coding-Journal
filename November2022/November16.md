# November 16, 2022 

## DSA Review
- A keys function in hashmaps allows for the pulling of all the keys
- Linked Lists
    - There are singly and doubly linked lists
    - Can be used with collisions in hash tables
    - Have to parts to it - a pointer and a node
        - Pointer points to next node which is located at a certain place in memory
    - Head is the first node
    - Tail points to null (the end)
    - JS doesnt come prebuilt with linked lists (Java does)
    - Linked lists are scattered in memory - take longer to traverse compared to arrays
    - Allows for sorted data unlike hashtables
    - Append (add end of list), prepend (add to beginning of list) are both O(1)
    - Lookup, insert and delete are O(n)
    - Best to use when you have little memory or memory is more expensive to you
    - Has fast insertion and deletion (not searching)
- Ex:
    `let linkedList = {`
        `head: {`
            `value: 5,`
            `next: {`
                `value: 15,`
                `next: {`
                    `value: 10,`
                    `next: {`
                         `value: 8,`
                         `next: null`
                    `}`
                `}`
            `}`
        `}`
    `}`
- Doubly linked list:
    - Similar to single linked list but points to the node before as well
        - There would be a node that points to previous && next
    - Allows you to start at the end or the beginning to traverse the node
        - Can be more efficient (you can look at what half of the list you need to get to and traverse from the closer side)
    - Takes up more space in memory

## Codewars && LeetCode Done

## What I Learned

#### Tomorrow's Goals
- Work on DSA Course
- Work on some Leetcode q's