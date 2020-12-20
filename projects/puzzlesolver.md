---
layout: post
title: 'Puzzle Solver: The Search for Intelligent Solutions'
---

<ul>
  <li><a href="https://github.com/sylvia-cs/PuzzleSolver">Github Repo</a></li>
  <li>Tools: OCaml (functional programming), OCaml Graphics</li>
</ul>  

With a partner, I developed an OCaml program that solves maze and tile puzzles, displaying the process in OCaml graphics along with real-time performance metrics. Our software rested heavily on modular coding principles that allow for the reusability of functions across different user-inputted puzzles and various solving algorithms. The underlying implementations of the BFS, fast BFS, and DFS solvers are developed with stack and queue structures, and I used OCaml’s higher-order functions to write an abstract, efficient solver function that searches neighbors and stores their states.

<img style="margin-right: 2rem; width: 250px; height: auto" src="{{ site.baseurl }}/assets/animation/puzzlesolve.gif">
<img style="width: 250px; height: auto" src="{{ site.baseurl }}/assets/animation/tile.gif">

This program allowed us to run experiments and conduct research on the effectiveness of various solvers for different situations, across different sizes, directions, and solvability. I developed an extensive performance testing system that feeds the program a variety of puzzle types while outputting their performance. See below for a detailed analysis of the time complexity and comparisons across different solvers and kinds of puzzles, considering the tradeoffs for each.

<h3 style="margin-top: 0; padding-top: 10px; padding-bottom: 10px" class="header">Writeup of Experimental Results</h3>
<iframe src="/assets/files/writeup.pdf" width="100%" height="500px"></iframe>