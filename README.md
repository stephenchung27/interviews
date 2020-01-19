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

This guide will go over how to best prepare for interviews at Big N companies while optimizing your time. All the information included in this guide is an aggregate of my personal research and various tips I received from current Big N employees on how they prepared for their interviews.

This guide is meant to prepare you specifically for Big N companies. If you are aiming for smaller start-ups, then this might be overkill and it could be wiser to concentrate on something else. Nonetheless, it's always good to overprepare and this will keep you engaged and motivated until you land a job. Additionally, front-end interviews might involve more JavaScript-related questions concerning DOM manipulation or React trivia in addition to algorithm questions. Unfortunately, this guide will not cover those topics.

I recommend going through this guide with the same intensity as the bootcamp. For some people, the job search can be longer and more stressful than the bootcamp. On top of that you lose the help and support of a TA and a curriculum to guide you. Keep the momentum going!

[Back to Top](#table-of-contents)

---

## Prerequisites

- Alvin's Data Structure Course
- Elements of Programming Interviews in Python   
  [Physical Version](https://www.amazon.com/Elements-Programming-Interviews-Python-Insiders/dp/1537713949)   
  [PDF Version](https://drive.google.com/open?id=15Km7MRDq5yWOt3XE5B2FDdQwMFnqWTtS)

[Back to Top](#table-of-contents)

---

## Explanations on Decisions

### Why Python?

Python offers many benefits over the languages that we learn at App Academy:

- It's statistically proven to be the most successful language for technical interviews<sup>1</sup>.
- The syntax is very close to Ruby so the transition is relatively easy.
- It's extremely quick to type or write on the whiteboard (arguably the fastest).
- There are built-in data structures that help simplify many problems (heaps, priority queues, ordered maps, etc.).
- It uses consistent APIs to operate on different data structures (E.g. `len()`, `for ... in ...` and slicing notation on sequences (strings/lists/tuples))
- Due to the structure of Python code blocks, it forces you to be more organized and the code is inherently more readable. 
- List comprehension allows you to condense complex code into a single line.
- Python is not statically typed (although extensions can emulate compile-time error checking) but it can be annotated<sup>2</sup>.

On a Python repl (you use the Python interpreter on your terminal), type in `import this` to get a short poem on the "Zen of Python". [Link to Documentation](https://www.python.org/dev/peps/pep-0020/)

### Why Elements of Programming Interviews?

I chose to write this guide using *Elements of Programming Interviews* instead of *Cracking the Coding Interview* for several reasons:

- It provides solutions in Python.
- The explanations are more technical, which will train you to better understand verbal explanations and to speak in a more technical manner.
- They have an honors section which contain common questions asked at Big N companies with in-depth solutions.
- It's what I used and has worked for countless other people.

1. [Technical Interview Performance by Editor/OS/Language](https://triplebyte.com/blog/technical-interview-performance-by-editor-os-language) by TripleByte
2. [PEP 3107 - Function Annotations](https://www.python.org/dev/peps/pep-3107/)

[Back to Top](#table-of-contents)

---

## 4-Week Sprint

This is a four week long, Monday to Friday schedule that will give you a good foundation on algorithms. This sprint will give you the confidence to jump into problems on LeetCode, as they can be daunting when first starting off. This alone will not prepare you for the Big N companies, although it is adequate for smaller start-ups. 

[Link to schedule on Google Sheets](https://docs.google.com/spreadsheets/d/1NeRp52zb8jryX3OTcx6-4DEl8YHqJCvVG63NSLlTwL0/edit?usp=sharing)

You will need a team of 3 including yourself. This is so that you can keep each other accountable. You should create an incentive for yourselves to come into the office (e.g. late/absent persons must owe their other team members lunch/dinner). 

**Choose your teammates wisely!** 

I recommend picking teammates you believe are on the same level or higher.

Doing mock interviews with your teammates will help you practice whiteboarding. It will also give you insight on what an interviewer is thinking when a candidate is struggling. Try to keep it as close to the real experience as you can.

I also recommend not choosing your friends as teammates. Along the same vein, and this will sound cynical, if you ever feel like your teammates are dragging you down, be quick to drop them and study on your own. 

**Important note**

The main goal of white boarding is to get practice explaining your thought process. I've seen people who were amazing at solving problems on a code editor but fail at explaining their solutions out loud. **Please do not fall into this trap!** 

First, take some time to think about what an interviewer looks for in a candidate:

- Does this person have sufficient problem solving skills?
- Does this person understand the logic/data structure involved in solving a problem?
- Can this person communicate his thought process well?
- Would I enjoy working with this person?

Do not disregard any of these four! A candidate can fail if they lack in even one. Keep these four things in mind while whiteboarding or doing mock interviews.

Think about why an interviewer is asking you a question. What skills or qualities are they looking for? What red flags are they filtering for? If you can correctly identify the "why", you will have a much easier time coming up with an answer.

**Follow all of the guidelines below:**

- Do the problems marked with a number with your team. The ones marked with an X can be done alone or together. Try to do all the problems for each day. If you can't, come back to the problem when you finish a problem set for the day.
- Designate two people to solve a problem and one person to act as an interviewer for each problem. 
- Only attempt the problem for 30 minutes. If you feel like you are close to a solution, take extra time to finish it.
- Your solution must include the time complexity of the algorithm.
- Afterwards, review the solution until you can understand it. Practice explaining it to your teammates if they are having trouble.
- Do **Problem Blitzes**. These are short sessions in which you spend at most 5 minutes visualizing a solution in your head before getting together and reviewing the solution. The goal is to fit as many problems as you can into an hour period. The idea of a *blitz* is based on the [Pareto Principle](https://www.briantracy.com/blog/personal-success/how-to-use-the-80-20-rule-pareto-principle/), or the 80/20 rule for short. You can pull these questions from any resource (LeetCode, Cracking the Coding Interview, CareerCup).

**Additional things you can do:**

- Write down short notes for each problem. This will help you internalize what you've learned.
- Keep track of whether or not you got a solution. Come back to the problem later on to review it.
- Spend time learning about a data structure before jumping into the problems.

[Back to Top](#table-of-contents)

---

## LeetCode Grind

The reality of technical interviews is that it is a flawed system that's dependent on luck. You can get a problem at an interview that you solved the day before and pass. Some problems are unnecessarily difficult unless you've solved them at least once. But don't be discouraged! The point of this entire guide is to help you develop a "tool kit" of problem-solving methods. Very soon, you will be able to solve complex problems that you don't even know how to approach right now.

Unfortunately, this part is less structured than the 4-week sprint. Now, all the daily problems and motivation will have to come from yourself. You will need to identify topics you are struggling with, which requires a certain level of awareness and introspection. Then, you have to have the patience to drill yourself on these problems until you're able to solve them, without any help, within a short time period.

[LeetCode Grinding Guide](https://www.reddit.com/r/cscareerquestions/comments/6luszf/a_leetcode_grinding_guide/) 

**When solving problems, abide by these rules:**

- Only attempt the problem for a maximum of 30 minutes.
- Use Youtube videos to help you get a better understanding of problems. 
- Keep a ratio of 30% Easy, 50% Medium, 20% Hard. (It'll be rough in the beginning.)
- Aim for at least 5 problems a day. 
- Read multiple solutions in the discussions. Sometimes a solution can be "neater", more novel, more space efficient as opposed to time efficient, or even better objectively. You want to be exposed to as many possible solutions as you can.
- **Come back to the problems you had trouble with after some time and review them.** See if you can solve them again, but without refering to the solution.
- Continue whiteboarding with your teammates or friends.

**Additional things you can do:**

- Verbalize how you plan to solve a problem, and the advantages and drawbacks of your solution.
- For harder problems, start with a brute force solution. Then work on optimizing it.
- Sign up for LeetCode Premium and use the Explore cards to study for the company you are interviewing for.

### When will I know I'm ready? How many problems should I do?

Some people argue around 300 problems are enough to get into Google. There are others who argue 500+ is needed to have a decent chance to get in. There have also been some people who have gotten offers at Google without doing any LeetCode problems and relying solely on what they learned from their textbook. 

In the end, it's not about how many problems you do. It's about how effectively you studied and what you did to maximize your chance of passing. That means doing as many problems as you can while deeply understanding the solutions to each one. 

[Back to Top](#table-of-contents)

---

## Miscellaneous Tips

- **Do your due diligence and research your company.** 
    - A lot of companies have their own list of problems that they pull from (E.g. Bloomberg). Company-specific lists of problems are available through LeetCode premium. Keep in mind this does not guarantee that the problems they ask during the interview will come from this list. The list serves only as a suggestion, and they are not required to ask from that list. 
    - Some companies have very specific traits that they look for during the behavioral part (E.g. Amazon and their Leadership Principles). They are usually available online. Molding your answers to reflect these traits is advantageous and oftentimes obligatory since every candidate would be doing the same. 
- Teach new students and practice explaining concepts. This is also a good way to boost your confidence. You might even learn a few things from them. 
- Apply and interview everywhere, even to non-Big N companies. Use the interviews as practice and it will help you become less anxious at the interviews that matter.
- Participate in Alvin's Fight Club that occurs every Sunday.
- Schedule mock behavioral/technical interviews with your career coach. They are very effective as they will go harder on you than your friends.
- Improve your typing speed/accuracy. Most coding challenges are timed and typing speed/accuracy is crucial. Additionally, many Big N companies now allow you to use a laptop instead of a whiteboard so this can help shave additional time during a problem.
- Carry your textbook around and read it during your commute. Live and breathe algorithms!
- Be confident, in your skills and your personality. App Academy does a better job at filtering people than you think! 

[Back to Top](#table-of-contents)

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

\* Asterisks signify problems that have solutions that are not worth spending the time figuring out yourself. Take the time and try solving them but don't dwell on them.

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

- [Andrew LaCivita](https://www.youtube.com/channel/UCP1UlYJH_QL4m5HVyikcxfQ) - Best behavioral YouTube channel I've seen2.
- [Dan Croitor](https://www.youtube.com/channel/UCw0uQHve23oMWgQcTTpgQsQ) - Videos related to behavioral questions for various Big N companies but with a focus on Amazon


[Back to Top](#table-of-contents)
