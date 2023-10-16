# FIZZBUZZ KATA BY LOREM IPSUM VERSION

## Introduction

This kata, taken from a popular children's maths game (or student drinking game), is the starting point on the TDD track.

We'll emphasise the following:

- Start by writing a failing test for the simplest behaviour.
- Implement the simplest amount of code needed to make the test pass.
- As you add more tests, refactor to make the code more generic and more suitable.

## Instructions

Write a function that takes a number and the output is its string representation.

Your function should comply with the following additional rules:

- If the number is a multiple of three, return the string "Fizz".
- If the number is a multiple of five, return the string "Buzz".
- If the number is a multiple of both three and five, return the string "FizzBuzz".
- If the number isn't a multiple of the previous cases, return the number to string.

## TDD Strategists:

1. **Fake it**:
   The "Fake it" strategy in TDD involves starting with a simple, hardcoded implementation that returns the expected output for a specific test case. The goal is to get the test to pass quickly and have a functioning piece of code. However, this initial implementation does not solve the problem completely or generically. Once the test is green, you gradually improve the implementation through additional test cases, making the code more generalized and refining it iteratively.

2. **Triangulation**:
   The "Triangulation" strategy is used when you are uncertain about the best implementation for a given functionality. Instead of going for an obvious implementation right away, you start with at least two different test cases that should have different outcomes. This approach prevents you from taking shortcuts and guides you towards a more robust and flexible solution. You refine your code to handle both test cases correctly, and by doing so, you converge on a better design.

3. **Obvious Implementation**:
   The "Obvious Implementation" strategy suggests that you start with a straightforward and easy-to-implement solution for the given problem, even if it is not the most efficient or complete one. You first write a test that defines the desired behavior, and then you implement the simplest code that makes that test pass. The goal is to get immediate feedback and build momentum to progress towards more complex solutions while always ensuring the tests are passing.
