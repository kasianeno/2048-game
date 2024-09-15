- [DEMO LINK](https://kasianeno.github.io/2048-game/)

<h1>Description</h1>

The 2048 game is a classic puzzle game that can be developed in JavaScript by leveraging core programming concepts like loops, functions, and the Document Object Model (DOM). 
The game is played on a 4x4 grid, which can be represented as a two-dimensional array in JavaScript. Each cell in this grid can either contain a number (a power of 2) or be empty (represented by 0).
To start the game, the grid needs to be initialized with two random tiles (either a 2 or a 4).
The game listens for keypress events (up, down, left, right arrow keys) to move the tiles on the grid. This can be handled using event listeners.
Each move operation (left, right, up, down) can be implemented as a function that manipulates the grid array. 
After every move, the grid needs to be updated on the webpage. This involves updating the HTML elements representing each tile.
The game should continuously check if the player has reached the 2048 tile or if there are no possible moves left.

The game runs in a loop triggered by user actions. Each time a key is pressed, the corresponding movement function is called, which updates the grid, adds a new tile, updates the DOM, and checks for win or game-over conditions.

By combining loops (for iterating over the grid), functions (for handling movement and game logic), and DOM manipulation (for updating the visual representation), the 2048 game can be effectively implemented in JavaScript.

This approach highlights how JavaScript's fundamental concepts can be used to create interactive and dynamic web-based games.

<h2>In this project, i used the following technologies:</h2>
<ol>
  <li>HTML5: Used to structure the layout of the web page and define the grid where the game takes place.</li>
  <li>CSS3: Used to set the size, colors, and animations for tiles. The game needs to be visually appealing, so animations for tile movements and merging are often added using CSS transitions.</li>
  <li>SASS: A CSS preprocessor that enhances my CSS with features like variables, nesting, mixins, and partials for better organization and reusability.</li>
  <li>JavaScript: The core technology used to implement the game logic and interactivity. It handles user input, tile movement, merging, scoring, and win/lose conditions.</li>
  <li>DOM Manipulation: Updates the visual elements of the game dynamically as the player interacts with it.</li>
  <li>Event Handling: Captures and responds to user inputs (arrow keys) to control tile movement.</li>
  <li>Math & Random Numbers: Randomly generates new tiles on the grid after each move.</li>
  <li>CSS Transitions: Adds smooth animations for moving and merging tiles.</li>
</ol>

<h2>How to run project locally:</h2>
<ol>
  <li>Clone repository using Git</li>
  <li>Open your terminal</li>
  <li>Install the standard package manager for Node.js using <b>npm i</b></li>
  <li>Type <b>npm start</b> to run project locally.</li>
</ol>
