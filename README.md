# AI Pong Game

This is an AI-powered Pong game implemented using the NEAT (NeuroEvolution of Augmenting Topologies) algorithm. The AI learns how to play Pong by evolving through generations.

## Features
- Play against an AI that learns through evolution.
- Train your own AI using NEAT.
- Simple and easy setup to get started.

## Installation

You have two options to install the required dependencies:

1. Install dependencies separately:
   ```sh
   pip install pygame neat-python
   ```

2. Install using the `requirements.txt` file:
   ```sh
   pip install -r requirements.txt
   ```

## How to Play

### 1. Play Against a Pre-Trained AI
To play the game directly against a pre-trained AI, download `play.py` and `neat-checkpoint-45` and run:
```sh
python play.py
```

### 2. Train the AI First, Then Play
If you want to train the AI yourself before playing, download `main.py` and run:
```sh
python main.py
```
This will train the AI over multiple generations. Once training is complete, the AI can be tested by playing against it.

## How It Works
- The AI uses NEAT to evolve and improve its gameplay over multiple generations.
- The `main.py` file first trains the AI and then allows you to play, while `play.py` allows you to play against a pre-trained AI.

## Controls
- **Player Paddle (Left Side):**
  - Move Up: `W`
  - Move Down: `S`
- **AI Paddle (Right Side):** Controlled by the AI.

## Repository Structure
- `play.py` - Play against a pre-trained AI.
- `main.py` - Train the AI from scratch.
- `config.txt` - Configuration file for NEAT.
- `requirements.txt` - Lists all required dependencies.
- `neat-checkpoint-45` - Pre-trained model checkpoint.

## Acknowledgments
This project was developed using the [NEAT-Python](https://neat-python.readthedocs.io/en/latest/) library.

Enjoy the game and experiment with AI training!