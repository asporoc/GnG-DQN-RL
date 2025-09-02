# Welcome to my Ghosts n' Ghouls Q- Learning Project

## The main purpose of this Goal was as a assignment for a Uni Coure in Big Data and Machine Learning
For the Assignment, you were supposed to solve a personal Problem or build something that you found interesting using AI or ML.

## My Choosen Project
As I had been Playing the NES classic Ghosts m' Ghouls on the Switch and found it to be very difficult i wanted to Try if I could Solve this "Problem" by letting a Reinforcement Agent (A concept I also find extremely interesting) play the game for me. In my Research if this was feasible and if this had already been done I could not find any Public Project which tackled this problem. I found inspiration in a Article (https://docs.pytorch.org/tutorials/intermediate/mario_rl_tutorial.html) About playing Super Mario Bros with a Double Q Network(DQN). I Decided to do something Similar:
Firstly I Tried to solve the Game with a DQN which was extremly similar to the Super Mario Bros one, which worked pretty well as the Agent got very good at surviving for long times as it was rewarded for beating enemies.
Secondly I implemented it again with a Single Q network which as expected did not work as well as the DQN but still showed some improvement over the same time. But as expected the Agent took much longer to show any improvement and failed to actually survive for longer Times.

## Conclusion
The Conclusion of my Project was that a Q-Network can certainly work but because of the slower convergence than that of a DQN it Takes a significant amount of time to actually show any improvement. There is probably room for improvement in the Code which would lead to a faster Convergence as this was my first attempt at Pytorch.
