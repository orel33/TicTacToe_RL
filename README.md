# TicTacToe_RL
This repository contains simple and unoptimised implementations of some Reinforcement Learning algorithms for the game of Tic Tac Toe.

* Min-max
* Monte Carlo (with epsilon-greedy strategies)
* Upper Confidence Bound (UCB)
* Temporal Difference (TD)

All training is done using self-play (playing against itself).
The State class is (heavily) inspired by Jeff Bradberry's own code (https://github.com/jbradberry).
Little effort should make this code compatible with Jeff's implementations of some other games.

Please find the Jupyer notebook [here](RL_TTT.ipynb)

Please find a description of the Monte Carlo algorithm on this [blog post](https://games-automata-play.github.io/blog/monte_carlo_tree_search/) of mine.
