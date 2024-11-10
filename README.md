# AI-mini_project
Pong Game with Fuzzy Logic AI
Welcome to the Pong Game — a modern take on the classic Pong game, built using Python and Pygame. This version includes an AI opponent that employs fuzzy logic to enhance gameplay by dynamically adjusting its paddle movement based on the ball's distance.
Table of Contents
•	Features
•	Technologies Used
•	Game Setup
o	Prerequisites
o	Installation
o	Running the Game
•	Game Controls
•	Game Mechanics
o	Player
o	AI Opponent (Fuzzy Logic)
o	Difficulty Levels
o	Winning the Game
•	Customization
•	Contribution Guidelines
•	License
Features
•	Fuzzy Logic AI Opponent: The AI paddle dynamically adjusts its speed using fuzzy logic based on the ball's distance from the paddle.
•	Three Difficulty Levels: Select from Easy, Medium, or Hard modes to suit your skill level.
•	Custom Game Parameters: Set your own maximum score to win the game and personalize the experience by entering your username.
•	Smooth Graphics and Real-Time Gameplay: Enjoy fluid motion, real-time collision detection, and fast-paced action.
•	Player Stats Display: Your username is displayed on-screen, and scores are tracked for both players.
Technologies Used
•	Python 3.x: The programming language used to build the game.
•	Pygame: The game engine responsible for rendering graphics, handling input, and managing game logic.
Game Setup
Prerequisites
To run this game, you'll need to have Python installed on your machine. You can download Python from here.
You'll also need the Pygame library. Install it using the following command:
bash
Copy code
pip install pygame
Installation
1.	Clone the repository:
bash
Copy code
git clone https://github.com/your-username/pong-game-fuzzy-ai.git
cd pong-game-fuzzy-ai
2.	Run the game script:
bash
Copy code
python pong_game.py
Running the Game
After launching the game, follow the on-screen prompts to:
1.	Enter your username.
2.	Choose a difficulty level: Easy, Medium, or Hard.
3.	Set the maximum points required to win the game.
Once you’ve set up the game, type START to begin the match!
Game Controls
•	Up Arrow: Move your paddle up
•	Down Arrow: Move your paddle down
Use these controls to compete against the AI and score points by getting the ball past the opponent's paddle.
Game Mechanics
Player
You control the right paddle using the arrow keys. Your goal is to prevent the ball from passing your paddle and to score points by hitting the ball past the opponent's paddle.
AI Opponent (Fuzzy Logic)
The AI opponent on the left uses fuzzy logic to adjust its movement:
•	Close Distance: If the ball is near the paddle, the AI moves faster to respond.
•	Medium Distance: The AI moves at a normal speed.
•	Far Distance: The AI moves slower, creating opportunities for skilled players.
The AI constantly monitors the distance between the ball and its paddle to dynamically adjust its speed, making for a more challenging opponent.
Difficulty Levels
The game offers three difficulty levels:
•	Easy: Slower AI reaction times and a larger margin of error for the player.
•	Medium: Balanced difficulty with moderate AI response times.
•	Hard: Fast AI reactions that require quick reflexes and strategy.
Winning the Game
The first player to reach the set number of points wins the game. The default maximum points can be customized during setup.
Customization
Change Paddle and Ball Settings
If you'd like to modify the paddle or ball settings, you can tweak the following variables in the code:
python
Copy code
PADDLE_WIDTH, PADDLE_HEIGHT = 10, 100
PADDLE_SPEED = 5
BALL_SIZE = 15
You can also customize the window size by adjusting the WIDTH and HEIGHT variables:
python
Copy code
WIDTH, HEIGHT = 800, 600
