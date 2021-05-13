# **General Explanation for RL Othello Model**

Artificial Intelligence has helped computers excel at board games since the 70's. Now, new approaches are helping these programs reach their final frontier in board games. This model is inspired by Google's AlphaZero program, which beat another program that beat the world's best player in an ancient Chinese board game called Go.

### The traditional approach

In the past, researchers have shown their programs real-life playthroughs to learn patterns of gameplay in games such as Go, Chess, and Othello. This model, however, plays against itself to develop its strategy. 

### Making a Move

While playing Othello, a player usually has a few choices as to where to place the stone in their turn. In any board game, the choice a made in a turn supports the player's strategic effort to win. So how does the program know which move to make when it looks at the board?

As mentioned before, the program learns how to play by playing against another version of itself. The program has two parts:

1. A Neural Network: this is a function that takes the board and provides suggestions on which move to take.

2. A Tree Search Function: Given the suggestions from the neural network, the tree search function explores the 'tree' of possiblilities following from carrying out the suggested moves.

If the tree search function predicts that a suggested move makes the player more likely to win, the neural network takes a reward which encourages it to provide similar suggestions in similar situations. If the suggested move makes the player less likely to win, the neural network is encouraged to provide different suggestions in the situation.

![reinforcement learning](https://hub.packtpub.com/wp-content/uploads/2019/12/reinforcement-learning-768x626.png)
