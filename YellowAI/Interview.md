SDE-1 Interview Experience | Yellow AI

Shortlisting Process

Recruiter reached out  and shared an initial interest form. The first interview was scheduled approximately one week later.

Round 1: DSA + Technical Discussion (60 Min)

Interviewer: SDE-3

Coding Questions (35 Min):

1. Maximum Altitude Gain (Easy): Given an array of altitudes, find the maximum difference between two elements where the smaller element appears earlier. O(N) solution.
2. Number of Disease Outbreaks (Medium): Given a 2D grid of healthy and diseased cells, count connected components using four-directional DFS/BFS.

Technical Discussion (25 Min):

* Kubernetes and Docker fundamentals
* AI Harness Engineering
* AI Security
* On-call incident handling (scenario-based leadership question)

Round 2: Backend System Design / LLD (90 Min)

Interviewers: VP and Cloud Engineer

Problem: Design a Conference Room Booking System

Office with 300 employees and 3 conference rooms.

Core Requirements:

* View available rooms, book, cancel, and reschedule.
* Design REST APIs, database schema, and entity relationships.
* Explain project architecture (MVC/layered).
* Database selection and justification.
* Authentication, authorization, and cloud deployment.

Follow-up Questions:

1. What happens when all rooms are booked?
2. How would you implement priority-based bookings (manager vs. associate)?
3. How would you restrict bookings during weekends or maintenance?
4. How would you prevent double bookings during concurrent requests?
5. How would you handle recurring meetings and buffer times?
6. How would you support timezone-based bookings?
7. How would you modify or cancel individual occurrences versus an entire recurring series?
8. What happens to existing and recurring bookings when an employee leaves the organization?

AI Discussion (Bonus):

* Smart meeting-time recommendations
* AI-based conflict resolution
* Cancellation prediction and automated booking
* Data and models required for these features