---
layout: essay
type: essay
title: A Newbie's Case for Javascript
# All dates must be YYYY-MM-DD format!
date: 2019-01-16
labels:
  - Javascript
---

## Fun with Functions

Coming from a background of Java, C, and C++, the most striking feature of Javascript is the sheer amount of freedom it gives you to manipulate functions, to pass functions to other functions, return functions, and store functions. Javascript may not be a functional language, but it does make functional programming exceedingly easy. Some of the advantages of functional programming include greater flexibility, brevity, and enhanced readability. To demonstrate this, suppose you are tasked with generating the first n terms of a sequence. You may have to do this multiple times and for wildly different sequences. Fortunately, you’ve been known to dabble in the dark arts every now and again, and so, upon selling the smallest, itsy-bitsiest, teensy-tiniest piece of your dark, stygian soul to Satan, you get them to concede that every sequence you encounter will have a closed form solution. The first three sequences you encounter are the fibonacci sequence, the sequence of squares, and the powers of 2. One way to approach this problem is to write a new function for every sequence, as in generateSquareNumbers, generatePowersOfTwo, and generateFibonacciSequence. However, an alternative approach would be to create a function called generateSequence which takes, as its arguments, a function, func, for generating each individual term, and the length, n. The code, in either case, might look something like this: [example](https://jsfiddle.net/morgan_stremick/7cksewb5/).

## Reading Code
The main benefit of functional programming to readability is that it breaks up complicated functions into smaller, bite-sized pieces. Whereas the function definition of generatePowersOfTwo(n) is a run-on sentence, the definition of generateSequence(powersOfTwo, n) is a neat and tidy, perfectly punctuated paragraph, which you can digest one sentence, or in this case, one function, at a time. An additional benefit is that once you understand what generateSequence does, you are, by necessity, halfway to understanding what generateSequence(fibonacci, n) does. In this way, functional programming allows you to highlight meaningful similarities between functions so that you can focus on what sets them apart. In general, the way that functions are composed with other functions can communicate a lot about what a piece of code was written to accomplish. Therefore, aiding in readability.

## Writing Flexible Code
This flows into the next point, which is that functional programming makes it easier to write flexible code. Nowadays, when more and more software is being developed continuously, it’s important to be able to accommodate an ever-expanding list of features and respond swiftly to changing demands. The reality is that it takes precious time to declare arr, write a for loop, and surgically transplant the body of powersOfTwo into the body of generatePowersOfTwo. If that wasn’t enough, you have to start from scratch each time you encounter a new sequence. On the other hand, by using functional programming, you can immediately sidestep all of the tedium. For example, instead of writing what amounts to a copy of generateSequence wrapped around powersOfTwo, you simply have to call generateSequence(powersOfTwo, n). In general, it takes less time and energy to build on existing code that utilizes functional programming.

## So Much More
Overall, I am thoroughly enjoying Javascript. Some of the other features that I enjoy include dynamic typing and prototypal inheritance. I’ve barely dipped my toe in the water when it comes to the latter. However, I am most excited to explore the possibilities of prototypal inheritance, multiple inheritance, delegation, and concatenation.
