# Neural Pong World Model

A machine learning project that trains a neural network to recreate Pong by learning from gameplay rather than relying on traditional game physics.

## How It Works

- Created a simple Pong game using Python.
- Generated 200,000 gameplay frames for training.
- Trained a convolutional neural network (CNN) to predict the next frame using four previous frames and a player's input.
- Used the model's own predictions to generate gameplay.
- Compared the original game with the neural network's predictions.

## Results

- Training loss decreased by 72.7%.
- Validation loss decreased by 24.3%.
- The model accurately predicted 26 consecutive frames in the evaluated gameplay sequence.

The model successfully learned short-term game dynamics, although its predictions became less accurate over time as errors accumulated.

## Technologies

Python, PyTorch, NumPy, Matplotlib and Google Colab.

## How to Run

Open the notebook in Google Colab, enable GPU acceleration and run the cells in order.

## Inspiration

[DIAMOND World Model](https://github.com/eloialonso/diamond)
