# Task 2 – Classroom Seating Arrangement Problem

The classroom seating arrangement problem demonstrates the difference between problems that are easy to verify and problems that are difficult to solve.

The teacher must arrange students while ensuring that:

* Friends are not seated next to each other.
* Students from the same city are not seated next to each other.

## Relationship to P and NP Problems

A problem belongs to class P if it can be solved efficiently using a polynomial-time algorithm.

A problem belongs to class NP if a solution can be verified quickly even though finding the solution may be computationally difficult.

In the seating arrangement problem, checking whether a seating plan satisfies the constraints is simple. The teacher only needs to check adjacent pairs of students. This takes linear time.

However, finding a valid seating plan requires testing many possible permutations of students. The number of possible arrangements grows factorially with the number of students.

## Brute Force Approach

A brute force approach generates all possible permutations of student arrangements and checks whether each arrangement satisfies the constraints.

This method guarantees that a correct solution will eventually be found if one exists.

However, the number of permutations grows very rapidly. For example:

* 5 students → 120 arrangements
* 10 students → 3,628,800 arrangements
* 15 students → more than 1 trillion arrangements

Because of this factorial growth, brute force becomes impractical for large classes.

## Heuristic Approach

A heuristic approach attempts to find a good solution more quickly without testing every possible arrangement.

Examples include:

* Seating students with many friends first
* Separating students from the same city early

Although heuristics do not always guarantee the optimal solution, they significantly reduce computation time and are often acceptable for real-world problems.

