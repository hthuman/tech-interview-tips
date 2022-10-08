---
title: Partial Credit Matters
--- 

# Partial Credit Matters

Coding interviews are about more than just whether or not you can solve a code puzzle perfectly.

You can absolutely pass with flying colors even if you don’t find the optimal solution on your own.

## No compromises: not being an asshole

The only area where there is no partial credit is not being an asshole. In theory everyone is on their best behavior during an interview, so if a candidate acts poorly then, how much worse will they be after getting hired?

Reasons I've seen candidates get no-hires who would otherwise have been passed:
* **HR violations**: This one is obvious.
* **Offensive comments**: We had a candidate complain about an interviewer's accent and ask for an American. Instantly cut the interview loop short.
* **Hostile attitude towards hints or feedback**: Unanimous opinion during a loop was that the candidate knocked it out of the park on coding, but got angry any time a bug was pointed out or a hint was given. No-hire from everyone.

## Coding skills

Competent coding skills are table stakes for a software engineer. If you can't write code, it doesn't matter how good you are at communication, analysis, testing, optimization, or anything else.

Happily, this is the easiest thing to train for with [code katas](https://hthuman.github.io/tech-interview-tips/code-katas).

The order of operations for showing coding skills:

<table>
  <tr>
    <td>Write <bold>any</bold> code</td>
    <td>
    If you're running out of time, unless the interviewer suggests otherwise, it's better to start coding with a non-optimal solution than it is to never write code. Just be sure to call out what you're doing and that you know it's a non-optimal solution.<br><br>
    I've passed candidates who displayed solid coding skills but didn't complete the optimal solution. The other way around is a no-hire.
    </td>
  </tr>
  <tr>
    <td>Write the core algorithm logic</td>
    <td>If you're writing a graph traversal, make sure you code up the terminal conditions and return values.<br><br>Don't spend time on finding node neighbors or figuring out off-by-one indexing errors, make a helper function stub, leave a TODO, and come back later.
    </td>
  </tr>
  <tr>
    <td>Test the core algorithm logic</td>
    <td>Write the code as fast as you can, then step through afterwards with a test case.<br><br>Best of all, call out your intention to do this before you start coding and provide some test cases. This will prevent your interviewer from jumping immediately on any bugs because they assume you don't see them
    </td>
  </tr>
</table>

## Big O complexity analysis

This is a close second to coding skills in importance, especially if you are interviewing at a company or team that works at scale.

When doing coding katas, memorize the time/space complexity of each algorithm.

If you can't get an optimal solution, it's almost as good if you can reach a non-optimal solution and explain precisely why it is non-optimal. Bonus points if you can also talk about the theoretical max efficiency.

I've been on both sides of the interview where this happened. I found a brute force solution and described the time complexity, then talked about how I could do better and what tools are generally used ("constant" = hashing, "linear" = trading space for time via memoization, etc). The interviewer said something like "What about nlogn?" which immediately got me thinking about sorting or trees. 
