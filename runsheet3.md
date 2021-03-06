---
title: The Road to Test Driven Development
description: Runsheet 3
layout: default
---

## 9:00 Recap

Recap from last time.  What have we learned?
- spiffy
- interesting
- name some refactoring techniques
- favourite smell

Why are we doing this? (Cynefin)

## 9:20 Advanced Testing

Context: Testing pyramid

Side effects

## 9:30 Test doubles, Fakes and Mocks

Reflect on previous exercise:
- Is this test even a micro-test? (draw dependency diagram)
- It's not independent - so what can we do about it.

We can isolate the SUT (subject under test) by swapping out the dependency for a fake one under "our control".

Definitions [(by Fowler)](https://martinfowler.com/bliki/TestDouble.html){:target="_present"}:
- Dummy: a placeholder value
- Stub: pre-canned response to a request
- Fake: working implementation simplified
- Spy: a fake or stub that remembers how it was used for interrogation by the test
- Mock: a double that verifies all expected calls were made

## 10:00 Break

## 10:15 Exercise Stubbing by hand

Checkout the ``advanced`` branch.

[Hangman ``advanced``](https://pete-the-programmer.com/tdd-ex-micro1/advanced){:target="_present"}

## 11:15 Exercise Mocking using a library

Intro to [MoQ](https://raw.githubusercontent.com/moq/moq4/master/README.md){:target="_present"} (may need intro to lambdas?)

Reset to the ``advanced`` branch root and try again after introducing 

[Hangman ``advanced``](https://pete-the-programmer.com/tdd-ex-micro1/advanced){:target="_present"}

## Lunch
