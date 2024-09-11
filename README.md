[DEMO LINK](https://kasianeno.github.io/2048-game/)

<h1>Descriptioon</h1>

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
