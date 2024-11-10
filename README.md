Pong Game with Fuzzy Logic Opponent AI:
This project is a Python-based Pong game built using Pygame. It features a classic 2D paddle-and-ball game with an opponent AI that uses fuzzy logic for responsive paddle movement. You can personalize the gameplay experience with username selection, difficulty level, and a custom winning score.

Features:
Single-player Pong Game: Control your paddle using arrow keys to prevent the ball from passing.
Fuzzy Logic Opponent: The opponent paddle's speed adjusts based on the ball's proximity, creating a more realistic and challenging experience.
Difficulty Levels: Choose between Easy, Medium, and Hard, which impact the ball's speed.
Custom Winning Score: Set the maximum points needed to win the game.
User Prompt to Start: Begin the game by typing "START."
Win/Loss Display: A message displays when a player or the opponent wins.

Installation:
Requirements:
Python 3.x
Pygame

Setup:
Install Pygame:
pip install pygame
Run the game:
python pong.py

How to Play:
Run the game and enter your username when prompted.
Choose a difficulty level (Easy, Medium, or Hard).
Set the maximum points needed to win.
Type "START" to begin the game.
Use the Up Arrow and Down Arrow keys to control your paddle.
Keep the ball from reaching your side while trying to get it past your opponent.

Fuzzy Logic Explanation:
The opponent AI uses fuzzy logic for adaptive paddle movement:
Fuzzy Distance: Calculates the distance between the ball and the opponent paddle, classifying it as "close," "medium," or "far."
Fuzzy Speed Adjustment: The opponent paddle’s speed increases when the ball is close, decreases when the ball is far, and remains constant at a medium distance.
This fuzzy logic creates a more dynamic opponent that reacts to the ball’s position.
