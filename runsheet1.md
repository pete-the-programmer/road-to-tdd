---
title: The Road to Test Driven Development
description: Runsheet
layout: default
---

## 9:00 Intro

## 9:30 Code Smells

What are _Code smells_
- a kind of technical debt (what's that) [video](assets/images/techdebt_small.mp4){:target="_present"}
- develop a nose for bad smelling code

Ref: [Reference](https://refactoring.guru/refactoring/smells){:target="_present"}

Ref (SQL): [SQL Reference](https://www.red-gate.com/simple-talk/sql/t-sql-programming/sql-code-smells/){:target="_present"}

Show the resource look through some titles.

[Samples](smells/index)

* Naming (not in resource)
* Duplication
* Dead Code
* [Long Method](smells/long_method){:target="_present"}
* [Comment](smells/comment){:target="_present"}
* [Primitive Obsession](smells/primitive_obsession){:target="_present"}

## 10:00 Refactoring

What is _Refactoring_

> A change made to the internal structure of software 
> to make it easier to understand and cheaper to modify 
> without changing its observable behaviour. 
> — Refactoring, Martin Fowler, page 53.

note:  non-functional changes are behaviour

Create a common language of how to manipulate code as a structure, rather than text.

[Reference](https://refactoring.guru/refactoring/techniques){:target="_present"}

## 10:15 Break

## 10:30 Exercise: Refactoring 1

[Smells](https://refactoring.guru/refactoring/smells){:target="_present"}:
- Speculative Generality

[Exercise: Vehicles](https://pete-the-programmer.com/tdd-ex-refactor1/){:target="_present"}

Focus on:
- making the bus and ferry the __same__ with _rename_ and _extract method_/_inline_
- _pull up_

Do it once. If we have time, demo it and then do it as a class again.

## 11:00 Exercise: Refactoring 2


[Smells](https://refactoring.guru/refactoring/smells){:target="_present"}:
- Primitive Obsession
- Temporary Field

[Exercise: Narrowed change](https://pete-the-programmer.com/tdd-ex-refactor2/){:target="_present"}

Narrowed change and scaffolding

## Lunch
