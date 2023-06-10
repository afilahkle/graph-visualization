# D3.js Chess Game Graph Visualizer

This project uses D3.js, jQuery, Chess.js and Chessboard.js to visualize a hierarchy of chess games and moves. The nodes represent different chess game states and the edges represent the transition from one game state to the next.

## Project Setup

To use this project, clone the repository and open the HTML file in your browser.

git clone https://github.com/afilahkle/graph-visualization.git
cd d3js-chess-game-graph
open index.html with any server you like, i'm using the live server extension in vscode.

## Features

* **Visualization of game state transitions**: The tree-like graph displays the different game states and the transitions between them.
* **Interactive nodes**: Hovering over a node displays the chess board's state at that particular moment.

## Dependencies

* [D3.js](https://d3js.org) is used for creating the graph and adding interactive features.
* [jQuery](https://jquery.com/) is used for handling events and modifying HTML.
* [Chess.js](https://github.com/jhlywa/chess.js) is used for chess move generation/validation, check/checkmate/stalemate detection, and FEN/PNG support.
* [Chessboard.js](http://chessboardjs.com/) is used for the chess board.

**Note**: if you have a .graphml file you'll need to convert it to .json format. see [link](https://github.com/afilahkle/graphml-visualization-and-convertor) for more information.
