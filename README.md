# 2DPong
This repo consists of a version of 2D Pong.

To play the game:
- Clone this Repo.
- Open the .exe file in: ...\2DPong\builds ("..." being where you saved the Repo).

# Playing the Game

- The game has 2 paddles, 1 ball and a scoreboard.
- Use W and S and the Up and Down arrows to control each of the 2 paddles.
- The ball will automatically pop off in a random direction.
- Each player should use their respective paddle to block the ball from going past their paddle.
- If the ball reaches the other side of the screen then the opposing player gets a point.
- The first player to 10 points wins!

# Project Notes

This Project uses C# for all of the code and Unity for the graphical interface.
I created multiple scripts to manage the Ball and Paddles respectively.
There is also a GameManager to manage the scoreboard.
The Unity set up makes use of RigidBody2D and Colliders to control the Ball and Paddle interactions and to keep the ball within the bounds of the screen.
