# Flappy-Bird-using-NEAT-Summary

NEAT-Flappy-Bird is an AI-powered version of the classic Flappy Bird game where the bird learns to play on its own using NeuroEvolution of Augmenting Topologies (NEAT) — a genetic algorithm that evolves neural networks over generations.

🔍 Key Features:
AI Training with NEAT: The bird starts with random actions and gradually learns to avoid pipes by evolving its neural network.

No Manual Gameplay Needed: The model trains itself to play the game without human intervention.

Visual Feedback: Neural network evolution can be visualized to understand learning progression.

Game Graphics Included: Uses classic sprites for bird, pipes, background, and base.

🗂️ Core Components:
flappy_bird.py: Main script that runs the game and handles training.

config-feedforward.txt: Configures how the NEAT algorithm evolves.

visualize.py: Plots network topology and fitness evolution.

imgs/: Contains sprites used in the game UI.

🛠️ Technologies Used:
Python

Pygame (for game rendering)

NEAT-Python (for neuroevolution)
