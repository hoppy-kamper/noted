# Game Playing

* Adversarial Search
* Minimax Algorithm
* Alpha-Beta Pruning
* Evaluation Functions
* Isolation Game Player
* Multi-Player, Probabilistic Games

### Building a Game Tree

* Opening Book Table
  * A way to signify the best opening move
* Triangles
  * up - computer player is trying to maximize the score
  * down - computer player minimize the score
* __Minimax Algorithm__ - process of computer values for the tree from bottom to top
* Quiescent search might provide better results, but requires more nodes to calculate. It should be used "when the time is right"
* Iterative Deepening
  * Doesn't waste much time
  * Because the exponential nature of the problem, time is dominated by the last level search.