I recently interviewed for an SDE-1 role at Blinkit, and I wanted to share my interview experience for anyone preparing for similar roles.

The process consisted of three rounds:

Problem Solving
Machine Coding / Design + SQL + Projects
Culture Fit
Here’s how each round went.

Round 1 — Problem Solving
Duration: ~1 hour

The interview started with a brief introduction, followed by two coding problems.

Problem 1 — Task Scheduler
The first problem was a Task Scheduler problem.

This was an end-to-end coding round, so the interviewer was interested not just in the final approach but also in:

How I understood the problem
How I approached the solution
Data structures used
Edge cases
Time and space complexity
Code quality
Dry Run and execute code for checking the output
I discussed the approach first and then implemented the solution.

Problem 2 — Dynamic Rolling Dice
The second problem was a variation of a dynamic rolling dice problem.

The key requirement was that every operation should run in O(1):

Addition
Removal
Get
The interesting part of this problem was figuring out the appropriate data structure combination to achieve constant-time operations so we had discussions on different data structures.

Overall, this round was less about simply knowing a particular algorithm and more about thinking through the problem and making the right data-structure choices.

Round 2 — Design + SQL + Projects
This was probably the most interesting round for me because it covered multiple areas.

C++ Standard Library Design
I was asked to design a Queue as a C++ standard-library-like implementation, while trying to make it as optimized as possible and covering the basic implementations.

Become a Medium member
I started with an array-based implementation and then discussed how it could be optimized/implemented using a linked list.

The discussion then went beyond simply implementing a queue.

We talked about:

Memory constraints
Memory allocation
Lock mechanisms
Thread safety
Trade-offs between different implementations
What happens when the queue grows
How the underlying implementation affects performance
The interviewer kept asking “what if?” questions, which made the discussion more interesting.

This round taught me that in a design-oriented interview, it’s important to understand not only how to implement something but also why a particular implementation makes sense under different constraints.

SQL
After the design discussion, I was given a database schema and asked to write SQL queries.

The focus was on writing the queries in an optimized way.

The interviewer went deeper into the projects I had worked on and asked about:

My contribution
Technical decisions
Challenges I faced
Why I chose certain approaches
Overall system design
Round 3 — Culture Fit
This was the final round. The discussion was much more conversational compared to the first two rounds.

I was asked : Why interested to join blinkit ?

I was also asked to name a feature I liked about Blinkit and one that I didn’t like. and a lot of behavourial questions like what can I bring to the table . What is something which distinguishes me from others. etc.

The round ended with an offer discussion.

And that’s how the interview process ended.

Final Result — Selected 🎉
I received the offer and was selected for the SDE-1 role at Blinkit.

Preperation : I solved the striver sheet and studied system design through hello interview. Prepared the behavourial questions through leetcode discussion.