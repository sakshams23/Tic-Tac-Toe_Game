## Tic Tac Toe Game using Javascript

This is a simple Tic Tac Toe game built using JavaScript. It allows two players to take turns and play the classic game on a web browser.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Game Rules](#game-rules)
- [Contributing](#contributing)

## Installation

To run this Tic Tac Toe game on your local machine, follow these steps:

1. Clone this repository to your local machine using the following command:

   \`\`\`bash
   git clone (https://github.com/sakshams23/Tic-Tac-Toe_Game)
   \`\`\`

2. Navigate to the project directory.
   
3. Open the \`index.html\` file in your preferred web browser.

That's it! You're ready to play Tic Tac Toe.

## Usage

- Upon opening the \`index.html\` file, you will see a 3x3 grid representing the Tic Tac Toe board.
- Players take turns by clicking on empty cells to place their respective symbols (X or O).
- The game will automatically determine if a player has won or if it's a draw.
- After the game ends, you can restart it by clicking the "Restart" button.

## Game Rules

- The game is played on a 3x3 grid.
- Two players take turns, one playing as X and the other as O.
- The objective is to get three of your own symbols (X or O) in a row, column, or diagonal.
- The game ends when one player achieves the winning condition or when all cells are filled without a winner (a draw).

## Contributing

Contributions to improve this Tic Tac Toe game are welcome. If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your modifications and commit changes.
4. Push your changes to your forked repository.
5. Submit a pull request detailing your changes.

Please ensure that your code follows the existing code style and includes appropriate tests.

fs.writeFile('README.md', readmeContent, (err) => {
  if (err) {
    console.error(err);
  } else {
    console.log('README.md file has been created successfully.');
  }
});
