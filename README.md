# Self-Driving Car Simulation using NEAT and Pygame

An AI-based self-driving car simulation built with Python, Pygame, and NEAT (NeuroEvolution of Augmenting Topologies). The project demonstrates how a virtual car can learn to navigate a racing track autonomously by evolving neural networks over multiple generations.

## Overview

This project simulates a self-driving car that learns to drive around a track without human control. The car uses radar sensors to detect track boundaries and makes movement decisions using a neural network trained through the NEAT evolutionary algorithm.

The system showcases fundamental concepts of artificial intelligence, autonomous navigation, and evolutionary machine learning.

## Features

- Autonomous car movement in a custom track environment
- AI training using NEAT evolutionary algorithm
- Radar-based obstacle sensing
- Real-time collision detection
- Dynamic steering and speed control
- Fitness-based learning across generations
- Visualization of training process using Pygame

## Technologies Used

- Python
- Pygame
- NEAT-Python

## How It Works

### Car Sensors
The car uses multiple radar sensors placed at different angles to measure the distance between itself and track borders.

### Neural Network Input
The radar distances are passed as input to the neural network.

### AI Decision Making
The neural network predicts one of the following actions:

- Turn Left
- Turn Right
- Slow Down
- Speed Up

### Evolution Process
NEAT evolves the neural networks over generations by:

- Evaluating fitness based on distance traveled
- Eliminating weak performers
- Reproducing stronger networks
- Improving driving performance over time

