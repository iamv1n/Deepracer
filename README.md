<h1 align = center>AWS Deepracer Student League</h1>
<p align = center>
  <img src="https://miro.medium.com/max/1400/1*vYUuQ7LJlWAaiAYShMKmPw.png">
</p>
<p align = center>
  <img src="https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/-AWS-232F3E?logo=amazon-aws&logoColor=white"/>
  <img src="https://img.shields.io/badge/-VS%20code-blue??style=flat&logo=visualstudiocode"/>
  <img src="https://img.shields.io/badge/-Sublime%20Text-DB6204?logo=sublime-text&logoColor=white"/>
  <img src="https://img.shields.io/badge/-Atom-239120?logo=atom&logoColor=white"/>
  <img src="https://img.shields.io/badge/-Git-D51007?logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/-GitHub-181717?logo=github&logoColor=white"/>
</p>

This README provides an overview of how I approached the AWS DeepRacer Student League Competition in the last 3 years. Over the course of the model's development it was necessary to define an action space, develop a reward function for reinforcement learning, and experiment with various hyperparameters controlling the underlying 3-layer neural network.

### Contents
- [About](#About)
- [Results](#Results)
- [Development](#Development)
  - [Pre-Season Model](#Pre-Season_Model)
- [Conclusion](#Conclusion)
- [Acknowledgments](#Acknowledgments)

## Development
### Pre-Season Model
#### Defining the action space
The Pre-Season track is the 2021 DeepRacer Championship Cup track named Vivalas Loop, which is a relatively straightforward loop with minor turns.

#### Developing the reward function
Initially, I trained the model with much simpler parameters on the Vivalas track using a centreline-following reward function with an incentive for faster speeds while travelling straight.

The sub-rewards can be seen in this code snippet from [reward_simple.py]():
