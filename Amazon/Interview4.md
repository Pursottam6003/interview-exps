Hi everyone, I recently went through the Amazon SDE2 interview, please find the details below

Round 1: Online Assessment
* 2 DSA Questions (1 Medium + 1 Hard)
* AI Debugging Round, given a code repository with a inbuilt LLM that will give very minimal details to our questions related to the repository and not the complete the solution

Round 2: Phone Screen (30 mins)
* DSA Question: Minimum Cost For Tickets

Round 3: Low-Level Design (LLD)
* Design Splitwise (Focus was on coding the debt-simplification algorithm to minimize transactions)

Round 4: High-Level Design (HLD)
* Design a Visitor Management System (like MyGate)

Round 5: DSA Round
* Q1: Course Schedule II (Topological Sort)
* Q2: Shortest Path Visiting All Nodes (Graph problem wrapped in a custom story), the interviewer expected only the approach and not the working solution but I felt it hard to even come up with the approach as it is a NP hard problem similar to travelling salesman problem

Round 6: Bar Raiser Round

Need to implement the below, by using the appropriate Data structure and OOPS principles

APIs to implement: requestRunway and allocateNextSlot

Rules to handle:

Landings get priority over Takeoffs (FIFO within same group)

Fuel Starvation: Flights with < 15 mins fuel are "Critical" (Top Priority, sorted by least fuel left)

Takeoff Starvation: Takeoffs waiting > 60 mins prioritize over standard landings (but below critical landings)


Every round had Amazon LP questions covered for around 20 minutes



Bar raiser round question

Design the models and APIs for a single-runway airport, handling arriving and departing flights.
APIS:
- "requestRunway': Called by arriving / departing flights to use the runway.
- "allocateNextSlot: Return "flightld that next gets the runway.
RULES:
1. Landings have priority over Takeoffs. And within their own categories, flights are processed FIFO.
2. Fuel Starvation: Flights with < 15 minutes of fuel are "Critical" and are a TOP priority, sorted by LEAST fuel remaining.
(Note: Fuel continuously depletes in the air)
3. Takeoff Starvation: A takeoff waiting > 60 minutes becomes "Delayed" and prioritizes over Standard Landings, but NOT over Critical Landings.