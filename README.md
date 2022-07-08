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

The straight forward function for the above can be seen in this code snippet from [reward_simple.py]():

[reward_funtion_L65.py]("./src/reward_funtion_L65.py") has the code for actual function I used for which the docs will be added as soon as possible.

## Other Useful Repositories to look at
1. [AWS DeepRacer League (https://aws.amazon.com/deepracer/league/)](https://aws.amazon.com/deepracer/league/)
2. [DeepRacer Logs Analysis tools (https://github.com/aws-deepracer-community/deepracer-analysis)](https://github.com/aws-deepracer-community/deepracer-analysis)
3. [AWS Deepracer Workshop Lab Github (https://github.com/aws-samples/aws-deepracer-workshops)](https://github.com/aws-samples/aws-deepracer-workshops)
4. [DeepRacer K1999 Racing Line Algo (https://github.com/cdthompson/deepracer-k1999-race-lines)](https://github.com/cdthompson/deepracer-k1999-race-lines)
5. [DeepRacer Utils CLI commands (https://github.com/aws-deepracer-community/deepracer-utils)](https://github.com/aws-deepracer-community/deepracer-utils)

## License
```
MIT License

Copyright (c) 2021 AWS DeepRacer Worksheet contributors community

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
