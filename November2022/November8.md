# November 8, 2022 

## DSA Review
- Struggled with leetcode 1221:
    - Solved by keeping track of the number of L's (could be R's, too)
    - How I solved:
        - Initialized a L counter and a balanced string counter for how many times the string will split
        - Loop through original string, if the current element is an L, it would add to the L counter and, if not, it would subtract from the L counter
        - When the L counter hits 0, the balanced string counter would increment up
        - Return the balanced string counter to showcase how many substrings would be present
- Leetcode 1859:
    - I opted to originally use an object to store the index and word since javascript objects tend to order things as they go
        - I stored the indexes as the key and the properties as the value - looped through them then pushed them into an array
    - Noticed it wasn't the most efficient memory wise (it was fairly efficient time wise).
    - Looking back, I could optimize the solution through just chaining methods - it makes it slightly slower time wise but it makes a big difference with memory.
- Leetcode 125:
    - Originally solved using JS built-in methods and regex to remove all non-alphanumeric characters.
    - Followed up by using recursion - slower than first try.
- Leetcode 242:
    - Started with brute force which ended up being quite slow - first compared lengths and if they weren't the same length, return false => split and sorted the string => looped through both strings to compare and if they were the same returned true else false
    - Follow up involved hashmaps:
        - Compared lengths and if they weren't the same length, return false
        - Initialized a map for reach string
        - Mapped through each character adding a key-value pair so I could increment if it was run into again
        - Looped through both hashmaps and if we ran into an instance that wasn't in the other, returned false and if we reached the end, returned true.


## Codewars && LeetCode Done

### 8KYU - Codewars
**All Star Code Challenge #18**
**Exclamation marks series #1: Remove an exclamation mark from the end of string**
**Short Long Short**
**Contamination #1 -String-**

### 7KYU - Codewars
**Sort by Last Char**

### 6KYU - Codewars
**Backspaces in string**
**Replace With Alphabet Position**

### Easy - Leetcode
**1221. Split a String in Balanced Strings**
**1859. Sorting the Sentence**
**125. Valid Palindrome** /Review Again/
**242. Valid Anagram** /Review Again/

### Medium - Leetcode
**28. Find the Index of the First Occurrence in a String**

## What I Learned
- When using `.split()` you can pass through a specific argument that you want 'filtered' out.
    Ex. you want to count how many letters are in a word, you can use `word.split(letter)`
- `.sort()` sorts the elements of an array in place and returns the reference to the same array, now sorted.
    - Time and space complexity of the sort cannot be guaranteed as it depends on the implementation
- `.charCodeAt()` returns an integer between 0 and 65535 representing the UTF-16 code unit at the given index
-`.slice()` 

#### Tomorrow's Goals
- Review leetcode questions worked on from today
- 4 Leetcode Medium
- Warm up with codewars 8kyu and 7kyu