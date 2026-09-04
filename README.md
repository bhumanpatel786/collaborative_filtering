# Collaborative Filtering Game Recommender

## Overview
A custom-built collaborative filtering recommendation engine created entirely from scratch using Matrix Factorization and Gradient Descent. Rather than relying on high-level machine learning libraries, this project implements the underlying mathematical algorithms to predict user ratings for games like Phasmophobia, Pacify, Escape the Backrooms, and Monument Valley.

## Key Features
* **Matrix Factorization:** Decomposed the user-item interaction matrix to extract latent features for both users and games.
* **Custom Gradient Descent:** Implemented a custom cost function and gradient descent loop to iteratively minimize prediction error over 1000 epochs.
* **L2 Regularization:** Integrated a lambda penalty to prevent the model weights from overfitting on a sparse dataset.
* **Rating Predictions:** Generates personalized "out of 5" rating predictions for unplayed titles based on historical user similarity.

## Tech Stack
* **Language:** Python
* **Mathematics & Matrices:** NumPy

## Author
**Bhuman Patel**  
B.Tech Student at IIIT Vadodara
