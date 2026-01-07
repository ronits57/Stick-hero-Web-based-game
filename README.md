# Stick-hero-Web-based-game
Stick Hero is a simple browser-based game built using HTML, CSS, and JavaScript.
The game uses the HTML5 Canvas API to draw all game elements such as platforms, hero, sticks, background, hills, and trees.

The main goal of the game is to stretch a stick so that the hero can walk safely to the next platform.
If the stick is too short or too long, the hero falls and the game ends.

🛠️ Technologies Used

HTML5 – Structure of the web page

CSS3 – Styling and layout

JavaScript (Vanilla JS) – Game logic and animation

Canvas API – Drawing and rendering the game

No external libraries or frameworks are used.

📂 Project Structure
project-folder/
│
├── index.html    → Main HTML file
├── style.css     → All CSS styles
├── script.js     → Complete game logic
└── README.md     → Project documentation

▶️ How to Run the Game

Download or clone the project.

Open the project folder.

Double-click on index.html
OR
Right-click → Open with any modern browser (Chrome / Edge / Firefox).

The game will start automatically.

No server or installation is required.

🎮 How to Play

Mouse Hold (Click & Hold) → Stretch the stick

Mouse Release → Drop the stick

The hero walks automatically

Try to land the stick exactly on the platform

Hitting the red center area gives double score

Press SPACE or RESTART to restart the game

🧠 Game Logic (Simple Explanation)

The game runs using requestAnimationFrame

Game has different phases:

waiting

stretching

turning

walking

transitioning

falling

Each phase controls what happens on screen

Stick length, hero position, and collisions are calculated using JavaScript

Background moves slower to create a parallax effect

🖌️ Drawing & Rendering

Everything is drawn using Canvas

Background includes:

Sky gradient

Hills (using sine wave)

Trees

Hero, platforms, and sticks are drawn frame-by-frame

Canvas automatically resizes with the window

🔁 Restart & Score

Score increases when the hero reaches a platform

Perfect landing gives 2 points

Game resets using the Reset Game function

Restart button appears when the hero falls
