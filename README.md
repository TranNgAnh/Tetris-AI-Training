# COGS188 Adversarial AI Training with Multiplayer Tetris

## Abstract 

Multiplayer Tetris is an adversarial task with complex interactions inside individual game states in addition to complex interactions between the game states of the agents. Tetris is particularly complex because of its potentially infinite nature and because of strict rulesets that reward certain types of performance. Examples of this include T-Spins and doing a “Tetris” (four line clear). Our goal is to implement various reinforcement learning algorithms in order to train a model capable of not only playing Tetris, but also being able to play it in a competitive environment. Our first metric of performance will be survival duration and score (with predefined rules on how a score will be generated from clearing lines in the game). Then, our metric for adversarial tasks will include winning as well as comparisons such as score differential. 

## Getting Started

This project was ran both on Datahub (UCSD) and locally. To install and run this project locally, please install the required dependencies.

```
pip install -r requirements.txt
```

## Acknowledgement

This project is a cumilation of our team's work which comprised of Kendrick Nguyen, Eric Song, and myself, Anh Tran. We use different level training algorithms to training the Tetris programming to test how the AI would perform. We utilized Q-learning, double Q-learning, DQN, NEAT and yield minimal results which can be found at [FinalProject.ipynb](FinalProject.ipynb).

