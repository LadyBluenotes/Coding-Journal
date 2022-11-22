# November 21, 2022 

## DSA Review
- Trees - Data structure with hierarchical structure
    - Many kinds:
        - Heaps
        - Binary tree
        - Linked lists (one path)
- Binary Tree:
    - Each node can only have 0, 1 or 2 nodes
    - Left and right pointers & value
    - Prefect tree = no gaps (everything is filled in and no node only has 0 or 1 child and bottom is entirely filled)
        - Number of nodes double as you move down the tree
        - Number of nodes on the bottom level is equal to the number of all the nodes in the above levels minus 1 (1/2 of the nodes are on the bottom level)
        - Lookup, insert and delete are O(log n)
        - To find out the number of nodes in a perfectly balanced binary tree we do 2^(levelsInTree)
        - To out all the nodes in a tree we do 2^(height)-1
    - Full tree = Nodes have either 0 or 2 nodes
    - Binary Search trees = divide and conquer techniques are used
        - Going to the left the numbers decrease and going to the right the numbers are higher
        - Balanced = log(n) performance
        - Unbalanced = looks like a linked list O(n) operations
        - Ordered and flexible with size
        - Downside is that there is no O(1) methods
        - In production would use an AVL or red black tree which re-ballance themselves (most popular)

