# Paper Explained: ViZDoom: A Doom-based AI Research Platform for Visual Reinforcement Learning

## Introduction

This paper has been out for several years, but given that I am working with VizDoom for my summer research project, it made sense to look at the paper that introduced VizDoom to the world. VizDoom is, at its core, a platform with which to interact with Doom. On it's own, Doom has no mechanism for allowing an agent to interact with it in ways that are needed; there is no easy mechanism for retrieving the screen buffer for example, or allowing actions taken by the agent to be used in the game. To that end, the four main features of ViZDoom are as follows. 

## Main Features

The four main features that ViZDoom offers are control modes, scenarios, and depth buffer access and off-screen rendering and frame skipping. The control modes are both synchronous and asynchronous, which allows for the engine to wait for the agent in synchronous mode and for multiplayer agents to play without blocking the other agents (or players). 

The ability to create scenarios allows for nearly limitless experimentation and also allows for the creation of different obstacles for agents to overcome. This allows for a better match between the difficulty of the environment and the capabilities of the agent in question. So, for instance, if you wanted to train an agent to pick up health packs, it would be easy to use any of the existing map editors to create an environment that features health packs. 

Utilizing the depth buffer in an agent can assist in understanding the visual information received through the screen buffer. Agents often underperform using just the screen buffer, so having more information about the environment can allow an agent to perform at a level higher than with just the screen alone.

Off-screen rendering improves performance by not having to draw the screen, which means that servers can be used which have no GUI. Frame skipping also improves performance, as most agents will not need to see every frame in order to make decisions.

## Experiments

The authors detailed a number of experiments done using the platform, done on a Core i7-4790k using a GeForce GTX 970. The basic experiment environment is detailed; a single chamber with a monster at the far end with 1 hp. The goal of the scenario is to kill the monster. The author's goal was to test how skipcounts (the number of frames skipped) affected an agent's performance. According to the results, skipcounts between 4 and 10 had the best balance between learning speed and performance. 

The second experiment is an experiment in medikit collection. The agent spawns in a pool of green acid, and is rewarded 100 and -100 for picking up a vial and a medikit, respectively. The neural network architecture used is similar to the skipcounts experiment, but the gamma, learning rate and mini-batch are different. The results are better than a random agent, but performs below what a human player could achieve. 

## Final Thoughts

ViZDoom is a really cool platform! One of my first real computer games I played was the original Doom, and the ability to build agents to play Doom now as an adult is very special to me, and I want to thank the ViZDoom team for creating such an amazing package. My next steps will to be implement the two experiments detailed here. Wish me luck!
