---
title: Partial Credit Matters
--- 

# Partial Credit Matters

This is a really important mindset for interviews.  

Of course it would be nice to do everything perfectly, but it's not required in order to pass an interview. If you can't get a 100%, at least ensure you get a 90% by spending your time on the most valuable actions.


## Coding skills

Competent coding skills are table stakes for a software engineer. If you can't write code, it doesn't matter how good you are at communication, analysis, testing, optimization, or anything else.

Happily, this is the easiest thing to train for with [code katas](https://hthuman.github.io/tech-interview-tips/code-katas).

The order of operations for showing coding skills:

* **Write ANY code**: If you're running out of time but you have a non-optimal solution, ask if you can code it up and work on the optimal approach later.  
* **Focus on the core logic**: Use TODOs with helper function stubs to avoid getting bogged down in non-essential boilerplate code. Come back later if you have time after writing the main code.

## Big O complexity analysis

This is a close second to coding skills in importance, especially if you are interviewing at a company or team that works at scale.

When doing coding katas, memorize the time/space complexity of each algorithm.

If you can't get an optimal solution, it's almost as good if you can reach a non-optimal solution and explain precisely why it is non-optimal. Bonus points if you can also talk about the theoretical max efficiency.

I've been on both sides of the interview where this happened. I found a brute force solution and described the time complexity, then talked about how I could do better and what tools are generally used ("constant" = hashing, "linear" = trading space for time via memoization, etc). The interviewer said something like "What about nlogn?" which immediately got me thinking about sorting or trees. 
