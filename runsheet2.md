---
title: The Road to Test Driven Development
description: Runsheet
layout: default
---

## 13:00 Micro Testing

What is a _Micro-Test_?

Spiffy
- __S__ mall
- __P__ recise
- __I__ ndependent
- __F__ ast
- __F__ lexible
- y

3 Axes:
- Complexity: easy-hard
- Collaboration: solo-group
- Timing: after-before

Optional structure of a micro test:
- Three As: Arrange, Act, Assert
- Fixtures: setup, test, teardown


## 13:30 Test Thinking

What should we test and what are the goals of micro testing?
Not:
- 100% coverage 
- One test per method
- Catch-em-all! Find every possible bug

Interesting:
- code that's called from _everywhere_
- code with lot's of impact - anything with people's money or welfare
- code we're unsure about
- code that has a bug
- code that has effects in "unrelated" areas 
- the behaviour that is specific to the code
- Use Your Judgement

## 14:00 Exercise

Test after code, simple code

[Hangman](https://pete-the-programmer.com/tdd-ex-micro1/)


## 15:00 Break

## 15:15 Exercise 

Test after code, complex code

[Hangman2] (not complete)

## 16:30 Wrap up

Now you can: 
- Identify and classify code smells in production code [(here)](https://refactoring.guru/refactoring/smells){:target="_present"}
- Use a library of refactoring techniques to remove code smells without breaking functionality [(here)](https://refactoring.guru/refactoring/techniques){:target="_present"}
- Design and implement micro-tests to detect existing production code functionality changes
