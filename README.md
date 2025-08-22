# Snake-Game-C
🐍 Snake Game in C

A simple terminal-based Snake Game built in C language, featuring real-time input handling, dynamic speed, and score tracking.

🎮 Features

Snake movement in all four directions (W, A, S, D)

Fruit spawning at random positions

Tail growth on eating fruit

Boundary wrapping (snake reappears from opposite edge)

Collision detection with snake’s own body (Game Over)

Dynamic speed adjustment based on score

Smooth terminal screen refresh for better gameplay

⚙️ Technologies Used

C Programming

termios for non-blocking keyboard input

select() system call for real-time input check

Unix/Linux terminal (works best on Linux/MacOS; Windows may need tweaks)

🚀 How to Run

Clone the repo

git clone https://github.com/<your-username>/snake-game-c.git
cd snake-game-c


Compile the code

gcc snake.c -o snake


Run the game

./snake

🎯 Controls

W → Move Up

S → Move Down

A → Move Left

D → Move Right

X → Exit Game
