# ZScript Basics: A Guide for Non-Programmers (from a non-programmer)

## Contents

1. [Introduction](#Introduction)
2. [Why ZScript?](Why_ZScript.md)
3. [Classes instead of actors](Classes_instead_of_actors.md)
4. [Anonymous functions](Anonymous_functions.md)
5. [Variables and data types](Variables_and_data_types.md)
   1. Turning variables into actor properties
   2. Access modifiers
   3. Data types
6. [Pointers and casting](Pointers_and_casting.md)
   1. What IS a pointer?
   2. Basic pointers
   3. Most important thing about pointers
   4. Using pointers in ZScript
   5. Usage of custom pointers
   6. Type casting pointers
7. [Custom functions](Custom_functions.md)
   1. Non-void functions and return values
8. [Virtual Functions](Virtual_functions.md)
   1. ZScript Virtual Functions
   2. Common ZScript virtual functions
9. [Event Handlers](Event_Handlers.md)
10. Arrays
    1. Dynamic arrays
    2. Static arrays
11. [Flow Control](Flow_Control.md)
12. [Best Practices and Rules of Thumb](Best_Practices.md)

## Introduction

Everyone is talking about ZScript. *DECORATE is dead*, they say. *You should be using ZScript*, they say. *I’m not gonna help you with your awful hacky DECORATE code,* they say.

You look around, confused. You’ve been using DECORATE for years now. You check ZDoom Wiki, and it’s still almost all about DECORATE. ZScript is barely documented. They tell you to look into ZScript code in gzdoom.pk3, and when you do, it makes your head spin. DECORATE is plain and simple, and with ZScript you don’t understand what’s going on at all.

Confusion leads to frustration, frustration leads to resentment. All the cool kids are playing with ZScript, and you don’t even know how and where to start. You wonder if your Doom modding career is over.

Sounds familiar?

That’s where lots of DECORATE users (some of them—known and respected modders even) have been finding themselves ever since ZScript became a thing. The reason is simple: ZScript is basically a programming language, and DECORATE has barely anything to do with that concept. As a result, there are *plenty* of people who’ve been doing just fine with DECORATE, and just a *handful* of people with previous programming experience who find it much easier to use ZScript. And it’s not surprising, ZScript *is* easier to use (more on that later) but it’s not easy for a non-programmer to begin.

I decided to write this short entry guide to help alleviate exactly that: it covers some basic programming concepts in simple terms which will help you to *get started*. Starting, after all, is the hardest part.



## Important notes

1. This guide is aimed at people with prior DECORATE (and possibly ACS) knowledge. It implies that you know what GZDoom is, what actors are, how they're structured, how they interact with each other. All of those aspects are covered by [ZDoom Wiki](http://zdoom.org/wiki/Main_Page), so I don't feel there's a need to describe them within this guide.

2. While all code examples in the guide are made to be runnable, it's *not* recommended to use them as is: many of them are purposefully inefficient, and the guide tends to iterate over them, improving various aspects while explaining new techniques. Examples are meant to be just that: examples—not ready-made solutions.
3. This document is a guide, not a wiki. As such, it's designed to be read from beginning to end. Chapters are not self-contained and often rely on information explained earlier in the guide, so it's not recommended to skip anything.



### [>> Next: Why ZScript?](Why_ZScript.md)
