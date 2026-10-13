# Overview

This is a simple Pong clone made with Löve 2D and Lua, with support for 2 players and sfx.

Pong is the simplest of games, there are 2 paddles for 2 players and a ball.
Once the "enter" or "return" key is pressed the ball randomly goes to one of the player's direction, the player goal is to use the paddle to not let the ball pass, because if it does their opponent scores a point.
To win you just have to score 3 points first.

**Controls:**
Enter/Return -> Starts game and rounds once a player scores
Esc/Escape -> Exits the game

Player 1 -> Uses "w" to go up and "s" to go down
Player 2 -> Uses "up" arrow key to go up and "down" arrow key to go down

**Why write yet another Pong clone?**
Since I was little I wanted to create my own games. Only now as a software developer I have the skills to do so, I wanted to know more about graphics libraries (more specifically Löve 2D) and also learn more about Lua since it was created in my beloved Brazil and I have never experimented it. Pong is a simple game, yet it covers the fundamentals of creating a video-game. Also I knew that Harvard had an amazing free class covering this exact project.

**How to play**
Just run the executable found in the main directory, since the source code is open for you to read you can exactly what you are going to execute.
If you are using a Linux or MacOs/OSX machine, you will have to compile the source code, for this you can follow the tutorial on the official Löve 2D website below:
[Game Distribution](https://www.love2d.org/wiki/Game_Distribution#:~:text=Once%20you%20have%20packed%20your%20game%20into%20a,file.%20The%20resulting%20file%20is%20your%20game%20executable.)

## Development Environment

I used VS Code with the "Löve 2D support" extension by Pixelbytes Studios on a Windows 11 Machine.
I used The Lua programming language and a Game development library called Löve 2D (very famous now thanks to Balatro).

## Useful Websites

[CS50 2D](https://cs50.harvard.edu/games/weeks/0/)
[Löve 2D](https://www.love2d.org/wiki/Main_Page)

## Future Work

- Add framerate visualization for debugging
- Add ball velocity increment
- Add turns once a player scores so they can start if they marked a point
