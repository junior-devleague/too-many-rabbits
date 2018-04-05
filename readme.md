---
author:
- Somewha7
title: 'Too Many Rabbits!'
type: Activity
---

Summary
=======

Activity for learning about recursion using the fibonacci sequence

Objective
=========

Rabbits... Rabbits, rabbits, RABBITS! You got a pair to keep as pets, but quickly found that one pair became two, two became three, three became five, and now there are more than you can count! Chewing through cables, eating the furniture, there's no peace to be had anymore! At this point you just want them out of your house, but you have no clue how you can tell when you've found them all... Create a function in python that models the fibonacci sequence so that you know how many pairs of rabbits you need to search for in order to avoid leaving any of them behind.

Prerequisites
=============

-   Basic usage of Python REPL


Requirements
============

-   Shell terminal or Python IDE
-   A bunny overabundance

Desired Outcomes
================

-   Basic understanding of recursion

Tasks
=====

1.   Create a new python file, or create a new REPL in repl.it
2.   Create a new function, calling it something like countAt(iteration)
3.   Find & establish the **base case(s)**. (*HINT:* when will the function *not* call itself?)
4.   Create the recursive portion of the function -- fibonacci sequence is function(input) = function(input-1) + function(input-2)
5.   Return the function with a value equal to the total from the fibonacci sequence
6.   Use an input to get the iteration to go to
7.   run the function using that iteration
8.   Print how many rabbits there are at that iteration

### Choto Stretch Goals
-   Make the print statement gramatically correct if there's only 1 rabbit
-   Use memoization to increase the efficiency of your function. [Explanation](https://stackoverflow.com/questions/1988804/what-is-memoization-and-how-can-i-use-it-in-python)
-   Print the iteration & amount of rabbits at that iteration for every even iteration (*HINT*: this depends on using your cache from the previous stretch goal)
-   Take a user input of 2 iterations between which to calculate the average increase in rabbits/generation. Then, print that information.
