---
layout: page
title: Coding Katas
--- 
 
# Coding Katas

I give a lot of coding interviews and it's very common to see candidates use up their time figuring out how to write a tree search or array traversal and run out of time to optimize or find all the bugs or even to finish. 

This is unfortunate because it's unnecessary. This is the easiest part of the coding interview to perfect. It's very straightforward to get to the point where you can write out a tree traversal without thinking about it. All it takes is regular practice. 

**Coding katas** provide this regular practice.

The concept borrows from martial arts where students will perform a pre-defined series of movements called *katas* in order to perfect techniques and build muscle memory. Coding katas have the same goal of perfecting coding and problem solving techniques and building muscle memory for them.

They help you build up a coding toolkit that you can use fluently even during high pressure situations like interviews. Once you recognize that a problem requires a breadth-first-search or an array traversal, you can spend minimal time and effort on coding it up. The faster you can write the code, the more time you have to [test it for bugs](https://github.com/hthuman/tech-interview-tips/blob/main/code/testing.md) or optimize it.

I also use them before interviews to calm me down and get myself into the right mental space.

## How to use coding katas
For every kata, do the following:
* **Practice until you can confidently and quickly code the solution.** It's fine to look up optimal solutions, just ensure that you understand every line and why it's better than other approaches. 
* **Think about the time/space complexity as you code.** Think about this with every line you write. When allocating supplemental data structures, think about how this impacts space complexity. When you add a for loop, think about what this means for time complexity.

Even 5 minutes of practice on one of these is beneficial. You don't need to grind for hours, you just need to do a little bit regularly until you are able to just sit down and confidently code the solution without backtracking or hesitation. An example progression would look like:
1. Unable to solve problem or write the code after 15 minutes of trying (at this point, no use in grinding further. Stop and look up the solution and ensure you really understand it)
2. Able to write the code, but it takes >15 minutes and multiple submission + bug fix rounds
3. Can write code in <15 minutes and perfectly on the first try

## List of katas

### Arrays/strings
* **Running sum of array** ([leetcode](https://leetcode.com/problems/running-sum-of-1d-array/))

### Linked Lists
* **Compare two linked lists** ([hackerrank](https://www.hackerrank.com/challenges/compare-two-linked-lists/problem))

### Trees
* **Traversals**
    * Time complexity: O(n) where `n` is the number of nodes. This is because you are visiting every node in the tree during a traversal.
  * **In-order traversal** ([hackerrank](https://www.hackerrank.com/challenges/tree-inorder-traversal/problem))
    * Useful for: Visiting binary search tree nodes in sorted order (this is where the name comes from)
  * **Pre-order traversal** ([hackerrank](https://www.hackerrank.com/challenges/tree-preorder-traversal/problem))
  * **Post-order traversal** ([hackerrank](https://www.hackerrank.com/challenges/tree-postorder-traversal/problem))

### Graphs

### Dynamic Programming
* **Ways to climb a staircase** ([hackerrank](https://www.hackerrank.com/challenges/ctci-recursive-staircase/problem))
