---
layout: post
title:  "Week 2 Update"
date:   2016-01-31 12:00:00
tags: [update]
---

## Current Status ##

### What did you do this past week? ###

This past week I finished up Project 1, except for some issues on github and
pushing my tests to the class repository, which shouldn't take me too long to
do. I also worked on a little side project related to Collatz, which I wrote
about below in my tip of the week section.

### What's in your way? ###

As of right now, I have no blockers.

### What will you do next week? ###

This week, I will finish up the first project. This includes just generating
some acceptance tests and finishing up my unit tests. Somewhere in this work I
will likely finish up the 15 issues I need to create (I'm at 10 now), which
should complete this project for me.

## Course Reflections ##

So far the class has been very good. I did will on the quizzes with the
exception of the most recent one, since I didn't read and got tripped up on
things like Javascript's block scoping (or lack of thereof). That should be
fine, since I typically do the readings and we will likely get some dropped by
the end of the semester, but it was a certainly a good lesson to learn this
early how important the readings are going to be for our performance in the
course.

## Tip of the week ##

In the last week, I worked on a little side project, an online judge for collatz
in the same effect as Sphere, with a few slight differences (including the fact
mine works to the specifications we were given at the start of the project).
Instead of giving a specific input and expecting a specific output, mine uses
pre-generated collatz cycle counts to generate 100 random tests to run on any
arbitrary input phython script, and will judge it for correctness. Additionally,
in the event the input code produces the wrong output, it generates an output
showing the differences between the two files. I built this using Python3,
flask, mongodb, React, and Docker. I do have it available online
[here][collatz-judge], though I've only tested my project specifcally on it, so
I have no garuntee it's always correct. The source code for the project is
available [on Github][collatz-judge-gh].

[collatz-judge]: http://collatz.robertlyn.ch/
[collatz-judge-gh]: https://github.com/BobertForever/collatz-judge