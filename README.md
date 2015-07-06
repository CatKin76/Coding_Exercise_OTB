# Coding_Exercise_OTB
# Java Attempt 6th July 2015

#To follow will be an attempt to solve the problem in Java programming language. When I first thought of using Java the
#first thing that sprang to my mind was that I would need to use arrays some how. I would need the program to follow 
sets of rules, and some kind of order. My first step is to do some more research on arrays and sorting the data held in
arrays and also dependencies.

coding_exercise.md
The Challenge
Imagine we have a list of jobs, each represented by a character. Because certain jobs must be done before others, a job may 
have a dependency on another job. For example, a may depend on b, meaning the final sequence of jobs should place b before a. 
If a has no dependency, the position of a in the final sequence does not matter.

*Given you’re passed an empty string (no jobs), the result should be an empty sequence.

*Given the following job structure:
a =>
The result should be a sequence consisting of a single job a.

*Given the following job structure:
a =>
b =>
c =>
The result should be a sequence containing all three jobs abc in no significant order.

*Given the following job structure:
a =>
b => c
c =>
The result should be a sequence that positions c before b, containing all three jobs abc.

*Given the following job structure:
a =>
b => c
c => f
d => a
e => b
f =>
The result should be a sequence that positions f before c, c before b, b before e and a before d containing 
all six jobs abcdef.

*Given the following job structure:
a =>
b =>
c => c
The result should be an error stating that jobs can’t depend on themselves.

*Given the following job structure:
a =>
b => c
c => f
d => a
e =>
f => b
The result should be an error stating that jobs can’t have circular dependencies.
