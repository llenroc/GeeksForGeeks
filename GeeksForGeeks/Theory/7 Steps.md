﻿# 7 Steps to solving an algorithm

1.  Listen carefully to the problem, generally every detail is important to solve the problem optimally.
    Ex: You have 2 arrays (sorted and distinct), find the # of elements in common. Sorted is an important detail.
    You want to write down the input, example and runtime / space restrictions right away!

2.  Ask for an example or come up with better examples on your own.
    Ex: A[1, 5, 15, 20] B[2, 5, 13, 30] The example is too small and is a specail case. 
    Better: A[1, 5, 15, 20, 30, 37] B[2, 5, 13, 30, 32, 35, 37, 42] This is a much larger example, and you avoid special cases.

3.  Come up with a brute force algo.  If first thing you have is slow and stupid, start with that.
    Don't code it! State the brute force and its runtime, and then go on to optimize it.

4.  Optimize. Spend some good time doing it.

5.  Walk through your algorithm. What are the variables and data structures? Why and how do they change? What is the code structure?

6.  Start Coding. Write well and neatly. Use board space wisely, give your code as much space as possible.
    Coding style matters, braces, naming conventions, camel case, underscore etc. Just be consistent.
    Use long discriptive variable names, they can be quite helpful, ask if you can abbrive next time.
    Modularize your code, any conceptual chunks of code, push that off to another function.

7.  Test your code. Example test case is usually too big and too familiar to test the code. 
    Walk through the code line by line, is it doing the right thing. Double check anything that looks weird (decrement vs incremenet etc)
    Use small test cases, that are different from your example.
    Go into edge cases (0, empty, null, things are the same).
    Maybe if you have time bigger test cases.
    Think as you test!
    Test your code, not your algorithm.
    When you find the bug, think about what caused it, you don't want to do the first fix that fixes it for that output.


# Links: 
https://www.youtube.com/watch?v=GKgAVjJxh9w&list=PLX6IKgS15Ue02WDPRCmYKuZicQHit9kFt&index=1 - hacker rank guide