# AI Pong Game using NEAT

This is an AI-powered Pong game implemented using the NEAT (NeuroEvolution of Augmenting Topologies) algorithm in Python. The AI is trained to play Pong by evolving neural networks.

## Features
- Play against an AI that learns through evolution.
- Train your own AI using NEAT.
- Simple and easy setup to get started.

## Installation
Make sure you have Python installed. Then, install the required dependencies:
```sh
pip install pygame neat-python
```

## How to Play
There are two ways to play the game:

### 1. Play with Pretrained AI
If you want to play directly against a pretrained AI, download `play.py` and `neat-checkpoint-45`, then run:
```sh
python play.py
```

### 2. Train Your Own AI and Then Play
If you want to train your own AI before playing, download `main.py` and run:
```sh
python main.py
```
This will train the AI using NEAT and then allow you to test it.

## Controls
- **W** - Move paddle up
- **S** - Move paddle down

The AI will control the other paddle.

## Repository Structure
- `play.py` - Plays the game using a pretrained AI from `neat-checkpoint-45`.
- `main.py` - Trains a new AI using NEAT and then allows you to play against it.
- `config.txt` - Configuration file for NEAT.