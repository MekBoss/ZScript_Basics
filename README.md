# ZScript Basics: A Guide for Non-Programmers (from a non-programmer)

## Contents

1. [Introduction](#Introduction)
2. [Why ZScript?](#Why ZScript.md)
3. Classes instead of actors
4. Anonymous functions
5. Variables and data types
   1. Data types
6. Pointers and casting
   1. Basic pointers
   2. Using pointers in ZScript
   3. Casting and custom pointers
   4. Type casting
7. Custom functions
   1. Non-void functions and return values
   2. Virtual functions
8. ZScript Virtual Functions
   1. Common virtual functions
9. Event Handlers
10. Arrays
    1. Dynamic arrays
11. Flow Control
    1. Operators
       1. Checks
       2. Setters

## Introduction

Everyone is talking about ZScript. *DECORATE is dead*, they say. *You should be using ZScript*, they say. *I’m not gonna help you with your awful hacky DECORATE code,* they say.

You look around, confused. You’ve been using DECORATE for years now. You check ZDoom Wiki, and it’s still almost all about DECORATE. ZScript is barely documented. They tell you to look into ZScript code in gzdoom.pk3, and when you do, it makes your head spin. DECORATE is plain and simple, and with ZScript you don’t understand what’s going on at all.

Confusion leads to frustration, frustration leads to resentment. All the cool kids are playing with ZScript, and you don’t even know how and where to start. You wonder if your Doom modding career is over.

Sounds familiar?

That’s where lots of DECORATE users (some of them—known and respected modders even) have been finding themselves ever since ZScript became a thing. The reason is simple: ZScript is basically a programming language, and DECORATE has barely anything to do with that concept. As a result, there are *plenty* of people who’ve been doing just fine with DECORATE, and just a *handful* of people with previous programming experience who find it much easier to use ZScript. And it’s not surprising, ZScript *is* easier to use (more on that later) but it’s not easy for a non-programmer to begin.

I decided to write this short entry guide to help alleviate exactly that: it covers some basic programming concepts in simple terms which will help you to *get started*. Starting, after all, is the hardest part.