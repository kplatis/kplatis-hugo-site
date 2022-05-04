+++
author = "Konstantinos Platis"
title = "Basic Programming Principles"
date = "2022-05-04"
description = "Sample article showcasing basic Markdown syntax and formatting for HTML elements."
tags = [
    "principles",
    "theory"
]
categories = [
    "programming",
]
series = ["Programming Guide"]
+++

# Table of contents
1. [Principle of the Least Privilege](#principle-of-the-least-privilege)
2. [DRY: Don't Repeat Yourself](#dry-dont-repeat-yourself)
3. [Composition over Inheritance](#composition-over-inheritance)
4. [Single Responsibility / Separation of concerns](#single-responsibility--separation-of-concerns)
5. [You aren't going to need it](#you-arent-going-to-need-it)

## Principle of the Least Privilege

📖 [Wiki page](https://en.wikipedia.org/wiki/Principle_of_least_privilege)

In computer science, every module must be able to access only the information and resources that are necessary for 
its legitimate purpose.

Some examples of POLP are the following:

- `React` Components should receive as props only the information they need
- `Permission` Each user/group should have access only to the necessary information

## DRY: Don't Repeat Yourself

📖 [Wiki page](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself)

This one is trivial. In programming, it is an anti-pattern to duplicate code or data if it can be avoided. If you have
ever copied and pasted code within your code, it's not DRY code. When the DRY principle is applied successfully, 
a modification of any single element of a system does not require a change in other logically unrelated elements.

Some examples of DRY include:

- `React` Components that share logic should be written as a single component
- `Functions` If there is a piece of code that repeats itself, it should be encapsulated in a function

## Composition over Inheritance

📖 [Wiki page](https://en.wikipedia.org/wiki/Composition_over_inheritance)

According to the **Composition over inheritance** principle, classes should achieve polymorphic behavior and code reuse
by their composition rather than inheritance from a base or parent class. In other words a class should take shape using
multiple classes that each one of them contributes one or more features. With composition, it is easier to change behavior
on the fly.

## Single Responsibility / Separation of concerns

📖 [Wiki page](https://en.wikipedia.org/wiki/Single-responsibility_principle)

According to the **single responsibility principle**, each module of a program should provide one specific functionality.

Some examples of this principle:

- `React` Each component should be responsible for implementing on specific functionality of the application

An abstract version of the single responsibility principle, is the **Separation of Concerns**, which constitutes a design
principle for separating a computer program into distinct sections.

## You aren't going to need it

📖 [Wiki page](https://en.wikipedia.org/wiki/You_aren%27t_gonna_need_it)

In other words, you should not implement a functionality that is not currently needed.

