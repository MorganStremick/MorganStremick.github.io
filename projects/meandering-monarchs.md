---
layout: project
type: project
image: images/checkerboard.png
title: Meandering Monarchs
permalink: projects/meandering-monarchs
date: 2019-01-27
labels:
  - Javascript
  - Latex
summary: An exploration of the Meandering Monarchs problem, including solutions in specific cases and a simulation.
---

A basic description of the meandering monarch problem is as follows: Given a board that is four tiles wide by four tiles tall, and a chess piece, which falls uniformly and at random on the board, find the probability that the chess piece lands on certain tile after n turns, if at the start of each turn the chess piece moves uniformly and at random to any of the adjacent tiles. Here, adjacent may be defined differently for different chess pieces. What appealed to me about this problem is that the results coincide very nicely with our intuition. For more information and a solution please visit the following overleaf document: [solution](https://www.overleaf.com/read/pvtxkrgtwtcx). If you are interested in a simulation of the experiment, then please refer to this GitHub repository: [simulation](https://github.com/MorganStremick/meandering-monarchs). Just as a note, you can change the dimension of the board to be anything you want. You can even make it 3-dimensional, or 4! It's very cool, I know.

While the solution draws from probability, of course, I was happy to be able to use some of my linear algebra experience as well. To calculate the eigenvalues required a short hop over to Octave, which I became more familiar with in my numerical analysis course, and to simulate the experiment I used Javascript, which is maybe not the best choice for the task, but nevertheless gave me the chance to demonstrate my current understanding of the language and learn a bit more about prototypal inheritance. Lastly, I used Latex to summarize my findings, competency with I developed over the course of many semesters by writing lab reports for physics and submitting wrtiting assignments for real analysis. In summary, while the project wasn’t expansive by any means, it allowed me to dip into a breadth of past experience, which was kind of fun, to say the least.
