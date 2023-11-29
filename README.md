# Fundamentals of Data Analysis

## Summary
This repository contains all of the code and notebooks 

## Table of contents
* [Weekly tasks](#weekly-tasks)
  * [Task 1](#Task 1)

## Weekly Tasks  

## ***Task 1***
#  Collatz sequence

      The Collatz conjecture is a famous unsolved problem in mathematics. The problem is to prove that if you start with any positive integer $x$ and repeatedly apply the function $f(x)$ below, you always get stuck in the repeating sequence 1, 4, 2, 1, 4, 2, . . .
      
      $$ f(x) = \begin{cases}
      x\div 2 & \text{if $x$ is even} \\
      3x+1 & \text{otherwise}
      \end{cases} $$

      For example, starting with the value 10, which is an even number , we divide it by 2 to get 5.  Then 5 is an odd number so, we multiply by 3 and add 1 to get 16.  Then we repeatedly divide by 2 to get 8, 4, 2, 1. Once we are at 1, we go back to 4 and get stuck in the repeating sequence 4,2,1 as we suspected.

      Your task is to verify, using Python, that the conjecture is true for the first 10000 positive integers.

This was a relativey
https://stackoverflow.com/questions/13366830/collatz-conjecture-sequence
Build on pythong coding used in previous module

## ***Task 2***
#  Pengiun Dataset Overview

Give an overview of the famous penguins data set, explaining the types of variables it contains. Suggest the types of variables that should be used to model them in Python, explaining your rationale.