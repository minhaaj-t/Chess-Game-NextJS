# Chess Game - Next.js

Welcome to the Chess Game built with **Next.js**! This project is a fully functional chess game where players can enjoy playing chess with a user-friendly interface. The game is built using modern web technologies, providing a smooth, real-time experience.

## Features

- **Interactive Chessboard**: A fully interactive chessboard with drag-and-drop functionality.
- **Game State**: Tracks the current game state, including moves, captures, and checkmate status.
- **Player vs Player**: Play against another person in real-time or in turns.
- **Undo Moves**: Option to undo the last move for both players.
- **Responsive Design**: Optimized for desktop and mobile use.
- **AI Mode**: Play against a simple AI (optional feature to be implemented).
  
## Technologies Used

- **Next.js**: React framework for server-side rendering and static site generation.
- **React**: For building the UI components.
- **Chess.js**: A library to handle game logic, rules, and chessboard state.
- **React-Beautiful-Dnd**: For drag-and-drop functionality to move the pieces.
- **Styled-components**: For styled-components to design the user interface.
- **Socket.io** (optional): For real-time multiplayer functionality (to be implemented).
  
## Installation

To get started with this project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/Chess-Game-NextJS.git
cd Chess-Game-NextJS
npm install
```

### Running the App

To run the app locally, use the following command:

```bash
npm run dev
```

This will start the Next.js development server at `http://localhost:3000`.

### Building the App

To create an optimized production build:

```bash
npm run build
```

To start the production server:

```bash
npm start
```

## Usage

- **Chessboard**: The game board displays chess pieces that you can move using drag-and-drop.
- **Moves**: Each player takes turns making moves.
- **Game Status**: The current status of the game (e.g., Check, Checkmate, Draw) is displayed.
  
## Contributing

Contributions to this project are welcome! If you would like to improve the game, please feel free to fork the repository, make your changes, and submit a pull request.

### Steps to Contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature-name`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature-name`)
5. Create a new Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **Chess.js** for providing the chess logic.
- **Next.js** for the amazing framework.
- **React** for building dynamic UI components.
- **React-Beautiful-Dnd** for drag-and-drop chessboard interactions.
