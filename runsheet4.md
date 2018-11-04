---
title: The Road to Test Driven Development
description: Runsheet
layout: default
---

## 13:00 Test Driven Development

What is a _TDD_?

[Classic TDD Cycle](assets/images/tdd.png){:target="_present"}

[...with integrate step](assets/images/tdd4.png){:target="_present"}

TDD and Formal Design discussion:
- [what is design?](what_is_design){:target="_present"}
- In TDD design is _Inverted_  (design-code-test -> test-code-design)
- in TDD design is _Distributed_ (each step improves and informs the design)
- This leads to a premise of _Emergent Architecture_ and is an ultimate conclusion of the YAGNI principle [incremental car](https://blog.crisp.se/wp-content/uploads/2016/01/mvp.png){:target="_present"}

### 14:00 Exercise TDD

Test before code, increasing complexity (refer to axes of testing)

[Total Complexity Games](https://pete-the-programmer.com/tdd-ex-tdd-final/){:target="_present"}


## 16:00 Extras for experts

Testing in an MVC pattern:
- Models are about business logic.  Should have NO dependencies
- Views are about display.  Should have no logic (no if statements) - pre-prepare everything in the view model
- Controllers are about flow. Is the user auth'd, where should they be routed to, where should they go next, what pieces of view-model does the view need.

So test:
- Models: classic logic and classes tests
- Views: keep these THIN and most easily tested at the system level (e.g. selenium)
- Controllers: all about the user context and which view is presented (not what's in it).  Use "Request" static object as little as possible - inject it if really needed.


## 16:30 Wrap up

Now you can: 
- Isolate interesting code components for testing independently
- Understand how micro-testing fits into quality control framework
