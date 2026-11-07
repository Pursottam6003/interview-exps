IBM (Winter Intern + FTE) 
Role: Software Developer
Batch: 2027

The entire process had 4 rounds:

1. Virtual HackerRank OA — 2 DSA questions
2. Offline OA in college — 1 DSA + 1 repository-based debugging question
3. Knockri-based interview round
4. Final HR + Technical Interview

The final interview started with a brief intro and questions revolving around my resume and projects — why I built them, what's their significance, what problem they solve, and why I chose the technologies I used. I was also asked to rate my technical skills across the technologies mentioned on my resume, along with questions about my internship work, what I worked on, and what my contribution was.

After this, we moved into the technical discussion. I was asked to rate myself across different technologies like DB, Java, frontend, backend, etc.

Then came the first question:

Suppose you are given an employee table where 3 attributes are there — "eid", "ename", "esalary". Write a SQL query to find the second-highest salary.

Followed by this, suppose that the salary of each employee keeps changing every month. I want to also know the previous salary of a particular employee. How will you handle it?

I was then asked to write a query to find the previous salary of a particular employee.

Again a follow-up:

«I don't want only the immediate previous salary. I want all the salary changes of every employee. How will you handle this? What changes will you make to the database schema?»

Why would you create a separate table for salary history?

Explain normalization. What's 2NF...

Then suppose you have millions of records to process, but your API has a limit on the number of records it can process per request. How will you make sure the processing happens?

Then we discussed batch processing. There were a few questions around batch processing, followed by writing the code for how I would handle the above situation based on this particular scenario.

We discussed some cases. Then came another follow-up:

Suppose the API limit is reached, how will you handle it in batch processing?

I discussed chunk size and related handling, followed by writing the exact PostgreSQL query to calculate the chunk size.

Suppose you are working on a production-grade system where a continuous stream of data keeps coming from an upstream system and you have a UI where you show some analytics based on that, but the expected result is not being reflected on the UI.

Now tell me the entire flow of how you will debug and rectify the issue.

There were multiple cross-questions based on the approach.

Then another scenario:

Suppose you are working in a team where you need to reduce the headcount without affecting the efficiency and work pace.

Explain the exact parameters which you will try to find and how you will approach this problem.

I had one of my projects, Vulnerability Tracker, where I automated the entire workflow of vulnerability management in my team, so the expectation was to answer everything around the project and the automation workflow.

Verdict: Selected