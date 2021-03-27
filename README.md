Algorithm practice -  “think like a programmer.”
===================

    “The biggest mistake I see new programmers make is focusing on 
     learning syntax instead of learning how to solve problems.” 
     — V. Anton Spraul


:warning: Be careful 
=======================

### Do not… 
- __Do not__ ignore information given. Info is there for a reason. 
- __Do not__ try to solve one big problem. You will cry. :cry:
- __Do not__ start solving without a plan. Plan your solution!
- __Do not__ try to solve problems in your head. Use an example! 
- __Do not__ push through code when confused. Stop and think! 
- __Do not__ dive into code without interviewer “sign off.”


First 3 things to do
=======================

1. Think out loud :loudspeaker:
   - One of the worst things you can do in an interview is to freeze up when solving the problem. It is always a good idea to __think out loud__ and stay engaged. On the one hand, this increases your chances of finding the right solution because it forces you to put your thoughts in a coherent manner. On the other hand, this helps the interviewer guide your thought process in the right direction. Even if you are not able to reach the solution, the interviewer will form some impression of your intellectual ability. 
2. Clarify the question
   - A good way of clarifying the question is to state a concrete instance of the problem. For example, if the question is "find the first occurrence of a number greater than k in a sorted array", you could ask "if the input array is <2,20,30> and k is 3, then are you supposed to return 1, the index of 20?" __These questions can be formalized as unit tests.__
3. Restate the problem
   - Restating a problem can produce valuable results. In some cases, a problem that looks very difficult may seem easy when stated in a different way or using different terms. 
   - If you are unaware of all possible actions you could take, you may be unable to solve the problem. We can
refer to these actions as operations. By enumerating all the possible operations, we can solve many problems by testing every combination of operations until we find one that works. More generally, by restating a problem
in more formal terms, we can often __uncover solutions__ that would have otherwise eluded us.
   - __Restatement can be a powerful technique__, but many programmers will skip it because it doesn’t
directly involve writing code or even designing a solution. This is another
reason why having a plan is essential. Without a plan, your only goal is to
have working code, and restatement is taking time away from writing code.
With a plan, you can put “formally restate the problem” as your first step;
therefore, completing the restatement officially counts as progress.
   - Even if a restatement doesn’t lead to any immediate insight, it can help
in other ways. For example, if a problem has been assigned to you (by a
supervisor or an instructor), you can take your restatement to the person
who assigned the problem and confirm your understanding. __Also, restating
the problem may be a necessary prerequisite step to using other common
techniques, like reducing or dividing the problem.__
More broadly, restatement can transform whole problem areas.


Next get a brute-force solution ASAP
=====================================================

1. No coding yet! :smirk:
2. Plan with comments, not code
3. Don't worry about an efficient algo yet
4. Try the following problem-solving approaches:
   - Simplify & generalize: solve a simpler version
   - Write base cases & build: solve for the base cases then build from there.
   - __Always break the problem into sub-problems__ :point_left:
      - Write them down. These are the steps to solve the problem.
      - Then, solve each sub-problem one by one. Begin with the simplest. Simplest means you know the answer (or are closer to that answer).
      - After that, simplest means this sub-problem being solved doesn’t depend on others being solved.
      - Once you solved every sub-problem, connect the dots.
      - Connecting all your “sub-solutions” will give you the solution to the original problem. Congratulations!
      - __This technique is a cornerstone of problem-solving. Remember it.__ :point_left:

Next optimize the brute-force solution
=========================================
1. Walk through your brute force and try some of these ideas:
    - Look for any unused info. You usually need all the information in a problem. 
    - Solve it manually on an example, then reverse engineer your thought process. How did you solve it? 
    - Solve it “incorrectly” and then think about why the algorithm fails. Can you fix those issues? 
    - Make a time vs. space tradeoff. Hash tables are especially useful!
    - __Apply patterns.__ Patterns -- general reusable solutions to commonly ocurring problems -- can be a good way to approach a baffling problem. Examples include finding a good data structure, a good fit for a general algorithmic technique (__divide-and-conquer, recursion, DP, sliding window, etc.__)

Next implement (You can code now. Yay!!) :smile:
=========================================

*  Your goal is to write beautiful code. Modularize your code from the beginning and refactor to clean up anything that isn’t beautiful

Finally, test your solution
=============================
1. Conceptual test. Walk through your code like you would for a detailed code review. 
2. Small test cases. It’s much faster than a big test case and just as effective. 
3. Special cases and edge cases. 
4. And when you find bugs, fix them carefully!

If you are stuck, remember the cornerstone of creating sub-problems
==========================
Nothing can help you if you can’t write down the exact steps (sub-problems)

In programming, this means don’t start hacking straight away. Give your brain time to analyze the problem and process the information.

To get a good plan, answer this question:

__“Given input X, what are the steps necessary to return output Y?”__

Sidenote: Programmers have a great tool to help them with this… __Comments!__


Final suggestion: practice micro-problems :video_game:
=========================
How to practice? There are options out the wazoo!

Chess puzzles, math problems, Sudoku, Go, Monopoly, video-games, cryptokitties, bla… bla… bla….

In fact, a common pattern amongst successful people is their habit of practicing __“micro problem-solving.”__ For example, Peter Thiel plays chess, and Elon Musk plays video-games.

“Byron Reeves said ‘If you want to see what business leadership may look like in three to five years, look at what’s happening in online games.’
Fast-forward to today. Elon [Musk], Reid [Hoffman], Mark Zuckerberg and many others say that games have been foundational to their success in building their companies.” — Mary Meeker (2017 internet trends report)

Does this mean you should just play video-games? Not at all.

But what are video-games all about? That’s right, problem-solving!

So, what you should do is find an outlet to practice. 
