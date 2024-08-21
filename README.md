# Tic Tac Toe game with GNN

This project is an implementation of Tic Tac Toe game, enhanced with AI capabilities powered by a Graph Neural Network (GNN). The AI plays as 'O' and attempts to make optimal moves based on the game state.

## Features

- **Interactive UI:** Play Tic Tac Toe against the AI through an intuitive, grid-based interface.
- **Winner Detection:** The game automatically detects when a player wins or when the game ends in a draw.

- ## Installation

To run this project, you will need to have the following dependencies installed:

- Python 3.x
- Jupyter Notebook or Google Colab
- PyTorch
- PyTorch Geometric
- ipywidgets

You can install the required Python packages using the following commands:

```bash
pip install torch
pip install torch-geometric
pip install ipywidgets
```

## How to Run

1. **Open the Jupyter Notebook:**

   You can open the Jupyter Notebook or Google Colab file in the folder where the code is located.

2. **Load the Model:**

   Ensure that the pre-trained GNN model (`GNN.ipynb`) file is available in the same folder. If the model file is missing, the game will not load correctly.

3. **Run the Cells:**

   Execute all the cells in the notebook to start the game.

4. **Play the Game:**

   - The game UI will be displayed, and you can start playing by clicking on the grid.
   - The AI will automatically make moves after you.

## How the GNN Works

The GNN model is trained to evaluate the Tic Tac Toe board as a graph, where each cell is represented as a node. The model predicts the best possible move for the AI based on the current game state. It uses two layers of Graph Convolutional Networks (GCNs) followed by fully connected layers to output the optimal move.

## Project Structure

```plaintext
Tic-Tac-Toe-GNN/
│
├── GNN.ipynb                     # Pre-trained GNN model file
├── Tic tac initial result.csv    # Containing Data set
├──tic_tac_toe.py                 # Google Colab containing the game and model code
└── README.md                     # Project documentation
