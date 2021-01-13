# Battlesnake-Game

Battlesnake is a multi-player game similar to the original game where players compete with each other.

![Alt Text](https://github.com/ArthurFirmino/gym-battlesnake/raw/master/render.gif)

## Features

  - Multi-threaded game implementation written in C++
  - Single agent training with multiple other agents as opponents
  - Render mode available to see your agents play

## Installation
### Dependencies
 -cmake
 -libopenmpi-dev
 -python3-dev
 -zlib1g-dev 
 -libsfml-dev

Tensorflow is also required for the functioning of BattleSnake Game.

```
## Recommendations
  - See OpenAI documentation on `gym` for more details about its interface
  - See `stable-baselines` documentation for more details on their PPO2 implementation and other suitable algorithms
  - For multi-agent training `tensorflow-gpu` is recommended, as well as a large number of environments (~100) to maximize data transfer to the GPU.

