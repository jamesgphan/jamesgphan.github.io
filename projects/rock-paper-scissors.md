---
layout: project
type: project
image: img/rockpaperscissors.jpg
title: "Rock Paper Scissors Game"
date: 2022
published: true
labels:
  - C
summary: "A rock paper scissors game written in C for ICS 212."
---
<p align="center">
  <img class="img-fluid" src="../img/rockpaperscissorssmall.jpeg">
</p>

This is a simple rock paper scissors game that can be played against the computer. The game keeps track of the stats and the user can choose when to quit playing. The user is allowed to input a choice between rock, paper, or scissors. The computer chooses its turn via a random value. The turns are compared, and the score is recorded. 

This project was perhaps the second game I ever created. The biggest hurdles for me back then were dealing with user input and potential errors, and outlining all the cases in which to determine a win, loss, or tie. Those would be sections of my code that could be shortened in the future.

```
$ ./program
This is a rock-paper-scissors game.
To quit the game, press Q or q and Enter.

Enter 'r', 'p', or 's' for rock, paper, or scissors: r
Rock vs. Rock. TIE!

Enter 'r', 'p', or 's' for rock, paper, or scissors: p
Paper vs. Scissors. COMPUTER WINS!

Enter 'r', 'p', or 's' for rock, paper, or scissors: q

User Wins: 0
Computer Wins: 1
Ties: 1
```
[Source code](https://github.com/jamesgphan/rock-paper-scissors)
