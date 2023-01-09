## See the live demo 👇

https://kepplin.github.io/odin-rockpaperscissor/

![demorps](https://user-images.githubusercontent.com/107027281/211229607-3701be47-54f3-47c3-b7d2-4ceb66083f8e.png)

## About

This was a two part project for [The Odin Project](https://www.theodinproject.com/lessons/foundations-rock-paper-scissors). The first part was simply making a rock paper scissors game to be played in the console. The second part was to add an UI to this page. The second part of this project felt somewhat overwhelming and I found myself finding a lot of bugs. Not my proudest project...

## Instructions

- Click on a button to select your choice for rock paper scissors against the computer. As soon as you press a button, the computer will randomly choose and the text will announce who won the round and got a point.

- The first to 5 points is deemed the winner.

- Click the 'Play again' button to reset the scores.

## How it Works

1. The user clicks a button to lock in their choice. When this happens, the functions getComputerChoice(), compareChoices() and incrementScore() run.
2. Within getComputerChoice(), the computer randomly chooses between 'Rock', 'Paper', or 'Scissors'. It does this through choosing a random number between 1 and 3, and assigning a value to that number. So if the number is 1, the computers choice is rock, if the number is 2, the computers choice is paper, etc.
3. compareChoices(), uses a bunch of if statements to determine who won the round. It returns a string with either 'Player wins' if the player won, or 'Computer wins' if the computer won.
4. incrementScore(), increases the winners point by 1, through scoreSpan.innerText = parseInt(scoreSpan.innerText) + 1
5. When clicked, the play again button simply reloads the page through 'location.reload()'.

## Features?

This page is in desperate need of styling. The code is also a bit ugly, and everything is text based so that needs refactoring too.
