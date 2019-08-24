# Interview Preparation

## Table of Contents
1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [Reasoning behind Decisions](#reasoning-behind-decisions)
4. [4-week Sprint](#4-week-Sprint)
5. [Leet Code Grind](#leet-code-grind)
6. [Miscellaneous Tips](#miscellaeneous-tips)
7. [Essential LeetCode Problems](#essential-leetcode-problems)
8. [Resources](#resources)

---

## Introduction

This guide will go over how to best prepare for interviews at Big N companies while optimizing your time. All the information included in this guide is an aggregate of my personal research and various tips I received from current Big N employees and how they prepared for their interviews.

This guide is meant to prepare you for Big N companies. If you are aiming for smaller start-ups then this might be overkill and it could be wiser to concentrate on something else. Nonetheless, it's always good to overprepare and this will keep you engaged and motivated until you land a job. Additionally, front-end interviews might involve more JavaScript related questions concerning DOM manipulation or React trivia in addition to algorithm questions. Unfortunately, this guide will not cover those topics.

I recommend going through this guide with the same intensity as the bootcamp. The job search can be longer and more stressful than the bootcamp for some people and you lose the help and support of a TA and a curriculum to guide you. Keep the momentum going!

[Back to Top](#table-of-contents)

---

## Prerequisites

- Alvin's Data Structure Course
- Elements of Programming Interviews in Python   
  [Physical Version](https://www.amazon.com/Elements-Programming-Interviews-Python-Insiders/dp/1537713949)   
  [PDF Version](https://drive.google.com/open?id=15Km7MRDq5yWOt3XE5B2FDdQwMFnqWTtS)

[Back to Top](#table-of-contents)

---

## Reasoning Behind Decisions

### Why Python?

Python offers many benefits over the languages that we learn at App Academy:

- It's statistically proven to be the most successful language for technical interviews<sup>1</sup>.
- Its syntax is very close to Ruby so the transition is relatively easy.
- Its extremely quick to type or write on the whiteboard (arguably the fastest).
- There are built-in data structures that help simplify many problems (heaps, priority queues, ordered maps, etc.).
- It uses consistent APIs that operate on different data structures (E.g. `len()`, `for ... in ...` and slicing notation on sequences (strings/lists/tuples))
- Due to the structure of Python code blocks, it forces you to be more organized and the code is inherently more readable. 
- List comprehension allows you to condense complex code into a single line.
- Python is not statically typed (although extensions can emulate compile-time error checking) but it can be annotated<sup>2</sup>.

### Why Elements of Programming Interviews?

I chose to write this guide using *Elements of Programming Interviews* instead of *Cracking the Coding Interview* for several reasons:

- It provides solutions in Python.
- The explanations are more technical, which will train you to better understand verbal explanations better and to speak in a more technical manner.
- They have a honors section which contain common questions asked at the Big N with in-depth solutions.
- It's what I used and it's worked for countless other people.

1. [Technical Interview Performance by Editor/OS/Language](https://triplebyte.com/blog/technical-interview-performance-by-editor-os-language) by TripleByte
2. [PEP 3107 - Function Annotations](https://www.python.org/dev/peps/pep-3107/)

[Back to Top](#table-of-contents)

---

## 4-week Sprint

This is a four week long, Monday to Friday schedule that will give you a good foundation on algorithms. This will give you the confidence to jump into problems on LeetCode as they can be daunting when first starting off. This alone will not prepare you for the Big N companies, although it is adequate for smaller start-ups. 

[Link to schedule on Google Sheets]()

You will need a team of 3 including yourself. This is so that you can keep each other accountable. You should create an incentive for yourselves to come into the office (E.g. Late/absent persons must owe their other team members lunch/dinner). 

**Choose your teammates wisely!** I recommend picking teammates you believe are on the same level or higher.

Doing mock interviews with your teammate will help you practice whiteboarding. It will also give you an insight on what an interviewer is thinking when a candidate is struggling. Try to keep it as close to the real experience as you can.

**Follow all of the guidelines below:**

- Do the problems marked with a number with your team. The ones marked with an X can be done alone or together. Try to do all the problems for each day. If you can't, come back to the problem when you finish a problem set for the day.

- Designate two people to solve a problem and one person to act as an interviewer for each problem. 

- Only attempt the problem for 30 minutes. If you feel like are close to a solution, then take extra time to finish it.

- Your solution must include the time complexity of the algorithm.

- Afterwards review the solution until you can understand it. Practice explaining it to your team mates if they are having trouble.

- Do **Problem Blitzs**. These are short sessions where you spend at most 5 minutes visualizing a solution in your head before getting together and reviewing the solution. You would try to get as many problems into an hour period. The idea of a *blitz* is based on the [Pareto Principle](https://www.briantracy.com/blog/personal-success/how-to-use-the-80-20-rule-pareto-principle/) or the 80/20 rule for short. You can pull these questions from any resource (LeetCode, Cracking the Coding Interview, CareerCup).

**Additional things you can do:**

- Write down short notes for each problem. This will help you internalize what you've learned.

- Keep track of whether or not you did or didn't get the solution. Come back to the problem later on to review it.

- Spend time learning about a data structure before jumping into the problems.

[Back to Top](#table-of-contents)

---

## LeetCode Grind

The reality of technical interviews is that it is a flawed system, dependent on luck. You can get a problem at an interview that you solved the day before and pass. Some problems are unnecessarily difficult unless you've solved them before. But don't be discouraged! The point of this entire guide is to help you develop a "toolkit" of problem-solving methods. Very soon, you will be able to solve more complex problems you don't know how to even approach right now.

Unfortunately, this part is less structured than the 4-week sprint. Now, all the daily problems and motivation will have to come from yourself. You will need to identify topics you are struggling with which requires a level of awareness and introspection. Then you have to have the patience to drill yourself on these problems until you're able to solve them without any help within a short time period.

[LeetCode Grinding Guide](https://www.reddit.com/r/cscareerquestions/comments/6luszf/a_leetcode_grinding_guide/) 

**When solving problems, abide by these rules:**

- Only attempt the problem for a maximum of 30 minutes.

- Use Youtube videos to help you get a better understanding of problems. 

- Keep a ratio of 20% Easy, 60% Medium, 20% Hard. (It'll be rough in the beginning.)

- Aim for at least 5 problems a day. 

- Read multiple solutions in the discussions. Sometimes a solution can "neater", more novel, more space efficient as opposed to time efficient, or even better objectively. You want to be exposed to as many possible solutions as you can.

- **Come back to a problem you had trouble with after some time and review it.** See if you can solve it again, but without refering to the solution.

- Continue whiteboarding with your former teammates or friends.

**Additional things you can do:**

- Verbalize how you plan to solve a problem, and the advantages and drawbacks of your solution.

- For harder problems, start with a brute force solution.

### When would I know I'm ready? How many problems should I do?

Some people argue around 300 problems are enough to get into Google. There are others who argue 500+ is needed to have a decent chance to get in. There have also been some people who have gotten offers at Google without doing any LeetCode problems and relying solely on what they learned from their textbook. 

In the end, it's not about how many problems you do. It's about how effectively you studied and what you did to maximize your chance of passing. That means doing as many problems as you can and deeply understanding the solutions to each one. Your mileage may vary.

[Back to Top](#table-of-contents)

---

## Miscellaneous Tips

- **Do your due diligence and research your company.**
- Participate in Alvin's Fight Club that occurs every Sunday.
- Schedule mock behavioral/technical interviews with your career coach. They are extremely effective.
- Improve your typing speed/accuracy. Most coding challenges are timed and typing speed/accuracy is crucial. Additionally many Big N companies now allow you to use a laptop instead of a whiteboard during interviews.
- Carry your textbook around and read it during train rides.

---

## Essential LeetCode Problems

- LeetCode Premium problems for the company you are interviewing for

- [Blind Curated List of 75 Questions](https://leetcode.com/list/xoqag3yj/)

- [Best Practice Questions from Tech Interview Handbook](https://yangshun.github.io/tech-interview-handbook/best-practice-questions/)

- [General approach to backtracking questions](https://leetcode.com/problems/permutations/discuss/18239/A-general-approach-to-backtracking-questions-in-Java-(Subsets-Permutations-Combination-Sum-Palindrome-Partioning))

- Best Time to Buy and Sell Stock [I](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/), [II](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-ii/), [III](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-iii/)

- Word Break [I](https://leetcode.com/problems/word-break/), [II](https://leetcode.com/problems/word-break-ii/)

- [LRU Cache](https://leetcode.com/problems/lru-cache/)

- [LFU Cache](https://leetcode.com/problems/lfu-cache/)

- [Construct Binary Tree from Preorder and Inorder Traversal](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/)

- [Construct Binary Tree from Inorder and Postorder Traversal](https://leetcode.com/problems/construct-binary-tree-from-inorder-and-postorder-traversal/)

- [Climbing Stairs](https://leetcode.com/problems/climbing-stairs/)*

- [Gray Code](https://leetcode.com/problems/gray-code/)*

- [Next Permutation](https://leetcode.com/problems/next-permutation/)*

- [Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/)*

\* Asterisks signify problems that have solutions that are not worth spending the time figuring out yourself.

[Back to Top](#table-of-contents)

---

## Resources

- [The only video channel on Python you need.](https://www.youtube.com/channel/UCCezIgC97PvUuR4_gbFUs5g)


### Must Read

- [Tech Interview Handbook](https://yangshun.github.io/tech-interview-handbook/)
- [Kevin Naughton Jr.'s Interviews Repo](https://github.com/kdn251/interviews)
- [Time complexity for Python operations](https://wiki.python.org/moin/TimeComplexity)
- [Combinations and Permutations](https://www.mathsisfun.com/combinatorics/combinations-permutations.html)

### Question Banks

- [CareerCup](https://www.careercup.com/)
- [LeetCode Discussion Forum](https://leetcode.com/discuss/interview-question)
- Glassdoor

### Youtube Videos/Channels on Algorithms

#### Channels
- [Abdul Bari](https://www.youtube.com/channel/UCZCFT11CWBi3MHNlGf019nw)
- [Tushar Roy](https://www.youtube.com/user/tusharroy2525/videos)

#### Videos on Algorithms
- [Tower of Hanoi Recursive Solution](https://www.youtube.com/watch?v=YstLjLCGmgg)
- [Djikstra's Algorithm](https://www.youtube.com/watch?v=GazC3A4OQTE)
- [A* Search Algorithm](https://www.youtube.com/watch?v=ySN5Wnu88nE)

### Supplemental Websites

#### Algorithm Solving Websites (LeetCode Alternatives)
- [AlgoExpert](https://www.algoexpert.io/product)
- [Interview Cake](https://www.interviewcake.com/)
- [Pramp](https://www.pramp.com/) - Schedule live interviews with a random person and give each other an algorithm problem.

#### Forums
- [Blind Forum](https://www.teamblind.com/)

#### Behavioral Stuff :eyes:

- [Andrew LaCivita](https://www.youtube.com/channel/UCP1UlYJH_QL4m5HVyikcxfQ) - Best behavioral YouTube channel I've seen so far.
- [Dan Croitor](https://www.youtube.com/channel/UCw0uQHve23oMWgQcTTpgQsQ) - Videos related to behavioral questions for various Big N companies but with a focus on Amazon


[Back to Top](#table-of-contents)