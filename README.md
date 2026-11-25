
# Neural Pong World Model

A deep learning project that recreates the dynamics of Pong
using a convolutional neural network (CNN).

Instead of relying on a traditional physics engine during
inference, the model learns to predict future game frames
from previous frames and player actions.

## Project Objectives

- Generate 200,000 simulated Pong gameplay frames.
- Develop an action-conditioned convolutional neural network.
- Predict future frames from four consecutive frames.
- Generate gameplay through autoregressive predictions.
- Compare simulated and neural gameplay accuracy.
- Investigate compounding prediction errors.

## Technologies

- Python
- PyTorch
- NumPy
- Matplotlib
- Google Colab
- CUDA

## Model Architecture

Input: 4 grayscale frames + 3 action channels
(7 x 40 x 40)

Output: Predicted next frame (1 x 40 x 40)

## Evaluation

- Training and validation loss
- Intersection over Union (IoU)
- Long-term prediction stability
- Side-by-side gameplay comparison

## Project Status


## Project Status

Completed — Version 1.0

- Implemented a custom Pong simulation.
- Trained an action-conditioned convolutional neural network.
- Implemented autoregressive gameplay generation without
  relying on a traditional physics engine during inference.
- Developed interactive player controls.
- Evaluated model performance using training loss,
  validation loss, and Intersection over Union (IoU).
- Created side-by-side comparisons of real and
  neural network-generated gameplay.
