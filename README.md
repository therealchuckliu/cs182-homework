
# CS 182: Artificial Intelligence
# Assignment 2: Adverserial Search
* Fall 2015
* Due: October 2, 5pm


![Ghost](http://vignette2.wikia.nocookie.net/pacman/images/c/c3/Pac-man_ghosts_blinky_inky.jpg/revision/latest?cb=20110314180633)




In this assignment, you will implement search algorithms to help Pacman find paths in a maze. 
Note: We will use the Pacman framework developed at Berkeley. This framework is used world-wide to teach AI, therefore it is very important that you DO NOT publish your solutions online.

## Computational Assignment:

Follow the instructions at: 

http://ai.berkeley.edu/multiagent.html

The page includes questions requiring implementation of some of the search algorithms we studied in class. Make sure to download the pacman project zip file from the above link. Do not use Assignment 1’s zip file because there are some small changes. You can, however, use your search.py and searchAgents.py files if they are helpful.
[The grading scheme described on the Berkeley webpage will not be used, but you can use it to evaluate your agent’s performance.]

We recommend cloning the assignment by running: 

> git clone https://github.com/CS182/HW2.git


Submit your project to the course dropbox folder. 

### Notes

1. Alpha-beta is an extension of MiniMax. Therefore, if you divide the work you probably don’t want to assign Minimax to one student and alpha-beta to the other. Implementing alpha-beta without first implementing Minimax will be very challenging.

2. The assignment uses the term "depth" to mean one pacman move *and* all the ghosts move (also known as a "ply"). This differs from the notes, so be sure to take this into account when implementing. 


## Written Assignment

Answer the following questions individually, and submit as pdf to the dropbox folder. 

### Question 1: 

Compare the performance of your pacman alpha-beta agent when it plays against the directional ghost, the random ghost and a mini-max ghost. Analyze and discuss your results.

### Question 2: 

If you were to design a ghost agent to play with people, how would you go about choosing a strategy for the ghost? Think about the strategies people might use when playing this game, and how they might differ from strategies played by computer agents.

### Question 3: 

Given the Minimax tree below, answer the following questions:

<img src="HW2_tree.png" alt="Drawing" style="width: 500px;"/>

1. Assume alpha-beta runs depth-first from left to right. For which values of A and B, will the algorithm prune nodes C and D?

2. Did alpha-beta have to expand the node with value 6? Explain.
