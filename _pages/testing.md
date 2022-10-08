---
title: Testing
--- 

# Testing

It's not enough to find the right algorithm, your code should also be correct. 

As you probably know from experience, it's almost guaranteed for your code to have bugs in it when you finish. Testing your code proactively will let you find and fix the bugs.

If your interviewer asks you to run through a specific test case or asks "what happens if X?", it's likely that you missed a bug. Don't worry, this is very common. It's almost as good if you can discover a bug this way.

## Test Driven Development

I use this at work and I've found it translates very well to coding interviews.

<table>
  <tr>
    <th>TDD step</th>
    <th>Suggestions</th>
  </tr>
  <tr>
    <td>Define test cases</td>
    <td>
      This step can be very useful when trying to find the solution.<br>
      Start with base cases (n=0, n=1, n=2, etc). It's often easier to solve a problem for a base case.<br>
      Define the expected inputs and outputs<br>
      Use examples the interviewer gave you. Do you understand all parts of it?
  </tr>
  <tr>
    <td>Find the solution and validate against test cases</td>
    <td>
      Verbally walk through your solution and make sure it works for the test cases<br>
    </td>
  </tr>
  <tr>
    <td>Code the solution and validate against test cases</td>
    <td>
      I suggest announcing your intention to do this before coding -- it prevents interviewers from interrupting you to point out bugs and if you run out of time, at least they know what you were planning<br>
      Step through your solution and make sure it works for the test cases. Step through like a debugger and track variable values.<br>
    </td>
  </tr>
</table>

