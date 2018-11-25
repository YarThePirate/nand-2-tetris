# Introduction
## Unit 0.1: The Road Ahead

As you might guess, this video doesn't have a lot of course material. It just outlines the reasons for the course and outlines what we are going to learn.

It does have a good summary of implementation vs. abstraction, however, that I'd like to record.

It says in computer science, you don't need to worry about the *how*, only about the *what*. And in this context, the *how* is the implementation, where the *what* is the abstraction. This is why most "intro to programming" courses teach you the *what* of printing to the screen, without teaching *how* that actually happens under the hood.

In other words, the abstraction is the promise of what our programming language is supposed to do. We just have to worry about the *interface* defined for the abstraction we're building on top of.

## Unit 0.2: From Nand to Hack

Nothing new here. Just an outline of how we're going to build a (simulated) hardware platform from logic gates. Specifically, logic gates built using only Nand gates. Neat.

## Unit 0.3: From Hack to Tetris

Same as Unit 0.2, except for the higher-level stuff.

## Unit 0.4: Project 0

Nothing relevant here. Just a description of Project 0, which justs tests your ability to reach the website, create a `.zip` archive and upload to Coursera.

Now the real fun begins.

## Reading

One final area of interest is the reading for this section, the introduction to *The Elements of Computing Systems*, the textbook for the course.

It mostly re-hashes what the videos covered, but with some added detail.

Of note: most standard services used by programming languages (i.e., C's `printf();`) are implemented either in the **standard library** of that language, or else in the **operating system** itself. Or, it could be a combination of the two. Definitions for both of these terms will be found in chapter 12 (a link here would be nice).

But basically, an operating system can be broken down into:
- libraries of mathematical functions
- string operations
- memory allocation tasks
- I/O routines

As well as some other things, such as thread and process management.

This course's high-level language will be called "Jack". It's not really used for anything outside of this course. Jack compiles to a machine-independent byte code, like Java or C#. (And apparently, writing an assembler is a "relatively simple task"... I'm looking forward to chapter 6).