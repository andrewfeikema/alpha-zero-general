# Alpha Zero General Implementation for Othello: Mastering Othello Without Human Knowledge

For final project in Calvin CS 344 with Prof. Kenneth Arnold

* [Training Notebook](https://github.com/andrewfeikema/alpha-zero-general/blob/master/Othello_Train_Trial_using_AlphaZero_General.ipynb)
* [Technical Report](https://github.com/andrewfeikema/alpha-zero-general/blob/master/Technical_Report_Mastering_Othello_Without_Human_Knowledge.ipynb)
* [Ethical Discussion](https://github.com/andrewfeikema/alpha-zero-general/blob/master/Ethical%20Discussion.md)
* [General Explanation](https://github.com/andrewfeikema/alpha-zero-general/blob/master/General%20Explanation.md)

```Coach.py``` contains the core training loop and ```MCTS.py``` performs the Monte Carlo Tree Search. The parameters for the self-play can be specified in ```main.py```. Additional neural network parameters are in ```othello/{pytorch,keras,tensorflow,chainer}/NNet.py``` (cuda flag, batch size, epochs, learning rate etc.). 

### Contributors and Credits

Forked from [suragnair/alpha-zero-general](https://github.com/suragnair/alpha-zero-general).
