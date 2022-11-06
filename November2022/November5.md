# November 5, 2022 - The Start

## DSA Review
- I made a summary in my DSA repo of some popular algorithms and data structures, starting with how to define them, what they look like and how they work as well as some examples in how to identify them.
- There are a lot of DSA things to know and I believe by getting an idea on how to identify some patterns or recognize how to solve problems is important.

## Codewars && LeetCode Done

### 8KYU - Codewars
**Name Shuffler**
**Alan Partridge II - Apple Turnover**
**Is there a vowel in there?**
**Remove exclamation marks**
**You only need one - Beginner**

### 7KYU - Codewars
**shorter concat [reverse longer]**
**Kooka-Counter**

### Easy - Leetcode
**Reverse String**

## What I Learned
- Worked a bit with some regular expressions (regex). This is something I don't find super intuitive but with practice I can see how it can make searching through strings more efficient. Some specific things I learned
    - `g` refers to global.
    - `i` refers to case insensitive.
    - `\D` refers to digits - this is something that works with numbers of all digit characters, including those of different languages.
- Chaining methods can make for an easy brute-force solution, and can seem more intuitive, but in the long run it tends to create performance issues. It is quite a bit slower than utilizing other methods.
    - Example of this is the `text.split().reverse().join()`. It can seem like the most inutitive solution however a more optimized solution is actually:

        `[...text].reduce((acc, char) => char + acc, '')`
        
        `if (text === "") {`
            `return ""`
        `} else {`
            `return reverseString(text.substr(1)) + text[0]`
        `}`
- Nested for-loops can, again, be an easy brute-force solution which can seem like the best answer but, much like chaining methods, it can lead to performance issues when comparing it to other ways of solving problems.

#### Tomorrow's Goals
- Continue to reflect on strings.
- Focus on more leetcode than codewars questions.