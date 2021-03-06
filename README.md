# Preliminaries
## Self-play
Self-play algorithms have agents trained against each other to avoid being exploitable. This technique works for competitative games, as both agents have competing objectives, and thus iteratively improve each others' strategies.
For cooperative games, SP will lead to agents that can only collaborate with their training partners. 

## Zero-shot coordination
Zero-shot coordination is the ability of an agent to cooperate with training partners unseen at training time.
It is different from ad-hoc teamplay, because in ZSC the training algorithm does not have access to an already trained population of agents.

## Dec-POMDP
A multi-agent partically observable markov decision process. 

## Other-play
An algorithm that uses symmetries in the dec-POMDP to avoid arbitrary symmetry breaking. 

# This repo
## Cooperative Communication
This game has three doors and behind one of them is a treasure. A sender agent can send a message, and the receiver can pick a door.
At the end of the round, the receiver will observe which door contained the treasure. And then, the game repeats.
