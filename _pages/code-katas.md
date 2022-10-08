---
title: Code Katas
--- 
 
# Code Katas

If you take one piece of advice from this site, this is it.

Code katas are how I spend the majority of my time when I prepare for coding interviews. They are the equivalent of easy hackerrank/leetcode problems.

By far the most common mistake I see candidates make is spending too much time figuring out how to write a tree search or array traversal and run out of time to optimize or find bugs or even to finish. 

This is unfortunate because it's unnecessary. This is the easiest part of the coding interview to perfect.

All it takes is regular practice. You don't need to grind for hours, you just need to do a little bit regularly until you are able to just sit down and confidently code the solution without backtracking or hesitation. Even 5 minutes of practice a day on one of these is beneficial. 

I also use them before interviews to calm myself down and get into the right mental space.

## List of katas

<table>
 <tr>
  <th>Category</th><th>Katas</th>
 </tr>
 <tr>
  <td>Arrays/Strings</td>
  <td>Running sum of array (<a href="https://leetcode.com/problems/running-sum-of-1d-array/">leetcode</a>)</td>
 </tr>
 <tr>
  <td>Linked Lists</td>
  <td>Compare two linked lists (<a href="https://www.hackerrank.com/challenges/compare-two-linked-lists/problem">hackerrank</a>)</td>
 </tr>
 <tr>
  <td>Trees</td>
  <td>
   
   * **Traversals**
    * Time complexity: O(n) where `n` is the number of nodes. This is because you are visiting every node in the tree during a traversal.
  * **In-order traversal** ([hackerrank](https://www.hackerrank.com/challenges/tree-inorder-traversal/problem))
    * Useful for: Visiting binary search tree nodes in sorted order (this is where the name comes from)
  * **Pre-order traversal** ([hackerrank](https://www.hackerrank.com/challenges/tree-preorder-traversal/problem))
  * **Post-order traversal** ([hackerrank](https://www.hackerrank.com/challenges/tree-postorder-traversal/problem))
   
  </td>
 </tr>
 <tr>
  <td>Dynamic Programming</td>
  <td>Ways to climb a staircase (<a href="https://www.hackerrank.com/challenges/ctci-recursive-staircase/problem">hackerrank</a>)</td>
 </tr>
</table>

## How to use code katas

For every kata, do the following:
* **Practice until you can confidently and correctly code the solution in <10 minutes.** An example progression would look like:
    1. Unable to write the code after 10 minutes of trying (Don't waste time deriving the optimal solution yourself, just look it up. Instead, spend your time understanding why it's better than other approaches.)
    2. Able to write the code, but it takes >10 minutes and/or multiple submission + bug fix rounds
    3. Can write code in <10 minutes and perfectly on the first try
* **Think about the time/space complexity as you code.** Think about this with every line you write. When allocating supplemental data structures, think about how this impacts space complexity. When you add a for loop, think about what this means for time complexity.

## What are code katas?

The concept borrows from martial arts where students will perform a pre-defined series of movements called *katas* in order to perfect techniques and build muscle memory. Code katas have the same goal of perfecting coding and problem solving techniques and building muscle memory for them.

They help you build up a coding toolkit that you can use fluently even during high pressure situations like interviews.

Once you recognize that a problem requires a breadth-first-search or an array traversal, you can spend minimal time and effort on coding it up. The faster you can write the code, the more time you have to [test it for bugs](https://github.com/hthuman/tech-interview-tips/blob/main/code/testing.md) or optimize it.



